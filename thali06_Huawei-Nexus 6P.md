#### Test 951040644e42f59_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-28 11:20:06.585   930  5253 D NetlinkSocketObserver: NeighborEvent{elapsedMs=161944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 11:20:07.048  5498  5498 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 11:20:07.055  5498  5498 D AndroidRuntime: CheckJNI is OFF
11-28 11:20:07.086  5498  5498 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-28 11:20:07.123  5498  5498 I Radio-JNI: register_android_hardware_Radio DONE
11-28 11:20:07.139  5498  5498 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-28 11:20:07.143   930   941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-28 11:20:07.196   930   941 I ActivityManager: Start proc 5507:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-28 11:20:07.214  5498  5498 D AndroidRuntime: Shutting down VM
,11-28 11:20:07.545   930  3025 I WindowManager: Screenshot max retries 4 of Token{b3602f3 ActivityRecord{916e162 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{6ff3aba u0 Starting com.test.thalitest} drawState=2
,11-28 11:20:07.628  5507  5507 I CordovaLog: Changing log level to DEBUG(3)
,11-28 11:20:07.629  5507  5507 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-28 11:20:07.629  5507  5507 D CordovaActivity: CordovaActivity.onCreate()
,11-28 11:20:07.635  5507  5507 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-28 11:20:07.669  5507  5507 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-28 11:20:07.735  5507  5507 I LibraryLoader: Time to load native libraries: 61 ms (timestamps 3033-3094)
11-28 11:20:07.735  5507  5507 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 11:20:07.768  5507  5507 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28e657e}
,11-28 11:20:07.768  5507  5507 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-28 11:20:07.768  5507  5507 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-28 11:20:07.774  5507  5507 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-28 11:20:07.776  5507  5507 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-28 11:20:07.838  5507  5507 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-28 11:20:07.852  5507  5507 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-28 11:20:07.852  5507  5507 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 11:20:07.852  5507  5507 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 11:20:07.852  5507  5507 I Adreno  : Build Date                       : 12/06/15
11-28 11:20:07.852  5507  5507 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 11:20:07.852  5507  5507 I Adreno  : Local Branch                     : mybranch17112971
11-28 11:20:07.852  5507  5507 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 11:20:07.852  5507  5507 I Adreno  : Remote Branch                    : NONE
11-28 11:20:07.852  5507  5507 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 11:20:07.905   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51e3f99:true
,11-28 11:20:07.927   407   407 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34064]" dev="sockfs" ino=34064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:07.927   407   407 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34064]" dev="sockfs" ino=34064 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:07.941  5507  5507 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-28 11:20:07.949  5507  5507 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-28 11:20:07.953  5507  5507 D PluginManager: init()
,11-28 11:20:07.956  5507  5507 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-28 11:20:07.969  5507  5507 D CordovaActivity: Started the activity.
,11-28 11:20:07.970  5507  5507 D CordovaActivity: Resumed the activity.
,11-28 11:20:07.970   407   407 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32950]" dev="sockfs" ino=32950 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:07.974  5507  5544 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-28 11:20:07.970   407   407 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32950]" dev="sockfs" ino=32950 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:07.974  3027  3027 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[15130]" dev="sockfs" ino=15130 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:07.974  3027  3027 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15130]" dev="sockfs" ino=15130 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:07.978  5507  5507 D CordovaActivity: Paused the activity.
,11-28 11:20:07.983  5507  5531 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-28 11:20:08.015  5507  5544 I OpenGLRenderer: Initialized EGL, version 1.4
,11-28 11:20:08.029  5507  5507 D CordovaActivity: Stopped the activity.
,11-28 11:20:08.084   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +538ms (total +909ms)
,11-28 11:20:08.098  5507  5507 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-28 11:20:08.105  5507  5507 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5507
,11-28 11:20:08.185  5507  5507 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-28 11:20:08.310  5507  5547 D jxcore_app_log: JniHelper::setJavaVM(0xf53bc000), pthread_self() = -563082960
,11-28 11:20:08.314  5507  5547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-28 11:20:08.314  5507  5547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-28 11:20:08.314  5507  5547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-28 11:20:08.314  5507  5547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-28 11:20:08.314  5507  5547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-28 11:20:08.314  5507  5547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5481297 added. We now have 1 listener(s)
,11-28 11:20:08.316  5507  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-28 11:20:08.316  5507  5547 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-28 11:20:08.317  5507  5547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 11:20:08.317  5507  5547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-28 11:20:08.319  5507  5547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@45b30a2 added. We now have 1 listener(s)
11-28 11:20:08.319  5507  5547 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 11:20:08.329   930  2870 D WifiService: New client listening to asynchronous messages
11-28 11:20:08.329  5507  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 11:20:08.329  5507  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-28 11:20:08.330  5507  5547 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-28 11:20:08.330  5507  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-28 11:20:08.330  5507  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-28 11:20:08.330  5507  5547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-28 11:20:08.330  5507  5547 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-28 11:20:08.331  5507  5547 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 11:20:08.341  5507  5507 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-28 11:20:08.468  5507  5507 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-28 11:20:08.468  5507  5507 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-28 11:20:08.569   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:08.657  5507  5516 I art     : Background sticky concurrent mark sweep GC freed 87838(8MB) AllocSpace objects, 16(1476KB) LOS objects, 20% free, 26MB/32MB, paused 1.707ms total 113.900ms
,11-28 11:20:08.777  5507  5553 W jxcore-log: Initializing JXcore engine
,11-28 11:20:08.778  5507  5553 W jxcore-log: JXcore engine is ready
,11-28 11:20:08.797  5553  5553 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11672 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-28 11:20:08.797  5553  5553 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[14413]" dev="sockfs" ino=14413 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-28 11:20:08.797  5553  5553 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-28 11:20:08.797  5553  5553 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34839]" dev="sockfs" ino=34839 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-28 11:20:08.810  5507  5553 W jxcore-log: Starting JXcore engine
,11-28 11:20:08.875  5507  5553 W jxcore-log: Platform android
11-28 11:20:08.875  5507  5553 W jxcore-log: 
,11-28 11:20:08.876  5507  5553 W jxcore-log: Process ARCH arm
11-28 11:20:08.876  5507  5553 W jxcore-log: 
,11-28 11:20:09.023  5507  5553 I jxcore-log: JXcore Cordova bridge is ready!
11-28 11:20:09.023  5507  5553 I jxcore-log: 
,11-28 11:20:09.023  5507  5553 W jxcore-log: JXcore engine is started
,11-28 11:20:09.028  5507  5547 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-28 11:20:09.031  5507  5507 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-28 11:20:09.031  5507  5507 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-28 11:20:09.570   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:10.571   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:11.572   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:12.573   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:13.573   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 11:20:18.677  5507  5553 I jxcore-log: 2016-11-28 16:20:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-28 11:20:18.677  5507  5553 I jxcore-log: 
,11-28 11:20:18.678  5507  5553 I jxcore-log: 2016-11-28 16:20:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-28 11:20:18.678  5507  5553 I jxcore-log: 
,11-28 11:20:18.684  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 11:20:18.684  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 11:20:18.685  5507  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 11:20:18.688  5507  5553 I jxcore-log: 2016-11-28 16:20:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-28 11:20:18.688  5507  5553 I jxcore-log: 
11-28 11:20:18.689  5507  5553 I jxcore-log: 2016-11-28 16:20:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-28 11:20:18.689  5507  5553 I jxcore-log: 
,11-28 11:20:18.937  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 11:20:18.937  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@934361c added. We now have 2 listener(s)
,11-28 11:20:18.938  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-28 11:20:18.938  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 11:20:18.938  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 11:20:18.938  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 11:20:18.938  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95fc225 added. We now have 2 listener(s)
11-28 11:20:18.938  5507  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 11:20:18.939  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 11:20:18.940  5507  5553 D ExecuteNativeTests: Running unit tests
11-28 11:20:18.941  5507  5553 D BluetoothAdapter: enable(): BT is already enabled..!
11-28 11:20:18.941   930  3025 D WifiService: setWifiEnabled: true pid=5507, uid=10077
11-28 11:20:18.941   930  3025 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 11:20:22.134   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 11:20:25.170   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 11:20:28.946  5507  5553 I com.test.thalitest.ThaliTestRunner: Running UT
,11-28 11:20:29.018  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 11:20:29.019  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@537256f added. We now have 3 listener(s)
11-28 11:20:29.019  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:29.020  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 11:20:29.020  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 11:20:29.020  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 11:20:29.020  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bcf27c added. We now have 3 listener(s)
11-28 11:20:29.020  5507  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 11:20:29.021  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 11:20:29.026  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-28 11:20:29.027  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 11:20:29.027  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:29.027  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 11:20:29.027  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:29.028  5507  5553 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-28 11:20:29.028  5507  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 11:20:29.028  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-28 11:20:29.028  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:29.028  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:29.029  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:29.029  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,11-28 11:20:29.030  5507  5553 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-28 11:20:29.032  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-28 11:20:29.033  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,11-28 11:20:29.034  5507  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 11:20:29.036  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:29.036  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 11:20:29.042  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 11:20:29.043  5507  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 11:20:29.043  5507  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 11:20:29.043  5507  5553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-28 11:20:29.043  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-28 11:20:29.044  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.044  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.044  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.044  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 11:20:29.044  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 11:20:29.044  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 11:20:29.044  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:29.044  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 11:20:29.045  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 11:20:29.045  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 11:20:29.045  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 11:20:29.045  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 11:20:29.045  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 11:20:29.045  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:29.045  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 11:20:29.046  5507  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 11:20:29.048  5507  5507 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 11:20:29.049  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 11:20:29.049  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 11:20:29.049  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 11:20:29.049  5507  5555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:29.052  5507  5507 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 11:20:29.052  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 11:20:29.052  5507  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 11:20:29.053  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.053  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 11:20:29.047  4340  4340 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32963]" dev="sockfs" ino=32963 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:29.047  4340  4340 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32963]" dev="sockfs" ino=32963 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:29.054  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 11:20:29.054  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 11:20:29.054  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-28 11:20:29.055  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.055  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.055  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 11:20:29.055  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 11:20:29.055  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-28 11:20:29.056  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-28 11:20:29.056  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:29.056  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:29.056  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.056  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 11:20:29.056  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:29.056  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.056  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.057  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.057  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:29.059  4173  4184 D BtGatt.GattService: registerClient() - UUID=07b425fa-adc1-4c37-ab9b-ca4ea21c7e57
11-28 11:20:29.060  4173  4192 D BtGatt.GattService: onClientRegistered() - UUID=07b425fa-adc1-4c37-ab9b-ca4ea21c7e57, clientIf=5
,11-28 11:20:29.061  5507  5517 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 11:20:29.064  4173  4196 D BtGatt.AdvertiseManager: message : 0
,11-28 11:20:29.067  4173  4196 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 11:20:29.081  4173  4192 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 11:20:29.089  4173  4192 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 11:20:29.090  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.090  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.090  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 11:20:29.090  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.090  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.090  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.091  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.091  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.091  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 11:20:29.091  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 11:20:29.091  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.092  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.092  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.092  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.092  5507  5553 I io.jxcore.node.ConnectionHelper: start: OK
11-28 11:20:29.092  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 11:20:29.093  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.093  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-28 11:20:29.093  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 11:20:29.094  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.094  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.094  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:29.094  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.094  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-28 11:20:29.095  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 11:20:29.095  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.095  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.095  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.095  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.095  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 11:20:29.098  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.098  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 11:20:29.099  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.099  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.099  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 11:20:29.331   930  5253 D NetlinkSocketObserver: NeighborEvent{elapsedMs=184690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-28 11:20:29.595  5507  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 11:20:29.596  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 11:20:29.597  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-28 11:20:29.598  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 11:20:29.599  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 11:20:29.599  5507  5553 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 11:20:29.599  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 11:20:29.599  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 11:20:29.599  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-28 11:20:29.599  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 11:20:29.599  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 11:20:29.600  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 11:20:29.600  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 11:20:29.600  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 11:20:29.600  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 11:20:29.600  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 11:20:29.600  5507  5555 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 11:20:29.601  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.601  5507  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 11:20:29.601  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 11:20:29.601  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 11:20:29.601  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 11:20:29.601  5507  5555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 11:20:29.602  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.602  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.602  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.602  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.604  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:29.604  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 11:20:29.605  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:29.605  5507  5553 D BluetoothLeScanner: could not find callback wrapper
11-28 11:20:29.605  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 11:20:29.606  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.606  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.606  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.606  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 11:20:29.606  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.607  4173  4196 D BtGatt.AdvertiseManager: message : 1
11-28 11:20:29.608  4173  4196 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 11:20:29.620  4173  4192 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 11:20:29.620  4173  4192 D BtGatt.GattService: Client app is not null!
11-28 11:20:29.621  4173  4340 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:29.622  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 11:20:29.623  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.623  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:29.623  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.623  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.623  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.623  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 11:20:29.624  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 11:20:29.624  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 11:20:29.624  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.626  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.626  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:29.626  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.626  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.627  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 11:20:29.627  5507  5507 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 11:20:29.628  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 11:20:29.628  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:29.628  5507  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 11:20:29.628  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:29.628  5507  5553 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 11:20:29.628  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 11:20:29.628  5507  5553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-28 11:20:29.628  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 11:20:29.628  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-28 11:20:29.629  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:29.629  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.629  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.629  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.629  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.629  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 11:20:29.629  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 11:20:29.629  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 11:20:29.629  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 11:20:29.629  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.629  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 11:20:29.629  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:29.629  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.630  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.630  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-28 11:20:29.630  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.630  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.633  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 11:20:29.634  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 11:20:29.634  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 11:20:29.634  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 11:20:29.634  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 11:20:29.635  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 11:20:29.635  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.635  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.635  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-28 11:20:29.635  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-28 11:20:29.635  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 11:20:29.635  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 11:20:29.637  5507  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 11:20:29.642  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 11:20:29.642  5507  5558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:29.642  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 11:20:29.642  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 11:20:29.640  4186  4186 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32449]" dev="sockfs" ino=32449 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:29.640  4186  4186 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32449]" dev="sockfs" ino=32449 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:29.646  5507  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 11:20:29.647  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.647  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 11:20:29.648  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 11:20:29.649  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 11:20:29.649  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-28 11:20:29.652  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.652  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.652  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 11:20:29.652  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 11:20:29.652  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:29.652  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-28 11:20:29.652  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:29.652  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:29.653  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.653  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 11:20:29.653  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:29.653  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.653  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.653  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.655  5507  5553 D BluetoothAdapter: STATE_ON
,11-28 11:20:29.659  4173  4328 D BtGatt.GattService: registerClient() - UUID=36569ddf-5a62-4597-a3ee-f0ef448f35a2
11-28 11:20:29.659  4173  4192 D BtGatt.GattService: onClientRegistered() - UUID=36569ddf-5a62-4597-a3ee-f0ef448f35a2, clientIf=5
,11-28 11:20:29.660  5507  5517 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 11:20:29.661  4173  4196 D BtGatt.AdvertiseManager: message : 0
,11-28 11:20:29.663  4173  4196 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 11:20:29.675  4173  4192 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 11:20:29.682  4173  4192 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 11:20:29.682  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.683  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 11:20:29.685  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 11:20:29.685  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.686  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:29.687  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.687  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:29.687  5507  5553 I io.jxcore.node.ConnectionHelper: start: OK
11-28 11:20:29.687  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:29.687  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.687  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:29.687  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.688  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 11:20:29.691  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.692  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 11:20:29.692  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.692  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:29.692  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 11:20:30.191  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-28 11:20:30.192  5507  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 11:20:30.192  5507  5553 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-28 11:20:30.192  5507  5553 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 11:20:30.192  5507  5553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-28 11:20:30.192  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-28 11:20:30.193  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.193  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.193  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 11:20:30.193  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 11:20:30.195  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.195  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-28 11:20:30.196  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.197  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.197  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.199  4173  4196 D BtGatt.AdvertiseManager: message : 1
11-28 11:20:30.201  4173  4196 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 11:20:30.214  4173  4192 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 11:20:30.214  4173  4192 D BtGatt.GattService: Client app is not null!
11-28 11:20:30.217  4173  4340 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:30.218  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-28 11:20:30.218  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.218  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:30.218  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.218  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.218  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.219  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 11:20:30.219  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.219  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.219  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.219  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 11:20:30.219  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,11-28 11:20:30.219  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:30.220  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
11-28 11:20:30.220  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:30.220  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:30.220  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.221  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 11:20:30.221  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:30.221  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.221  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.221  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.222  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:30.228  4173  4340 D BtGatt.GattService: registerClient() - UUID=87ea39cf-d5aa-4b99-b838-a62a96fa2ab6
11-28 11:20:30.228  4173  4192 D BtGatt.GattService: onClientRegistered() - UUID=87ea39cf-d5aa-4b99-b838-a62a96fa2ab6, clientIf=5
,11-28 11:20:30.229  5507  5518 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 11:20:30.232  4173  4196 D BtGatt.AdvertiseManager: message : 0
11-28 11:20:30.236  4173  4196 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 11:20:30.250  4173  4192 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 11:20:30.258  4173  4192 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 11:20:30.260  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.260  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.260  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-28 11:20:30.260  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.260  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.260  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.260  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.260  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.261  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.261  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-28 11:20:30.261  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.261  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 11:20:30.261  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 11:20:30.261  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 11:20:30.261  5507  5553 I io.jxcore.node.ConnectionHelper: start: OK
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.262  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 11:20:30.262  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.263  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.263  5507  5553 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 11:20:30.263  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-28 11:20:30.263  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 11:20:30.263  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 11:20:30.263  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 11:20:30.263  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 11:20:30.264  5507  5558 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 11:20:30.264  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 11:20:30.264  5507  5558 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 11:20:30.264  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 11:20:30.264  5507  5558 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 11:20:30.264  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 11:20:30.264  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.265  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.265  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.265  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.266  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:30.266  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 11:20:30.268  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:30.268  5507  5553 D BluetoothLeScanner: could not find callback wrapper
11-28 11:20:30.268  5507  5,553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 11:20:30.268  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.268  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.268  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.268  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 11:20:30.268  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.269  4173  4196 D BtGatt.AdvertiseManager: message : 1
11-28 11:20:30.270  4173  4196 D BtGatt.AdvertiseManager: stop advertise for client 5
11-28 11:20:30.278  4173  4192 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-28 11:20:30.278  4173  4192 D BtGatt.GattService: Client app is not null!
11-28 11:20:30.280  4173  4186 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:30.281  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 11:20:30.281  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.281  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:30.281  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.281  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.281  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.282  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 11:20:30.282  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 11:20:30.283  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 11:20:30.284  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.285  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.285  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:30.286  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.286  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.286  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 11:20:30.286  5507  5507 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 11:20:30.286  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 11:20:30.286  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 11:20:30.286  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:30.287  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:30.287  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:30.287  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.287  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 11:20:30.287  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 11:20:30.287  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.287  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.287  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.288  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:30.291  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.291  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.292  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-28 11:20:30.292  5507  5553 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-28 11:20:30.293  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.293  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.293  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.294  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-28 11:20:30.295  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 11:20:30.295  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-28 11:20:30.295  5507  5553 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-28 11:20:30.296  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-28 11:20:30.296  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-28 11:20:30.297  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-28 11:20:30.297  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 11:20:30.297  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:30.297  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:30.298  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:30.298  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:30.298  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 11:20:30.299  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-28 11:20:30.300  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 11:20:30.300  5507  5553 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 11:20:30.300  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 11:20:30.303  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 11:20:30.304  5507  5553 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 11:20:30.304  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 11:20:30.305  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 11:20:30.306  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 11:20:30.306  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 11:20:30.306  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 11:20:30.306  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 11:20:30.306  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-28 11:20:30.306  5507  5553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 11:20:30.306  5507  5553 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-28 11:20:30.307  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 11:20:30.307  5507  5553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 11:20:30.307  5507  5553 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-28 11:20:30.307  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 11:20:30.307  5507  5553 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 11:20:30.307  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-28 11:20:30.311  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-28 11:20:30.312  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-28 11:20:30.312  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-28 11:20:30.313  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-28 11:20:30.313  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-28 11:20:30.313  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-28 11:20:30.313  5507  5553 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 11:20:30.313  5507  5553 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,11-28 11:20:30.315  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-28 11:20:30.318  5507  5553 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-28 11:20:30.318  5507  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
11-28 11:20:30.318  5507  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-28 11:20:30.318  5507  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-28 11:20:30.318  5507  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-28 11:20:30.319  5507  5562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-28 11:20:30.319  5507  5562 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-28 11:20:30.319  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-28 11:20:30.319  5507  5562 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:30.319  5507  5553 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-28 11:20:30.320  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-28 11:20:30.320  5507  5553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-28 11:20:30.320  5507  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-28 11:20:30.320  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 11:20:30.320  5507  5553 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-28 11:20:30.320  5507  5553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 11:20:30.320  5507  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-28 11:20:30.320  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 11:20:30.317  4328  4328 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32456]" dev="sockfs" ino=32456 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:30.320  5507  5553 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-28 11:20:30.320  5507  5553 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 11:20:30.320  5507  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 11:20:30.321  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 11:20:30.321  5507  5553 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-28 11:20:30.321  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-28 11:20:30.321  5507  5553 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-28 11:20:30.321  5507  5553 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-28 11:20:30.322  5507  5553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-28 11:20:30.317  4328  4328 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32456]" dev="sockfs" ino=32456 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:30.322  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-28 11:20:30.322  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.322  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.322  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.322  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:30.322  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 11:20:30.322  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 11:20:30.322  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:30.323  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 11:20:30.324  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 11:20:30.324  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 11:20:30.324  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 11:20:30.324  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 11:20:30.324  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 11:20:30.324  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:30.324  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 11:20:30.324  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 11:20:30.327  5507  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 11:20:30.327  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 11:20:30.327  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 11:20:30.327  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 11:20:30.328  5507  5563 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:30.330  5507  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 11:20:30.327  4186  4186 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31246]" dev="sockfs" ino=31246 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:30.327  4186  4186 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31246]" dev="sockfs" ino=31246 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:30.331  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.331  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 11:20:30.332  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 11:20:30.332  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 11:20:30.332  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-28 11:20:30.334  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.334  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.334  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 11:20:30.335  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 11:20:30.335  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:30.335  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-28 11:20:30.335  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:30.335  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:30.335  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.335  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 11:20:30.335  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:30.335  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.335  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.335  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.336  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:30.338  4173  4340 D BtGatt.GattService: registerClient() - UUID=7baa2002-77a4-4b89-8f60-677cb21504e1
11-28 11:20:30.339  4173  4192 D BtGatt.GattService: onClientRegistered() - UUID=7baa2002-77a4-4b89-8f60-677cb21504e1, clientIf=5
11-28 11:20:30.339  5507  5518 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-28 11:20:30.340  4173  4196 D BtGatt.AdvertiseManager: message : 0
11-28 11:20:30.342  4173  4196 D BtGatt.AdvertiseManager: starting multi advertising
11-28 11:20:30.351  4173  4192 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 11:20:30.356  4173  4192 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 11:20:30.357  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.357  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.357  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-28 11:20:30.358  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.358  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.358  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.358  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.358  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.358  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 11:20:30.359  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-28 11:20:30.359  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.361  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.362  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.362  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.362  5507  5553 I io.jxcore.node.ConnectionHelper: start: OK
11-28 11:20:30.362  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:30.362  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.362  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:30.362  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.363  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 11:20:30.365  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.366  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 11:20:30.366  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.366  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.366  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 11:20:30.864  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 11:20:30.864  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 11:20:30.864  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 11:20:30.864  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 11:20:30.865  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 11:20:30.865  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 11:20:30.865  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-28 11:20:30.865  5507  5563 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 11:20:30.865  5507  5563 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 11:20:30.865  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 11:20:30.866  5507  5563 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 11:20:30.866  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-28 11:20:30.866  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 11:20:30.866  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 11:20:30.867  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 11:20:30.867  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 11:20:30.869  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@537256f removed from the list
11-28 11:20:30.869  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 11:20:30.870  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 11:20:30.870  5507  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
11-28 11:20:30.870  5507  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-28 11:20:30.871  5507  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
,11-28 11:20:30.871  5507  5564 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
11-28 11:20:30.871  4173  4326 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-28 11:20:30.871  5507  5562 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-28 11:20:30.871  5507  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
,11-28 11:20:30.871  5507  5562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
11-28 11:20:30.873  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 11:20:30.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 11:20:30.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.875  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.877  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:30.877  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 11:20:30.879  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:30.879  5507  5553 D BluetoothLeScanner: could not find callback wrapper
,11-28 11:20:30.879  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 11:20:30.879  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.880  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.881  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.881  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 11:20:30.881  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.882  4173  4196 D BtGatt.AdvertiseManager: message : 1
11-28 11:20:30.883  4173  4196 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 11:20:30.893  4173  4192 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 11:20:30.893  4173  4192 D BtGatt.GattService: Client app is not null!
11-28 11:20:30.894  4173  4186 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:30.895  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 11:20:30.896  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.896  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:30.896  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:30.897  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.897  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.897  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 11:20:30.897  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 11:20:30.898  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 11:20:30.898  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.901  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.901  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:30.901  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.902  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:30.902  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bcf27c removed from the list
11-28 11:20:30.902  5507  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-28 11:20:30.902  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:30.902  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 11:20:30.902  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:30.903  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:30.903  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.903  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 11:20:30.903  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 11:20:30.904  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.904  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.904  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.904  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:30.905  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.905  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.907  5507  5507 D org.thaliproject.p2p.btconnectorlib.Discovery,Manager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.907  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:30.907  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 11:20:31.406  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 11:20:33.574   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:34.575   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:35.450  4173  4323 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-28 11:20:35.451  4173  4323 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-28 11:20:35.576   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:20:35.907  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
11-28 11:20:35.909  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-28 11:20:35.910  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:35.910  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 11:20:35.917  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 11:20:35.918  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 11:20:35.918  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 11:20:35.918  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 11:20:35.919  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-28 11:20:35.919  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 11:20:35.919  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 11:20:35.919  5507  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 11:20:35.920  5507  5565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:35.921  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-28 11:20:35.923  5507  5553 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-28 11:20:35.923  5507  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 11:20:35.924  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 11:20:35.924  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:35.924  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 11:20:35.920  4328  4328 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:35.920  4328  4328 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:35.926  5507  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-28 11:20:35.927  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-28 11:20:35.932  5507  5553 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
11-28 11:20:35.933  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 11:20:35.933  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 11:20:35.933  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 11:20:35.933  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 11:20:35.933  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 11:20:35.933  5507  5565 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 11:20:35.933  5507  5565 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 11:20:35.934  5507  5565 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 11:20:35.934  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 11:20:35.934  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 11:20:35.934  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 11:20:35.935  5507  5553 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@537256f not in the list
11-28 11:20:35.935  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 11:20:35.935  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 11:20:35.935  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 11:20:35.935  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 11:20:35.935  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:35.935  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-28 11:20:35.935  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 11:20:35.935  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:35.939  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:35.940  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:35.940  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:35.940  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:35.940  5507  5553 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bcf27c not in the list
11-28 11:20:35.940  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:35.940  5507  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-28 11:20:35.940  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:35.940  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:35.942  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-28 11:20:35.942  5507  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-28 11:20:35.942  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-28 11:20:35.942  5507  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-28 11:20:35.943  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 11:20:35.943  5507  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-28 11:20:35.943  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 11:20:35.944  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-28 11:20:35.944  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-28 11:20:35.945  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-28 11:20:35.946  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 11:20:35.946  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-28 11:20:35.946  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-28 11:20:35.946  5507  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-28 11:20:35.946  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 11:20:35.946  5507  5553 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-28 11:20:35.947  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 11:20:35.947  5507  5553 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-28 11:20:35.947  5507  5553 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-28 11:20:35.947  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-28 11:20:35.948  5507  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-28 11:20:35.948  5507  5553 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-28 11:20:35.949  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-28 11:20:35.949  5507  5553 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-28 11:20:35.949  5507  5553 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-28 11:20:35.949  5507  5553 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-28 11:20:35.949  5507  5553 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-28 11:20:35.950  5507  5553 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-28 11:20:35.951  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 11:20:35.951  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a170a added. We now have 3 listener(s)
11-28 11:20:35.952  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:35.952  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 11:20:35.952  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 11:20:35.952  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 11:20:35.953  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30d0b7b added. We now have 3 listener(s)
11-28 11:20:35.953  5507  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 11:20:35.954  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 11:20:35.957  5507  5553 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 11:20:35.957   930  3027 D WifiService: setWifiEnabled: true pid=5507, uid=10077
11-28 11:20:35.957   930  3027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 11:20:35.959  5507  5553 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-28 11:20:35.961  5507  5553 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-28 11:20:35.962  5507  5553 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-28 11:20:35.963  5507  5553 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-28 11:20:35.968  4173  4188 D BluetoothAdapterState: Current state: ON, message: 23
11-28 11:20:35.968  4173  4188 D BluetoothAdapterProperties: Setting state to 13
11-28 11:20:35.968  4173  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 11:20:35.968  5507  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 11:20:35.969  4173  4188 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 11:20:35.969  4173  4188 I BluetoothAdapterState: Entering PendingCommandState
11-28 11:20:35.970  5507  5553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 11:20:35.970  5507  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 11:20:35.970  4173  4173 D BluetoothMapService: onReceive
11-28 11:20:35.970  4173  4173 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-28 11:20:35.970  4173  4173 D BluetoothMapService: STATE_TURNING_OFF
,11-28 11:20:35.973  4173  4173 D BluetoothMapService: MAP Service closeService in
,11-28 11:20:35.973  4173  4173 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 11:20:35.973  4173  4173 D ObexServerSockets0: shutdown(block = true)
11-28 11:20:35.974  4173  4343 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-28 11:20:35.974  4173  4173 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 11:20:35.974  4173  4173 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 11:20:35.974  4173  4326 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 11:20:35.974  4173  4344 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-28 11:20:35.977  4173  4173 I BtOppRfcommListener: stopping Accept Thread
,11-28 11:20:35.977  4173  5199 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 11:20:35.977  4173  5199 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-28 11:20:35.986   930   943 I ActivityManager: Start proc 5568:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-28 11:20:35.986  4173  4192 D BluetoothAdapterProperties: Scan Mode:20
,11-28 11:20:35.988  4173  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-28 11:20:35.991  4173  4173 D HeadsetService: Received stop request...Stopping profile...
,11-28 11:20:35.993   930   930 D BluetoothHeadset: Proxy object disconnected
,11-28 11:20:35.993   930   930 D BluetoothHeadset: Proxy object disconnected
,11-28 11:20:35.994  3030  3041 D BluetoothHeadset: Proxy object disconnected
,11-28 11:20:35.994   930   930 D BluetoothHeadset: Proxy object disconnected
11-28 11:20:35.994  3030  3030 D HeadsetProfile: Bluetooth service disconnected
11-28 11:20:35.994  4173  4173 D A2dpService: Received stop request...Stopping profile...
11-28 11:20:35.994  3659  4033 D BluetoothHeadset: Proxy object disconnected
,11-28 11:20:35.995  4173  4332 D A2dpStateMachine: Exit Disconnected: -1
11-28 11:20:35.996   930   930 D BluetoothA2dp: Proxy object disconnected
11-28 11:20:35.997  3030  3030 D BluetoothA2dp: Proxy object disconnected
,11-28 11:20:35.997  4173  4173 D HidService: Received stop request...Stopping profile...
11-28 11:20:35.997  4173  4173 D HidService: Stopping Bluetooth HidService
11-28 11:20:35.998  4173  4173 V BluetoothAdapterState: isTurningOff()=true
11-28 11:20:35.998  3030  3030 D BluetoothInputDevice: Proxy object disconnected
11-28 11:20:35.998  4173  4173 V BluetoothAdapterState: isTurningOn()=false
,11-28 11:20:35.998  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:35.998  3030  3030 D HidProfile: Bluetooth service disconnected
11-28 11:20:35.998  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:35.999  4173  4173 D HealthService: Received stop request...Stopping profile...
,11-28 11:20:36.004  4173  4173 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-28 11:20:36.004  4173  4173 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 11:20:36.004  4173  4323 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 11:20:36.004  4173  4323 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 11:20:36.004  4173  4323 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 11:20:36.004  4173  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 11:20:36.004  4173  4192 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-28 11:20:36.004  4173  4173 D PanService: Received stop request...Stopping profile...
,11-28 11:20:36.005  3030  3030 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 11:20:36.005  3030  3030 D PanProfile: Bluetooth service disconnected
11-28 11:20:36.005  4173  4173 V BluetoothAdapterState: isTurningOff()=true
11-28 11:20:36.006  4173  4173 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.006  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:36.006  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.006  4173  4173 D BluetoothMapService: Received stop request...Stopping profile...
,11-28 11:20:36.006  4173  4173 D BluetoothMapService: stop()
11-28 11:20:36.007  4173  4173 D BluetoothMapAppObserver: deinitObservers()
11-28 11:20:36.007  4173  4173 D BluetoothMapAppObserver: removeReceiver()
,11-28 11:20:36.008  3030  3030 D BluetoothMap: Proxy object disconnected
11-28 11:20:36.008  3030  3030 D MapProfile: Bluetooth service disconnected
,11-28 11:20:36.009  4173  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 11:20:36.009  4173  4323 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 11:20:36.009  4173  4173 V BluetoothAdapterState: isTurningOff()=true
,11-28 11:20:36.009  4173  4173 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.010  4173  4323 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 11:20:36.010  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:36.010  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.010  4173  4323 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 11:20:36.010  4173  4323 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 11:20:36.010  4173  4323 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 11:20:36.010  4173  4323 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-28 11:20:36.010  4173  4173 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-28 11:20:36.010  4173  4173 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 11:20:36.010  4173  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 11:20:36.010  4173  4173 V BluetoothAdapterState: isTurningOff()=true
11-28 11:20:36.011  4173  4173 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.011  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:36.011  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.011  4173  4173 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 11:20:36.011  4173  4192 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-28 11:20:36.014  4173  4173 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-28 11:20:36.018  4173  4173 D SapService: Received stop request...Stopping profile...
11-28 11:20:36.018  4173  4173 V SapService: stop()
11-28 11:20:36.019  4173  4173 V BluetoothAdapterState: isTurningOff()=true
11-28 11:20:36.019  4173  4173 V BluetoothAdapterState: isTurningOn()=false
,11-28 11:20:36.019  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 11:20:36.019  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.019  4173  4173 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 11:20:36.019  4173  4173 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 11:20:36.021  4173  4173 D BluetoothMapService: MAP Service closeService in
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isTurningOff()=true
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
,11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.021  4173  4173 D BluetoothMapService: cleanup()
11-28 11:20:36.021  4173  4173 D BluetoothMapService: MAP Service closeService in
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isTurningOff()=true
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:36.021  4173  4173 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.022  4173  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 11:20:36.022  4173  4188 D BluetoothAdapterProperties: Setting state to 15
11-28 11:20:36.022  4173  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-28 11:20:36.022  4173  4188 I BluetoothAdapterState: Entering BleOnState
11-28 11:20:36.022   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 11:20:36.023  3030  3046 D BluetoothMap: onBluetoothStateChange: up=false
11-28 11:20:36.023  3030  3863 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-28 11:20:36.024  3030  3041 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 11:20:36.025   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 11:20:36.025  3030  3046 D BluetoothPan: onBluetoothStateChange on: false
11-28 11:20:36.026   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 11:20:36.026  3030  3863 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 11:20:36.027  3030  3041 D BluetoothPbap: onBluetoothStateChange: up=false
,11-28 11:20:36.028  3659  3681 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 11:20:36.028   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-28 11:20:36.031  4173  4188 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-28 11:20:36.031  4173  4188 D BluetoothAdapterProperties: Setting state to 16
11-28 11:20:36.031  4173  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 11:20:36.032  4173  4188 D BluetoothAdapterProperties: onBleDisable
11-28 11:20:36.032  4173  4188 I BluetoothAdapterState: Entering PendingCommandState
11-28 11:20:36.032  4173  4189 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 11:20:36.033  4173  4323 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-28 11:20:36.034  4173  4323 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 11:20:36.034  4173  4192 D BluetoothAdapterProperties: Scan Mode:20
,11-28 11:20:36.047  5568  5568 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-28 11:20:36.059  5568  5568 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 11:20:36.064   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d473096:true
,11-28 11:20:36.065  3473  3473 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 11:20:36.079   930  4620 I ActivityManager: Start proc 5580:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-28 11:20:36.091  5568  5568 D LocalBluetoothProfileManager: Adding local MAP profile
,11-28 11:20:36.094  5568  5568 D BluetoothMap: Create BluetoothMap proxy object
,11-28 11:20:36.103  5568  5568 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-28 11:20:36.115  5580  5580 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-28 11:20:36.119  5568  5568 D DockEventReceiver: finishStartingService: stopping service
,11-28 11:20:36.128   930  4620 I ActivityManager: Killing 4711:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-28 11:20:36.240  4173  4192 I bt_hci  : shut_down
,11-28 11:20:36.244  4173  4198 D bt_hwcfg: hw_epilog_process
,11-28 11:20:36.244  4173  4198 I bt_vendor: low_power_mode_cb
,11-28 11:20:36.246  4173  4198 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-28 11:20:36.246  4173  4198 I bt_vendor: epilog_cb
11-28 11:20:36.246  4173  4198 I bt_hci  : epilog_finished_callback
,11-28 11:20:36.248  4173  4192 I bt_hci_h4: hal_close
,11-28 11:20:36.248  4173  4192 I bt_userial_vendor: device fd = 54 close
,11-28 11:20:36.345  5580  5580 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-28 11:20:36.345  5580  5580 D StrictMode: ,	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.345  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMo,de: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.,java:177)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.k.d(PG:583)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.346  5580  5580 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:20:36.346  5580  5580 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:20:36.353  4173  4189 D bt_stack_manager: event_shut_down_stack finished.
11-28 11:20:36.353  5568  5568 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 11:20:36.353  4173  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-28 11:20:36.355  4173  4188 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-28 11:20:36.356  4173  4173 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 11:20:36.357  4173  4173 D BtGatt.GattService: Received stop request...Stopping profile...
11-28 11:20:36.357  4173  4173 D BtGatt.GattService: stop()
11-28 11:20:36.357  4173  4173 D BtGatt.AdvertiseManager: advertise clients cleared
11-28 11:20:36.358  4173  4173 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:36.359  4173  4173 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.359  4173  4173 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:36.359  4173  4173 V BluetoothAdapterState: isBleTurningOff()=true
11-28 11:20:36.359  4173  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-28 11:20:36.359  4173  4188 D BluetoothAdapterProperties: Setting state to 10
11-28 11:20:36.359  4173  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 11:20:36.359  4173  4188 I BluetoothAdapterState: Entering OffState
11-28 11:20:36.360   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-28 11:20:36.361  3473  3473 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 11:20:36.368  5568  5568 D DockEventReceiver: finishStartingService: stopping service
11-28 11:20:36.370   930  3313 I ActivityManager: Killing 5154:com.google.android.music:main/u0a59 (adj 15): empty #17
11-28 11:20:36.374  4173  4173 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-28 11:20:36.374  4173  4173 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-28 11:20:36.374  4173  4189 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-28 11:20:36.374  4173  4173 I BluetoothServiceJni: cleanupNative: return from cleanup
11-28 11:20:36.379  4173  4173 I art     : System.exit called, status: 0
11-28 11:20:36.379  4173  4173 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 11:20:36.440  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 11:20:36.469  5507  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 11:20:36.469  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 11:20:36.469  5507  5566 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 11:20:36.469  5507  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 11:20:36.472  5507  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 11:20:36.476   930  3027 I ActivityManager: Process com.android.bluetooth (pid 4173) has died
,11-28 11:20:36.491   930   947 I ActivityManager: Start proc 5612:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 11:20:36.551  5612  5612 D AdapterServiceConfig: Adding HeadsetService
,11-28 11:20:36.551  5612  5612 D AdapterServiceConfig: Adding A2dpService
11-28 11:20:36.551  5612  5612 D AdapterServiceConfig: Adding HidService
11-28 11:20:36.551  5612  5612 D AdapterServiceConfig: Adding HealthService
11-28 11:20:36.551  5612  5612 D AdapterServiceConfig: Adding PanService
11-28 11:20:36.552  5612  5612 D AdapterServiceConfig: Adding GattService
,11-28 11:20:36.552  5612  5612 D AdapterServiceConfig: Adding BluetoothMapService
11-28 11:20:36.552  5612  5612 D AdapterServiceConfig: Adding SapService
,11-28 11:20:36.561   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@392ed2a:true
,11-28 11:20:36.562  5612  5612 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 11:20:36.564  5612  5612 I bt_bluedroid: init
,11-28 11:20:36.564  5612  5625 I BluetoothAdapterState: Entering OffState
,11-28 11:20:36.566  5612  5626 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-28 11:20:36.566  5612  5626 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 11:20:36.566  5612  5626 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 11:20:36.566  5612  5626 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-28 11:20:36.566  5612  5612 I bt_bluedroid: get_profile_interface socket
,11-28 11:20:36.568  5612  5629 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-28 11:20:36.568  5612  5612 I bt_bluedroid: get_profile_interface sdp
11-28 11:20:36.569  5612  5629 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 11:20:36.572  5612  5623 I bt_bluedroid: config_hci_snoop_log
,11-28 11:20:36.573   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-28 11:20:36.576  5612  5625 D BluetoothAdapterState: Current state: OFF, message: 0
,11-28 11:20:36.576  5612  5625 D BluetoothAdapterProperties: Setting state to 14
11-28 11:20:36.576  5612  5625 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-28 11:20:36.577   540   540 I ServiceManager: Waiting for service AtCmdFwd...
11-28 11:20:36.577  5612  5625 D BluetoothBondStateMachine: make
,11-28 11:20:36.578  5612  5630 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 11:20:36.579  5580  5624 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-28 11:20:36.581  5612  5625 I BluetoothAdapterState: Entering PendingCommandState
11-28 11:20:36.581  5612  5612 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-28 11:20:36.583  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 11:20:36.584  5612  5612 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 11:20:36.584  5612  5612 D BtGatt.GattService: Received start request. Starting profile...
,11-28 11:20:36.584  5612  5612 D BtGatt.GattService: start()
11-28 11:20:36.584  5612  5612 I bt_bluedroid: get_profile_interface gatt
11-28 11:20:36.585  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 11:20:36.585  5612  5612 D BtGatt.AdvertiseManager: advertise manager created
,11-28 11:20:36.589  5612  5612 V BluetoothAdapterState: isTurningOff()=false
,11-28 11:20:36.589  5612  5612 V BluetoothAdapterState: isTurningOn()=false
11-28 11:20:36.589  5612  5612 V BluetoothAdapterState: isBleTurningOn()=true
11-28 11:20:36.589  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:36.589  5612  5625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-28 11:20:36.590  5612  5625 I bt_bluedroid: bt_bluedroid
11-28 11:20:36.590  5612  5626 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-28 11:20:36.591  5612  5626 I bt_hci  : start_up
,11-28 11:20:36.595  5612  5626 I bt_vendor: alloc value 0xf4088871
,11-28 11:20:36.595  5612  5626 I bt_vendor: init
11-28 11:20:36.595  5612  5626 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 11:20:36.595  5612  5626 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 11:20:36.599  5580  5601 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-28 11:20:36.614   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aba2e93:true
,11-28 11:20:36.704  5612  5626 D bt_hci  : start_up starting async portion
,11-28 11:20:36.705  5612  5634 I bt_hci  : event_finish_startup
11-28 11:20:36.705  5612  5634 I bt_hci_h4: hal_open
,11-28 11:20:36.705  5612  5634 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 11:20:36.700  5637  5637 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-28 11:20:36.706  5612  5634 I bt_userial_vendor: device fd = 54 open
,11-28 11:20:36.717  5612  5634 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 11:20:36.719  5612  5634 D bt_hwcfg: Chipset BCM4358A3
,11-28 11:20:36.719  5612  5634 D bt_hwcfg: Target name = [BCM4358A3]
11-28 11:20:36.720  5612  5634 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 11:20:36.979  5612  5625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-28 11:20:37.018  3473  5643 V NQFileLogger: [132] e.a: about to write to file
,11-28 11:20:37.022  3473  5643 V ProcessReports: [132] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-28 11:20:37.044  5612  5634 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 11:20:37.045  5612  5634 D bt_hwcfg: Settlement delay -- 100 ms
11-28 11:20:37.045  5612  5634 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 11:20:37.168  5612  5634 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 11:20:37.168  5612  5634 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-28 11:20:37.169  5612  5634 I bt_hwcfg: vendor lib fwcfg completed
,11-28 11:20:37.169  5612  5634 I bt_vendor: firmware callback
11-28 11:20:37.169  5612  5634 I bt_hci  : firmware_config_callback
,11-28 11:20:37.173  5612  5645 I bt_btu  : btu_task pending for preload complete event
,11-28 11:20:37.173  5612  5645 I bt_btu_task: Bluetooth chip preload is complete
11-28 11:20:37.173  5612  5645 I bt_btu  : btu_task received preload complete event
,11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_AVRC
11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_A2D
11-28 11:20:37.177  5612  5645 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_BTM
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_GAP
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_SDP
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_GATT
,11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_SMP
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 11:20:37.178  5612  5645 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 11:20:37.250  5612  5645 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4006549
,11-28 11:20:37.250  5612  5645 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4006549 
,11-28 11:20:37.270  5612  5629 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 11:20:37.272  5612  5629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 11:20:37.273  5612  5629 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-28 11:20:37.275  5612  5629 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 11:20:37.277  5612  5629 D BluetoothAdapterProperties: Scan Mode:20
,11-28 11:20:37.278  5612  5629 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-28 11:20:37.278  5612  5629 D bt_hci  : do_postload posting postload work item
11-28 11:20:37.278  5612  5634 I bt_hci  : event_postload
11-28 11:20:37.278  5612  5634 I bt_vendor: sco_config_cb
,11-28 11:20:37.278  5612  5634 I bt_hci  : sco_config_callback postload finished.
11-28 11:20:37.281  5612  5629 D bt_bte_conf: Device ID record 1 : primary
11-28 11:20:37.281  5612  5629 D bt_bte_conf:   vendorId            = 000f
11-28 11:20:37.281  5612  5629 D bt_bte_conf:   vendorIdSource      = 0001
11-28 11:20:37.281  5612  5629 D bt_bte_conf:   product             = 1200
,11-28 11:20:37.281  5612  5629 D bt_bte_conf:   version             = 1436
11-28 11:20:37.281  5612  5629 D bt_bte_conf:   clientExecutableURL = 
11-28 11:20:37.281  5612  5629 D bt_bte_conf:   serviceDescription  = 
,11-28 11:20:37.281  5612  5629 D bt_bte_conf:   documentationURL    = 
11-28 11:20:37.282  5612  5629 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 11:20:37.282  5612  5626 D bt_stack_manager: event_start_up_stack finished
11-28 11:20:37.283  5612  5625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 11:20:37.284  5612  5625 D BluetoothAdapterProperties: Setting state to 15
11-28 11:20:37.284  5612  5625 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-28 11:20:37.286  5612  5625 I BluetoothAdapterState: Entering BleOnState
11-28 11:20:37.287  5612  5634 I bt_vendor: low_power_mode_cb
,11-28 11:20:37.289  5612  5625 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-28 11:20:37.289  5612  5625 D BluetoothAdapterProperties: Setting state to 11
11-28 11:20:37.289  5612  5625 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-28 11:20:37.297  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 11:20:37.298  5612  5612 D HeadsetService: Received start request. Starting profile...
11-28 11:20:37.300  5612  5612 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 11:20:37.300  5612  5612 D HeadsetStateMachine: make
,11-28 11:20:37.306  5612  5625 I BluetoothAdapterState: Entering PendingCommandState
,11-28 11:20:37.309  5612  5612 D HeadsetStateMachine: max_hf_connections = 1
,11-28 11:20:37.309  5612  5612 I bt_bluedroid: get_profile_interface handsfree
11-28 11:20:37.309  5612  5629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-28 11:20:37.310  5612  5629 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-28 11:20:37.312  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 11:20:37.313  5612  5612 D A2dpService: Received start request. Starting profile...
,11-28 11:20:37.313  5612  5612 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-28 11:20:37.314  5612  5612 I bt_bluedroid: get_profile_interface avrcp
,11-28 11:20:37.319  5612  5612 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 11:20:37.319  5612  5612 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 11:20:37.319  5612  5612 D A2dpStateMachine: make
11-28 11:20:37.320  5612  5612 I bt_bluedroid: get_profile_interface a2dp
,11-28 11:20:37.321  5612  5629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-28 11:20:37.322  5612  5653 D A2dpStateMachine: Enter Disconnected: -2
,11-28 11:20:37.324  5612  5612 I BluetoothHidServiceJni: classInitNative: succeeds
,11-28 11:20:37.325  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 11:20:37.325  3473  3473 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 11:20:37.327  5568  5568 D BluetoothInputDevice: Proxy object connected
11-28 11:20:37.328  5568  5568 D HidProfile: Bluetooth service connected
11-28 11:20:37.329  5612  5612 D HidService: Received start request. Starting profile...
11-28 11:20:37.329  5612  5612 I bt_bluedroid: get_profile_interface hidhost
11-28 11:20:37.329  5612  5612 D HidService: setHidService(): set to: null
11-28 11:20:37.329  5612  5629 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fe756d
11-28 11:20:37.329  5612  5629 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 11:20:37.329  5612  5612 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-28 11:20:37.330  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 11:20:37.331  5612  5612 D HealthService: Received start request. Starting profile...
11-28 11:20:37.332  5612  5612 I bt_bluedroid: get_profile_interface health
11-28 11:20:37.333  5612  5612 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-28 11:20:37.334  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
,11-28 11:20:37.335  5568  5568 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 11:20:37.335  5612  5612 D PanService: Received start request. Starting profile...
11-28 11:20:37.336  5612  5612 D BluetoothPanServiceJni: initializeNative(L110): pan
11-28 11:20:37.336  5612  5612 I bt_bluedroid: get_profile_interface pan
11-28 11:20:37.336  5568  5568 D PanProfile: Bluetooth service connected
11-28 11:20:37.336  5612  5629 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-28 11:20:37.338  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 11:20:37.339  5568  5568 D BluetoothMap: Proxy object connected
11-28 11:20:37.339  5612  5612 D BluetoothMapService: Received start request. Starting profile...
11-28 11:20:37.339  5612  5612 D BluetoothMapService: start()
11-28 11:20:37.340  5568  5568 D MapProfile: Bluetooth service connected
11-28 11:20:37.340  5568  5568 D BluetoothMap: getConnectedDevices()
11-28 11:20:37.341  5568  5568 D BluetoothMap: Bluetooth is Not enabled
11-28 11:20:37.342  5612  5612 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-28 11:20:37.343  5612  5612 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-28 11:20:37.343  5612  5612 D BluetoothMapAppObserver: createReceiver()
11-28 11:20:37.344  5612  5612 D BluetoothMapAppObserver: initObservers()
11-28 11:20:37.344  5612  5612 D BluetoothMapAppObserver: getEnabledAccountItems()
11-28 11:20:37.350  5612  5612 V SapService: SapBinder()
11-28 11:20:37.350  5612  5612 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 11:20:37.352  5612  5612 D SapService: Received start request. Starting profile...
11-28 11:20:37.352  5612  5612 V SapService: start()
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.354  5612  5651 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.354  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.355  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.356  5612  5612 V BluetoothAdapterState: isTurningOff()=false
11-28 11:20:37.356  5612  5612 V BluetoothAdapterState: isTurningOn()=true
11-28 11:20:37.356  5612  5612 V BluetoothAdapterState: isBleTurningOn()=false
11-28 11:20:37.356  5612  5612 V BluetoothAdapterState: isBleTurningOff()=false
11-28 11:20:37.356  5612  5625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 11:20:37.356  5612  5625 D BluetoothAdapterProperties: ScanMode =  20
11-28 11:20:37.357  5612  5625 D BluetoothAdapterProperties: State =  11
11-28 11:20:37.358  5612  5629 D BluetoothAdapterProperties: Scan Mode:21
11-28 11:20:37.358  5612  5625 D BluetoothAdapterProperties: Setting state to 12
11-28 11:20:37.358  5612  5625 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-28 11:20:37.358  5612  5629 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 11:20:37.359  5568  5579 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 11:20:37.359  5612  5625 I BluetoothAdapterState: Entering OnState
11-28 11:20:37.360   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 11:20:37.360  5568  5578 D BluetoothPan: onBluetoothStateChange on: true
11-28 11:20:37.361  3030  3046 D BluetoothMap: onBluetoothStateChange: up=true
11-28 11:20:37.362  3030  3863 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 11:20:37.362  3030  3030 D BluetoothMap: Proxy object connected
11-28 11:20:37.362  3030  3030 D MapProfile: Bluetooth service connected
11-28 11:20:37.362  3030  3030 D BluetoothMap: getConnectedDevices()
11-28 11:20:37.364  3030  3046 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 11:20:37.365  3030  3030 D BluetoothA2dp: Proxy object connected
11-28 11:20:37.366  5568  5579 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 11:20:37.367  3030  3030 D BluetoothInputDevice: Proxy object connected
11-28 11:20:37.367  3030  3030 D HidProfile: Bluetooth service connected
11-28 11:20:37.367  5568  5578 D BluetoothMap: onBluetoothStateChange: up=true
11-28 11:20:37.367   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 11:20:37.368  3030  3041 D BluetoothPan: onBluetoothStateChange on: true
11-28 11:20:37.368  5612  5612 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 11:20:37.369  5612  5612 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-28 11:20:37.370  5612  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:37.371   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 11:20:37.371  3030  3030 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 11:20:37.371  3030  3030 D PanProfile: Bluetooth service connected
11-28 11:20:37.371  3030  3863 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 11:20:37.371  3030  3041 D BluetoothPbap: onBluetoothStateChange: up=true
,11-28 11:20:37.372  5612  5612 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:37.373  3659  4033 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 11:20:37.373  5612  5612 D ObexServerSockets: Succeed to create listening sockets 
11-28 11:20:37.373  5612  5612 D ObexServerSockets0: startAccept()
11-28 11:20:37.373  5612  5612 D ObexServerSockets0: prepareForNewConnect()
11-28 11:20:37.373   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 11:20:37.374   930   930 D BluetoothA2dp: Proxy object connected
11-28 11:20:37.375  5612  5612 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-28 11:20:37.375  5612  5612 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 11:20:37.375  5612  5612 D BluetoothMapService: onReceive
11-28 11:20:37.375  5612  5612 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 11:20:37.375  5612  5612 D BluetoothMapService: STATE_ON
,11-28 11:20:37.377  5612  5659 D ObexServerSockets0: Accepting socket connection...
,11-28 11:20:37.379   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-28 11:20:37.379  5612  5658 D ObexServerSockets0: Accepting socket connection...
11-28 11:20:37.380  5612  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 11:20:37.380  5568  5568 D LocalBluetoothProfileManager: Adding local A2DP profile
11-28 11:20:37.381  5612  5661 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-28 11:20:37.381  5612  5661 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-28 11:20:37.384  5568  5568 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-28 11:20:37.389  5568  5568 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 11:20:37.392  5568  5568 D BluetoothA2dp: Proxy object connected
,11-28 11:20:37.395  3473  3473 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 11:20:37.399  5568  5568 D DockEventReceiver: finishStartingService: stopping service
,11-28 11:20:37.404  3030  3030 D BluetoothPbap: Proxy object connected
11-28 11:20:37.404  3030  3030 D PbapServerProfile: Bluetooth service connected
,11-28 11:20:37.404  5612  5612 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 11:20:37.404  5612  5612 D ObexServerSockets0: prepareForNewConnect()
,11-28 11:20:37.409  5568  5568 D BluetoothPbap: Proxy object connected
11-28 11:20:37.410  5568  5568 D PbapServerProfile: Bluetooth service connected
,11-28 11:20:37.414  5612  5665 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 11:20:37.426  5612  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 11:20:37.428  5612  5669 I BtOppRfcommListener: Accept thread started.
,11-28 11:20:37.462   930   930 D BluetoothHeadset: Proxy object connected
11-28 11:20:37.462   930   930 D BluetoothHeadset: Proxy object connected
,11-28 11:20:37.462  3030  3041 D BluetoothHeadset: Proxy object connected
11-28 11:20:37.462  3030  3030 D HeadsetProfile: Bluetooth service connected
11-28 11:20:37.462   930   930 D BluetoothHeadset: Proxy object connected
,11-28 11:20:37.463  3659  3683 D BluetoothHeadset: Proxy object connected
,11-28 11:20:37.467   930   947 D BluetoothHeadset: Proxy object connected
,11-28 11:20:37.471   930   947 D BluetoothHeadset: Proxy object connected
,11-28 11:20:37.471  3030  3046 D BluetoothHeadset: Proxy object connected
11-28 11:20:37.472  3030  3030 D HeadsetProfile: Bluetooth service connected
,11-28 11:20:37.473  3659  3921 D BluetoothHeadset: Proxy object connected
,11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 11:20:37.482  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 11:20:37.483  5507  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 11:20:37.484  5507  5553 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-28 11:20:37.485   930  3027 D WifiService: setWifiEnabled: false pid=5507, uid=10077
11-28 11:20:37.485   930  3027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 11:20:37.486   930  2860 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-28 11:20:37.487   930  2860 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 11:20:37.487   930  2860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 11:20:37.487   930  2860 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 11:20:37.487  5507  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 11:20:37.487  5568  5579 D BluetoothHeadset: Proxy object connected
11-28 11:20:37.488  5568  5568 D HeadsetProfile: Bluetooth service connected
,11-28 11:20:37.498   930  5254 D DhcpClient: Clearing IP address
,11-28 11:20:37.499   509   920 D CommandListener: Clearing all IP addresses on wlan0
,11-28 11:20:37.506   509   920 D CommandListener: Setting iface cfg
,11-28 11:20:37.507  3473  5321 V NativeCrypto: Read error: ssl=0x7f90548b80: I/O error during system call, Connection timed out
,11-28 11:20:37.509  3473  5321 V NativeCrypto: SSL shutdown failed: ssl=0x7f90548b80: I/O error during system call, Broken pipe
11-28 11:20:37.510   930  4620 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-28 11:20:37.511   930  5252 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-28 11:20:37.512   930  5252 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-28 11:20:37.513   930  2872 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-28 11:20:37.513   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-28 11:20:37.514   930  2872 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-28 11:20:37.520   930  2872 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-28 11:20:37.521   930  2872 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-28 11:20:37.523   538   538 E Parcel  : Reading a NULL string not supported here.
,11-28 11:20:37.527   930   930 D RttService: SCAN_AVAILABLE : 1
,11-28 11:20:37.527   930  2955 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 11:20:37.528   930  2872 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-28 11:20:37.530  3630  3786 W QCNEJ   : |CORE| network lost: 100
11-28 11:20:37.530  3630  3786 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-28 11:20:37.532   930  5255 D DhcpClient: Receive thread stopped
,11-28 11:20:37.542   930  2860 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-28 11:20:37.550   930  2860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 11:20:37.552   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 11:20:37.574   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-28 11:20:37.574   509   920 D CommandListener: Clearing all IP addresses on wlan0
11-28 11:20:37.575   930  2872 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-28 11:20:37.575   509   920 D TetherController: Setting IP forward enable = 0
11-28 11:20:37.575   930  2872 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 11:20:37.578   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-28 11:20:37.580   540   540 I ServiceManager: Waiting for service AtCmdFwd...
11-28 11:20:37.581   930  2860 D DhcpClient: doQuit
11-28 11:20:37.581   930  2860 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-28 11:20:37.582  3338  3338 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 11:20:37.583   930  5254 D DhcpClient: onQuitting
11-28 11:20:37.584  3797  3797 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-28 11:20:37.588  4836  4860 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-28 11:20:37.588  4836  4860 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-28 11:20:37.588  4836  4860 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 11:20:37.588  4836  4860 E SarControlService: no key has been found,reset the power
11-28 11:20:37.589  4836  4873 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 11:20:37.589  4836  4873 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-28 11:20:37.589  4836  4873 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 11:20:37.589  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 11:20:37.589  4861  4861 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 11:20:37.590  4836  4873 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 11:20:37.591  4836  4873 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-28 11:20:37.592  4836  4873 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 11:20:37.593  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 11:20:37.593  4861  4861 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 11:20:37.593  3821  3821 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 11:20:37.594  4861  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000ea03000000000000ffffffff]
11-28 11:20:37.594  4861  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 11:20:37.594  4861  4875 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-28 11:20:37.594  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 11:20:37.594  4836  4846 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 11:20:37.596  3821  3821 D SystemUpdateService: onCreate
11-28 11:20:37.598  4861  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000eb03000000000000ffffffff]
11-28 11:20:37.598  4861  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 11:20:37.598  4861  4875 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-28 11:20:37.599  3821  3821 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 11:20:37.601  3338  3338 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-28 11:20:37.602  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 11:20:37.603  4836  4847 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 11:20:37.606  3821  5684 I SystemUpdateService: active receiver: enabled
11-28 11:20:37.607  3338  3338 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-28 11:20:37.609  3821  3821 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-28 11:20:37.609  3821  5684 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 11:20:37.610   509   913 W SocketClient: write error (Broken pipe)
,11-28 11:20:37.610   509   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-28 11:20:37.611   509   913 W SocketListener: Error sending broadcast (Broken pipe)
11-28 11:20:37.612  3821  5287 I iu.UploadsManager: num queued entries: 0
11-28 11:20:37.612  3821  5287 I iu.UploadsManager: num updated entries: 0
11-28 11:20:37.613  3821  5287 I iu.SyncManager: NEXT; no task
,11-28 11:20:37.615  3821  5684 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-28 11:20:37.616  3821  5684 I SystemUpdateService: now status is 0 (complete)
11-28 11:20:37.616  3821  5684 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 11:20:37.616  3821  5684 I SystemUpdateService: file has been verified
,11-28 11:20:37.616  3821  5684 I SystemUpdateService: OTA package size = 21989297
,11-28 11:20:37.618  3821  5684 I SystemUpdateService: showing system update notification
,11-28 11:20:37.625  3821  3821 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 11:20:37.626  3821  3821 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 11:20:37.628  5291  5291 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-28 11:20:37.630  3821  3821 D SystemUpdateService: onDestroy
,11-28 11:20:37.636   509   920 E Netd    : netlink response contains error (No such file or directory)
,11-28 11:20:37.636   509   920 D TetherController: Setting IP forward enable = 0
11-28 11:20:37.637   930  2872 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-28 11:20:37.637   930  2872 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 11:20:37.640  5291  5291 D SprintDMHelper: simOperator: 
,11-28 11:20:37.640  5291  5291 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 11:20:37.652  4781  5693 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 11:20:37.655  3338  3338 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 11:20:37.658  3338  3338 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 11:20:37.666   930  3813 I ActivityManager: Start proc 5694:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-28 11:20:37.669  4781  4781 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 11:20:37.669   930  2860 D wifi    : In wifi stop Hal
11-28 11:20:37.669   930  2860 D wifi    : halHandle = 0x7f80a76200, mVM = 0x7f9b04d140, mCls = 0x100a12
11-28 11:20:37.669   930  3337 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 11:20:37.669   930  3337 D WifiHAL : Got a signal to exit!!!
11-28 11:20:37.669   930  3337 I WifiHAL : Exit wifi_event_loop
11-28 11:20:37.670   930  2860 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 11:20:37.670   930  2860 E WifiHAL : Event processing terminated
11-28 11:20:37.670   930  2860 D wifi    : In wifi cleaned up handler
,11-28 11:20:37.670   930  2860 I WifiHAL : Internal cleanup completed
11-28 11:20:37.671  4008  4125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 11:20:37.692   930  3337 D wifi    : set interface wlan0 flags (DOWN)
,11-28 11:20:37.692   930  2860 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 11:20:37.699  5694  5694 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-28 11:20:37.897   930   947 D Tethering: InitialState.processMessage what=4
,11-28 11:20:37.903   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 11:20:37.994  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 11:20:37.999  5507  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 11:20:38.004   930  3488 D WifiService: setWifiEnabled: true pid=5507, uid=10077
,11-28 11:20:38.004   930  3488 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 11:20:38.007  5507  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 11:20:38.011   509   920 D SoftapController: Softap fwReload - Ok
,11-28 11:20:38.017   509   920 D CommandListener: Setting iface cfg
,11-28 11:20:38.017   509   920 D CommandListener: Trying to bring down wlan0
11-28 11:20:38.018   509   920 D CommandListener: Clearing all IP addresses on wlan0
,11-28 11:20:38.021   930  2860 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 11:20:38.510   930  3313 D WifiService: setWifiEnabled: true pid=5507, uid=10077
,11-28 11:20:38.513   930  3313 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 11:20:38.581   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 11:20:38.611   930  2860 D wifi    : set interface wlan0 flags (UP)
,11-28 11:20:38.612   930  2860 I WifiHAL : Initializing wifi
,11-28 11:20:38.612   930  2860 I WifiHAL : Creating socket
,11-28 11:20:38.617   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 11:20:38.623   930  2860 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-28 11:20:38.624   930  2860 D wifi    : Did set static halHandle = 0x7f80a76200
11-28 11:20:38.624   930  2860 D wifi    : halHandle = 0x7f80a76200, mVM = 0x7f9b04d140, mCls = 0x200d66
,11-28 11:20:38.624   930  2860 D wifi    : array field set
11-28 11:20:38.624   930  2860 I WifiNative-HAL: interface[0] = wlan0
11-28 11:20:38.626   930  5710 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547619299840
11-28 11:20:38.626   930  5710 D wifi    : waitForHalEvents called, vm = 0x7f9b04d140, obj = 0x200d66, env = 0x7f83e3dd40
,11-28 11:20:38.706  5711  5711 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 11:20:38.728  5711  5711 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 11:20:38.734   930  2860 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 11:20:38.760  5711  5711 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 11:20:38.760  5711  5711 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 11:20:38.775   930  2860 D WifiConfigStore: Loading config and enabling all networks 
,11-28 11:20:38.784   930  2860 D WifiConfigStore: loaded 0 passpoint configs
,11-28 11:20:38.785   930  2860 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-28 11:20:38.785   930  2860 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-28 11:20:38.786   930  2860 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-28 11:20:38.788   930  2860 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 11:20:38.788   930  2860 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-28 11:20:38.788   930  2860 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-28 11:20:38.788   930  2860 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-28 11:20:38.792   930  2860 D WifiNative-HAL: Setting external_sim to 1
11-28 11:20:38.792  4781  4781 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 11:20:38.792   930  2860 D wifi    : setting dfs flag to true, 0x7f84bfddc0
11-28 11:20:38.793   930  2860 D WifiStateMachine: Setting OUI to DA-A1-19
,11-28 11:20:38.793   930  2860 D wifi    : setting scan oui 0x7f84bfddc0
11-28 11:20:38.793   930  2860 D WifiHAL : Sending mac address OUI
,11-28 11:20:38.797   930  2860 E native  : do suspend false
,11-28 11:20:38.804   930  2860 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 11:20:38.804   930   930 D RttService: SCAN_AVAILABLE : 3
11-28 11:20:38.804   509   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 11:20:38.805   930  2955 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-28 11:20:38.806   509   920 D CommandListener: Setting iface cfg
,11-28 11:20:38.809   930  2843 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-28 11:20:38.809   930  2843 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 11:20:38.817   930  2843 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 11:20:38.821   930  2843 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
11-28 11:20:38.821   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=194181 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 11:20:39.024  5507  5566 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 11:20:39.032  5507  5566 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 11:20:39.036  5507  5553 D BluetoothAdapter: enable(): BT is already enabled..!
,11-28 11:20:39.037   930   940 D WifiService: setWifiEnabled: true pid=5507, uid=10077
11-28 11:20:39.037   930   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-28 11:20:39.038  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 11:20:39.038  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 11:20:39.038  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 11:20:39.039  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a170a removed from the list
11-28 11:20:39.039  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 11:20:39.039  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30d0b7b removed from the list
,11-28 11:20:39.039  5507  5553 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 11:20:39.042  5507  5553 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-28 11:20:39.044  5507  5553 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-28 11:20:39.046  5507  5553 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-28 11:20:39.048  5507  5553 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-28 11:20:39.051  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-28 11:20:39.052  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-28 11:20:39.053  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-28 11:20:39.053  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-28 11:20:39.054  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-28 11:20:39.058  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-28 11:20:39.058  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@41b0bc4 Bundle[{}]
11-28 11:20:39.059  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-28 11:20:39.059  5507  5553 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 11:20:39.060  5507  5553 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-28 11:20:39.061  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-28 11:20:39.061  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-28 11:20:39.062  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-28 11:20:39.062  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-28 11:20:39.064  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-28 11:20:39.064  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-28 11:20:39.064  5507  5553 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-28 11:20:39.065  5507  5553 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-28 11:20:39.067  5507  5553 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-28 11:20:39.069  5507  5553 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-28 11:20:39.071  5507  5553 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-28 11:20:39.072  5507  5553 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-28 11:20:39.073  5507  5553 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-28 11:20:39.073  5507  5553 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
11-28 11:20:39.075  5507  5553 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
11-28 11:20:39.076  5507  5553 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-28 11:20:40.082  5507  5553 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-28 11:20:40.084  5507  5553 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-28 11:20:40.088  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-28 11:20:40.090  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-28 11:20:40.092  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-28 11:20:40.092  5507  5553 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,11-28 11:20:40.094  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-28 11:20:40.094  5507  5553 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-28 11:20:40.095  5507  5553 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,11-28 11:20:40.096  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-28 11:20:40.098  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-28 11:20:40.099  5507  5553 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-28 11:20:40.100  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 11:20:40.100  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f3c9f1 added. We now have 3 listener(s)
11-28 11:20:40.102  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:40.102  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 11:20:40.102  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 11:20:40.102  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 11:20:40.102  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eba99d6 added. We now have 3 listener(s)
11-28 11:20:40.103  5507  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 11:20:40.103  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 11:20:40.111  5507  5553 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-28 11:20:40.112  5507  5553 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-28 11:20:40.112  5507  5553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-28 11:20:40.112  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-28 11:20:40.112  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.112  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.112  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.112  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-28 11:20:40.113  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 11:20:40.113  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 11:20:40.113  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:40.113  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-28 11:20:40.122  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 11:20:40.124  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 11:20:40.124  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 11:20:40.124  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 11:20:40.124  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 11:20:40.124  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-28 11:20:40.124  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 11:20:40.124  5507  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 11:20:40.124  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:40.124  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 11:20:40.125  5507  5717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 11:20:40.124  5623  5623 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[35110]" dev="sockfs" ino=35110 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:40.124  5623  5623 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[35110]" dev="sockfs" ino=35110 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:40.129  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 11:20:40.129  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 11:20:40.129  5507  5717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 11:20:40.129  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 11:20:40.134  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:40.134  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 11:20:40.135  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 11:20:40.135  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 11:20:40.135  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-28 11:20:40.137  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.138  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.138  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-28 11:20:40.138  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 11:20:40.138  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:40.138  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
11-28 11:20:40.138  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:40.138  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:40.138  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.138  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 11:20:40.138  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 11:20:40.138  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.139  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.139  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.140  5507  5553 D BluetoothAdapter: STATE_ON
,11-28 11:20:40.144  5612  5660 D BtGatt.GattService: registerClient() - UUID=87d9cbf1-1418-49a9-aec4-6998cb9b2250
,11-28 11:20:40.144  5612  5629 D BtGatt.GattService: onClientRegistered() - UUID=87d9cbf1-1418-49a9-aec4-6998cb9b2250, clientIf=5
,11-28 11:20:40.145  5507  5517 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-28 11:20:40.147  5612  5632 D BtGatt.AdvertiseManager: message : 0
,11-28 11:20:40.149  5612  5632 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 11:20:40.160  5612  5629 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-28 11:20:40.166  5612  5629 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-28 11:20:40.167  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.167  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:40.167  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 11:20:40.167  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.167  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.167  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.167  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.168  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:40.168  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 11:20:40.169  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-28 11:20:40.169  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.170  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.170  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.170  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:40.170  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.171  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.172  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.174  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.174  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-28 11:20:40.174  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.174  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:40.174  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-28 11:20:40.675  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-28 11:20:40.676  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-28 11:20:40.676  5507  5507 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 11:20:41.951  5711  5711 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 11:20:41.955  5711  5711 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 11:20:41.962  5711  5711 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 11:20:41.992   930  3675 I ActivityManager: Killing 5346:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-28 11:20:42.023   930  2860 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 11:20:42.035   930  2860 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-28 11:20:42.036   930  2860 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 11:20:42.047   930  2860 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 11:20:42.083   930  2860 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 11:20:42.085  5711  5711 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 11:20:42.519  5711  5711 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 11:20:42.553  5711  5711 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 11:20:42.555  5711  5711 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 11:20:42.567   930  2860 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 11:20:42.568   930  2860 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 11:20:42.568   930  2872 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 11:20:42.585   930  2860 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 11:20:42.599   509   920 D CommandListener: Setting iface cfg
,11-28 11:20:42.606   930  2860 D WifiStateMachine: Start Dhcp Watchdog 2
,11-28 11:20:42.611   930  5722 D DhcpClient: Receive thread started
,11-28 11:20:42.616   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:20:42.616   930  2860 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-28 11:20:42.616   930  2872 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-28 11:20:42.699   930  2860 E native  : do suspend false
,11-28 11:20:42.713   930  5721 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 11:20:42.725   930  5722 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172643, domain null
,11-28 11:20:42.726   930  5721 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172643 seconds
11-28 11:20:42.727   930  5721 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-28 11:20:42.738   930  5722 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 11:20:42.738   930  5721 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 11:20:42.739   509   920 D CommandListener: Setting iface cfg
,11-28 11:20:42.741   930  2860 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 11:20:42.743   930  5721 D DhcpClient: Scheduling renewal in 86399s
,11-28 11:20:42.749   930  2860 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-28 11:20:42.749   930  2860 D WifiConfigStore: No blacklist allowed without epno enabled
,11-28 11:20:42.749   930  2872 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-28 11:20:42.750   930  2860 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-28 11:20:42.752   930  2872 D ConnectivityService: Adding iface wlan0 to network 101
,11-28 11:20:42.781   930  2872 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-28 11:20:42.781   930  2872 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-28 11:20:42.783   930  2872 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-28 11:20:42.785   930  2872 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-28 11:20:42.787   930  2872 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
11-28 11:20:42.792   930  2872 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-28 11:20:42.796   930  2872 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-28 11:20:42.796   930  2872 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-28 11:20:42.796   930  2872 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,11-28 11:20:42.796   930  2860 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-28 11:20:42.796   930  2872 D ConnectivityService:    accepting network in place of null
11-28 11:20:42.796   930  2860 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 11:20:42.797   930  2872 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 11:20:42.816   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 11:20:42.823   930  5720 D NetlinkSocketObserver: NeighborEvent{elapsedMs=198183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 11:20:42.835   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 11:20:42.838   930  2872 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-28 11:20:42.838  3630  3786 W QCNEJ   : |CORE| network available: 101
11-28 11:20:42.838   930  2872 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 11:20:42.839   930  2872 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-28 11:20:42.839   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-28 11:20:42.847  3630  3786 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-28 11:20:42.848  3630  3786 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-28 11:20:42.848  3630  3786 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-28 11:20:42.854  4836  4860 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 11:20:42.854  4836  4860 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 11:20:42.855  4836  4860 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-28 11:20:42.855  4836  4860 E SarControlService: no key has been found,reset the power
11-28 11:20:42.855  4836  4873 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 11:20:42.855  4836  4873 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 11:20:42.855  4836  4873 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 11:20:42.855  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 11:20:42.855  4861  4861 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-28 11:20:42.859  4836  4873 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 11:20:42.859  4836  4873 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 11:20:42.859  4836  4873 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 11:20:42.860  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 11:20:42.860  4861  4861 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 11:20:42.861  3797  3797 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-28 11:20:42.862  4861  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000ec03000000000000ffffffff]
11-28 11:20:42.862  4861  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 11:20:42.862  4861  4875 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-28 11:20:42.864  4861  4875 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@11ff700 HexData = [00000000ed03000000000000ffffffff]
,11-28 11:20:42.865  3821  3821 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-28 11:20:42.869  4861  4875 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-28 11:20:42.869  4861  4875 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-28 11:20:42.869  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 11:20:42.870  4836  4846 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 11:20:42.870  3821  3821 D SystemUpdateService: onCreate
11-28 11:20:42.871  4861  4861 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 11:20:42.871  4836  4847 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 11:20:42.876  3821  3821 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 11:20:42.887  3821  3821 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-28 11:20:42.892  3821  5287 I iu.UploadsManager: num queued entries: 0
,11-28 11:20:42.892  3821  5287 I iu.UploadsManager: num updated entries: 0
,11-28 11:20:42.897  3821  3821 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 11:20:42.898  3821  3821 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-28 11:20:42.900  5291  5291 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 11:20:42.903  5291  5291 D SprintDMHelper: simOperator: 
,11-28 11:20:42.903  5291  5291 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-28 11:20:42.903   930  5719 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-28 11:20:42.915  3821  5732 I SystemUpdateService: active receiver: enabled
,11-28 11:20:42.893  3821  5287 I iu.SyncManager: NEXT; no task
,11-28 11:20:42.939  3821  5732 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 11:20:42.945  3821  5732 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-28 11:20:42.946  3821  5732 I SystemUpdateService: now status is 0 (complete)
11-28 11:20:42.946  3821  5732 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 11:20:42.946  3821  5732 I SystemUpdateService: file has been verified
11-28 11:20:42.946  3821  5732 I SystemUpdateService: OTA package size = 21989297
,11-28 11:20:42.953  3821  5732 I SystemUpdateService: showing system update notification
,11-28 11:20:42.965   930  5719 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 16:20:42 GMT], X-Android-Received-Millis=[1480350042964], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480350042933]}
,11-28 11:20:42.965   930  2872 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-28 11:20:42.965  3821  3821 D SystemUpdateService: onDestroy
,11-28 11:20:42.965   930  2872 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-28 11:20:42.965   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-28 11:20:42.967   930  2872 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-28 11:20:43.005  4781  5736 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-28 11:20:43.673  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-28 11:20:43.673  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 11:20:43.673  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 11:20:43.674  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 11:20:43.674  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 11:20:43.674  5507  5717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 11:20:43.674  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 11:20:43.675  5507  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 11:20:43.675  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 11:20:43.675  5507  5717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 11:20:43.675  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 11:20:43.675  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 11:20:43.676  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 11:20:43.676  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 11:20:43.677  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.677  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 11:20:43.677  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 11:20:43.677  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 11:20:43.677  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 11:20:43.677  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.678  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.678  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.678  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.680  5507  5553 D BluetoothAdapter: STATE_ON
,11-28 11:20:43.680  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 11:20:43.682  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:43.682  5507  5553 D BluetoothLeScanner: could not find callback wrapper
,11-28 11:20:43.682  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 11:20:43.682  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.682  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.682  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.683  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 11:20:43.683  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.684  5612  5632 D BtGatt.AdvertiseManager: message : 1
,11-28 11:20:43.686  5612  5632 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-28 11:20:43.699  5612  5629 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-28 11:20:43.699  5612  5629 D BtGatt.GattService: Client app is not null!
11-28 11:20:43.701  5612  5622 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:43.702  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 11:20:43.702  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.702  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:43.703  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.703  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.703  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.703  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 11:20:43.703  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 11:20:43.705  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 11:20:43.706  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.709  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.709  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:43.709  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.710  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.710  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 11:20:43.710  5507  5507 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-28 11:20:43.711  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:43.711  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:43.711  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:43.711  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.711  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 11:20:43.711  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-28 11:20:43.712  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.712  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.712  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.712  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:43.713  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.713  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 11:20:43.714  5507  5553 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-28 11:20:43.714  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 11:20:43.715  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.715  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 11:20:43.715  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-28 11:20:43.715  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 11:20:43.715  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.716  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 11:20:43.716  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 11:20:43.716  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-28 11:20:43.720  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 11:20:43.726  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-28 11:20:43.726  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 11:20:43.726  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 11:20:43.735  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.735  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 11:20:43.736  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 11:20:43.736  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 11:20:43.736  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-28 11:20:43.740  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-28 11:20:43.744  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-28 11:20:43.745  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.745  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 11:20:43.745  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-28 11:20:43.745  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 11:20:43.746  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 11:20:43.746  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.747  5507  5553 D BluetoothAdapter: STATE_ON
,11-28 11:20:43.751  5612  5650 D BtGatt.GattService: registerClient() - UUID=12b25604-cf23-43b7-9fe0-cc36feadf168
,11-28 11:20:43.752  5612  5629 D BtGatt.GattService: onClientRegistered() - UUID=12b25604-cf23-43b7-9fe0-cc36feadf168, clientIf=5
,11-28 11:20:43.753  5507  5518 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 11:20:43.754  5612  5660 D BtGatt.GattService: start scan with filters
,11-28 11:20:43.759  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 11:20:43.759  5612  5633 D BtGatt.ScanManager: handling starting scan
11-28 11:20:43.759  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.759  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 11:20:43.759  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.760  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 11:20:43.760  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:43.760  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 11:20:43.760  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 11:20:43.760  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 11:20:43.761  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.761  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.761  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.761  5612  5633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3733871
11-28 11:20:43.762  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.763  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 11:20:43.763  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.766  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.766  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 11:20:43.766  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:43.766  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:43.769  5612  5629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-28 11:20:43.769  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.769  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:43.769  5612  5633 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 11:20:43.772  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 11:20:43.772  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.772  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:43.772  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-28 11:20:43.775  5612  5629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 11:20:43.776  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:43.776  5612  5633 D BtGatt.ScanManager: Starting BLE batch scan
11-28 11:20:43.776  5612  5633 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 11:20:43.785  5612  5629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 11:20:43.785  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:43.790  5612  5629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 11:20:43.790  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:43.838   930  2872 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-28 11:20:44.273  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-28 11:20:44.274  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 11:20:44.274  5507  5507 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 11:20:45.864   930  2860 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,11-28 11:20:46.768  5507  5553 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-28 11:20:46.769  5507  5553 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-28 11:20:46.769  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-28 11:20:46.769  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.770  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.770  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-28 11:20:46.770  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.770  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-28 11:20:46.771  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.771  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.771  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 11:20:46.771  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 11:20:46.771  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.772  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.772  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.774  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:46.775  5612  5660 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-28 11:20:46.776  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-28 11:20:46.777  5612  5633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 11:20:46.778  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:46.779  5612  5623 D BtGatt.GattService: stopScan() - queue size =1
,11-28 11:20:46.782  5612  5650 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:46.782  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 11:20:46.783  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.783  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:46.783  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.783  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 11:20:46.783  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.783  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.784  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 11:20:46.784  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 11:20:46.784  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 11:20:46.784  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 11:20:46.784  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.786  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:46.789  5612  5612 D BtGatt.ScanManager: awakened up at time 202148
11-28 11:20:46.791  5612  5622 D BtGatt.GattService: registerClient() - UUID=f22dbaab-09d6-4c5d-a07d-779b5cf6049f
11-28 11:20:46.793  5612  5629 D BtGatt.GattService: onClientRegistered() - UUID=f22dbaab-09d6-4c5d-a07d-779b5cf6049f, clientIf=5
11-28 11:20:46.793  5507  5518 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 11:20:46.794  5612  5650 D BtGatt.GattService: start scan with filters
,11-28 11:20:46.799  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 11:20:46.799  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.799  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 11:20:46.800  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.800  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.800  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:46.800  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 11:20:46.800  5507  5553 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-28 11:20:46.800  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.800  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-28 11:20:46.800  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 11:20:46.800  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 11:20:46.800  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 11:20:46.800  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.801  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-28 11:20:46.802  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-28 11:20:46.802  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-28 11:20:46.802  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-28 11:20:46.802  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 11:20:46.802  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 11:20:46.803  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 11:20:46.803  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-28 11:20:46.803  5507  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 11:20:46.804  5507  5746 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 11:20:46.805  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 11:20:46.805  5507  5553 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 11:20:46.807  5507  5746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-28 11:20:46.800  5623  5623 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33164]" dev="sockfs" ino=33164 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-28 11:20:46.800  5623  5623 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33164]" dev="sockfs" ino=33164 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 11:20:46.809  5612  5629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-28 11:20:46.809  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:46.809  5612  5629 D BtGatt.GattService: current time is 202169445135
11-28 11:20:46.811  5612  5629 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -72, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -68, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 48, -60, -48, -14, 51, -33, 1, 0, -94, 39, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 9, 105, 101, 3, 2, -29, 20, 61, -18, -50, -126, 28, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 50, -35, 86, -77, -92, -11, 1, 0, -100, 37, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 67, 113, 101, 3, 2, -33, 21, 61, -123, -14, 66, 28, 6, 8, 116, 105, 115, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 35, 97, 126, -92, 22, -56, 1, -128, -70, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 86, -31, -99, 30, -52, -57, 1, 0, -92, 32, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, 12, -111, 101, 3, 2, -29, 20, 62, -43, 83, 92, 28, 6, 8, 116, 105, 115, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-28 11:20:46.812  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 11:20:46.812  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.812  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.812  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.812  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-28 11:20:46.812  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-28 11:20:46.813  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-28 11:20:46.813  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-28 11:20:46.813  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-28 11:20:46.813  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -26, 55, -125, -44, -32, -2, 61, 78, 9, 105, 101, 3, 2, -29, 20, 61, -18, -50, -126, 6, 8, 116, 105, 115, 53, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-28 11:20:46.813  5507  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 11:20:46.813  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-28 11:20:46.813  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 67, 113, 101, 3, 2, -33, 21, 61, -123, -14, 66, 6, 8, 116, 105, 115, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-28 11:20:46.813  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.813  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-28 11:20:46.813  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-28 11:20:46.813  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.813  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 11:20:46.813  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.813  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.813  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, 12, -111, 101, 3, 2, -29, 20, 62, -43, 83, 92, 6, 8, 116, 105, 115, 53, 54, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-28 11:20:46.814  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:46.817  5612  5660 D BtGatt.GattService: registerClient() - UUID=867deb02-cdfb-4a3e-8536-116ad152d2df
11-28 11:20:46.817  5612  5629 D BtGatt.GattService: onClientRegistered() - UUID=867deb02-cdfb-4a3e-8536-116ad152d2df, clientIf=6
,11-28 11:20:46.818  5507  5517 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-28 11:20:46.819  5612  5629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 11:20:46.819  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:46.820  5612  5632 D BtGatt.AdvertiseManager: message : 0
,11-28 11:20:46.822  5612  5632 D BtGatt.AdvertiseManager: starting multi advertising
,11-28 11:20:46.823  5612  5633 D BtGatt.ScanManager: stopping BLe Batch
,11-28 11:20:46.828  5612  5629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 11:20:46.828  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:46.829  5612  5633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 11:20:46.836  5612  5629 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-28 11:20:46.840  5612  5629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 11:20:46.840  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:46.842  5612  5633 D BtGatt.ScanManager: handling starting scan
,11-28 11:20:46.844  5612  5629 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-28 11:20:46.845  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-28 11:20:46.845  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-28 11:20:46.845  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 11:20:46.847  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 11:20:46.847  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.848  5612  5629 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 11:20:46.848  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:46.848  5612  5633 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 11:20:46.849  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.849  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:46.849  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:46.850  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.850  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 11:20:46.850  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.851  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.851  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.851  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
,11-28 11:20:46.851  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.853  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.854  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-28 11:20:46.854  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.854  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:46.854  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-28 11:20:46.854  5612  5629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 11:20:46.854  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:46.854  5612  5633 D BtGatt.ScanManager: Starting BLE batch scan
11-28 11:20:46.854  5612  5633 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 11:20:46.863  5612  5629 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 11:20:46.863  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:46.867  5612  5629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 11:20:46.867  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:47.355  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-28 11:20:47.355  5507  5507 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-28 11:20:47.355  5507  5507 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 11:20:49.856  5507  5553 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-28 11:20:49.857  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 11:20:49.857  5507  5553 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-28 11:20:49.857  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 11:20:49.858  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-28 11:20:49.858  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 11:20:49.858  5507  5746 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-28 11:20:49.858  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-28 11:20:49.858  5507  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-28 11:20:49.858  5507  5553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 11:20:49.859  5507  5746 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-28 11:20:49.859  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 11:20:49.859  5507  5507 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-28 11:20:49.859  5507  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f3c9f1 removed from the list
11-28 11:20:49.859  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 11:20:49.859  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-28 11:20:49.859  5507  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 11:20:49.860  5507  5507 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 11:20:49.860  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.861  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-28 11:20:49.861  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 11:20:49.862  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.863  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.863  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.863  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-28 11:20:49.863  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.865  5507  5553 D BluetoothAdapter: STATE_ON
11-28 11:20:49.866  5612  5622 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 11:20:49.867  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 11:20:49.867  5612  5633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 11:20:49.868  5507  5553 D BluetoothAdapter: STATE_ON
,11-28 11:20:49.870  5612  5623 D BtGatt.GattService: stopScan() - queue size =1
11-28 11:20:49.872  5612  5660 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 11:20:49.872  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 11:20:49.873  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.873  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:49.873  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:49.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:49.874  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-28 11:20:49.874  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.875  5612  5632 D BtGatt.AdvertiseManager: message : 1
,11-28 11:20:49.876  5612  5612 D BtGatt.ScanManager: awakened up at time 205236
11-28 11:20:49.877  5612  5632 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-28 11:20:49.887  5612  5629 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
11-28 11:20:49.888  5612  5629 D BtGatt.GattService: Client app is not null!
,11-28 11:20:49.889  5612  5623 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-28 11:20:49.889  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 11:20:49.890  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:49.890  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-28 11:20:49.890  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.891  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.891  5507  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.891  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 11:20:49.891  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 11:20:49.892  5507  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 11:20:49.893  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.895  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.895  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:49.896  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 11:20:49.896  5507  5553 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 11:20:49.896  5507  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eba99d6 removed from the list
11-28 11:20:49.896  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 11:20:49.896  5507  5553 D io.jxcore.node.ConnectivityMonitor: stop
11-28 11:20:49.896  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-28 11:20:49.896  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:49.896  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.897  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 11:20:49.897  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-28 11:20:49.897  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-28 11:20:49.897  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.897  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.897  5507  5507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 11:20:49.897  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.898  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-28 11:20:49.898  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 11:20:49.898  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.898  5507  5507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.898  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-28 11:20:49.898  5507  5507 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 11:20:49.898  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-28 11:20:49.898  5507  5507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.898  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 11:20:49.898  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.898  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 11:20:49.898  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 11:20:49.899  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-28 11:20:49.899  5507  5553 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 11:20:49.900  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-28 11:20:49.900  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.900  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.900  5507  5507 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 11:20:49.901  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-28 11:20:49.902  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-28 11:20:49.903  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,11-28 11:20:49.905  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-28 11:20:49.906  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-28 11:20:49.907  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-28 11:20:49.908  5507  5553 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-28 11:20:49.923  5612  5629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=11
,11-28 11:20:49.923  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:49.923  5612  5629 D BtGatt.GattService: current time is 205283553400
11-28 11:20:49.924  5612  5629 D BtGatt.GattService: Batch record : [122, 119, 120, -114, 116, 113, 1, -128, -94, 34, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -75, 106, -94, 85, -85, 87, 22, 80, -79, -51, 47, 35, 62, 0, 35, 97, 126, -92, 22, -56, 1, -128, -71, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 50, -35, 86, -77, -92, -11, 1, 0, -94, 47, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 70, 113, 101, 3, 2, -33, 21, -106, -79, 97, -99, 28, 6, 8, 116, 105, 110, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -72, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -70, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -68, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -67, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -61, -94, -52, 43, 94, -20, 1, -128, -99, 26, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 18, -56, -112, 117, -46, 36, -117, -107, 51, 112, 101, 3, 0, -25, 28, -105, 64, -83, 69, 0, -24, -5, 124, 62, -54, -40, 1, 0, -94, 26, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 108, 109, 101, 3, 0, -25, 27, -109, -44, 18, 12, 28, 6, 8, 116, 105, 110, 52, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -53, -6, 15, 37, 127, -32, 1, -128, -97, 25, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 12, -29, -2, -128, -84, 126, 120, -26, -108, 108, 101, 3, 1, -29, 24, -108, 120, 88, -47, 0, 122, 119, 120, -114, 116, 113, 1, -128, -84, 23, 0, 23, 2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -76, 106, 6, -59, 119, 92, -81, -59, -115, -103, 114, 35, 73, 0]
,11-28 11:20:49.924  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -75, 106, -94, 85, -85, 87, 22, 80, -79, -51, 47, 35, 62]
11-28 11:20:49.924  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 11:20:49.924  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 70, 113, 101, 3, 2, -33, 21, -106, -79, 97, -99, 6, 8, 116, 105, 110, 53, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-28 11:20:49.925  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 11:20:49.925  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-28 11:20:49.925  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 11:20:49.925  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-28 11:20:49.925  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 18, -56, -112, 117, -46, 36, -117, -107, 51, 112, 101, 3, 0, -25, 28, -105, 64, -83, 69]
11-28 11:20:49.926  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, 108, 109, 101, 3, 0, -25, 27, -109, -44, 18, 12, 6, 8, 116, 105, 110, 52, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,11-28 11:20:49.926  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 12, -29, -2, -128, -84, 126, 120, -26, -108, 108, 101, 3, 1, -29, 24, -108, 120, 88, -47]
11-28 11:20:49.926  5612  5629 D BtGatt.GattService: ScanRecord : [2, 1, 26, 19, -1, 76, 0, 12, 14, 0, -76, 106, 6, -59, 119, 92, -81, -59, -115, -103, 114, 35, 73]
,11-28 11:20:49.932  5612  5629 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 11:20:49.933  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:49.933  5612  5633 D BtGatt.ScanManager: stopping BLe Batch
,11-28 11:20:49.938  5612  5629 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-28 11:20:49.938  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 11:20:49.939  5612  5633 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 11:20:49.945  5612  5629 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 11:20:49.945  5612  5629 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 11:20:50.399  5507  5507 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 11:20:50.801   930  2872 D ConnectivityService: handlePromptUnvalidated 101
,11-28 11:20:51.913  5507  5553 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-28 11:20:52.043  5507  5748 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 11:20:52.043  5507  5748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:20:52.834  5507  5748 W !!      : call onHalfStreamCopied
,11-28 11:20:52.834  5507  5748 I testCopyDataAndClose: closing input stream
,11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing,
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 11:20:53.615  5507  5748 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 11:20:53.818   930  2860 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,11-28 11:20:57.373  5507  5553 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-28 11:20:57.459  5507  5749 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 11:20:57.459  5507  5749 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 11:20:59.120  5507  5749 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 11:21:02.863  5507  5553 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-28 11:21:02.865  5507  5750 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 11:21:02.865  5507  5750 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:21:02.866  5507  5750 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
11-28 11:21:02.866  5507  5750 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:21:02.866  5507  5750 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 11:21:02.866  5507  5750 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:21:02.866  5507  5750 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 11:21:02.867  5507  5750 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-28 11:21:02.867  5507  5750 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-28 11:21:02.867  5507  5750 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 11:21:02.867  5507  5750 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 11:21:02.867  5507  5750 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-28 11:21:02.867  5507  5750 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-28 11:21:02.869  5507  5553 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-28 11:21:02.869  5507  5553 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-28 11:21:02.870  5507  5553 I StreamCopyingThreadTest: Starting test: testRunWithException
11-28 11:21:02.872  5507  5751 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-28 11:21:02.872  5507  5751 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 11:21:02.872  5507  5751 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
11-28 11:21:02.873  5507  5751 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-28 11:21:02.873  5507  5751 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-28 11:21:02.873  5507  5751 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-28 11:21:02.873  5507  5751 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-28 11:21:02.873  5507  5751 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-28 11:21:02.877  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG UnitTest_app: 'Running unit tests'
11-28 11:21:02.877  5507  5553 I jxcore-log: 
11-28 11:21:02.877  5507  5553 I jxcore-log: *Native tests were executed*
11-28 11:21:02.877  5507  5553 I jxcore-log: 
11-28 11:21:02.877  5507  5553 I jxcore-log: Total number of executed tests:  81
11-28 11:21:02.877  5507  5553 I jxcore-log: 
11-28 11:21:02.877  5507  5553 I jxcore-log: Number of passed tests:  79
11-28 11:21:02.877  5507  5553 I jxcore-log: 
11-28 11:21:02.877  5507  5553 I jxcore-log: Number of failed tests:  0
11-28 11:21:02.877  5507  5553 I jxcore-log: 
11-28 11:21:02.877  5507  5553 I jxcore-log: Number of ignored tests:  2
11-28 11:21:02.877  5507  5553 I jxcore-log: 
11-28 11:21:02.878  5507  5553 I jxcore-log: Total duration:  33858
11-28 11:21:02.878  5507  5553 I jxcore-log: 
11-28 11:21:02.880  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-28 11:21:02.880  5507  5553 I jxcore-log: 
11-28 11:21:02.884  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 11:21:02.884  5507  5553 I jxcore-log: 
11-28 11:21:02.884  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.884  5507  5553 I jxcore-log: 
11-28 11:21:02.885  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 11:21:02.885  5507  5553 I jxcore-log: 
11-28 11:21:02.885  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.885  5507  5553 I jxcore-log: 
,11-28 11:21:02.886  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 11:21:02.886  5507  5553 I jxcore-log: 
11-28 11:21:02.887  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 11:21:02.887  5507  5553 I jxcore-log: 
,11-28 11:21:02.888  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.888  5507  5553 I jxcore-log: 
11-28 11:21:02.888  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 11:21:02.888  5507  5553 I jxcore-log: 
11-28 11:21:02.888  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 11:21:02.888  5507  5553 I jxcore-log: 
11-28 11:21:02.888  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.888  5507  5553 I jxcore-log: 
,11-28 11:21:02.889  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 11:21:02.889  5507  5553 I jxcore-log: 
11-28 11:21:02.889  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 11:21:02.889  5507  5553 I jxcore-log: 
11-28 11:21:02.889  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.889  5507  5553 I jxcore-log: 
11-28 11:21:02.889  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 11:21:02.889  5507  5553 I jxcore-log: 
11-28 11:21:02.890  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.890  5507  5553 I jxcore-log: 
,11-28 11:21:02.890  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 11:21:02.890  5507  5553 I jxcore-log: 
11-28 11:21:02.890  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.890  5507  5553 I jxcore-log: 
11-28 11:21:02.890  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 11:21:02.890  5507  5553 I jxcore-log: 
11-28 11:21:02.891  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.891  5507  5553 I jxcore-log: 
11-28 11:21:02.891  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 11:21:02.891  5507  5553 I jxcore-log: 
,11-28 11:21:02.891  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.891  5507  5553 I jxcore-log: 
,11-28 11:21:02.891  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 11:21:02.891  5507  5553 I jxcore-log: 
11-28 11:21:02.891  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.891  5507  5553 I jxcore-log: 
,11-28 11:21:02.892  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 11:21:02.892  5507  5553 I jxcore-log: 
11-28 11:21:02.892  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.892  5507  5553 I jxcore-log: 
11-28 11:21:02.892  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-28 11:21:02.892  5507  5553 I jxcore-log: 
,11-28 11:21:02.893  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-28 11:21:02.893  5507  5553 I jxcore-log: 
11-28 11:21:02.893  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-28 11:21:02.893  5507  5553 I jxcore-log: 
11-28 11:21:02.893  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 11:21:02.893  5507  5553 I jxcore-log: 
11-28 11:21:02.895  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.895  5507  5553 I jxcore-log: 
11-28 11:21:02.895  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 11:21:02.895  5507  5553 I jxcore-log: 
,11-28 11:21:02.895  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 11:21:02.895  5507  5553 I jxcore-log: 
11-28 11:21:02.896  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.896  5507  5553 I jxcore-log: 
11-28 11:21:02.896  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-28 11:21:02.896  5507  5553 I jxcore-log: 
11-28 11:21:02.896  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 11:21:02.896  5507  5553 I jxcore-log: 
,11-28 11:21:02.896  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.896  5507  5553 I jxcore-log: 
11-28 11:21:02.896  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 11:21:02.896  5507  5553 I jxcore-log: 
11-28 11:21:02.897  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 11:21:02.897  5507  5553 I jxcore-log: 
,11-28 11:21:02.901  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-28 11:21:02.901  5507  5553 I jxcore-log: 
11-28 11:21:02.902  5507  5553 I jxcore-log: 2016-11-28 16:21:02 - WARN testUtils: 'myNameCallback not set!'
11-28 11:21:02.902  5507  5553 I jxcore-log: 
,11-28 11:21:02.903  5507  5507 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-28 11:21:02.903  5507  5507 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-28 11:21:03.581   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-28 11:21:03.581   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 11:21:04.968  5507  5553 I jxcore-log: 2016-11-28 16:21:04 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-28 11:21:04.968  5507  5553 I jxcore-log: 
,11-28 11:21:04.970  5507  5553 I jxcore-log: 2016-11-28 16:21:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-28 11:21:04.970  5507  5553 I jxcore-log: 
,11-28 11:21:05.311  5507  5553 I jxcore-log: 2016-11-28 16:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-28 11:21:05.311  5507  5553 I jxcore-log: 
,11-28 11:21:05.324  5507  5553 I jxcore-log: 2016-11-28 16:21:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-28 11:21:05.324  5507  5553 I jxcore-log: 
,11-28 11:21:06.418  5507  5553 I jxcore-log: 2016-11-28 16:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-28 11:21:06.418  5507  5553 I jxcore-log: 
,11-28 11:21:06.582  5507  5553 I jxcore-log: 2016-11-28 16:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-28 11:21:06.582  5507  5553 I jxcore-log: 
,11-28 11:21:06.587  5507  5553 I jxcore-log: 2016-11-28 16:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-28 11:21:06.587  5507  5553 I jxcore-log: 
,11-28 11:21:06.600  5507  5553 I jxcore-log: 2016-11-28 16:21:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-28 11:21:06.600  5507  5553 I jxcore-log: 
,11-28 11:21:07.090  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-28 11:21:07.090  5507  5553 I jxcore-log: 
,11-28 11:21:07.134  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-28 11:21:07.134  5507  5553 I jxcore-log: 
,11-28 11:21:07.147  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-28 11:21:07.147  5507  5553 I jxcore-log: 
,11-28 11:21:07.151  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-28 11:21:07.151  5507  5553 I jxcore-log: 
,11-28 11:21:07.429  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-28 11:21:07.429  5507  5553 I jxcore-log: 
,11-28 11:21:07.558  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-28 11:21:07.558  5507  5553 I jxcore-log: 
,11-28 11:21:07.936  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-28 11:21:07.936  5507  5553 I jxcore-log: 
,11-28 11:21:07.943  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-28 11:21:07.943  5507  5553 I jxcore-log: 
,11-28 11:21:07.947  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-28 11:21:07.947  5507  5553 I jxcore-log: 
,11-28 11:21:07.951  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-28 11:21:07.951  5507  5553 I jxcore-log: 
,11-28 11:21:07.956  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-28 11:21:07.956  5507  5553 I jxcore-log: 
,11-28 11:21:07.994  5507  5553 I jxcore-log: 2016-11-28 16:21:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-28 11:21:07.994  5507  5553 I jxcore-log: 
,11-28 11:21:08.000  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-28 11:21:08.000  5507  5553 I jxcore-log: 
,11-28 11:21:08.029  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-28 11:21:08.029  5507  5553 I jxcore-log: 
,11-28 11:21:08.068  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-28 11:21:08.068  5507  5553 I jxcore-log: 
,11-28 11:21:08.075  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-28 11:21:08.075  5507  5553 I jxcore-log: 
,11-28 11:21:08.081  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-28 11:21:08.081  5507  5553 I jxcore-log: 
,11-28 11:21:08.097  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-28 11:21:08.097  5507  5553 I jxcore-log: 
,11-28 11:21:08.111  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-28 11:21:08.111  5507  5553 I jxcore-log: 
,11-28 11:21:08.118  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-28 11:21:08.118  5507  5553 I jxcore-log: 
,11-28 11:21:08.123  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-28 11:21:08.123  5507  5553 I jxcore-log: 
,11-28 11:21:08.136  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-28 11:21:08.136  5507  5553 I jxcore-log: 
,11-28 11:21:08.153  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-28 11:21:08.153  5507  5553 I jxcore-log: 
,11-28 11:21:08.168  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-28 11:21:08.168  5507  5553 I jxcore-log: 
,11-28 11:21:08.180  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-28 11:21:08.180  5507  5553 I jxcore-log: 
,11-28 11:21:08.193  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-28 11:21:08.193  5507  5553 I jxcore-log: 
,11-28 11:21:08.203  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-28 11:21:08.203  5507  5553 I jxcore-log: 
,11-28 11:21:08.217  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-28 11:21:08.217  5507  5553 I jxcore-log: 
,11-28 11:21:08.227  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-28 11:21:08.227  5507  5553 I jxcore-log: 
,11-28 11:21:08.233  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-28 11:21:08.233  5507  5553 I jxcore-log: 
,11-28 11:21:08.254  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-28 11:21:08.254  5507  5553 I jxcore-log: 
,11-28 11:21:08.261  5507  5553 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-28 11:21:08.262  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO testUtils: 'BLE multiple advertisement supported'
11-28 11:21:08.262  5507  5553 I jxcore-log: 
,11-28 11:21:08.298  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-28 11:21:08.298  5507  5553 I jxcore-log: 
,11-28 11:21:08.507  5507  5553 I jxcore-log: 2016-11-28 16:21:08 - DEBUG CoordinatedClient: 'connected to the test server'
11-28 11:21:08.507  5507  5553 I jxcore-log: 
,11-28 11:21:13.582   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:14.584   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:15.585   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:16.587   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:17.588   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:18.589   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 11:21:22.755   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:21:23.591   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:24.592   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:25.594   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:26.595   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:27.597   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:28.598   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 11:21:38.599   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:39.601   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:40.602   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:41.603   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:42.604   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:43.605   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-28 11:21:58.606   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:21:59.608   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:00.609   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:01.611   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:02.612   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:02.762   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:22:03.613   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 11:22:22.763   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:22:23.614   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:24.616   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:25.617   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:26.618   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:27.619   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:22:28.620   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 11:22:43.612   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:22:46.629   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:22:53.621   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 11:22:53.621   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 11:23:02.766   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:23:08.622   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:09.625   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:10.626   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:11.628   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:12.629   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:13.630   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 11:23:18.632   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:19.633   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:20.635   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:21.636   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:22.638   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:22.769   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:23:23.639   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 11:23:33.640   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:34.642   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:35.643   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:36.645   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:37.646   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:38.647   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-28 11:23:42.772   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:23:47.176   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:23:53.237   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:23:53.648   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:54.650   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:55.651   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:56.653   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:57.654   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:23:58.655   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 11:24:18.657   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:24:19.658   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:24:20.429   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:24:20.659   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:24:21.661   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:24:22.662   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:24:22.774   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:24:23.445   930  2872 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 11:24:23.662   540   540 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 11:24:42.775   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:24:48.663   540   540 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 11:24:48.663   540   540 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 11:24:59.981   930   940 I ActivityManager: Start proc 5762:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-28 11:25:00.019  5762  5762 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-28 11:25:00.121  5762  5774 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-28 11:25:00.208  5762  5774 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-28 11:25:00.270  5762  5774 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-28 11:25:00.285  5787  5787 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads490447212.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads490447212.dex
,11-28 11:25:00.298  5762  5762 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-28 11:25:00.318  5787  5787 I dex2oat : dex2oat took 34.248ms (threads: 2) arena alloc=180KB java alloc=37KB native alloc=1258KB free=1045KB
,11-28 11:25:00.440  5762  5762 W InstanceID/Rpc: Found 10012
,11-28 11:25:00.861   930  3313 I ActivityManager: Killing 3297:android.process.acore/u0a2 (adj 15): empty #17
,11-28 11:25:02.784   930  2860 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 11:25:08.664   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:25:09.666   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:25:10.667   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:25:11.156  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-28 11:25:11.156  5507  5553 I jxcore-log: 
,11-28 11:25:11.462  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 11:25:11.462  5507  5553 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 11:25:11.462  5507  5553 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 11:25:11.462  5507  5553 I jxcore-log: emit@events.js:82:1
11-28 11:25:11.462  5507  5553 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 11:25:11.462  5507  5553 I jxcore-log: emit@events.js:82:1''
11-28 11:25:11.462  5507  5553 I jxcore-log: 
,11-28 11:25:11.465  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - DEBUG CoordinatedClient: 'test client failed'
11-28 11:25:11.465  5507  5553 I jxcore-log: 
,11-28 11:25:11.474  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 11:25:11.474  5507  5553 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 11:25:11.474  5507  5553 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 11:25:11.474  5507  5553 I jxcore-log: emit@events.js:82:1
11-28 11:25:11.474  5507  5553 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 11:25:11.474  5507  5553 I jxcore-log: emit@events.js:82:1''
11-28 11:25:11.474  5507  5553 I jxcore-log: 
11-28 11:25:11.474  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - DEBUG CoordinatedClient: 'test client failed'
11-28 11:25:11.474  5507  5553 I jxcore-log: 
,11-28 11:25:11.478  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 11:25:11.478  5507  5553 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 11:25:11.478  5507  5553 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 11:25:11.478  5507  5553 I jxcore-log: emit@events.js:82:1
11-28 11:25:11.478  5507  5553 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 11:25:11.478  5507  5553 I jxcore-log: emit@events.js:82:1''
11-28 11:25:11.478  5507  5553 I jxcore-log: 
,11-28 11:25:11.479  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-28 11:25:11.479  5507  5553 I jxcore-log: 
,11-28 11:25:11.482  5507  5553 I jxcore-log: 2016-11-28 16:25:11 - ERROR runTests: 'websocket error
11-28 11:25:11.482  5507  5553 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-28 11:25:11.482  5507  5553 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-28 11:25:11.482  5507  5553 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-28 11:25:11.482  5507  5553 I jxcore-log: emit@events.js:82:1
11-28 11:25:11.482  5507  5553 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-28 11:25:11.482  5507  5553 I jxcore-log: emit@events.js:82:1'
11-28 11:25:11.482  5507  5553 I jxcore-log: 
,11-28 11:25:11.667   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:25:11.941  5846  5846 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-28 11:25:11.946  5846  5846 D AndroidRuntime: CheckJNI is OFF
,11-28 11:25:11.972  5846  5846 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-28 11:25:12.001  5846  5846 I Radio-JNI: register_android_hardware_Radio DONE
,11-28 11:25:12.016  5846  5846 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-28 11:25:12.027   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-28 11:25:12.028   930   943 I ActivityManager: Killing 5507:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-28 11:25:12.092   930   940 D GraphicsStats: Buffer count: 2
,11-28 11:25:12.095   930  2870 D WifiService: Client connection lost with reason: 4
,11-28 11:25:12.096   930  3488 I WindowState: WIN DEATH: Window{6614109 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-28 11:25:12.191   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-28 11:25:12.192   930   953 I art     : Starting a blocking GC Explicit
11-28 11:25:12.193   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-28 11:25:12.199   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-28 11:25:12.199   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-28 11:25:12.199   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:25:12.199   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:25:12.199   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 11:25:12.199   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-28 11:25:12.199   930   943 I ActivityManager:   Force finishing activity ActivityRecord{916e162 u0 com.test.thalitest/.MainActivity t10}
,11-28 11:25:12.205   930   940 W ActivityManager: Spurious death for ProcessRecord{5bfe3e0 0:com.test.thalitest/u0a77}, curProc for 5507: null
,11-28 11:25:12.213   930   948 W WindowManager: Attempted to add application window with unknown token Token{b3602f3 ActivityRecord{916e162 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-28 11:25:12.214   930   948 W WindowManager: Token{b3602f3 ActivityRecord{916e162 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{b3602f3 ActivityRecord{916e162 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-28 11:25:12.214   930   948 W WindowManager: view not successfully added to wm, removing view
11-28 11:25:12.214   930   948 W WindowManager: Exception when adding starting window
11-28 11:25:12.214   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{fae765b V.E...... R.....ID 0,0-0,0} not attached to window manager
11-28 11:25:12.214   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-28 11:25:12.214   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-28 11:25:12.214   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-28 11:25:12.214   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-28 11:25:12.214   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-28 11:25:12.214   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:25:12.214   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:25:12.214   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 11:25:12.214   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-28 11:25:12.298   930   953 I art     : Explicit concurrent mark sweep GC freed 109355(7MB) AllocSpace objects, 79(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.736ms total 105.382ms
,11-28 11:25:12.317   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-28 11:25:12.320  5846  5846 I art     : System.exit called, status: 0
,11-28 11:25:12.320  5846  5846 I AndroidRuntime: VM exiting with result code 0.
,11-28 11:25:12.336   930   953 I ActivityManager: Start proc 5857:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-28 11:25:12.336   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-28 11:25:12.340   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-28 11:25:12.343  5612  5612 D BluetoothMapAppObserver: onReceive
11-28 11:25:12.343  5612  5612 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-28 11:25:12.350  3558  3558 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-28 11:25:12.359  4008  4089 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-28 11:25:12.364   930   943 I ActivityManager: Start proc 5870:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,11-28 11:25:12.373  3558  5867 I Keyboard.Facilitator.DecoderInitializer: run()
,11-28 11:25:12.373   930  2809 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-28 11:25:12.378  3558  5867 I Decoder : createOrResetDecoder
11-28 11:25:12.379  3659  3659 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-28 11:25:12.415   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-28 11:25:12.430    27    27 W kworker/1:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 11:25:12.427  3473  3473 I ConfigService: onCreate
11-28 11:25:12.428  5870  5870 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,11-28 11:25:12.434    27    27 W kworker/1:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 11:25:12.444  3685  3831 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-28 11:25:12.461   930  3896 I ActivityManager: Start proc 5887:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-28 11:25:12.461  3685  3831 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-28 11:25:12.461  3685  3831 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3685
11-28 11:25:12.461  3685  3831 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:25:12.461  3685  3831 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 11:25:12.464   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-28 11:25:12.450    27    27 W kworker/1:1: type=1400 audit(0.0:129): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-28 11:25:12.468   930  5893 E DropBoxManagerService: Can't write: system_app_crash
11-28 11:25:12.468   930  5893 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 11:25:12.468   930  5893 E DropBoxManagerService: 	... 5 more
11-28 11:25:12.470  3685  3831 I Process : Sending signal. PID: 3685 SIG: 9
11-28 11:25:12.477  3558  5867 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-28 11:25:12.494   930  3025 I ActivityManager: Killing 5390:com.google.android.partnersetup/u0a18 (adj 15): empty #17
,11-28 11:25:12.535  3558  5867 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-28 11:25:12.537  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-28 11:25:12.537  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-28 11:25:12.544  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-28 11:25:12.545  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-28 11:25:12.545  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-28 11:25:12.545  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-28 11:25:12.546  3558  5867 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-28 11:25:12.546  3558  5867 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-28 11:25:12.546  3558  5867 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-28 11:25:12.547  3558  5867 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-28 11:25:12.547  3558  5867 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-28 11:25:12.547  3558  5867 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-28 11:25:12.585  5870  5870 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,11-28 11:25:12.634  5870  5908 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-28 11:25:12.668   930  3313 D GraphicsStats: Buffer count: 1
,11-28 11:25:12.668   930  4620 I WindowState: WIN DEATH: Window{20455ca u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,11-28 11:25:12.669   540   540 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 11:25:12.673   930  3027 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3685) has died
,11-28 11:25:12.674   930  3027 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-28 11:25:12.675   930  3027 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-28 11:25:12.692   930   943 I ActivityManager: Start proc 5910:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-28 11:25:12.733  5910  5910 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:25:12.733  5910  5910 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:25:12.734  5910  5910 D AndroidRuntime: Shutting down VM
11-28 11:25:12.741  5910  5910 E AndroidRuntime: FATAL EXCEPTION: main
11-28 11:25:12.741  5910  5910 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5910
11-28 11:25:12.741  5910 , 5910 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-28 11:25:12.741  5910  5910 E AndroidRuntime: 	... 10 more
1,1-28 11:25:12.743   930  3027 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-28 11:25:12.744  5910  5910 I Process : Sending signal. PID: 5910 SIG: 9
11-28 11:25:12.759   930   940 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5910) has died
11-28 11:25:12.761   930   940 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
11-28 11:25:12.775   930   943 I ActivityManager: Start proc 5923:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-28 11:25:12.823  5923  5923 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 11:25:12.823  5923  5923 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-28 11:25:12.824  5923  5923 D AndroidRuntime: Shutting down VM

```
