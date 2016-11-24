#### Test 9504761598f4ffc_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
,11-24 04:33:55.313  3556  5621 I VacuumService: Vacuum at: now=1479980035313 tag=VacuumService
11-24 04:33:55.343  3556  5624 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-24 04:33:55.377  3556  5622 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-24 04:33:55.380  3556  5622 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-24 04:33:55.424  3556  5622 W Uploader:  no longer exists, so no auth token.
11-24 04:33:55.429  3556  5624 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-24 04:33:55.690  5627  5627 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 04:33:55.696  5627  5627 D AndroidRuntime: CheckJNI is OFF
11-24 04:33:55.697  3556  5626 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-24 04:33:55.721  5627  5627 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 04:33:55.746  5627  5627 I Radio-JNI: register_android_hardware_Radio DONE
11-24 04:33:55.761  5627  5627 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 04:33:55.764   930  3130 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 04:33:55.794   930  3130 I ActivityManager: Start proc 5639:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 04:33:55.806  5627  5627 D AndroidRuntime: Shutting down VM
,11-24 04:33:56.115   930  3398 I WindowManager: Screenshot max retries 4 of Token{326c945 ActivityRecord{e6465bc u0 com.test.thalitest/.MainActivity t10}} appWin=Window{3f9b054 u0 Starting com.test.thalitest} drawState=2
,11-24 04:33:56.138  3556  5624 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 04:33:56.193  5639  5639 I CordovaLog: Changing log level to DEBUG(3)
,11-24 04:33:56.194  5639  5639 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 04:33:56.194  5639  5639 D CordovaActivity: CordovaActivity.onCreate()
,11-24 04:33:56.201  5639  5639 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-24 04:33:56.208  3556  5622 W Uploader:  no longer exists, so no auth token.
,11-24 04:33:56.214  3556  5626 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader,
,11-24 04:33:56.235  5639  5639 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 04:33:56.277  3556  5624 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 04:33:56.305  5639  5639 I LibraryLoader: Time to load native libraries: 64 ms (timestamps 1283-1347)
,11-24 04:33:56.305  5639  5639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 04:33:56.339  5639  5639 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {91e180d}
,11-24 04:33:56.339  5639  5639 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 04:33:56.340  5639  5639 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 04:33:56.345  5639  5639 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 04:33:56.346  5639  5639 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 04:33:56.386  5639  5639 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 04:33:56.403  5639  5639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 04:33:56.403  5639  5639 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 04:33:56.403  5639  5639 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 04:33:56.403  5639  5639 I Adreno  : Build Date                       : 12/06/15
11-24 04:33:56.403  5639  5639 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 04:33:56.403  5639  5639 I Adreno  : Local Branch                     : mybranch17112971
11-24 04:33:56.403  5639  5639 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 04:33:56.403  5639  5639 I Adreno  : Remote Branch                    : NONE
11-24 04:33:56.403  5639  5639 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 04:33:56.455   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4c17bb:true
,11-24 04:33:56.478   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34319]" dev="sockfs" ino=34319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 04:33:56.478   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34319]" dev="sockfs" ino=34319 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 04:33:56.492  5639  5639 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 04:33:56.502  5639  5639 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 04:33:56.506  5639  5639 D PluginManager: init()
,11-24 04:33:56.509  5639  5639 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 04:33:56.529  5639  5639 D CordovaActivity: Started the activity.
,11-24 04:33:56.529  5639  5639 D CordovaActivity: Resumed the activity.
,11-24 04:33:56.528   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32587]" dev="sockfs" ino=32587 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 04:33:56.528   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32587]" dev="sockfs" ino=32587 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 04:33:56.533  5639  5676 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 04:33:56.531  3397  3397 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13297]" dev="sockfs" ino=13297 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 04:33:56.536  5639  5639 D CordovaActivity: Paused the activity.
,11-24 04:33:56.531  3397  3397 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[13297]" dev="sockfs" ino=13297 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 04:33:56.538  5639  5663 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 04:33:56.561  5639  5676 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 04:33:56.568  5639  5639 D CordovaActivity: Stopped the activity.
,11-24 04:33:56.618   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +499ms (total +838ms)
,11-24 04:33:56.637  5639  5639 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 04:33:56.660  5639  5639 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5639
,11-24 04:33:56.752  5639  5639 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 04:33:56.913  5639  5678 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -564659920
,11-24 04:33:56.917  5639  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 04:33:56.917  5639  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 04:33:56.917  5639  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 04:33:56.917  5639  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 04:33:56.917  5639  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 04:33:56.917  5639  5678 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68c0b added. We now have 1 listener(s)
,11-24 04:33:56.920  5639  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-24 04:33:56.920  5639  5678 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:33:56.921  5639  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 04:33:56.921  5639  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-24 04:33:56.923  5639  5678 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdc3fa6 added. We now have 1 listener(s)
11-24 04:33:56.923  5639  5678 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:33:56.927   930  2939 D WifiService: New client listening to asynchronous messages
,11-24 04:33:56.928  5639  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 04:33:56.928  5639  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-24 04:33:56.928  5639  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 04:33:56.929  5639  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 04:33:56.929  5639  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 04:33:56.929  5639  5678 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-24 04:33:56.929  5639  5678 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 04:33:56.930  5639  5678 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 04:33:57.044  5639  5639 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 04:33:57.048  5639  5639 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-24 04:33:57.048  5639  5639 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 04:33:57.664  5639  5687 W jxcore-log: Initializing JXcore engine
11-24 04:33:57.664  5639  5687 W jxcore-log: JXcore engine is ready
,11-24 04:33:57.688  5687  5687 W Thread-62: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11839 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 04:33:57.688  5687  5687 W Thread-62: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12351]" dev="sockfs" ino=12351 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 04:33:57.688  5687  5687 W Thread-62: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 04:33:57.688  5687  5687 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31399]" dev="sockfs" ino=31399 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 04:33:57.697  5639  5687 W jxcore-log: Starting JXcore engine
,11-24 04:33:57.747  5639  5687 W jxcore-log: Platform android
11-24 04:33:57.747  5639  5687 W jxcore-log: 
,11-24 04:33:57.747  5639  5687 W jxcore-log: Process ARCH arm
11-24 04:33:57.747  5639  5687 W jxcore-log: 
,11-24 04:33:57.928  5639  5687 I jxcore-log: JXcore Cordova bridge is ready!
11-24 04:33:57.928  5639  5687 I jxcore-log: 
,11-24 04:33:57.928  5639  5687 W jxcore-log: JXcore engine is started
,11-24 04:33:57.938  5639  5678 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 04:33:57.944  5639  5639 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 04:33:57.944  5639  5639 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 04:33:59.215  3422  3422 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:34:00.136   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:01.137   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:01.758   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 04:34:02.138   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:03.139   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:04.140   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:04.787   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 04:34:05.140   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 04:34:07.576  5639  5687 I jxcore-log: 2016-11-24 09:34:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 04:34:07.576  5639  5687 I jxcore-log: 
,11-24 04:34:07.578  5639  5687 I jxcore-log: 2016-11-24 09:34:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 04:34:07.578  5639  5687 I jxcore-log: 
,11-24 04:34:07.583  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 04:34:07.583  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 04:34:07.584  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 04:34:07.587  5639  5687 I jxcore-log: 2016-11-24 09:34:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 04:34:07.587  5639  5687 I jxcore-log: 
,11-24 04:34:07.589  5639  5687 I jxcore-log: 2016-11-24 09:34:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 04:34:07.589  5639  5687 I jxcore-log: 
,11-24 04:34:07.832  5639  5687 I jxcore-log: 2016-11-24 09:34:07 - DEBUG UnitTest_app: 'Running unit tests'
11-24 04:34:07.832  5639  5687 I jxcore-log: 
,11-24 04:34:07.832  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:34:07.832  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c680362 added. We now have 2 listener(s)
11-24 04:34:07.833  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:34:07.833  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 04:34:07.833  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:34:07.833  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:34:07.833  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91d7cf3 added. We now have 2 listener(s)
,11-24 04:34:07.833  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:34:07.834  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 04:34:07.835  5639  5687 D executeNativeTests: Running unit tests
,11-24 04:34:07.879  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 04:34:07.879  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 added. We now have 3 listener(s)
,11-24 04:34:07.879  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 04:34:07.880  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:34:07.880  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:34:07.880  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 04:34:07.880  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 added. We now have 3 listener(s)
11-24 04:34:07.880  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:34:07.881  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 04:34:07.883  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-24 04:34:07.883  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:07.883  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:07.883  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:07.884  5639  5687 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 04:34:07.884  5639  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 04:34:07.884  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-24 04:34:07.884  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:07.884  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:07.884  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:07.884  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:07.885  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:07.885  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:07.885  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:07.885  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:07.885  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 04:34:07.885  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 removed from the list
11-24 04:34:07.886  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:07.886  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 removed from the list
11-24 04:34:07.886  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:07.886  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.886  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:07.887  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.887  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.887  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.887  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:07.887  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 04:34:07.887  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:07.887  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:07.888  5639  5687 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 04:34:07.888  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:07.888  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:07.888  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:07.888  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:07.889  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:07.889  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:07.889  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:07.889  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:07.889  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:07.889  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:07.889  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:07.889  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.889  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.890  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.890  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:07.890  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:07.890  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:07.890  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:07.892  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 04:34:07.892  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 04:34:07.892  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 04:34:07.892  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 04:34:07.892  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 04:34:07.892  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 04:34:07.893  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 04:34:07.894  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 04:34:07.894  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:07.894  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:07.894  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:07.894  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:07.894  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:07.894  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:07.894  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:07.894  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:07.894  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:07.894  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.894  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.895  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.895  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.895  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.895  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:07.895  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:07.895  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:07.895  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:07.895  5639  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 04:34:07.897  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:34:07.897  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 04:34:07.909  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 04:34:07.912  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 04:34:07.912  5639  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 04:34:07.913  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:34:07.913  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 04:34:07.914  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 04:34:07.914  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:34:07.914  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 04:34:07.915  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 04:34:07.915  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 04:34:07.915  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 04:34:07.917  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:07.919  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.919  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 04:34:07.919  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:07.921  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 04:34:07.921  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 04:34:07.921  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 04:34:07.924  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 04:34:07.925  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 04:34:07.925  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.925  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 04:34:07.926  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 04:34:07.926  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 04:34:07.926  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 04:34:07.926  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.926  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:07.928  4574  4785 D BtGatt.GattService: registerClient() - UUID=8dfcea44-f146-4aab-bff7-43605e8778e1
11-24 04:34:07.929  4574  4655 D BtGatt.GattService: onClientRegistered() - UUID=8dfcea44-f146-4aab-bff7-43605e8778e1, clientIf=5
11-24 04:34:07.930  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 04:34:07.931  4574  4589 D BtGatt.GattService: start scan with filters
11-24 04:34:07.937  4574  4666 D BtGatt.ScanManager: handling starting scan
11-24 04:34:07.938  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 04:34:07.938  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.938  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 04:34:07.938  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.938  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 04:34:07.938  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 04:34:07.938  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.939  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 04:34:07.939  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 04:34:07.939  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 04:34:07.939  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.939  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.939  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.939  4574  4666 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:34:07.939  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.939  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.939  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.939  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.939  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:07.940  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.940  5639  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-24 04:34:07.942  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.942  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:34:07.943  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.943  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:07.943  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:34:07.946  4574  4655 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 04:34:07.946  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:07.947  4574  4666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 04:34:07.954  4574  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 04:34:07.954  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:07.954  4574  4666 D BtGatt.ScanManager: Starting BLE batch scan
11-24 04:34:07.955  4574  4666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 04:34:07.966  4574  4655 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 04:34:07.966  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:07.974  4574  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 04:34:07.974  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:08.443  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 04:34:08.444  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:34:08.444  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 04:34:10.835   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 04:34:12.944  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:12.945  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 04:34:12.945  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 04:34:12.945  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 04:34:12.945  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 04:34:12.945  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 04:34:12.945  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 04:34:12.945  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 04:34:12.945  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.946  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 04:34:12.946  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 04:34:12.946  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.947  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.947  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.947  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 04:34:12.947  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.948  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:12.948  4574  4785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 04:34:12.949  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 04:34:12.950  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:12.950  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:34:12.950  4574  4589 D BtGatt.GattService: stopScan() - queue size =1
11-24 04:34:12.951  4574  4785 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.952  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.953  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 04:34:12.953  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.953  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.953  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.953  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 04:34:12.954  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 04:34:12.955  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:34:12.955  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.956  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.956  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:12.956  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.957  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:12.957  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:12.957  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:34:12.957  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:34:12.957  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:12.957  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:12.957  4574  4574 D BtGatt.ScanManager: awakened up at time 178000
11-24 04:34:12.957  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:12.957  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:12.957  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:12.957  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:12.957  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:12.958  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:34:12.958  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 04:34:12.958  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.958  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 04:34:12.958  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 04:34:12.959  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.959  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.959  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.959  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:12.960  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.960  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.964  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.964  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:12.964  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 04:34:12.978  4574  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 04:34:12.978  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:12.978  4574  4655 D BtGatt.GattService: current time is 178021534561
11-24 04:34:12.978  4574  4655 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -73, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -71, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -71, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -70, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -70, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -66, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 04:34:12.980  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 04:34:12.981  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 04:34:12.981  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 04:34:12.981  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 04:34:12.981  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 04:34:12.982  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 04:34:12.988  4574  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 04:34:12.988  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:12.988  4574  4666 D BtGatt.ScanManager: stopping BLe Batch
,11-24 04:34:12.995  4574  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 04:34:12.995  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:12.995  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 04:34:13.002  4574  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:34:13.002  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:13.461  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 04:34:13.865   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 04:34:17.694   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:34:17.965  5639  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 04:34:17.968  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:34:17.969  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 04:34:17.977  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 04:34:17.980  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 04:34:17.981  5639  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 04:34:17.981  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:34:17.981  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 04:34:17.981  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 04:34:17.981  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:34:17.982  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 04:34:17.985  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:17.986  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 04:34:17.986  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 04:34:17.986  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 04:34:17.988  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:17.990  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:17.990  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 04:34:17.991  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 04:34:17.991  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 04:34:17.991  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 04:34:17.995  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:17.995  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 04:34:17.995  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 04:34:17.995  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 04:34:17.995  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 04:34:17.996  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:17.997  5639  5687 D BluetoothAdapter: STATE_ON
,11-24 04:34:17.999  4574  4785 D BtGatt.GattService: registerClient() - UUID=8472d6da-3b6e-4321-acc5-dd5d4d3fd66f
11-24 04:34:18.000  4574  4655 D BtGatt.GattService: onClientRegistered() - UUID=8472d6da-3b6e-4321-acc5-dd5d4d3fd66f, clientIf=5
,11-24 04:34:18.000  5639  5649 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 04:34:18.001  4574  4589 D BtGatt.GattService: start scan with filters
,11-24 04:34:18.004  4574  4666 D BtGatt.ScanManager: handling starting scan
11-24 04:34:18.005  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 04:34:18.005  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.005  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 04:34:18.005  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.005  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 04:34:18.005  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 04:34:18.005  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.005  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 04:34:18.006  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 04:34:18.006  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.006  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.006  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.006  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.007  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 04:34:18.007  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.010  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.010  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 04:34:18.010  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.010  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:18.010  5639  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-24 04:34:18.011  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.012  4574  4655 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 04:34:18.012  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:18.013  4574  4666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 04:34:18.015  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:18.015  5639  5687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 04:34:18.015  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:18.015  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 04:34:18.015  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:34:18.016  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 04:34:18.016  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:18.016  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 04:34:18.016  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.017  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.017  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.017  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 04:34:18.017  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:34:18.017  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.017  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 04:34:18.017  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 04:34:18.017  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.017  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.017  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.017  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 04:34:18.018  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.019  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:18.019  4574  4591 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 04:34:18.019  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 04:34:18.020  4574  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 04:34:18.020  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:18.021  4574  4666 D BtGatt.ScanManager: Starting BLE batch scan
11-24 04:34:18.021  4574  4666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 04:34:18.021  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:18.022  4574  4589 D BtGatt.GattService: stopScan() - queue size =1
11-24 04:34:18.022  4574  4591 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 04:34:18.023  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 04:34:18.023  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.023  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 04:34:18.023  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:18.023  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.023  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.024  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.024  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 04:34:18.024  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.024  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.024  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.024  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 04:34:18.024  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 04:34:18.025  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:34:18.025  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.026  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.026  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:18.027  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.027  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.027  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:18.027  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:18.027  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:34:18.027  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:34:18.027  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:18.027  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:18.027  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 04:34:18.027  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:18.027  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.027  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:18.027  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 04,:34:18.027  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:18.027  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 04:34:18.027  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:18.027  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.027  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:34:18.027  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.028  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.028  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:18.028  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.028  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.030  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.030  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.030  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.030  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.030  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:18.032  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.032  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.032  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.032  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:18.032  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 04:34:18.032  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:18.032  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:18.033  4574  4655 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 04:34:18.033  5639  5687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 04:34:18.033  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:18.035  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 04:34:18.035  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 04:34:18.040  4574  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 04:34:18.040  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 04:34:18.041  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 04:34:18.041  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 04:34:18.044  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 04:34:18.044  5639  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 04:34:18.044  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:34:18.044  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 04:34:18.044  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 04:34:18.044  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 04:34:18.044  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 04:34:18.048  4574  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 04:34:18.048  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:18.048  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 04:34:18.048  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 04:34:18.049  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 04:34:18.049  4574  4655 E BtGatt.ContextMap: Context not found for ID 5
11-24 04:34:18.049  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:18.053  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:18.053  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.053  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 04:34:18.054  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 04:34:18.054  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 04:34:18.054  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 04:34:18.056  4574  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 04:34:18.056  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:18.056  4574  4666 D BtGatt.ScanManager: stopping BLe Batch
11-24 04:34:18.056  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:18.056  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 04:34:18.056  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 04:34:18.056  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 04:34:18.057  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 04:34:18.057  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.057  5639  5687 D BluetoothAdapter: STATE_ON
,11-24 04:34:18.059  4574  4591 D BtGatt.GattService: registerClient() - UUID=a4fc0324-6671-4aeb-b2bc-b3001e9e3714
11-24 04:34:18.060  4574  4655 D BtGatt.GattService: onClientRegistered() - UUID=a4fc0324-6671-4aeb-b2bc-b3001e9e3714, clientIf=5
11-24 04:34:18.060  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 04:34:18.060  4574  4589 D BtGatt.GattService: start scan with filters
11-24 04:34:18.063  4574  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 04:34:18.063  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:18.063  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:34:18.063  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 04:34:18.063  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.063  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 04:34:18.063  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.063  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 04:34:18.063  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 04:34:18.063  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 04:34:18.064  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 04:34:18.064  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 04:34:18.064  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.064  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.064  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.064  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.065  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 04:34:18.065  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:18.067  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.067  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:34:18.067  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.067  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:18.067  5639  5687 I io.jxcore.node.ConnectionHelper: start: OK
11-24 04:34:18.067  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.068  4574  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:34:18.068  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:18.069  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.069  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.070  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:18.070  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:34:18.070  4574  4666 D BtGatt.ScanManager: handling starting scan
,11-24 04:34:18.075  4574  4655 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 04:34:18.075  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:18.075  4574  4666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 04:34:18.080  4574  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 04:34:18.080  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:18.080  4574  4666 D BtGatt.ScanManager: Starting BLE batch scan
11-24 04:34:18.080  4574  4666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 04:34:18.088  4574  4655 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 04:34:18.088  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:18.092  4574  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 04:34:18.092  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:18.571  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 04:34:18.571  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 04:34:18.572  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 04:34:23.068  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:23.068  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:23.068  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 04:34:23.068  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:34:23.069  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 04:34:23.069  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:23.069  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 04:34:23.069  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 04:34:23.069  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.069  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 04:34:23.070  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 04:34:23.072  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.072  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.072  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.072  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 04:34:23.073  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.075  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:23.076  4574  4785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 04:34:23.077  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 04:34:23.078  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 04:34:23.079  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:34:23.081  4574  4591 D BtGatt.GattService: stopScan() - queue size =1
11-24 04:34:23.083  4574  4785 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 04:34:23.084  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 04:34:23.084  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.085  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 04:34:23.085  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.085  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.085  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.085  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.086  4574  4574 D BtGatt.ScanManager: awakened up at time 188129
11-24 04:34:23.086  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 04:34:23.086  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.086  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.086  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.086  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 04:34:23.088  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 04:34:23.089  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:34:23.089  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.091  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.091  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:23.091  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:23.091  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:23.093  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 04:34:23.093  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:23.093  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 04:34:23.093  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.093  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 04:34:23.094  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 04:34:23.094  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.094  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 04:34:23.094  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.094  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:23.094  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.094  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.096  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.097  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:34:23.097  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 04:34:23.110  4574  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-24 04:34:23.110  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:23.110  4574  4655 D BtGatt.GattService: current time is 188154087404
11-24 04:34:23.111  4574  4655 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -71, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -66, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -69, 68, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -74, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -71, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, 57, 25, -57, 101, -38, 1, 0, -96, 57, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, 82, -54, 95, 3, 3, -12, 24, -109, 64, -15, -85, 28, 6, 8, 116, 105, 110, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-24 04:34:23.111  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 04:34:23.111  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 04:34:23.111  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 04:34:23.112  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 04:34:23.112  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 04:34:23.112  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 1,11, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 04:34:23.112  4574  4655 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -85, -24, 108, -51, -91, -51, 103, 118, 82, -54, 95, 3, 3, -12, 24, -109, 64, -15, -85, 6, 8, 116, 105, 110, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,11-24 04:34:23.117  4574  4655 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 04:34:23.117  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:23.117  4574  4666 D BtGatt.ScanManager: stopping BLe Batch
,11-24 04:34:23.123  4574  4655 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 04:34:23.123  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:34:23.123  4574  4666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 04:34:23.127  4574  4655 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:34:23.128  4574  4655 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:34:23.567   930  5392 D NetlinkSocketObserver: NeighborEvent{elapsedMs=188610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 04:34:23.595  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 04:34:23.595  5639  5639 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:23.595  5639  5639 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 04:34:25.142   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:26.144   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:27.145   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:28.093  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:28.094  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 04:34:28.094  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:28.094  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 04:34:28.094  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 04:34:28.094  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 04:34:28.094  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.095  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.095  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:28.095  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.095  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.095  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:34:28.098  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.099  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.102  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.102  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.102  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.103  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 04:34:28.103  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.103  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.103  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.105  5639  5687 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-24 04:34:28.106  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.107  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.107  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:28.107  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.107  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.107  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.108  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.108  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.108  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.108  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.109  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.112  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.112  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.112  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.112  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 04:34:28.112  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.112  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.112  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:28.114  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 04:34:28.114  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:28.114  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.114  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:28.114  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.114  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.114  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
,11-24 04:34:28.115  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.115  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.115  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.115  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.115  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.117  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.117  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.117  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.117  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.117  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.117  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:28.118  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:28.119  5639  5687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 04:34:28.119  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.119  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.119  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:28.119  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 04:34:28.119  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.119  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.119  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.120  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.120  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.120  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.120  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.122  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.122  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.122  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.122  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.122  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 04:34:28.122  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.122  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.123  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 04:34:28.124  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.124  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.124  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:28.124  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.124  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.124  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.124  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.124  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:28.124  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.124  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.124  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.127  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.127  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.127  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.127  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.127  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.127  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.127  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:28.128  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 04:34:28.128  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:28.128  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:28.129  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 04:34:28.129  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:28.129  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:28.129  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 04:34:28.129  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:28.129  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 04:34:28.129  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.129  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.129  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:28.130  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.130  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.130  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.130  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.130  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.130  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.131  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.131  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.135  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.135  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.135  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.136  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.136  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.136  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:28.137  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:28.139  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 04:34:28.139  5639  5687 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 04:34:28.139  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 04:34:28.145  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 04:34:28.145  5639  5687 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 04:34:28.146   546   546 I ServiceManager: Waiting for service AtCmdFwd...
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 04:34:28.146  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 04:34:28.147  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 04:34:28.147  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-24 04:34:28.147  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 04:34:28.147  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 04:34:28.147  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 04:34:28.147  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 04:34:28.148  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 04:34:28.149  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 04:34:28.149  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 04:34:28.149  5639  5687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 04:34:28.149  5639  5687 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,11-24 04:34:28.149  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 04:34:28.149  5639  5687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 04:34:28.149  5639  5687 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 04:34:28.150  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 04:34:28.150  5639  5687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 04:34:28.150  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 04:34:28.154  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 04:34:28.155  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 04:34:28.155  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 04:34:28.155  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 04:34:28.156  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 04:34:28.156  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,11-24 04:34:28.156  5639  5687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 04:34:28.156  5639  5687 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 04:34:28.156  5639  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-24 04:34:28.156  5639  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 04:34:28.156  5639  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 04:34:28.156  5639  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-24 04:34:28.157  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:28.157  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.157  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:28.157  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.158  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.158  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,11-24 04:34:28.159  5639  5689 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 04:34:28.158  4785  4785 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32979]" dev="sockfs" ino=32979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 04:34:28.158  4785  4785 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32979]" dev="sockfs" ino=32979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 04:34:28.159  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.159  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.159  5639  5689 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 04:34:28.159  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.159  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.159  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.160  5639  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-24 04:34:28.160  5639  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 04:34:28.160  5639  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
,11-24 04:34:28.160  5639  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
11-24 04:34:28.160  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.160  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.161  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.161  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.161  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.161  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.161  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.162  5639  5687 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 04:34:28.162  5639  5689 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
,11-24 04:34:28.162  5639  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 04:34:28.162  5639  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
11-24 04:34:28.162  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.162  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.162  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:28.162  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.162  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.163  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
,11-24 04:34:28.163  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.163  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.163  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.163  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.163  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.166  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.167  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.168  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.168  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 04:34:28.168  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.168  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.168  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.169  5639  5687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 04:34:28.169  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.169  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.169  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:28.169  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.169  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 04:34:28.170  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.170  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.170  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.170  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.170  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.170  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.171  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.171  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:28.171  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.171  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.171  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.171  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.171  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.172  5639  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 04:34:28.172  5639  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 04:34:28.172  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 04:34:28.172  5639  5687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-24 04:34:28.172  5639  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 04:34:28.172  5639  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 04:34:28.173  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 04:34:28.173  5639  5687 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 04:34:28.173  5639  5687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 04:34:28.173  5639  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 04:34:28.173  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 04:34:28.173  5639  5687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 04:34:28.173  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:28.173  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:28.173  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:28.173  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.173  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 04:34:28.173  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.173  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.173  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.173  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:28.174  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.174  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.175  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.175  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.175  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:28.175  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:28.175  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:28.175  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:28.175  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.176  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:28.176  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:28.176  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:28.176  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:28.176  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:28.176  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:29.147   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:34:30.148   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 04:34:33.177  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:33.177  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.177  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 04:34:33.177  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.178  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.178  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:33.178  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:33.178  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:33.178  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:33.179  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.179  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.179  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.179  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.179  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:34:33.180  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.180  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.183  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.184  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.184  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.184  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 04:34:33.184  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:33.184  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.184  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:33.190  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 04:34:33.191  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:34:33.191  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 04:34:33.196  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 04:34:33.198  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 04:34:33.199  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-24 04:34:33.201  4589  4589 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32982]" dev="sockfs" ino=32982 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 04:34:33.199  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 04:34:33.199  5639  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 04:34:33.200  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 04:34:33.200  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 04:34:33.200  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 04:34:33.201  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:33.201  5639  5691 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 04:34:33.201  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 04:34:33.201  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 04:34:33.201  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-24 04:34:33.201  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:34:33.202  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 04:34:33.203  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 04:34:33.203  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.203  5639  5639 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-24 04:34:33.203  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.203  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 04:34:33.203  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.203  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 04:34:33.204  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 04:34:33.204  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.201  4589  4589 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32982]" dev="sockfs" ino=32982 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 04:34:33.206  5639  5691 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 04:34:33.207  5639  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-24 04:34:33.207  5639  5691 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-24 04:34:33.210  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:33.210  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:33.210  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.211  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.211  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.211  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:33.211  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 04:34:33.211  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:34:33.211  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:33.211  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 04:34:33.211  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:34:33.211  5639  5639 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.211  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 04:34:33.211  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:34:33.211  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.212  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.212  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.212  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.212  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:33.212  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.212  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.214  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.214  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.214  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:33.215  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:33.215  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:33.215  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.215  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.217  5639  5687 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 04:34:33.217  5639  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-24 04:34:33.218  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 04:34:33.218  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:33.218  5639  5687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 04:34:33.220  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:33.220  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:33.220  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:33.220  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:33.220  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.221  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.221  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.221  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.221  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:33.221  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.221  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.223  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.223  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.223  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.223  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 04:34:33.223  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:33.223  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.223  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.228  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:33.229  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:33.229  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:33.230  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:33.230  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.230  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.230  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.230  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.230  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:33.230  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.231  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.233  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.233  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.233  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.234  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 04:34:33.234  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:33.234  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.234  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.235  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:34:33.235  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:34:33.235  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:34:33.236  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:34:33.236  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:34:33.236  5639  5687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db4a2e0 not in the list
11-24 04:34:33.236  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.236  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
11-24 04:34:33.236  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:33.236  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.236  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.239  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.239  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:34:33.239  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:34:33.239  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:34:33.239  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:34:33.239  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:34:33.239  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c9c999 not in the list
,11-24 04:34:33.241  5639  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 04:34:33.241  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 04:34:33.241  5639  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-24 04:34:33.241  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 04:34:33.241  5639  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 04:34:33.242  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 04:34:33.244  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 04:34:33.244  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 04:34:33.245  5639  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 04:34:33.245  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-24 04:34:33.245  5639  5687 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 04:34:33.245  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 04:34:33.245  5639  5687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 04:34:33.245  5639  5687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 04:34:33.246  5639  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 04:34:33.246  5639  5687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-24 04:34:33.246  5639  5687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 04:34:33.246  5639  5687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 04:34:33.247  5639  5687 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 04:34:33.247  5639  5687 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 04:34:33.248  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:34:33.248  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@939e10e added. We now have 3 listener(s)
,11-24 04:34:33.249  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:34:33.252  5639  5687 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 04:34:33.252   930  4817 D WifiService: setWifiEnabled: true pid=5639, uid=10077
11-24 04:34:33.252   930  4817 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 04:34:33.289  4574  4778 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 04:34:33.289  4574  4783 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 04:34:33.712  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 04:34:37.697   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:34:38.258  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 04:34:38.259  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0b472f added. We now have 4 listener(s)
,11-24 04:34:38.259  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:34:38.273  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:38.273  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f0b472f removed from the list
11-24 04:34:38.273  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:38.275  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:34:38.275  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d7d13c added. We now have 4 listener(s)
11-24 04:34:38.275  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:34:38.279  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:34:38.279  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d7d13c removed from the list
,11-24 04:34:38.279  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:34:38.281  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:34:38.281  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20c8ec5 added. We now have 4 listener(s)
11-24 04:34:38.281  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:34:38.287   930   941 D WifiService: setWifiEnabled: false pid=5639, uid=10077
11-24 04:34:38.287   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 04:34:38.291   930  2929 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 04:34:38.291   930  2929 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 04:34:38.291   930  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 04:34:38.292   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 04:34:38.296  4574  4648 D BluetoothAdapterState: Current state: ON, message: 23
11-24 04:34:38.296  4574  4648 D BluetoothAdapterProperties: Setting state to 13
11-24 04:34:38.296  4574  4648 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 04:34:38.298  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:34:38.298  4574  4648 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 04:34:38.299  4574  4648 I BluetoothAdapterState: Entering PendingCommandState
,11-24 04:34:38.299  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 04:34:38.300  4574  4655 D BluetoothAdapterProperties: Scan Mode:20
11-24 04:34:38.300  4574  4648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 04:34:38.303  4574  4574 D HeadsetService: Received stop request...Stopping profile...
11-24 04:34:38.305   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:38.305   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:38.305   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:38.305  3771  3986 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:38.306  4574  4574 D A2dpService: Received stop request...Stopping profile...
11-24 04:34:38.306  4574  4788 D A2dpStateMachine: Exit Disconnected: -1
11-24 04:34:38.306  3100  3962 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:38.307  3100  3100 D HeadsetProfile: Bluetooth service disconnected
11-24 04:34:38.308   930   930 D BluetoothA2dp: Proxy object disconnected
11-24 04:34:38.309  3100  3100 D BluetoothA2dp: Proxy object disconnected
11-24 04:34:38.309  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.309   930  5393 D DhcpClient: Clearing IP address
11-24 04:34:38.310   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 04:34:38.310  4574  4574 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:38.311  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.311  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:38.311  4574  4574 D HidService: Received stop request...Stopping profile...
11-24 04:34:38.311  4574  4574 D HidService: Stopping Bluetooth HidService
11-24 04:34:38.312  3100  3100 D BluetoothInputDevice: Proxy object disconnected
11-24 04:34:38.312  3100  3100 D HidProfile: Bluetooth service disconnected
11-24 04:34:38.315  4574  4574 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 04:34:38.315  4574  4574 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 04:34:38.315  4574  4778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:38.315  4574  4778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:38.315  4574  4778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:38.316  4574  4655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 04:34:38.316  4574  4655 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 04:34:38.316  4574  4574 D HealthService: Received stop request...Stopping profile...
,11-24 04:34:38.317   508   922 D CommandListener: Setting iface cfg
11-24 04:34:38.317  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.317  4574  4574 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:38.317  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.317  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 04:34:38.318  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 04:34:38.318  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 04:34:38.318  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:38.318  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 04:34:38.319  4574  4778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 04:34:38.319  5639  5687 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 04:34:38.319  4574  4778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:38.319  4574  4655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 04:34:38.319  4574  4778 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 04:34:38.319  4574  4778 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 04:34:38.319  4574  4778 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 04:34:38.319  4574  4778 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 04:34:38.320  4574  4574 D PanService: Received stop request...Stopping profile...
,11-24 04:34:38.321  3100  3100 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 04:34:38.321   930  5394 D DhcpClient: Receive thread stopped
11-24 04:34:38.321  3100  3100 D PanProfile: Bluetooth service disconnected
11-24 04:34:38.321  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.321  4574  4574 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:38.321  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.321  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:38.322  4574  4574 D BluetoothMapService: Received stop request...Stopping profile...
11-24 04:34:38.322  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:38.322  4574  4574 D BluetoothMapService: stop()
11-24 04:34:38.323  4574  4574 D BluetoothMapAppObserver: deinitObservers()
,11-24 04:34:38.323  4574  4574 D BluetoothMapAppObserver: removeReceiver()
11-24 04:34:38.325  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:38.325  3100  3100 D BluetoothMap: Proxy object disconnected
11-24 04:34:38.325  3100  3100 D MapProfile: Bluetooth service disconnected
11-24 04:34:38.325  4574  4574 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 04:34:38.325  4574  4574 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 04:34:38.326  4574  4655 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 04:34:38.326  4574  4574 D SapService: Received stop request...Stopping profile...
11-24 04:34:38.326  4574  4574 V SapService: stop()
,11-24 04:34:38.328  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.328  4574  4574 V BluetoothAdapterState: isTurningOn()=false
,11-24 04:34:38.328  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.328  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:38.328  4574  4574 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 04:34:38.329  3556  5460 V NativeCrypto: Read error: ssl=0x7f8269fb80: I/O error during system call, Connection timed out
11-24 04:34:38.329  4574  4574 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 04:34:38.329  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.329  4574  4574 V BluetoothAdapterState: isTurningOn()=false
,11-24 04:34:38.329  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.329  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:38.329  4574  4655 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 04:34:38.329  4574  4574 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 04:34:38.329  4574  4574 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 04:34:38.330  4574  4574 D BluetoothMapService: MAP Service closeService in
11-24 04:34:38.330  4574  4574 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 04:34:38.330  4574  4574 D ObexServerSockets0: shutdown(block = true)
11-24 04:34:38.330  3556  5460 V NativeCrypto: SSL shutdown failed: ssl=0x7f8269fb80: I/O error during system call, Broken pipe
,11-24 04:34:38.331  4574  4821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-24 04:34:38.331  4574  4574 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 04:34:38.331  4574  4574 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 04:34:38.331  4574  4783 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-24 04:34:38.331  4574  4822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-24 04:34:38.331  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.332  4574  4574 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:38.332  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.332  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:38.336  4574  4574 D BluetoothMapService: cleanup()
11-24 04:34:38.336  4574  4574 D BluetoothMapService: MAP Service closeService in
11-24 04:34:38.337  4574  4574 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:38.337  4574  4574 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:38.337  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.337  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:38.337   930  3693 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-24 04:34:38.337  4574  4648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 04:34:38.337  4574  4648 D BluetoothAdapterProperties: Setting state to 15
11-24 04:34:38.337  4574  4648 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 04:34:38.337   930  5391 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-24 04:34:38.338   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 04:34:38.338  4574  4648 I BluetoothAdapterState: Entering BleOnState
,11-24 04:34:38.338   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 04:34:38.340   930  5391 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-24 04:34:38.342   544   544 E Parcel  : Reading a NULL string not supported here.
11-24 04:34:38.342   930   930 D RttService: SCAN_AVAILABLE : 1
11-24 04:34:38.342   930  3048 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 04:34:38.345   930  2944 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-24 04:34:38.347  3734  3901 W QCNEJ   : |CORE| network lost: 100
11-24 04:34:38.347  3734  3901 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 04:34:38.350  3771  3986 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 04:34:38.350   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:38.350  4574  4574 I BtOppRfcommListener: stopping Accept Thread
11-24 04:34:38.350  3100  3113 D BluetoothMap: onBluetoothStateChange: up=false
11-24 04:34:38.350  4574  5330 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 04:34:38.350  4574  5330 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 04:34:38.352  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:38.352  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 04:34:38.353  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 04:34:38.353  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 04:34:38.363   930  3693 I ActivityManager: Start proc 5699:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-24 04:34:38.365  3100  3962 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 04:34:38.366  3100  3123 D BluetoothPan: onBluetoothStateChange on: false
,11-24 04:34:38.366   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:38.367  3100  3967 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 04:34:38.368   930  2929 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 04:34:38.369   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 04:34:38.369   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:38.369  3100  3113 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:38.370  3100  3962 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 04:34:38.371  4574  4648 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 04:34:38.371  4574  4648 D BluetoothAdapterProperties: Setting state to 16
11-24 04:34:38.371  4574  4648 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 04:34:38.371  4574  4648 D BluetoothAdapterProperties: onBleDisable
11-24 04:34:38.372  4574  4648 I BluetoothAdapterState: Entering PendingCommandState
11-24 04:34:38.373  4574  4655 D BluetoothAdapterProperties: Scan Mode:20
11-24 04:34:38.372  4574  4649 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 04:34:38.374  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:38.376  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:38.376   930  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 04:34:38.377  4574  4778 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 04:34:38.377  4574  4778 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 04:34:38.393   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:34:38.403  5699  5699 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 04:34:38.411   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:34:38.412   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 04:34:38.412   508   922 D TetherController: Setting IP forward enable = 0
11-24 04:34:38.413   930  2944 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-24 04:34:38.413   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 04:34:38.414   930  2929 D DhcpClient: doQuit
11-24 04:34:38.414   930  2929 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 04:34:38.415  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 04:34:38.415   930  5393 D DhcpClient: onQuitting
11-24 04:34:38.415  3422  3422 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 04:34:38.416   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 04:34:38.417  5301  5301 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e4285c9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 04:34:38.419  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:38.420  4932  4932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 04:34:38.424  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:38.424  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 04:34:38.425  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:38.425  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 04:34:38.428  5047  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 04:34:38.428  5047  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 04:34:38.428  5047  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 04:34:38.428  5047  5073 E SarControlService: no key has been found,reset the power
11-24 04:34:38.428  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 04:34:38.429  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 04:34:38.429  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 04:34:38.429  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 04:34:38.429  5074  5074 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 04:34:38.432  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 04:34:38.432  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 04:34:38.432  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 04:34:38.434  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 04:34:38.434  5074  5074 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 04:34:38.437  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000ea03000000000000ffffffff]
,11-24 04:34:38.437  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 04:34:38.437  5074  5090 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 04:34:38.437  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:34:38.437  5047  5058 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 04:34:38.441   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@323f45f:true
11-24 04:34:38.442  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000eb03000000000000ffffffff]
,11-24 04:34:38.442  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 04:34:38.442  5074  5090 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 04:34:38.443  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:34:38.443  5047  5059 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 04:34:38.443  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 04:34:38.445  3422  3422 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 04:34:38.459  3422  3422 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 04:34:38.461   930  3837 I ActivityManager: Start proc 5726:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 04:34:38.479  5699  5699 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 04:34:38.479   508   922 E Netd    : netlink response contains error (No such file or directory)
11-24 04:34:38.480   508   922 D TetherController: Setting IP forward enable = 0
11-24 04:34:38.480   930  2944 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 04:34:38.481   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 04:34:38.481  5699  5699 D BluetoothMap: Create BluetoothMap proxy object
,11-24 04:34:38.492  3422  3422 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 04:34:38.497  5699  5699 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 04:34:38.504  3422  3422 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 04:34:38.509  5726  5726 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 04:34:38.513  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,11-24 04:34:38.521   930  3693 I ActivityManager: Killing 4973:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 04:34:38.584  4574  4655 I bt_hci  : shut_down
,11-24 04:34:38.588  4574  4670 D bt_hwcfg: hw_epilog_process
,11-24 04:34:38.588  4574  4670 I bt_vendor: low_power_mode_cb
,11-24 04:34:38.591  4574  4670 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 04:34:38.591  4574  4670 I bt_vendor: epilog_cb
11-24 04:34:38.591  4574  4670 I bt_hci  : epilog_finished_callback
11-24 04:34:38.593  4574  4655 I bt_hci_h4: hal_close
11-24 04:34:38.593  4574  4655 I bt_userial_vendor: device fd = 54 close
,11-24 04:34:38.605   930  2929 D wifi    : In wifi stop Hal
,11-24 04:34:38.606   930  2929 D wifi    : halHandle = 0x7f80b59b80, mVM = 0x7f9d18d140, mCls = 0x100a02
11-24 04:34:38.607   930  3421 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 04:34:38.607   930  3421 D WifiHAL : Got a signal to exit!!!
11-24 04:34:38.607   930  3421 I WifiHAL : Exit wifi_event_loop
11-24 04:34:38.607   930  2929 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 04:34:38.607   930  2929 E WifiHAL : Event processing terminated
11-24 04:34:38.607   930  2929 D wifi    : In wifi cleaned up handler
11-24 04:34:38.607   930  2929 I WifiHAL : Internal cleanup completed
11-24 04:34:38.606  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 04:34:38.609  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:38.610  4039  4205 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 04:34:38.630   930  3421 D wifi    : set interface wlan0 flags (DOWN)
11-24 04:34:38.630   930  2929 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 04:34:38.702  4574  4649 D bt_stack_manager: event_shut_down_stack finished.
,11-24 04:34:38.702  4574  4648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 04:34:38.704  4574  4648 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 04:34:38.704  4574  4574 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 04:34:38.704  4574  4574 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 04:34:38.704  4574  4574 D BtGatt.GattService: stop()
11-24 04:34:38.704  4574  4574 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 04:34:38.706  4574  4574 V BluetoothAdapterState: isTurningOff()=false
11-24 04:34:38.706  4574  4574 V BluetoothAdapterState: isTurningOn()=false
,11-24 04:34:38.706  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:38.706  4574  4574 V BluetoothAdapterState: isBleTurningOff()=true
11-24 04:34:38.706  4574  4648 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 04:34:38.706  4574  4648 D BluetoothAdapterProperties: Setting state to 10
11-24 04:34:38.707  4574  4648 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 04:34:38.707  4574  4648 I BluetoothAdapterState: Entering OffState
,11-24 04:34:38.708   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-24 04:34:38.719  4574  4574 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 04:34:38.719  4574  4574 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 04:34:38.720  4574  4574 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 04:34:38.721  4574  4649 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 04:34:38.733  4574  4649 D bt_stack_manager: event_clean_up_stack finished.
,11-24 04:34:38.747  4574  4574 I art     : System.exit called, status: 0
,11-24 04:34:38.747  4574  4574 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 04:34:38.787  5726  5726 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 04:34:38.787  5726  5726 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.787  5726  5726 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.787  5726  5726 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.787  5726  5726 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.787  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.788  5726  5726 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.788  5726  5726 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.788  5726  5726 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:34:38.788  5726  5726 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:34:38.798   930  3138 I ActivityManager: Process com.android.bluetooth (pid 4574) has died
,11-24 04:34:38.824  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 04:34:38.832   930   947 D Tethering: InitialState.processMessage what=4
11-24 04:34:38.838   930  3837 I ActivityManager: Start proc 5762:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-24 04:34:38.839  5699  5699 D DockEventReceiver: finishStartingService: stopping service
11-24 04:34:38.839   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-24 04:34:38.841   930  3837 I ActivityManager: Killing 5417:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 04:34:38.913  5762  5762 D AdapterServiceConfig: Adding HeadsetService
,11-24 04:34:38.913  5762  5762 D AdapterServiceConfig: Adding A2dpService
,11-24 04:34:38.914  5762  5762 D AdapterServiceConfig: Adding HidService
11-24 04:34:38.914  5762  5762 D AdapterServiceConfig: Adding HealthService
11-24 04:34:38.914  5762  5762 D AdapterServiceConfig: Adding PanService
11-24 04:34:38.914  5762  5762 D AdapterServiceConfig: Adding GattService
11-24 04:34:38.914  5762  5762 D AdapterServiceConfig: Adding BluetoothMapService
11-24 04:34:38.914  5762  5762 D AdapterServiceConfig: Adding SapService
,11-24 04:34:38.916   930  3138 I ActivityManager: Killing 5429:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 04:34:38.970  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 04:34:38.979  3681  3681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 04:34:38.982  3681  3681 D SystemUpdateService: onCreate
,11-24 04:34:38.988  3681  3681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 04:34:38.996  3681  3681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 04:34:39.002  3681  5415 I iu.UploadsManager: num queued entries: 0
,11-24 04:34:39.003  3681  5415 I iu.UploadsManager: num updated entries: 0
,11-24 04:34:39.004  3681  5415 I iu.SyncManager: NEXT; no task
,11-24 04:34:39.005  3681  3681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 04:34:39.007  3681  3681 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 04:34:39.008  3681  5774 I SystemUpdateService: active receiver: enabled
,11-24 04:34:39.019   930   941 I ActivityManager: Start proc 5776:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 04:34:39.021  3681  5774 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 04:34:39.024  3681  5774 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 04:34:39.024  3681  5774 I SystemUpdateService: now status is 0 (complete)
11-24 04:34:39.024  3681  5774 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 04:34:39.024  3681  5774 I SystemUpdateService: file has been verified
,11-24 04:34:39.024  3681  5774 I SystemUpdateService: OTA package size = 21989297
,11-24 04:34:39.035  3681  5774 I SystemUpdateService: showing system update notification
,11-24 04:34:39.055  5776  5776 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 04:34:39.061  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 04:34:39.069  5776  5776 D SprintDMHelper: simOperator: 
,11-24 04:34:39.069  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 04:34:39.082   930  3693 I ActivityManager: Start proc 5788:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 04:34:39.085  3681  3681 D SystemUpdateService: onDestroy
,11-24 04:34:39.086   930   940 I ActivityManager: Killing 5444:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 04:34:39.158  5726  5750 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 04:34:39.185  5020  5802 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 04:34:39.193   930  3693 I ActivityManager: Start proc 5803:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 04:34:39.195   930  3397 I ActivityManager: Killing 5301:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 04:34:39.221   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c02e6e3:true
,11-24 04:34:39.263  5803  5803 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 04:34:39.427   930  3397 I ActivityManager: Killing 5495:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 04:34:39.458   930  3693 I ActivityManager: Start proc 5818:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 04:34:39.488  5818  5818 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 04:34:39.496   930  3693 I ActivityManager: Killing 4672:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 04:34:43.322   930  3837 D WifiService: setWifiEnabled: true pid=5639, uid=10077
11-24 04:34:43.322   930  3837 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 04:34:43.328   508   922 D SoftapController: Softap fwReload - Ok
,11-24 04:34:43.334   508   922 D CommandListener: Setting iface cfg
,11-24 04:34:43.335   508   922 D CommandListener: Trying to bring down wlan0
11-24 04:34:43.336   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 04:34:43.341   930  2929 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 04:34:43.917   930  2929 D wifi    : set interface wlan0 flags (UP)
11-24 04:34:43.920   930  2929 I WifiHAL : Initializing wifi
11-24 04:34:43.920   930  2929 I WifiHAL : Creating socket
,11-24 04:34:43.922   930  2929 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 04:34:43.922   930  2929 D wifi    : Did set static halHandle = 0x7f80b59b80
11-24 04:34:43.923   930  2929 D wifi    : halHandle = 0x7f80b59b80, mVM = 0x7f9d18d140, mCls = 0x1019ae
11-24 04:34:43.923   930  2929 D wifi    : array field set
11-24 04:34:43.923   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 04:34:43.923   930  2929 I WifiNative-HAL: interface[0] = wlan0
11-24 04:34:43.924   930  5836 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547620232064
11-24 04:34:43.925   930  5836 D wifi    : waitForHalEvents called, vm = 0x7f9d18d140, obj = 0x1019ae, env = 0x7f8140cec0
,11-24 04:34:43.991  5837  5837 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 04:34:44.006  5837  5837 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 04:34:44.027   930  2929 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 04:34:44.031  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:44.062  5837  5837 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 04:34:44.062  5837  5837 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 04:34:44.078   930  2929 D WifiConfigStore: Loading config and enabling all networks 
,11-24 04:34:44.079  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:44.079  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 04:34:44.079  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:44.080  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 04:34:44.091   930  2929 D WifiConfigStore: loaded 0 passpoint configs
,11-24 04:34:44.092   930  2929 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-24 04:34:44.092   930  2929 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 04:34:44.093   930  2929 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 04:34:44.095   930  2929 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 04:34:44.095   930  2929 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 04:34:44.095   930  2929 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 04:34:44.095   930  2929 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 04:34:44.099   930  2929 D WifiNative-HAL: Setting external_sim to 1
,11-24 04:34:44.099  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 04:34:44.099   930  2929 D wifi    : setting dfs flag to true, 0x7f840b5d60
,11-24 04:34:44.100   930  2929 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 04:34:44.100   930  2929 D wifi    : setting scan oui 0x7f840b5d60
11-24 04:34:44.100   930  2929 D WifiHAL : Sending mac address OUI
,11-24 04:34:44.104   930  2929 E native  : do suspend false
,11-24 04:34:44.111   930  2929 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 04:34:44.111   930   930 D RttService: SCAN_AVAILABLE : 3
11-24 04:34:44.111   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 04:34:44.111   930  3048 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 04:34:44.112   508   922 D CommandListener: Setting iface cfg
,11-24 04:34:44.116   930  2927 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-24 04:34:44.116   930  2927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 04:34:44.123   930  2927 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 04:34:44.128   930  2927 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 04:34:44.128   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=209171 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-24 04:34:47.213  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:34:47.220  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:34:47.227  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:34:47.231  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:34:47.282   930  2929 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 04:34:47.283   930  2929 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 04:34:47.283   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 04:34:47.298   930  2929 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 04:34:47.337   930  2929 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 04:34:47.339  5837  5837 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 04:34:47.773  5837  5837 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 04:34:47.822  5837  5837 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-24 04:34:47.823  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 04:34:47.839   930  2929 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 04:34:47.839   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 04:34:47.840   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 04:34:47.860   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 04:34:47.880   508   922 D CommandListener: Setting iface cfg
,11-24 04:34:47.887   930  2929 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 04:34:47.895   930  5843 D DhcpClient: Receive thread started
,11-24 04:34:47.901   930  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 04:34:47.901   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 04:34:47.901   930  2944 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 04:34:47.989   930  2929 E native  : do suspend false
,11-24 04:34:48.010   930  5842 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 04:34:48.030   930  5843 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172630, domain null
,11-24 04:34:48.031   930  5842 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172630 seconds
,11-24 04:34:48.034   930  5842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 04:34:48.054   930  5843 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 04:34:48.055   930  5842 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 04:34:48.058   508   922 D CommandListener: Setting iface cfg
11-24 04:34:48.063   930  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 04:34:48.067   930  5842 D DhcpClient: Scheduling renewal in 86399s
,11-24 04:34:48.082   930  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 04:34:48.083   930  2929 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 04:34:48.084   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 04:34:48.086   930  2944 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 04:34:48.090   930  2929 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 04:34:48.134   930  2944 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 04:34:48.135   930  2944 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 04:34:48.137   930  2944 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 04:34:48.140   930  2944 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 04:34:48.143   930  2944 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 04:34:48.151   930  2944 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 04:34:48.155   930  2944 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 04:34:48.155   930  2944 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 04:34:48.155   930  2944 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 04:34:48.155   930  2944 D ConnectivityService:    accepting network in place of null
11-24 04:34:48.155   930  2929 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 04:34:48.155   930  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 04:34:48.156   930  2944 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 04:34:48.167   930  5841 D NetlinkSocketObserver: NeighborEvent{elapsedMs=213210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 04:34:48.176   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:34:48.198   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:34:48.201   930  2944 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 04:34:48.202   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 04:34:48.202  3734  3901 W QCNEJ   : |CORE| network available: 101
11-24 04:34:48.203   930  2944 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 04:34:48.203   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 04:34:48.206  3734  3901 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 04:34:48.207  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 04:34:48.207  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 04:34:48.207  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:48.207  3734  3901 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 04:34:48.208  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 04:34:48.208  3734  3901 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 04:34:48.219  5047  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 04:34:48.219  5047  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 04:34:48.219  5047  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-24 04:34:48.219  5047  5073 E SarControlService: no key has been found,reset the power
11-24 04:34:48.220  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 04:34:48.220  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 04:34:48.220  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 04:34:48.220  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 04:34:48.220  5074  5074 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 04:34:48.221  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 04:34:48.221  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 04:34:48.221  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 04:34:48.222  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 04:34:48.222  5074  5074 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 04:34:48.224  4932  4932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 04:34:48.227  3681  3681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 04:34:48.230  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000ec03000000000000ffffffff]
,11-24 04:34:48.230  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 04:34:48.230  5074  5090 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 04:34:48.230  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:34:48.231  5047  5058 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 04:34:48.231  3681  3681 D SystemUpdateService: onCreate
,11-24 04:34:48.235   930  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 04:34:48.237  3681  3681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 04:34:48.238  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000ed03000000000000ffffffff]
11-24 04:34:48.238  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 04:34:48.238  5074  5090 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-24 04:34:48.239  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:34:48.239  5047  5059 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 04:34:48.249  3681  3681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 04:34:48.256  3681  5415 I iu.UploadsManager: num queued entries: 0
11-24 04:34:48.256  3681  5415 I iu.UploadsManager: num updated entries: 0
,11-24 04:34:48.261  3681  3681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 04:34:48.262  3681  5853 I SystemUpdateService: active receiver: enabled
11-24 04:34:48.263  3681  3681 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 04:34:48.266  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 04:34:48.271  5776  5776 D SprintDMHelper: simOperator: 
11-24 04:34:48.271  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 04:34:48.281  3681  5415 I iu.SyncManager: NEXT; no task
,11-24 04:34:48.291   930  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 09:34:48 GMT], X-Android-Received-Millis=[1479980088290], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479980088265]}
,11-24 04:34:48.291  3681  5853 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 04:34:48.292   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 04:34:48.292   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 04:34:48.292   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 04:34:48.293   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 04:34:48.306  3681  5853 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 04:34:48.306  3681  5853 I SystemUpdateService: now status is 0 (complete)
11-24 04:34:48.306  3681  5853 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 04:34:48.306  3681  5853 I SystemUpdateService: file has been verified
11-24 04:34:48.307  3681  5853 I SystemUpdateService: OTA package size = 21989297
,11-24 04:34:48.313  3681  5853 I SystemUpdateService: showing system update notification
,11-24 04:34:48.324  3681  3681 D SystemUpdateService: onDestroy
,11-24 04:34:48.326   930  3138 D WifiService: setWifiEnabled: false pid=5639, uid=10077
11-24 04:34:48.326   930  3138 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 04:34:48.328   930  2929 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 04:34:48.328   930  2929 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 04:34:48.328   930  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 04:34:48.328   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 04:34:48.338   930  5842 D DhcpClient: Clearing IP address
,11-24 04:34:48.338   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 04:34:48.340   508   922 D CommandListener: Setting iface cfg
,11-24 04:34:48.342  3556  5854 V NativeCrypto: SSL handshake aborted: ssl=0x7f932cc480: I/O error during system call, Connection timed out
11-24 04:34:48.344  5020  5858 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
11-24 04:34:48.347   930  4817 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-24 04:34:48.347   930  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-24 04:34:48.348   930  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 04:34:48.353   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 04:34:48.353   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 04:34:48.356   544   544 E Parcel  : Reading a NULL string not supported here.
11-24 04:34:48.358   930   930 D RttService: SCAN_AVAILABLE : 1
11-24 04:34:48.358   930  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-24 04:34:48.359   930  3048 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 04:34:48.360   930  2944 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.22.110 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(Sou,rceFile:1100)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
11-24 04:34:48.361  5020  5858 W Babel_NetworkConnectionCheckingService: 	... 23 more
11-24 04:34:48.361  5020  5858 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 04:34:48.362   930  2929 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 04:34:48.364  3734  3901 W QCNEJ   : |CORE| network lost: 101
11-24 04:34:48.364  3734  3901 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 04:34:48.366   930  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 04:34:48.368   930  5843 D DhcpClient: Receive thread stopped
,11-24 04:34:48.386   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:34:48.405   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:34:48.405   930  2944 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 04:34:48.405   508   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 04:34:48.406   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 04:34:48.407   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 04:34:48.409  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:48.409  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 04:34:48.409  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:48.410  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 04:34:48.410  4932  4932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 04:34:48.414  3681  3681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 04:34:48.416  5047  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 04:34:48.416  5047  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 04:34:48.416  5047  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-24 04:34:48.421  5047  5073 E SarControlService: no key has been found,reset the power
,11-24 04:34:48.422  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 04:34:48.422  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 04:34:48.422  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 04:34:48.422  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 04:34:48.422  5074  5074 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 04:34:48.424  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 04:34:48.424  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 04:34:48.424  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 04:34:48.424  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 04:34:48.424  5074  5074 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 04:34:48.425  3681  3681 D SystemUpdateService: onCreate
,11-24 04:34:48.429  3681  3681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 04:34:48.430  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000ee03000000000000ffffffff]
11-24 04:34:48.431  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 04:34:48.431  5074  5090 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 04:34:48.431  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:34:48.431  5047  5059 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 04:34:48.431  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000ef03000000000000ffffffff]
11-24 04:34:48.431  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 04:34:48.431  5074  5090 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 04:34:48.432  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:34:48.432  5047  5058 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 04:34:48.438  3681  5871 I SystemUpdateService: active receiver: enabled
,11-24 04:34:48.440  3681  3681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 04:34:48.445  3681  5415 I iu.UploadsManager: num queued entries: 0
11-24 04:34:48.446  3681  5415 I iu.UploadsManager: num updated entries: 0
,11-24 04:34:48.448  3681  3681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 04:34:48.450  3681  3681 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 04:34:48.453  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 04:34:48.455   508   922 E Netd    : netlink response contains error (No such file or directory)
11-24 04:34:48.456   930  2944 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 04:34:48.456   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 04:34:48.457  5776  5776 D SprintDMHelper: simOperator: 
11-24 04:34:48.457   930  2929 D DhcpClient: doQuit
11-24 04:34:48.457  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 04:34:48.457   930  2929 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 04:34:48.457   930  5842 D DhcpClient: onQuitting
11-24 04:34:48.458  5837  5837 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 04:34:48.461  3681  5871 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 04:34:48.462  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:48.462  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 04:34:48.462  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:48.462  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 04:34:48.465  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 04:34:48.468  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 04:34:48.473  3681  5415 I iu.SyncManager: NEXT; no task
,11-24 04:34:48.475  5020  5875 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 04:34:48.479  3681  5871 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 04:34:48.479  3681  5871 I SystemUpdateService: now status is 0 (complete)
11-24 04:34:48.479  3681  5871 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 04:34:48.479  3681  5871 I SystemUpdateService: file has been verified
,11-24 04:34:48.480  3681  5871 I SystemUpdateService: OTA package size = 21989297
,11-24 04:34:48.495  3681  5871 I SystemUpdateService: showing system update notification
,11-24 04:34:48.502  5837  5837 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 04:34:48.502  3681  3681 D SystemUpdateService: onDestroy
,11-24 04:34:48.507  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 04:34:48.611   930  2929 D wifi    : In wifi stop Hal
,11-24 04:34:48.612   930  2929 D wifi    : halHandle = 0x7f80b59b80, mVM = 0x7f9d18d140, mCls = 0x1019ae
,11-24 04:34:48.612   930  5836 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 11
,11-24 04:34:48.612   930  5836 D WifiHAL : Got a signal to exit!!!
,11-24 04:34:48.612   930  5836 I WifiHAL : Exit wifi_event_loop
11-24 04:34:48.613   930  2929 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 04:34:48.613   930  2929 E WifiHAL : Event processing terminated
,11-24 04:34:48.614   930  2929 D wifi    : In wifi cleaned up handler
,11-24 04:34:48.614   930  2929 I WifiHAL : Internal cleanup completed
11-24 04:34:48.619  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:48.621  4039  4205 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 04:34:48.625  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 04:34:48.650   930  5836 D wifi    : set interface wlan0 flags (DOWN)
,11-24 04:34:48.650   930  2929 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 04:34:48.856   930   947 D Tethering: InitialState.processMessage what=4
,11-24 04:34:48.862   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 04:34:49.202   930  2944 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 04:34:53.364   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@99af82:true
,11-24 04:34:53.365  5762  5762 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 04:34:53.371  5762  5762 I bt_bluedroid: init
,11-24 04:34:53.371  5762  5878 I BluetoothAdapterState: Entering OffState
,11-24 04:34:53.374  5762  5879 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 04:34:53.374  5762  5879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 04:34:53.374  5762  5879 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 04:34:53.375  5762  5879 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 04:34:53.376  5762  5762 I bt_bluedroid: get_profile_interface socket
,11-24 04:34:53.379  5762  5762 I bt_bluedroid: get_profile_interface sdp
11-24 04:34:53.379  5762  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 04:34:53.381  5762  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 04:34:53.387  5762  5773 I bt_bluedroid: config_hci_snoop_log
11-24 04:34:53.388   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 04:34:53.395  5762  5878 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 04:34:53.395  5762  5878 D BluetoothAdapterProperties: Setting state to 14
11-24 04:34:53.395  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 04:34:53.397  5762  5878 D BluetoothBondStateMachine: make
,11-24 04:34:53.399  5762  5883 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 04:34:53.401  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
,11-24 04:34:53.403  5762  5762 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 04:34:53.405  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:53.406  5762  5762 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 04:34:53.406  5762  5762 D BtGatt.GattService: Received start request. Starting profile...
,11-24 04:34:53.406  5762  5762 D BtGatt.GattService: start()
11-24 04:34:53.407  5762  5762 I bt_bluedroid: get_profile_interface gatt
,11-24 04:34:53.408  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:53.408  5762  5762 D BtGatt.AdvertiseManager: advertise manager created
,11-24 04:34:53.413  5762  5762 V BluetoothAdapterState: isTurningOff()=false
,11-24 04:34:53.413  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:53.413  5762  5762 V BluetoothAdapterState: isBleTurningOn()=true
11-24 04:34:53.413  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:53.414  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 04:34:53.415  5762  5878 I bt_bluedroid: bt_bluedroid
,11-24 04:34:53.416  5762  5879 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 04:34:53.416  5762  5879 I bt_hci  : start_up
,11-24 04:34:53.422  5762  5879 I bt_vendor: alloc value 0xf4138871
,11-24 04:34:53.422  5762  5879 I bt_vendor: init
11-24 04:34:53.422  5762  5879 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 04:34:53.422  5762  5879 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 04:34:53.533  5762  5879 D bt_hci  : start_up starting async portion
,11-24 04:34:53.534  5762  5886 I bt_hci  : event_finish_startup
11-24 04:34:53.534  5762  5886 I bt_hci_h4: hal_open
11-24 04:34:53.534  5762  5886 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 04:34:53.531  5887  5887 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 04:34:53.537  5762  5886 I bt_userial_vendor: device fd = 54 open
,11-24 04:34:53.551  5762  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 04:34:53.554  5762  5886 D bt_hwcfg: Chipset BCM4358A3
,11-24 04:34:53.555  5762  5886 D bt_hwcfg: Target name = [BCM4358A3]
11-24 04:34:53.555  5762  5886 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 04:34:53.967  5762  5886 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 04:34:53.967  5762  5886 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 04:34:53.967  5762  5886 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 04:34:54.101  5762  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 04:34:54.102  5762  5886 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-24 04:34:54.104  5762  5886 I bt_hwcfg: vendor lib fwcfg completed
,11-24 04:34:54.104  5762  5886 I bt_vendor: firmware callback
11-24 04:34:54.104  5762  5886 I bt_hci  : firmware_config_callback
,11-24 04:34:54.112  5762  5889 I bt_btu  : btu_task pending for preload complete event
,11-24 04:34:54.112  5762  5889 I bt_btu_task: Bluetooth chip preload is complete
11-24 04:34:54.112  5762  5889 I bt_btu  : btu_task received preload complete event
,11-24 04:34:54.119  5762  5889 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 04:34:54.120  5762  5889 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 04:34:54.121  5762  5889 I         : BTE_InitTraceLevels -- TRC_PAN
,11-24 04:34:54.122  5762  5889 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 04:34:54.122  5762  5889 I         : BTE_InitTraceLevels -- TRC_GATT
,11-24 04:34:54.122  5762  5889 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 04:34:54.122  5762  5889 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 04:34:54.122  5762  5889 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 04:34:54.205  5762  5889 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40b6549
,11-24 04:34:54.206  5762  5889 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40b6549 
,11-24 04:34:54.224  5762  5882 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 04:34:54.225  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 04:34:54.225  5762  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 04:34:54.227  5762  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 04:34:54.230  5762  5882 D BluetoothAdapterProperties: Scan Mode:20
11-24 04:34:54.230  5762  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 04:34:54.231  5762  5882 D bt_hci  : do_postload posting postload work item
,11-24 04:34:54.232  5762  5886 I bt_hci  : event_postload
,11-24 04:34:54.232  5762  5886 I bt_vendor: sco_config_cb
11-24 04:34:54.232  5762  5886 I bt_hci  : sco_config_callback postload finished.
11-24 04:34:54.234  5762  5882 D bt_bte_conf: Device ID record 1 : primary
11-24 04:34:54.234  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:54.234  5762  5882 D bt_bte_conf:   vendorId            = 000f
,11-24 04:34:54.235  5762  5882 D bt_bte_conf:   vendorIdSource      = 0001
11-24 04:34:54.235  5762  5882 D bt_bte_conf:   product             = 1200
11-24 04:34:54.235  5762  5882 D bt_bte_conf:   version             = 1436
11-24 04:34:54.235  5762  5882 D bt_bte_conf:   clientExecutableURL = 
11-24 04:34:54.235  5762  5882 D bt_bte_conf:   serviceDescription  = 
11-24 04:34:54.235  5762  5882 D bt_bte_conf:   documentationURL    = 
11-24 04:34:54.235  5762  5882 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 04:34:54.236  5762  5879 D bt_stack_manager: event_start_up_stack finished
11-24 04:34:54.237  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 04:34:54.238  5762  5878 D BluetoothAdapterProperties: Setting state to 15
11-24 04:34:54.238  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 04:34:54.239  5762  5878 I BluetoothAdapterState: Entering BleOnState
11-24 04:34:54.241  5762  5886 I bt_vendor: low_power_mode_cb
,11-24 04:34:54.245  5762  5878 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 04:34:54.245  5762  5878 D BluetoothAdapterProperties: Setting state to 11
11-24 04:34:54.246  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 04:34:54.252  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:54.257  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:34:54.257  5762  5762 D HeadsetService: Received start request. Starting profile...
11-24 04:34:54.260  5762  5762 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 04:34:54.261  5762  5762 D HeadsetStateMachine: make
,11-24 04:34:54.273  5762  5762 D HeadsetStateMachine: max_hf_connections = 1
,11-24 04:34:54.273  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
11-24 04:34:54.274  5762  5762 I bt_bluedroid: get_profile_interface handsfree
11-24 04:34:54.274  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 04:34:54.275  5762  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 04:34:54.278  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:54.278  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 04:34:54.278  5762  5762 D A2dpService: Received start request. Starting profile...
11-24 04:34:54.279  5762  5762 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 04:34:54.279  5762  5762 I bt_bluedroid: get_profile_interface avrcp
,11-24 04:34:54.285  5762  5762 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 04:34:54.285  5762  5762 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 04:34:54.285  5762  5762 D A2dpStateMachine: make
,11-24 04:34:54.286  5762  5762 I bt_bluedroid: get_profile_interface a2dp
,11-24 04:34:54.288  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 04:34:54.288  5762  5897 D A2dpStateMachine: Enter Disconnected: -2
,11-24 04:34:54.289  5762  5762 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 04:34:54.290  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:54.294  5762  5762 D HidService: Received start request. Starting profile...
,11-24 04:34:54.294  5762  5762 I bt_bluedroid: get_profile_interface hidhost
11-24 04:34:54.294  5762  5882 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf409756d
11-24 04:34:54.294  5762  5762 D HidService: setHidService(): set to: null
11-24 04:34:54.294  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 04:34:54.295  5699  5699 D BluetoothInputDevice: Proxy object connected
11-24 04:34:54.295  5762  5762 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 04:34:54.295  5699  5699 D HidProfile: Bluetooth service connected
,11-24 04:34:54.296  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:54.296  5762  5762 D HealthService: Received start request. Starting profile...
,11-24 04:34:54.298  5762  5762 I bt_bluedroid: get_profile_interface health
11-24 04:34:54.298  5762  5762 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 04:34:54.299  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:54.301  5699  5699 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 04:34:54.301  5762  5762 D PanService: Received start request. Starting profile...
,11-24 04:34:54.301  5762  5762 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 04:34:54.301  5762  5762 I bt_bluedroid: get_profile_interface pan
11-24 04:34:54.301  5762  5882 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 04:34:54.302  5699  5699 D PanProfile: Bluetooth service connected
11-24 04:34:54.303  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:54.305  5762  5762 D BluetoothMapService: Received start request. Starting profile...
,11-24 04:34:54.305  5699  5699 D BluetoothMap: Proxy object connected
11-24 04:34:54.305  5762  5762 D BluetoothMapService: start()
11-24 04:34:54.305  5699  5699 D MapProfile: Bluetooth service connected
11-24 04:34:54.306  5699  5699 D BluetoothMap: getConnectedDevices()
11-24 04:34:54.306  5699  5699 D BluetoothMap: Bluetooth is Not enabled
11-24 04:34:54.307  5762  5762 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 04:34:54.308  5762  5762 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 04:34:54.308  5762  5762 D BluetoothMapAppObserver: createReceiver()
11-24 04:34:54.310  5762  5762 D BluetoothMapAppObserver: initObservers()
11-24 04:34:54.310  5762  5762 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 04:34:54.317  5762  5762 V SapService: SapBinder()
11-24 04:34:54.318  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:34:54.318  5762  5762 D SapService: Received start request. Starting profile...
11-24 04:34:54.318  5762  5762 V SapService: start()
,11-24 04:34:54.320  5762  5762 V BluetoothAdapterState: isTurningOff()=false
,11-24 04:34:54.320  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.320  5762  5895 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 04:34:54.320  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:54.320  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isTurningOff()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isTurningOff()=false
,11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isTurningOff()=false
11-24 04:34:54.321  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isTurningOff()=false
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isTurningOff()=false
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:54.322  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:54.323  5762  5762 V BluetoothAdapterState: isTurningOff()=false
11-24 04:34:54.323  5762  5762 V BluetoothAdapterState: isTurningOn()=true
11-24 04:34:54.323  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:54.324  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 04:34:54.324  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 04:34:54.324  5762  5878 D BluetoothAdapterProperties: ScanMode =  20
11-24 04:34:54.324  5762  5878 D BluetoothAdapterProperties: State =  11
11-24 04:34:54.324  5762  5878 D BluetoothAdapterProperties: Setting state to 12
11-24 04:34:54.324  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 04:34:54.325  3771  3798 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:34:54.325  5762  5882 D BluetoothAdapterProperties: Scan Mode:21
11-24 04:34:54.325   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:34:54.325  5762  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 04:34:54.326  3100  3123 D BluetoothMap: onBluetoothStateChange: up=true
11-24 04:34:54.326  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 04:34:54.327  5762  5878 I BluetoothAdapterState: Entering OnState
11-24 04:34:54.327  3100  3100 D BluetoothMap: Proxy object connected
11-24 04:34:54.327  3100  3100 D MapProfile: Bluetooth service connected
11-24 04:34:54.327  3100  3100 D BluetoothMap: getConnectedDevices()
11-24 04:34:54.328  3100  3967 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:54.329  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 04:34:54.330  3100  3962 D BluetoothPan: onBluetoothStateChange on: true
,11-24 04:34:54.330  3100  3100 D BluetoothInputDevice: Proxy object connected
11-24 04:34:54.330  3100  3100 D HidProfile: Bluetooth service connected
11-24 04:34:54.332   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:34:54.332  5699  5715 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 04:34:54.332  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 04:34:54.333  3100  3100 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 04:34:54.333  3100  3100 D PanProfile: Bluetooth service connected
,11-24 04:34:54.334  3100  3967 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 04:34:54.334  5762  5762 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 04:34:54.335  5762  5762 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 04:34:54.336   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 04:34:54.336  5762  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 04:34:54.337  5699  5712 D BluetoothMap: onBluetoothStateChange: up=true
11-24 04:34:54.337   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:34:54.337  3100  3113 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:34:54.338  3100  3123 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 04:34:54.338  5762  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 04:34:54.339  5762  5762 D ObexServerSockets: Succeed to create listening sockets 
,11-24 04:34:54.339  5762  5762 D ObexServerSockets0: startAccept()
11-24 04:34:54.339  5762  5762 D ObexServerSockets0: prepareForNewConnect()
11-24 04:34:54.339  5699  5715 D BluetoothPan: onBluetoothStateChange on: true
11-24 04:34:54.340  5699  5712 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 04:34:54.341   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 04:34:54.342  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 04:34:54.342  5762  5762 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 04:34:54.343  5762  5762 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 04:34:54.343  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:54.344   930   930 D BluetoothA2dp: Proxy object connected
11-24 04:34:54.344  3100  3100 D BluetoothA2dp: Proxy object connected
11-24 04:34:54.344  5762  5762 D BluetoothMapService: onReceive
11-24 04:34:54.344  5762  5762 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 04:34:54.344  5762  5762 D BluetoothMapService: STATE_ON
11-24 04:34:54.345  5699  5699 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 04:34:54.346  5762  5904 D ObexServerSockets0: Accepting socket connection...
11-24 04:34:54.346  5762  5905 D ObexServerSockets0: Accepting socket connection...
11-24 04:34:54.347  5762  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 04:34:54.348  5699  5699 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-24 04:34:54.348  5762  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 04:34:54.348  5762  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 04:34:54.355  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 04:34:54.359  5699  5699 D BluetoothA2dp: Proxy object connected
,11-24 04:34:54.363  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 04:34:54.365  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,11-24 04:34:54.369  5699  5699 D BluetoothPbap: Proxy object connected
,11-24 04:34:54.369  3100  3100 D BluetoothPbap: Proxy object connected
11-24 04:34:54.370  3100  3100 D PbapServerProfile: Bluetooth service connected
11-24 04:34:54.370  5762  5762 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 04:34:54.370  5762  5762 D ObexServerSockets0: prepareForNewConnect()
11-24 04:34:54.370  5699  5699 D PbapServerProfile: Bluetooth service connected
,11-24 04:34:54.378  5762  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 04:34:54.389  5762  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 04:34:54.392  5762  5914 I BtOppRfcommListener: Accept thread started.
,11-24 04:34:54.427   930   930 D BluetoothHeadset: Proxy object connected
,11-24 04:34:54.427   930   930 D BluetoothHeadset: Proxy object connected
11-24 04:34:54.427   930   930 D BluetoothHeadset: Proxy object connected
11-24 04:34:54.427  3771  3791 D BluetoothHeadset: Proxy object connected
,11-24 04:34:54.428  3100  3967 D BluetoothHeadset: Proxy object connected
11-24 04:34:54.428  3100  3100 D HeadsetProfile: Bluetooth service connected
,11-24 04:34:54.432   930   947 D BluetoothHeadset: Proxy object connected
,11-24 04:34:54.437   930   947 D BluetoothHeadset: Proxy object connected
,11-24 04:34:54.438  3100  3113 D BluetoothHeadset: Proxy object connected
11-24 04:34:54.438  3100  3100 D HeadsetProfile: Bluetooth service connected
,11-24 04:34:54.451  5699  5715 D BluetoothHeadset: Proxy object connected
,11-24 04:34:54.453  5699  5699 D HeadsetProfile: Bluetooth service connected
,11-24 04:34:55.149   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 04:34:55.149   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 04:34:56.162   930  2944 D ConnectivityService: handlePromptUnvalidated 101
,11-24 04:34:58.343  5762  5878 D BluetoothAdapterState: Current state: ON, message: 23
11-24 04:34:58.344  5762  5878 D BluetoothAdapterProperties: Setting state to 13
11-24 04:34:58.344  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 04:34:58.345  5762  5878 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 04:34:58.347  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
,11-24 04:34:58.352  5762  5762 D BluetoothMapService: onReceive
11-24 04:34:58.352  5762  5762 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 04:34:58.353  5762  5762 D BluetoothMapService: STATE_TURNING_OFF
11-24 04:34:58.354  5762  5762 D BluetoothMapService: MAP Service closeService in
11-24 04:34:58.355  5762  5762 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 04:34:58.355  5762  5762 D ObexServerSockets0: shutdown(block = true)
,11-24 04:34:58.357  5762  5904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-24 04:34:58.359  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:34:58.359  5639  5639 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 04:34:58.359  5762  5762 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 04:34:58.360  5762  5882 D BluetoothAdapterProperties: Scan Mode:20
11-24 04:34:58.361  5762  5762 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 04:34:58.361  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 04:34:58.361  5762  5905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 04:34:58.363  5762  5762 I BtOppRfcommListener: stopping Accept Thread
11-24 04:34:58.363  5762  5914 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 04:34:58.364  5762  5914 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 04:34:58.364  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 04:34:58.368  5639  5639 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 04:34:58.368  5639  5639 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 04:34:58.368  5762  5891 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 04:34:58.371  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:34:58.372  5762  5762 D HeadsetService: Received stop request...Stopping profile...
11-24 04:34:58.374   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:58.375   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:58.375   930   930 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:58.375  5699  5715 D BluetoothHeadset: Proxy object disconnected
11-24 04:34:58.375  3771  4017 D BluetoothHeadset: Proxy object disconnected
,11-24 04:34:58.376  3100  3123 D BluetoothHeadset: Proxy object disconnected
,11-24 04:34:58.380  5762  5762 D A2dpService: Received stop request...Stopping profile...
,11-24 04:34:58.381  5762  5897 D A2dpStateMachine: Exit Disconnected: -1
11-24 04:34:58.382  3100  3100 D HeadsetProfile: Bluetooth service disconnected
,11-24 04:34:58.382   930   930 D BluetoothA2dp: Proxy object disconnected
11-24 04:34:58.382  3100  3100 D BluetoothA2dp: Proxy object disconnected
11-24 04:34:58.383  5762  5762 D HidService: Received stop request...Stopping profile...
11-24 04:34:58.383  5762  5762 D HidService: Stopping Bluetooth HidService
11-24 04:34:58.384  3100  3100 D BluetoothInputDevice: Proxy object disconnected
11-24 04:34:58.384  3100  3100 D HidProfile: Bluetooth service disconnected
11-24 04:34:58.384  5762  5762 D HealthService: Received stop request...Stopping profile...
11-24 04:34:58.385  5762  5762 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:58.386  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:58.386  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.386  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:58.387  5762  5762 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 04:34:58.388  5762  5762 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 04:34:58.388  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:58.388  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:58.388  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:58.388  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 04:34:58.389  5762  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 04:34:58.390  5762  5762 D PanService: Received stop request...Stopping profile...
11-24 04:34:58.390  5699  5699 D DockEventReceiver: finishStartingService: stopping service
11-24 04:34:58.391  5699  5699 D HeadsetProfile: Bluetooth service disconnected
11-24 04:34:58.391  5762  5762 D BluetoothMapService: Received stop request...Stopping profile...
11-24 04:34:58.391  5762  5762 D BluetoothMapService: stop()
11-24 04:34:58.391  5699  5699 D BluetoothA2dp: Proxy object disconnected
11-24 04:34:58.392  5699  5699 D BluetoothInputDevice: Proxy object disconnected
11-24 04:34:58.392  5699  5699 D HidProfile: Bluetooth service disconnected
11-24 04:34:58.392  5762  5762 D BluetoothMapAppObserver: deinitObservers()
11-24 04:34:58.392  5762  5762 D BluetoothMapAppObserver: removeReceiver()
11-24 04:34:58.392  5699  5699 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 04:34:58.392  5699  5699 D PanProfile: Bluetooth service disconnected
11-24 04:34:58.394  3100  3100 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 04:34:58.394  3100  3100 D PanProfile: Bluetooth service disconnected
11-24 04:34:58.395  3100  3100 D BluetoothMap: Proxy object disconnected
11-24 04:34:58.395  3100  3100 D MapProfile: Bluetooth service disconnected
11-24 04:34:58.397  5699  5699 D BluetoothMap: Proxy object disconnected
11-24 04:34:58.397  5699  5699 D MapProfile: Bluetooth service disconnected
,11-24 04:34:58.399  5762  5762 D SapService: Received stop request...Stopping profile...
11-24 04:34:58.399  5762  5762 V SapService: stop()
,11-24 04:34:58.399  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 04:34:58.404  5762  5762 V BluetoothAdapterState: isTurningOff()=true
,11-24 04:34:58.405  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:58.405  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.405  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 04:34:58.406  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:58.406  5762  5762 V BluetoothAdapterState: isTurningOff()=true
,11-24 04:34:58.406  5762  5762 V BluetoothAdapterState: isTurningOn()=false
,11-24 04:34:58.406  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.406  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:58.406  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:58.406  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 04:34:58.406  5762  5762 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 04:34:58.406  5762  5762 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 04:34:58.406  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 04:34:58.406  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 04:34:58.406  5762  5762 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:58.406  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 04:34:58.406  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:58.407  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 04:34:58.406  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 04:34:58.407  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:58.407  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 04:34:58.407  5762  5762 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-24 04:34:58.407  5762  5882 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-24 04:34:58.407  5762  5762 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 04:34:58.408  5762  5762 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:58.408  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:58.408  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.408  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:58.408  5762  5762 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 04:34:58.408  5762  5762 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 04:34:58.409  5762  5762 D BluetoothMapService: MAP Service closeService in
11-24 04:34:58.409  5762  5762 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:58.409  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:58.409  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.409  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:58.409  5762  5762 D BluetoothMapService: cleanup()
11-24 04:34:58.409  5762  5762 D BluetoothMapService: MAP Service closeService in
11-24 04:34:58.411  3100  3100 D BluetoothPbap: Proxy object disconnected
11-24 04:34:58.411  3100  3100 D PbapServerProfile: Bluetooth service disconnected
11-24 04:34:58.411  5762  5762 V BluetoothAdapterState: isTurningOff()=true
11-24 04:34:58.411  5762  5762 V BluetoothAdapterState: isTurningOn()=false
,11-24 04:34:58.411  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.411  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:34:58.412  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 04:34:58.412  5762  5878 D BluetoothAdapterProperties: Setting state to 15
,11-24 04:34:58.412  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 04:34:58.412  5762  5878 I BluetoothAdapterState: Entering BleOnState
11-24 04:34:58.413  3771  3986 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:58.414   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:58.414  3100  3123 D BluetoothMap: onBluetoothStateChange: up=false
11-24 04:34:58.415  3100  3967 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 04:34:58.416  5699  5699 D BluetoothPbap: Proxy object disconnected
,11-24 04:34:58.416  5699  5699 D PbapServerProfile: Bluetooth service disconnected
11-24 04:34:58.417  3100  3962 D BluetoothPan: onBluetoothStateChange on: false
11-24 04:34:58.417   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:58.417  5699  5712 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 04:34:58.418  3100  3113 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 04:34:58.419   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 04:34:58.419  5699  5715 D BluetoothMap: onBluetoothStateChange: up=false
11-24 04:34:58.419   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:58.420  3100  3123 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 04:34:58.420  3100  3967 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 04:34:58.420  5699  5712 D BluetoothPan: onBluetoothStateChange on: false
11-24 04:34:58.421  5699  5715 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 04:34:58.422  5699  5712 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 04:34:58.423  5699  5715 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 04:34:58.424  5762  5878 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 04:34:58.424  5762  5878 D BluetoothAdapterProperties: Setting state to 16
11-24 04:34:58.424  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-24 04:34:58.424  5762  5878 D BluetoothAdapterProperties: onBleDisable
11-24 04:34:58.425  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
11-24 04:34:58.425  5762  5879 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-24 04:34:58.427  5762  5889 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-24 04:34:58.427  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 04:34:58.427  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 04:34:58.429  5762  5882 D BluetoothAdapterProperties: Scan Mode:20
11-24 04:34:58.430  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:58.431  5639  5639 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 04:34:58.432  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 04:34:58.434  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,11-24 04:34:58.644  5762  5882 I bt_hci  : shut_down
,11-24 04:34:58.650  5762  5886 D bt_hwcfg: hw_epilog_process
,11-24 04:34:58.651  5762  5886 I bt_vendor: low_power_mode_cb
,11-24 04:34:58.654  5762  5886 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 04:34:58.654  5762  5886 I bt_vendor: epilog_cb
11-24 04:34:58.654  5762  5886 I bt_hci  : epilog_finished_callback
,11-24 04:34:58.659  5762  5882 I bt_hci_h4: hal_close
,11-24 04:34:58.661  5762  5882 I bt_userial_vendor: device fd = 54 close
,11-24 04:34:58.778  5762  5879 D bt_stack_manager: event_shut_down_stack finished.
,11-24 04:34:58.779  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 04:34:58.783  5762  5878 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 04:34:58.783  5762  5762 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 04:34:58.785  5762  5762 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 04:34:58.785  5762  5762 D BtGatt.GattService: stop()
,11-24 04:34:58.785  5762  5762 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 04:34:58.789  5762  5762 V BluetoothAdapterState: isTurningOff()=false,
11-24 04:34:58.789  5762  5762 V BluetoothAdapterState: isTurningOn()=false
11-24 04:34:58.789  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:34:58.789  5762  5762 V BluetoothAdapterState: isBleTurningOff()=true
11-24 04:34:58.790  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 04:34:58.790  5762  5878 D BluetoothAdapterProperties: Setting state to 10
11-24 04:34:58.791  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 04:34:58.792  5762  5878 I BluetoothAdapterState: Entering OffState
11-24 04:34:58.793   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 04:34:58.808  5762  5762 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 04:34:58.808  5762  5762 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 04:34:58.808  5762  5762 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 04:34:58.812  5762  5879 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 04:34:58.820  5762  5762 I art     : System.exit called, status: 0
,11-24 04:34:58.820  5762  5762 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 04:34:58.860   930  3138 I ActivityManager: Process com.android.bluetooth (pid 5762) has died
,11-24 04:35:03.341  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:03.342  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 04:35:03.348  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:35:03.348  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20c8ec5 removed from the list
,11-24 04:35:03.348  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 04:35:03.350  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 04:35:03.351  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8eec528 added. We now have 4 listener(s)
11-24 04:35:03.351  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:03.352  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:35:03.353  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8eec528 removed from the list
11-24 04:35:03.353  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:03.354  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:03.355  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ac5241 added. We now have 4 listener(s)
11-24 04:35:03.355  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:35:05.150   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:06.152   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:07.153   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:08.155   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:08.366  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:35:08.402   930   947 I ActivityManager: Start proc 5922:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 04:35:08.498  5922  5922 D AdapterServiceConfig: Adding HeadsetService
,11-24 04:35:08.499  5922  5922 D AdapterServiceConfig: Adding A2dpService
11-24 04:35:08.499  5922  5922 D AdapterServiceConfig: Adding HidService
11-24 04:35:08.499  5922  5922 D AdapterServiceConfig: Adding HealthService
11-24 04:35:08.499  5922  5922 D AdapterServiceConfig: Adding PanService
11-24 04:35:08.499  5922  5922 D AdapterServiceConfig: Adding GattService
11-24 04:35:08.500  5922  5922 D AdapterServiceConfig: Adding BluetoothMapService
11-24 04:35:08.500  5922  5922 D AdapterServiceConfig: Adding SapService
,11-24 04:35:08.513   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4dd7e53:true
,11-24 04:35:08.514  5922  5922 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 04:35:08.517  5922  5922 I bt_bluedroid: init
,11-24 04:35:08.518  5922  5934 I BluetoothAdapterState: Entering OffState
,11-24 04:35:08.521  5922  5935 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 04:35:08.521  5922  5935 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 04:35:08.521  5922  5935 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 04:35:08.521  5922  5935 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 04:35:08.522  5922  5922 I bt_bluedroid: get_profile_interface socket
,11-24 04:35:08.524  5922  5938 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-24 04:35:08.524  5922  5922 I bt_bluedroid: get_profile_interface sdp
11-24 04:35:08.525  5922  5938 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 04:35:08.533  5922  5933 I bt_bluedroid: config_hci_snoop_log
,11-24 04:35:08.534   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 04:35:08.539  5922  5934 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 04:35:08.539  5922  5934 D BluetoothAdapterProperties: Setting state to 14
11-24 04:35:08.539  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 04:35:08.540  5922  5934 D BluetoothBondStateMachine: make
,11-24 04:35:08.542  5922  5939 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 04:35:08.546  5922  5934 I BluetoothAdapterState: Entering PendingCommandState
,11-24 04:35:08.547  5922  5922 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 04:35:08.550  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:08.550  5922  5922 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 04:35:08.551  5922  5922 D BtGatt.GattService: Received start request. Starting profile...
11-24 04:35:08.551  5922  5922 D BtGatt.GattService: start()
11-24 04:35:08.551  5922  5922 I bt_bluedroid: get_profile_interface gatt
11-24 04:35:08.552  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:08.552  5922  5922 D BtGatt.AdvertiseManager: advertise manager created
,11-24 04:35:08.558  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:08.558  5922  5922 V BluetoothAdapterState: isTurningOn()=false
11-24 04:35:08.558  5922  5922 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 04:35:08.558  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:35:08.558  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 04:35:08.560  5922  5934 I bt_bluedroid: bt_bluedroid
11-24 04:35:08.560  5922  5935 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 04:35:08.561  5922  5935 I bt_hci  : start_up
,11-24 04:35:08.566  5922  5935 I bt_vendor: alloc value 0xf41a5871
,11-24 04:35:08.566  5922  5935 I bt_vendor: init
11-24 04:35:08.566  5922  5935 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 04:35:08.566  5922  5935 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 04:35:08.677  5922  5935 D bt_hci  : start_up starting async portion
,11-24 04:35:08.677  5922  5942 I bt_hci  : event_finish_startup
11-24 04:35:08.678  5922  5942 I bt_hci_h4: hal_open
11-24 04:35:08.678  5922  5942 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 04:35:08.680  5922  5942 I bt_userial_vendor: device fd = 54 open
,11-24 04:35:08.675  5943  5943 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 04:35:08.697  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 04:35:08.701  5922  5942 D bt_hwcfg: Chipset BCM4358A3
,11-24 04:35:08.701  5922  5942 D bt_hwcfg: Target name = [BCM4358A3]
11-24 04:35:08.702  5922  5942 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 04:35:09.156   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:09.217  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 04:35:09.218  5922  5942 D bt_hwcfg: Settlement delay -- 100 ms
11-24 04:35:09.218  5922  5942 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 04:35:09.352  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 04:35:09.352  5922  5942 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-24 04:35:09.354  5922  5942 I bt_hwcfg: vendor lib fwcfg completed
,11-24 04:35:09.354  5922  5942 I bt_vendor: firmware callback
11-24 04:35:09.354  5922  5942 I bt_hci  : firmware_config_callback
,11-24 04:35:09.364  5922  5945 I bt_btu  : btu_task pending for preload complete event
,11-24 04:35:09.365  5922  5945 I bt_btu_task: Bluetooth chip preload is complete
11-24 04:35:09.365  5922  5945 I bt_btu  : btu_task received preload complete event
,11-24 04:35:09.373  5922  5945 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 04:35:09.373  5922  5945 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 04:35:09.373  5922  5945 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 04:35:09.373  5922  5945 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 04:35:09.373  5922  5945 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTM
,11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 04:35:09.374  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 04:35:09.475  5922  5945 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4123549
,11-24 04:35:09.475  5922  5945 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4123549 
,11-24 04:35:09.491  5922  5938 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 04:35:09.493  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 04:35:09.494  5922  5938 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 04:35:09.496  5922  5938 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 04:35:09.501  5922  5938 D BluetoothAdapterProperties: Scan Mode:20
,11-24 04:35:09.502  5922  5938 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 04:35:09.502  5922  5938 D bt_hci  : do_postload posting postload work item
11-24 04:35:09.502  5922  5942 I bt_hci  : event_postload
,11-24 04:35:09.502  5922  5942 I bt_vendor: sco_config_cb
11-24 04:35:09.502  5922  5942 I bt_hci  : sco_config_callback postload finished.
11-24 04:35:09.506  5922  5938 D bt_bte_conf: Device ID record 1 : primary
11-24 04:35:09.507  5922  5938 D bt_bte_conf:   vendorId            = 000f
,11-24 04:35:09.507  5922  5938 D bt_bte_conf:   vendorIdSource      = 0001
11-24 04:35:09.507  5922  5938 D bt_bte_conf:   product             = 1200
11-24 04:35:09.507  5922  5938 D bt_bte_conf:   version             = 1436
11-24 04:35:09.507  5922  5938 D bt_bte_conf:   clientExecutableURL = 
11-24 04:35:09.507  5922  5938 D bt_bte_conf:   serviceDescription  = 
11-24 04:35:09.507  5922  5938 D bt_bte_conf:   documentationURL    = 
11-24 04:35:09.507  5922  5938 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 04:35:09.508  5922  5935 D bt_stack_manager: event_start_up_stack finished
11-24 04:35:09.509  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 04:35:09.511  5922  5942 I bt_vendor: low_power_mode_cb
,11-24 04:35:09.510  5922  5934 D BluetoothAdapterProperties: Setting state to 15
11-24 04:35:09.511  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 04:35:09.514  5922  5934 I BluetoothAdapterState: Entering BleOnState
,11-24 04:35:09.518  5922  5934 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 04:35:09.518  5922  5934 D BluetoothAdapterProperties: Setting state to 11
11-24 04:35:09.518  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 04:35:09.523  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:35:09.524  5922  5922 D HeadsetService: Received start request. Starting profile...
,11-24 04:35:09.529  5922  5922 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 04:35:09.529  5922  5922 D HeadsetStateMachine: make
,11-24 04:35:09.539  5922  5934 I BluetoothAdapterState: Entering PendingCommandState
,11-24 04:35:09.541  5922  5922 D HeadsetStateMachine: max_hf_connections = 1
,11-24 04:35:09.541  5922  5922 I bt_bluedroid: get_profile_interface handsfree
11-24 04:35:09.541  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 04:35:09.542  5922  5938 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 04:35:09.544  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:35:09.545  5922  5922 D A2dpService: Received start request. Starting profile...
,11-24 04:35:09.546  5922  5922 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 04:35:09.546  5922  5922 I bt_bluedroid: get_profile_interface avrcp
,11-24 04:35:09.552  5922  5922 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 04:35:09.552  5922  5922 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 04:35:09.552  5922  5922 D A2dpStateMachine: make
11-24 04:35:09.553  5922  5922 I bt_bluedroid: get_profile_interface a2dp
11-24 04:35:09.555  5922  5952 D A2dpStateMachine: Enter Disconnected: -2
11-24 04:35:09.556  5922  5922 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 04:35:09.557  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 04:35:09.557  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:09.557  5922  5922 D HidService: Received start request. Starting profile...
11-24 04:35:09.558  5922  5922 I bt_bluedroid: get_profile_interface hidhost
11-24 04:35:09.558  5922  5922 D HidService: setHidService(): set to: null
11-24 04:35:09.558  5922  5938 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf410456d
11-24 04:35:09.558  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 04:35:09.558  5922  5922 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 04:35:09.559  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:09.559  5922  5922 D HealthService: Received start request. Starting profile...
,11-24 04:35:09.561  5922  5922 I bt_bluedroid: get_profile_interface health
,11-24 04:35:09.562  5922  5922 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 04:35:09.563  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:09.564  5922  5922 D PanService: Received start request. Starting profile...
11-24 04:35:09.564  5922  5922 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 04:35:09.564  5922  5922 I bt_bluedroid: get_profile_interface pan
11-24 04:35:09.564  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 04:35:09.565  5922  5938 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 04:35:09.566  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
,11-24 04:35:09.567  5922  5922 D BluetoothMapService: Received start request. Starting profile...
,11-24 04:35:09.567  5922  5922 D BluetoothMapService: start()
11-24 04:35:09.570  5922  5922 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 04:35:09.571  5922  5922 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 04:35:09.571  5922  5922 D BluetoothMapAppObserver: createReceiver()
11-24 04:35:09.572  5922  5922 D BluetoothMapAppObserver: initObservers()
11-24 04:35:09.572  5922  5922 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 04:35:09.580  5922  5922 V SapService: SapBinder()
,11-24 04:35:09.580  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:09.581  5922  5922 D SapService: Received start request. Starting profile...
11-24 04:35:09.581  5922  5922 V SapService: start()
,11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isTurningOn()=true
,11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.583  5922  5950 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isTurningOn()=true
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:35:09.583  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isTurningOn()=true
,11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isTurningOn()=true
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isTurningOn()=true
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.584  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 04:35:09.585  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.585  5922  5922 V BluetoothAdapterState: isTurningOn()=true
11-24 04:35:09.585  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.585  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 04:35:09.586  5922  5922 V BluetoothAdapterState: isTurningOff()=false
11-24 04:35:09.586  5922  5922 V BluetoothAdapterState: isTurningOn()=true
11-24 04:35:09.586  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
11-24 04:35:09.586  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 04:35:09.587  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 04:35:09.587  5922  5934 D BluetoothAdapterProperties: ScanMode =  20
11-24 04:35:09.587  5922  5934 D BluetoothAdapterProperties: State =  11
11-24 04:35:09.587  5922  5934 D BluetoothAdapterProperties: Setting state to 12
11-24 04:35:09.587  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 04:35:09.587  5922  5934 I BluetoothAdapterState: Entering OnState
11-24 04:35:09.588  3771  3798 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:35:09.588   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:35:09.588  3100  3962 D BluetoothMap: onBluetoothStateChange: up=true
11-24 04:35:09.589  5922  5938 D BluetoothAdapterProperties: Scan Mode:21
,11-24 04:35:09.589  5922  5938 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 04:35:09.591  3100  3123 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 04:35:09.592  3100  3100 D BluetoothMap: Proxy object connected
,11-24 04:35:09.592  3100  3100 D MapProfile: Bluetooth service connected
11-24 04:35:09.592  3100  3100 D BluetoothMap: getConnectedDevices()
11-24 04:35:09.593  3100  3962 D BluetoothPan: onBluetoothStateChange on: true
11-24 04:35:09.594  3100  3100 D BluetoothInputDevice: Proxy object connected
11-24 04:35:09.595  3100  3100 D HidProfile: Bluetooth service connected
11-24 04:35:09.595   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 04:35:09.596  5699  5715 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 04:35:09.596  3100  3100 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 04:35:09.596  3100  3100 D PanProfile: Bluetooth service connected
11-24 04:35:09.598  3100  3123 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 04:35:09.598  5922  5922 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 04:35:09.599  5922  5922 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 04:35:09.599   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 04:35:09.600  5922  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 04:35:09.600  5699  5712 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 04:35:09.601  5922  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 04:35:09.601   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:35:09.602  3100  3113 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:35:09.602  3100  3962 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 04:35:09.602  5922  5922 D ObexServerSockets: Succeed to create listening sockets 
11-24 04:35:09.602  5922  5922 D ObexServerSockets0: startAccept()
11-24 04:35:09.602  5922  5922 D ObexServerSockets0: prepareForNewConnect()
11-24 04:35:09.603  5699  5712 D BluetoothPan: onBluetoothStateChange on: true
11-24 04:35:09.604  5922  5922 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 04:35:09.604  5922  5922 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 04:35:09.605  5922  5958 D ObexServerSockets0: Accepting socket connection...
11-24 04:35:09.605  5922  5959 D ObexServerSockets0: Accepting socket connection...
11-24 04:35:09.606  5699  5712 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 04:35:09.606   930   930 D BluetoothA2dp: Proxy object connected
11-24 04:35:09.606  3100  3100 D BluetoothA2dp: Proxy object connected
11-24 04:35:09.606  5699  5712 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 04:35:09.608  5699  5715 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 04:35:09.611  5699  5699 D BluetoothMap: Proxy object connected
11-24 04:35:09.611  5699  5699 D MapProfile: Bluetooth service connected
11-24 04:35:09.611  5699  5699 D BluetoothMap: getConnectedDevices()
11-24 04:35:09.612  5922  5922 D BluetoothMapService: onReceive
11-24 04:35:09.612  5922  5922 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 04:35:09.612  5922  5922 D BluetoothMapService: STATE_ON
11-24 04:35:09.612   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 04:35:09.614  5699  5699 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 04:35:09.614  5699  5699 D PanProfile: Bluetooth service connected
11-24 04:35:09.614  5699  5699 D BluetoothA2dp: Proxy object connected
,11-24 04:35:09.615  5922  5962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 04:35:09.616  5699  5699 D BluetoothInputDevice: Proxy object connected
11-24 04:35:09.616  5699  5699 D HidProfile: Bluetooth service connected
11-24 04:35:09.616  5922  5962 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 04:35:09.617  5922  5962 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 04:35:09.621  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 04:35:09.628  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 04:35:09.629  5699  5699 D DockEventReceiver: finishStartingService: stopping service
11-24 04:35:09.636  3100  3100 D BluetoothPbap: Proxy object connected
,11-24 04:35:09.636  3100  3100 D PbapServerProfile: Bluetooth service connected
,11-24 04:35:09.636  5699  5699 D BluetoothPbap: Proxy object connected
11-24 04:35:09.636  5699  5699 D PbapServerProfile: Bluetooth service connected
,11-24 04:35:09.642  5922  5922 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 04:35:09.642  5922  5922 D ObexServerSockets0: prepareForNewConnect()
,11-24 04:35:09.647  5922  5966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 04:35:09.660  5922  5970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 04:35:09.661  5922  5970 I BtOppRfcommListener: Accept thread started.
,11-24 04:35:09.689   930   930 D BluetoothHeadset: Proxy object connected
,11-24 04:35:09.689   930   930 D BluetoothHeadset: Proxy object connected
11-24 04:35:09.689   930   930 D BluetoothHeadset: Proxy object connected
11-24 04:35:09.689  5699  5960 D BluetoothHeadset: Proxy object connected
,11-24 04:35:09.690  3771  3791 D BluetoothHeadset: Proxy object connected
,11-24 04:35:09.690  3100  3123 D BluetoothHeadset: Proxy object connected
11-24 04:35:09.691  3100  3100 D HeadsetProfile: Bluetooth service connected
11-24 04:35:09.693  5699  5699 D HeadsetProfile: Bluetooth service connected
,11-24 04:35:09.695   930   947 D BluetoothHeadset: Proxy object connected
,11-24 04:35:09.702   930   947 D BluetoothHeadset: Proxy object connected
,11-24 04:35:09.702  3100  3113 D BluetoothHeadset: Proxy object connected
11-24 04:35:09.702  3100  3100 D HeadsetProfile: Bluetooth service connected
,11-24 04:35:09.707  5699  5712 D BluetoothHeadset: Proxy object connected
,11-24 04:35:09.707  5699  5699 D HeadsetProfile: Bluetooth service connected
,11-24 04:35:10.157   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:35:13.382  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 04:35:13.387  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 04:35:13.388  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:13.389  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ac5241 removed from the list
11-24 04:35:13.389  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:13.391  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 04:35:13.391  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b503e6 added. We now have 4 listener(s)
,11-24 04:35:13.391  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:35:13.396   930   940 D WifiService: setWifiEnabled: false pid=5639, uid=10077
,11-24 04:35:13.397   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 04:35:15.158   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:16.159   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:17.160   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:18.161   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:18.408  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 04:35:18.409   930  3693 D WifiService: setWifiEnabled: true pid=5639, uid=10077
11-24 04:35:18.410   930  3693 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 04:35:18.416   508   922 D SoftapController: Softap fwReload - Ok
,11-24 04:35:18.422   508   922 D CommandListener: Setting iface cfg
,11-24 04:35:18.422   508   922 D CommandListener: Trying to bring down wlan0
11-24 04:35:18.424   508   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 04:35:18.429   930  2929 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 04:35:19.035   930  2929 D wifi    : set interface wlan0 flags (UP)
,11-24 04:35:19.036   930  2929 I WifiHAL : Initializing wifi
11-24 04:35:19.036   930  2929 I WifiHAL : Creating socket
,11-24 04:35:19.042   930  2929 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 04:35:19.042   930  2929 D wifi    : Did set static halHandle = 0x7f80b59b80
11-24 04:35:19.043   930  2929 D wifi    : halHandle = 0x7f80b59b80, mVM = 0x7f9d18d140, mCls = 0x201582
11-24 04:35:19.043   930  2929 D wifi    : array field set
11-24 04:35:19.043   930  2929 I WifiNative-HAL: interface[0] = wlan0
,11-24 04:35:19.046   930  5975 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547620232064
11-24 04:35:19.046   930  5975 D wifi    : waitForHalEvents called, vm = 0x7f9d18d140, obj = 0x201582, env = 0x7f925c8200
11-24 04:35:19.047   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 04:35:19.049   930  2929 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 04:35:19.051   930  2929 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-24 04:35:19.107  5976  5976 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 04:35:19.129  5976  5976 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 04:35:19.160  5976  5976 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-24 04:35:19.160  5976  5976 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 04:35:19.162   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:20.066   930  2929 D WifiConfigStore: Loading config and enabling all networks 
,11-24 04:35:20.097   930  2929 D WifiConfigStore: loaded 0 passpoint configs
,11-24 04:35:20.098   930  2929 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-24 04:35:20.099   930  2929 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 04:35:20.101   930  2929 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 04:35:20.104   930  2929 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 04:35:20.105   930  2929 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,11-24 04:35:20.105   930  2929 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,11-24 04:35:20.105   930  2929 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 04:35:20.112   930  2929 D WifiNative-HAL: Setting external_sim to 1
11-24 04:35:20.113  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 04:35:20.114   930  2929 D wifi    : setting dfs flag to true, 0x7f840b53e0
,11-24 04:35:20.115   930  2929 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 04:35:20.115   930  2929 D wifi    : setting scan oui 0x7f840b53e0
11-24 04:35:20.115   930  2929 D WifiHAL : Sending mac address OUI
,11-24 04:35:20.122   930  2929 E native  : do suspend false
,11-24 04:35:20.135   930  2929 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 04:35:20.136   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 04:35:20.137   930   930 D RttService: SCAN_AVAILABLE : 3
11-24 04:35:20.137   930  3048 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 04:35:20.139   508   922 D CommandListener: Setting iface cfg
,11-24 04:35:20.144   930  2927 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-24 04:35:20.144   930  2927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 04:35:20.159   930  2927 D WifiNative-HAL: p2pGetDeviceAddress
11-24 04:35:20.160   930  2927 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 04:35:20.162   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 04:35:20.167   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=245210 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=23 mControllerEnergyUsed=87 }
,11-24 04:35:23.213  5976  5976 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:35:23.225  5976  5976 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:35:23.259   930  2929 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 04:35:23.261   930  2929 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 04:35:23.261   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 04:35:23.276   930  2929 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 04:35:23.314   930  2929 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 04:35:23.316  5976  5976 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 04:35:23.425  5639  5687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 04:35:23.429  5639  5687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 04:35:23.430  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 04:35:23.430  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b503e6 removed from the list
,11-24 04:35:23.431  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:23.437  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 04:35:23.438  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-24 04:35:23.443  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3361c4b Bundle[{}]
,11-24 04:35:23.444  5639  5687 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 04:35:23.445  5639  5687 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 04:35:23.446  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 04:35:23.447  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-24 04:35:23.447  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 04:35:23.449  5639  5687 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-24 04:35:23.456  5639  5687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-24 04:35:23.457  5639  5687 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 04:35:23.457  5639  5687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-24 04:35:23.460  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.461  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@526ed27 added. We now have 3 listener(s)
,11-24 04:35:23.462  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 04:35:23.463  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.463  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.463  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.463  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff0bd4 added. We now have 4 listener(s)
11-24 04:35:23.463  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:35:23.464  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 04:35:23.466  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.466  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2ad17d added. We now have 4 listener(s)
,11-24 04:35:23.468  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.468  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.468  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.468  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.468  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd7872 added. We now have 5 listener(s)
11-24 04:35:23.468  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.468  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:35:23.468  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.468  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 04:35:23.468  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.469  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.469  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.469  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@526ed27 removed from the list
11-24 04:35:23.469  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.469  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff0bd4 removed from the list
11-24 04:35:23.469  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:23.469  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:35:23.469  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.471  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.471  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.471  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.471  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.471  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.471  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.471  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff0bd4 not in the list
11-24 04:35:23.471  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.471  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.473  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.473  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:35:23.473  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.473  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.473  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.473  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.473  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbd7872 removed from the list
11-24 04:35:23.473  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.473  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.473  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.473  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2ad17d removed from the list
11-24 04:35:23.474  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.474  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8b34c3 added. We now have 3 listener(s)
11-24 04:35:23.476  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.476  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.476  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.476  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.476  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b1140 added. We now have 4 listener(s)
11-24 04:35:23.476  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 04:35:23.478  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 04:35:23.482  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 04:35:23.482  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2180879 added. We now have 4 listener(s)
,11-24 04:35:23.485  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 04:35:23.485  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.485  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.485  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.485  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d66a9be added. We now have 5 listener(s)
11-24 04:35:23.486  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.486  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:23.486  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 04:35:23.486  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 04:35:23.486  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 04:35:23.486  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 04:35:23.488  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 04:35:23.491  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 04:35:23.492  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 04:35:23.492  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 04:35:23.495  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.496  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 04:35:23.496  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 04:35:23.496  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-24 04:35:23.496  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 04:35:23.501  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.501  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 04:35:23.501  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 04:35:23.501  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 04:35:23.501  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 04:35:23.501  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.502  5639  5687 D BluetoothAdapter: STATE_ON
,11-24 04:35:23.504  5922  5932 D BtGatt.GattService: registerClient() - UUID=e062e171-f655-4f97-b8df-da88312ed2c7
11-24 04:35:23.505  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=e062e171-f655-4f97-b8df-da88312ed2c7, clientIf=5
,11-24 04:35:23.506  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 04:35:23.507  5922  5933 D BtGatt.GattService: start scan with filters
11-24 04:35:23.511  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 04:35:23.511  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.512  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 04:35:23.512  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.512  5922  5941 D BtGatt.ScanManager: handling starting scan
11-24 04:35:23.512  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 04:35:23.512  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 04:35:23.512  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-24 04:35:23.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 04:35:23.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.513  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 04:35:23.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.513  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.513  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 04:35:23.513  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.514  5922  5941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7c1123c
11-24 04:35:23.515  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.516  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 04:35:23.516  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.516  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.516  5639  5687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 04:35:23.516  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.516  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.516  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 04:35:23.516  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 04:35:23.516  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.516  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.516  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 04:35:23.521  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.521  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.521  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.521  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:35:23.521  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.522  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 04:35:23.522  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.523  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 04:35:23.523  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.524  5639  5687 D BluetoothAdapter: STATE_ON
,11-24 04:35:23.524  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 04:35:23.524  5922  5933 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 04:35:23.524  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 04:35:23.525  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.526  5922  5961 D BtGatt.GattService: stopScan() - queue size =1
11-24 04:35:23.526  5922  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.527  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 04:35:23.527  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 04:35:23.528  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:35:23.528  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.529  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.529  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:35:23.529  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.529  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.530  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 04:35:23.530  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:35:23.530  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.530  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Disco,very mode: BLE, start discovery: false, start advertiser: false
11-24 04:35:23.530  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.530  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:35:23.530  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
11-24 04:35:23.530  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 04:35:23.530  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.530  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.532  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.532  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.532  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.533  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:35:23.533  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.533  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:35:23.533  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.533  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.533  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.533  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8b34c3 removed from the list
11-24 04:35:23.533  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.533  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b1140 removed from the list
11-24 04:35:23.533  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:23.533  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.533  5639  5687 D org.thalipr,oject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.535  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.535  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.535  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.535  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.535  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.535  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.535  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b1140 not in the list
11-24 04:35:23.535  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.535  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.537  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.537  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.537  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.537  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.537  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.537  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.537  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d66a9be removed from the list
11-24 04:35:23.537  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.537  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.537  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.537  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2180879 removed from the list
11-24 04:35:23.538  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.538  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95c793b added. We now have 3 listener(s)
11-24 04:35:23.539  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.539  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.539  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.539  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.539  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f1c858 added. We now have 4 listener(s)
11-24 04:35:23.540  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.540  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 04:35:23.541  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.541  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90d4db1 added. We now have 4 listener(s)
11-24 04:35:23.541  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 04:35:23.541  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.542  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.542  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.542  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.543  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.543  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3296 added. We now have 5 listener(s)
11-24 04:35:23.543  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.543  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:23.544  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:23.544  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 04:35:23.544  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 04:35:23.544  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:35:23.544  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 04:35:23.545  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 04:35:23.548  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 04:35:23.548  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 04:35:23.548  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 04:35:23.548  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 04:35:23.548  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.550  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:35:23.551  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.552  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 04:35:23.554  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 04:35:23.554  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 04:35:23.554  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 04:35:23.556  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:35:23.556  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.556  5922  5938 E BtGatt.ContextMap: Context not found for ID 5
11-24 04:35:23.558  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.558  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 04:35:23.558  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 04:35:23.559  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 04:35:23.559  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 04:35:23.559  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.560  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.562  5922  5957 D BtGatt.GattService: registerClient() - UUID=c69a52a5-efdf-4178-a7c7-817774360c54
11-24 04:35:23.562  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=c69a52a5-efdf-4178-a7c7-817774360c54, clientIf=5
11-24 04:35:23.563  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 04:35:23.563  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 04:35:23.563  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.563  5922  5933 D BtGatt.GattService: start scan with filters
11-24 04:35:23.563  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
11-24 04:35:23.568  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 04:35:23.568  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 04:35:23.568  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.568  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.568  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 04:35:23.568  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:35:23.568  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.568  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 04:35:23.568  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 04:35:23.568  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.568  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 04:35:23.568  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 04:35:23.569  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.569  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.569  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.569  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.570  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 04:35:23.570  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.574  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:35:23.574  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:35:23.575  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.575  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:35:23.575  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.575  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.575  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.575  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:23.575  5639  5687 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 04:35:23.575  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:35:23.575  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.575  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:35:23.575  5922  5941 D BtGatt.ScanManager: handling starting scan
11-24 04:35:23.575  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.575  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.575  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.576  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.576  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.576  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95c793b removed from the list
11-24 04:35:23.576  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.576  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f1c858 removed from the list
11-24 04:35:23.576  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:23.576  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.576  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.576  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.576  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.576  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 04:35:23.576  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.576  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.576  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.577  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.577  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.577  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.577  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.577  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.577  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.577  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.577  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.577  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.577  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:35:23.577  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f1c858 not in the list
11-24 04:35:23.577  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.578  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 04:35:23.578  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.579  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.579  5922  5932 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 04:35:23.580  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 04:35:23.580  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.581  5922  5933 D BtGatt.GattService: stopScan() - queue size =1
11-24 04:35:23.581  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 04:35:23.581  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.581  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 04:35:23.582  5922  5932 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.582  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 04:35:23.583  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 04:35:23.583  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:35:23.584  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.585  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.585  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:35:23.585  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.585  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.585  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.585  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.585  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.585  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c3296 removed from the list
11-24 04:35:23.585  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:35:23.585  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.585  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.585  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:35:23.585  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.585  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 04:35:23.585  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90d4db1 removed from the list
11-24 04:35:23.585  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.586  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 04:35:23.586  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 04:35:23.586  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.586  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.586  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.586  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.586  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:35:23.586  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92d4b3 added. We now have 3 listener(s)
11-24 04:35:23.586  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.586  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.586  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 04:35:23.586  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.586  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
11-24 04:35:23.586  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 04:35:23.587  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.587  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.587  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.587  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.587  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.587  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.587  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.587  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc54a70 added. We now have 4 listener(s)
11-24 04:35:23.588  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.588  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 04:35:23.590  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.590  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4f01e9 added. We now have 4 listener(s)
11-24 04:35:23.591  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.592  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.592  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.592  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.592  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6efe6e added. We now have 5 listener(s)
11-24 04:35:23.592  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.592  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:23.592  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 04:35:23.592  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 04:35:23.592  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 04:35:23.592  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 04:35:23.593  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 04:35:23.596  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 04:35:23.596  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.596  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 04:35:23.596  5639  5687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 04:35:23.597  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 04:35:23.601  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.601  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 04:35:23.601  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 04:35:23.601  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.602  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 04:35:23.602  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 04:35:23.602  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 04:35:23.603  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:35:23.606  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.606  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 04:35:23.606  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 04:35:23.606  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 04:35:23.606  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 04:35:23.606  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.607  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.608  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:35:23.608  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.608  5922  5938 E BtGatt.ContextMap: Context not found for ID 5
11-24 04:35:23.609  5922  5933 D BtGatt.GattService: registerClient() - UUID=54537d0e-3ee9-413f-b5c8-ecc67ff779b1
11-24 04:35:23.610  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=54537d0e-3ee9-413f-b5c8-ecc67ff779b1, clientIf=5
11-24 04:35:23.610  5639  5650 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 04:35:23.610  5922  5957 D BtGatt.GattService: start scan with filters
,11-24 04:35:23.612  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 04:35:23.612  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.612  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 04:35:23.612  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.612  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 04:35:23.613  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 04:35:23.613  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.613  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 04:35:23.613  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 04:35:23.613  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.613  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.613  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.613  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.613  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 04:35:23.614  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.615  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 04:35:23.615  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.615  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
11-24 04:35:23.615  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.615  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:35:23.616  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.616  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.616  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.618  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:35:23.618  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.618  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:35:23.618  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.618  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.618  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.618  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.618  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.618  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.618  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.618  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.618  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c92d4b3 removed from the list
11-24 04:35:23.618  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 04:35:23.618  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.619  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc54a70 removed from the list
11-24 04:35:23.619  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:23.619  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.619  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.619  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.619  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.619  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 04:35:23.619  5639  5687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 04:35:23.619  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 04:35:23.619  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.620  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.620  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.620  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.620  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc54a70 not in the list
11-24 04:35:23.620  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.620  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.621  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.621  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 04:35:23.621  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.621  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 04:35:23.621  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.621  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:35:23.622  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.622  5922  5957 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 04:35:23.622  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 04:35:23.622  5639  5687 D BluetoothAdapter: STATE_ON
11-24 04:35:23.623  5922  5932 D BtGatt.GattService: stopScan() - queue size =0
11-24 04:35:23.623  5922  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.624  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 04:35:23.624  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 04:35:23.625  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 04:35:23.625  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.626  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:35:23.626  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.626  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.626  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:35:23.626  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.626  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.626  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.627  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.627  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.627  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6efe6e removed from the list
11-24 04:35:23.627  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:35:23.627  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.627  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.627  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 04:35:23.628  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.628  5639  5639 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.628  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4f01e9 removed from the list
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.628  5639  5639 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 04:35:23.628  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.628  5639  5639 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.628  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eda272b added. We now have 3 listener(s)
11-24 04:35:23.628  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.630  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.630  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.630  5639  5639 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 04:35:23.630  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.630  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.630  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.630  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.630  5922  5941 D BtGatt.ScanManager: handling starting scan
11-24 04:35:23.630  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113f788 added. We now have 4 listener(s)
11-24 04:35:23.631  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.631  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 04:35:23.632  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 04:35:23.632  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61c0521 added. We now have 4 listener(s)
11-24 04:35:23.634  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 04:35:23.634  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 04:35:23.634  5639  5687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 04:35:23.634  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 04:35:23.634  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c046d46 added. We now have 5 listener(s)
11-24 04:35:23.635  5639  5687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 04:35:23.635  5639  5687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 04:35:23.635  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.635  5639  5687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 04:35:23.635  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.635  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.635  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.635  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eda272b removed from the list
11-24 04:35:23.635  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.636  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113f788 removed from the list
11-24 04:35:23.636  5639  5687 D io.jxcore.node.ConnectivityMonitor: stop
11-24 04:35:23.636  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.636  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.637  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.637  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 04:35:23.637  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.637  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.637  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.638  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.638  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 04:35:23.638  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.638  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.638  5639  5687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113f788 not in the list
11-24 04:35:23.638  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.638  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.639  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.639  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.640  5639  5687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-24 04:35:23.640  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 04:35:23.640  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 04:35:23.640  5639  5687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 04:35:23.640  5639  5687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c046d46 removed from the list
11-24 04:35:23.640  5639  5687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 04:35:23.640  5639  5687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 04:35:23.640  5639  5687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 04:35:23.640  5639  5687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61c0521 removed from the list
11-24 04:35:23.641  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 04:35:23.641  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 04:35:23.641  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 04:35:23.641  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:23.642  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 04:35:23.642  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:23.644  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 04:35:23.645  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.645  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
11-24 04:35:23.645  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 04:35:23.653  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 04:35:23.653  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:35:23.658  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 04:35:23.658  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.659  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:35:23.663  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:35:23.664  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.664  5922  5938 E BtGatt.ContextMap: Context not found for ID 5
11-24 04:35:23.669  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 04:35:23.669  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.670  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
11-24 04:35:23.676  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 04:35:23.676  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 04:35:23.676  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 04:35:23.681  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 04:35:23.681  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 04:35:23.759  5976  5976 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 04:35:23.786  5976  5976 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 04:35:23.786  5976  5976 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 04:35:23.794   930  2929 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 04:35:23.794   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 04:35:23.794   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 04:35:23.808   930  2929 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 04:35:23.818   508   922 D CommandListener: Setting iface cfg
,11-24 04:35:23.822   930  2929 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 04:35:23.827   930  5981 D DhcpClient: Receive thread started
,11-24 04:35:23.831   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 04:35:23.831   930  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 04:35:23.831   930  2944 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 04:35:23.918   930  2929 E native  : do suspend false
,11-24 04:35:23.934   930  5980 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 04:35:23.953   930  5981 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-24 04:35:23.954   930  5980 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-24 04:35:23.955   930  5980 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 04:35:23.967   930  5981 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 04:35:23.968   930  5980 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 04:35:23.970   508   922 D CommandListener: Setting iface cfg
,11-24 04:35:23.974   930  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 04:35:23.978   930  5980 D DhcpClient: Scheduling renewal in 86399s
,11-24 04:35:23.988   930  2929 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 04:35:23.989   930  2929 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 04:35:23.990   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 04:35:23.993   930  2944 D ConnectivityService: Adding iface wlan0 to network 102
,11-24 04:35:23.994   930  2929 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 04:35:24.031  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 04:35:24.034   930  2944 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 04:35:24.034   930  2944 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-24 04:35:24.036   930  2944 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 04:35:24.040   930  2944 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 04:35:24.042   930  2944 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-24 04:35:24.047   930  2944 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 04:35:24.052   930  2944 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 04:35:24.052   930  2944 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 04:35:24.052   930  2944 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 04:35:24.052   930  2944 D ConnectivityService:    accepting network in place of null
11-24 04:35:24.052   930  2929 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 04:35:24.052   930  2929 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 04:35:24.053   930  2944 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 04:35:24.066   930  5979 D NetlinkSocketObserver: NeighborEvent{elapsedMs=249108, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 04:35:24.074   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:35:24.086  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 04:35:24.095   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 04:35:24.098   930  2944 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 04:35:24.098  3734  3901 W QCNEJ   : |CORE| network available: 102
,11-24 04:35:24.098   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 04:35:24.099   930  2944 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-24 04:35:24.099  3734  3901 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 04:35:24.100   930   947 D Tethering: MasterInitialState.processMessage what=3
11-24 04:35:24.102  3734  3901 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 04:35:24.102  3734  3901 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 04:35:24.111  5047  5073 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 04:35:24.111  5047  5073 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 04:35:24.111  5047  5073 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 04:35:24.111  5047  5073 E SarControlService: no key has been found,reset the power
11-24 04:35:24.111  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 04:35:24.111  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 04:35:24.111  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 04:35:24.112  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 04:35:24.112  5074  5074 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 04:35:24.115  5047  5088 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 04:35:24.115  5047  5088 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 04:35:24.115  5047  5088 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 04:35:24.117  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 04:35:24.117  5074  5074 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 04:35:24.118  4932  4932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 04:35:24.121  3681  3681 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 04:35:24.124  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000f003000000000000ffffffff]
11-24 04:35:24.125  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 04:35:24.125  5074  5090 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 04:35:24.125  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:35:24.125  5047  5059 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 04:35:24.125  3681  3681 D SystemUpdateService: onCreate
11-24 04:35:24.128  5639  5639 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-24 04:35:24.130   930  5978 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 04:35:24.131  5074  5090 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c2f8d37 HexData = [00000000f103000000000000ffffffff]
11-24 04:35:24.131  5074  5090 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 04:35:24.131  5074  5090 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 04:35:24.131  3681  3681 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 04:35:24.133  5074  5074 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 04:35:24.133  5047  5058 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 04:35:24.144  3681  3681 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 04:35:24.151  3681  5415 I iu.UploadsManager: num queued entries: 0
11-24 04:35:24.152  3681  5415 I iu.UploadsManager: num updated entries: 0
11-24 04:35:24.152  3681  5415 I iu.SyncManager: NEXT; no task
,11-24 04:35:24.153  3681  5991 I SystemUpdateService: active receiver: enabled
,11-24 04:35:24.155  3681  3681 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 04:35:24.157  3681  3681 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 04:35:24.158  5776  5776 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 04:35:24.162  5776  5776 D SprintDMHelper: simOperator: 
,11-24 04:35:24.162  5776  5776 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 04:35:24.184   930  5978 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 09:35:24 GMT], X-Android-Received-Millis=[1479980124183], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479980124155]}
,11-24 04:35:24.184   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 04:35:24.184   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 04:35:24.184   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 04:35:24.185   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 04:35:24.194  3681  5991 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 04:35:24.204  3681  5991 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 04:35:24.204  3681  5991 I SystemUpdateService: now status is 0 (complete)
11-24 04:35:24.204  3681  5991 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 04:35:24.204  3681  5991 I SystemUpdateService: file has been verified
11-24 04:35:24.204  3681  5991 I SystemUpdateService: OTA package size = 21989297
,11-24 04:35:24.210  3681  5991 I SystemUpdateService: showing system update notification
,11-24 04:35:24.225  3681  3681 D SystemUpdateService: onDestroy
,11-24 04:35:24.287  5020  5996 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 04:35:25.775  5639  6003 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 04:35:25.775  5639  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:26.582  5639  6003 W !!      : call onHalfStreamCopied
,11-24 04:35:26.583  5639  6003 I testCopyDataAndClose: closing input stream
,11-24 04:35:26.852   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 04:35:27.357  5639  6003 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 04:35:30.163   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:31.121  5639  6004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:31.121  5639  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:31.165   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:32.058   930  2944 D ConnectivityService: handlePromptUnvalidated 102
,11-24 04:35:32.166   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:33.121  5639  5687 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 04:35:33.121  5639  5687 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:33.121  5639  5687 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 04:35:33.167   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:33.183  5639  6004 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 04:35:33.183  5639  6004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:33.183  5639  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-24 04:35:33.259  5639  6005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 04:35:33.259  5639  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:34.168   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 04:35:34.873  5639  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 04:35:35.160   930  2929 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-24 04:35:35.169   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 04:35:38.638  5639  6006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:38.638  5639  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 04:35:38.639  5639  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 04:35:38.640  5639  6006 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 04:35:38.640  5639  6006 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 04:35:38.640  5639  6006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:38.640  5639  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-24 04:35:38.642  5639  5687 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 04:35:38.645  5639  6007 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:38.645  5639  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 04:35:38.645  5639  6007 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 04:35:38.646  5639  6007 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:38.646  5639  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 04:35:38.646  5639  6007 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 04:35:38.646  5639  6007 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 04:35:38.646  5639  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 04:35:38.651  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 04:35:38.651  5639  5687 I jxcore-log: 
,11-24 04:35:38.652  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 04:35:38.652  5639  5687 I jxcore-log: 
11-24 04:35:38.652  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 04:35:38.652  5639  5687 I jxcore-log: 
11-24 04:35:38.652  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 04:35:38.652  5639  5687 I jxcore-log: 
11-24 04:35:38.653  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'Total duration:  90771'
11-24 04:35:38.653  5639  5687 I jxcore-log: 
,11-24 04:35:38.655  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 04:35:38.655  5639  5687 I jxcore-log: 
,11-24 04:35:38.658  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 04:35:38.658  5639  5687 I jxcore-log: 
11-24 04:35:38.659  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 04:35:38.659  5639  5687 I jxcore-log: 
11-24 04:35:38.659  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 04:35:38.659  5639  5687 I jxcore-log: 
11-24 04:35:38.659  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 04:35:38.659  5639  5687 I jxcore-log: 
11-24 04:35:38.660  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.660  5639  5687 I jxcore-log: 
11-24 04:35:38.660  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 04:35:38.660  5639  5687 I jxcore-log: 
11-24 04:35:38.660  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.660  5639  5687 I jxcore-log: 
11-24 04:35:38.660  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 04:35:38.660  5639  5687 I jxcore-log: 
11-24 04:35:38.661  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 04:35:38.661  5639  5687 I jxcore-log: 
11-24 04:35:38.661  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 04:35:38.661  5639  5687 I jxcore-log: 
11-24 04:35:38.661  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 04:35:38.661  5639  5687 I jxcore-log: 
11-24 04:35:38.661  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.661  5639  5687 I jxcore-log: 
11-24 04:35:38.662  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 04:35:38.662  5639  5687 I jxcore-log: 
11-24 04:35:38.662  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.662  5639  5687 I jxcore-log: 
11-24 04:35:38.662  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 04:35:38.662  5639  5687 I jxcore-log: 
11-24 04:35:38.662  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.662  5639  5687 I jxcore-log: 
,11-24 04:35:38.662  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 04:35:38.662  5639  5687 I jxcore-log: 
11-24 04:35:38.663  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 04:35:38.663  5639  5687 I jxcore-log: 
11-24 04:35:38.663  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 04:35:38.663  5639  5687 I jxcore-log: 
11-24 04:35:38.663  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 04:35:38.663  5639  5687 I jxcore-log: 
11-24 04:35:38.664  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 04:35:38.664  5639  5687 I jxcore-log: 
11-24 04:35:38.664  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 04:35:38.664  5639  5687 I jxcore-log: 
11-24 04:35:38.664  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 04:35:38.664  5639  5687 I jxcore-log: 
11-24 04:35:38.665  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 04:35:38.665  5639  5687 I jxcore-log: 
,11-24 04:35:38.666  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 04:35:38.666  5639  5687 I jxcore-log: 
11-24 04:35:38.666  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 04:35:38.666  5639  5687 I jxcore-log: 
11-24 04:35:38.667  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 04:35:38.667  5639  5687 I jxcore-log: 
,11-24 04:35:38.667  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 04:35:38.667  5639  5687 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 04:35:38.667  5639  5687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 04:35:38.667  5639  5687 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 04:35:38.667  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 04:35:38.667  5639  5687 I jxcore-log: 
11-24 04:35:38.668  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.668  5639  5687 I jxcore-log: 
11-24 04:35:38.668  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 04:35:38.668  5639  5687 I jxcore-log: 
11-24 04:35:38.668  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.668  5639  5687 I jxcore-log: 
11-24 04:35:38.668  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 04:35:38.668  5639  5687 I jxcore-log: 
,11-24 04:35:38.668  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 04:35:38.668  5639  5687 I jxcore-log: 
,11-24 04:35:38.671  5639  5639 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 04:35:38.672  5639  5639 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 04:35:38.674  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 04:35:38.674  5639  5687 I jxcore-log: 
11-24 04:35:38.674  5639  5687 I jxcore-log: 2016-11-24 09:35:38 - WARN testUtils: 'myNameCallback not set!'
11-24 04:35:38.674  5639  5687 I jxcore-log: 
,11-24 04:35:40.709  5639  5687 I jxcore-log: 2016-11-24 09:35:40 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 04:35:40.709  5639  5687 I jxcore-log: 
,11-24 04:35:40.711  5639  5687 I jxcore-log: 2016-11-24 09:35:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 04:35:40.711  5639  5687 I jxcore-log: 
,11-24 04:35:41.061  5639  5687 I jxcore-log: 2016-11-24 09:35:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 04:35:41.061  5639  5687 I jxcore-log: 
,11-24 04:35:41.071  5639  5687 I jxcore-log: 2016-11-24 09:35:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 04:35:41.071  5639  5687 I jxcore-log: 
,11-24 04:35:42.170  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 04:35:42.170  5639  5687 I jxcore-log: 
,11-24 04:35:42.363  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 04:35:42.363  5639  5687 I jxcore-log: 
,11-24 04:35:42.368  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 04:35:42.368  5639  5687 I jxcore-log: 
,11-24 04:35:42.373  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 04:35:42.373  5639  5687 I jxcore-log: 
,11-24 04:35:42.856  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 04:35:42.856  5639  5687 I jxcore-log: 
,11-24 04:35:42.901  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 04:35:42.901  5639  5687 I jxcore-log: 
,11-24 04:35:42.914  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 04:35:42.914  5639  5687 I jxcore-log: 
,11-24 04:35:42.918  5639  5687 I jxcore-log: 2016-11-24 09:35:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 04:35:42.918  5639  5687 I jxcore-log: 
,11-24 04:35:43.188  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 04:35:43.188  5639  5687 I jxcore-log: 
,11-24 04:35:43.315  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 04:35:43.315  5639  5687 I jxcore-log: 
,11-24 04:35:43.683  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 04:35:43.683  5639  5687 I jxcore-log: 
,11-24 04:35:43.692  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 04:35:43.692  5639  5687 I jxcore-log: 
,11-24 04:35:43.696  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 04:35:43.696  5639  5687 I jxcore-log: 
,11-24 04:35:43.701  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 04:35:43.701  5639  5687 I jxcore-log: 
,11-24 04:35:43.707  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 04:35:43.707  5639  5687 I jxcore-log: 
,11-24 04:35:43.737  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 04:35:43.737  5639  5687 I jxcore-log: 
,11-24 04:35:43.774  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 04:35:43.774  5639  5687 I jxcore-log: 
,11-24 04:35:43.782  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 04:35:43.782  5639  5687 I jxcore-log: 
,11-24 04:35:43.788  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 04:35:43.788  5639  5687 I jxcore-log: 
,11-24 04:35:43.804  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 04:35:43.804  5639  5687 I jxcore-log: 
,11-24 04:35:43.819  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 04:35:43.819  5639  5687 I jxcore-log: 
,11-24 04:35:43.825  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 04:35:43.825  5639  5687 I jxcore-log: 
,11-24 04:35:43.830  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 04:35:43.830  5639  5687 I jxcore-log: 
,11-24 04:35:43.843  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 04:35:43.843  5639  5687 I jxcore-log: 
,11-24 04:35:43.860  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 04:35:43.860  5639  5687 I jxcore-log: 
,11-24 04:35:43.875  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 04:35:43.875  5639  5687 I jxcore-log: 
,11-24 04:35:43.886  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 04:35:43.886  5639  5687 I jxcore-log: 
,11-24 04:35:43.898  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 04:35:43.898  5639  5687 I jxcore-log: 
,11-24 04:35:43.908  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 04:35:43.908  5639  5687 I jxcore-log: 
,11-24 04:35:43.921  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 04:35:43.921  5639  5687 I jxcore-log: 
,11-24 04:35:43.931  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 04:35:43.931  5639  5687 I jxcore-log: 
,11-24 04:35:43.938  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 04:35:43.938  5639  5687 I jxcore-log: 
,11-24 04:35:43.960  5639  5687 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 04:35:43.961  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 04:35:43.961  5639  5687 I jxcore-log: 
,11-24 04:35:43.994  5639  5687 I jxcore-log: 2016-11-24 09:35:43 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 04:35:43.994  5639  5687 I jxcore-log: 
,11-24 04:35:44.224  5639  5687 I jxcore-log: 2016-11-24 09:35:44 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 04:35:44.224  5639  5687 I jxcore-log: 
,11-24 04:35:47.905  5976  5976 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:35:50.170   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:51.171   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:52.173   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:53.174   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:54.175   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:35:55.176   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 04:36:04.037   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:36:15.177   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:36:16.179   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:36:17.180   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:36:18.181   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:36:19.182   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:36:20.183   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 04:36:27.777  5976  5976 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 04:36:44.043   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:36:45.183   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 04:36:45.184   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 04:37:00.185   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:01.186   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:02.188   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:03.189   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:04.044   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:37:04.190   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:05.191   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 04:37:10.192   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:11.194   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:12.195   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:13.197   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:14.198   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:15.199   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 04:37:21.829   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 04:37:24.853   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 04:37:25.200   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:26.202   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:27.203   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:28.205   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:29.206   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:30.207   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 04:37:44.047   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:37:45.208   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:46.210   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:47.211   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:48.212   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:49.214   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:37:50.214   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 04:38:04.050   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:38:10.215   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:38:11.217   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:38:12.218   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:38:13.220   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:38:14.221   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:38:15.222   546   546 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 04:38:24.050   930  2929 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 04:38:40.223   546   546 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 04:38:40.223   546   546 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 04:39:00.225   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:39:00.279  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 04:39:00.279  5639  5687 I jxcore-log: 
,11-24 04:39:00.577  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 04:39:00.577  5639  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 04:39:00.577  5639  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 04:39:00.577  5639  5687 I jxcore-log: emit@events.js:82:1
11-24 04:39:00.577  5639  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 04:39:00.577  5639  5687 I jxcore-log: emit@events.js:82:1''
11-24 04:39:00.577  5639  5687 I jxcore-log: 
,11-24 04:39:00.579  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedClient: 'test client failed'
11-24 04:39:00.579  5639  5687 I jxcore-log: 
,11-24 04:39:00.589  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 04:39:00.589  5639  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 04:39:00.589  5639  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 04:39:00.589  5639  5687 I jxcore-log: emit@events.js:82:1
11-24 04:39:00.589  5639  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 04:39:00.589  5639  5687 I jxcore-log: emit@events.js:82:1''
11-24 04:39:00.589  5639  5687 I jxcore-log: 
,11-24 04:39:00.591  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedClient: 'test client failed'
11-24 04:39:00.591  5639  5687 I jxcore-log: 
,11-24 04:39:00.596  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 04:39:00.596  5639  5687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 04:39:00.596  5639  5687 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 04:39:00.596  5639  5687 I jxcore-log: emit@events.js:82:1
11-24 04:39:00.596  5639  5687 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 04:39:00.596  5639  5687 I jxcore-log: emit@events.js:82:1''
11-24 04:39:00.596  5639  5687 I jxcore-log: 
11-24 04:39:00.597  5639  5687 I jxcore-log: 2016-11-24 09:39:00 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 04:39:00.597  5639  5687 I jxcore-log: 
,11-24 04:39:01.156  6017  6017 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 04:39:01.161  6017  6017 D AndroidRuntime: CheckJNI is OFF
,11-24 04:39:01.189  6017  6017 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 04:39:01.224  6017  6017 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 04:39:01.226   546   546 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 04:39:01.242  6017  6017 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 04:39:01.253   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 04:39:01.254   930   943 I ActivityManager: Killing 5639:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 04:39:01.355   930  4817 I WindowState: WIN DEATH: Window{f2e65ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-24 04:39:01.355   930   940 D GraphicsStats: Buffer count: 2
,11-24 04:39:01.355   930  2939 D WifiService: Client connection lost with reason: 4
,11-24 04:39:01.396   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-24 04:39:01.397   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-24 04:39:01.398   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-24 04:39:01.398   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-24 04:39:01.398   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.398   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.398   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 04:39:01.398   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 04:39:01.399   930   943 I ActivityManager:   Force finishing activity ActivityRecord{e6465bc u0 com.test.thalitest/.MainActivity t10}
11-24 04:39:01.400   930   954 I art     : Starting a blocking GC Explicit
,11-24 04:39:01.407   930   948 W WindowManager: Attempted to add application window with unknown token Token{326c945 ActivityRecord{e6465bc u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-24 04:39:01.408   930   948 W WindowManager: Token{326c945 ActivityRecord{e6465bc u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{326c945 ActivityRecord{e6465bc u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-24 04:39:01.408   930   948 W WindowManager: view not successfully added to wm, removing view
11-24 04:39:01.408   930  3397 W ActivityManager: Spurious death for ProcessRecord{c354a40 0:com.test.thalitest/u0a77}, curProc for 5639: null
11-24 04:39:01.408   930   948 W WindowManager: Exception when adding starting window
11-24 04:39:01.408   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{e6b1c3 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-24 04:39:01.408   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-24 04:39:01.408   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-24 04:39:01.408   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-24 04:39:01.408   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-24 04:39:01.408   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-24 04:39:01.408   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.408   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.408   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 04:39:01.408   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 04:39:01.495   930   954 I art     : Explicit concurrent mark sweep GC freed 104619(7MB) AllocSpace objects, 62(1880KB) LOS objects, 33% free, 29MB/43MB, paused 1.707ms total 95.561ms
,11-24 04:39:01.515   930   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
11-24 04:39:01.517  6017  6017 I art     : System.exit called, status: 0
11-24 04:39:01.517  6017  6017 I AndroidRuntime: VM exiting with result code 0.
,11-24 04:39:01.533   930   954 I ActivityManager: Start proc 6027:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-24 04:39:01.534   930   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 04:39:01.540   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-24 04:39:01.548  4039  4149 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-24 04:39:01.548  3643  3643 I Keyboard.Facilitator: resetDictionaries() : en_US
11-24 04:39:01.548  5922  5922 D BluetoothMapAppObserver: onReceive
11-24 04:39:01.548  5922  5922 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 04:39:01.553   930  2920 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 04:39:01.583  3643  6038 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 04:39:01.586  3380  6041 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 04:39:01.592  3771  3771 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 04:39:01.612  3643  6038 I Decoder : createOrResetDecoder
,11-24 04:39:01.611   710   710 W kworker/1:3: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 04:39:01.616  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-24 04:39:01.616  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 04:39:01.615   710   710 W kworker/1:3: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 04:39:01.624   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 04:39:01.630   930   942 E PackageManager: Failed to write settings, restoring backup
11-24 04:39:01.630   930   942 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
11-24 04:39:01.630   930   942 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-24 04:39:01.630   930   942 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-24 04:39:01.630   930   942 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
11-24 04:39:01.630   930   942 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
11-24 04:39:01.630   930   942 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
11-24 04:39:01.630   930   942 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
11-24 04:39:01.630   930   942 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:468)
11-24 04:39:01.630   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4644)
11-24 04:39:01.630   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-24 04:39:01.630   930   942 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-24 04:39:01.630   930   942 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.630   930   942 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.630   930   942 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 04:39:01.630   930   942 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
11-24 04:39:01.630   930   942 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
11-24 04:39:01.630   930   942 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
11-24 04:39:01.630   930   942 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-24 04:39:01.630   930   942 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-24 04:39:01.630   930   942 E PackageManager: 	... 12 more
,11-24 04:39:01.632  3681  6046 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-24 04:39:01.644  3681  6046 D AccountUtils: Clearing selected account for com.test.thalitest
,11-24 04:39:01.641   710   710 W kworker/1:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 04:39:01.654   930   941 I ActivityManager: Start proc 6047:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-24 04:39:01.655  3812  3953 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 04:39:01.655  3812  3953 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3812
11-24 04:39:01.655  3812  3953 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.655  3812  3953 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 04:39:01.657   930  3693 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 04:39:01.658   930  6057 E DropBoxManagerService: Can't write: system_app_crash
11-24 04:39:01.658   930  6057 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 04:39:01.658   930  6057 E DropBoxManagerService: 	... 5 more
,11-24 04:39:01.668  3812  3953 I Process : Sending signal. PID: 3812 SIG: 9
,11-24 04:39:01.692  3556  3556 I ConfigService: onCreate
,11-24 04:39:01.694  3556  6063 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	,at com.google.android.gms.config.j.run(SourceFile:152)
11-24 04:39:01.694  3556  6063 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-24 04:39:01.695  3556  6063 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-24 04:39:01.696  3556  6063 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-24 04:39:01.714  3681  6046 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-24 04:39:01.720  3643  6038 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 04:39:01.744  3681  6046 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.744  3681  6046 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.744  3681  6046 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.744  3681  6046 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 04:39:01.758  3681  6046 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-24 04:39:01.819   930   941 D GraphicsStats: Buffer count: 1
11-24 04:39:01.819   930  4817 I WindowState: WIN DEATH: Window{f016e95 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,11-24 04:39:01.823  3681  6068 I GMPM-SVC: App measurement is starting up
11-24 04:39:01.824   930  5816 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3812) has died
,11-24 04:39:01.825   930  5816 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
11-24 04:39:01.831  3681  6068 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-24 04:39:01.827   930  5816 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 04:39:01.832  3681  6068 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-24 04:39:01.853   930   943 I ActivityManager: Start proc 6070:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 04:39:01.899  6070  6070 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:39:01.899  6070  6070 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 04:39:01.900  6070  6070 D AndroidRuntime: Shutting down VM
,11-24 04:39:01.907  6070  6070 E AndroidRuntime: FATAL EXCEPTION: main
11-24 04:39:01.907  6070  6070 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6070
11-24 04:39:01.907  6070  6070 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 04:39:01.907  6070  6070 E AndroidRuntime: 	... 10 more
11-24 04:39:01.909   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 04:39:01.910  6070  6070 I Process : Sending signal. PID: 6070 SIG: 9
,11-24 04:39:01.925   930  5816 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6070) has died
,11-24 04:39:01.926   930  5816 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 04:39:01.940   930   943 I ActivityManager: Start proc 6085:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 04:39:01.994  6085  6085 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
,11-24 04:39:01.994  6085  6085 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 04:39:01.994  6085  6085 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 04:39:01.994  6085  6085 D AndroidRuntime: Shutting down VM

```
