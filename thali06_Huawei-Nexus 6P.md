#### Test 89975734f660a83_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of system
11-25 07:23:44.582   930  3384 I ActivityManager: Killing 5210:org.codeaurora.ims/1001 (adj 15): empty #17
,--------- beginning of main
11-25 07:23:44.757  5513  5565 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-25 07:23:44.805  5513  5565 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-25 07:23:44.833  5513  5565 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-25 07:23:44.838  4035  4925 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-25 07:23:44.907  4035  4925 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-25 07:23:44.948  5567  5567 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-25 07:23:44.951  5567  5567 D AndroidRuntime: CheckJNI is OFF
11-25 07:23:44.974  5567  5567 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-25 07:23:45.017  5567  5567 I Radio-JNI: register_android_hardware_Radio DONE
11-25 07:23:45.032  5567  5567 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-25 07:23:45.042   930  3764 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-25 07:23:45.086   930  3764 I ActivityManager: Start proc 5580:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-25 07:23:45.092  5567  5567 D AndroidRuntime: Shutting down VM
,11-25 07:23:45.430   930  3383 I WindowManager: Screenshot max retries 4 of Token{9067cbb ActivityRecord{da9854a u0 com.test.thalitest/.MainActivity t10}} appWin=Window{1f573a2 u0 Starting com.test.thalitest} drawState=2
,11-25 07:23:45.516  5580  5580 I CordovaLog: Changing log level to DEBUG(3)
,11-25 07:23:45.516  5580  5580 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-25 07:23:45.516  5580  5580 D CordovaActivity: CordovaActivity.onCreate()
,11-25 07:23:45.523  5580  5580 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-25 07:23:45.552  5580  5580 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-25 07:23:45.610  5580  5580 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 574-628)
,11-25 07:23:45.610  5580  5580 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-25 07:23:45.646  5580  5580 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eeb412b}
11-25 07:23:45.647  5580  5580 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-25 07:23:45.647  5580  5580 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-25 07:23:45.651  5580  5580 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-25 07:23:45.652  5580  5580 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-25 07:23:45.699  5580  5580 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-25 07:23:45.707  5580  5580 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-25 07:23:45.707  5580  5580 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-25 07:23:45.707  5580  5580 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-25 07:23:45.707  5580  5580 I Adreno  : Build Date                       : 12/06/15
11-25 07:23:45.707  5580  5580 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-25 07:23:45.707  5580  5580 I Adreno  : Local Branch                     : mybranch17112971
11-25 07:23:45.707  5580  5580 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-25 07:23:45.707  5580  5580 I Adreno  : Remote Branch                    : NONE
11-25 07:23:45.707  5580  5580 I Adreno  : Reconstruct Branch               : NOTHING
,11-25 07:23:45.753   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@89c46c6:true
,11-25 07:23:45.775  4196  4196 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25186]" dev="sockfs" ino=25186 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:23:45.778  4196  4196 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25186]" dev="sockfs" ino=25186 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:23:45.790  5580  5580 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-25 07:23:45.797  5580  5580 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-25 07:23:45.801  5580  5580 D PluginManager: init()
,11-25 07:23:45.803  5580  5580 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-25 07:23:45.824  5580  5580 D CordovaActivity: Started the activity.
,11-25 07:23:45.824  5580  5580 D CordovaActivity: Resumed the activity.
,11-25 07:23:45.821  4196  4196 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33890]" dev="sockfs" ino=33890 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:23:45.827  5580  5617 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-25 07:23:45.821  4196  4196 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33890]" dev="sockfs" ino=33890 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-25 07:23:45.825  3782  3782 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[25195]" dev="sockfs" ino=25195 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-25 07:23:45.825  3782  3782 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[25195]" dev="sockfs" ino=25195 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-25 07:23:45.831  5580  5580 D CordovaActivity: Paused the activity.
,11-25 07:23:45.833  5580  5604 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-25 07:23:45.866  5580  5617 I OpenGLRenderer: Initialized EGL, version 1.4
,11-25 07:23:45.879  5580  5580 D CordovaActivity: Stopped the activity.
,11-25 07:23:45.956   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +521ms (total +895ms)
,11-25 07:23:45.967  5580  5580 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-25 07:23:45.985  5580  5580 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5580
,11-25 07:23:46.091  5580  5580 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-25 07:23:46.135   930  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 07:23:46.402  5580  5619 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -561514192
,11-25 07:23:46.421  5580  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-25 07:23:46.421  5580  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-25 07:23:46.421  5580  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-25 07:23:46.421  5580  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-25 07:23:46.421  5580  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-25 07:23:46.422  5580  5619 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7cce60 added. We now have 1 listener(s)
,11-25 07:23:46.430  5580  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-25 07:23:46.431  5580  5619 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:23:46.432  5580  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-25 07:23:46.432  5580  5619 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-25 07:23:46.438  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-25 07:23:46.439  5580  5619 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb091bf added. We now have 1 listener(s)
11-25 07:23:46.439  5580  5619 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,11-25 07:23:46.443   930  2942 D WifiService: New client listening to asynchronous messages
,11-25 07:23:46.444  5580  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:23:46.444  5580  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-25 07:23:46.445  5580  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
11-25 07:23:46.445  5580  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-25 07:23:46.445  5580  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-25 07:23:46.445  5580  5619 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-25 07:23:46.445  5580  5619 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 51
,11-25 07:23:46.447  5580  5619 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-25 07:23:46.464  5580  5580 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-25 07:23:46.475  5580  5580 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-25 07:23:46.475  5580  5580 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-25 07:23:47.103  5580  5626 W jxcore-log: Initializing JXcore engine
,11-25 07:23:47.103  5580  5626 W jxcore-log: JXcore engine is ready
11-25 07:23:47.125  5626  5626 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-25 07:23:47.125  5626  5626 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13542]" dev="sockfs" ino=13542 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-25 07:23:47.125  5626  5626 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-25 07:23:47.125  5626  5626 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33857]" dev="sockfs" ino=33857 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-25 07:23:47.136  5580  5626 W jxcore-log: Starting JXcore engine
,11-25 07:23:47.186  5580  5626 W jxcore-log: Platform android
11-25 07:23:47.186  5580  5626 W jxcore-log: 
,11-25 07:23:47.186  5580  5626 W jxcore-log: Process ARCH arm
11-25 07:23:47.186  5580  5626 W jxcore-log: 
,11-25 07:23:47.372  5580  5626 I jxcore-log: JXcore Cordova bridge is ready!
11-25 07:23:47.372  5580  5626 I jxcore-log: 
,11-25 07:23:47.373  5580  5626 W jxcore-log: JXcore engine is started
,11-25 07:23:47.384  5580  5619 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-25 07:23:47.390  5580  5580 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-25 07:23:47.390  5580  5580 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-25 07:23:49.193  3550  3550 I ConfigService: onDestroy
,11-25 07:23:49.479   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:23:50.480   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:23:51.481   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:23:52.483   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:23:53.484   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:23:54.485   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-25 07:23:57.054  5580  5626 I jxcore-log: 2016-11-25 12:23:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-25 07:23:57.054  5580  5626 I jxcore-log: 
,11-25 07:23:57.056  5580  5626 I jxcore-log: 2016-11-25 12:23:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-25 07:23:57.056  5580  5626 I jxcore-log: 
,11-25 07:23:57.062  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:23:57.062  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:23:57.063  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 07:23:57.066  5580  5626 I jxcore-log: 2016-11-25 12:23:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-25 07:23:57.066  5580  5626 I jxcore-log: 
,11-25 07:23:57.067  5580  5626 I jxcore-log: 2016-11-25 12:23:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-25 07:23:57.067  5580  5626 I jxcore-log: 
,11-25 07:23:57.312  5580  5626 I jxcore-log: 2016-11-25 12:23:57 - DEBUG UnitTest_app: 'Running unit tests'
11-25 07:23:57.312  5580  5626 I jxcore-log: 
,11-25 07:23:57.312  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:23:57.312  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c698628 added. We now have 2 listener(s)
,11-25 07:23:57.313  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:23:57.313  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:23:57.313  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:23:57.313  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:23:57.313  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abe7f41 added. We now have 2 listener(s)
11-25 07:23:57.314  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:23:57.314  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:23:57.315  5580  5626 D executeNativeTests: Running unit tests
,11-25 07:23:57.360  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 07:23:57.360  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 added. We now have 3 listener(s)
11-25 07:23:57.360  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:23:57.361  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:23:57.361  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:23:57.361  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:23:57.361  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 added. We now have 3 listener(s)
11-25 07:23:57.361  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:23:57.362  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:23:57.364  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-25 07:23:57.364  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:23:57.364  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:23:57.364  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:23:57.365  5580  5626 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-25 07:23:57.365  5580  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-25 07:23:57.365  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 07:23:57.365  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:23:57.365  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:23:57.365  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:23:57.366  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:23:57.366  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:23:57.366  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:23:57.366  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:23:57.366  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:23:57.367  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:23:57.367  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 removed from the list
11-25 07:23:57.367  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:23:57.367  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 removed from the list
11-25 07:23:57.367  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:23:57.367  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.367  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.368  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.368  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:23:57.368  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.368  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:23:57.368  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:23:57.368  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:23:57.368  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:23:57.369  5580  5626 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-25 07:23:57.370  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:23:57.370  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:23:57.370  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:23:57.370  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:23:57.370  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:23:57.370  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:23:57.370  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:23:57.370  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:23:57.370  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:23:57.370  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.370  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.371  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.371  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.371  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.371  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:23:57.371  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:23:57.371  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:23:57.371  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 07:23:57.374  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 07:23:57.375  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:23:57.375  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:23:57.375  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:23:57.375  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:23:57.375  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:23:57.375  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:23:57.375  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:23:57.375  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:23:57.375  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:23:57.375  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.375  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.376  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.376  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.376  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.376  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:23:57.376  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:23:57.376  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:23:57.376  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:23:57.376  5580  5626 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 07:23:57.378  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:23:57.378  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:23:57.384  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:23:57.385  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:23:57.385  5580  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:23:57.386  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:23:57.386  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:23:57.387  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:23:57.387  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:23:57.387  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 07:23:57.388  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:23:57.389  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:23:57.389  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 07:23:57.391  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.391  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 07:23:57.392  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:23:57.392  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:23:57.392  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 07:23:57.394  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:23:57.395  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-25 07:23:57.395  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:23:57.397  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-25 07:23:57.397  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.397  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:23:57.397  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-25 07:23:57.397  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:23:57.397  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:23:57.397  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.398  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:23:57.400  4581  4594 D BtGatt.GattService: registerClient() - UUID=3fc2cf9f-9dcb-4824-8c6f-db7e56e3537c
,11-25 07:23:57.401  4581  4643 D BtGatt.GattService: onClientRegistered() - UUID=3fc2cf9f-9dcb-4824-8c6f-db7e56e3537c, clientIf=5
,11-25 07:23:57.402  5580  5591 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 07:23:57.403  4581  4827 D BtGatt.GattService: start scan with filters
,11-25 07:23:57.408  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:23:57.408  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.408  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:23:57.408  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:23:57.408  4581  4646 D BtGatt.ScanManager: handling starting scan
11-25 07:23:57.408  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:23:57.408  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:23:57.409  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.409  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:23:57.409  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.409  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-25 07:23:57.409  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 07:23:57.409  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.409  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.410  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:23:57.410  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.411  4581  4646 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:23:57.411  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:23:57.412  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:23:57.412  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:23:57.412  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.412  5580  5626 I io.jxcore.node.ConnectionHelper: start: OK
,11-25 07:23:57.416  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.416  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:23:57.416  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:23:57.416  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:23:57.416  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:23:57.421  4581  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:23:57.421  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:23:57.422  4581  4646 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 07:23:57.429  4581  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:23:57.429  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:23:57.429  4581  4646 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:23:57.429  4581  4646 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 07:23:57.440  4581  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 07:23:57.441  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:23:57.447  4581  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 07:23:57.447  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:23:57.918  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 07:23:57.918  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:23:57.918  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 07:24:00.230   930   930 I ActivityManager: Killing 5223:com.android.settings/1000 (adj 15): empty #17
,11-25 07:24:02.418  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:02.419  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:24:02.419  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 07:24:02.419  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:24:02.419  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-25 07:24:02.419  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:24:02.420  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:24:02.420  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:24:02.420  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.420  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 07:24:02.420  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:24:02.422  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:02.422  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.422  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.422  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-25 07:24:02.422  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.423  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:24:02.424  4581  4594 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:24:02.424  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 07:24:02.426  4581  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:24:02.427  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:24:02.429  4581  4807 D BtGatt.GattService: stopScan() - queue size =1
,11-25 07:24:02.431  4581  4593 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:24:02.432  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:24:02.433  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.433  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:24:02.433  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.433  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.433  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.434  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.434  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:24:02.436  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.436  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.436  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.436  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:24:02.436  4581  4581 D BtGatt.ScanManager: awakened up at time 97455
11-25 07:24:02.437  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:24:02.442  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:24:02.442  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:02.444  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:02.444  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 07:24:02.444  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.444  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:02.444  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:24:02.444  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:24:02.444  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:02.445  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:24:02.445  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:24:02.445  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:24:02.445  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:24:02.445  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:02.445  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:24:02.445  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:02.445  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:02.445  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:24:02.445  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 07:24:02.445  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:02.445  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:02.445  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:24:02.445  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:24:02.445  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:24:02.445  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:24:02.446  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-25 07:24:02.446  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:24:02.448  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:24:02.449  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:24:02.449  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:24:02.471  4581  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-25 07:24:02.472  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:02.472  4581  4643 D BtGatt.GattService: current time is 97490728849
11-25 07:24:02.472  4581  4643 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -66, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -68, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -68, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -71, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -24, -5, 124, 62, -54, -40, 1, 0, -94, 78, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 90, 65, 97, 3, 0, -25, 27, -109, 112, -47, -110, 28, 6, 8, 116, 105, 110, 53, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -75, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -72, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 07:24:02.473  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 07:24:02.474  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 07:24:02.474  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 07:24:02.474  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-25 07:24:02.474  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 90, 65, 97, 3, 0, -25, 27, -109, 112, -47, -110, 6, 8, 116, 105, 110, 53, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-25 07:24:02.475  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 07:24:02.47,5  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 07:24:02.480  4581  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 07:24:02.480  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:02.480  4581  4646 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:24:02.486  4581  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 07:24:02.486  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:02.486  4581  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:24:02.491  4581  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:24:02.491  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:24:02.540  4815  4849 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-25 07:24:02.542  4815  4815 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-25 07:24:02.947  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:24:07.450  5580  5626 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-25 07:24:07.456  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 07:24:07.456  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:24:07.469  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 07:24:07.473  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:24:07.474  5580  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-25 07:24:07.474  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:24:07.474  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:24:07.474  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:24:07.474  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:24:07.474  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 07:24:07.479  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:07.480  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 07:24:07.480  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:24:07.481  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 07:24:07.483  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:07.488  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.488  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:24:07.489  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 07:24:07.490  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:24:07.490  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:24:07.496  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.496  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:24:07.496  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:24:07.496  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:24:07.496  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:24:07.496  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.497  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:24:07.501  4581  4807 D BtGatt.GattService: registerClient() - UUID=d80619ee-6302-488e-88e6-1081593938d2
11-25 07:24:07.501  4581  4643 D BtGatt.GattService: onClientRegistered() - UUID=d80619ee-6302-488e-88e6-1081593938d2, clientIf=5
,11-25 07:24:07.502  5580  5591 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 07:24:07.503  4581  4593 D BtGatt.GattService: start scan with filters
,11-25 07:24:07.507  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 07:24:07.507  4581  4646 D BtGatt.ScanManager: handling starting scan
11-25 07:24:07.507  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.508  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:24:07.508  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.508  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:24:07.508  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:24:07.509  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.509  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:24:07.509  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:24:07.509  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 07:24:07.509  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.509  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.509  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.510  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:24:07.510  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.514  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.515  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:24:07.515  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.515  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.515  5580  5626 I io.jxcore.node.ConnectionHelper: start: OK
11-25 07:24:07.515  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.516  4581  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:24:07.517  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.517  4581  4646 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 07:24:07.520  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.520  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.520  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:24:07.521  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:24:07.521  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:07.521  5580  5626 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 07:24:07.522  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:07.522  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 07:24:07.522  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:07.522  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 07:24:07.522  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.522  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.523  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.523  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:24:07.523  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.524  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:24:07.524  4581  4594 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 07:24:07.524  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:24:07.525  4581  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:24:07.525  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.525  4581  4646 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:24:07.525  4581  4646 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:24:07.525  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:24:07.526  4581  4593 D BtGatt.GattService: stopScan() - queue size =1
,11-25 07:24:07.527  4581  4807 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:24:07.527  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:24:07.527  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.527  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.528  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:24:07.528  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-25 07:24:07.529  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:24:07.530  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.531  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.531  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 07:24:07.531  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.532  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.532  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:07.532  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:24:07.532  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:24:07.532  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:24:07.532  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:24:07.532  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:07.532  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:07.532  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:24:07.532  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:07.532  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.532  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:07.532  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:07.532  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-25 07:24:07.532  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:24:07.532  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:24:07.532  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.532  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.532  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.532  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:24:07.533  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.533  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.534  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.534  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 07:24:07.534  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.534  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.534  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.535  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.535  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.535  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.536  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:24:07.536  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:07.536  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:07.536  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:07.536  5580  5626 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-25 07:24:07.538  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:24:07.539  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:24:07.540  4581  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:24:07.540  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.546  4581  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 07:24:07.546  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:24:07.547  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:24:07.547  4581  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:24:07.549  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:24:07.549  5580  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:24:07.549  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:24:07.549  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:24:07.549  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:24:07.549  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:24:07.549  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 07:24:07.552  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:07.553  4581  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:24:07.553  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.553  4581  4643 E BtGatt.ContextMap: Context not found for ID 5
11-25 07:24:07.554  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:24:07.554  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:24:07.554  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-25 07:24:07.555  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:07.559  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.559  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:24:07.559  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:24:07.559  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:24:07.560  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:24:07.562  4581  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:24:07.562  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.562  4581  4646 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:24:07.564  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.564  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:24:07.564  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:24:07.564  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:24:07.564  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-25 07:24:07.564  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.565  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:24:07.568  4581  4827 D BtGatt.GattService: registerClient() - UUID=191b3a4e-7192-4dcb-9700-99acd9dd9fc9
,11-25 07:24:07.569  4581  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 07:24:07.569  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.569  4581  4643 D BtGatt.GattService: onClientRegistered() - UUID=191b3a4e-7192-4dcb-9700-99acd9dd9fc9, clientIf=5
11-25 07:24:07.569  4581  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:24:07.570  5580  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:24:07.570  4581  4594 D BtGatt.GattService: start scan with filters
,11-25 07:24:07.573  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 07:24:07.573  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.573  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:24:07.573  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.573  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:24:07.573  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:24:07.573  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.573  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:24:07.573  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:24:07.573  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.574  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.574  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.574  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-25 07:24:07.574  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:24:07.575  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.575  4581  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:24:07.575  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.577  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:07.577  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:24:07.577  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.577  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:07.577  5580  5626 I io.jxcore.node.ConnectionHelper: start: OK
11-25 07:24:07.577  4581  4646 D BtGatt.ScanManager: handling starting scan
11-25 07:24:07.577  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.579  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.580  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 07:24:07.580  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:24:07.580  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:24:07.583  4581  4643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:24:07.583  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:07.583  4581  4646 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-25 07:24:07.588  4581  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:24:07.588  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:24:07.588  4581  4646 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:24:07.588  4581  4646 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 07:24:07.597  4581  4643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:24:07.597  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:24:07.602  4581  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 07:24:07.602  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:24:07.702  3408  3408 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:24:07.860   930  5333 D NetlinkSocketObserver: NeighborEvent{elapsedMs=102878, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-25 07:24:08.082  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-25 07:24:08.082  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:24:08.082  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 07:24:12.578  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:12.578  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:12.578  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-25 07:24:12.578  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:24:12.579  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-25 07:24:12.579  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:12.579  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 07:24:12.579  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:24:12.579  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.579  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:24:12.580  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:24:12.580  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.580  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:12.580  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.580  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:24:12.581  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.583  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:24:12.584  4581  4594 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:24:12.584  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:24:12.585  4581  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:24:12.586  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:24:12.588  4581  4807 D BtGatt.GattService: stopScan() - queue size =1
,11-25 07:24:12.591  4581  4581 D BtGatt.ScanManager: awakened up at time 107609
,11-25 07:24:12.593  4581  4827 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-25 07:24:12.594  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:24:12.595  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.595  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-25 07:24:12.595  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.595  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.596  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.596  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.596  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:24:12.596  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:12.597  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.597  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.597  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-25 07:24:12.597  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:24:12.597   930  3786 I ActivityManager: Killing 5021:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-25 07:24:12.632  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:24:12.632  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:12.633  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.633  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:24:12.633  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.634  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:12.634  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:24:12.634  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:24:12.634  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:24:12.634  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.635  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:24:12.635  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:24:12.635  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.635  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.635  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.635  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-25 07:24:12.635  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.635  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.637  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.637  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:24:12.637  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-25 07:24:12.650  4581  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-25 07:24:12.650  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:12.650  4581  4643 D BtGatt.GattService: current time is 107669347045
11-25 07:24:12.651  4581  4643 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -68, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -68, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -79, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -66, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -75, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -68, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -24, -5, 124, 62, -54, -40, 1, -128, -97, 75, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 101, 65, 97, 3, 0, -25, 27, -109, 45, 109, -48, 0]
11-25 07:24:12.651  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-25 07:24:12.651  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-25 07:24:12.651  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-25 07:24:12.652  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-25 07:24:12.652  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-25 07:24:12.652  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-25 07:24:12.652  4581  4643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 101, 65, 97, 3, 0, -25, 27, -109, 45, 109, -48]
,11-25 07:24:12.657  4581  4643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 07:24:12.658  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:24:12.658  4581  4646 D BtGatt.ScanManager: stopping BLe Batch
,11-25 07:24:12.664  4581  4643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:24:12.664  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:24:12.664  4581  4646 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:24:12.669  4581  4643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:24:12.669  4581  4643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:24:13.136  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:24:13.137  5580  5580 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:13.137  5580  5580 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-25 07:24:17.635  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:17.636  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.636  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.636  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.636  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:24:17.636  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:24:17.637  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.637  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.637  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.637  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.637  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:17.637  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 07:24:17.644  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.645  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.648  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.649  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.649  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.649  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.649  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:24:17.649  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.649  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:17.651  5580  5626 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-25 07:24:17.653  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:17.653  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.654  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.654  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.654  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.654  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.655  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.656  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.656  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:17.656  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.656  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.658  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.658  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.658  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.658  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.658  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.658  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:17.658  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.660  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 07:24:17.660  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:17.660  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.660  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.660  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.660  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:24:17.660  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.660  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.660  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:17.660  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.661  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.661  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.663  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.663  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.663  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.663  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.663  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.663  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.663  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.664  5580  5626 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-25 07:24:17.664  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:17.665  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.665  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.665  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.665  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.665  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.665  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.665  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:17.665  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.665  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.665  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.667  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.667  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.667  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.667  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.667  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.668  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.668  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.669  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-25 07:24:17.669  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:17.669  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.669  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.669  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.669  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.670  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.670  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.670  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.670  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.670  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.670  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.673  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.673  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.673  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.673  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.673  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.673  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.673  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.674  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-25 07:24:17.676  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 07:24:17.676  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:24:17.676  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 07:24:17.676  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:24:17.676  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:24:17.676  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-25 07:24:17.676  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-25 07:24:17.676  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-25 07:24:17.676  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:17.676  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.677  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.677  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.677  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.677  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.677  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.677  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.677  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.677  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.677  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.680  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.680  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.680  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.680  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.680  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.680  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.680  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.682  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:24:17.682  5580  5626 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 07:24:17.682  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-25 07:24:17.685  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-25 07:24:17.685  5580  5626 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-25 07:24:17.685  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-25 07:24:17.686  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-25 07:24:17.687  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-25 07:24:17.687  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-25 07:24:17.687  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-25 07:24:17.687  5580  5626 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 07:24:17.687  5580  5626 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-25 07:24:17.687  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:24:17.687  5580  5626 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 07:24:17.687  5580  5626 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,11-25 07:24:17.687  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:24:17.687  5580  5626 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-25 07:24:17.687  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-25 07:24:17.692  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-25 07:24:17.693  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-25 07:24:17.693  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-25 07:24:17.694  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-25 07:24:17.694  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-25 07:24:17.694  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-25 07:24:17.694  5580  5626 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-25 07:24:17.694  5580  5626 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-25 07:24:17.694  5580  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
11-25 07:24:17.694  5580  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-25 07:24:17.694  5580  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-25 07:24:17.695  5580  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-25 07:24:17.696  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:17.696  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.696  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.696  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.696  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.696  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-25 07:24:17.697  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
,11-25 07:24:17.695  4827  4827 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29398]" dev="sockfs" ino=29398 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 07:24:17.695  4827  4827 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29398]" dev="sockfs" ino=29398 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 07:24:17.697  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.697  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.697  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.697  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.697  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
11-25 07:24:17.697  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.698  5580  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-25 07:24:17.698  5580  5627 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,11-25 07:24:17.698  5580  5627 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:24:17.700  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.701  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.701  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.701  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.701  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.701  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.701  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.702  5580  5626 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-25 07:24:17.702  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:17.702  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.702  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.702  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.702  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.703  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.703  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.703  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.703  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.703  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.703  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.704  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.704  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.704  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.704  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.704  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.704  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.704  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.705  5580  5626 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-25 07:24:17.705  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:17.706  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.706  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.706  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.706  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.706  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.706  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.706  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.706  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:17.706  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.706  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.708  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.708  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.708  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.708  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.708  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-25 07:24:17.708  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.708  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.709  5580  5626 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-25 07:24:17.709  5580  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-25 07:24:17.709  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 07:24:17.709  5580  5626 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-25 07:24:17.709  5580  5626 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-25 07:24:17.709  5580  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-25 07:24:17.709  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 07:24:17.709  5580  5626 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-25 07:24:17.709  5580  5626 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-25 07:24:17.709  5580  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-25 07:24:17.709  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-25 07:24:17.709  5580  5626 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-25 07:24:17.710  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:17.710  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:17.710  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:17.710  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.710  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:24:17.710  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.710  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.710  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.710  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:17.710  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.710  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:17.711  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.711  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.711  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:17.711  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:17.711  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:17.711  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:17.711  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:17.712  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:17.712  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:17.712  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:17.712  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:17.712  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:17.712  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:19.486   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-25 07:24:19.486   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-25 07:24:22.713  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:22.713  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.714  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:22.714  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:24:22.714  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:22.714  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:22.715  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:24:22.715  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:22.715  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:24:22.715  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:22.715  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
,11-25 07:24:22.715  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.716  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:22.716  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:22.716  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.716  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.720  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.720  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.720  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.720  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:22.721  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:22.721  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.721  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:22.725  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-25 07:24:22.726  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-25 07:24:22.726  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:24:22.733  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-25 07:24:22.735  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-25 07:24:22.735  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-25 07:24:22.735  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-25 07:24:22.736  5580  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-25 07:24:22.736  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-25 07:24:22.736  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-25 07:24:22.736  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-25 07:24:22.737  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:22.737  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-25 07:24:22.737  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-25 07:24:22.737  5580  5629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:24:22.737  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-25 07:24:22.737  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:24:22.738  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-25 07:24:22.738  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-25 07:24:22.738  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:22.738  5580  5580 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-25 07:24:22.738  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:22.738  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:24:22.739  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.739  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:24:22.739  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:24:22.739  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.741  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.742  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:24:22.734  4594  4594 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31564]" dev="sockfs" ino=31564 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-25 07:24:22.742  5580  5629 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-25 07:24:22.742  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.734  4594  4594 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31564]" dev="sockfs" ino=31564 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-25 07:24:22.742  5580  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-25 07:24:22.742  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.742  5580  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-25 07:24:22.742  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.742  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:24:22.742  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:22.742  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:24:22.742  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:22.742  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:24:22.742  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:22.743  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:22.743  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-25 07:24:22.743  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-25 07:24:22.743  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:22.743  5580  5580 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:22.743  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.743  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.743  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:22.743  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.743  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.746  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.746  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.746  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.746  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:22.746  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:22.746  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.746  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.748  5580  5626 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-25 07:24:22.749  5580  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-25 07:24:22.749  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-25 07:24:22.749  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:24:22.749  5580  5626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-25 07:24:22.749  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:22.749  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:22.749  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-25 07:24:22.750  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:22.750  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:22.750  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:22.750  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.750  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.751  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:22.752  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.752  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.756  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.756  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.756  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.756  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:22.757  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:22.757  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.757  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.762  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:24:22.762  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:22.762  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:22.762  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:22.762  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:22.762  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:22.762  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:22.762  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.762  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:22.762  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.763  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.764  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:24:22.764  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.764  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.764  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:24:22.764  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:22.764  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.764  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
,11-25 07:24:22.765  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:24:22.765  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:24:22.765  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:24:22.765  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:24:22.766  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:24:22.766  5580  5626 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b9b96 not in the list
11-25 07:24:22.766  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:22.766  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.766  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:22.766  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.766  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.768  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.768  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.768  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:24:22.768  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-25 07:24:22.768  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:24:22.768  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:22.768  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9d2317 not in the list
11-25 07:24:22.769  5580  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-25 07:24:22.769  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 07:24:22.770  5580  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-25 07:24:22.770  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-25 07:24:22.770  5580  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-25 07:24:22.770  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-25 07:24:22.773  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-25 07:24:22.773  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-25 07:24:22.774  5580  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-25 07:24:22.774  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 07:24:22.774  5580  5626 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-25 07:24:22.774  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-25 07:24:22.774  5580  5626 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-25 07:24:22.774  5580  5626 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-25 07:24:22.776  5580  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-25 07:24:22.776  5580  5626 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-25 07:24:22.776  5580  5626 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-25 07:24:22.776  5580  5626 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-25 07:24:22.776  5580  5626 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-25 07:24:22.776  5580  5626 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-25 07:24:22.777  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:24:22.777  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d75534 added. We now have 3 listener(s)
11-25 07:24:22.777  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:24:22.779  5580  5626 D BluetoothAdapter: enable(): BT is already enabled..!
11-25 07:24:22.779   930  3770 D WifiService: setWifiEnabled: true pid=5580, uid=10077
11-25 07:24:22.780   930  3770 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:24:22.826  4581  4797 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-25 07:24:22.826  4581  4805 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-25 07:24:22.826  5580  5627 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-25 07:24:22.827  5580  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-25 07:24:22.827  5580  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,11-25 07:24:23.243  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:24:24.487   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:25.488   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:26.141   930  2941 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-25 07:24:26.489   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:27.490   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:27.785  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:24:27.785  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dd4f5d added. We now have 4 listener(s)
,11-25 07:24:27.785  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:24:27.799  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:24:27.799  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dd4f5d removed from the list
,11-25 07:24:27.799  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:27.801  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:24:27.801  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95750d2 added. We now have 4 listener(s)
,11-25 07:24:27.801  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:24:27.805  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:27.805  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95750d2 removed from the list
,11-25 07:24:27.805  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:27.807  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:24:27.807  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93995a3 added. We now have 4 listener(s)
11-25 07:24:27.807  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:24:27.812   930  3815 D WifiService: setWifiEnabled: false pid=5580, uid=10077
11-25 07:24:27.812   930  3815 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:24:27.817   930  2941 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 07:24:27.817   930  2941 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 07:24:27.817   930  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:24:27.817   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:24:27.826  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:24:27.827  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:24:27.830  4581  4639 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 07:24:27.830  4581  4639 D BluetoothAdapterProperties: Setting state to 13
11-25 07:24:27.830  4581  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-25 07:24:27.831  4581  4639 D BluetoothAdapterProperties: onBluetoothDisable()
11-25 07:24:27.832  4581  4639 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:24:27.834  4581  4643 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:24:27.834  4581  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-25 07:24:27.836  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:24:27.836  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:24:27.837  4581  4581 D BluetoothMapService: onReceive
11-25 07:24:27.837  4581  4581 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 07:24:27.837  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:27.837  4581  4581 D BluetoothMapService: STATE_TURNING_OFF
11-25 07:24:27.837  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:24:27.838  4581  4581 D BluetoothMapService: MAP Service closeService in
11-25 07:24:27.838  4581  4581 D BluetoothMapMasInstance0: MAP Service shutdown
,11-25 07:24:27.838  4581  4581 D ObexServerSockets0: shutdown(block = true)
,11-25 07:24:27.838  5580  5626 D io.jxcore.node.ConnectivityMonitor: start: OK
11-25 07:24:27.839  4581  4829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-25 07:24:27.839  4581  4581 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 07:24:27.839  4581  4581 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 07:24:27.839  4581  4805 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 07:24:27.841  4581  4830 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-25 07:24:27.842   930  5334 D DhcpClient: Clearing IP address
11-25 07:24:27.843   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:24:27.850  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:27.850   509   927 D CommandListener: Setting iface cfg
11-25 07:24:27.855  4581  4581 I BtOppRfcommListener: stopping Accept Thread
,11-25 07:24:27.855  4581  5278 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-25 07:24:27.855  4581  5278 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 07:24:27.856  3550  5390 V NativeCrypto: Read error: ssl=0x7f5a58d580: I/O error during system call, Connection timed out
11-25 07:24:27.856  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:27.858  3550  5390 V NativeCrypto: SSL shutdown failed: ssl=0x7f5a58d580: I/O error during system call, Broken pipe
,11-25 07:24:27.861   930  3790 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-25 07:24:27.861  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:27.861   930  5332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-25 07:24:27.863   930  5332 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-25 07:24:27.864   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-25 07:24:27.864   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-25 07:24:27.865   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 07:24:27.866  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:27.868   930   943 I ActivityManager: Start proc 5633:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-25 07:24:27.871   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-25 07:24:27.871   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-25 07:24:27.874  4581  4581 D HeadsetService: Received stop request...Stopping profile...
11-25 07:24:27.876   930   930 D RttService: SCAN_AVAILABLE : 1
11-25 07:24:27.876   930  5335 D DhcpClient: Receive thread stopped
11-25 07:24:27.876   930  3050 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 07:24:27.876   930  2943 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-25 07:24:27.877   535   535 E Parcel  : Reading a NULL string not supported here.
11-25 07:24:27.879  3697  3858 W QCNEJ   : |CORE| network lost: 100
11-25 07:24:27.879  3697  3858 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-25 07:24:27.879  3741  3967 D BluetoothHeadset: Proxy object disconnected
,11-25 07:24:27.880   930   930 D BluetoothHeadset: Proxy object disconnected
,11-25 07:24:27.880   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:27.880   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:27.881  3085  3097 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:27.883  4581  4581 D A2dpService: Received stop request...Stopping profile...
11-25 07:24:27.884  4581  4810 D A2dpStateMachine: Exit Disconnected: -1
11-25 07:24:27.885   930   930 D BluetoothA2dp: Proxy object disconnected
11-25 07:24:27.885  4581  4581 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:27.885  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.885  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 07:24:27.885  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:27.886  4581  4581 D HidService: Received stop request...Stopping profile...
11-25 07:24:27.886  4581  4581 D HidService: Stopping Bluetooth HidService
11-25 07:24:27.886  3085  3085 D HeadsetProfile: Bluetooth service disconnected
11-25 07:24:27.887  3085  3085 D BluetoothA2dp: Proxy object disconnected
,11-25 07:24:27.892   930  2941 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 07:24:27.891  4581  4581 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-25 07:24:27.893  4581  4581 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 07:24:27.893  4581  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:27.893  4581  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:27.893  4581  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:27.893  4581  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 07:24:27.893  4581  4581 D HealthService: Received stop request...Stopping profile...
11-25 07:24:27.893  4581  4643 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-25 07:24:27.895  4581  4581 D PanService: Received stop request...Stopping profile...
,11-25 07:24:27.897  4581  4581 D BluetoothMapService: Received stop request...Stopping profile...
,11-25 07:24:27.897  4581  4581 D BluetoothMapService: stop()
11-25 07:24:27.897  4581  4581 D BluetoothMapAppObserver: deinitObservers()
11-25 07:24:27.897  4581  4581 D BluetoothMapAppObserver: removeReceiver()
,11-25 07:24:27.899  3085  3085 D BluetoothInputDevice: Proxy object disconnected
11-25 07:24:27.899  3085  3085 D HidProfile: Bluetooth service disconnected
11-25 07:24:27.899  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 07:24:27.900  3085  3085 D PanProfile: Bluetooth service disconnected
,11-25 07:24:27.900  4581  4581 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:27.900  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.900  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:27.900  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:24:27.901  4581  4581 D SapService: Received stop request...Stopping profile...
,11-25 07:24:27.901  4581  4581 V SapService: stop()
11-25 07:24:27.903   930  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:24:27.905  4581  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:27.905  4581  4581 V BluetoothAdapterState: isTurningOff()=true
,11-25 07:24:27.905  4581  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:27.905  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.905  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:27.905  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:27.906  4581  4581 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 07:24:27.906  4581  4581 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 07:24:27.906  4581  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 07:24:27.906  4581  4797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-25 07:24:27.906  4581  4797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 07:24:27.906  4581  4643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 07:24:27.906  4581  4797 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:24:27.906  4581  4797 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-25 07:24:27.906  4581  4581 V BluetoothAdapterState: isTurningOff()=true
,11-25 07:24:27.906  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.906  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:27.906  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:27.907  4581  4581 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 07:24:27.907  4581  4643 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 07:24:27.907  4581  4581 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 07:24:27.907  4581  4581 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:27.907  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.907  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:27.907  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:27.907  4581  4581 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-25 07:24:27.908  4581  4581 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 07:24:27.909  4581  4581 D BluetoothMapService: MAP Service closeService in
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:27.909  4581  4581 D BluetoothMapService: cleanup()
11-25 07:24:27.909  4581  4581 D BluetoothMapService: MAP Service closeService in
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:27.909  4581  4581 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:27.910  4581  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 07:24:27.910  4581  4639 D BluetoothAdapterProperties: Setting state to 15
11-25 07:24:27.910  4581  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 07:24:27.911  3085  3085 D BluetoothMap: Proxy object disconnected
11-25 07:24:27.911  3085  3085 D MapProfile: Bluetooth service disconnected
11-25 07:24:27.911  3085  3941 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:27.911   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:27.911  4581  4639 I BluetoothAdapterState: Entering BleOnState
11-25 07:24:27.912  3085  3097 D BluetoothPan: onBluetoothStateChange on: false
11-25 07:24:27.912  3085  3941 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:24:27.913   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:24:27.913   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:27.913  3741  3773 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:27.913   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:27.913  3085  3097 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 07:24:27.914  3085  3941 D BluetoothMap: onBluetoothStateChange: up=false
11-25 07:24:27.915  3085  3098 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 07:24:27.916  4581  4639 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 07:24:27.916  4581  4639 D BluetoothAdapterProperties: Setting state to 16
11-25 07:24:27.916  4581  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-25 07:24:27.916  4581  4639 D BluetoothAdapterProperties: onBleDisable
11-25 07:24:27.916  4581  4639 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:24:27.917  4581  4640 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 07:24:27.918  4581  4643 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:24:27.918  4581  4797 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-25 07:24:27.919  4581  4797 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:27.920  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:24:27.920  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:24:27.921  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:27.921  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:24:27.926  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:27.934   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 07:24:27.936  5633  5633 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-25 07:24:27.949  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:24:27.952   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-25 07:24:27.953   509   927 D CommandListener: Clearing all IP addresses on wlan0
11-25 07:24:27.953   509   927 D TetherController: Setting IP forward enable = 0
11-25 07:24:27.954   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e60bba:true
11-25 07:24:27.954   930  2943 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-25 07:24:27.955   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 07:24:27.958   930  2941 D DhcpClient: doQuit
11-25 07:24:27.958  5237  5237 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@86050c7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-25 07:24:27.958   930  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 07:24:27.959   930   947 D Tethering: MasterInitialState.processMessage what=3
11-25 07:24:27.959  3408  3408 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 07:24:27.959   930  5334 D DhcpClient: onQuitting
11-25 07:24:27.960  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:27.960  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 07:24:27.963  5007  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-25 07:24:27.964  5007  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:24:27.964  5007  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 07:24:27.965  5007  5020 E SarControlService: no key has been found,reset the power
11-25 07:24:27.965  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:24:27.965  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 07:24:27.965  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 07:24:27.966  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:24:27.966  5033  5033 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:24:27.967  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 07:24:27.967  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 07:24:27.967  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 07:24:27.968  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:24:27.968  5033  5033 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 07:24:27.970  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000ea03000000000000ffffffff]
11-25 07:24:27.970  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:24:27.971  5033  5047 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-25 07:24:27.971  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:24:27.971  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:24:27.972  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:24:27.972  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:24:27.972  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000eb03000000000000ffffffff]
11-25 07:24:27.972  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:24:27.972  5033  5047 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-25 07:24:27.973  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:27.973  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:24:27.973  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:24:27.973  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 07:24:27.975   930  3770 I ActivityManager: Start proc 5658:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-25 07:24:27.978  3408  3408 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-25 07:24:27.982  3408  3408 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 07:24:27.989  5633  5633 D LocalBluetoothProfileManager: Adding local MAP profile
,11-25 07:24:27.992  5633  5633 D BluetoothMap: Create BluetoothMap proxy object
,11-25 07:24:27.997  5633  5633 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-25 07:24:28.008   509   927 E Netd    : netlink response contains error (No such file or directory)
,11-25 07:24:28.009   930  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-25 07:24:28.010  5633  5633 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:24:28.017   930  3815 I ActivityManager: Killing 4971:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-25 07:24:28.020  3408  3408 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 07:24:28.031  5658  5658 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-25 07:24:28.033  3408  3408 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-25 07:24:28.127  4581  4643 I bt_hci  : shut_down
,11-25 07:24:28.131  4581  4647 D bt_hwcfg: hw_epilog_process
,11-25 07:24:28.131  4581  4647 I bt_vendor: low_power_mode_cb
,11-25 07:24:28.134  4581  4647 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-25 07:24:28.134  4581  4647 I bt_vendor: epilog_cb
11-25 07:24:28.134  4581  4647 I bt_hci  : epilog_finished_callback
,11-25 07:24:28.136  4380  4380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:24:28.136   930  2941 D wifi    : In wifi stop Hal
11-25 07:24:28.136   930  2941 D wifi    : halHandle = 0x7f58388180, mVM = 0x7f74a0d140, mCls = 0x100a02
11-25 07:24:28.136   930  3407 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 07:24:28.137   930  3407 D WifiHAL : Got a signal to exit!!!
11-25 07:24:28.137   930  3407 I WifiHAL : Exit wifi_event_loop
11-25 07:24:28.137   930  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-25 07:24:28.137   930  2941 E WifiHAL : Event processing terminated
11-25 07:24:28.137   930  2941 D wifi    : In wifi cleaned up handler
11-25 07:24:28.137   930  2941 I WifiHAL : Internal cleanup completed
,11-25 07:24:28.138  4581  4643 I bt_hci_h4: hal_close
11-25 07:24:28.139  3907  4191 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 07:24:28.139  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:28.140  4581  4643 I bt_userial_vendor: device fd = 54 close
,11-25 07:24:28.159   930  3407 D wifi    : set interface wlan0 flags (DOWN)
,11-25 07:24:28.159   930  2941 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.k.d(PG:583)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.e.b(PG:170)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.exists(File.java:361)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.215  5658  5658 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-25 07:24:28.215  5658  5658 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-25 07:24:28.222  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:24:28.226  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:24:28.233  4035  4035 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 07:24:28.236  4035  4035 D SystemUpdateService: onCreate
11-25 07:24:28.237  5633  5633 D DockEventReceiver: finishStartingService: stopping service
11-25 07:24:28.241  4035  4035 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 07:24:28.248  4581  4640 D bt_stack_manager: event_shut_down_stack finished.
11-25 07:24:28.249  4581  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-25 07:24:28.250  4035  4035 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-25 07:24:28.252  4581  4639 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-25 07:24:28.252  4581  4581 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 07:24:28.252  4581  4581 D BtGatt.GattService: Received stop request...Stopping profile...
,11-25 07:24:28.252  4581  4581 D BtGatt.GattService: stop()
11-25 07:24:28.252  4581  4581 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 07:24:28.254  4581  4581 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:28.254  4581  4581 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:28.254  4035  5361 I iu.UploadsManager: num queued entries: 0
11-25 07:24:28.254  4581  4581 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:28.254  4581  4581 V BluetoothAdapterState: isBleTurningOff()=true
11-25 07:24:28.255  4581  4639 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 07:24:28.255  4581  4639 D BluetoothAdapterProperties: Setting state to 10
11-25 07:24:28.255  4581  4639 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 07:24:28.255  4035  5361 I iu.UploadsManager: num updated entries: 0
11-25 07:24:28.255  4581  4639 I BluetoothAdapterState: Entering OffState
11-25 07:24:28.256  4035  5361 I iu.SyncManager: NEXT; no task
11-25 07:24:28.256   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-25 07:24:28.257  4035  4035 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-25 07:24:28.262  4581  4581 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-25 07:24:28.262  4581  4581 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 07:24:28.262  4581  4581 I BluetoothServiceJni: cleanupNative: return from cleanup
11-25 07:24:28.263  4581  4640 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-25 07:24:28.265  4035  4035 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-25 07:24:28.267  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 07:24:28.275  4581  4640 D bt_stack_manager: event_clean_up_stack finished.
11-25 07:24:28.275  5365  5365 D SprintDMHelper: simOperator: 
11-25 07:24:28.275  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-25 07:24:28.277  4581  4581 I art     : System.exit called, status: 0
11-25 07:24:28.280  4581  4581 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-25 07:24:28.285  4380  5693 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 07:24:28.299  4035  5690 I SystemUpdateService: active receiver: enabled
,11-25 07:24:28.305   930  3767 I ActivityManager: Start proc 5694:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-25 07:24:28.309  4035  5690 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:24:28.311  4035  5690 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 07:24:28.313  4035  5690 I SystemUpdateService: now status is 0 (complete)
11-25 07:24:28.313  4035  5690 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-25 07:24:28.313  4035  5690 I SystemUpdateService: file has been verified
11-25 07:24:28.313  4035  5690 I SystemUpdateService: OTA package size = 21989297
,11-25 07:24:28.325   930  3764 I ActivityManager: Process com.android.bluetooth (pid 4581) has died
,11-25 07:24:28.349  5694  5694 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-25 07:24:28.361   930   947 D Tethering: InitialState.processMessage what=4
,11-25 07:24:28.364   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 07:24:28.366   930  3770 I ActivityManager: Killing 5237:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-25 07:24:28.390  4035  5690 I SystemUpdateService: showing system update notification
,11-25 07:24:28.447  4035  4035 D SystemUpdateService: onDestroy
,11-25 07:24:28.449   930  3384 I ActivityManager: Killing 4663:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-25 07:24:28.490   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:28.569  5658  5678 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-25 07:24:28.578   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@55ada2f:true
,11-25 07:24:29.033   509   927 D TetherController: Setting IP forward enable = 0
,11-25 07:24:29.491   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-25 07:24:32.841   930  3790 D WifiService: setWifiEnabled: true pid=5580, uid=10077
,11-25 07:24:32.841   930  3790 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:24:32.855   509   927 D SoftapController: Softap fwReload - Ok
,11-25 07:24:32.861   509   927 D CommandListener: Setting iface cfg
,11-25 07:24:32.861   509   927 D CommandListener: Trying to bring down wlan0
,11-25 07:24:32.863   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:24:32.868   930  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 07:24:33.439   930  2941 D wifi    : set interface wlan0 flags (UP)
,11-25 07:24:33.442   930  2941 I WifiHAL : Initializing wifi
11-25 07:24:33.442   930  2941 I WifiHAL : Creating socket
11-25 07:24:33.445   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-25 07:24:33.447   930  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-25 07:24:33.448   930  2941 D wifi    : Did set static halHandle = 0x7f58388180
,11-25 07:24:33.448   930  2941 D wifi    : halHandle = 0x7f58388180, mVM = 0x7f74a0d140, mCls = 0x199a
,11-25 07:24:33.448   930  2941 D wifi    : array field set
11-25 07:24:33.448   930  2941 I WifiNative-HAL: interface[0] = wlan0
11-25 07:24:33.453   930  5721 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546940944768
11-25 07:24:33.453   930  5721 D wifi    : waitForHalEvents called, vm = 0x7f74a0d140, obj = 0x199a, env = 0x7f55fc8980
,11-25 07:24:33.527  5722  5722 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 07:24:33.548  5722  5722 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:24:33.555   930  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 07:24:33.562  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:33.580  5722  5722 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:24:33.580  5722  5722 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 07:24:33.596  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:24:33.596  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:24:33.596  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:33.596   930  2941 D WifiConfigStore: Loading config and enabling all networks 
11-25 07:24:33.596  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:24:33.605   930  2941 D WifiConfigStore: loaded 0 passpoint configs
11-25 07:24:33.605   930  2941 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 07:24:33.606   930  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-25 07:24:33.607   930  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-25 07:24:33.607   930  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-25 07:24:33.608   930  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-25 07:24:33.608   930  2941 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-25 07:24:33.608   930  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 07:24:33.611   930  2941 D WifiNative-HAL: Setting external_sim to 1
11-25 07:24:33.611  4380  4380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:24:33.612   930  2941 D wifi    : setting dfs flag to true, 0x7f5a433240
,11-25 07:24:33.613   930  2941 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 07:24:33.613   930  2941 D wifi    : setting scan oui 0x7f5a433240
11-25 07:24:33.613   930  2941 D WifiHAL : Sending mac address OUI
,11-25 07:24:33.617   930  2941 E native  : do suspend false
,11-25 07:24:33.624   930  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-25 07:24:33.625   509   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 07:24:33.625   930   930 D RttService: SCAN_AVAILABLE : 3
11-25 07:24:33.625   930  3050 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 07:24:33.626   509   927 D CommandListener: Setting iface cfg
,11-25 07:24:33.630   930  2937 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-25 07:24:33.630   930  2937 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 07:24:33.639   930  2937 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 07:24:33.639   930  2937 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-25 07:24:33.646   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128664 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-25 07:24:34.492   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:35.493   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:36.494   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:36.714  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:24:36.719  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:24:36.726  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:24:36.778   930  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 07:24:36.780   930  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-25 07:24:36.780   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:24:36.793   930  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:24:36.825   930  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:24:36.826  5722  5722 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:24:37.243  5722  5722 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 07:24:37.284  5722  5722 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 07:24:37.286  5722  5722 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 07:24:37.294   930  2941 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 07:24:37.294   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-25 07:24:37.294   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 07:24:37.310   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:24:37.325   509   927 D CommandListener: Setting iface cfg
,11-25 07:24:37.330   930  2941 D WifiStateMachine: Start Dhcp Watchdog 2
,11-25 07:24:37.336   930  5728 D DhcpClient: Receive thread started
,11-25 07:24:37.341   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 07:24:37.341   930  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 07:24:37.341   930  2943 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-25 07:24:37.422   930  2941 E native  : do suspend false
,11-25 07:24:37.437   930  5727 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 07:24:37.450   930  5728 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-25 07:24:37.450   930  5727 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-25 07:24:37.453   930  5727 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-25 07:24:37.476   930  5728 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-25 07:24:37.477   930  5727 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 07:24:37.480   509   927 D CommandListener: Setting iface cfg
11-25 07:24:37.485   930  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 07:24:37.489   930  5727 D DhcpClient: Scheduling renewal in 86399s
,11-25 07:24:37.495   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:37.500   930  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-25 07:24:37.501   930  2941 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 07:24:37.502   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 07:24:37.504   930  2943 D ConnectivityService: Adding iface wlan0 to network 101
,11-25 07:24:37.524   930  2941 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 07:24:37.562   930  2943 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-25 07:24:37.562   930  2943 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-25 07:24:37.565   930  2943 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-25 07:24:37.567   930  2943 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-25 07:24:37.570   930  2943 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-25 07:24:37.576   930  2943 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 07:24:37.580   930  2943 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-25 07:24:37.580   930  2943 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-25 07:24:37.580   930  2943 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-25 07:24:37.580   930  2943 D ConnectivityService:    accepting network in place of null
11-25 07:24:37.580   930  2941 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 07:24:37.580   930  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:24:37.581   930  2943 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 07:24:37.594   930  5726 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132613, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 07:24:37.602   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:24:37.623   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:24:37.626   930  2943 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-25 07:24:37.626   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:24:37.626  3697  3858 W QCNEJ   : |CORE| network available: 101
11-25 07:24:37.627   930  2943 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-25 07:24:37.628   930   947 D Tethering: MasterInitialState.processMessage what=3
11-25 07:24:37.628  3697  3858 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-25 07:24:37.630  3697  3858 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-25 07:24:37.630  3697  3858 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-25 07:24:37.632  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:24:37.632  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-25 07:24:37.632  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:37.632  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-25 07:24:37.640  5007  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 07:24:37.640  5007  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:24:37.640  5007  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 07:24:37.640  5007  5020 E SarControlService: no key has been found,reset the power
11-25 07:24:37.640  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:24:37.640  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 07:24:37.641  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 07:24:37.641  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:24:37.641  5033  5033 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:24:37.642  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 07:24:37.643  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-25 07:24:37.643  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 07:24:37.643  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:24:37.643  5033  5033 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-25 07:24:37.645  4035  4035 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 07:24:37.649  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000ec03000000000000ffffffff]
,11-25 07:24:37.649  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:24:37.649  5033  5047 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-25 07:24:37.649  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000ed03000000000000ffffffff]
11-25 07:24:37.649  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:24:37.649  5033  5047 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-25 07:24:37.650  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:24:37.650  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:24:37.651  4035  4035 D SystemUpdateService: onCreate
11-25 07:24:37.652  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:24:37.652  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-25 07:24:37.655  4035  4035 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 07:24:37.662   930  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 07:24:37.664  4035  4035 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 07:24:37.669  4035  5361 I iu.UploadsManager: num queued entries: 0
,11-25 07:24:37.669  4035  5361 I iu.UploadsManager: num updated entries: 0
11-25 07:24:37.669  4035  5361 I iu.SyncManager: NEXT; no task
,11-25 07:24:37.673  4035  5739 I SystemUpdateService: active receiver: enabled
,11-25 07:24:37.675  4035  4035 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 07:24:37.677  4035  4035 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-25 07:24:37.678  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-25 07:24:37.681  5365  5365 D SprintDMHelper: simOperator: 
11-25 07:24:37.681  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 07:24:37.702  4035  5739 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:24:37.714  4035  5739 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 07:24:37.714  4035  5739 I SystemUpdateService: now status is 0 (complete)
11-25 07:24:37.714  4035  5739 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 07:24:37.714  4035  5739 I SystemUpdateService: file has been verified
11-25 07:24:37.714  4035  5739 I SystemUpdateService: OTA package size = 21989297
,11-25 07:24:37.719  4035  5739 I SystemUpdateService: showing system update notification
,11-25 07:24:37.723   930  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:24:37 GMT], X-Android-Received-Millis=[1480076677722], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480076677688]}
,11-25 07:24:37.723   930  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 07:24:37.723   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-25 07:24:37.723   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-25 07:24:37.725   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-25 07:24:37.729  4035  4035 D SystemUpdateService: onDestroy
,11-25 07:24:37.783  4380  5744 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-25 07:24:37.846   930  3786 D WifiService: setWifiEnabled: false pid=5580, uid=10077
,11-25 07:24:37.846   930  3786 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:24:37.847   930  2941 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-25 07:24:37.847   930  2941 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-25 07:24:37.847   930  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 07:24:37.847   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:24:37.856   930  5727 D DhcpClient: Clearing IP address
11-25 07:24:37.856   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:24:37.858   509   927 D CommandListener: Setting iface cfg
,11-25 07:24:37.860   930  5728 D DhcpClient: Receive thread stopped
11-25 07:24:37.861  3550  5749 V NativeCrypto: Read error: ssl=0x7f58c86700: I/O error during system call, Connection timed out
11-25 07:24:37.862  3550  5749 V NativeCrypto: SSL shutdown failed: ssl=0x7f58c86700: I/O error during system call, Broken pipe
,11-25 07:24:37.873   930  3770 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-25 07:24:37.873   930  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-25 07:24:37.874   930  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 07:24:37.876   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-25 07:24:37.876   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-25 07:24:37.879   535   535 E Parcel  : Reading a NULL string not supported here.
,11-25 07:24:37.882   930   930 D RttService: SCAN_AVAILABLE : 1
,11-25 07:24:37.882   930  2943 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-25 07:24:37.882   930  3050 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-25 07:24:37.882   930  5725 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-25 07:24:37.884  3697  3858 W QCNEJ   : |CORE| network lost: 101
,11-25 07:24:37.884   930  2941 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-25 07:24:37.885  3697  3858 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-25 07:24:37.888   930  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-25 07:24:37.906   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:24:37.925   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:24:37.925   509   927 D CommandListener: Clearing all IP addresses on wlan0
11-25 07:24:37.925   930  2943 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-25 07:24:37.926   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-25 07:24:37.927   930   947 D Tethering: MasterInitialState.processMessage what=3
11-25 07:24:37.928   930  2941 D DhcpClient: doQuit
11-25 07:24:37.928   930  2941 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-25 07:24:37.929  5722  5722 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-25 07:24:37.929   930  5727 D DhcpClient: onQuitting
11-25 07:24:37.931  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:24:37.931  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:24:37.931  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:37.931  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:24:37.933  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:37.936  5007  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 07:24:37.936  5007  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:24:37.937  5007  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-25 07:24:37.937  5007  5020 E SarControlService: no key has been found,reset the power
11-25 07:24:37.938  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:24:37.938  4035  4035 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-25 07:24:37.939  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-25 07:24:37.939  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-25 07:24:37.939  5722  5722 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-25 07:24:37.939  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:24:37.940  5033  5033 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:24:37.941  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-25 07:24:37.941  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 07:24:37.941  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 07:24:37.941  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:24:37.941  5033  5033 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 07:24:37.943  5722  5722 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-25 07:24:37.944  4035  4035 D SystemUpdateService: onCreate
,11-25 07:24:37.946  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000ee03000000000000ffffffff]
11-25 07:24:37.947  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:24:37.947  5033  5047 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-25 07:24:37.947  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:24:37.947  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:24:37.948  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000ef03000000000000ffffffff]
11-25 07:24:37.948  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:24:37.948  5033  5047 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-25 07:24:37.949  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:24:37.949  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 07:24:37.952  4035  4035 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-25 07:24:37.956  4035  5759 I SystemUpdateService: active receiver: enabled
11-25 07:24:37.960  4035  4035 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-25 07:24:37.965  4035  5361 I iu.UploadsManager: num queued entries: 0
,11-25 07:24:37.965  4035  5361 I iu.UploadsManager: num updated entries: 0
,11-25 07:24:37.966  4035  5361 I iu.SyncManager: NEXT; no task
,11-25 07:24:37.968  4035  4035 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 07:24:37.970  4035  4035 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 07:24:37.972  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:24:37.976  5365  5365 D SprintDMHelper: simOperator: 
11-25 07:24:37.976  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 07:24:37.977   509   927 E Netd    : netlink response contains error (No such file or directory)
11-25 07:24:37.978   930  2943 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-25 07:24:37.978   930  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 07:24:37.979  4035  5759 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:24:37.982  5722  5722 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-25 07:24:37.987  4035  5759 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-25 07:24:37.987  4035  5759 I SystemUpdateService: now status is 0 (complete)
11-25 07:24:37.987  4035  5759 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 07:24:37.987  4035  5759 I SystemUpdateService: file has been verified
11-25 07:24:37.987  4035  5759 I SystemUpdateService: OTA package size = 21989297
,11-25 07:24:37.988  5722  5722 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-25 07:24:37.989  4380  5763 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-25 07:24:38.007  4035  5759 I SystemUpdateService: showing system update notification
,11-25 07:24:38.014  4035  4035 D SystemUpdateService: onDestroy
,11-25 07:24:38.090   930  2941 D wifi    : In wifi stop Hal
11-25 07:24:38.090   930  2941 D wifi    : halHandle = 0x7f58388180, mVM = 0x7f74a0d140, mCls = 0x199a
,11-25 07:24:38.090   930  5721 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-25 07:24:38.090   930  5721 D WifiHAL : Got a signal to exit!!!
,11-25 07:24:38.090   930  5721 I WifiHAL : Exit wifi_event_loop
11-25 07:24:38.091   930  2941 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-25 07:24:38.091   930  2941 E WifiHAL : Event processing terminated
11-25 07:24:38.091   930  2941 D wifi    : In wifi cleaned up handler
11-25 07:24:38.091   930  2941 I WifiHAL : Internal cleanup completed
11-25 07:24:38.093  4380  4380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-25 07:24:38.093  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:38.094  3907  4191 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:24:38.120   930  5721 D wifi    : set interface wlan0 flags (DOWN)
,11-25 07:24:38.121   930  2941 D WifiNative-HAL: HAL event thread stopped successfully
,11-25 07:24:38.327   930   947 D Tethering: InitialState.processMessage what=4
,11-25 07:24:38.335   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-25 07:24:38.496   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:38.626   930  2943 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-25 07:24:39.497   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-25 07:24:42.886   930   947 I ActivityManager: Start proc 5765:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 07:24:42.975  5765  5765 D AdapterServiceConfig: Adding HeadsetService
,11-25 07:24:42.975  5765  5765 D AdapterServiceConfig: Adding A2dpService
11-25 07:24:42.975  5765  5765 D AdapterServiceConfig: Adding HidService
11-25 07:24:42.975  5765  5765 D AdapterServiceConfig: Adding HealthService
11-25 07:24:42.975  5765  5765 D AdapterServiceConfig: Adding PanService
11-25 07:24:42.976  5765  5765 D AdapterServiceConfig: Adding GattService
,11-25 07:24:42.976  5765  5765 D AdapterServiceConfig: Adding BluetoothMapService
11-25 07:24:42.976  5765  5765 D AdapterServiceConfig: Adding SapService
,11-25 07:24:42.987   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c86b632:true
,11-25 07:24:42.987  5765  5765 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 07:24:42.990  5765  5765 I bt_bluedroid: init
,11-25 07:24:42.990  5765  5777 I BluetoothAdapterState: Entering OffState
,11-25 07:24:42.993  5765  5778 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-25 07:24:42.993  5765  5778 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-25 07:24:42.993  5765  5778 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 07:24:42.993  5765  5778 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 07:24:42.994  5765  5765 I bt_bluedroid: get_profile_interface socket
,11-25 07:24:42.996  5765  5781 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-25 07:24:42.996  5765  5765 I bt_bluedroid: get_profile_interface sdp
,11-25 07:24:42.997  5765  5781 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:24:43.001  5765  5776 I bt_bluedroid: config_hci_snoop_log
11-25 07:24:43.002   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-25 07:24:43.006  5765  5777 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 07:24:43.007  5765  5777 D BluetoothAdapterProperties: Setting state to 14
11-25 07:24:43.007  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 07:24:43.008  5765  5777 D BluetoothBondStateMachine: make
,11-25 07:24:43.010  5765  5782 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 07:24:43.013  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:24:43.014  5765  5765 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 07:24:43.016  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:43.017  5765  5765 D BtGatt.DebugUtils: handleDebugAction() action=null
11-25 07:24:43.017  5765  5765 D BtGatt.GattService: Received start request. Starting profile...
11-25 07:24:43.018  5765  5765 D BtGatt.GattService: start()
11-25 07:24:43.018  5765  5765 I bt_bluedroid: get_profile_interface gatt
,11-25 07:24:43.019  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:43.019  5765  5765 D BtGatt.AdvertiseManager: advertise manager created
,11-25 07:24:43.024  5765  5765 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:24:43.025  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:43.025  5765  5765 V BluetoothAdapterState: isBleTurningOn()=true
11-25 07:24:43.025  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:43.025  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 07:24:43.026  5765  5777 I bt_bluedroid: bt_bluedroid
,11-25 07:24:43.026  5765  5778 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-25 07:24:43.027  5765  5778 I bt_hci  : start_up
,11-25 07:24:43.032  5765  5778 I bt_vendor: alloc value 0xf423d871
11-25 07:24:43.032  5765  5778 I bt_vendor: init
11-25 07:24:43.032  5765  5778 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 07:24:43.032  5765  5778 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 07:24:43.145  5765  5778 D bt_hci  : start_up starting async portion
,11-25 07:24:43.145  5765  5785 I bt_hci  : event_finish_startup
,11-25 07:24:43.145  5765  5785 I bt_hci_h4: hal_open
,11-25 07:24:43.146  5765  5785 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 07:24:43.141  5786  5786 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-25 07:24:43.149  5765  5785 I bt_userial_vendor: device fd = 54 open
,11-25 07:24:43.164  5765  5785 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:24:43.167  5765  5785 D bt_hwcfg: Chipset BCM4358A3
,11-25 07:24:43.167  5765  5785 D bt_hwcfg: Target name = [BCM4358A3]
11-25 07:24:43.168  5765  5785 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 07:24:43.563  5765  5785 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 07:24:43.563  5765  5785 D bt_hwcfg: Settlement delay -- 100 ms
11-25 07:24:43.564  5765  5785 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 07:24:43.698  5765  5785 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:24:43.698  5765  5785 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-25 07:24:43.700  5765  5785 I bt_hwcfg: vendor lib fwcfg completed
11-25 07:24:43.700  5765  5785 I bt_vendor: firmware callback
11-25 07:24:43.700  5765  5785 I bt_hci  : firmware_config_callback
,11-25 07:24:43.709  5765  5788 I bt_btu  : btu_task pending for preload complete event
,11-25 07:24:43.709  5765  5788 I bt_btu_task: Bluetooth chip preload is complete
,11-25 07:24:43.709  5765  5788 I bt_btu  : btu_task received preload complete event
,11-25 07:24:43.716  5765  5788 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 07:24:43.716  5765  5788 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-25 07:24:43.716  5765  5788 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_A2D
11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_BTM
,11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 07:24:43.717  5765  5788 I         : BTE_InitTraceLevels -- TRC_SDP
,11-25 07:24:43.718  5765  5788 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 07:24:43.718  5765  5788 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 07:24:43.718  5765  5788 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 07:24:43.718  5765  5788 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 07:24:43.799  5765  5788 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41bb549
11-25 07:24:43.800  5765  5788 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41bb549 
,11-25 07:24:43.822  5765  5781 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 07:24:43.823  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-25 07:24:43.823  5765  5781 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 07:24:43.826  5765  5781 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:24:43.829  5765  5781 D BluetoothAdapterProperties: Scan Mode:20
,11-25 07:24:43.830  5765  5781 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 07:24:43.830  5765  5781 D bt_hci  : do_postload posting postload work item
11-25 07:24:43.830  5765  5785 I bt_hci  : event_postload
,11-25 07:24:43.830  5765  5785 I bt_vendor: sco_config_cb
11-25 07:24:43.830  5765  5785 I bt_hci  : sco_config_callback postload finished.
11-25 07:24:43.835  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:43.837  5765  5781 D bt_bte_conf: Device ID record 1 : primary
11-25 07:24:43.837  5765  5781 D bt_bte_conf:   vendorId            = 000f
11-25 07:24:43.837  5765  5781 D bt_bte_conf:   vendorIdSource      = 0001
11-25 07:24:43.837  5765  5781 D bt_bte_conf:   product             = 1200
11-25 07:24:43.838  5765  5781 D bt_bte_conf:   version             = 1436
11-25 07:24:43.838  5765  5785 I bt_vendor: low_power_mode_cb
11-25 07:24:43.838  5765  5781 D bt_bte_conf:   clientExecutableURL = 
11-25 07:24:43.838  5765  5781 D bt_bte_conf:   serviceDescription  = 
11-25 07:24:43.839  5765  5781 D bt_bte_conf:   documentationURL    = 
,11-25 07:24:43.839  5765  5781 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 07:24:43.839  5765  5778 D bt_stack_manager: event_start_up_stack finished
,11-25 07:24:43.840  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 07:24:43.841  5765  5777 D BluetoothAdapterProperties: Setting state to 15
11-25 07:24:43.841  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 07:24:43.842  5765  5777 I BluetoothAdapterState: Entering BleOnState
,11-25 07:24:43.846  5765  5777 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-25 07:24:43.846  5765  5777 D BluetoothAdapterProperties: Setting state to 11
11-25 07:24:43.846  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-25 07:24:43.854  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:43.855  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:43.855  5765  5765 D HeadsetService: Received start request. Starting profile...
,11-25 07:24:43.860  5765  5765 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-25 07:24:43.861  5765  5765 D HeadsetStateMachine: make
,11-25 07:24:43.870  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:24:43.872  5765  5765 D HeadsetStateMachine: max_hf_connections = 1
,11-25 07:24:43.872  5765  5765 I bt_bluedroid: get_profile_interface handsfree
11-25 07:24:43.872  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 07:24:43.873  5765  5781 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-25 07:24:43.876  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:43.876  5765  5765 D A2dpService: Received start request. Starting profile...
,11-25 07:24:43.877  5765  5765 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 07:24:43.878  5765  5765 I bt_bluedroid: get_profile_interface avrcp
,11-25 07:24:43.884  5765  5765 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 07:24:43.885  5765  5765 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 07:24:43.885  5765  5765 D A2dpStateMachine: make
,11-25 07:24:43.886  5765  5765 I bt_bluedroid: get_profile_interface a2dp
,11-25 07:24:43.887  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 07:24:43.889  5765  5796 D A2dpStateMachine: Enter Disconnected: -2
,11-25 07:24:43.889  5765  5765 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 07:24:43.890  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:43.892  5633  5633 D BluetoothInputDevice: Proxy object connected
,11-25 07:24:43.892  5765  5765 D HidService: Received start request. Starting profile...
11-25 07:24:43.892  5765  5765 I bt_bluedroid: get_profile_interface hidhost
11-25 07:24:43.893  5765  5765 D HidService: setHidService(): set to: null
11-25 07:24:43.893  5633  5633 D HidProfile: Bluetooth service connected
11-25 07:24:43.893  5765  5781 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf419c56d
11-25 07:24:43.893  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-25 07:24:43.895  5765  5765 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 07:24:43.896  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:43.896  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:24:43.896  5765  5765 D HealthService: Received start request. Starting profile...
,11-25 07:24:43.898  5765  5765 I bt_bluedroid: get_profile_interface health
,11-25 07:24:43.899  5765  5765 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 07:24:43.900  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:43.902  5633  5633 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:24:43.902  5765  5765 D PanService: Received start request. Starting profile...
11-25 07:24:43.902  5765  5765 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 07:24:43.902  5765  5765 I bt_bluedroid: get_profile_interface pan
,11-25 07:24:43.902  5633  5633 D PanProfile: Bluetooth service connected
,11-25 07:24:43.905  5765  5781 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-25 07:24:43.906  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:43.907  5633  5633 D BluetoothMap: Proxy object connected
,11-25 07:24:43.907  5765  5765 D BluetoothMapService: Received start request. Starting profile...
11-25 07:24:43.907  5765  5765 D BluetoothMapService: start()
11-25 07:24:43.908  5633  5633 D MapProfile: Bluetooth service connected
11-25 07:24:43.908  5633  5633 D BluetoothMap: getConnectedDevices()
11-25 07:24:43.909  5633  5633 D BluetoothMap: Bluetooth is Not enabled
,11-25 07:24:43.910  5765  5765 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 07:24:43.912  5765  5765 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-25 07:24:43.912  5765  5765 D BluetoothMapAppObserver: createReceiver()
11-25 07:24:43.914  5765  5765 D BluetoothMapAppObserver: initObservers()
11-25 07:24:43.914  5765  5765 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 07:24:43.923  5765  5765 V SapService: SapBinder()
,11-25 07:24:43.923  5765  5765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:43.924  5765  5765 D SapService: Received start request. Starting profile...
11-25 07:24:43.924  5765  5765 V SapService: start()
,11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 07:24:43.926  5765  5794 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:43.926  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:43.927  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:43.928  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.928  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:43.928  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:43.929  5765  5765 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:43.929  5765  5765 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:43.929  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:43.929  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:24:43.929  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 07:24:43.929  5765  5777 D BluetoothAdapterProperties: ScanMode =  20
11-25 07:24:43.929  5765  5777 D BluetoothAdapterProperties: State =  11
11-25 07:24:43.930  5765  5777 D BluetoothAdapterProperties: Setting state to 12
11-25 07:24:43.930  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-25 07:24:43.930  5765  5777 I BluetoothAdapterState: Entering OnState
11-25 07:24:43.931  3085  3097 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-25 07:24:43.932   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:43.932  5765  5781 D BluetoothAdapterProperties: Scan Mode:21
11-25 07:24:43.932  5765  5781 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 07:24:43.932  3085  3098 D BluetoothPan: onBluetoothStateChange on: true
,11-25 07:24:43.933  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-25 07:24:43.934  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:24:43.934  3085  3085 D PanProfile: Bluetooth service connected
11-25 07:24:43.934  3085  3941 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:24:43.936   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:24:43.937  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:24:43.937   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:43.937   930   930 D BluetoothA2dp: Proxy object connected
,11-25 07:24:43.937  3741  4012 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:43.938  3085  3085 D BluetoothA2dp: Proxy object connected
11-25 07:24:43.939  5633  5645 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 07:24:43.941  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:24:43.942  5633  5648 D BluetoothPan: onBluetoothStateChange on: true
11-25 07:24:43.942  5633  5645 D BluetoothMap: onBluetoothStateChange: up=true
11-25 07:24:43.942  5765  5765 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:24:43.943   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:43.943  3085  3098 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 07:24:43.943  5765  5765 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-25 07:24:43.944  3085  3941 D BluetoothMap: onBluetoothStateChange: up=true
11-25 07:24:43.945  5765  5765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:24:43.946  3085  3085 D BluetoothMap: Proxy object connected
11-25 07:24:43.946  5633  5648 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 07:24:43.946  3085  3085 D MapProfile: Bluetooth service connected
11-25 07:24:43.946  3085  3085 D BluetoothMap: getConnectedDevices()
11-25 07:24:43.946  5765  5765 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-25 07:24:43.946  3085  3098 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-25 07:24:43.948  3085  3085 D BluetoothInputDevice: Proxy object connected
,11-25 07:24:43.948  3085  3085 D HidProfile: Bluetooth service connected
,11-25 07:24:43.949   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-25 07:24:43.950  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-25 07:24:43.952  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:43.952  5633  5633 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-25 07:24:43.952  5765  5765 D ObexServerSockets: Succeed to create listening sockets 
11-25 07:24:43.952  5765  5765 D ObexServerSockets0: startAccept()
11-25 07:24:43.952  5765  5765 D ObexServerSockets0: prepareForNewConnect()
,11-25 07:24:43.954  5765  5765 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 07:24:43.955  5765  5765 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-25 07:24:43.956  5633  5633 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-25 07:24:43.956  5765  5803 D ObexServerSockets0: Accepting socket connection...
11-25 07:24:43.957  5765  5765 D BluetoothMapService: onReceive
11-25 07:24:43.957  5765  5804 D ObexServerSockets0: Accepting socket connection...
11-25 07:24:43.957  5765  5765 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 07:24:43.957  5765  5765 D BluetoothMapService: STATE_ON
,11-25 07:24:43.960  5765  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:43.961  5765  5805 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-25 07:24:43.961  5765  5805 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-25 07:24:43.964  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 07:24:43.966  5633  5633 D BluetoothA2dp: Proxy object connected
,11-25 07:24:43.969  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:24:43.970  5633  5633 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:24:43.980  5633  5633 D BluetoothPbap: Proxy object connected
,11-25 07:24:43.980  5633  5633 D PbapServerProfile: Bluetooth service connected
,11-25 07:24:43.980  3085  3085 D BluetoothPbap: Proxy object connected
,11-25 07:24:43.981  3085  3085 D PbapServerProfile: Bluetooth service connected
11-25 07:24:43.981  5765  5765 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:24:43.981  5765  5765 D ObexServerSockets0: prepareForNewConnect()
11-25 07:24:43.982  5765  5809 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:43.998  5765  5813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:43.999  5765  5813 I BtOppRfcommListener: Accept thread started.
,11-25 07:24:44.033  3741  3763 D BluetoothHeadset: Proxy object connected
,11-25 07:24:44.033   930   930 D BluetoothHeadset: Proxy object connected
11-25 07:24:44.033   930   930 D BluetoothHeadset: Proxy object connected
11-25 07:24:44.033   930   930 D BluetoothHeadset: Proxy object connected
11-25 07:24:44.033  3085  3097 D BluetoothHeadset: Proxy object connected
,11-25 07:24:44.033  3085  3085 D HeadsetProfile: Bluetooth service connected
,11-25 07:24:44.038   930   947 D BluetoothHeadset: Proxy object connected
,11-25 07:24:44.038  3741  3967 D BluetoothHeadset: Proxy object connected
,11-25 07:24:44.043   930   947 D BluetoothHeadset: Proxy object connected
,11-25 07:24:44.060  5633  5648 D BluetoothHeadset: Proxy object connected
11-25 07:24:44.061  5633  5633 D HeadsetProfile: Bluetooth service connected
,11-25 07:24:45.587   930  2943 D ConnectivityService: handlePromptUnvalidated 101
,11-25 07:24:47.863  5765  5777 D BluetoothAdapterState: Current state: ON, message: 23
,11-25 07:24:47.863  5765  5777 D BluetoothAdapterProperties: Setting state to 13
11-25 07:24:47.863  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-25 07:24:47.865  5765  5777 D BluetoothAdapterProperties: onBluetoothDisable()
,11-25 07:24:47.867  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:24:47.874  5765  5765 D BluetoothMapService: onReceive
11-25 07:24:47.874  5765  5765 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-25 07:24:47.874  5765  5765 D BluetoothMapService: STATE_TURNING_OFF
11-25 07:24:47.875  5765  5765 D BluetoothMapService: MAP Service closeService in
11-25 07:24:47.875  5765  5765 D BluetoothMapMasInstance0: MAP Service shutdown
,11-25 07:24:47.875  5765  5765 D ObexServerSockets0: shutdown(block = true)
,11-25 07:24:47.876  5765  5803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-25 07:24:47.877  5765  5765 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-25 07:24:47.877  5765  5765 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-25 07:24:47.878  5765  5804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-25 07:24:47.878  5765  5790 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-25 07:24:47.879  5765  5781 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:24:47.882  5765  5765 I BtOppRfcommListener: stopping Accept Thread
11-25 07:24:47.884  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:24:47.884  5580  5580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-25 07:24:47.885  5765  5813 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-25 07:24:47.880  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-25 07:24:47.885  5580  5580 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-25 07:24:47.885  5580  5580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-25 07:24:47.886  5765  5813 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-25 07:24:47.888  5765  5765 D HeadsetService: Received stop request...Stopping profile...
11-25 07:24:47.889  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:47.891  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:24:47.892  3741  3773 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:47.892   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:47.892   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:47.895  5633  5645 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:47.896   930   930 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:47.896  3085  3098 D BluetoothHeadset: Proxy object disconnected
11-25 07:24:47.897  5765  5765 D A2dpService: Received stop request...Stopping profile...
11-25 07:24:47.897  5765  5796 D A2dpStateMachine: Exit Disconnected: -1
11-25 07:24:47.899   930   930 D BluetoothA2dp: Proxy object disconnected
11-25 07:24:47.900  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.900  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:47.900  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:47.900  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:47.901  5765  5765 D HidService: Received stop request...Stopping profile...
11-25 07:24:47.901  5765  5765 D HidService: Stopping Bluetooth HidService
11-25 07:24:47.902  5633  5633 D HeadsetProfile: Bluetooth service disconnected
11-25 07:24:47.904  5633  5633 D DockEventReceiver: finishStartingService: stopping service
11-25 07:24:47.904  5765  5765 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-25 07:24:47.904  5765  5765 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-25 07:24:47.904  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-25 07:24:47.905  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:47.905  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:47.905  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:47.905  5765  5765 D HealthService: Received stop request...Stopping profile...
,11-25 07:24:47.905  5633  5633 D BluetoothA2dp: Proxy object disconnected
11-25 07:24:47.906  5633  5633 D BluetoothInputDevice: Proxy object disconnected
11-25 07:24:47.906  5765  5781 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-25 07:24:47.906  5633  5633 D HidProfile: Bluetooth service disconnected
11-25 07:24:47.908  5765  5765 D PanService: Received stop request...Stopping profile...
11-25 07:24:47.910  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.910  5765  5765 V BluetoothAdapterState: isTurningOn()=false
,11-25 07:24:47.910  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:47.910  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:47.910  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.910  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:47.911  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:47.911  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:47.912  5765  5765 D BluetoothMapService: Received stop request...Stopping profile...
11-25 07:24:47.912  5765  5765 D BluetoothMapService: stop()
,11-25 07:24:47.912  3085  3085 D HeadsetProfile: Bluetooth service disconnected
11-25 07:24:47.912  3085  3085 D BluetoothA2dp: Proxy object disconnected
11-25 07:24:47.912  3085  3085 D BluetoothInputDevice: Proxy object disconnected
11-25 07:24:47.912  3085  3085 D HidProfile: Bluetooth service disconnected
11-25 07:24:47.913  3085  3085 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-25 07:24:47.913  5765  5765 D BluetoothMapAppObserver: deinitObservers()
11-25 07:24:47.913  3085  3085 D PanProfile: Bluetooth service disconnected
11-25 07:24:47.913  5765  5765 D BluetoothMapAppObserver: removeReceiver()
,11-25 07:24:47.916  5633  5633 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-25 07:24:47.916  5633  5633 D PanProfile: Bluetooth service disconnected
11-25 07:24:47.916  5633  5633 D BluetoothMap: Proxy object disconnected
11-25 07:24:47.916  5633  5633 D MapProfile: Bluetooth service disconnected
11-25 07:24:47.916  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 07:24:47.916  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-25 07:24:47.916  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:24:47.917  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 07:24:47.917  5765  5765 D SapService: Received stop request...Stopping profile...
11-25 07:24:47.917  5765  5765 V SapService: stop()
11-25 07:24:47.917  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-25 07:24:47.917  5765  5788 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-25 07:24:47.917  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-25 07:24:47.917  3085  3085 D BluetoothMap: Proxy object disconnected
11-25 07:24:47.917  3085  3085 D MapProfile: Bluetooth service disconnected
11-25 07:24:47.918  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:24:47.920  5765  5765 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-25 07:24:47.920  5765  5765 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-25 07:24:47.920  5765  5781 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 07:24:47.921  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.921  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:47.921  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
,11-25 07:24:47.921  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:47.921  5765  5765 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-25 07:24:47.923  5765  5765 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-25 07:24:47.923  5765  5781 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-25 07:24:47.923  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.924  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:47.924  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:47.924  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:47.924  5765  5765 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-25 07:24:47.924  5765  5765 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-25 07:24:47.927  5765  5765 D BluetoothMapService: MAP Service closeService in
11-25 07:24:47.927  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.927  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:47.927  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:47.927  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:47.928  5765  5765 D BluetoothMapService: cleanup()
,11-25 07:24:47.928  5765  5765 D BluetoothMapService: MAP Service closeService in
,11-25 07:24:47.929  3085  3085 D BluetoothPbap: Proxy object disconnected
11-25 07:24:47.929  3085  3085 D PbapServerProfile: Bluetooth service disconnected
11-25 07:24:47.929  5633  5633 D BluetoothPbap: Proxy object disconnected
11-25 07:24:47.929  5633  5633 D PbapServerProfile: Bluetooth service disconnected
11-25 07:24:47.930  5765  5765 V BluetoothAdapterState: isTurningOff()=true
11-25 07:24:47.930  5765  5765 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:47.930  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:47.930  5765  5765 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:24:47.932  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-25 07:24:47.932  5765  5777 D BluetoothAdapterProperties: Setting state to 15
11-25 07:24:47.932  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-25 07:24:47.932  5765  5777 I BluetoothAdapterState: Entering BleOnState
11-25 07:24:47.932  3085  3941 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-25 07:24:47.935  5633  5645 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:47.935   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:47.936  3085  3097 D BluetoothPan: onBluetoothStateChange on: false
11-25 07:24:47.936  3085  3098 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:24:47.937   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:24:47.937   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:47.937  3741  4012 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:47.938  5633  5648 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 07:24:47.939  5633  5818 D BluetoothPan: onBluetoothStateChange on: false
,11-25 07:24:47.940  5633  5645 D BluetoothA2dp: onBluetoothStateChange: up=false
11-25 07:24:47.940  5633  5648 D BluetoothMap: onBluetoothStateChange: up=false
11-25 07:24:47.941   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-25 07:24:47.941  3085  3941 D BluetoothPbap: onBluetoothStateChange: up=false
11-25 07:24:47.941  3085  3097 D BluetoothMap: onBluetoothStateChange: up=false
11-25 07:24:47.942  5633  5818 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 07:24:47.942  3085  3098 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-25 07:24:47.943  5765  5777 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-25 07:24:47.943  5765  5777 D BluetoothAdapterProperties: Setting state to 16
11-25 07:24:47.943  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-25 07:24:47.944  5765  5777 D BluetoothAdapterProperties: onBleDisable
11-25 07:24:47.946  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:24:47.946  5765  5777 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:24:47.946  5765  5778 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-25 07:24:47.947  5765  5781 D BluetoothAdapterProperties: Scan Mode:20
11-25 07:24:47.948  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-25 07:24:47.949  5580  5580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:47.948  5765  5788 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-25 07:24:47.955  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:24:47.955  5633  5633 D DockEventReceiver: finishStartingService: stopping service
11-25 07:24:47.958  5765  5788 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-25 07:24:48.169  5765  5781 I bt_hci  : shut_down
,11-25 07:24:48.180  5765  5785 D bt_hwcfg: hw_epilog_process
,11-25 07:24:48.180  5765  5785 I bt_vendor: low_power_mode_cb
,11-25 07:24:48.183  5765  5785 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-25 07:24:48.183  5765  5785 I bt_vendor: epilog_cb
11-25 07:24:48.184  5765  5785 I bt_hci  : epilog_finished_callback
,11-25 07:24:48.189  5765  5781 I bt_hci_h4: hal_close
,11-25 07:24:48.190  5765  5781 I bt_userial_vendor: device fd = 54 close
,11-25 07:24:48.310  5765  5778 D bt_stack_manager: event_shut_down_stack finished.
,11-25 07:24:48.311  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-25 07:24:48.316  5765  5777 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-25 07:24:48.316  5765  5765 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 07:24:48.318  5765  5765 D BtGatt.GattService: Received stop request...Stopping profile...
,11-25 07:24:48.318  5765  5765 D BtGatt.GattService: stop()
11-25 07:24:48.318  5765  5765 D BtGatt.AdvertiseManager: advertise clients cleared
11-25 07:24:48.322  5765  5765 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:24:48.322  5765  5765 V BluetoothAdapterState: isTurningOn()=false
,11-25 07:24:48.322  5765  5765 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:48.323  5765  5765 V BluetoothAdapterState: isBleTurningOff()=true
11-25 07:24:48.323  5765  5777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-25 07:24:48.323  5765  5777 D BluetoothAdapterProperties: Setting state to 10
,11-25 07:24:48.324  5765  5777 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-25 07:24:48.325  5765  5777 I BluetoothAdapterState: Entering OffState
,11-25 07:24:48.328   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-25 07:24:48.343  5765  5765 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-25 07:24:48.343  5765  5765 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-25 07:24:48.343  5765  5765 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-25 07:24:48.346  5765  5778 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-25 07:24:48.353  5765  5765 I art     : System.exit called, status: 0
,11-25 07:24:48.353  5765  5765 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-25 07:24:48.382   930  3815 I ActivityManager: Process com.android.bluetooth (pid 5765) has died
,11-25 07:24:49.498   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:50.499   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:51.500   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:52.501   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:52.861  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:24:52.861  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 07:24:52.870  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:52.870  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93995a3 removed from the list
11-25 07:24:52.870  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:52.872  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:24:52.873  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@735a81e added. We now have 4 listener(s)
11-25 07:24:52.873  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:24:52.874  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:24:52.875  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@735a81e removed from the list
11-25 07:24:52.875  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:24:52.876  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:24:52.876  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45e8ff added. We now have 4 listener(s)
11-25 07:24:52.877  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:24:53.502   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:24:54.502   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-25 07:24:57.887  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-25 07:24:57.920   930   947 I ActivityManager: Start proc 5824:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-25 07:24:58.006  5824  5824 D AdapterServiceConfig: Adding HeadsetService
,11-25 07:24:58.006  5824  5824 D AdapterServiceConfig: Adding A2dpService
11-25 07:24:58.007  5824  5824 D AdapterServiceConfig: Adding HidService
,11-25 07:24:58.007  5824  5824 D AdapterServiceConfig: Adding HealthService
11-25 07:24:58.007  5824  5824 D AdapterServiceConfig: Adding PanService
11-25 07:24:58.007  5824  5824 D AdapterServiceConfig: Adding GattService
,11-25 07:24:58.007  5824  5824 D AdapterServiceConfig: Adding BluetoothMapService
11-25 07:24:58.007  5824  5824 D AdapterServiceConfig: Adding SapService
,11-25 07:24:58.018   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b8d6743:true
,11-25 07:24:58.018  5824  5824 D BluetoothAdapterState: make() - Creating AdapterState
,11-25 07:24:58.021  5824  5824 I bt_bluedroid: init
11-25 07:24:58.021  5824  5836 I BluetoothAdapterState: Entering OffState
,11-25 07:24:58.023  5824  5837 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-25 07:24:58.024  5824  5837 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-25 07:24:58.024  5824  5837 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-25 07:24:58.024  5824  5837 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-25 07:24:58.025  5824  5824 I bt_bluedroid: get_profile_interface socket
,11-25 07:24:58.026  5824  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-25 07:24:58.027  5824  5824 I bt_bluedroid: get_profile_interface sdp
,11-25 07:24:58.028  5824  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:24:58.031  5824  5835 I bt_bluedroid: config_hci_snoop_log
,11-25 07:24:58.032   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-25 07:24:58.036  5824  5836 D BluetoothAdapterState: Current state: OFF, message: 0
,11-25 07:24:58.036  5824  5836 D BluetoothAdapterProperties: Setting state to 14
11-25 07:24:58.036  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-25 07:24:58.038  5824  5836 D BluetoothBondStateMachine: make
,11-25 07:24:58.040  5824  5841 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-25 07:24:58.042  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
,11-25 07:24:58.043  5824  5824 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-25 07:24:58.046  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:58.046  5824  5824 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-25 07:24:58.047  5824  5824 D BtGatt.GattService: Received start request. Starting profile...
11-25 07:24:58.047  5824  5824 D BtGatt.GattService: start()
11-25 07:24:58.047  5824  5824 I bt_bluedroid: get_profile_interface gatt
,11-25 07:24:58.048  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:58.048  5824  5824 D BtGatt.AdvertiseManager: advertise manager created
,11-25 07:24:58.054  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:24:58.054  5824  5824 V BluetoothAdapterState: isTurningOn()=false
11-25 07:24:58.054  5824  5824 V BluetoothAdapterState: isBleTurningOn()=true
11-25 07:24:58.054  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:58.054  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-25 07:24:58.055  5824  5836 I bt_bluedroid: bt_bluedroid
,11-25 07:24:58.055  5824  5837 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-25 07:24:58.056  5824  5837 I bt_hci  : start_up
,11-25 07:24:58.060  5824  5837 I bt_vendor: alloc value 0xf423d871
,11-25 07:24:58.060  5824  5837 I bt_vendor: init
11-25 07:24:58.060  5824  5837 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-25 07:24:58.060  5824  5837 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-25 07:24:58.170  5824  5837 D bt_hci  : start_up starting async portion
,11-25 07:24:58.171  5824  5844 I bt_hci  : event_finish_startup
11-25 07:24:58.171  5824  5844 I bt_hci_h4: hal_open
,11-25 07:24:58.171  5824  5844 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-25 07:24:58.168  5845  5845 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:24:58.172  5824  5844 I bt_userial_vendor: device fd = 54 open
,11-25 07:24:58.187  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:24:58.191  5824  5844 D bt_hwcfg: Chipset BCM4358A3
,11-25 07:24:58.191  5824  5844 D bt_hwcfg: Target name = [BCM4358A3]
11-25 07:24:58.191  5824  5844 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-25 07:24:58.704  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-25 07:24:58.704  5824  5844 D bt_hwcfg: Settlement delay -- 100 ms
11-25 07:24:58.704  5824  5844 I bt_hwcfg: Setting fw settlement delay to 100 
,11-25 07:24:58.839  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-25 07:24:58.839  5824  5844 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-25 07:24:58.841  5824  5844 I bt_hwcfg: vendor lib fwcfg completed
11-25 07:24:58.841  5824  5844 I bt_vendor: firmware callback
11-25 07:24:58.841  5824  5844 I bt_hci  : firmware_config_callback
,11-25 07:24:58.849  5824  5847 I bt_btu  : btu_task pending for preload complete event
,11-25 07:24:58.849  5824  5847 I bt_btu_task: Bluetooth chip preload is complete
11-25 07:24:58.849  5824  5847 I bt_btu  : btu_task received preload complete event
,11-25 07:24:58.854  5824  5847 I         : BTE_InitTraceLevels -- TRC_HCI
,11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_AVDT
11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_AVRC
11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_A2D
,11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_BNEP
11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTM
11-25 07:24:58.855  5824  5847 I         : BTE_InitTraceLevels -- TRC_GAP
11-25 07:24:58.856  5824  5847 I         : BTE_InitTraceLevels -- TRC_PAN
11-25 07:24:58.856  5824  5847 I         : BTE_InitTraceLevels -- TRC_SDP
,11-25 07:24:58.856  5824  5847 I         : BTE_InitTraceLevels -- TRC_GATT
11-25 07:24:58.856  5824  5847 I         : BTE_InitTraceLevels -- TRC_SMP
11-25 07:24:58.856  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-25 07:24:58.856  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-25 07:24:58.949  5824  5847 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41bb549
,11-25 07:24:58.950  5824  5847 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41bb549 
,11-25 07:24:58.973  5824  5840 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-25 07:24:58.976  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-25 07:24:58.976  5824  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-25 07:24:58.979  5824  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-25 07:24:58.981  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
,11-25 07:24:58.981  5824  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
11-25 07:24:58.982  5824  5840 D bt_hci  : do_postload posting postload work item
11-25 07:24:58.982  5824  5844 I bt_hci  : event_postload
11-25 07:24:58.982  5824  5844 I bt_vendor: sco_config_cb
11-25 07:24:58.982  5824  5844 I bt_hci  : sco_config_callback postload finished.
,11-25 07:24:58.984  5824  5840 D bt_bte_conf: Device ID record 1 : primary
,11-25 07:24:58.984  5824  5840 D bt_bte_conf:   vendorId            = 000f
11-25 07:24:58.984  5824  5840 D bt_bte_conf:   vendorIdSource      = 0001
11-25 07:24:58.984  5824  5840 D bt_bte_conf:   product             = 1200
11-25 07:24:58.984  5824  5840 D bt_bte_conf:   version             = 1436
11-25 07:24:58.984  5824  5840 D bt_bte_conf:   clientExecutableURL = 
11-25 07:24:58.984  5824  5840 D bt_bte_conf:   serviceDescription  = 
11-25 07:24:58.985  5824  5840 D bt_bte_conf:   documentationURL    = 
11-25 07:24:58.985  5824  5840 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-25 07:24:58.985  5824  5837 D bt_stack_manager: event_start_up_stack finished
11-25 07:24:58.986  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-25 07:24:58.986  5824  5836 D BluetoothAdapterProperties: Setting state to 15
11-25 07:24:58.987  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-25 07:24:58.988  5824  5836 I BluetoothAdapterState: Entering BleOnState
,11-25 07:24:58.992  5824  5844 I bt_vendor: low_power_mode_cb
,11-25 07:24:58.992  5824  5836 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-25 07:24:58.992  5824  5836 D BluetoothAdapterProperties: Setting state to 11
11-25 07:24:58.992  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-25 07:24:58.997  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:58.998  5824  5824 D HeadsetService: Received start request. Starting profile...
11-25 07:24:59.002  5824  5824 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-25 07:24:59.002  5824  5824 D HeadsetStateMachine: make
,11-25 07:24:59.012  5824  5824 D HeadsetStateMachine: max_hf_connections = 1
,11-25 07:24:59.013  5824  5824 I bt_bluedroid: get_profile_interface handsfree
11-25 07:24:59.013  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-25 07:24:59.013  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
11-25 07:24:59.014  5824  5840 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-25 07:24:59.017  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:59.017  5824  5824 D A2dpService: Received start request. Starting profile...
,11-25 07:24:59.018  5824  5824 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-25 07:24:59.018  5824  5824 I bt_bluedroid: get_profile_interface avrcp
,11-25 07:24:59.024  5824  5824 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-25 07:24:59.024  5824  5824 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-25 07:24:59.024  5824  5824 D A2dpStateMachine: make
,11-25 07:24:59.026  5824  5824 I bt_bluedroid: get_profile_interface a2dp
,11-25 07:24:59.027  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-25 07:24:59.028  5824  5854 D A2dpStateMachine: Enter Disconnected: -2
,11-25 07:24:59.030  5824  5824 I BluetoothHidServiceJni: classInitNative: succeeds
,11-25 07:24:59.030  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:59.031  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-25 07:24:59.031  5824  5824 D HidService: Received start request. Starting profile...
11-25 07:24:59.031  5824  5824 I bt_bluedroid: get_profile_interface hidhost
11-25 07:24:59.031  5824  5840 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf419c56d
11-25 07:24:59.031  5824  5824 D HidService: setHidService(): set to: null
11-25 07:24:59.031  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-25 07:24:59.032  5824  5824 I BluetoothHealthServiceJni: classInitNative: succeeds
11-25 07:24:59.032  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:59.033  5824  5824 D HealthService: Received start request. Starting profile...
,11-25 07:24:59.034  5824  5824 I bt_bluedroid: get_profile_interface health
,11-25 07:24:59.037  5824  5824 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-25 07:24:59.037  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:59.038  5824  5824 D PanService: Received start request. Starting profile...
,11-25 07:24:59.038  5824  5824 D BluetoothPanServiceJni: initializeNative(L110): pan
11-25 07:24:59.038  5824  5824 I bt_bluedroid: get_profile_interface pan
11-25 07:24:59.038  5824  5840 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-25 07:24:59.040  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:24:59.041  5824  5824 D BluetoothMapService: Received start request. Starting profile...
11-25 07:24:59.041  5824  5824 D BluetoothMapService: start()
,11-25 07:24:59.044  5824  5824 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-25 07:24:59.045  5824  5824 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-25 07:24:59.045  5824  5824 D BluetoothMapAppObserver: createReceiver()
,11-25 07:24:59.046  5824  5824 D BluetoothMapAppObserver: initObservers()
11-25 07:24:59.047  5824  5824 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-25 07:24:59.054  5824  5824 V SapService: SapBinder()
11-25 07:24:59.054  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
,11-25 07:24:59.055  5824  5824 D SapService: Received start request. Starting profile...
11-25 07:24:59.055  5824  5824 V SapService: start()
,11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.056  5824  5852 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.056  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:59.057  5824  5824 V BluetoothAdapterState: isTurningOff()=false
11-25 07:24:59.058  5824  5824 V BluetoothAdapterState: isTurningOn()=true
11-25 07:24:59.058  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.058  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:59.059  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,11-25 07:24:59.059  5824  5824 V BluetoothAdapterState: isTurningOn()=true
,11-25 07:24:59.059  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
11-25 07:24:59.059  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
11-25 07:24:59.059  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-25 07:24:59.059  5824  5836 D BluetoothAdapterProperties: ScanMode =  20
11-25 07:24:59.059  5824  5836 D BluetoothAdapterProperties: State =  11
11-25 07:24:59.061  5824  5836 D BluetoothAdapterProperties: Setting state to 12
11-25 07:24:59.061  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-25 07:24:59.062  5824  5840 D BluetoothAdapterProperties: Scan Mode:21
11-25 07:24:59.062  5824  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-25 07:24:59.062  3085  3097 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:59.063  5824  5836 I BluetoothAdapterState: Entering OnState
11-25 07:24:59.063  5633  5648 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:59.063   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:59.063  3085  3098 D BluetoothPan: onBluetoothStateChange on: true
11-25 07:24:59.065  3085  3941 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:24:59.067  3085  3085 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:24:59.067  3085  3085 D PanProfile: Bluetooth service connected
,11-25 07:24:59.068   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:24:59.068   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:59.068  3741  3763 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:59.069   930   930 D BluetoothA2dp: Proxy object connected
,11-25 07:24:59.069  3085  3085 D BluetoothA2dp: Proxy object connected
11-25 07:24:59.069  5633  5818 D BluetoothPbap: onBluetoothStateChange: up=true
,11-25 07:24:59.073  5824  5824 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-25 07:24:59.074  5824  5824 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-25 07:24:59.075  5824  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:59.077  5824  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:59.079  5824  5824 D ObexServerSockets: Succeed to create listening sockets 
,11-25 07:24:59.079  5824  5824 D ObexServerSockets0: startAccept()
11-25 07:24:59.079  5824  5824 D ObexServerSockets0: prepareForNewConnect()
11-25 07:24:59.081  5824  5824 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-25 07:24:59.081  5824  5824 D BluetoothSdpJni: SDP Create record success - handle: 0
11-25 07:24:59.081  5824  5860 D ObexServerSockets0: Accepting socket connection...
,11-25 07:24:59.081  5824  5861 D ObexServerSockets0: Accepting socket connection...
11-25 07:24:59.082  5633  5645 D BluetoothPan: onBluetoothStateChange on: true
11-25 07:24:59.083  5633  5818 D BluetoothA2dp: onBluetoothStateChange: up=true
11-25 07:24:59.085  5633  5645 D BluetoothMap: onBluetoothStateChange: up=true
11-25 07:24:59.087   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-25 07:24:59.087  3085  3097 D BluetoothPbap: onBluetoothStateChange: up=true
11-25 07:24:59.089  3085  3941 D BluetoothMap: onBluetoothStateChange: up=true
11-25 07:24:59.090  3085  3085 D BluetoothMap: Proxy object connected
,11-25 07:24:59.090  3085  3085 D MapProfile: Bluetooth service connected
11-25 07:24:59.090  5633  5818 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 07:24:59.090  3085  3085 D BluetoothMap: getConnectedDevices()
,11-25 07:24:59.092  5633  5633 D BluetoothPan: BluetoothPAN Proxy object connected
11-25 07:24:59.092  5633  5633 D PanProfile: Bluetooth service connected
11-25 07:24:59.092  5633  5633 D BluetoothA2dp: Proxy object connected
11-25 07:24:59.094  3085  3098 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-25 07:24:59.096  3085  3085 D BluetoothInputDevice: Proxy object connected
11-25 07:24:59.096  3085  3085 D HidProfile: Bluetooth service connected
11-25 07:24:59.096  5633  5633 D BluetoothMap: Proxy object connected
11-25 07:24:59.096  5633  5633 D MapProfile: Bluetooth service connected
11-25 07:24:59.096  5633  5633 D BluetoothMap: getConnectedDevices()
11-25 07:24:59.097   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-25 07:24:59.098  5824  5824 D BluetoothMapService: onReceive
11-25 07:24:59.098  5824  5824 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-25 07:24:59.098  5824  5824 D BluetoothMapService: STATE_ON
11-25 07:24:59.099  5633  5633 D BluetoothInputDevice: Proxy object connected
11-25 07:24:59.099  5633  5633 D HidProfile: Bluetooth service connected
11-25 07:24:59.101  5824  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:59.102  5824  5864 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-25 07:24:59.103  5824  5864 D BluetoothSdpJni: SDP Create record success - handle: 1
11-25 07:24:59.107  5633  5633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-25 07:24:59.112  5633  5633 D DockEventReceiver: finishStartingService: stopping service
,11-25 07:24:59.116  3550  3550 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-25 07:24:59.124  5633  5633 D BluetoothPbap: Proxy object connected
,11-25 07:24:59.124  3085  3085 D BluetoothPbap: Proxy object connected
11-25 07:24:59.124  3085  3085 D PbapServerProfile: Bluetooth service connected
11-25 07:24:59.125  5633  5633 D PbapServerProfile: Bluetooth service connected
11-25 07:24:59.125  5824  5824 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-25 07:24:59.125  5824  5824 D ObexServerSockets0: prepareForNewConnect()
,11-25 07:24:59.139  5824  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:59.148  5824  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-25 07:24:59.150  5824  5872 I BtOppRfcommListener: Accept thread started.
,11-25 07:24:59.164  3741  3967 D BluetoothHeadset: Proxy object connected
,11-25 07:24:59.164   930   947 D BluetoothHeadset: Proxy object connected
11-25 07:24:59.164   930   930 D BluetoothHeadset: Proxy object connected
11-25 07:24:59.164   930   930 D BluetoothHeadset: Proxy object connected
11-25 07:24:59.165  5633  5645 D BluetoothHeadset: Proxy object connected
11-25 07:24:59.165   930   930 D BluetoothHeadset: Proxy object connected
11-25 07:24:59.165  3085  3941 D BluetoothHeadset: Proxy object connected
11-25 07:24:59.165  3085  3085 D HeadsetProfile: Bluetooth service connected
11-25 07:24:59.167  5633  5633 D HeadsetProfile: Bluetooth service connected
11-25 07:24:59.168   930   947 D BluetoothHeadset: Proxy object connected
,11-25 07:24:59.169  3741  3773 D BluetoothHeadset: Proxy object connected
,11-25 07:24:59.187   930   947 D BluetoothHeadset: Proxy object connected
,11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-25 07:25:02.905  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-25 07:25:02.910  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-25 07:25:02.911  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:02.911  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45e8ff removed from the list
,11-25 07:25:02.911  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:25:02.913  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:02.913  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@efc16cc added. We now have 4 listener(s)
,11-25 07:25:02.913  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:25:02.918   930  3382 D WifiService: setWifiEnabled: false pid=5580, uid=10077
11-25 07:25:02.918   930  3382 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:25:07.929  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-25 07:25:07.931   930  3764 D WifiService: setWifiEnabled: true pid=5580, uid=10077
11-25 07:25:07.931   930  3764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-25 07:25:07.940   509   927 D SoftapController: Softap fwReload - Ok
,11-25 07:25:07.945   509   927 D CommandListener: Setting iface cfg
,11-25 07:25:07.945   509   927 D CommandListener: Trying to bring down wlan0
,11-25 07:25:07.948   509   927 D CommandListener: Clearing all IP addresses on wlan0
,11-25 07:25:07.953   930  2941 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-25 07:25:08.639   930  2941 D wifi    : set interface wlan0 flags (UP)
,11-25 07:25:08.640   930  2941 I WifiHAL : Initializing wifi
11-25 07:25:08.640   930  2941 I WifiHAL : Creating socket
,11-25 07:25:08.647   930  2941 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-25 07:25:08.647   930  2941 D wifi    : Did set static halHandle = 0x7f58388180
11-25 07:25:08.647   930  2941 D wifi    : halHandle = 0x7f58388180, mVM = 0x7f74a0d140, mCls = 0x1916
,11-25 07:25:08.647   930  2941 D wifi    : array field set
,11-25 07:25:08.647   930  2941 I WifiNative-HAL: interface[0] = wlan0
11-25 07:25:08.648   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-25 07:25:08.650   930  5877 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=546940944768
,11-25 07:25:08.650   930  5877 D wifi    : waitForHalEvents called, vm = 0x7f74a0d140, obj = 0x1916, env = 0x7f5caa9780
,11-25 07:25:08.710  5878  5878 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-25 07:25:08.730  5878  5878 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:25:08.748  5878  5878 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-25 07:25:08.748  5878  5878 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-25 07:25:08.751   930  2941 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-25 07:25:08.773   930  2941 D WifiConfigStore: Loading config and enabling all networks 
,11-25 07:25:08.789   930  2941 D WifiConfigStore: loaded 0 passpoint configs
,11-25 07:25:08.789   930  2941 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-25 07:25:08.790   930  2941 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-25 07:25:08.791   930  2941 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-25 07:25:08.792   930  2941 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-25 07:25:08.792   930  2941 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-25 07:25:08.793   930  2941 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-25 07:25:08.793   930  2941 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-25 07:25:08.796   930  2941 D WifiNative-HAL: Setting external_sim to 1
,11-25 07:25:08.797   930  2941 D wifi    : setting dfs flag to true, 0x7f583f3900
11-25 07:25:08.797  4380  4380 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-25 07:25:08.797   930  2941 D WifiStateMachine: Setting OUI to DA-A1-19
11-25 07:25:08.797   930  2941 D wifi    : setting scan oui 0x7f583f3900
11-25 07:25:08.797   930  2941 D WifiHAL : Sending mac address OUI
,11-25 07:25:08.801   930  2941 E native  : do suspend false
,11-25 07:25:08.809   930  2941 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-25 07:25:08.809   930   930 D RttService: SCAN_AVAILABLE : 3
11-25 07:25:08.809   509   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-25 07:25:08.809   930  3050 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-25 07:25:08.810   509   927 D CommandListener: Setting iface cfg
,11-25 07:25:08.815   930  2937 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-25 07:25:08.815   930  2937 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-25 07:25:08.825   930  2937 D WifiNative-HAL: p2pGetDeviceAddress
,11-25 07:25:08.826   930  2937 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-25 07:25:08.832   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163850 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-25 07:25:09.504   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:25:10.505   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:25:11.506   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:25:11.877  5878  5878 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:25:11.882  5878  5878 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:25:11.886  5878  5878 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-25 07:25:11.935   930  2941 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-25 07:25:11.936   930  2941 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-25 07:25:11.937   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:25:11.948   930  2941 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-25 07:25:11.983   930  2941 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-25 07:25:11.984  5878  5878 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-25 07:25:12.421  5878  5878 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-25 07:25:12.456  5878  5878 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-25 07:25:12.457  5878  5878 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-25 07:25:12.465   930  2941 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-25 07:25:12.466   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:25:12.466   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-25 07:25:12.483   930  2941 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-25 07:25:12.496   509   927 D CommandListener: Setting iface cfg
,11-25 07:25:12.502   930  2941 D WifiStateMachine: Start Dhcp Watchdog 3
,11-25 07:25:12.507   537   537 I ServiceManager: Waiting for service AtCmdFwd...
11-25 07:25:12.507   930  5883 D DhcpClient: Receive thread started
,11-25 07:25:12.512   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:12.513   930  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-25 07:25:12.513   930  2943 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-25 07:25:12.593   930  2941 E native  : do suspend false
,11-25 07:25:12.605   930  5882 D DhcpClient: Broadcasting DHCPDISCOVER
,11-25 07:25:12.622   930  5883 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-25 07:25:12.623   930  5882 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-25 07:25:12.624   930  5882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-25 07:25:12.638   930  5883 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-25 07:25:12.639   930  5882 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-25 07:25:12.641   509   927 D CommandListener: Setting iface cfg
,11-25 07:25:12.645   930  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-25 07:25:12.653   930  5882 D DhcpClient: Scheduling renewal in 86399s
,11-25 07:25:12.662   930  2941 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-25 07:25:12.664   930  2941 D WifiConfigStore: No blacklist allowed without epno enabled
,11-25 07:25:12.665   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-25 07:25:12.667   930  2943 D ConnectivityService: Adding iface wlan0 to network 102
11-25 07:25:12.674   930  2941 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-25 07:25:12.716   930  2943 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-25 07:25:12.716   930  2943 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-25 07:25:12.718   930  2943 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-25 07:25:12.721   930  2943 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-25 07:25:12.723   930  2943 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-25 07:25:12.731   930  2943 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:12.735   930  2943 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-25 07:25:12.735   930  2943 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-25 07:25:12.735   930  2943 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-25 07:25:12.735   930  2943 D ConnectivityService:    accepting network in place of null
11-25 07:25:12.735   930  2941 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-25 07:25:12.736   930  2941 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-25 07:25:12.736   930  2943 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-25 07:25:12.747   930  5881 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167765, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-25 07:25:12.758   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:25:12.778   509   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-25 07:25:12.781   930  2943 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-25 07:25:12.781  3697  3858 W QCNEJ   : |CORE| network available: 102
11-25 07:25:12.781   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:25:12.783   930  2943 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:12.784  3697  3858 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-25 07:25:12.785  3697  3858 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-25 07:25:12.785  3697  3858 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-25 07:25:12.786   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-25 07:25:12.805  5007  5020 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-25 07:25:12.805  5007  5020 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-25 07:25:12.805  5007  5020 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-25 07:25:12.806  5007  5020 E SarControlService: no key has been found,reset the power
11-25 07:25:12.806  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-25 07:25:12.806  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-25 07:25:12.806  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-25 07:25:12.806  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:25:12.806  5033  5033 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-25 07:25:12.808  5007  5045 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-25 07:25:12.808  5007  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-25 07:25:12.808  5007  5045 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-25 07:25:12.808  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-25 07:25:12.808  5033  5033 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-25 07:25:12.810  4035  4035 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-25 07:25:12.814  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000f003000000000000ffffffff]
,11-25 07:25:12.814  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-25 07:25:12.814  5033  5047 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-25 07:25:12.814  5033  5047 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@addda5 HexData = [00000000f103000000000000ffffffff]
11-25 07:25:12.814  5033  5047 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-25 07:25:12.814  5033  5047 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,11-25 07:25:12.815  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:25:12.815  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-25 07:25:12.816  4035  4035 D SystemUpdateService: onCreate
11-25 07:25:12.817  5033  5033 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-25 07:25:12.817  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-25 07:25:12.820  4035  4035 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-25 07:25:12.843  4035  4035 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-25 07:25:12.854  4035  5893 I SystemUpdateService: active receiver: enabled
,11-25 07:25:12.862  4035  5361 I iu.UploadsManager: num queued entries: 0
,11-25 07:25:12.862  4035  5361 I iu.UploadsManager: num updated entries: 0
11-25 07:25:12.863  4035  5361 I iu.SyncManager: NEXT; no task
,11-25 07:25:12.865   930  5880 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-25 07:25:12.867  4035  5893 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-25 07:25:12.868  4035  4035 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-25 07:25:12.871  4035  4035 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-25 07:25:12.874  5365  5365 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-25 07:25:12.879  5365  5365 D SprintDMHelper: simOperator: 
11-25 07:25:12.879  5365  5365 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-25 07:25:12.880  4035  5893 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-25 07:25:12.880  4035  5893 I SystemUpdateService: now status is 0 (complete)
11-25 07:25:12.881  4035  5893 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-25 07:25:12.881  4035  5893 I SystemUpdateService: file has been verified
,11-25 07:25:12.891  4035  5893 I SystemUpdateService: OTA package size = 21989297
,11-25 07:25:12.915  3550  5903 I VacuumService: Vacuum at: now=1480076712915 tag=VacuumService
,11-25 07:25:12.918  4035  5893 I SystemUpdateService: showing system update notification
,11-25 07:25:12.936  4035  4035 D SystemUpdateService: onDestroy
,11-25 07:25:12.939  3550  5906 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-25 07:25:12.946  5580  5626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-25 07:25:12.949  5580  5626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-25 07:25:12.949  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:12.949  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@efc16cc removed from the list
11-25 07:25:12.949  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
,11-25 07:25:12.952  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-25 07:25:12.952  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-25 07:25:12.954  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4622159 Bundle[{}]
11-25 07:25:12.954  5580  5626 I io.jxcore.node.LifeCycleMonitor: start: OK
11-25 07:25:12.955  5580  5626 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-25 07:25:12.955  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-25 07:25:12.955  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-25 07:25:12.956  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-25 07:25:12.956  5580  5626 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-25 07:25:12.963  5580  5626 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,11-25 07:25:12.964  5580  5626 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-25 07:25:12.964  5580  5626 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,11-25 07:25:12.966  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 07:25:12.966  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e100d15 added. We now have 3 listener(s)
,11-25 07:25:12.968  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:25:12.968  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:12.968  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:12.968  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:12.968  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@410282a added. We now have 4 listener(s)
11-25 07:25:12.968  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:12.969  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:25:12.970  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-25 07:25:12.970  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19a161b added. We now have 4 listener(s)
,11-25 07:25:12.971  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:25:12.972  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:12.972  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:12.972  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:12.972  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@539d3b8 added. We now have 5 listener(s)
11-25 07:25:12.972  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:12.972  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:25:12.972  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:25:12.972  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:25:12.972  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:12.972  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:12.972  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:12.972  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e100d15 removed from the list
11-25 07:25:12.972  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:12.973  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@410282a removed from the list
,11-25 07:25:12.973  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:25:12.973  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.973  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:12.974  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:12.974  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.974  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.974  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:12.974  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:12.974  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:12.974  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@410282a not in the list
11-25 07:25:12.975  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.975  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.976  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:12.976  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.976  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.976  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:12.976  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:12.976  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:12.976  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@539d3b8 removed from the list
11-25 07:25:12.976  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:12.976  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:12.976  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:12.976  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19a161b removed from the list
11-25 07:25:12.977  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:12.977  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@716591 added. We now have 3 listener(s)
11-25 07:25:12.978  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:25:12.978  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:12.978  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:12.978  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:12.978  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c609cf6 added. We now have 4 listener(s)
,11-25 07:25:12.978  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:12.979  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:25:12.980  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:12.980  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139f8f7 added. We now have 4 listener(s)
,11-25 07:25:12.981  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:25:12.982  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:12.982  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:12.982  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:12.982  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5947364 added. We now have 5 listener(s)
11-25 07:25:12.982  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:12.982  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 07:25:12.982  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:25:12.982  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:25:12.983  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:25:12.983  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:25:12.984  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-25 07:25:12.985  3550  5904 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-25 07:25:12.988  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 07:25:12.988  3550  5904 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-25 07:25:12.988  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:25:12.988  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:25:12.992  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.992  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:25:12.993  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:25:12.993  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:25:12.993  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:25:12.996  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.996  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-25 07:25:12.996  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:25:12.996  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:25:12.996  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:25:12.996  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:12.997  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:12.999  5824  5863 D BtGatt.GattService: registerClient() - UUID=0c7ff30e-2c59-4e66-bf24-1a895bb54c9e
11-25 07:25:13.000  5824  5840 D BtGatt.GattService: onClientRegistered() - UUID=0c7ff30e-2c59-4e66-bf24-1a895bb54c9e, clientIf=5
11-25 07:25:13.000  5580  5707 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 07:25:13.001  5824  5859 D BtGatt.GattService: start scan with filters
,11-25 07:25:13.003  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-25 07:25:13.003  5824  5843 D BtGatt.ScanManager: handling starting scan
11-25 07:25:13.003  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.004  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:25:13.004  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.004  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-25 07:25:13.004  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:25:13.004  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.004  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:25:13.004  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-25 07:25:13.004  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.004  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.004  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.004  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.005  5824  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@64d99d2
11-25 07:25:13.005  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:25:13.005  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.009  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.009  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:25:13.009  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.009  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.009  5580  5626 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-25 07:25:13.009  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.009  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:25:13.010  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-25 07:25:13.010  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-25 07:25:13.010  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:25:13.010  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.010  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-25 07:25:13.011  5824  5840 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 07:25:13.012  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.012  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.012  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.012  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.012  5824  5843 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 07:25:13.012  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:25:13.012  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.012  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:25:13.012  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.013  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:13.013  5824  5863 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 07:25:13.014  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-25 07:25:13.015  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:13.015  5824  5834 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:25:13.016  5824  5835 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:25:13.016  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.017  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.017  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.017  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:25:13.017  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:25:13.017  5824  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:25:13.017  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:25:13.017  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:25:13.017  5824  5843 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:25:13.017  5824  5843 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:25:13.017  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.020  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.020  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:25:13.020  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.020  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.021  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:25:13.021  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:25:13.021  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.021  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:25:13.021  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.021  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.022  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:25:13.022  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:25:13.022  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:25:13.023  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.023  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.023  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.023  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@716591 removed from the list
11-25 07:25:13.023  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.023  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c609cf6 removed from the list
11-25 07:25:13.023  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:25:13.023  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.023  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.023  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.023  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.023  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.024  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.024  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.024  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.024  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.024  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.024  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-25 07:25:13.024  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c609cf6 not in the list
11-25 07:25:13.024  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.024  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.025  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.025  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.025  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.025  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.026  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.026  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.026  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5947364 removed from the list
11-25 07:25:13.026  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.026  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-25 07:25:13.026  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.026  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139f8f7 removed from the list
11-25 07:25:13.026  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:13.026  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6235c9 added. We now have 3 listener(s)
11-25 07:25:13.027  5824  5840 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:25:13.027  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.027  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:25:13.027  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:13.027  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:13.028  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:13.028  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8aa54ce added. We now have 4 listener(s)
11-25 07:25:13.028  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-25 07:25:13.029  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-25 07:25:13.030  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:13.030  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb10fef added. We now have 4 listener(s)
11-25 07:25:13.031  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:25:13.031  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:13.031  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:13.031  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:13.031  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f18cafc added. We now have 5 listener(s)
11-25 07:25:13.031  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:13.032  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-25 07:25:13.032  5824  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-25 07:25:13.032  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.032  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:25:13.032  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:25:13.032  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:25:13.032  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:25:13.032  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-25 07:25:13.033  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 07:25:13.033  5824  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:25:13.034  3550  5904 W Uploader:  no longer exists, so no auth token.
,11-25 07:25:13.035  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-25 07:25:13.035  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:25:13.035  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:25:13.038  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.038  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-25 07:25:13.038  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-25 07:25:13.038  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:25:13.038  5824  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:25:13.038  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-25 07:25:13.038  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.039  5824  5840 E BtGatt.ContextMap: Context not found for ID 5
,11-25 07:25:13.039  3550  5906 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-25 07:25:13.040  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.040  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:25:13.040  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:25:13.041  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-25 07:25:13.041  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:25:13.041  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.041  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:13.043  5824  5834 D BtGatt.GattService: registerClient() - UUID=604a8ad2-6cb2-4372-bd32-b7ce598f89fc
11-25 07:25:13.043  5824  5840 D BtGatt.GattService: onClientRegistered() - UUID=604a8ad2-6cb2-4372-bd32-b7ce598f89fc, clientIf=5
11-25 07:25:13.044  5824  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-25 07:25:13.044  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.044  5580  5590 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-25 07:25:13.044  5824  5843 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:25:13.044  5824  5863 D BtGatt.GattService: start scan with filters
,11-25 07:25:13.048  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:25:13.048  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.048  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:25:13.048  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.048  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 07:25:13.048  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:25:13.048  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.049  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:25:13.049  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:25:13.049  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.049  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.049  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.049  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.049  5824  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 07:25:13.049  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.049  5824  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:25:13.049  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-25 07:25:13.049  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.051  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.051  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-25 07:25:13.051  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.051  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.052  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:25:13.052  5580  5626 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-25 07:25:13.052  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.052  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:25:13.052  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:25:13.052  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:25:13.052  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-25 07:25:13.052  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.052  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:25:13.052  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.052  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.052  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6235c9 removed from the list
11-25 07:25:13.052  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.052  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8aa54ce removed from the list
11-25 07:25:13.052  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:25:13.052  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.052  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-25 07:25:13.052  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.052  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.052  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 07:25:13.052  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.052  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:25:13.053  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.054  5824  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:25:13.054  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.054  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.054  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.054  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.054  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.054  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.054  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:25:13.054  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.054  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8aa54ce not in the list
,11-25 07:25:13.054  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.054  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.055  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.055  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:25:13.055  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.055  5824  5843 D BtGatt.ScanManager: handling starting scan
,11-25 07:25:13.056  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:25:13.056  5824  5862 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-25 07:25:13.056  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:25:13.057  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:13.057  5824  5835 D BtGatt.GattService: stopScan() - queue size =1
11-25 07:25:13.058  5824  5834 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:25:13.060  5824  5840 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-25 07:25:13.060  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5824  5843 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.060  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:25:13.060  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:25:13.061  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-25 07:25:13.061  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.062  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.062  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:25:13.062  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.062  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.062  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.062  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.062  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.062  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f18cafc removed from the list
,11-25 07:25:13.062  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.062  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.063  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.063  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb10fef removed from the list
11-25 07:25:13.063  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:13.063  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c25d501 added. We now have 3 listener(s)
11-25 07:25:13.064   930  5880 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 25 Nov 2016 12:25:12 GMT], X-Android-Received-Millis=[1480076713063], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480076712912]}
11-25 07:25:13.064   930  2943 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-25 07:25:13.064  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-25 07:25:13.064   930  2943 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-25 07:25:13.064  5824  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:25:13.064  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:13.064  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:25:13.064   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-25 07:25:13.064  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.064  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:13.065  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:25:13.065  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-25 07:25:13.065  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:25:13.065  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82fa6 added. We now have 4 listener(s)
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.065  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.065  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:25:13.065  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:25:13.065  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.065  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.065   930  2943 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-25 07:25:13.067  5824  5843 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:25:13.067  5824  5843 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-25 07:25:13.068  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:13.068  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e250de7 added. We now have 4 listener(s)
11-25 07:25:13.068  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.068  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.068  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.069  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:25:13.069  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:13.069  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-25 07:25:13.069  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:13.069  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad7d94 added. We now have 5 listener(s)
,11-25 07:25:13.069  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:13.069  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:25:13.069  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-25 07:25:13.069  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-25 07:25:13.070  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-25 07:25:13.070  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-25 07:25:13.070  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-25 07:25:13.072  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-25 07:25:13.072  5580  5626 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-25 07:25:13.072  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-25 07:25:13.077  5824  5840 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-25 07:25:13.077  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:25:13.078  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.078  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-25 07:25:13.078  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-25 07:25:13.078  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-25 07:25:13.078  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-25 07:25:13.081  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.081  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-25 07:25:13.081  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-25 07:25:13.081  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-25 07:25:13.081  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-25 07:25:13.081  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.082  5580  5626 D BluetoothAdapter: STATE_ON
,11-25 07:25:13.082  5824  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 07:25:13.083  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.084  5824  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:25:13.084  5824  5835 D BtGatt.GattService: registerClient() - UUID=4814d82e-5e90-470f-9648-04e6db5451d0
11-25 07:25:13.084  5824  5840 D BtGatt.GattService: onClientRegistered() - UUID=4814d82e-5e90-470f-9648-04e6db5451d0, clientIf=5
11-25 07:25:13.085  5580  5591 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-25 07:25:13.085  5824  5863 D BtGatt.GattService: start scan with filters
,11-25 07:25:13.087  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-25 07:25:13.087  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.087  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-25 07:25:13.087  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.087  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-25 07:25:13.088  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-25 07:25:13.088  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.088  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-25 07:25:13.088  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-25 07:25:13.088  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.088  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.088  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.088  5824  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:25:13.088  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.088  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:25:13.089  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-25 07:25:13.089  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.090  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.090  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:25:13.090  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.091  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.091  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.094  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.094  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.094  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.094  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.094  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-25 07:25:13.094  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-25 07:25:13.094  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:25:13.094  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:25:13.095  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.095  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.095  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:25:13.095  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.095  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.095  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c25d501 removed from the list
11-25 07:25:13.095  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.095  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82fa6 removed from the list
,11-25 07:25:13.095  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:25:13.095  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.095  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:25:13.095  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.095  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.095  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-25 07:25:13.095  5580  5626 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-25 07:25:13.095  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-25 07:25:13.096  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.096  5824  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:25:13.096  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.096  5824  5843 D BtGatt.ScanManager: stopping BLe Batch
11-25 07:25:13.096  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.096  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.096  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.097  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.097  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.097  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.097  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82fa6 not in the list
11-25 07:25:13.097  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.097  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-25 07:25:13.097  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.098  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:13.098  5824  5859 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-25 07:25:13.098  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-25 07:25:13.099  5580  5626 D BluetoothAdapter: STATE_ON
11-25 07:25:13.099  5824  5835 D BtGatt.GattService: stopScan() - queue size =0
,11-25 07:25:13.100  5824  5834 D BtGatt.GattService: unregisterClient() - clientIf=5
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.100  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-25 07:25:13.101  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.101  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.101  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.101  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-25 07:25:13.101  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-25 07:25:13.101  5824  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-25 07:25:13.101  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.101  5824  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-25 07:25:13.101  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-25 07:25:13.102  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.103  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.103  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:25:13.103  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.103  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.103  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.103  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.103  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.103  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-25 07:25:13.103  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad7d94 removed from the list
11-25 07:25:13.103  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.103  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-25 07:25:13.103  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.103  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.103  5580  5580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-25 07:25:13.103  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.103  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-25 07:25:13.103  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e250de7 removed from the list
11-25 07:25:13.103  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-25 07:25:13.103  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.103  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.104  5580  5580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-25 07:25:13.104  5580  5580 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-25 07:25:13.104  5580  5580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.104  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.104  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:13.104  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3672339 added. We now have 3 listener(s)
11-25 07:25:13.105  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.105  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.105  5580  5580 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-25 07:25:13.105  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:25:13.105  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:13.105  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:13.105  5824  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:25:13.105  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.105  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:13.105  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bb8d7e added. We now have 4 listener(s)
11-25 07:25:13.105  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:13.106  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-25 07:25:13.106  4380  5899 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-25 07:25:13.107  5824  5843 D BtGatt.ScanManager: handling starting scan
11-25 07:25:13.107  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-25 07:25:13.107  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bd2df added. We now have 4 listener(s)
11-25 07:25:13.108  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-25 07:25:13.108  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-25 07:25:13.108  5580  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-25 07:25:13.108  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-25 07:25:13.108  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Lis,tener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa2eb2c added. We now have 5 listener(s)
11-25 07:25:13.108  5580  5626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-25 07:25:13.109  5580  5626 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-25 07:25:13.109  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-25 07:25:13.109  5580  5626 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-25 07:25:13.109  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.109  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.109  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.109  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3672339 removed from the list
11-25 07:25:13.109  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.109  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bb8d7e removed from the list
11-25 07:25:13.109  5580  5626 D io.jxcore.node.ConnectivityMonitor: stop
11-25 07:25:13.109  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.109  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.110  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.110  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.110  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.110  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.110  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.110  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.110  5580  5626 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6bb8d7e not in the list
11-25 07:25:13.111  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.111  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.112  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,11-25 07:25:13.112  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.112  5580  5626 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
11-25 07:25:13.112  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-25 07:25:13.112  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-25 07:25:13.112  5580  5626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-25 07:25:13.112  5824  5840 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-25 07:25:13.112  5580  5626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa2eb2c removed from the list
11-25 07:25:13.112  5580  5626 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-25 07:25:13.112  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.112  5580  5626 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-25 07:25:13.112  5580  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-25 07:25:13.112  5580  5626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6bd2df removed from the list
11-25 07:25:13.112  5824  5843 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-25 07:25:13.113  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-25 07:25:13.113  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-25 07:25:13.113  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-25 07:25:13.113  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:25:13.113  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-25 07:25:13.113  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:25:13.117  5824  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-25 07:25:13.117  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.117  5824  5843 D BtGatt.ScanManager: Starting BLE batch scan
11-25 07:25:13.117  5824  5843 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-25 07:25:13.124  5824  5840 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-25 07:25:13.124  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:25:13.128  5824  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-25 07:25:13.128  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:25:13.129  5824  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:25:13.133  5824  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-25 07:25:13.133  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.133  5824  5840 E BtGatt.ContextMap: Context not found for ID 5
,11-25 07:25:13.139  5824  5840 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-25 07:25:13.139  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.139  5824  5843 D BtGatt.ScanManager: stopping BLe Batch
,11-25 07:25:13.143  5824  5840 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-25 07:25:13.143  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-25 07:25:13.143  5824  5843 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-25 07:25:13.147  5824  5840 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-25 07:25:13.147  5824  5840 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-25 07:25:13.369  3550  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 07:25:13.508   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:25:13.523  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:25:13.566  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,11-25 07:25:13.579  3550  5906 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 07:25:13.604  5580  5580 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-25 07:25:13.634  3550  5904 W Uploader:  no longer exists, so no auth token.
,11-25 07:25:13.644  3550  5908 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 07:25:13.732  3550  5906 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-25 07:25:14.251  3550  5907 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-25 07:25:14.254  3550  5907 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-25 07:25:14.509   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-25 07:25:15.247  5580  5915 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 07:25:15.247  5580  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:15.532   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:16.035  5580  5915 W !!      : call onHalfStreamCopied
,11-25 07:25:16.036  5580  5915 I testCopyDataAndClose: closing input stream
,11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-25 07:25:16.793  5580  5915 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 07:25:16.794  5580  5915 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-25 07:25:16.794  5580  5915 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 07:25:18.558   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:20.686  5580  5916 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:20.686  5580  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:20.738   930  2943 D ConnectivityService: handlePromptUnvalidated 102
,11-25 07:25:21.575   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:22.686  5580  5626 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
11-25 07:25:22.686  5580  5626 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:22.686  5580  5626 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,11-25 07:25:22.740  5580  5916 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-25 07:25:22.740  5580  5916 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:22.740  5580  5916 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-25 07:25:22.840  5580  5917 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 07:25:22.840  5580  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:23.835   930  2941 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-25 07:25:24.474  5580  5917 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:25:28.216  5580  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-25 07:25:28.217  5580  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-25 07:25:28.217  5580  5918 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-25 07:25:28.217  5580  5918 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-25 07:25:28.217  5580  5918 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-25 07:25:28.217  5580  5918 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:28.217  5580  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-25 07:25:28.219  5580  5626 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-25 07:25:28.222  5580  5919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:28.222  5580  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-25 07:25:28.223  5580  5919 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
11-25 07:25:28.224  5580  5919 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:28.224  5580  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 07:25:28.224  5580  5919 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-25 07:25:28.225  5580  5919 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-25 07:25:28.225  5580  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-25 07:25:28.227  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-25 07:25:28.227  5580  5626 I jxcore-log: 
,11-25 07:25:28.228  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-25 07:25:28.228  5580  5626 I jxcore-log: 
11-25 07:25:28.228  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-25 07:25:28.228  5580  5626 I jxcore-log: 
11-25 07:25:28.228  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-25 07:25:28.228  5580  5626 I jxcore-log: 
,11-25 07:25:28.229  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'Total duration:  90868'
11-25 07:25:28.229  5580  5626 I jxcore-log: 
,11-25 07:25:28.230  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-25 07:25:28.230  5580  5626 I jxcore-log: 
,11-25 07:25:28.234  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.234  5580  5626 I jxcore-log: 
11-25 07:25:28.235  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.235  5580  5626 I jxcore-log: 
,11-25 07:25:28.235  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 07:25:28.235  5580  5626 I jxcore-log: 
,11-25 07:25:28.235  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 07:25:28.235  5580  5626 I jxcore-log: 
,11-25 07:25:28.236  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.236  5580  5626 I jxcore-log: 
11-25 07:25:28.236  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:25:28.236  5580  5626 I jxcore-log: 
,11-25 07:25:28.236  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.236  5580  5626 I jxcore-log: 
11-25 07:25:28.236  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.236  5580  5626 I jxcore-log: 
11-25 07:25:28.237  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.237  5580  5626 I jxcore-log: 
11-25 07:25:28.237  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-25 07:25:28.237  5580  5626 I jxcore-log: 
,11-25 07:25:28.237  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-25 07:25:28.237  5580  5626 I jxcore-log: 
11-25 07:25:28.237  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.237  5580  5626 I jxcore-log: 
,11-25 07:25:28.238  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:25:28.238  5580  5626 I jxcore-log: 
11-25 07:25:28.238  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.238  5580  5626 I jxcore-log: 
11-25 07:25:28.238  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:25:28.238  5580  5626 I jxcore-log: 
11-25 07:25:28.238  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.238  5580  5626 I jxcore-log: 
11-25 07:25:28.238  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.238  5580  5626 I jxcore-log: 
,11-25 07:25:28.239  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 07:25:28.239  5580  5626 I jxcore-log: 
,11-25 07:25:28.239  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 07:25:28.239  5580  5626 I jxcore-log: 
11-25 07:25:28.239  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-25 07:25:28.239  5580  5626 I jxcore-log: 
11-25 07:25:28.239  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.239  5580  5626 I jxcore-log: 
,11-25 07:25:28.240  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 07:25:28.240  5580  5626 I jxcore-log: 
11-25 07:25:28.240  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 07:25:28.240  5580  5626 I jxcore-log: 
11-25 07:25:28.240  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-25 07:25:28.240  5580  5626 I jxcore-log: 
11-25 07:25:28.242  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-25 07:25:28.242  5580  5626 I jxcore-log: 
11-25 07:25:28.242  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-25 07:25:28.242  5580  5626 I jxcore-log: 
,11-25 07:25:28.242  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-25 07:25:28.242  5580  5626 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-25 07:25:28.242  5580  5626 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-25 07:25:28.243  5580  5626 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-25 07:25:28.243  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:25:28.243  5580  5626 I jxcore-log: 
,11-25 07:25:28.243  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.243  5580  5626 I jxcore-log: 
11-25 07:25:28.243  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:25:28.243  5580  5626 I jxcore-log: 
11-25 07:25:28.243  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.243  5580  5626 I jxcore-log: 
,11-25 07:25:28.244  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-25 07:25:28.244  5580  5626 I jxcore-log: 
11-25 07:25:28.244  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-25 07:25:28.244  5580  5626 I jxcore-log: 
11-25 07:25:28.249  5580  5580 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-25 07:25:28.250  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-25 07:25:28.250  5580  5626 I jxcore-log: 
11-25 07:25:28.250  5580  5580 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-25 07:25:28.250  5580  5626 I jxcore-log: 2016-11-25 12:25:28 - WARN testUtils: 'myNameCallback not set!'
11-25 07:25:28.250  5580  5626 I jxcore-log: 
,11-25 07:25:30.303  5580  5626 I jxcore-log: 2016-11-25 12:25:30 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-25 07:25:30.303  5580  5626 I jxcore-log: 
,11-25 07:25:30.304  5580  5626 I jxcore-log: 2016-11-25 12:25:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-25 07:25:30.304  5580  5626 I jxcore-log: 
,11-25 07:25:30.655  5580  5626 I jxcore-log: 2016-11-25 12:25:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-25 07:25:30.655  5580  5626 I jxcore-log: 
,11-25 07:25:30.667  5580  5626 I jxcore-log: 2016-11-25 12:25:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-25 07:25:30.667  5580  5626 I jxcore-log: 
,11-25 07:25:31.757  5580  5626 I jxcore-log: 2016-11-25 12:25:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-25 07:25:31.757  5580  5626 I jxcore-log: 
,11-25 07:25:31.944  5580  5626 I jxcore-log: 2016-11-25 12:25:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-25 07:25:31.944  5580  5626 I jxcore-log: 
,11-25 07:25:31.949  5580  5626 I jxcore-log: 2016-11-25 12:25:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-25 07:25:31.949  5580  5626 I jxcore-log: 
,11-25 07:25:31.954  5580  5626 I jxcore-log: 2016-11-25 12:25:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-25 07:25:31.954  5580  5626 I jxcore-log: 
,11-25 07:25:32.433  5580  5626 I jxcore-log: 2016-11-25 12:25:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-25 07:25:32.433  5580  5626 I jxcore-log: 
,11-25 07:25:32.477  5580  5626 I jxcore-log: 2016-11-25 12:25:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-25 07:25:32.477  5580  5626 I jxcore-log: 
,11-25 07:25:32.491  5580  5626 I jxcore-log: 2016-11-25 12:25:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-25 07:25:32.491  5580  5626 I jxcore-log: 
,11-25 07:25:32.495  5580  5626 I jxcore-log: 2016-11-25 12:25:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-25 07:25:32.495  5580  5626 I jxcore-log: 
,11-25 07:25:32.762  5580  5626 I jxcore-log: 2016-11-25 12:25:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-25 07:25:32.762  5580  5626 I jxcore-log: 
,11-25 07:25:32.884  5580  5626 I jxcore-log: 2016-11-25 12:25:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-25 07:25:32.884  5580  5626 I jxcore-log: 
,11-25 07:25:33.260  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-25 07:25:33.260  5580  5626 I jxcore-log: 
,11-25 07:25:33.269  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-25 07:25:33.269  5580  5626 I jxcore-log: 
,11-25 07:25:33.273  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-25 07:25:33.273  5580  5626 I jxcore-log: 
,11-25 07:25:33.278  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-25 07:25:33.278  5580  5626 I jxcore-log: 
,11-25 07:25:33.284  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-25 07:25:33.284  5580  5626 I jxcore-log: 
,11-25 07:25:33.313  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-25 07:25:33.313  5580  5626 I jxcore-log: 
,11-25 07:25:33.351  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-25 07:25:33.351  5580  5626 I jxcore-log: 
,11-25 07:25:33.358  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-25 07:25:33.358  5580  5626 I jxcore-log: 
,11-25 07:25:33.364  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-25 07:25:33.364  5580  5626 I jxcore-log: 
,11-25 07:25:33.380  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-25 07:25:33.380  5580  5626 I jxcore-log: 
,11-25 07:25:33.395  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-25 07:25:33.395  5580  5626 I jxcore-log: 
,11-25 07:25:33.401  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-25 07:25:33.401  5580  5626 I jxcore-log: 
,11-25 07:25:33.407  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-25 07:25:33.407  5580  5626 I jxcore-log: 
,11-25 07:25:33.420  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-25 07:25:33.420  5580  5626 I jxcore-log: 
,11-25 07:25:33.437  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-25 07:25:33.437  5580  5626 I jxcore-log: 
,11-25 07:25:33.451  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-25 07:25:33.451  5580  5626 I jxcore-log: 
,11-25 07:25:33.462  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-25 07:25:33.462  5580  5626 I jxcore-log: 
,11-25 07:25:33.475  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-25 07:25:33.475  5580  5626 I jxcore-log: 
,11-25 07:25:33.485  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-25 07:25:33.485  5580  5626 I jxcore-log: 
,11-25 07:25:33.498  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-25 07:25:33.498  5580  5626 I jxcore-log: 
,11-25 07:25:33.508  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-25 07:25:33.508  5580  5626 I jxcore-log: 
,11-25 07:25:33.515  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-25 07:25:33.515  5580  5626 I jxcore-log: 
,11-25 07:25:33.537  5580  5626 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-25 07:25:33.538  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO testUtils: 'BLE multiple advertisement supported'
11-25 07:25:33.538  5580  5626 I jxcore-log: 
,11-25 07:25:33.569  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-25 07:25:33.569  5580  5626 I jxcore-log: 
,11-25 07:25:33.658   930  2943 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-25 07:25:33.693  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 07:25:33.693  5580  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 07:25:33.693  5580  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 07:25:33.693  5580  5626 I jxcore-log: emit@events.js:82:1
11-25 07:25:33.693  5580  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 07:25:33.693  5580  5626 I jxcore-log: emit@events.js:82:1''
11-25 07:25:33.693  5580  5626 I jxcore-log: 
11-25 07:25:33.693  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - DEBUG CoordinatedClient: 'test client failed'
11-25 07:25:33.693  5580  5626 I jxcore-log: 
,11-25 07:25:33.700  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-25 07:25:33.700  5580  5626 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-25 07:25:33.700  5580  5626 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-25 07:25:33.700  5580  5626 I jxcore-log: emit@events.js:82:1
11-25 07:25:33.700  5580  5626 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-25 07:25:33.700  5580  5626 I jxcore-log: emit@events.js:82:1''
11-25 07:25:33.700  5580  5626 I jxcore-log: 
,11-25 07:25:33.700  5580  5626 I jxcore-log: 2016-11-25 12:25:33 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-25 07:25:33.700  5580  5626 I jxcore-log: 
,11-25 07:25:34.232  5920  5920 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-25 07:25:34.238  5920  5920 D AndroidRuntime: CheckJNI is OFF
,11-25 07:25:34.267  5920  5920 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-25 07:25:34.301  5920  5920 I Radio-JNI: register_android_hardware_Radio DONE
,11-25 07:25:34.319  5920  5920 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-25 07:25:34.329   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-25 07:25:34.330   930   943 I ActivityManager: Killing 5580:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-25 07:25:34.436   930  3767 D GraphicsStats: Buffer count: 2
,11-25 07:25:34.437   930  3786 I WindowState: WIN DEATH: Window{c69ed76 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-25 07:25:34.439   930  2942 D WifiService: Client connection lost with reason: 4
,11-25 07:25:34.485   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-25 07:25:34.486   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-25 07:25:34.487   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-25 07:25:34.487   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-25 07:25:34.487   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:25:34.487   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:25:34.487   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 07:25:34.487   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-25 07:25:34.488   930   943 I ActivityManager:   Force finishing activity ActivityRecord{da9854a u0 com.test.thalitest/.MainActivity t10}
,11-25 07:25:34.493   930   953 I art     : Starting a blocking GC Explicit
,11-25 07:25:34.499   930  3117 W ActivityManager: Spurious death for ProcessRecord{675292b 0:com.test.thalitest/u0a77}, curProc for 5580: null
,11-25 07:25:34.503   930   948 W WindowManager: Attempted to add application window with unknown token Token{9067cbb ActivityRecord{da9854a u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
11-25 07:25:34.503   930   948 W WindowManager: Token{9067cbb ActivityRecord{da9854a u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{9067cbb ActivityRecord{da9854a u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
,11-25 07:25:34.503   930   948 W WindowManager: view not successfully added to wm, removing view
11-25 07:25:34.504   930   948 W WindowManager: Exception when adding starting window
11-25 07:25:34.504   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a3721d2 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-25 07:25:34.504   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-25 07:25:34.504   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-25 07:25:34.504   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-25 07:25:34.504   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-25 07:25:34.504   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-25 07:25:34.504   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:25:34.504   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:25:34.504   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 07:25:34.504   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-25 07:25:34.509   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-25 07:25:34.578   930   953 I art     : Explicit concurrent mark sweep GC freed 53498(3MB) AllocSpace objects, 10(304KB) LOS objects, 33% free, 28MB/43MB, paused 1.619ms total 84.545ms
,11-25 07:25:34.598   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-25 07:25:34.600  5920  5920 I art     : System.exit called, status: 0
11-25 07:25:34.600  5920  5920 I AndroidRuntime: VM exiting with result code 0.
,11-25 07:25:34.605   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-25 07:25:34.615   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-25 07:25:34.618  3630  3630 I Keyboard.Facilitator: resetDictionaries() : en_US
11-25 07:25:34.619  5824  5824 D BluetoothMapAppObserver: onReceive
11-25 07:25:34.620  5824  5824 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-25 07:25:34.632   930  2907 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-25 07:25:34.646  3907  4073 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-25 07:25:34.648  3630  5931 I Keyboard.Facilitator.DecoderInitializer: run()
,11-25 07:25:34.654  3630  5931 I Decoder : createOrResetDecoder
,11-25 07:25:34.674  3741  3741 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-25 07:25:34.684  3550  3550 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-25 07:25:34.684  3550  3550 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-25 07:25:34.678    28    28 W kworker/2:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:25:34.685    28    28 W kworker/2:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:25:34.691   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-25 07:25:34.691    28    28 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-25 07:25:34.700  3550  3550 I ConfigService: onCreate
,11-25 07:25:34.701  3780  3883 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-25 07:25:34.702   930   942 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-25 07:25:34.703   930   942 E PackageManager: Failed to write settings, restoring backup
11-25 07:25:34.703   930   942 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-25 07:25:34.703   930   942 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-25 07:25:34.703   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-25 07:25:34.703   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-25 07:25:34.703   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-25 07:25:34.703   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:25:34.703   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:25:34.703   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 07:25:34.704  3367  5934 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-25 07:25:34.706  3550  5937 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-25 07:25:34.706  3550  5937 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-25 07:25:34.706  3550  5937 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-25 07:25:34.707  3550  5937 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-25 07:25:34.710   930   943 E DropBoxManagerService: Can't write: system_server_wtf
11-25 07:25:34.710   930   943 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-25 07:25:34.710   930   943 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:25:34.710   930   943 E DropBoxManagerService: 	... 13 more
,11-25 07:25:34.713  3367  3394 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjED4C3A9D6) - 
,--------- beginning of crash
11-25 07:25:34.714  3367  3394 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-25 07:25:34.714  3367  3394 E AndroidRuntime: Process: android.process.acore, PID: 3367
11-25 07:25:34.714  3367  3394 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:25:34.714  3367  3394 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 07:25:34.716   930  3815 I ActivityManager: Start proc 5939:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
11-25 07:25:34.717  3780  3883 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-25 07:25:34.717  3780  3883 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3780
11-25 07:25:34.717  3780  3883 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-25 07:25:34.717  3780  3883 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-25 07:25:34.721   930  3767 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-25 07:25:34.725  3780  3883 I Process : Sending signal. PID: 3780 SIG: 9
,11-25 07:25:34.723   930  5944 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:25:34.723   930  5944 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:25:34.723   930  5944 E DropBoxManagerService: 	... 5 more
11-25 07:25:34.725   930  5950 E DropBoxManagerService: Can't write: system_app_crash
11-25 07:25:34.725   930  5950 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-25 07:25:34.725   930  5950 E DropBoxManagerService: 	... 5 more
,11-25 07:25:34.746  3630  5931 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-25 07:25:34.753  4035  5938 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-25 07:25:34.754  4035  5938 D AccountUtils: Clearing selected account for com.test.thalitest
,11-25 07:25:34.783  3367  5934 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-25 07:25:34.800  3367  5934 I Process : Sending signal. PID: 3367 SIG: 9
,11-25 07:25:34.829   930  2906 W InputDispatcher: channel '2b4200a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-25 07:25:34.829   930  3767 D GraphicsStats: Buffer count: 1
11-25 07:25:34.829   930  3764 I WindowState: WIN DEATH: Window{2b4200a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,11-25 07:25:34.829   930  2906 E InputDispatcher: channel '2b4200a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-25 07:25:34.829   930  3764 W InputDispatcher: Attempted to unregister already unregistered input channel '2b4200a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-25 07:25:34.834   930  3118 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3780) has died
,11-25 07:25:34.835   930  3118 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-25 07:25:34.860   930  3815 I ActivityManager: Process android.process.acore (pid 3367) has died
11-25 07:25:34.860   930  3815 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-25 07:25:35.079   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
