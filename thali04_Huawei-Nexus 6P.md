#### Test 850469116a90ff6_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-20 01:36:22.127   597   597 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-20 01:36:22.128   597   597 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-20 01:36:22.609  5741  5741 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-20 01:36:22.615  5741  5741 D AndroidRuntime: CheckJNI is OFF
09-20 01:36:22.643  5741  5741 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-20 01:36:22.679  5741  5741 I Radio-JNI: register_android_hardware_Radio DONE
09-20 01:36:22.696  5741  5741 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-20 01:36:22.706   926  3755 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-20 01:36:22.769   926  3755 I ActivityManager: Start proc 5750:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-20 01:36:22.775  5741  5741 D AndroidRuntime: Shutting down VM
,09-20 01:36:23.113   926  3412 I WindowManager: Screenshot max retries 4 of Token{7aee6b ActivityRecord{b26efba u0 com.test.thalitest/.MainActivity t4}} appWin=Window{187bc12 u0 Starting com.test.thalitest} drawState=4
,09-20 01:36:23.176  5750  5750 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-20 01:36:23.208  5750  5750 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-20 01:36:23.279  5750  5750 I LibraryLoader: Time to load native libraries: 66 ms (timestamps 752-818)
09-20 01:36:23.280  5750  5750 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-20 01:36:23.331  5750  5750 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f565864}
,09-20 01:36:23.332  5750  5750 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-20 01:36:23.332  5750  5750 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-20 01:36:23.338  5750  5750 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-20 01:36:23.340  5750  5750 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-20 01:36:23.378  5750  5750 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-20 01:36:23.394  5750  5750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-20 01:36:23.394  5750  5750 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-20 01:36:23.395  5750  5750 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-20 01:36:23.395  5750  5750 I Adreno  : Build Date                       : 12/06/15
09-20 01:36:23.395  5750  5750 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-20 01:36:23.395  5750  5750 I Adreno  : Local Branch                     : mybranch17112971
09-20 01:36:23.395  5750  5750 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-20 01:36:23.395  5750  5750 I Adreno  : Remote Branch                    : NONE
09-20 01:36:23.395  5750  5750 I Adreno  : Reconstruct Branch               : NOTHING
,09-20 01:36:23.446   926   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ae81d1:true
,09-20 01:36:23.478   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[31990]" dev="sockfs" ino=31990 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-20 01:36:23.478   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31990]" dev="sockfs" ino=31990 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-20 01:36:23.494  5750  5750 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-20 01:36:23.503  5750  5750 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-20 01:36:23.521   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32871]" dev="sockfs" ino=32871 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-20 01:36:23.521   408   408 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32871]" dev="sockfs" ino=32871 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-20 01:36:23.524  3148  3148 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31994]" dev="sockfs" ino=31994 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-20 01:36:23.524  3148  3148 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31994]" dev="sockfs" ino=31994 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-20 01:36:23.532  5750  5774 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-20 01:36:23.560  5750  5787 I OpenGLRenderer: Initialized EGL, version 1.4
,09-20 01:36:23.622   926   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +507ms (total +880ms)
,09-20 01:36:23.645  5750  5750 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5750
,09-20 01:36:23.732  5750  5750 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-20 01:36:23.778   926  2949 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-20 01:36:23.859  5750  5790 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -563345104
,09-20 01:36:23.864  5750  5790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-20 01:36:23.864  5750  5790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-20 01:36:23.864  5750  5790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-20 01:36:23.864  5750  5790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-20 01:36:23.864  5750  5790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-20 01:36:23.864  5750  5790 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8754045 added. We now have 1 listener(s)
,09-20 01:36:23.866  5750  5790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-20 01:36:23.866  5750  5790 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-20 01:36:23.866  5750  5790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-20 01:36:23.867  5750  5790 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-20 01:36:23.869  5750  5790 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece44a8 added. We now have 1 listener(s)
09-20 01:36:23.869  5750  5790 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-20 01:36:23.873   926  2959 D WifiService: New client listening to asynchronous messages
09-20 01:36:23.873  5750  5790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-20 01:36:23.873  5750  5790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-20 01:36:23.874  5750  5790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-20 01:36:23.874  5750  5790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-20 01:36:23.874  5750  5790 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-20 01:36:23.876  5750  5790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-20 01:36:23.876  5750  5790 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-20 01:36:23.881  5750  5790 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 01:36:23.881  5750  5790 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-20 01:36:23.881  5750  5790 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-20 01:36:23.881  5750  5790 D io.jxcore.node.ConnectivityMonitor: start: OK
09-20 01:36:23.882  5750  5790 I io.jxcore.node.LifeCycleMonitor: start: OK
09-20 01:36:23.884  5750  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 01:36:23.886  5750  5750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-20 01:36:23.896  5750  5750 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-20 01:36:24.169  5750  5796 W jxcore-log: Initializing JXcore engine
,09-20 01:36:24.169  5750  5796 W jxcore-log: JXcore engine is ready
,09-20 01:36:24.188  5796  5796 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10672 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-20 01:36:24.191  5796  5796 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13342]" dev="sockfs" ino=13342 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-20 01:36:24.191  5796  5796 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=6259 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-20 01:36:24.191  5796  5796 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33893]" dev="sockfs" ino=33893 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-20 01:36:24.201  5750  5796 W jxcore-log: Starting JXcore engine
,09-20 01:36:24.250  5750  5796 W jxcore-log: Platform android
09-20 01:36:24.250  5750  5796 W jxcore-log: 
09-20 01:36:24.250  5750  5796 W jxcore-log: Process ARCH arm
09-20 01:36:24.250  5750  5796 W jxcore-log: 
,09-20 01:36:24.354  5750  5796 I jxcore-log: JXcore Cordova bridge is ready!
09-20 01:36:24.354  5750  5796 I jxcore-log: 
,09-20 01:36:24.354  5750  5796 W jxcore-log: JXcore engine is started
,09-20 01:36:24.360  5750  5790 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-20 01:36:24.363  5750  5750 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-20 01:36:30.924  5750  5796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-20 01:36:30.924  5750  5796 I jxcore-log: 
,09-20 01:36:30.925  5750  5796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-20 01:36:30.925  5750  5796 I jxcore-log: 
,09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-20 01:36:30.929  5750  5796 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-20 01:36:30.931  5750  5796 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-20 01:36:30.932  5750  5796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-20 01:36:30.932  5750  5796 I jxcore-log: 
,09-20 01:36:30.934  5750  5796 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-20 01:36:30.934  5750  5796 I jxcore-log: 
,09-20 01:36:31.291  5750  5796 D executeNativeTests: Running unit tests
,09-20 01:36:31.304  5750  5796 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 1
,09-20 01:36:31.304  5750  5796 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 1
09-20 01:36:31.304  5750  5796 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-20 01:36:31.305  5750  5796 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-20 01:36:31.305  5750  5796 D com.test.thalitest.ThaliTestRunner: Total duration: 2 ms
09-20 01:36:31.306  5750  5796 I jxcore-log: *Native tests were executed*
09-20 01:36:31.306  5750  5796 I jxcore-log: 
09-20 01:36:31.306  5750  5796 I jxcore-log: Total number of executed tests:  1
09-20 01:36:31.306  5750  5796 I jxcore-log: 
,09-20 01:36:31.306  5750  5796 I jxcore-log: Number of passed tests:  1
09-20 01:36:31.306  5750  5796 I jxcore-log: 
09-20 01:36:31.306  5750  5796 I jxcore-log: Number of failed tests:  0
09-20 01:36:31.306  5750  5796 I jxcore-log: 
09-20 01:36:31.307  5750  5796 I jxcore-log: Number of ignored tests:  0
09-20 01:36:31.307  5750  5796 I jxcore-log: 
09-20 01:36:31.307  5750  5796 I jxcore-log: Total duration:  2
09-20 01:36:31.307  5750  5796 I jxcore-log: 
09-20 01:36:31.307  5750  5796 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-20 01:36:31.307  5750  5796 I jxcore-log: 
09-20 01:36:31.309  5750  5796 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-20 01:36:31.309  5750  5796 I jxcore-log: 
,09-20 01:36:31.330  5750  5750 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-20 01:36:31.781  5797  5797 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-20 01:36:31.786  5797  5797 D AndroidRuntime: CheckJNI is OFF
,09-20 01:36:31.817  5797  5797 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-20 01:36:31.852  5797  5797 I Radio-JNI: register_android_hardware_Radio DONE
,09-20 01:36:31.868  5797  5797 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-20 01:36:31.890   926   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-20 01:36:31.891   926   940 I ActivityManager: Killing 5750:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-20 01:36:31.968   926  3776 D GraphicsStats: Buffer count: 2
,09-20 01:36:31.969   926  2959 D WifiService: Client connection lost with reason: 4
,09-20 01:36:31.971   926  3800 I WindowState: WIN DEATH: Window{6028141 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-20 01:36:31.971   926  2939 W InputDispatcher: channel '6028141 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-20 01:36:31.971   926  2939 E InputDispatcher: channel '6028141 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-20 01:36:31.971   926  3800 W InputDispatcher: Attempted to unregister already unregistered input channel '6028141 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,09-20 01:36:31.991   926   935 I art     : Background partial concurrent mark sweep GC freed 71744(5MB) AllocSpace objects, 33(1008KB) LOS objects, 33% free, 29MB/43MB, paused 3.448ms total 118.057ms
,09-20 01:36:32.010   926   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-20 01:36:32.011   926   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-20 01:36:32.011   926   950 I art     : Starting a blocking GC Explicit
,09-20 01:36:32.012   926   940 E ActivityManager: Failure starting process com.test.thalitest
09-20 01:36:32.012   926   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-20 01:36:32.012   926   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 01:36:32.012   926   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-20 01:36:32.012   926   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 01:36:32.012   926   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-20 01:36:32.013   926   940 I ActivityManager:   Force finishing activity ActivityRecord{b26efba u0 com.test.thalitest/.MainActivity t4}
,09-20 01:36:32.023   926  3797 W ActivityManager: Spurious death for ProcessRecord{1cd3cb1 0:com.test.thalitest/u0a77}, curProc for 5750: null
,09-20 01:36:32.023   926   945 W WindowManager: Attempted to add application window with unknown token Token{7aee6b ActivityRecord{b26efba u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
09-20 01:36:32.024   926   945 W WindowManager: Token{7aee6b ActivityRecord{b26efba u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{7aee6b ActivityRecord{b26efba u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-20 01:36:32.024   926   945 W WindowManager: view not successfully added to wm, removing view
09-20 01:36:32.024   926   945 W WindowManager: Exception when adding starting window
09-20 01:36:32.024   926   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{18e7517 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-20 01:36:32.024   926   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-20 01:36:32.024   926   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-20 01:36:32.024   926   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-20 01:36:32.024   926   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-20 01:36:32.024   926   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-20 01:36:32.024   926   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 01:36:32.024   926   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-20 01:36:32.024   926   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 01:36:32.024   926   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-20 01:36:32.082   926   950 I art     : Explicit concurrent mark sweep GC freed 6263(445KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.363ms total 70.896ms
,09-20 01:36:32.100   926   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-20 01:36:32.103  5797  5797 I art     : System.exit called, status: 0
09-20 01:36:32.103  5797  5797 I AndroidRuntime: VM exiting with result code 0.
,09-20 01:36:32.108   926   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-20 01:36:32.119   926   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-20 01:36:32.123  3661  3661 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-20 01:36:32.123  4588  4588 D BluetoothMapAppObserver: onReceive
09-20 01:36:32.123  4588  4588 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-20 01:36:32.128   597   597 I ServiceManager: Waiting for service AtCmdFwd...
,09-20 01:36:32.130   926  2940 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-20 01:36:32.131  4101  4182 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-20 01:36:32.161  3661  5808 I Keyboard.Facilitator.DecoderInitializer: run()
,09-20 01:36:32.167  3397  5810 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-20 01:36:32.178  3788  3788 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-20 01:36:32.185   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-20 01:36:32.191  3578  3578 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-20 01:36:32.191  3578  3578 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-20 01:36:32.201  3661  5808 I Decoder : createOrResetDecoder
,09-20 01:36:32.224  3578  3578 I ConfigService: onCreate
,09-20 01:36:32.224  3961  5814 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-20 01:36:32.225  3961  5814 D AccountUtils: Clearing selected account for com.test.thalitest
,09-20 01:36:32.234    29    29 W kworker/3:1: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-20 01:36:32.238    29    29 W kworker/3:1: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-20 01:36:32.247  3661  5808 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-20 01:36:32.264   926   937 I ActivityManager: Start proc 5819:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-20 01:36:32.266  3807  3913 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-20 01:36:32.266  3807  3913 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3807
09-20 01:36:32.266  3807  3913 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-20 01:36:32.266  3807  3913 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-20 01:36:32.261    29    29 W kworker/3:1: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-20 01:36:32.270   926  3797 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-20 01:36:32.271   926  5828 E DropBoxManagerService: Can't write: system_app_crash
09-20 01:36:32.271   926  5828 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-20 01:36:32.271   926  5828 E DropBoxManagerService: 	... 5 more
,09-20 01:36:32.271  3397  3423 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjE256DE94D) - 
,09-20 01:36:32.275  3807  3913 I Process : Sending signal. PID: 3807 SIG: 9
,09-20 01:36:32.285  3961  5814 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-20 01:36:32.315  3961  5814 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-20 01:36:32.315  3961  5814 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-20 01:36:32.315  3961  5814 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-20 01:36:32.316  3961  5814 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-20 01:36:32.335  3961  3961 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-20 01:36:32.335  3961  3961 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-20 01:36:32.348  3961  3961 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-20 01:36:32.349  3961  3961 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-20 01:36:32.378  3397  3423 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-20 01:36:32.378  3397  3423 E AndroidRuntime: Process: android.process.acore, PID: 3397
09-20 01:36:32.378  3397  3423 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-20 01:36:32.378  3397  3423 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-20 01:36:32.385   381   381 E lowmemorykiller: Error writing /proc/3807/oom_score_adj; errno=22
,09-20 01:36:32.386   926  3755 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
09-20 01:36:32.386   926  3755 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-20 01:36:32.386   926  3755 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-20 01:36:32.386   926  3755 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-20 01:36:32.409   926  3148 D GraphicsStats: Buffer count: 1
09-20 01:36:32.409   926  3150 I WindowState: WIN DEATH: Window{2216aae u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-20 01:36:32.411  3397  3423 I Process : Sending signal. PID: 3397 SIG: 9
,09-20 01:36:32.413   926  3755 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-20 01:36:32.425   926  3755 I ActivityManager: Start proc 5841:com.google.android.googlequicksearchbox/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,09-20 01:36:32.428   381   381 E lowmemorykiller: Error writing /proc/3397/oom_score_adj; errno=22
,09-20 01:36:32.429   926  3797 W ActivityManager: Spurious death for ProcessRecord{7b3c298 5841:com.google.android.googlequicksearchbox/u0a29}, curProc for 3807: null
,09-20 01:36:32.430  4946  5836 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-20 01:36:32.457   381   381 E lowmemorykiller: Error writing /proc/3397/oom_score_adj; errno=22
,09-20 01:36:32.460   381   381 E lowmemorykiller: Error writing /proc/3397/oom_score_adj; errno=22
,09-20 01:36:32.496  3961  5835 W BaseAppContext: Using Auth Proxy for data requests.
,09-20 01:36:32.505  3961  5835 W BaseAppContext: Using Auth Proxy for data requests.
,09-20 01:36:32.531  3961  3961 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-20 01:36:32.545  3961  5855 I GMPM-SVC: App measurement is starting up
,09-20 01:36:32.555  3961  5855 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-20 01:36:32.564  3961  5855 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-20 01:36:32.653   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
