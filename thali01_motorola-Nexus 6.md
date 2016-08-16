#### Test 80598852b8a90be_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 18:16:46.720  1524  1524 I ConfigService: onDestroy
,08-16 18:16:47.381  3857  3857 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 18:16:47.386  3857  3857 D AndroidRuntime: CheckJNI is OFF
08-16 18:16:47.429  3857  3857 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 18:16:47.479  3857  3857 I Radio-JNI: register_android_hardware_Radio DONE
08-16 18:16:47.501  3857  3857 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 18:16:47.507   872  1953 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 18:16:47.564   872  1953 I ActivityManager: Start proc 3867:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 18:16:47.567  3857  3857 D AndroidRuntime: Shutting down VM
08-16 18:16:47.684  3867  3867 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 18:16:47.708  3867  3867 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 18:16:47.716  3867  3867 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6119-6122)
08-16 18:16:47.716  3867  3867 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:16:47.754  3867  3867 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c3831df}
08-16 18:16:47.754  3867  3867 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 18:16:47.755  3867  3867 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 18:16:47.763  3867  3867 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 18:16:47.765  3867  3867 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 18:16:47.781  3867  3867 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 18:16:47.796  3867  3867 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 18:16:47.796  3867  3867 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 18:16:47.796  3867  3867 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 18:16:47.796  3867  3867 I Adreno  : Build Date                       : 10/20/15
08-16 18:16:47.796  3867  3867 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 18:16:47.796  3867  3867 I Adreno  : Local Branch                     : M14
08-16 18:16:47.796  3867  3867 I Adreno  : Remote Branch                    : 
08-16 18:16:47.796  3867  3867 I Adreno  : Remote Branch                    : 
08-16 18:16:47.796  3867  3867 I Adreno  : Reconstruct Branch               : 
,08-16 18:16:47.874   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53120e3:true
,08-16 18:16:47.921  3867  3867 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 18:16:47.935  3867  3867 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 18:16:47.996  3867  3904 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 18:16:48.031  3867  3891 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 18:16:48.073  3867  3904 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 18:16:48.137  1847  1847 I Keyboard.Facilitator: onFinishInput()
,08-16 18:16:48.208   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +581ms (total +665ms)
,08-16 18:16:48.212  3867  3867 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3867
,08-16 18:16:48.277  3867  3867 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 18:16:48.422  3867  3906 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681131216
,08-16 18:16:48.430  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 18:16:48.430  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 18:16:48.430  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 18:16:48.430  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 18:16:48.430  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 18:16:48.431  3867  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18863a2 added. We now have 1 listener(s)
,08-16 18:16:48.435  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 18:16:48.436  3867  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 18:16:48.437  3867  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:16:48.437  3867  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 18:16:48.441  3867  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb79169 added. We now have 1 listener(s)
08-16 18:16:48.442  3867  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:16:48.446  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:16:48.446  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 18:16:48.447  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
,08-16 18:16:48.447  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-16 18:16:48.447   872  1307 D WifiService: New client listening to asynchronous messages
08-16 18:16:48.447  3867  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 18:16:48.451  3867  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:16:48.451  3867  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-16 18:16:48.457  3867  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:16:48.457  3867  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:16:48.457  3867  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 18:16:48.457  3867  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:16:48.458  3867  3906 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 18:16:48.459  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:16:48.461  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:16:48.491  3867  3867 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 18:16:49.120  3867  3913 W jxcore-log: Initializing JXcore engine
08-16 18:16:49.120  3867  3913 W jxcore-log: JXcore engine is ready
,08-16 18:16:49.158  3913  3913 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8993 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 18:16:49.158  3913  3913 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10757]" dev="sockfs" ino=10757 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-16 18:16:49.158  3913  3913 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-16 18:16:49.158  3913  3913 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24450]" dev="sockfs" ino=24450 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 18:16:49.170  3867  3913 W jxcore-log: Starting JXcore engine
,08-16 18:16:49.250  3867  3913 W jxcore-log: Platform android
08-16 18:16:49.250  3867  3913 W jxcore-log: 
,08-16 18:16:49.250  3867  3913 W jxcore-log: Process ARCH arm
08-16 18:16:49.250  3867  3913 W jxcore-log: 
,08-16 18:16:49.420  3867  3913 I jxcore-log: JXcore Cordova bridge is ready!
08-16 18:16:49.420  3867  3913 I jxcore-log: 
,08-16 18:16:49.420  3867  3913 W jxcore-log: JXcore engine is started,
,08-16 18:16:49.431  3867  3906 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 18:16:49.435  3867  3867 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 18:16:52.535  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 18:16:52.546  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 18:16:52.561  3783  3914 V GoogleAuthProtoRequest: [319] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 18:16:52.590  1524  3479 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 18:16:52.590  1524  3479 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 18:16:52.590  1524  3479 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 18:16:52.590  1524  3479 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 18:16:52.617  3783  3914 W ExperimentUpdateService: [319] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: [319] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 18:16:52.618  3783  3914 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 18:16:59.321  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 18:16:59.321  3867  3913 I jxcore-log: 
,08-16 18:16:59.323  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 18:16:59.323  3867  3913 I jxcore-log: 
,08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:16:59.335  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:16:59.341  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:16:59.343  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 18:16:59.343  3867  3913 I jxcore-log: 
,08-16 18:16:59.346  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 18:16:59.346  3867  3913 I jxcore-log: 
,08-16 18:16:59.670  3867  3913 D ExecuteNativeTests: Running unit tests
,08-16 18:16:59.728  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:16:59.728  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 added. We now have 2 listener(s)
08-16 18:16:59.729  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 18:16:59.729  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:16:59.730  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 18:16:59.730  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:16:59.730  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 added. We now have 2 listener(s)
08-16 18:16:59.730  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:16:59.731  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:16:59.734  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:16:59.746  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:16:59.751  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:16:59.751  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:16:59.754  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 18:16:59.754  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-16 18:16:59.754  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 18:16:59.755  3867  3913 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 18:16:59.756  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:16:59.756  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:16:59.756  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:16:59.756  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:16:59.756  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:16:59.757  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:16:59.757  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:16:59.757  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:16:59.757  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.758  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:16:59.758  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:16:59.758  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 removed from the list
08-16 18:16:59.758  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.758  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 removed from the list
08-16 18:16:59.758  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:16:59.758  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:16:59.759  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.760  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.761  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.762  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:16:59.762  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:16:59.763  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.763  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.764  3867  3913 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 18:16:59.765  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:16:59.765  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:16:59.765  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:16:59.765  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:16:59.765  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:16:59.765  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:16:59.766  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
,08-16 18:16:59.766  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.766  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.770  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:16:59.770  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:16:59.770  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.770  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.770  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.770  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.771  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:16:59.771  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:16:59.771  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.772  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:16:59.776  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:16:59.777  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:16:59.778  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:16:59.778  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:16:59.778  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:16:59.778  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:16:59.778  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:16:59.778  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.778  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.779  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:16:59.779  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.779  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.779  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:16:59.779  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.779  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.779  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.779  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.781  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:16:59.781  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:16:59.781  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.781  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.782  3867  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:16:59.784  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:16:59.792  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:16:59.796  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:59.796  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:16:59.797  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:16:59.797  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:16:59.797  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:16:59.797  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:16:59.798  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:16:59.807  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:16:59.809  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 18:16:59.809  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 18:16:59.813  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:16:59.818  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:16:59.823  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 18:16:59.824  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 18:16:59.830  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 18:16:59.835  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 18:16:59.836  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 18:16:59.837  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:16:59.838  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:16:59.839  3867  3913 D BluetoothAdapter: STATE_ON
08-16 18:16:59.848  2700  2891 D BtGatt.GattService: registerClient() - UUID=a239c3b6-f4da-444d-8be9-6cfb4a7a4506
08-16 18:16:59.849  2700  2752 D BtGatt.GattService: onClientRegistered() - UUID=a239c3b6-f4da-444d-8be9-6cfb4a7a4506, clientIf=5
08-16 18:16:59.850  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 18:16:59.852  2700  2711 D BtGatt.GattService: start scan with filters
08-16 18:16:59.858  2700  2756 D BtGatt.ScanManager: handling starting scan
08-16 18:16:59.858  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:16:59.859  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:16:59.859  2700  2756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
08-16 18:16:59.859  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:16:59.860  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:16:59.866  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:16:59.867  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:16:59.868  2700  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 18:16:59.868  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:16:59.868  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 18:16:59.870  2700  2756 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 18:16:59.873  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:16:59.880  3867  3913 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:16:59.884  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:16:59.884  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:16:59.885  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:16:59.885  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 18:16:59.885  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.885  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:16:59.885  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:16:59.885  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:16:59.885  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 18:16:59.885  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:16:59.886  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:16:59.886  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:16:59.890  3867  3913 D BluetoothAdapter: STATE_ON
08-16 18:16:59.891  2700  2891 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:16:59.891  2700  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 18:16:59.892  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 18:16:59.892  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:16:59.892  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 18:16:59.892  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 18:16:59.892  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 18:16:59.893  2700  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 18:16:59.893  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:16:59.893  2700  2756 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:16:59.893  2700  2756 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 18:16:59.894  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:16:59.894  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:16:59.894  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:16:59.895  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:16:59.895  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:16:59.897  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:16:59.897  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:16:59.897  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:16:59.897  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:16:59.897  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.898  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:16:59.898  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:16:59.898  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.898  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.898  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:16:59.898  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:16:59.898  3867  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 18:16:59.905  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:16:59.912  2700  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 18:16:59.912  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:16:59.914  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:16:59.917  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:16:59.917  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:16:59.917  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-16 18:16:59.917  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:16:59.917  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 18:16:59.918  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:16:59.918  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:16:59.920  2700  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 18:16:59.920  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:16:59.922  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 18:16:59.922  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-16 18:16:59.922  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:16:59.926  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:16:59.926  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:16:59.927  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 18:16:59.927  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:16:59.932  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:16:59.932  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:16:59.932  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:16:59.933  3867  3913 D BluetoothAdapter: STATE_ON
,08-16 18:16:59.935  2700  2712 D BtGatt.GattService: registerClient() - UUID=71cb5456-f602-4c8c-b533-089a9a456e93
,08-16 18:16:59.936  2700  2752 D BtGatt.GattService: onClientRegistered() - UUID=71cb5456-f602-4c8c-b533-089a9a456e93, clientIf=5
08-16 18:16:59.936  3867  3878 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 18:16:59.937  2700  2891 D BtGatt.GattService: start scan with filters
,08-16 18:16:59.937  2700  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 18:16:59.937  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-16 18:16:59.938  2700  2756 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:16:59.940  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:16:59.940  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:16:59.940  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:16:59.940  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:16:59.943  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:16:59.943  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 18:16:59.943  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:16:59.945  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:16:59.948  3867  3913 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 18:16:59.952  2700  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 18:16:59.952  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:16:59.953  2700  2756 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 18:16:59.953  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:16:59.953  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:16:59.953  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:16:59.953  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:16:59.953  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.954  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:16:59.954  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:16:59.954  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:16:59.954  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 18:16:59.954  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:16:59.954  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:16:59.954  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:16:59.955  3867  3913 D BluetoothAdapter: STATE_ON
08-16 18:16:59.956  2700  2711 D BtGatt.GattService: stopScan() - queue size =0,
08-16 18:16:59.957  2700  2712 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 18:16:59.957  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:16:59.957  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 18:16:59.958  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:16:59.958  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:16:59.958  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 18:16:59.959  2700  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 18:16:59.960  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:16:59.961  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:16:59.961  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 18:16:59.961  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:16:59.961  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:16:59.962  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:16:59.962  2700  2756 D BtGatt.ScanManager: handling starting scan
,08-16 18:16:59.963  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:16:59.963  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:16:59.964  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:16:59.965  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:16:59.965  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:16:59.965  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:16:59.965  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:16:59.966  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.966  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:16:59.966  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:16:59.966  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:16:59.967  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:16:59.967  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:16:59.969  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:16:59.969  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:16:59.969  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:16:59.969  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:16:59.969  2700  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 18:16:59.969  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:16:59.970  2700  2756 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 18:16:59.970  3867  3913 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 18:16:59.972  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:16:59.979  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:16:59.982  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:16:59.982  2700  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 18:16:59.982  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:16:59.982  2700  2756 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:16:59.982  2700  2756 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 18:16:59.982  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:16:59.983  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:16:59.983  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 18:16:59.983  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:16:59.983  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:16:59.983  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:16:59.987  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:16:59.989  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 18:16:59.989  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:16:59.995  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:16:59.996  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:16:59.997  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 18:16:59.998  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:17:00.002  2700  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 18:17:00.003  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.004  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:17:00.004  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:17:00.004  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:17:00.005  3867  3913 D BluetoothAdapter: STATE_ON,
,08-16 18:17:00.008  2700  2711 D BtGatt.GattService: registerClient() - UUID=8e66d301-1095-46ed-9fd7-4fbf21c4cb15
08-16 18:17:00.009  2700  2752 D BtGatt.GattService: onClientRegistered() - UUID=8e66d301-1095-46ed-9fd7-4fbf21c4cb15, clientIf=5
08-16 18:17:00.009  2700  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 18:17:00.009  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.010  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 18:17:00.010  2700  2891 D BtGatt.GattService: start scan with filters
,08-16 18:17:00.016  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:17:00.016  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 18:17:00.016  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:17:00.016  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:17:00.019  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:17:00.019  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:17:00.020  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:17:00.021  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:17:00.022  2700  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 18:17:00.023  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.023  2700  2756 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:17:00.025  3867  3913 I io.jxcore.node.ConnectionHelper: start: OK
08-16 18:17:00.025  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:17:00.025  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:17:00.025  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.025  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 18:17:00.025  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.025  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:17:00.025  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:17:00.026  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:17:00.026  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:17:00.026  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:17:00.026  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 18:17:00.026  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 18:17:00.027  3867  3913 D BluetoothAdapter: STATE_ON
,08-16 18:17:00.028  2700  2712 D BtGatt.GattService: stopScan() - queue size =0
08-16 18:17:00.028  2700  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 18:17:00.029  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:17:00.029  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:17:00.030  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:17:00.030  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 18:17:00.030  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 18:17:00.031  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:00.031  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:17:00.031  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:17:00.031  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:17:00.032  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:17:00.033  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:00.033  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:00.033  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:17:00.034  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.034  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:17:00.034  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.034  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.034  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.034  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.035  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:17:00.035  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.035  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.035  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.035  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.035  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.035  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.036  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.038  2700  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 18:17:00.038  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.038  2700  2756 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 18:17:00.044  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.044  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.044  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.044  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.045  3867  3913 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 18:17:00.046  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:17:00.046  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.046  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.047  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:00.047  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.047  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.047  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.047  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:00.047  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.047  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:17:00.047  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.048  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.048  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.048  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.050  2700  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 18:17:00.050  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:17:00.051  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.051  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.051  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.051  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.052  2700  2756 D BtGatt.ScanManager: handling starting scan
08-16 18:17:00.053  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 18:17:00.054  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.054  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.054  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:00.055  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.055  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.055  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.055  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.055  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-16 18:17:00.055  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.055  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.055  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:00.055  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.056  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:00.056  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.057  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.057  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.057  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:00.057  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.058  3867  3913 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 18:17:00.058  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.059  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:17:00.059  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:00.059  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:00.059  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.059  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.060  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
,08-16 18:17:00.060  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.060  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.060  2700  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 18:17:00.060  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.060  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:17:00.060  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:00.060  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.060  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.060  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.060  2700  2756 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 18:17:00.061  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.062  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.062  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:00.062  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.063  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 18:17:00.063  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:17:00.063  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:17:00.063  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:00.064  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:00.064  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.064  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.064  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
,08-16 18:17:00.064  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.064  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.064  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:17:00.064  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:00.065  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.065  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:00.065  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.066  2700  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 18:17:00.067  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.067  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.067  2700  2756 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:17:00.067  2700  2756 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 18:17:00.067  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:17:00.067  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.067  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.068  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 18:17:00.069  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 18:17:00.070  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:17:00.071  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:17:00.071  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 18:17:00.071  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 18:17:00.072  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:17:00.072  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.072  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:00.072  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.072  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.072  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.072  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.073  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.073  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.073  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.073  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.073  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 18:17:00.073  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.073  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.075  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.075  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.075  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:00.075  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.076  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 18:17:00.076  3867  3913 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 18:17:00.076  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 18:17:00.080  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:17:00.081  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 18:17:00.081  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 18:17:00.082  2700  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 18:17:00.082  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 18:17:00.082  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 18:17:00.083  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 18:17:00.083  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 18:17:00.083  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 18:17:00.083  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 18:17:00.083  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 18:17:00.083  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 18:17:00.083  3867  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:17:00.084  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 18:17:00.084  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:17:00.084  3867  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:17:00.084  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 18:17:00.084  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:17:00.084  3867  3913 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 18:17:00.084  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 18:17:00.088  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 18:17:00.088  2700  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 18:17:00.088  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.089  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 18:17:00.089  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 18:17:00.090  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 18:17:00.090  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 18:17:00.090  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 18:17:00.090  3867  3913 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 18:17:00.090  3867  3913 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 18:17:00.090  3867  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-16 18:17:00.091  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.091  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.091  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.091  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.091  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.091  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.091  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 18:17:00.092  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.092  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.092  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.092  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.092  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.093  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.093  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.093  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.094  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.094  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.094  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.094  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.095  3867  3913 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 18:17:00.096  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.096  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.096  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.096  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.096  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.096  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.096  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.096  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.096  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.096  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.096  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.096  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.096  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.097  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.097  3867  3915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:17:00.097  2700  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 18:17:00.097  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.097  2700  2756 D BtGatt.ScanManager: stopping BLe Batch
08-16 18:17:00.097  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.097  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.097  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.098  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.099  3867  3913 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 18:17:00.099  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.099  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.099  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.099  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.099  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.099  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.099  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.099  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.099  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.100  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.100  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.100  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.100  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.100  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.101  3867  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-16 18:17:00.101  3867  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-16 18:17:00.101  3867  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
08-16 18:17:00.102  3867  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-16 18:17:00.104  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.104  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.104  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.104  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.105  3867  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 18:17:00.105  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 18:17:00.105  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:17:00.105  3867  3913 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 18:17:00.105  3867  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:17:00.105  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 18:17:00.105  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:17:00.105  3867  3913 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 18:17:00.105  3867  3913 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 18:17:00.105  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 18:17:00.105  2700  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 18:17:00.105  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 18:17:00.105  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.105  3867  3913 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 18:17:00.105  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.105  2700  2756 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 18:17:00.106  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.106  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.106  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.106  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.106  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.106  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.106  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.106  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.106  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.106  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.106  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.106  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.106  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.107  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.107  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.107  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.107  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.108  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.108  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.108  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.108  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.108  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.108  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.108  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.108  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.108  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.108  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.108  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.109  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.109  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.109  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.109  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.109  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.109  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.109  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.109  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.109  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.109  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.109  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.109  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.110  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.110  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.110  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.110  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.110  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.110  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.111  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.111  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.111  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.111  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.112  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 18:17:00.112  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:17:00.112  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 18:17:00.113  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 18:17:00.113  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:17:00.113  3867  3867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 18:17:00.113  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 18:17:00.113  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.113  3867  3913 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 18:17:00.113  2700  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 18:17:00.113  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.113  2700  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:00.113  3867  3867 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.113  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 18:17:00.113  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:17:00.114  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:17:00.114  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.114  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.115  3867  3920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 18:17:00.115  3867  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 18:17:00.115  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:00.115  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:00.115  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.115  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:00.115  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.115  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:00.115  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.115  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.115  3867  3867 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 18:17:00.115  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.115  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.115  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.115  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.115  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.115  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.115  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.115  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.116  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.116  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.116  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.116  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.116  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.116  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.116  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.117  3867  3913 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 18:17:00.117  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 18:17:00.117  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 18:17:00.118  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 18:17:00.119  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:17:00.119  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 18:17:00.119  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.119  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.119  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.119  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.119  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
,08-16 18:17:00.119  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.119  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.119  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.119  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.119  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.119  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.119  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.120  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.120  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.120  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:00.120  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
,08-16 18:17:00.122  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 18:17:00.122  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.122  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:00.123  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.123  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.123  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.123  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.123  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.123  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.123  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.123  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.123  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.123  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:00.123  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:00.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.124  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.124  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:00.124  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:00.124  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:00.124  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:00.124  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.124  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.125  3867  3913 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@601eda8 not in the list
08-16 18:17:00.125  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.125  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.125  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:00.125  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.125  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:00.125  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:00.125  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:00.125  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:00.125  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:00.125  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:00.126  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2b90c1 not in the list
08-16 18:17:00.126  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 18:17:00.126  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:17:00.126  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 18:17:00.126  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 18:17:00.126  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 18:17:00.126  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 18:17:00.128  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 18:17:00.128  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 18:17:00.128  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 18:17:00.128  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:17:00.128  3867  3913 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 18:17:00.128  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 18:17:00.128  3867  3913 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 18:17:00.128  3867  3913 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-16 18:17:00.129  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 18:17:00.129  3867  3913 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 18:17:00.129  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 18:17:00.129  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 18:17:00.129  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 18:17:00.129  3867  3913 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 18:17:00.130  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:00.130  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ec93bb added. We now have 2 listener(s)
08-16 18:17:00.130  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:00.131  3867  3913 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 18:17:00.131   872  2110 D WifiService: setWifiEnabled: true pid=3867, uid=10000
08-16 18:17:00.132   872  2110 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 18:17:00.132  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:00.132  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e6010d8 added. We now have 3 listener(s)
08-16 18:17:00.132  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:00.135  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:00.135  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3192c31 added. We now have 4 listener(s)
08-16 18:17:00.135  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:00.137  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:00.137  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c14ef16 added. We now have 5 listener(s)
08-16 18:17:00.137  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:00.138   872   882 D WifiService: setWifiEnabled: false pid=3867, uid=10000
08-16 18:17:00.138   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 18:17:00.148  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:17:00.149  2700  2747 D BluetoothAdapterState: Current state: ON, message: 23
08-16 18:17:00.149  2700  2747 D BluetoothAdapterProperties: Setting state to 13
08-16 18:17:00.149  2700  2747 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:17:00.149  2700  2747 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 18:17:00.150  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:17:,00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:17:00.150  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:17:00.151  2700  2747 I BluetoothAdapterState: Entering PendingCommandState
08-16 18:17:00.151  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.151  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:00.151  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:17:00.151  2700  2700 D BluetoothMapService: onReceive
08-16 18:17:00.151  2700  2700 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:17:00.152  2700  2700 D BluetoothMapService: STATE_TURNING_OFF
08-16 18:17:00.152  2700  2700 D BluetoothMapService: MAP Service closeService in
08-16 18:17:00.152  2700  2700 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 18:17:00.152  2700  2700 D ObexServerSockets0: shutdown(block = true)
08-16 18:17:00.152  2700  2700 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 18:17:00.152  2700  2700 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 18:17:00.153  2700  2892 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 18:17:00.153  2700  2893 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 18:17:00.153  2700  2880 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 18:17:00.153  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:00.153  2700  2700 I BtOppRfcommListener: stopping Accept Thread
08-16 18:17:00.154  2700  3430 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 18:17:00.154  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 18:17:00.154  2700  3430 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 18:17:00.155   872  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 18:17:00.155   872  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 18:17:00.155   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 18:17:00.155   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:17:00.157  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:00.160   872  1305 E native  : do suspend true
08-16 18:17:00.160  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:17:00.160  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:17:00.161  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.161  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:00.163  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:00.163   872   885 I ActivityManager: Start proc 3923:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-16 18:17:00.164  2700  2752 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:17:00.164  2700  2747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 18:17:00.167  2700  2700 D HeadsetService: Received stop request...Stopping profile...
08-16 18:17:00.169   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:00.169   872   872 D BluetoothHeadset: Proxy object disconnected
,08-16 18:17:00.169  1914  2087 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:00.169   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:00.169  1361  1373 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:00.169  2700  2700 D A2dpService: Received stop request...Stopping profile...
08-16 18:17:00.170  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:00.170  2700  2886 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:17:00.171   872   872 D BluetoothA2dp: Proxy object disconnected
08-16 18:17:00.172   872  1873 D DhcpClient: Clearing IP address
08-16 18:17:00.173  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:00.173   372   870 D CommandListener: Clearing all IP addresses on wlan0
08-16 18:17:00.173  2700  2700 D HidService: Received stop request...Stopping profile...
,08-16 18:17:00.173  2700  2700 D HidService: Stopping Bluetooth HidService
08-16 18:17:00.175  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:00.175  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.175  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.175  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:00.175   372   870 D CommandListener: Setting iface cfg
08-16 18:17:00.177  2700  2700 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 18:17:00.177  2700  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 18:17:00.177  2700  2700 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 18:17:00.177  2700  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:00.177  2700  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:00.177  1524  2136 V NativeCrypto: Read error: ssl=0xaec4f000: I/O error during system call, Connection timed out
08-16 18:17:00.177  2700  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:00.177  2700  2752 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 18:17:00.177  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:00.177  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.177  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.177  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:00.178   872  1878 D DhcpClient: Receive thread stopped
08-16 18:17:00.178  2700  2700 V BluetoothAdapterState: isTurningOff()=true
,08-16 18:17:00.179  2700  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 18:17:00.179  2700  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:00.179  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.179  2700  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:00.179  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.179  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:00.179  2700  2871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:17:00.179  2700  2871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:17:00.179  2700  2871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:17:00.180  2700  2871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:17:00.180  2700  2700 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:17:00.180  2700  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 18:17:00.180  2700  2700 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:17:00.180   872  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 18:17:00.181   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 18:17:00.181  2700  2700 D HealthService: Received stop request...Stopping profile...
08-16 18:17:00.181   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 18:17:00.183   397   397 E Parcel  : Reading a NULL string not supported here.
08-16 18:17:00.183   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 18:17:00.183   872  1305 E native  : do suspend true
08-16 18:17:00.184  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 18:17:00.184  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-16 18:17:00.184  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 18:17:00.184  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 18:17:00.187  2700  2700 D PanService: Received stop request...Stopping profile...
,08-16 18:17:00.188  2700  2700 D BluetoothMapService: Received stop request...Stopping profile...
08-16 18:17:00.188  2700  2700 D BluetoothMapService: stop()
08-16 18:17:00.189   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 18:17:00.190  2700  2700 D BluetoothMapAppObserver: deinitObservers()
08-16 18:17:00.190  2700  2700 D BluetoothMapAppObserver: removeReceiver()
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:00.193  2700  2700 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:17:00.193  2700  2752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 18:17:00.193  2700  2700 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isTurningOff()=true
,08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.193  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:00.194  2700  2700 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:17:00.195  2700  2700 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 18:17:00.196  2700  2700 D BluetoothMapService: MAP Service closeService in
08-16 18:17:00.196  2700  2700 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:00.197  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.197  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.197  2700  2700 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:00.198  2700  2747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 18:17:00.198  2700  2700 D BluetoothMapService: cleanup()
08-16 18:17:00.198  2700  2700 D BluetoothMapService: MAP Service closeService in
08-16 18:17:00.198  2700  2747 D BluetoothAdapterProperties: Setting state to 15
08-16 18:17:00.198  2700  2747 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 18:17:00.198  2700  2747 I BluetoothAdapterState: Entering BleOnState
08-16 18:17:00.199  1361  1379 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:17:00.199  1524  2136 V NativeCrypto: SSL shutdown failed: ssl=0xaec4f000: I/O error during system call, Broken pipe
08-16 18:17:00.200   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:17:00.200  1361  2014 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:17:00.203  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:17:00.203  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 18:17:00.204   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:00.204   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:00.204   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:00.204  1361  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:00.204  1914  2069 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:00.204  1361  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 18:17:00.205  1361  2014 D BluetoothPan: onBluetoothStateChange on: false
,08-16 18:17:00.205  1361  1379 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:17:00.206  2700  2747 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 18:17:00.206  2700  2747 D BluetoothAdapterProperties: Setting state to 16
08-16 18:17:00.206  2700  2747 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 18:17:00.206  2700  2747 D BluetoothAdapterProperties: onBleDisable
08-16 18:17:00.207  2700  2747 I BluetoothAdapterState: Entering PendingCommandState
08-16 18:17:00.207  2700  2748 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 18:17:00.208  2700  2871 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 18:17:00.208  2700  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 18:17:00.208  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:00.208  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:00.209  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.209  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:00.209  2700  2752 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:17:00.210  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:00.211  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:00.211  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:17:00.211  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:00.212  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:00.213  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:00.239  3923  3923 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 18:17:00.240   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:00.248  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:17:00.253  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:17:00.255   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb0fd2:true
,08-16 18:17:00.263   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:00.264   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:17:00.264   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 18:17:00.264   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:00.265   872  1954 I ActivityManager: Start proc 3939:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 18:17:00.267   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 18:17:00.272   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:17:00.274  3381  3381 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6b9f833 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 18:17:00.276  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:00.277  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:00.288   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 18:17:00.291  2175  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:17:00.292   872  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:17:00.293  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:00.293  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:00.293  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.293  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:00.294  3923  3923 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 18:17:00.295  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:00.295  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:00.296  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:00.296  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:00.299  3923  3923 D BluetoothMap: Create BluetoothMap proxy object
,08-16 18:17:00.308  3923  3923 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 18:17:00.313  3939  3939 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 18:17:00.323  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:17:00.331   872   883 I ActivityManager: Killing 3564:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 18:17:00.333   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-16 18:17:00.410  2700  2752 I bt_hci  : shut_down
,08-16 18:17:00.417  2700  2758 I bt_vendor: low_power_mode_cb
08-16 18:17:00.417  2700  2758 D bt_hwcfg: hw_epilog_process
,08-16 18:17:00.438  2700  2758 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 18:17:00.438  2700  2758 I bt_vendor: epilog_cb
,08-16 18:17:00.438  2700  2758 I bt_hci  : epilog_finished_callback
,08-16 18:17:00.443  2700  2752 I bt_hci_h4: hal_close
,08-16 18:17:00.444  2700  2752 I bt_userial_vendor: device fd = 51 close
,08-16 18:17:00.483  3939  3939 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265),
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:00.483  3939  3939 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2,
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.483  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:00.484  3939  3939 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:00.484  3939  3939 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:00.484  3939  3939 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.484  3939  3939 D StrictMode: 	,at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 18:17:00.484  3939  3939 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:00.484  3939  3939 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 18:17:00.484  3939  3939 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:00.484  3939  3939 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:00.489  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:17:00.496  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:17:00.500  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:17:00.548   872  1877 I ActivityManager: Start proc 3974:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 18:17:00.549   872  1877 I ActivityManager: Killing 3381:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 18:17:00.616  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:17:00.661  3974  3974 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 18:17:00.664  2700  2748 D bt_stack_manager: event_shut_down_stack finished.
,08-16 18:17:00.665  2700  2747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 18:17:00.670  2700  2747 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 18:17:00.670  2700  2700 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 18:17:00.671  2700  2700 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 18:17:00.671  2700  2700 D BtGatt.GattService: stop()
,08-16 18:17:00.672  2700  2700 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 18:17:00.676  2700  2700 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:00.676  2700  2700 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:00.677  2700  2700 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:00.677  2700  2700 V BluetoothAdapterState: isBleTurningOff()=true
08-16 18:17:00.679  2700  2747 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 18:17:00.679  2700  2747 D BluetoothAdapterProperties: Setting state to 10
08-16 18:17:00.679  2700  2747 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 18:17:00.680  2700  2747 I BluetoothAdapterState: Entering OffState
08-16 18:17:00.683   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 18:17:00.703  2700  2700 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 18:17:00.704  2700  2700 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 18:17:00.704  2700  2748 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 18:17:00.706  2700  2748 D bt_stack_manager: event_clean_up_stack finished.
,08-16 18:17:00.706  2700  2700 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 18:17:00.710  2700  2700 I art     : System.exit called, status: 0
,08-16 18:17:00.710  2700  2700 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 18:17:00.789   872  2109 I ActivityManager: Process com.android.bluetooth (pid 2700) has died
,08-16 18:17:00.930  3974  3995 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 18:17:00.930  3974  3995 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 18:17:00.937  3974  3995 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 18:17:00.937  3974  3995 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 18:17:00.978  3974  3995 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 18:17:00.978  3974  3995 I Babel_SMS: MmsConfig.loadFromResources
08-16 18:17:00.979  3974  3995 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 18:17:00.981  3974  3995 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 18:17:01.003  3974  3974 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 18:17:01.005  3974  3974 I Babel_Crash: startup - clean
,08-16 18:17:01.041  3974  3974 I Babel_telephony: TeleModule.launchCompleted
,08-16 18:17:01.046   872  1619 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 18:17:01.060  3974  3974 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 18:17:01.067  3974  3974 W Babel   : BAM#gBA: invalid account id: -1
08-16 18:17:01.068  3974  3974 W Babel   : BAM#gBA: invalid account id: -1
,08-16 18:17:01.068  3974  3974 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 18:17:01.072   872  1934 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 18:17:01.076  3974  4000 I Babel   : deleted: false for 0
,08-16 18:17:01.102  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 18:17:01.117  1738  1738 D SystemUpdateService: onCreate
,08-16 18:17:01.127  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 18:17:01.138  1738  4002 I SystemUpdateService: active receiver: enabled
,08-16 18:17:01.161  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 18:17:01.161  1738  4002 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 18:17:01.162  1738  2419 I iu.UploadsManager: num queued entries: 0
,08-16 18:17:01.163  1738  2419 I iu.UploadsManager: num updated entries: 0
,08-16 18:17:01.164  1738  2419 I iu.SyncManager: NEXT; no task
,08-16 18:17:01.168  1738  4002 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 18:17:01.168  1738  4002 I SystemUpdateService: now status is 0 (complete)
08-16 18:17:01.168  1738  4002 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 18:17:01.168  1738  4002 I SystemUpdateService: file has been verified
,08-16 18:17:01.169  1738  4002 I SystemUpdateService: OTA package size = 12249756
08-16 18:17:01.170  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 18:17:01.171  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,08-16 18:17:01.178  1738  4002 I SystemUpdateService: showing system update notification
,08-16 18:17:01.181  3974  3974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:17:01.199   872  1877 I ActivityManager: Start proc 4004:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 18:17:01.223  1738  1738 D SystemUpdateService: onDestroy
,08-16 18:17:01.245  4004  4004 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 18:17:01.247  3974  3974 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 18:17:01.253  3974  3974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:17:01.253  3939  3966 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 18:17:01.256  3974  3974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:17:01.257  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:01.270  3974  3974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:17:01.271  4004  4004 D SprintDMHelper: simOperator: 
08-16 18:17:01.272  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 18:17:01.283  3974  3974 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 18:17:01.311   872  2108 I ActivityManager: Start proc 4016:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 18:17:01.323  3974  3974 I vclib   : onServiceConnected
,08-16 18:17:01.327   872  2108 I ActivityManager: Killing 3451:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 18:17:01.361   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2cdd56:true
,08-16 18:17:01.504   872  1372 I ActivityManager: Start proc 4031:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 18:17:01.512  3974  4030 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 18:17:01.531   872  1877 I ActivityManager: Killing 3491:android.process.acore/u0a5 (adj 15): empty #17
,08-16 18:17:01.560  4031  4031 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 18:17:01.637  4031  4031 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 18:17:01.637  4031  4031 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 18:17:01.637  4031  4031 I GAv4    :   adb logcat -s GAv4
,08-16 18:17:01.655  4031  4031 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 18:17:01.662  4031  4031 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 18:17:01.686  4031  4048 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 18:17:01.795  4031  4031 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 18:17:01.835  4031  4031 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 18:17:01.847  4031  4031 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 251-253)
,08-16 18:17:01.847  4031  4031 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 18:17:01.861  4031  4031 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e715423}
,08-16 18:17:01.862  4031  4031 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 18:17:01.862  4031  4031 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 18:17:01.872  4031  4031 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 18:17:01.873  4031  4031 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 18:17:01.889  4031  4031 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 18:17:01.901  4031  4031 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 18:17:01.901  4031  4031 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 18:17:01.901  4031  4031 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 18:17:01.901  4031  4031 I Adreno  : Build Date                       : 10/20/15
08-16 18:17:01.901  4031  4031 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 18:17:01.901  4031  4031 I Adreno  : Local Branch                     : M14
08-16 18:17:01.901  4031  4031 I Adreno  : Remote Branch                    : 
08-16 18:17:01.901  4031  4031 I Adreno  : Remote Branch                    : 
08-16 18:17:01.901  4031  4031 I Adreno  : Reconstruct Branch               : 
,08-16 18:17:01.973  4031  4031 I NSApplication: Starting up...
,08-16 18:17:01.984  4031  4077 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 18:17:02.016   872  1954 I ActivityManager: Start proc 4082:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 18:17:02.018   872  1954 I ActivityManager: Killing 3654:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 18:17:02.097  4082  4082 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 18:17:02.293   872   882 I ActivityManager: Killing 3671:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 18:17:03.154   872   883 D WifiService: setWifiEnabled: true pid=3867, uid=10000
,08-16 18:17:03.154   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:17:03.167   872  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-16 18:17:03.175  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:03.176  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:03.176  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:03.176  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:03.179  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:03.180  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:03.180  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:17:03.180  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:03.214   872  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-16 18:17:03.215   872  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 18:17:03.217   872  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 18:17:03.219   872  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 18:17:03.219   872  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 18:17:03.219   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 18:17:03.219   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 18:17:03.238   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 18:17:03.240   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 18:17:03.240   372   870 D CommandListener: Setting iface cfg
,08-16 18:17:03.242   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 18:17:03.242   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 18:17:03.253   872  1305 E native  : do suspend true
,08-16 18:17:03.264   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 18:17:03.271   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 18:17:03.271   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 18:17:04.637   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 18:17:04.738   872  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.75 rxSuccessRate=10.06 delta 1000 -> 994
,08-16 18:17:04.740   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 18:17:04.740   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:17:04.755   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 18:17:04.791   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 18:17:04.792  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 18:17:05.217  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 18:17:05.257  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 18:17:05.257  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 18:17:05.263   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 18:17:05.279   872  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 18:17:05.279   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 18:17:05.280   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 18:17:05.310   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:17:05.321   372   870 D CommandListener: Setting iface cfg
,08-16 18:17:05.322   872  1305 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 18:17:05.327   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 18:17:05.369   872  4108 D DhcpClient: Receive thread started
,08-16 18:17:05.446   872  1305 E native  : do suspend false
,08-16 18:17:05.457   872  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 18:17:05.473   872  4108 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172588, domain null
,08-16 18:17:05.473   872  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172588 seconds
,08-16 18:17:05.477   872  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 18:17:05.488   872  4108 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 18:17:05.489   872  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 18:17:05.494   372   870 D CommandListener: Setting iface cfg
,08-16 18:17:05.506   872  1873 D DhcpClient: Scheduling renewal in 86399s
,08-16 18:17:05.507   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 18:17:05.512   872  1305 E native  : do suspend true
,08-16 18:17:05.531   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 18:17:05.532   872  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 18:17:05.533   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 18:17:05.535   872  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 18:17:05.535   872  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 18:17:05.585   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 18:17:05.585   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 18:17:05.587   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 18:17:05.588   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 18:17:05.590   872  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 18:17:05.600   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 18:17:05.606   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 18:17:05.607   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 18:17:05.607   872  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 18:17:05.608   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 18:17:05.608   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 18:17:05.608   872  1308 D ConnectivityService:    accepting network in place of null
,08-16 18:17:05.610   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 18:17:05.618   872  4107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=234025, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 18:17:05.635   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:05.662   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:05.666   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 18:17:05.667   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:05.672   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 18:17:05.673   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:17:05.685   872  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:810::200e
08-16 18:17:05.692  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:17:05.692  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 18:17:05.692  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:05.692  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:05.694  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:17:05.694  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:17:05.694  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:05.694  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 18:17:05.701  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 18:17:05.703  1738  1738 D SystemUpdateService: onCreate
,08-16 18:17:05.708  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 18:17:05.711  1738  4120 I SystemUpdateService: active receiver: enabled
,08-16 18:17:05.715  1738  4120 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 18:17:05.718  1738  4120 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 18:17:05.719  1738  4120 I SystemUpdateService: now status is 0 (complete)
,08-16 18:17:05.719  1738  4120 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 18:17:05.719  1738  4120 I SystemUpdateService: file has been verified
,08-16 18:17:05.721  1738  4120 I SystemUpdateService: OTA package size = 12249756
,08-16 18:17:05.729  1738  4120 I SystemUpdateService: showing system update notification
,08-16 18:17:05.733  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 18:17:05.738  1738  2419 I iu.UploadsManager: num queued entries: 0
,08-16 18:17:05.739  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 18:17:05.740  1738  2419 I iu.UploadsManager: num updated entries: 0
,08-16 18:17:05.741  1738  2419 I iu.SyncManager: NEXT; no task
,08-16 18:17:05.744  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 18:17:05.749  1738  1738 D SystemUpdateService: onDestroy
,08-16 18:17:05.750  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:05.753  1738  4123 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 18:17:05.753  1738  4123 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 18:17:05.754  1738  4123 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 18:17:05.758  4004  4004 D SprintDMHelper: simOperator: 
08-16 18:17:05.758  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 18:17:05.760  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 18:17:05.763  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 18:17:05.766   872  4106 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:17:05 GMT], X-Android-Received-Millis=[1471364225765], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471364225732]}
08-16 18:17:05.767   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 18:17:05.767   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 18:17:05.767   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 18:17:05.768   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 18:17:05.787  1524  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 18:17:05.787  1524  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 18:17:05.787  1524  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 18:17:05.787  1524  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 18:17:05.799  1738  4123 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-16 18:17:05.819  3974  3974 I art     : Waiting for a blocking GC DisableMovingGc
,08-16 18:17:05.823  3974  3974 I art     : Starting a blocking GC DisableMovingGc
,08-16 18:17:05.960  3974  4128 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 18:17:05.962   872   883 I ActivityManager: Killing 2237:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 18:17:06.160   872  2110 D WifiService: setWifiEnabled: false pid=3867, uid=10000
,08-16 18:17:06.160   872  2110 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:17:06.191  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 18:17:06.202   872  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 18:17:06.202   872  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 18:17:06.203   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 18:17:06.203   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:17:06.232   872  1305 E native  : do suspend true
,08-16 18:17:06.247   872  1873 D DhcpClient: Clearing IP address
,08-16 18:17:06.248   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:17:06.263  1524  4130 V NativeCrypto: Read error: ssl=0x9a8d5000: I/O error during system call, Connection timed out
,08-16 18:17:06.269   372   870 D CommandListener: Setting iface cfg
,08-16 18:17:06.273   872  4108 D DhcpClient: Receive thread stopped
,08-16 18:17:06.276   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 18:17:06.276   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 18:17:06.283   397   397 E Parcel  : Reading a NULL string not supported here.
,08-16 18:17:06.283  1524  4130 V NativeCrypto: SSL shutdown failed: ssl=0x9a8d5000: I/O error during system call, Broken pipe
,08-16 18:17:06.290   872  1305 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 18:17:06.291   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 18:17:06.291   872  1305 E native  : do suspend true
,08-16 18:17:06.295   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 18:17:06.330   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:06.355   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:06.356   372   870 D CommandListener: Clearing all IP addresses on wlan0
,08-16 18:17:06.356   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 18:17:06.357   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:06.363   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:17:06.366  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:06.367  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:06.367  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.367  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:06.371  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:06.371  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:06.371  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.372  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:06.375   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 18:17:06.386  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 18:17:06.390   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 18:17:06.393  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:06.393  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:06.393  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.393  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:06.394  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.394  1738  1738 D SystemUpdateService: onCreate
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:06.394  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:06.394  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:06.394  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:06.397  2175  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 18:17:06.398   872  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 18:17:06.398  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 18:17:06.420  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 18:17:06.439  1738  4143 I SystemUpdateService: active receiver: enabled
,08-16 18:17:06.442  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 18:17:06.443  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 18:17:06.444  1738  2419 I iu.UploadsManager: num queued entries: 0
,08-16 18:17:06.445  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:06.449   372   870 E Netd    : netlink response contains error (No such file or directory)
,08-16 18:17:06.450   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 18:17:06.451  4004  4004 D SprintDMHelper: simOperator: 
08-16 18:17:06.451  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 18:17:06.463  1738  2419 I iu.UploadsManager: num updated entries: 0
,08-16 18:17:06.471  1738  4143 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 18:17:06.473  1738  2419 I iu.SyncManager: NEXT; no task
,08-16 18:17:06.489  3974  4147 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 18:17:06.498  1738  4143 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 18:17:06.498  1738  4143 I SystemUpdateService: now status is 0 (complete)
,08-16 18:17:06.498  1738  4143 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 18:17:06.498  1738  4143 I SystemUpdateService: file has been verified
08-16 18:17:06.498  1738  4143 I SystemUpdateService: OTA package size = 12249756
,08-16 18:17:06.526  1738  4143 I SystemUpdateService: showing system update notification
,08-16 18:17:06.537  1738  1738 D SystemUpdateService: onDestroy
,08-16 18:17:06.666   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 18:17:09.221   872   889 I ActivityManager: Start proc 4150:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 18:17:09.339  4150  4150 D AdapterServiceConfig: Adding HeadsetService
,08-16 18:17:09.340  4150  4150 D AdapterServiceConfig: Adding A2dpService
,08-16 18:17:09.340  4150  4150 D AdapterServiceConfig: Adding HidService
,08-16 18:17:09.340  4150  4150 D AdapterServiceConfig: Adding HealthService
,08-16 18:17:09.341  4150  4150 D AdapterServiceConfig: Adding PanService
08-16 18:17:09.341  4150  4150 D AdapterServiceConfig: Adding GattService
,08-16 18:17:09.341  4150  4150 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 18:17:09.357  4150  4150 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 18:17:09.357   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e5089b:true
,08-16 18:17:09.365  4150  4150 I bt_bluedroid: init
,08-16 18:17:09.365  4150  4162 I BluetoothAdapterState: Entering OffState
,08-16 18:17:09.372  4150  4163 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 18:17:09.372  4150  4163 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 18:17:09.373  4150  4163 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 18:17:09.373  4150  4163 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 18:17:09.375  4150  4150 I bt_bluedroid: get_profile_interface socket
08-16 18:17:09.377  4150  4150 I bt_bluedroid: get_profile_interface sdp
,08-16 18:17:09.381  4150  4161 I bt_bluedroid: config_hci_snoop_log
,08-16 18:17:09.382  4150  4166 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 18:17:09.383   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 18:17:09.385  4150  4166 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 18:17:09.393  4150  4162 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 18:17:09.393  4150  4162 D BluetoothAdapterProperties: Setting state to 14
08-16 18:17:09.394  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 18:17:09.397  4150  4162 D BluetoothBondStateMachine: make
,08-16 18:17:09.401  4150  4167 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 18:17:09.405  4150  4162 I BluetoothAdapterState: Entering PendingCommandState
,08-16 18:17:09.406  4150  4150 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 18:17:09.409  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:09.410  4150  4150 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 18:17:09.410  4150  4150 D BtGatt.GattService: Received start request. Starting profile...
,08-16 18:17:09.411  4150  4150 D BtGatt.GattService: start()
,08-16 18:17:09.411  4150  4150 I bt_bluedroid: get_profile_interface gatt
,08-16 18:17:09.412  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
08-16 18:17:09.412  4150  4150 D BtGatt.AdvertiseManager: advertise manager created
,08-16 18:17:09.420  4150  4150 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:09.421  4150  4150 V BluetoothAdapterState: isTurningOn()=false
,08-16 18:17:09.421  4150  4150 V BluetoothAdapterState: isBleTurningOn()=true
08-16 18:17:09.421  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:09.421  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 18:17:09.421  4150  4162 I bt_bluedroid: enable
08-16 18:17:09.422  4150  4163 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 18:17:09.422  4150  4163 I bt_hci  : start_up
,08-16 18:17:09.437  4150  4163 I bt_vendor: alloc value 0xb3a70189
,08-16 18:17:09.437  4150  4163 I bt_vendor: init
08-16 18:17:09.437  4150  4163 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 18:17:09.437  4150  4163 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 18:17:09.545  4150  4163 D bt_hci  : start_up starting async portion
,08-16 18:17:09.546  4150  4170 I bt_hci  : event_finish_startup
08-16 18:17:09.546  4150  4170 I bt_hci_h4: hal_open
08-16 18:17:09.546  4150  4170 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 18:17:09.558  4150  4170 I bt_userial_vendor: device fd = 51 open
,08-16 18:17:09.587  4150  4170 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 18:17:09.619  4150  4170 D bt_hwcfg: Chipset BCM4354A2
,08-16 18:17:09.619  4150  4170 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 18:17:09.620  4150  4170 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 18:17:10.275  4150  4170 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 18:17:10.276  4150  4170 D bt_hwcfg: Settlement delay -- 100 ms
08-16 18:17:10.277  4150  4170 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 18:17:10.393  4150  4170 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 18:17:10.394  4150  4170 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 18:17:10.424  4150  4170 I bt_hwcfg: vendor lib fwcfg completed
,08-16 18:17:10.424  4150  4170 I bt_vendor: firmware callback
08-16 18:17:10.424  4150  4170 I bt_hci  : firmware_config_callback
,08-16 18:17:10.435  4150  4172 I bt_btu  : btu_task pending for preload complete event
,08-16 18:17:10.435  4150  4172 I bt_btu_task: Bluetooth chip preload is complete
,08-16 18:17:10.436  4150  4172 I bt_btu  : btu_task received preload complete event
,08-16 18:17:10.445  4150  4172 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 18:17:10.446  4150  4172 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 18:17:10.446  4150  4172 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 18:17:10.446  4150  4172 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 18:17:10.447  4150  4172 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:17:10.447  4150  4172 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 18:17:10.447  4150  4172 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 18:17:10.447  4150  4172 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:17:10.448  4150  4172 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 18:17:10.448  4150  4172 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:17:10.448  4150  4172 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 18:17:10.448  4150  4172 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 18:17:10.449  4150  4172 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 18:17:10.449  4150  4172 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 18:17:10.449  4150  4172 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 18:17:10.581  4150  4172 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,08-16 18:17:10.582  4150  4172 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,08-16 18:17:10.591  4150  4166 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-16 18:17:10.592  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 18:17:10.592  4150  4166 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 18:17:10.594  4150  4166 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 18:17:10.596  4150  4166 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:17:10.596  4150  4166 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 18:17:10.597  4150  4166 D bt_hci  : do_postload posting postload work item
,08-16 18:17:10.597  4150  4170 I bt_hci  : event_postload
08-16 18:17:10.597  4150  4170 I bt_vendor: sco_config_cb
,08-16 18:17:10.598  4150  4170 I bt_hci  : sco_config_callback postload finished.
,08-16 18:17:10.601  4150  4166 D bt_bte_conf: Device ID record 1 : primary
,08-16 18:17:10.601  4150  4166 D bt_bte_conf:   vendorId            = 000f
08-16 18:17:10.601  4150  4166 D bt_bte_conf:   vendorIdSource      = 0001
08-16 18:17:10.601  4150  4166 D bt_bte_conf:   product             = 1200
,08-16 18:17:10.601  4150  4166 D bt_bte_conf:   version             = 1436
08-16 18:17:10.601  4150  4166 D bt_bte_conf:   clientExecutableURL = 
,08-16 18:17:10.601  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:10.601  4150  4166 D bt_bte_conf:   serviceDescription  = 
,08-16 18:17:10.601  4150  4166 D bt_bte_conf:   documentationURL    = 
,08-16 18:17:10.602  4150  4166 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 18:17:10.602  4150  4163 D bt_stack_manager: event_start_up_stack finished
08-16 18:17:10.602  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 18:17:10.602  4150  4162 D BluetoothAdapterProperties: Setting state to 15
,08-16 18:17:10.603  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 18:17:10.605  4150  4162 I BluetoothAdapterState: Entering BleOnState
08-16 18:17:10.606  4150  4170 I bt_vendor: low_power_mode_cb
,08-16 18:17:10.607  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:10.608  4150  4162 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 18:17:10.608  4150  4162 D BluetoothAdapterProperties: Setting state to 11
,08-16 18:17:10.609  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 18:17:10.620  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
08-16 18:17:10.623  4150  4150 D HeadsetService: Received start request. Starting profile...
08-16 18:17:10.630  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:10.631  4150  4150 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 18:17:10.631  4150  4150 D HeadsetStateMachine: make
08-16 18:17:10.632  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:10.643  4150  4162 I BluetoothAdapterState: Entering PendingCommandState
,08-16 18:17:10.644  4150  4150 D HeadsetStateMachine: max_hf_connections = 1
,08-16 18:17:10.644  4150  4150 I bt_bluedroid: get_profile_interface handsfree
08-16 18:17:10.644  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 18:17:10.645  4150  4166 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 18:17:10.650  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:10.651  4150  4150 D A2dpService: Received start request. Starting profile...
,08-16 18:17:10.653  4150  4150 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 18:17:10.653  4150  4150 I bt_bluedroid: get_profile_interface avrcp
,08-16 18:17:10.661  4150  4150 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 18:17:10.661  4150  4150 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:17:10.662  4150  4150 D A2dpStateMachine: make
,08-16 18:17:10.663  4150  4150 I bt_bluedroid: get_profile_interface a2dp
,08-16 18:17:10.664  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 18:17:10.666  4150  4183 D A2dpStateMachine: Enter Disconnected: -2
,08-16 18:17:10.666  4150  4150 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 18:17:10.668  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:10.669  4150  4150 D HidService: Received start request. Starting profile...
,08-16 18:17:10.669  3923  3923 D BluetoothInputDevice: Proxy object connected,
08-16 18:17:10.669  4150  4150 I bt_bluedroid: get_profile_interface hidhost
08-16 18:17:10.670  4150  4150 D HidService: setHidService(): set to: null
,08-16 18:17:10.670  4150  4166 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
08-16 18:17:10.670  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 18:17:10.670  3923  3923 D HidProfile: Bluetooth service connected
08-16 18:17:10.671  4150  4150 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:17:10.671  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
08-16 18:17:10.672  4150  4150 D HealthService: Received start request. Starting profile...
,08-16 18:17:10.674  4150  4150 I bt_bluedroid: get_profile_interface health
,08-16 18:17:10.675  4150  4150 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 18:17:10.676  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:10.679  4150  4150 D PanService: Received start request. Starting profile...
,08-16 18:17:10.679  3923  3923 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:17:10.679  4150  4150 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 18:17:10.679  4150  4150 I bt_bluedroid: get_profile_interface pan
08-16 18:17:10.680  3923  3923 D PanProfile: Bluetooth service connected
08-16 18:17:10.680  4150  4166 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 18:17:10.685  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:17:10.686  4150  4150 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
08-16 18:17:10.688  3923  3923 D BluetoothMap: Proxy object connected
,08-16 18:17:10.689  4150  4150 D BluetoothMapService: Received start request. Starting profile...
,08-16 18:17:10.690  3923  3923 D MapProfile: Bluetooth service connected
,08-16 18:17:10.691  3923  3923 D BluetoothMap: getConnectedDevices()
,08-16 18:17:10.692  3923  3923 D BluetoothMap: Bluetooth is Not enabled
,08-16 18:17:10.689  4150  4150 D BluetoothMapService: start()
,08-16 18:17:10.696  4150  4150 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 18:17:10.697  4150  4150 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 18:17:10.697  4150  4150 D BluetoothMapAppObserver: createReceiver()
,08-16 18:17:10.699  4150  4150 D BluetoothMapAppObserver: initObservers()
,08-16 18:17:10.699  4150  4150 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 18:17:10.707  4150  4150 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:10.708  4150  4150 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:10.708  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:10.708  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:10.712  4150  4150 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:10.712  4150  4181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 18:17:10.712  4150  4150 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:10.712  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:10.713  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:10.713  4150  4150 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:10.713  4150  4150 V BluetoothAdapterState: isTurningOn()=true
,08-16 18:17:10.714  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:10.714  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:10.714  4150  4150 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:10.715  4150  4150 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:10.715  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:10.715  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:10.716  4150  4150 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:10.716  4150  4150 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:10.716  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:10.717  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:10.718  4150  4150 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:10.719  4150  4150 V BluetoothAdapterState: isTurningOn()=true
,08-16 18:17:10.719  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:10.719  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:10.720  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 18:17:10.720  4150  4162 D BluetoothAdapterProperties: ScanMode =  20
08-16 18:17:10.721  4150  4162 D BluetoothAdapterProperties: State =  11
,08-16 18:17:10.724  4150  4166 D BluetoothAdapterProperties: Scan Mode:21
,08-16 18:17:10.725  4150  4162 D BluetoothAdapterProperties: Setting state to 12
,08-16 18:17:10.725  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 18:17:10.725  4150  4166 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:17:10.725  4150  4162 I BluetoothAdapterState: Entering OnState
08-16 18:17:10.726  3923  3934 D BluetoothPan: onBluetoothStateChange on: true
,08-16 18:17:10.726  1361  2014 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:17:10.728   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:17:10.728  4150  4150 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 18:17:10.729  1361  1373 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:17:10.729  4150  4150 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 18:17:10.731  4150  4150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:10.731  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:10.732   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:10.732   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:10.732   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 18:17:10.733  1361  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:10.734  3923  3935 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 18:17:10.735  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:10.735  4150  4150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 18:17:10.736  1914  1926 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:10.736  4150  4150 D ObexServerSockets: Succeed to create listening sockets 
,08-16 18:17:10.737  4150  4150 D ObexServerSockets0: startAccept()
08-16 18:17:10.737  4150  4150 D ObexServerSockets0: prepareForNewConnect()
08-16 18:17:10.737  1361  2014 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:10.738  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 18:17:10.739  1361  1361 D BluetoothInputDevice: Proxy object connected
08-16 18:17:10.739  1361  1361 D HidProfile: Bluetooth service connected
,08-16 18:17:10.739  3923  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:17:10.740  3923  3935 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:17:10.740  1361  1379 D BluetoothPan: onBluetoothStateChange on: true
08-16 18:17:10.741  4150  4150 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 18:17:10.741  4150  4150 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 18:17:10.741  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:10.742  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:17:10.742  1361  1361 D PanProfile: Bluetooth service connected
,08-16 18:17:10.742   872   872 D BluetoothA2dp: Proxy object connected
08-16 18:17:10.742  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 18:17:10.743  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
08-16 18:17:10.744  4150  4188 D ObexServerSockets0: Accepting socket connection...
08-16 18:17:10.745  4150  4189 D ObexServerSockets0: Accepting socket connection...
08-16 18:17:10.747  1361  1361 D BluetoothMap: Proxy object connected
08-16 18:17:10.747  1361  1361 D MapProfile: Bluetooth service connected
08-16 18:17:10.747  1361  1361 D BluetoothMap: getConnectedDevices()
,08-16 18:17:10.749   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 18:17:10.751  4150  4150 D BluetoothMapService: onReceive
08-16 18:17:10.751  4150  4150 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 18:17:10.752  4150  4150 D BluetoothMapService: STATE_ON
08-16 18:17:10.752  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:10.754  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:10.758  3923  3923 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 18:17:10.762  3923  3923 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 18:17:10.768  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:17:10.770  3923  3923 D BluetoothA2dp: Proxy object connected
,08-16 18:17:10.773  4150  4150 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 18:17:10.773  4150  4150 D ObexServerSockets0: prepareForNewConnect()
08-16 18:17:10.773  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:17:10.777  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:17:10.788  3923  3923 D BluetoothPbap: Proxy object connected
,08-16 18:17:10.788  1361  1361 D BluetoothPbap: Proxy object connected
08-16 18:17:10.788  1361  1361 D PbapServerProfile: Bluetooth service connected
08-16 18:17:10.789  3923  3923 D PbapServerProfile: Bluetooth service connected
,08-16 18:17:10.797  4150  4195 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:17:10.825  4150  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:17:10.827  4150  4199 I BtOppRfcommListener: Accept thread started.
,08-16 18:17:10.834   872   872 D BluetoothHeadset: Proxy object connected
,08-16 18:17:10.835   872   872 D BluetoothHeadset: Proxy object connected
,08-16 18:17:10.836  1914  2207 D BluetoothHeadset: Proxy object connected
,08-16 18:17:10.836   872   872 D BluetoothHeadset: Proxy object connected
,08-16 18:17:10.837  1361  1379 D BluetoothHeadset: Proxy object connected
08-16 18:17:10.837  1361  1361 D HeadsetProfile: Bluetooth service connected
08-16 18:17:10.838  1914  2069 D BluetoothHeadset: Proxy object connected
,08-16 18:17:10.865  3923  3934 D BluetoothHeadset: Proxy object connected
,08-16 18:17:10.867  3923  3923 D HeadsetProfile: Bluetooth service connected
,08-16 18:17:12.183  4150  4162 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 18:17:12.184  4150  4162 D BluetoothAdapterProperties: Setting state to 13
08-16 18:17:12.184  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 18:17:12.185  4150  4162 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 18:17:12.190  4150  4162 I BluetoothAdapterState: Entering PendingCommandState
,08-16 18:17:12.197  4150  4150 D BluetoothMapService: onReceive
08-16 18:17:12.198  4150  4150 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:17:12.198  4150  4150 D BluetoothMapService: STATE_TURNING_OFF
08-16 18:17:12.199  4150  4150 D BluetoothMapService: MAP Service closeService in
08-16 18:17:12.199  4150  4150 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 18:17:12.200  4150  4150 D ObexServerSockets0: shutdown(block = true)
08-16 18:17:12.201  4150  4188 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 18:17:12.202  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:12.202  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:12.205  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:12.205  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:12.205  4150  4166 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:17:12.206  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 18:17:12.204  4150  4150 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 18:17:12.207  4150  4189 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 18:17:12.208  4150  4176 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 18:17:12.208  4150  4150 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 18:17:12.208  4150  4150 I BtOppRfcommListener: stopping Accept Thread
,08-16 18:17:12.208  4150  4199 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 18:17:12.209  4150  4199 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 18:17:12.212  4150  4150 D HeadsetService: Received stop request...Stopping profile...
08-16 18:17:12.212  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 18:17:12.214  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:12.214  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:12.216  3923  3935 D BluetoothHeadset: Proxy object disconnected
,08-16 18:17:12.215  3867  3867 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 18:17:12.216   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:12.216  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:12.216   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:12.216  1914  2087 D BluetoothHeadset: Proxy object disconnected,
08-16 18:17:12.217   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:12.217  1361  2014 D BluetoothHeadset: Proxy object disconnected
08-16 18:17:12.219  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:12.221  4150  4150 D A2dpService: Received stop request...Stopping profile...
08-16 18:17:12.221  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:12.222  4150  4183 D A2dpStateMachine: Exit Disconnected: -1
08-16 18:17:12.223   872   872 D BluetoothA2dp: Proxy object disconnected
08-16 18:17:12.224  3923  3923 D HeadsetProfile: Bluetooth service disconnected
,08-16 18:17:12.227  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,08-16 18:17:12.227  1361  1361 D BluetoothA2dp: Proxy object disconnected
,08-16 18:17:12.228  4150  4150 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:12.228  4150  4150 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:12.228  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:12.228  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:12.229  4150  4150 D HidService: Received stop request...Stopping profile...
,08-16 18:17:12.229  4150  4150 D HidService: Stopping Bluetooth HidService
08-16 18:17:12.230  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 18:17:12.230  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 18:17:12.232  4150  4150 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 18:17:12.232  4150  4150 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 18:17:12.232  4150  4150 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:12.232  4150  4150 V BluetoothAdapterState: isTurningOn()=false
,08-16 18:17:12.232  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 18:17:12.232  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:12.233  4150  4172 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 18:17:12.233  4150  4172 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:12.233  4150  4172 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:12.233  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 18:17:12.233  4150  4166 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-16 18:17:12.234  4150  4150 D HealthService: Received stop request...Stopping profile...
,08-16 18:17:12.236  4150  4172 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 18:17:12.236  4150  4172 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:12.237  4150  4172 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:17:12.237  4150  4172 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:17:12.237  4150  4172 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 18:17:12.237  4150  4172 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 18:17:12.237  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 18:17:12.239  4150  4150 D PanService: Received stop request...Stopping profile...
08-16 18:17:12.241  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:17:12.241  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 18:17:12.242  3923  3923 D DockEventReceiver: finishStartingService: stopping service
08-16 18:17:12.243  3923  3923 D BluetoothA2dp: Proxy object disconnected
,08-16 18:17:12.243  3923  3923 D BluetoothInputDevice: Proxy object disconnected
08-16 18:17:12.244  4150  4150 D BluetoothMapService: Received stop request...Stopping profile...
08-16 18:17:12.244  4150  4150 D BluetoothMapService: stop()
08-16 18:17:12.245  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 18:17:12.245  4150  4150 D BluetoothMapAppObserver: deinitObservers()
08-16 18:17:12.245  4150  4150 D BluetoothMapAppObserver: removeReceiver()
08-16 18:17:12.245  3923  3923 D HidProfile: Bluetooth service disconnected
08-16 18:17:12.245  3923  3923 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 18:17:12.245  3923  3923 D PanProfile: Bluetooth service disconnected
,08-16 18:17:12.249  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 18:17:12.249  1361  1361 D MapProfile: Bluetooth service disconnected
08-16 18:17:12.249  4150  4150 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:12.249  4150  4150 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:12.249  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:12.249  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:12.249  3923  3923 D BluetoothMap: Proxy object disconnected
08-16 18:17:12.249  3923  3923 D MapProfile: Bluetooth service disconnected
08-16 18:17:12.250  4150  4150 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 18:17:12.250  4150  4150 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 18:17:12.250  4150  4150 V BluetoothAdapterState: isTurningOff()=true
,08-16 18:17:12.250  4150  4150 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:12.250  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:12.250  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:12.250  4150  4150 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 18:17:12.251  4150  4166 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 18:17:12.251  4150  4150 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 18:17:12.251  4150  4166 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 18:17:12.251  4150  4150 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:12.252  4150  4150 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:12.252  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:12.252  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:12.253  4150  4150 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 18:17:12.253  4150  4150 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 18:17:12.258  1361  1361 D BluetoothPbap: Proxy object disconnected
,08-16 18:17:12.258  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-16 18:17:12.259  3923  3923 D BluetoothPbap: Proxy object disconnected
08-16 18:17:12.259  3923  3923 D PbapServerProfile: Bluetooth service disconnected
,08-16 18:17:12.259  4150  4150 D BluetoothMapService: MAP Service closeService in
,08-16 18:17:12.259  4150  4150 V BluetoothAdapterState: isTurningOff()=true
08-16 18:17:12.260  4150  4150 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:12.260  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:12.260  4150  4150 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:12.260  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 18:17:12.260  4150  4162 D BluetoothAdapterProperties: Setting state to 15
08-16 18:17:12.260  4150  4150 D BluetoothMapService: cleanup()
08-16 18:17:12.260  4150  4150 D BluetoothMapService: MAP Service closeService in
08-16 18:17:12.260  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 18:17:12.261  4150  4162 I BluetoothAdapterState: Entering BleOnState
,08-16 18:17:12.265  3923  3934 D BluetoothPan: onBluetoothStateChange on: false
,08-16 18:17:12.266  3923  3934 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:12.267  1361  1379 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 18:17:12.267  3923  3934 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:17:12.268   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 18:17:12.268  1361  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 18:17:12.268   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:12.268   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:12.268   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:12.269  1361  2014 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:12.269  3923  3935 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 18:17:12.269  1914  1925 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 18:17:12.270  1361  1379 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 18:17:12.270  3923  3934 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 18:17:12.271  3923  3935 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:17:12.271  1361  1373 D BluetoothPan: onBluetoothStateChange on: false
08-16 18:17:12.272  1361  2014 D BluetoothMap: onBluetoothStateChange: up=false
08-16 18:17:12.272  4150  4162 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 18:17:12.272  4150  4162 D BluetoothAdapterProperties: Setting state to 16
08-16 18:17:12.273  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-16 18:17:12.273  4150  4162 D BluetoothAdapterProperties: onBleDisable
,08-16 18:17:12.273  4150  4163 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 18:17:12.273  4150  4162 I BluetoothAdapterState: Entering PendingCommandState
08-16 18:17:12.275  4150  4172 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 18:17:12.275  4150  4172 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 18:17:12.276  4150  4166 D BluetoothAdapterProperties: Scan Mode:20
08-16 18:17:12.277  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:12.278  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:12.279  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:12.280  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:12.286  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:17:12.289  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:17:12.290  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:17:12.476  4150  4166 I bt_hci  : shut_down
,08-16 18:17:12.477  4150  4170 D bt_hwcfg: hw_epilog_process
,08-16 18:17:12.490  4150  4170 I bt_vendor: low_power_mode_cb
,08-16 18:17:12.517  4150  4170 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 18:17:12.517  4150  4170 I bt_vendor: epilog_cb
08-16 18:17:12.517  4150  4170 I bt_hci  : epilog_finished_callback
,08-16 18:17:12.524  4150  4166 I bt_hci_h4: hal_close
,08-16 18:17:12.525  4150  4166 I bt_userial_vendor: device fd = 51 close
,08-16 18:17:12.660  4150  4163 D bt_stack_manager: event_shut_down_stack finished.
,08-16 18:17:12.661  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 18:17:12.667  4150  4162 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 18:17:12.667  4150  4150 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 18:17:12.668  4150  4150 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 18:17:12.669  4150  4150 D BtGatt.GattService: stop()
,08-16 18:17:12.669  4150  4150 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 18:17:12.674  4150  4150 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:12.674  4150  4150 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:12.674  4150  4150 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:12.675  4150  4150 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 18:17:12.675  4150  4162 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 18:17:12.676  4150  4162 D BluetoothAdapterProperties: Setting state to 10
08-16 18:17:12.677  4150  4162 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 18:17:12.678  4150  4162 I BluetoothAdapterState: Entering OffState
,08-16 18:17:12.683   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 18:17:12.704  4150  4150 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 18:17:12.704  4150  4150 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 18:17:12.704  4150  4163 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 18:17:12.708  4150  4150 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 18:17:12.714  4150  4163 D bt_stack_manager: event_clean_up_stack finished.
,08-16 18:17:12.719  4150  4150 I art     : System.exit called, status: 0
,08-16 18:17:12.720  4150  4150 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 18:17:12.766   872  2109 I ActivityManager: Process com.android.bluetooth (pid 4150) has died
,08-16 18:17:13.614   872  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-16 18:17:15.180  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:17:15.181  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:18.189  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:17:18.190  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8316284 added. We now have 6 listener(s)
,08-16 18:17:18.190  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:17:18.194  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:17:18.194  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f235a6d added. We now have 7 listener(s)
,08-16 18:17:18.195  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:18.196  3867  3913 I System.out: IsBluetoothEnabled
,08-16 18:17:18.207  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:18.216  1524  2194 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 18:17:18.254   872   889 I ActivityManager: Start proc 4211:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 18:17:18.397  4211  4211 D AdapterServiceConfig: Adding HeadsetService
,08-16 18:17:18.398  4211  4211 D AdapterServiceConfig: Adding A2dpService
,08-16 18:17:18.399  4211  4211 D AdapterServiceConfig: Adding HidService
,08-16 18:17:18.400  4211  4211 D AdapterServiceConfig: Adding HealthService
,08-16 18:17:18.401  4211  4211 D AdapterServiceConfig: Adding PanService
08-16 18:17:18.402  4211  4211 D AdapterServiceConfig: Adding GattService
,08-16 18:17:18.402  4211  4211 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 18:17:18.436   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e69280c:true
,08-16 18:17:18.436  4211  4211 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 18:17:18.440  4211  4211 I bt_bluedroid: init
,08-16 18:17:18.440  4211  4223 I BluetoothAdapterState: Entering OffState
,08-16 18:17:18.445  4211  4224 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 18:17:18.445  4211  4224 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 18:17:18.445  4211  4224 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 18:17:18.446  4211  4224 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 18:17:18.449  4211  4211 I bt_bluedroid: get_profile_interface socket
,08-16 18:17:18.451  4211  4211 I bt_bluedroid: get_profile_interface sdp
,08-16 18:17:18.452  4211  4227 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 18:17:18.453  4211  4227 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 18:17:18.455  4211  4222 I bt_bluedroid: config_hci_snoop_log
,08-16 18:17:18.456   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 18:17:18.462  4211  4223 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 18:17:18.462  4211  4223 D BluetoothAdapterProperties: Setting state to 14
08-16 18:17:18.463  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-16 18:17:18.464  4211  4223 D BluetoothBondStateMachine: make
,08-16 18:17:18.468  4211  4228 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 18:17:18.472  4211  4223 I BluetoothAdapterState: Entering PendingCommandState
,08-16 18:17:18.474  4211  4211 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 18:17:18.479  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:18.480  4211  4211 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 18:17:18.481  4211  4211 D BtGatt.GattService: Received start request. Starting profile...
08-16 18:17:18.481  4211  4211 D BtGatt.GattService: start()
08-16 18:17:18.481  4211  4211 I bt_bluedroid: get_profile_interface gatt
,08-16 18:17:18.482  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:18.482  4211  4211 D BtGatt.AdvertiseManager: advertise manager created
,08-16 18:17:18.492  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:18.492  4211  4211 V BluetoothAdapterState: isTurningOn()=false
08-16 18:17:18.492  4211  4211 V BluetoothAdapterState: isBleTurningOn()=true
08-16 18:17:18.492  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:18.493  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 18:17:18.493  4211  4223 I bt_bluedroid: enable
08-16 18:17:18.494  4211  4224 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 18:17:18.495  4211  4224 I bt_hci  : start_up
,08-16 18:17:18.508  4211  4224 I bt_vendor: alloc value 0xb3a70189
08-16 18:17:18.508  4211  4224 I bt_vendor: init
,08-16 18:17:18.508  4211  4224 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 18:17:18.508  4211  4224 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 18:17:18.613  4211  4224 D bt_hci  : start_up starting async portion
,08-16 18:17:18.614  4211  4231 I bt_hci  : event_finish_startup
,08-16 18:17:18.614  4211  4231 I bt_hci_h4: hal_open
,08-16 18:17:18.614  4211  4231 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 18:17:18.623  4211  4231 I bt_userial_vendor: device fd = 51 open
,08-16 18:17:18.657  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 18:17:18.688  4211  4231 D bt_hwcfg: Chipset BCM4354A2
,08-16 18:17:18.689  4211  4231 D bt_hwcfg: Target name = [BCM4354A2]
08-16 18:17:18.690  4211  4231 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 18:17:19.350  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 18:17:19.352  4211  4231 D bt_hwcfg: Settlement delay -- 100 ms
08-16 18:17:19.352  4211  4231 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 18:17:19.469  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 18:17:19.470  4211  4231 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 18:17:19.500  4211  4231 I bt_hwcfg: vendor lib fwcfg completed
,08-16 18:17:19.500  4211  4231 I bt_vendor: firmware callback
08-16 18:17:19.500  4211  4231 I bt_hci  : firmware_config_callback
,08-16 18:17:19.511  4211  4233 I bt_btu  : btu_task pending for preload complete event
,08-16 18:17:19.512  4211  4233 I bt_btu_task: Bluetooth chip preload is complete
,08-16 18:17:19.512  4211  4233 I bt_btu  : btu_task received preload complete event
,08-16 18:17:19.522  4211  4233 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 18:17:19.522  4211  4233 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 18:17:19.522  4211  4233 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 18:17:19.523  4211  4233 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 18:17:19.523  4211  4233 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 18:17:19.523  4211  4233 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 18:17:19.523  4211  4233 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 18:17:19.524  4211  4233 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 18:17:19.524  4211  4233 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 18:17:19.524  4211  4233 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 18:17:19.525  4211  4233 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 18:17:19.525  4211  4233 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 18:17:19.525  4211  4233 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 18:17:19.525  4211  4233 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 18:17:19.526  4211  4233 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 18:17:19.658  4211  4233 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39edd9d
,08-16 18:17:19.658  4211  4233 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39edd9d 
,08-16 18:17:19.668  4211  4227 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 18:17:19.670  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 18:17:19.670  4211  4227 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 18:17:19.676  4211  4227 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 18:17:19.683  4211  4227 D BluetoothAdapterProperties: Scan Mode:20
,08-16 18:17:19.684  4211  4227 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:17:19.684  4211  4227 D bt_hci  : do_postload posting postload work item
,08-16 18:17:19.685  4211  4231 I bt_hci  : event_postload
08-16 18:17:19.685  4211  4231 I bt_vendor: sco_config_cb
08-16 18:17:19.685  4211  4231 I bt_hci  : sco_config_callback postload finished.
,08-16 18:17:19.688  4211  4227 D bt_bte_conf: Device ID record 1 : primary
,08-16 18:17:19.688  4211  4227 D bt_bte_conf:   vendorId            = 000f
08-16 18:17:19.688  4211  4227 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 18:17:19.689  4211  4227 D bt_bte_conf:   product             = 1200
08-16 18:17:19.689  4211  4227 D bt_bte_conf:   version             = 1436
08-16 18:17:19.689  4211  4227 D bt_bte_conf:   clientExecutableURL = 
08-16 18:17:19.689  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:19.689  4211  4227 D bt_bte_conf:   serviceDescription  = 
08-16 18:17:19.690  4211  4227 D bt_bte_conf:   documentationURL    = 
08-16 18:17:19.690  4211  4227 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 18:17:19.691  4211  4224 D bt_stack_manager: event_start_up_stack finished
08-16 18:17:19.691  4211  4231 I bt_vendor: low_power_mode_cb
08-16 18:17:19.692  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 18:17:19.693  4211  4223 D BluetoothAdapterProperties: Setting state to 15
08-16 18:17:19.693  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 18:17:19.694  4211  4223 I BluetoothAdapterState: Entering BleOnState
,08-16 18:17:19.698  4211  4223 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 18:17:19.698  4211  4223 D BluetoothAdapterProperties: Setting state to 11
08-16 18:17:19.698  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 18:17:19.708  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:19.709  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:19.709  4211  4211 D HeadsetService: Received start request. Starting profile...
08-16 18:17:19.716  4211  4211 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 18:17:19.716  4211  4211 D HeadsetStateMachine: make
,08-16 18:17:19.724  4211  4223 I BluetoothAdapterState: Entering PendingCommandState
,08-16 18:17:19.727  4211  4211 D HeadsetStateMachine: max_hf_connections = 1
,08-16 18:17:19.727  4211  4211 I bt_bluedroid: get_profile_interface handsfree
,08-16 18:17:19.729  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 18:17:19.729  4211  4227 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 18:17:19.734  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:17:19.734  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:19.735  4211  4211 D A2dpService: Received start request. Starting profile...
,08-16 18:17:19.737  4211  4211 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 18:17:19.737  4211  4211 I bt_bluedroid: get_profile_interface avrcp
,08-16 18:17:19.750  4211  4211 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 18:17:19.751  4211  4211 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 18:17:19.751  4211  4211 D A2dpStateMachine: make
,08-16 18:17:19.753  4211  4211 I bt_bluedroid: get_profile_interface a2dp
,08-16 18:17:19.754  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 18:17:19.757  4211  4242 D A2dpStateMachine: Enter Disconnected: -2
,08-16 18:17:19.758  4211  4211 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 18:17:19.759  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:19.760  4211  4211 D HidService: Received start request. Starting profile...
,08-16 18:17:19.760  4211  4211 I bt_bluedroid: get_profile_interface hidhost
,08-16 18:17:19.760  4211  4227 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cf3e5
08-16 18:17:19.761  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 18:17:19.761  4211  4211 D HidService: setHidService(): set to: null
,08-16 18:17:19.762  4211  4211 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 18:17:19.762  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:19.763  4211  4211 D HealthService: Received start request. Starting profile...
,08-16 18:17:19.765  4211  4211 I bt_bluedroid: get_profile_interface health
,08-16 18:17:19.765  4211  4211 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 18:17:19.766  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
08-16 18:17:19.767  4211  4211 D PanService: Received start request. Starting profile...
,08-16 18:17:19.767  4211  4211 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 18:17:19.767  4211  4211 I bt_bluedroid: get_profile_interface pan
08-16 18:17:19.768  4211  4227 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 18:17:19.771  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771
,08-16 18:17:19.772  4211  4211 D BluetoothMapService: Received start request. Starting profile...
08-16 18:17:19.772  4211  4211 D BluetoothMapService: start()
,08-16 18:17:19.774  4211  4211 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 18:17:19.775  4211  4211 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 18:17:19.775  4211  4211 D BluetoothMapAppObserver: createReceiver()
,08-16 18:17:19.776  4211  4211 D BluetoothMapAppObserver: initObservers()
,08-16 18:17:19.776  4211  4211 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 18:17:19.785  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:19.785  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:19.785  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 18:17:19.785  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:19.788  4211  4240 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 18:17:19.790  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:19.790  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 18:17:19.791  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-16 18:17:19.792  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 18:17:19.793  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 18:17:19.793  4211  4223 D BluetoothAdapterProperties: ScanMode =  20
,08-16 18:17:19.793  4211  4223 D BluetoothAdapterProperties: State =  11
,08-16 18:17:19.794  4211  4223 D BluetoothAdapterProperties: Setting state to 12
,08-16 18:17:19.794  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 18:17:19.795  4211  4223 I BluetoothAdapterState: Entering OnState
,08-16 18:17:19.796  3923  3934 D BluetoothPan: onBluetoothStateChange on: true
,08-16 18:17:19.797  4211  4227 D BluetoothAdapterProperties: Scan Mode:21
,08-16 18:17:19.797  4211  4227 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 18:17:19.803  4211  4211 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 18:17:19.803  3923  3935 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:19.804  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:19.804  4211  4211 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 18:17:19.804  1361  2014 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 18:17:19.807  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:19.807  4211  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:17:19.808  3923  3935 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 18:17:19.809  4211  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:17:19.810  4211  4211 D ObexServerSockets: Succeed to create listening sockets 
,08-16 18:17:19.810  4211  4211 D ObexServerSockets0: startAccept()
08-16 18:17:19.810  4211  4211 D ObexServerSockets0: prepareForNewConnect()
08-16 18:17:19.811   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:17:19.812  1361  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 18:17:19.812  4211  4211 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 18:17:19.812  4211  4211 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 18:17:19.814  4211  4248 D ObexServerSockets0: Accepting socket connection...
08-16 18:17:19.815   872   872 D BluetoothA2dp: Proxy object connected
08-16 18:17:19.815  3923  3923 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 18:17:19.815  3923  3923 D PanProfile: Bluetooth service connected
08-16 18:17:19.815  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 18:17:19.815  3923  3923 D BluetoothA2dp: Proxy object connected
08-16 18:17:19.816   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:19.816   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:19.816   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:19.816  1361  2014 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:19.817  4211  4249 D ObexServerSockets0: Accepting socket connection...
08-16 18:17:19.818  3923  4247 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 18:17:19.820  1914  2087 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 18:17:19.821  1361  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 18:17:19.824  3923  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 18:17:19.824  1361  1361 D BluetoothInputDevice: Proxy object connected
08-16 18:17:19.824  1361  1361 D HidProfile: Bluetooth service connected
,08-16 18:17:19.826  3923  4247 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 18:17:19.828  3923  3923 D BluetoothInputDevice: Proxy object connected
,08-16 18:17:19.828  3923  3923 D HidProfile: Bluetooth service connected
,08-16 18:17:19.829  1361  2014 D BluetoothPan: onBluetoothStateChange on: true
08-16 18:17:19.830  3923  3923 D BluetoothMap: Proxy object connected
08-16 18:17:19.830  3923  3923 D MapProfile: Bluetooth service connected
08-16 18:17:19.830  3923  3923 D BluetoothMap: getConnectedDevices()
,08-16 18:17:19.831  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 18:17:19.831  1361  1361 D PanProfile: Bluetooth service connected
08-16 18:17:19.832  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 18:17:19.834  1361  1361 D BluetoothMap: Proxy object connected
,08-16 18:17:19.834  1361  1361 D MapProfile: Bluetooth service connected
08-16 18:17:19.834  1361  1361 D BluetoothMap: getConnectedDevices()
08-16 18:17:19.835   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 18:17:19.837  4211  4211 D BluetoothMapService: onReceive
08-16 18:17:19.837  4211  4211 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 18:17:19.838  4211  4211 D BluetoothMapService: STATE_ON
,08-16 18:17:19.838  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:19.843  3923  3923 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 18:17:19.850  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 18:17:19.851  3923  3923 D DockEventReceiver: finishStartingService: stopping service
,08-16 18:17:19.864  1361  1361 D BluetoothPbap: Proxy object connected
08-16 18:17:19.864  3923  3923 D BluetoothPbap: Proxy object connected
08-16 18:17:19.864  3923  3923 D PbapServerProfile: Bluetooth service connected
08-16 18:17:19.864  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-16 18:17:19.871  4211  4211 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 18:17:19.871  4211  4211 D ObexServerSockets0: prepareForNewConnect()
,08-16 18:17:19.876  4211  4254 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:17:19.895  4211  4258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 18:17:19.897  4211  4258 I BtOppRfcommListener: Accept thread started.
,08-16 18:17:19.906  3923  4247 D BluetoothHeadset: Proxy object connected
,08-16 18:17:19.906   872   872 D BluetoothHeadset: Proxy object connected
08-16 18:17:19.907   872   872 D BluetoothHeadset: Proxy object connected
08-16 18:17:19.907  3923  3923 D HeadsetProfile: Bluetooth service connected
08-16 18:17:19.907  1914  1925 D BluetoothHeadset: Proxy object connected
08-16 18:17:19.907   872   872 D BluetoothHeadset: Proxy object connected
,08-16 18:17:19.908  1361  2014 D BluetoothHeadset: Proxy object connected
08-16 18:17:19.908  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 18:17:19.916   872   889 D BluetoothHeadset: Proxy object connected
,08-16 18:17:19.916   872   889 D BluetoothHeadset: Proxy object connected
,08-16 18:17:19.916   872   889 D BluetoothHeadset: Proxy object connected
08-16 18:17:19.917  1361  1379 D BluetoothHeadset: Proxy object connected
08-16 18:17:19.917  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 18:17:19.922  1914  1926 D BluetoothHeadset: Proxy object connected
,08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:20.231  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:20.238  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:20.241  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:20.241  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e8e6a2 added. We now have 8 listener(s)
08-16 18:17:20.241  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:17:20.247   872  2108 D WifiService: setWifiEnabled: false pid=3867, uid=10000
08-16 18:17:20.247   872  2108 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:17:20.259  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:20.260   872  2109 D WifiService: setWifiEnabled: true pid=3867, uid=10000
08-16 18:17:20.260   872  2109 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 18:17:20.271   872  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:20.297  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:20.304  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:20.307   872  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-16 18:17:20.309   872  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 18:17:20.310   872  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000,
,08-16 18:17:20.311   872  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 18:17:20.311   872  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 18:17:20.311   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 18:17:20.311   872  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 18:17:20.325   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 18:17:20.326   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 18:17:20.326   372   870 D CommandListener: Setting iface cfg
,08-16 18:17:20.327   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-16 18:17:20.327   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 18:17:20.383   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
08-16 18:17:20.383   872  1305 E native  : do suspend true
,08-16 18:17:20.384   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 18:17:20.427   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:21.284  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:21.290  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:21.302  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 18:17:21.304  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 18:17:21.311  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2a109ad Bundle[{}]
,08-16 18:17:21.314  3867  3913 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 18:17:21.315  3867  3913 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 18:17:21.319  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 18:17:21.322  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 18:17:21.324  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 18:17:21.327  3867  3913 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 18:17:21.340  3867  3913 I System.out: Running OutgoingSocketThread
,08-16 18:17:21.343  3867  4266 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 427)
,08-16 18:17:21.345  3867  4266 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45164
08-16 18:17:21.345  3867  4266 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 18:17:21.812   872  1305 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 18:17:21.922   872  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.44 rxSuccessRate=11.50 delta 1000 -> 994
,08-16 18:17:21.923   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 18:17:21.924   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:17:21.946   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 18:17:22.018   872  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 18:17:22.023  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 18:17:22.343  3867  3913 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 428)
,08-16 18:17:22.344  3867  3913 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 428)
,08-16 18:17:22.354  3867  3913 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 433)
,08-16 18:17:22.356  3867  3913 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 18:17:22.357  3867  3913 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-16 18:17:22.365  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:17:22.365  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbbf33 added. We now have 2 listener(s)
,08-16 18:17:22.371  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 18:17:22.372  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.372  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.373  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.373  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a422f0 added. We now have 9 listener(s)
08-16 18:17:22.373  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:17:22.374  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:17:22.381  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:22.389  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:22.395  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:22.395  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:17:22.396  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.396  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@812caee added. We now have 3 listener(s)
,08-16 18:17:22.397  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.400  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.403  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 18:17:22.403  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.403  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.404  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.404  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be91b8f added. We now have 10 listener(s)
,08-16 18:17:22.405  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.405  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:22.405  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:22.406  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:22.406  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:22.406  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.407  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.407  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 18:17:22.407  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bbbf33 removed from the list
,08-16 18:17:22.408  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:22.408  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a422f0 removed from the list
08-16 18:17:22.408  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 18:17:22.408  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:22.410  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:22.410  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.413  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.413  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.413  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.413  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a422f0 not in the list
08-16 18:17:22.413  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.414  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.416  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.417  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.417  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.417  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be91b8f removed from the list
08-16 18:17:22.418  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:22.418  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.418  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.418  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.419  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@812caee removed from the list
08-16 18:17:22.421  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.422  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8407e1c added. We now have 2 listener(s)
,08-16 18:17:22.428  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 18:17:22.428  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.429  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.430  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:17:22.430  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8a6a25 added. We now have 9 listener(s)
,08-16 18:17:22.430  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.432  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:17:22.437  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:22.444  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:22.450  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 18:17:22.450  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 18:17:22.450  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:17:22.451  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:17:22.451  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce5e1ab added. We now have 3 listener(s)
08-16 18:17:22.453  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:22.453  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 18:17:22.453  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:17:22.454  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.454  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.454  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de56008 added. We now have 10 listener(s)
08-16 18:17:22.454  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 18:17:22.454  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 18:17:22.454  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 18:17:22.454  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 18:17:22.454  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:17:22.454  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:17:22.458  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.463  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 18:17:22.463  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:17:22.475  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:17:22.477  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 18:17:22.477  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:17:22.480  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 18:17:22.481  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 18:17:22.484  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:17:22.484  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:17:22.484  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 18:17:22.484  3867  3913 D BluetoothAdapter: STATE_ON
,08-16 18:17:22.488   872  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 18:17:22.488  4211  4222 D BtGatt.GattService: registerClient() - UUID=45cd3162-6a0e-4b78-8060-4494d5640bf5
,08-16 18:17:22.490  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=45cd3162-6a0e-4b78-8060-4494d5640bf5, clientIf=5
,08-16 18:17:22.491  3867  3878 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5,
,08-16 18:17:22.494  4211  4221 D BtGatt.GattService: start scan with filters
,08-16 18:17:22.496   872  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 18:17:22.497   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 18:17:22.497   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:17:22.500  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 18:17:22.501  4211  4230 D BtGatt.ScanManager: handling starting scan
08-16 18:17:22.501  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 18:17:22.501  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:17:22.502  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 18:17:22.502  4211  4230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65e6771,
,08-16 18:17:22.507  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 18:17:22.507  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:17:22.508  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 18:17:22.511  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:17:22.511  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:17:22.511  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:17:22.513  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:17:22.515  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 18:17:22.515  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.516  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:17:22.516  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 18:17:22.517   872  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 18:17:22.518  3867  3913 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 18:17:22.519  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-16 18:17:22.519  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
08-16 18:17:22.519  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.519  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 18:17:22.519  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 18:17:22.519  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 18:17:22.519  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 18:17:22.519  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:17:22.520  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:17:22.520  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 18:17:22.521  3867  3913 D BluetoothAdapter: STATE_ON
,08-16 18:17:22.522  4211  4221 D BtGatt.GattService: stopScan() - queue size =1
,08-16 18:17:22.522  4211  4250 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 18:17:22.523  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 18:17:22.523  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 18:17:22.523  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 18:17:22.523  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:17:22.523  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 18:17:22.524  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:22.525  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:17:22.525  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:17:22.525  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:17:22.525  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.527  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:17:22.527  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:22.527  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:17:22.528   372   870 D CommandListener: Setting iface cfg
08-16 18:17:22.530  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:22.530   872  1305 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 18:17:22.530  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:22.530  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:22.530  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:22.531  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.531  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.531  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 18:17:22.531  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.531  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.531  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8407e1c removed from the list
08-16 18:17:22.531  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.532  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8a6a25 removed from the list
,08-16 18:17:22.532  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:22.532  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.532  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.532  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:22.533  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.533  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.534  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:22.534  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8a6a25 not in the list
,08-16 18:17:22.534  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:22.534  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.535  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.535  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 18:17:22.535  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.535  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de56008 removed from the list
08-16 18:17:22.535  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:22.535  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.535  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.535  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 18:17:22.535  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce5e1ab removed from the list
08-16 18:17:22.536  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.536  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7474b4 added. We now have 2 listener(s)
08-16 18:17:22.538  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 18:17:22.538  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.538  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 18:17:22.539  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 18:17:22.539  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.539  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.539  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5cb8dd added. We now have 9 listener(s)
,08-16 18:17:22.539  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.539  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 18:17:22.540   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-16 18:17:22.543  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:17:22.545  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 18:17:22.545  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:22.545  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:22.545  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
08-16 18:17:22.547  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:22.547  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 18:17:22.547   872  4269 D DhcpClient: Receive thread started
,08-16 18:17:22.548  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:22.550  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.550  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.550  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2db23 added. We now have 3 listener(s)
08-16 18:17:22.551  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 18:17:22.551  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.551  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 18:17:22.552  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 18:17:22.552  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.553  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.553  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.553  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53e2820 added. We now have 10 listener(s)
,08-16 18:17:22.553  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.553  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:17:22.554  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:17:22.554  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:17:22.554  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 18:17:22.554  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 18:17:22.554  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 18:17:22.556  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 18:17:22.556  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.557  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 18:17:22.557  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:17:22.560  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 18:17:22.560  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 18:17:22.560  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:17:22.562  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:17:22.562  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:17:22.562  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:17:22.563  3867  3913 D BluetoothAdapter: STATE_ON
,08-16 18:17:22.564  4211  4239 D BtGatt.GattService: registerClient() - UUID=e7ba6bae-6410-4f8c-90bc-81d99ddf382f
,08-16 18:17:22.564  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=e7ba6bae-6410-4f8c-90bc-81d99ddf382f, clientIf=5
08-16 18:17:22.565  3867  3878 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 18:17:22.565  4211  4222 D BtGatt.GattService: start scan with filters
,08-16 18:17:22.566  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 18:17:22.567  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:17:22.567  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:17:22.567  4211  4230 D BtGatt.ScanManager: handling starting scan
08-16 18:17:22.567  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:17:22.568  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:17:22.569  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:17:22.569  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:17:22.570  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:17:22.572  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 18:17:22.572  3867  3913 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 18:17:22.572  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:22.572  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 18:17:22.572  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:22.572  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:22.572  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:17:22.572  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:22.572  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 18:17:22.572  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.572  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:17:22.573  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.573  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7474b4 removed from the list
,08-16 18:17:22.573  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.573  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5cb8dd removed from the list
08-16 18:17:22.573  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:22.573  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.573  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.573  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 18:17:22.573  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.573  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 18:17:22.574  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.574  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.574  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.574  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d5cb8dd not in the list
08-16 18:17:22.574  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:17:22.574  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:17:22.574  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 18:17:22.574  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:17:22.575  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 18:17:22.575  3867  3913 D BluetoothAdapter: STATE_ON
08-16 18:17:22.575  4211  4250 D BtGatt.GattService: stopScan() - queue size =1
08-16 18:17:22.576  4211  4221 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 18:17:22.576  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 18:17:22.576  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:17:22.576  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 18:17:22.576  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:17:22.577  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 18:17:22.577  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 18:17:22.577  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.577  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
08-16 18:17:22.577  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:22.577  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 18:17:22.577  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:17:22.577  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:17:22.578  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:17:22.578  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.579  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:22.579  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:22.579  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 18:17:22.579  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.579  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.579  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.579  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53e2820 removed from the list
08-16 18:17:22.579  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:22.579  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:22.579  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.579  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.579  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf2db23 removed from the list
08-16 18:17:22.580  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.580  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62da64c added. We now have 2 listener(s)
,08-16 18:17:22.581  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 18:17:22.581  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.581  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.581  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.581  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e32695 added. We now have 9 listener(s)
08-16 18:17:22.581  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.582  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:17:22.584  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:22.586  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:22.587  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 18:17:22.587  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.587  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:22.587  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:17:22.588  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.588  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 18:17:22.589  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e868b9b added. We now have 3 listener(s)
08-16 18:17:22.589  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 18:17:22.591  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 18:17:22.592  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.592  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 18:17:22.592  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.592  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.593  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:17:22.593  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4db38 added. We now have 10 listener(s)
08-16 18:17:22.593  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.594  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:17:22.594  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 18:17:22.594  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 18:17:22.594  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:17:22.594  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 18:17:22.597  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 18:17:22.597  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.597  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
,08-16 18:17:22.598  3867  3913 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 18:17:22.598  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 18:17:22.601  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 18:17:22.601  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 18:17:22.601  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 18:17:22.602  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 18:17:22.602  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.602  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 18:17:22.604  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 18:17:22.604  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 18:17:22.604  3867  3913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 18:17:22.605  3867  3913 D BluetoothAdapter: STATE_ON
,08-16 18:17:22.606  4211  4239 D BtGatt.GattService: registerClient() - UUID=60e59b04-7a75-4dc5-9118-11d9f5eece98
,08-16 18:17:22.606  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=60e59b04-7a75-4dc5-9118-11d9f5eece98, clientIf=5
08-16 18:17:22.606  3867  3877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 18:17:22.607  4211  4250 D BtGatt.GattService: start scan with filters
,08-16 18:17:22.607  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 18:17:22.607  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 18:17:22.609  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 18:17:22.609  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 18:17:22.609  4211  4230 D BtGatt.ScanManager: handling starting scan
08-16 18:17:22.609  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 18:17:22.609  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 18:17:22.611  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 18:17:22.611  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 18:17:22.611  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 18:17:22.612  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 18:17:22.614  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 18:17:22.614  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.615  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 18:17:22.615  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:22.615  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:22.615  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 18:17:22.615  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:22.615  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.615  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 18:17:22.615  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.616  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62da64c removed from the list
,08-16 18:17:22.616  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.616  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e32695 removed from the list
08-16 18:17:22.616  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:22.616  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.616  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.616  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 18:17:22.616  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.616  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.617  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:22.617  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.617  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.617  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e32695 not in the list
08-16 18:17:22.617  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 18:17:22.617  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 18:17:22.617  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 18:17:22.617  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 18:17:22.617  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 18:17:22.618  3867  3913 D BluetoothAdapter: STATE_ON
08-16 18:17:22.618  4211  4250 D BtGatt.GattService: stopScan() - queue size =1
08-16 18:17:22.619  4211  4221 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 18:17:22.619  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 18:17:22.619  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 18:17:22.619  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 18:17:22.619  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 18:17:22.619  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 18:17:22.619  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 18:17:22.620  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.620  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:22.620  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 18:17:22.620  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 18:17:22.620  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 18:17:22.620  3867  3913 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 18:17:22.620  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 18:17:22.620  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.621  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 18:17:22.621  3867  3867 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 18:17:22.621  3867  3867 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 18:17:22.621  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.621  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.622  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.622  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b4db38 removed from the list
08-16 18:17:22.622  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:22.622  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.622  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.622  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.622  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e868b9b removed from the list
08-16 18:17:22.622  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.622  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7872e4 added. We now have 2 listener(s)
,08-16 18:17:22.624  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 18:17:22.624  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.624  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.624  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 18:17:22.624  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a2934d added. We now have 9 listener(s)
08-16 18:17:22.624  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.624  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 18:17:22.625  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 18:17:22.628  3867  3913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 18:17:22.629  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 18:17:22.629  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.629   872  1305 E native  : do suspend false
,08-16 18:17:22.630  3867  3913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 18:17:22.630  3867  3913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 18:17:22.632  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.633  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 18:17:22.633  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 18:17:22.633  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e0d313 added. We now have 3 listener(s)
08-16 18:17:22.633  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 18:17:22.633  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.635  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 18:17:22.635  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 18:17:22.635  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 18:17:22.635  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 18:17:22.635  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bbd950 added. We now have 10 listener(s)
08-16 18:17:22.635  3867  3913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 18:17:22.635  3867  3913 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 18:17:22.635  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:22.635  3867  3913 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 18:17:22.636  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 18:17:22.636  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.636  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 18:17:22.636  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 18:17:22.636  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7872e4 removed from the list
08-16 18:17:22.636  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 18:17:22.636  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a2934d removed from the list
08-16 18:17:22.636  3867  3913 D io.jxcore.node.ConnectivityMonitor: stop
08-16 18:17:22.636  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.636  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 18:17:22.636  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 18:17:22.637  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 18:17:22.637  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 18:17:22.637  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 18:17:22.637  3867  3913 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a2934d not in the list
,08-16 18:17:22.637  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:22.638  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 18:17:22.638  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 18:17:22.638  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 18:17:22.638  3867  3913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-16 18:17:22.638  3867  3913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bbd950 removed from the list
,08-16 18:17:22.638  3867  3913 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 18:17:22.639  3867  3913 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 18:17:22.639  3867  3913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 18:17:22.639  3867  3913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 18:17:22.639  3867  3913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e0d313 removed from the list
,08-16 18:17:22.639  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 18:17:22.639  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.640  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 18:17:22.640  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
08-16 18:17:22.640  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 18:17:22.640   872  1873 D DhcpClient: Broadcasting DHCPDISCOVER
08-16 18:17:22.640  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 18:17:22.641  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 18:17:22.641  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 18:17:22.641  3867  3913 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 18:17:22.645  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 18:17:22.645  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.645  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 18:17:22.646  3867  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
08-16 18:17:22.646  3867  4270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
08-16 18:17:22.646  3867  4270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:17:22.647  3867  4271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: My test thread name)
08-16 18:17:22.648  3867  4271 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: My test thread name)
08-16 18:17:22.648  3867  4271 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 18:17:22.649  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 18:17:22.649  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 18:17:22.649  3867  3913 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 18:17:22.649  3867  3913 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 18:17:22.650  3867  3913 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 18:17:22.650  3867  3913 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 18:17:22.650  3867  3913 D com.test.thalitest.ThaliTestRunner: Total duration: 22923 ms
08-16 18:17:22.651  3867  3913 I jxcore-log: Total number of executed tests:  80
08-16 18:17:22.651  3867  3913 I jxcore-log: 
08-16 18:17:22.651  3867  3913 I jxcore-log: Number of passed tests:  80
08-16 18:17:22.651  3867  3913 I jxcore-log: 
08-16 18:17:22.652  3867  3913 I jxcore-log: Number of failed tests:  0
08-16 18:17:22.652  3867  3913 I jxcore-log: 
08-16 18:17:22.652  3867  ,3913 I jxcore-log: Number of ignored tests:  0
08-16 18:17:22.652  3867  3913 I jxcore-log: 
08-16 18:17:22.652  3867  3913 I jxcore-log: Total duration:  22923
08-16 18:17:22.652  3867  3913 I jxcore-log: 
08-16 18:17:22.653  3867  3913 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 18:17:22.653  3867  3913 I jxcore-log: 
,08-16 18:17:22.660  3867  3867 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-16 18:17:22.661  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.661  3867  3913 I jxcore-log: 
08-16 18:17:22.663  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.663  3867  3913 I jxcore-log: 
08-16 18:17:22.663  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.663  3867  3913 I jxcore-log: 
08-16 18:17:22.664  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.664  3867  3913 I jxcore-log: 
08-16 18:17:22.664  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.664  3867  3913 I jxcore-log: 
08-16 18:17:22.665  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.665  3867  3913 I jxcore-log: 
,08-16 18:17:22.667  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.667  3867  3913 I jxcore-log: 
,08-16 18:17:22.668  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.668  3867  3913 I jxcore-log: 
,08-16 18:17:22.668  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.668  3867  3913 I jxcore-log: 
08-16 18:17:22.669  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.669  3867  3913 I jxcore-log: 
,08-16 18:17:22.669  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.669  3867  3913 I jxcore-log: 
08-16 18:17:22.670  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:17:22.670  3867  3913 I jxcore-log: 
08-16 18:17:22.671  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.671  3867  3913 I jxcore-log: 
08-16 18:17:22.671  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.671  3867  3913 I jxcore-log: 
08-16 18:17:22.671  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.671  3867  3913 I jxcore-log: 
08-16 18:17:22.672  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.672  3867  3913 I jxcore-log: 
08-16 18:17:22.672  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.672  3867  3913 I jxcore-log: 
08-16 18:17:22.673  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.673  3867  3913 I jxcore-log: 
08-16 18:17:22.673  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.673  3867  3913 I jxcore-log: 
08-16 18:17:22.674  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.674  3867  3913 I jxcore-log: 
08-16 18:17:22.674  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.674  3867  3913 I jxcore-log: 
08-16 18:17:22.675  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.675  3867  3913 I jxcore-log: 
,08-16 18:17:22.675  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.675  3867  3913 I jxcore-log: 
08-16 18:17:22.676  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.676  3867  3913 I jxcore-log: 
08-16 18:17:22.676  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.676  3867  3913 I jxcore-log: 
08-16 18:17:22.676   872  4269 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
08-16 18:17:22.677   872  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 18:17:22.677  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 18:17:22.677  3867  3913 I jxcore-log: 
08-16 18:17:22.677  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.677  3867  3913 I jxcore-log: 
08-16 18:17:22.678   872  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
08-16 18:17:22.678  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.678  3867  3913 I jxcore-log: 
,08-16 18:17:22.678  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.678  3867  3913 I jxcore-log: 
08-16 18:17:22.679  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.679  3867  3913 I jxcore-log: 
,08-16 18:17:22.679  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.679  3867  3913 I jxcore-log: 
,08-16 18:17:22.680  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.680  3867  3913 I jxcore-log: 
08-16 18:17:22.680  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 18:17:22.680  3867  3913 I jxcore-log: 
,08-16 18:17:22.689   872  4269 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 18:17:22.689   872  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 18:17:22.690   372   870 D CommandListener: Setting iface cfg
,08-16 18:17:22.693   872  1873 D DhcpClient: Scheduling renewal in 86399s
08-16 18:17:22.694   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 18:17:22.694   872  1305 E native  : do suspend true
,08-16 18:17:22.704   872  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 18:17:22.705   872  1305 D WifiConfigStore: No blacklist allowed without epno enabled
08-16 18:17:22.705   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 18:17:22.707   872  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 18:17:22.711   872  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 18:17:22.745   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 18:17:22.745   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 18:17:22.746   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 18:17:22.747   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 18:17:22.748   872  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 18:17:22.755   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 18:17:22.760   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 18:17:22.760   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 18:17:22.760   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 18:17:22.760   872  1308 D ConnectivityService:    accepting network in place of null
08-16 18:17:22.760   872  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 18:17:22.761   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 18:17:22.763   872  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 18:17:22.766   872  4268 D NetlinkSocketObserver: NeighborEvent{elapsedMs=251173, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 18:17:22.784   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:22.808   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 18:17:22.811   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 18:17:22.811   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:22.815   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 18:17:22.815   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 18:17:22.819  3867  3867 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 18:17:22.821  3867  3867 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 18:17:22.822  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 18:17:22.822  3867  3913 I jxcore-log: 
,08-16 18:17:22.834   872  4267 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:80a::200e
,08-16 18:17:22.846  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 18:17:22.853  1738  1738 D SystemUpdateService: onCreate
,08-16 18:17:22.857  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 18:17:22.885  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 18:17:22.887  1738  2419 I iu.UploadsManager: num queued entries: 0
,08-16 18:17:22.888  1738  2419 I iu.UploadsManager: num updated entries: 0
,08-16 18:17:22.893  1738  4282 I SystemUpdateService: active receiver: enabled
,08-16 18:17:22.897  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 18:17:22.898  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 18:17:22.899  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 18:17:22.902  1738  4285 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 18:17:22.902  1738  4285 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 18:17:22.905  4004  4004 D SprintDMHelper: simOperator: 
08-16 18:17:22.905  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 18:17:22.907   872  4267 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 16:17:22 GMT], X-Android-Received-Millis=[1471364242906], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471364242876]}
,08-16 18:17:22.907   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 18:17:22.907   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 18:17:22.908   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 18:17:22.908   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 18:17:22.924  1738  4285 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 18:17:22.938  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 18:17:22.939  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 18:17:22.945  1738  2419 I iu.SyncManager: NEXT; no task
,08-16 18:17:22.946  1738  4282 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 18:17:22.965  1738  4282 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 18:17:22.965  1738  4282 I SystemUpdateService: now status is 0 (complete)
,08-16 18:17:22.965  1738  4282 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 18:17:22.965  1738  4282 I SystemUpdateService: file has been verified
08-16 18:17:22.966  1738  4282 I SystemUpdateService: OTA package size = 12249756
,08-16 18:17:22.979  1738  4282 I SystemUpdateService: showing system update notification
,08-16 18:17:22.990  1524  2309 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 18:17:22.991  1524  2309 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 18:17:22.991  1524  2309 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 18:17:22.991  1524  2309 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 18:17:23.028  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:17:23.029  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:17:23.029  3867  3913 I jxcore-log: 
,08-16 18:17:23.030  1738  1738 D SystemUpdateService: onDestroy
,08-16 18:17:23.039  1738  4285 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-16 18:17:23.048  3029  4283 V KeepSync: Connecting to GoogleApiClient
,08-16 18:17:23.048   872  1372 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 18:17:23.079  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:17:23.080  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:17:23.080  3867  3913 I jxcore-log: 
,08-16 18:17:23.088  1524  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 18:17:23.089  1524  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 18:17:23.089  1524  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 18:17:23.089  1524  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 18:17:23.102  1738  4294 V BaseAuthAsyncOperation: access token request failed
,08-16 18:17:23.103  3029  4283 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 18:17:23.121  3867  3867 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 18:17:23.123  3867  3913 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 18:17:23.123  3867  3913 I jxcore-log: 
,08-16 18:17:23.151  1524  3479 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 18:17:23.151  1524  3479 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-16 18:17:23.151  1524  3479 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 18:17:23.151  1524  3479 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 18:17:23.170  3029  4283 E KeepSync: IOException
08-16 18:17:23.170  3029  4283 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 18:17:23.170  3029  4283 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 18:17:23.170  3029  4283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 18:17:23.170  3029  4283 E KeepSync: 	... 10 more
,08-16 18:17:23.170  3029  4283 W KeepSync: Sync result 2
,08-16 18:17:23.175   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 247863, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 18:17:23.280  4273  4273 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 18:17:23.285  4273  4273 D AndroidRuntime: CheckJNI is OFF
,08-16 18:17:23.327  4273  4273 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 18:17:23.374  4273  4273 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 18:17:23.399  4273  4273 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 18:17:23.408   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 18:17:23.409   872   885 I ActivityManager: Killing 3867:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 18:17:23.513   872  1941 D GraphicsStats: Buffer count: 2
,08-16 18:17:23.513   872  1934 I WindowState: WIN DEATH: Window{d1c08d3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 18:17:23.515   872  1307 D WifiService: Client connection lost with reason: 4
,08-16 18:17:23.531   872   895 W PackageSettings: Skipping PackageSetting{635675a com.example.hello/10273} due to missing metadata
,08-16 18:17:23.580   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 18:17:23.580   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 18:17:23.580   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-16 18:17:23.580   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 18:17:23.580   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:23.580   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:23.580   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 18:17:23.580   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 18:17:23.581   872   885 I ActivityManager:   Force finishing activity ActivityRecord{95becdc u0 com.test.thalitest/.MainActivity t2}
,08-16 18:17:23.582   872   895 I art     : Starting a blocking GC Explicit
,08-16 18:17:23.592   872  1941 W ActivityManager: Spurious death for ProcessRecord{dee8145 0:com.test.thalitest/u0a0}, curProc for 3867: null
,08-16 18:17:23.654   872   895 I art     : Explicit concurrent mark sweep GC freed 53003(3MB) AllocSpace objects, 9(224KB) LOS objects, 33% free, 29MB/43MB, paused 873us total 70.762ms
,08-16 18:17:23.703   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 18:17:23.706  4273  4273 I art     : System.exit called, status: 0
08-16 18:17:23.707  4273  4273 I AndroidRuntime: VM exiting with result code 0.
,08-16 18:17:23.716   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 18:17:23.737   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-16 18:17:23.740  1847  1847 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 18:17:23.742  4211  4211 D BluetoothMapAppObserver: onReceive
08-16 18:17:23.742  4211  4211 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 18:17:23.742  2175  2290 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 18:17:23.743   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 18:17:23.745  3640  3640 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 18:17:23.789  1914  1914 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-16 18:17:23.791   872  2109 I ActivityManager: Start proc 4307:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-16 18:17:23.799  1847  4305 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 18:17:23.812  1847  4305 I Decoder : createOrResetDecoder
,08-16 18:17:23.829   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 18:17:23.837  1524  1524 I ConfigService: onCreate
,08-16 18:17:23.839  4307  4307 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 18:17:23.853   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 18:17:23.853   872   884 E PackageManager: Failed to write settings, restoring backup
08-16 18:17:23.853   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 18:17:23.853   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 18:17:23.853   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 18:17:23.853   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 18:17:23.853   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 18:17:23.853   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:23.853   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:23.853   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:17:23.854   872  1954 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3867 uid 10000
08-16 18:17:23.855   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-16 18:17:23.855   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 18:17:23.855   872   885 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 18:17:23.855   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:23.855   872   885 E DropBoxManagerService: 	... 13 more
,08-16 18:17:23.860  1927  2013 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 18:17:23.864  1847  1847 I Keyboard.Facilitator: onFinishInput()
,08-16 18:17:23.872  1524  4319 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-16 18:17:23.872   872  2111 I ActivityManager: Start proc 4320:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-16 18:17:23.873  1927  2013 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 18:17:23.873  1927  2013 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1927
08-16 18:17:23.873  1927  2013 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:23.873  1927  2013 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:17:23.876   872  2109 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 18:17:23.877   872  4326 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:17:23.877   872  4326 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:23.877   872  4326 E DropBoxManagerService: 	... 5 more
,08-16 18:17:23.884  1927  2013 I Process : Sending signal. PID: 1927 SIG: 9
,08-16 18:17:23.913  1847  4305 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 18:17:23.935  1847  4305 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 18:17:23.937  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-16 18:17:23.938  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 18:17:23.950   872  2109 I WindowState: WIN DEATH: Window{20fad39 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 18:17:23.950   872  1934 D GraphicsStats: Buffer count: 1
,08-16 18:17:23.963  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 18:17:23.963  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-16 18:17:23.964  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-16 18:17:23.964  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 18:17:23.966   872  1619 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1927) has died
,08-16 18:17:23.967   872  1619 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 18:17:23.968   872  1619 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 18:17:23.971  1847  4305 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-16 18:17:23.971  1847  4305 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 18:17:23.971  1847  4305 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 18:17:23.972  1847  4305 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 18:17:23.972  1847  4305 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-16 18:17:23.972  1847  4305 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 18:17:23.994   872   885 I ActivityManager: Start proc 4338:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 18:17:24.001  4307  4307 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 18:17:24.010  4307  4334 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.010  4307  4334 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.010  4307  4334 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:17:24.015  4307  4351 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 18:17:24.020   872  1619 I ActivityManager: Start proc 4352:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 18:17:24.050  4338  4338 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:24.050  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:24.050  4338  4338 D AndroidRuntime: Shutting down VM
,08-16 18:17:24.056  4338  4338 E AndroidRuntime: FATAL EXCEPTION: main
08-16 18:17:24.056  4338  4338 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4338
08-16 18:17:24.056  4338  4338 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 18:17:24.056  4338  4338 E AndroidRuntime: 	... 10 more
,08-16 18:17:24.058   872  2109 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 18:17:24.059   872  4365 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:17:24.059   872  4365 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:24.059   872  4365 E DropBoxManagerService: 	... 5 more
,08-16 18:17:24.059  4338  4338 I Process : Sending signal. PID: 4338 SIG: 9
,08-16 18:17:24.082  4352  4352 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 18:17:24.090   872  2108 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4338) has died
,08-16 18:17:24.091   872  2108 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 18:17:24.093  1738  4364 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 18:17:24.094  1738  4364 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 18:17:24.121   872   885 I ActivityManager: Start proc 4368:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 18:17:24.130  1738  4364 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 18:17:24.132  1738  4364 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 18:17:24.141  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 18:17:24.144  1524  1524 D AndroidRuntime: Shutting down VM
,08-16 18:17:24.146  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
08-16 18:17:24.146  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
08-16 18:17:24.146  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 18:17:24.146  1524  1524 E AndroidRuntime: 	... 8 more
,08-16 18:17:24.153  4307  4334 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 18:17:24.153  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
,08-16 18:17:24.154   872  4381 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:17:24.154   872  4381 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:24.154   872  4381 E DropBoxManagerService: 	... 5 more
,08-16 18:17:24.176  4307  4351 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.176  4307  4351 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:17:24.177  4307  4351 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 18:17:24.177  4307  4351 E AndroidRuntime: Process: android.process.acore, PID: 4307
08-16 18:17:24.177  4307  4351 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.177  4307  4351 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 18:17:24.180  4307  4351 I Process : Sending signal. PID: 4307 SIG: 9
08-16 18:17:24.180   872  4382 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:17:24.180   872  4382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:24.180   872  4382 E DropBoxManagerService: 	... 5 more
,08-16 18:17:24.184  4368  4368 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:24.184  4368  4368 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 18:17:24.184  4368  4368 D AndroidRuntime: Shutting down VM
,08-16 18:17:24.195  4368  4368 E AndroidRuntime: FATAL EXCEPTION: main
08-16 18:17:24.195  4368  4368 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4368
08-16 18:17:24.195  4368  4368 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 18:17:24.195  4368  4368 E AndroidRuntime: 	... 10 more
08-16 18:17:24.198   872  1307 D WifiService: Client connection lost with reason: 4
,08-16 18:17:24.203   872  1941 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
,08-16 18:17:24.203   872  1941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-16 18:17:24.203   872  1941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 10999ms
,08-16 18:17:24.204   872  1941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
08-16 18:17:24.204   872  1941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30999ms
,08-16 18:17:24.205   279   279 E lowmemorykiller: Error writing /proc/4307/oom_score_adj; errno=22
,08-16 18:17:24.209   279   279 E lowmemorykiller: Error writing /proc/4307/oom_score_adj; errno=22
,08-16 18:17:24.213  1738  1738 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-16 18:17:24.216   872  4383 E DropBoxManagerService: Can't write: system_app_crash
08-16 18:17:24.216   872  4383 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 18:17:24.216   872  4383 E DropBoxManagerService: 	... 5 more
,08-16 18:17:24.217   872  1934 I ActivityManager: Process android.process.acore (pid 4307) has died
,08-16 18:17:24.217   872  1934 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40986ms
,08-16 18:17:24.220   872  1877 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 18:17:24.224  4368  4368 I Process : Sending signal. PID: 4368 SIG: 9
08-16 18:17:24.231  1738  4364 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 18:17:24.231  1738  4364 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 18:17:24.252   872  1372 I ActivityManager: Start proc 4386:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-16 18:17:24.256  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games

```
