#### Test 78968685da35147_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-27 08:57:33.660  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:33.671  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 08:57:33.674  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-27 08:57:33.723  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-27 08:57:33.723  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-27 08:57:33.724  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:33.724  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:57:33.750  1507  1898 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:33.750  1507  1898 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:33.750  1507  1898 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:33.750  1507  1898 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-27 08:57:33.750  1507  1898 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:57:33.750  1507  1898 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:57:33.750  1507  1898 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:57:33.755  2577  2612 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:57:33.755  2577  2612 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 08:57:33.755  2577  2612 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-27 08:57:33.755  2577  2612 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-27 08:57:33.755  2577  2612 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-27 08:57:33.755  2577  2612 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 08:57:33.755  2577  2612 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:57:34.309  3335  3335 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 08:57:34.314  3335  3335 D AndroidRuntime: CheckJNI is OFF
07-27 08:57:34.349  3335  3335 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 08:57:34.392  3335  3335 I Radio-JNI: register_android_hardware_Radio DONE
07-27 08:57:34.411  3335  3335 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-27 08:57:34.415   873  1757 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 08:57:34.455   873  1757 I ActivityManager: Start proc 3346:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-27 08:57:34.468  3335  3335 D AndroidRuntime: Shutting down VM
07-27 08:57:34.639  3346  3346 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-27 08:57:34.671  3346  3346 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-27 08:57:34.685  3346  3346 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 2344-2351)
07-27 08:57:34.685  3346  3346 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:57:34.708  3346  3346 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25921fe}
,07-27 08:57:34.709  3346  3346 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:57:34.709  3346  3346 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:57:34.721  3346  3346 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-27 08:57:34.723  3346  3346 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 08:57:34.750  3346  3361 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,07-27 08:57:34.766  3346  3346 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-27 08:57:34.783  3346  3346 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:57:34.783  3346  3346 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:57:34.783  3346  3346 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 08:57:34.783  3346  3346 I Adreno  : Build Date                       : 10/20/15
07-27 08:57:34.783  3346  3346 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 08:57:34.783  3346  3346 I Adreno  : Local Branch                     : M14
07-27 08:57:34.783  3346  3346 I Adreno  : Remote Branch                    : 
07-27 08:57:34.783  3346  3346 I Adreno  : Remote Branch                    : 
07-27 08:57:34.783  3346  3346 I Adreno  : Reconstruct Branch               : 
,07-27 08:57:34.869   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@717c5c:true
,07-27 08:57:34.937  3346  3346 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 08:57:34.955  3346  3346 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-27 08:57:35.054  3346  3383 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-27 08:57:35.073   873   886 W ActivityManager: Activity pause timeout for ActivityRecord{6abf171 u0 com.test.thalitest/.MainActivity t2}
,07-27 08:57:35.085  3346  3370 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-27 08:57:35.122  3346  3383 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 08:57:35.157  1650  1650 I Keyboard.Facilitator: onFinishInput()
,07-27 08:57:35.226   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +654ms (total +787ms)
,07-27 08:57:35.316  3346  3346 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3346
,07-27 08:57:35.475  3346  3346 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 08:57:35.773  3346  3385 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1649411792
,07-27 08:57:35.780  3346  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 08:57:35.780  3346  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 08:57:35.780  3346  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 08:57:35.780  3346  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 08:57:35.780  3346  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-27 08:57:35.780  3346  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cbaa2ed added. We now have 1 listener(s)
,07-27 08:57:35.784  3346  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-27 08:57:35.785  3346  3385 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-27 08:57:35.785  3346  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 08:57:35.786  3346  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 08:57:35.790  3346  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4586570 added. We now have 1 listener(s)
07-27 08:57:35.791  3346  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 08:57:35.800   873  1304 D WifiService: New client listening to asynchronous messages
,07-27 08:57:35.801  3346  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:57:35.803  3346  3385 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-27 08:57:35.806  3346  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 08:57:35.806  3346  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:57:35.807  3346  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:57:35.807  3346  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 08:57:35.814  3346  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 08:57:35.814  3346  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-27 08:57:35.822  3346  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:35.822  3346  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:57:35.822  3346  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 08:57:35.823  3346  3385 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 08:57:35.824  3346  3346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:57:35.824  3346  3385 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 08:57:35.867  3346  3346 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:57:36.563  3346  3392 W jxcore-log: Initializing JXcore engine
,07-27 08:57:36.563  3346  3392 W jxcore-log: JXcore engine is ready
,07-27 08:57:36.614  3392  3392 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-27 08:57:36.614  3392  3392 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12854]" dev="sockfs" ino=12854 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-27 08:57:36.614  3392  3392 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-27 08:57:36.614  3392  3392 W Thread-285: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[23401]" dev="sockfs" ino=23401 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-27 08:57:36.629  3346  3392 W jxcore-log: Starting JXcore engine
,07-27 08:57:36.708  3346  3392 W jxcore-log: Platform android
07-27 08:57:36.708  3346  3392 W jxcore-log: 
07-27 08:57:36.708  3346  3392 W jxcore-log: Process ARCH arm
07-27 08:57:36.708  3346  3392 W jxcore-log: 
,07-27 08:57:36.866  3346  3392 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:57:36.866  3346  3392 I jxcore-log: 
07-27 08:57:36.867  3346  3392 W jxcore-log: JXcore engine is started
,07-27 08:57:36.880  3346  3385 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:57:36.886  3346  3346 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:57:46.885  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 08:57:46.885  3346  3392 I jxcore-log: 
,07-27 08:57:46.888  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 08:57:46.888  3346  3392 I jxcore-log: 
,07-27 08:57:46.890  3346  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:46.890  3346  3392 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 08:57:46.890  3346  3392 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:46.890  3346  3392 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:57:46.893  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 08:57:46.893  3346  3392 I jxcore-log: 
,07-27 08:57:46.894  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 08:57:46.894  3346  3392 I jxcore-log: 
,07-27 08:57:47.225  3346  3392 I jxcore-log: Unit Test app is loaded
07-27 08:57:47.225  3346  3392 I jxcore-log: 
,07-27 08:57:47.230  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 08:57:47.230  3346  3392 I jxcore-log: 
,07-27 08:57:47.236   873  1389 D WifiService: setWifiEnabled: true pid=3346, uid=10000
07-27 08:57:47.236   873  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-27 08:57:47.251  3346  3392 I jxcore-log: My device name is: motorola-Nexus 6
07-27 08:57:47.251  3346  3392 I jxcore-log: 
,07-27 08:57:47.253  3346  3392 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 08:57:47.253  3346  3392 I jxcore-log: 
,07-27 08:57:47.257  3346  3346 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-27 08:57:47.272   873   890 I ActivityManager: Start proc 3395:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-27 08:57:47.275   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,07-27 08:57:47.284  3346  3346 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:47.284  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:57:47.284  3346  3346 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:57:47.284  3346  3346 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 08:57:47.301   873   886 I ActivityManager: Start proc 3400:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-27 08:57:47.314   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,07-27 08:57:47.314   873  1303 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:57:47.315   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-27 08:57:47.315   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-27 08:57:47.316   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-27 08:57:47.316   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-27 08:57:47.316   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-27 08:57:47.317   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-27 08:57:47.332  3400  3400 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-27 08:57:47.368   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-27 08:57:47.369   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-27 08:57:47.369   371   871 D CommandListener: Setting iface cfg
,07-27 08:57:47.369   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,07-27 08:57:47.369   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 08:57:47.374  3400  3400 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
07-27 08:57:47.377   873  1303 E native  : do suspend true
,07-27 08:57:47.394  3395  3395 D AdapterServiceConfig: Adding HeadsetService
,07-27 08:57:47.395  3395  3395 D AdapterServiceConfig: Adding A2dpService
07-27 08:57:47.395  3395  3395 D AdapterServiceConfig: Adding HidService
07-27 08:57:47.395  3395  3395 D AdapterServiceConfig: Adding HealthService
07-27 08:57:47.395  3395  3395 D AdapterServiceConfig: Adding PanService
07-27 08:57:47.395  3395  3395 D AdapterServiceConfig: Adding GattService
,07-27 08:57:47.395  3395  3395 D AdapterServiceConfig: Adding BluetoothMapService
07-27 08:57:47.395   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
07-27 08:57:47.395   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
07-27 08:57:47.399   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:57:47.424   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79a58bc:true
,07-27 08:57:47.425  3395  3395 D BluetoothAdapterState: make() - Creating AdapterState
,07-27 08:57:47.430  3395  3395 I bt_bluedroid: init
,07-27 08:57:47.430  3395  3431 I BluetoothAdapterState: Entering OffState
,07-27 08:57:47.433  3395  3432 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-27 08:57:47.434  3395  3432 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 08:57:47.434  3395  3432 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-27 08:57:47.434  3395  3432 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-27 08:57:47.435  3395  3395 I bt_bluedroid: get_profile_interface socket
07-27 08:57:47.439  3395  3435 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-27 08:57:47.440  3395  3435 D BluetoothAdapterProperties: Name is: Nexus 6
07-27 08:57:47.441  3395  3395 I bt_bluedroid: get_profile_interface sdp
07-27 08:57:47.445  3395  3418 I bt_bluedroid: config_hci_snoop_log
07-27 08:57:47.446   873   884 I ActivityManager: Killing 2665:com.google.android.calendar/u0a37 (adj 15): empty #17
07-27 08:57:47.446   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-27 08:57:47.449  3395  3431 D BluetoothAdapterState: Current state: OFF, message: 0
,07-27 08:57:47.449  3395  3431 D BluetoothAdapterProperties: Setting state to 14
07-27 08:57:47.449  3395  3431 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-27 08:57:47.450  3395  3431 D BluetoothBondStateMachine: make
,07-27 08:57:47.452  3395  3437 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 08:57:47.480  3395  3431 I BluetoothAdapterState: Entering PendingCommandState
,07-27 08:57:47.482  3395  3395 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-27 08:57:47.485  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
07-27 08:57:47.485  3395  3395 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 08:57:47.486  3395  3395 D BtGatt.GattService: Received start request. Starting profile...
07-27 08:57:47.486  3395  3395 D BtGatt.GattService: start()
07-27 08:57:47.486  3395  3395 I bt_bluedroid: get_profile_interface gatt
07-27 08:57:47.487  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
07-27 08:57:47.487  3395  3395 D BtGatt.AdvertiseManager: advertise manager created
,07-27 08:57:47.494  3395  3395 V BluetoothAdapterState: isTurningOff()=false,
,07-27 08:57:47.494  3395  3395 V BluetoothAdapterState: isTurningOn()=false
07-27 08:57:47.494  3395  3395 V BluetoothAdapterState: isBleTurningOn()=true
07-27 08:57:47.494  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:47.494  3395  3431 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-27 08:57:47.494  3395  3431 I bt_bluedroid: enable
07-27 08:57:47.495  3395  3432 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-27 08:57:47.495  3395  3432 I bt_hci  : start_up
,07-27 08:57:47.502  3395  3432 I bt_vendor: alloc value 0xb3a5c189
,07-27 08:57:47.502  3395  3432 I bt_vendor: init
07-27 08:57:47.502  3395  3432 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 08:57:47.502  3395  3432 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-27 08:57:47.610  3395  3432 D bt_hci  : start_up starting async portion
07-27 08:57:47.610  3395  3440 I bt_hci  : event_finish_startup
,07-27 08:57:47.611  3395  3440 I bt_hci_h4: hal_open
07-27 08:57:47.611  3395  3440 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 08:57:47.616  3395  3440 I bt_userial_vendor: device fd = 51 open
,07-27 08:57:47.652  3395  3440 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 08:57:47.684  3395  3440 D bt_hwcfg: Chipset BCM4354A2
,07-27 08:57:47.684  3395  3440 D bt_hwcfg: Target name = [BCM4354A2]
07-27 08:57:47.685  3395  3440 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-27 08:57:48.349  3395  3440 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-27 08:57:48.349  3395  3440 D bt_hwcfg: Settlement delay -- 100 ms
07-27 08:57:48.349  3395  3440 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 08:57:48.465  3395  3440 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 08:57:48.466  3395  3440 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-27 08:57:48.499  3395  3440 I bt_hwcfg: vendor lib fwcfg completed
,07-27 08:57:48.499  3395  3440 I bt_vendor: firmware callback
,07-27 08:57:48.499  3395  3440 I bt_hci  : firmware_config_callback
,07-27 08:57:48.508  3395  3442 I bt_btu  : btu_task pending for preload complete event
,07-27 08:57:48.508  3395  3442 I bt_btu_task: Bluetooth chip preload is complete
,07-27 08:57:48.508  3395  3442 I bt_btu  : btu_task received preload complete event
,07-27 08:57:48.517  3395  3442 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 08:57:48.517  3395  3442 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-27 08:57:48.517  3395  3442 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 08:57:48.517  3395  3442 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-27 08:57:48.518  3395  3442 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-27 08:57:48.518  3395  3442 I         : BTE_InitTraceLevels -- TRC_A2D
,07-27 08:57:48.518  3395  3442 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-27 08:57:48.518  3395  3442 I         : BTE_InitTraceLevels -- TRC_BTM
,07-27 08:57:48.519  3395  3442 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 08:57:48.519  3395  3442 I         : BTE_InitTraceLevels -- TRC_PAN
,07-27 08:57:48.519  3395  3442 I         : BTE_InitTraceLevels -- TRC_SDP
,07-27 08:57:48.519  3395  3442 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 08:57:48.519  3395  3442 I         : BTE_InitTraceLevels -- TRC_SMP
,07-27 08:57:48.520  3395  3442 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-27 08:57:48.520  3395  3442 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-27 08:57:48.651  3395  3442 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,07-27 08:57:48.651  3395  3442 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,07-27 08:57:48.655   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-27 08:57:48.657   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,07-27 08:57:48.659   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:57:48.660  3395  3435 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-27 08:57:48.662  3395  3435 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-27 08:57:48.664  3395  3435 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-27 08:57:48.669  3395  3435 D BluetoothAdapterProperties: Name is: Nexus 6
,07-27 08:57:48.671  3395  3435 D BluetoothAdapterProperties: Scan Mode:20
,07-27 08:57:48.671  3395  3435 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 08:57:48.671  3395  3435 D bt_hci  : do_postload posting postload work item
,07-27 08:57:48.671  3395  3440 I bt_hci  : event_postload
,07-27 08:57:48.671  3395  3440 I bt_vendor: sco_config_cb
,07-27 08:57:48.671  3395  3440 I bt_hci  : sco_config_callback postload finished.
,07-27 08:57:48.672   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
07-27 08:57:48.675  3346  3346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 08:57:48.676  3395  3440 I bt_vendor: low_power_mode_cb
07-27 08:57:48.680  3395  3435 D bt_bte_conf: Device ID record 1 : primary
07-27 08:57:48.681  3395  3435 D bt_bte_conf:   vendorId            = 000f
,07-27 08:57:48.681  3395  3435 D bt_bte_conf:   vendorIdSource      = 0001
07-27 08:57:48.681  3395  3435 D bt_bte_conf:   product             = 1200
,07-27 08:57:48.681  3395  3435 D bt_bte_conf:   version             = 1436
07-27 08:57:48.681  3395  3435 D bt_bte_conf:   clientExecutableURL = 
,07-27 08:57:48.681  3395  3435 D bt_bte_conf:   serviceDescription  = 
07-27 08:57:48.682  3395  3435 D bt_bte_conf:   documentationURL    = 
,07-27 08:57:48.682  3395  3435 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-27 08:57:48.682  3395  3432 D bt_stack_manager: event_start_up_stack finished
,07-27 08:57:48.684  3395  3431 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-27 08:57:48.684  3395  3431 D BluetoothAdapterProperties: Setting state to 15
,07-27 08:57:48.685  3395  3431 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-27 08:57:48.685  3395  3431 I BluetoothAdapterState: Entering BleOnState
,07-27 08:57:48.689  3395  3431 D BluetoothAdapterState: Current state: BLE ON, message: 1
,07-27 08:57:48.689  3395  3431 D BluetoothAdapterProperties: Setting state to 11
07-27 08:57:48.689  3395  3431 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-27 08:57:48.693  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
07-27 08:57:48.694  3395  3395 D HeadsetService: Received start request. Starting profile...
07-27 08:57:48.696  3395  3395 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-27 08:57:48.696  3395  3395 D HeadsetStateMachine: make
07-27 08:57:48.711   873   886 I ActivityManager: Start proc 3449:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-27 08:57:48.715   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-27 08:57:48.715  3395  3395 D HeadsetStateMachine: max_hf_connections = 1
07-27 08:57:48.715  3395  3395 I bt_bluedroid: get_profile_interface handsfree
07-27 08:57:48.715  3395  3435 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-27 08:57:48.716  3395  3435 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-27 08:57:48.717  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
07-27 08:57:48.719  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
07-27 08:57:48.720   873   873 D BluetoothA2dp: Proxy object connected
,07-27 08:57:48.720  3395  3395 D A2dpService: Received start request. Starting profile...
07-27 08:57:48.721  3395  3431 I BluetoothAdapterState: Entering PendingCommandState
07-27 08:57:48.721  3395  3395 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 08:57:48.721  3395  3395 I bt_bluedroid: get_profile_interface avrcp
,07-27 08:57:48.727  3395  3395 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 08:57:48.727  3395  3395 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 08:57:48.727  3395  3395 D A2dpStateMachine: make
,07-27 08:57:48.729  3395  3395 I bt_bluedroid: get_profile_interface a2dp
,07-27 08:57:48.730  3395  3435 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-27 08:57:48.731  3395  3462 D A2dpStateMachine: Enter Disconnected: -2
,07-27 08:57:48.733  3395  3395 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 08:57:48.733  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
,07-27 08:57:48.734  3395  3395 D HidService: Received start request. Starting profile...
07-27 08:57:48.734  1371  1371 D BluetoothInputDevice: Proxy object connected
07-27 08:57:48.734  3395  3395 I bt_bluedroid: get_profile_interface hidhost
,07-27 08:57:48.735  3395  3395 D HidService: setHidService(): set to: null
07-27 08:57:48.735  1371  1371 D HidProfile: Bluetooth service connected
07-27 08:57:48.735  3395  3435 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
07-27 08:57:48.735  3395  3435 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-27 08:57:48.735  3395  3395 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 08:57:48.736  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
07-27 08:57:48.736  3395  3395 D HealthService: Received start request. Starting profile...
07-27 08:57:48.737  3395  3395 I bt_bluedroid: get_profile_interface health
07-27 08:57:48.738  3395  3395 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 08:57:48.738  3395  3448 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 08:57:48.739  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
07-27 08:57:48.739  3395  3395 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:48.739  3395  3395 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:48.739  3395  3395 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:48.739  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 08:57:48.739  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:48.740  1371  1371 D PanProfile: Bluetooth service connected
07-27 08:57:48.741  3395  3395 D PanService: Received start request. Starting profile...
07-27 08:57:48.741  3395  3395 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 08:57:48.741  3395  3395 I bt_bluedroid: get_profile_interface pan
,07-27 08:57:48.741  3395  3435 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 08:57:48.743  3395  3395 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5a67e98
,07-27 08:57:48.745  3395  3395 D BluetoothMapService: Received start request. Starting profile...
,07-27 08:57:48.745  3395  3395 D BluetoothMapService: start()
,07-27 08:57:48.747  3395  3395 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-27 08:57:48.747  1371  1371 D BluetoothMap: Proxy object connected
07-27 08:57:48.748  1371  1371 D MapProfile: Bluetooth service connected
07-27 08:57:48.748  1371  1371 D BluetoothMap: getConnectedDevices()
,07-27 08:57:48.748  1371  1371 D BluetoothMap: Bluetooth is Not enabled
07-27 08:57:48.749  3395  3395 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-27 08:57:48.749  3395  3395 D BluetoothMapAppObserver: createReceiver()
,07-27 08:57:48.750  3395  3395 D BluetoothMapAppObserver: initObservers()
,07-27 08:57:48.750  3395  3395 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-27 08:57:48.753  3449  3449 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:57:48.756  3395  3395 V BluetoothAdapterState: isBleTurningOn()=false
,07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isTurningOff()=false
,07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isTurningOn()=true
,07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
07-27 08:57:48.757  3395  3395 V BluetoothAdapterState: isTurningOff()=false
07-27 08:57:48.758  3395  3395 V BluetoothAdapterState: isTurningOn()=true
07-27 08:57:48.758  3395  3395 V BluetoothAdapterState: isBleTurningOn()=false
07-27 08:57:48.758  3395  3395 V BluetoothAdapterState: isBleTurningOff()=false
,07-27 08:57:48.758  3395  3431 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-27 08:57:48.758  3395  3431 D BluetoothAdapterProperties: ScanMode =  20
07-27 08:57:48.758  3395  3431 D BluetoothAdapterProperties: State =  11
,07-27 08:57:48.758  3395  3431 D BluetoothAdapterProperties: Setting state to 12
,07-27 08:57:48.758  3395  3431 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-27 08:57:48.758  3395  3431 I BluetoothAdapterState: Entering OnState
07-27 08:57:48.759  1371  1384 D BluetoothPbap: onBluetoothStateChange: up=true
07-27 08:57:48.759  3395  3435 D BluetoothAdapterProperties: Scan Mode:21
07-27 08:57:48.759  3395  3435 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 08:57:48.761  3346  3346 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-27 08:57:48.762   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 08:57:48.766  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 08:57:48.767  3346  3346 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 08:57:48.768  1371  3345 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 08:57:48.768  1371  1386 D BluetoothPan: onBluetoothStateChange on: true
07-27 08:57:48.769  1371  1387 D BluetoothMap: onBluetoothStateChange: up=true
07-27 08:57:48.769   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:57:48.769  1704  1720 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:57:48.769   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
07-27 08:57:48.769   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 08:57:48.770   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 08:57:48.771  3395  3395 D BluetoothMapService: onReceive
07-27 08:57:48.771  3395  3395 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 08:57:48.771  3395  3395 D BluetoothMapService: STATE_ON
07-27 08:57:48.772  1371  1670 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 08:57:48.773   873  1383 I ActivityManager: Killing 2823:com.google.android.gm/u0a78 (adj 15): empty #17
07-27 08:57:48.775  3395  3395 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-27 08:57:48.776  3395  3395 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-27 08:57:48.822  1371  1371 D BluetoothA2dp: Proxy object connected
07-27 08:57:48.824  3395  3395 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:48.825  1371  1670 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:57:48.826  3395  3395 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:57:48.827  3395  3395 D ObexServerSockets: Succeed to create listening sockets 
07-27 08:57:48.827  3395  3395 D ObexServerSockets0: startAccept()
07-27 08:57:48.827  3395  3395 D ObexServerSockets0: prepareForNewConnect()
,07-27 08:57:48.829  3395  3395 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-27 08:57:48.829  3395  3395 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-27 08:57:48.829  3395  3470 D ObexServerSockets0: Accepting socket connection...
07-27 08:57:48.830  3395  3395 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-27 08:57:48.830  3395  3395 D ObexServerSockets0: prepareForNewConnect()
,07-27 08:57:48.831  3395  3471 D ObexServerSockets0: Accepting socket connection...
,07-27 08:57:48.832  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-27 08:57:48.847   873  1389 I ActivityManager: Start proc 3472:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-27 08:57:48.868   873   890 D BluetoothHeadset: Proxy object connected
07-27 08:57:48.868   873   890 D BluetoothHeadset: Proxy object connected
,07-27 08:57:48.871  1704  1933 D BluetoothHeadset: Proxy object connected
,07-27 08:57:48.872   873   890 D BluetoothHeadset: Proxy object connected
,07-27 08:57:48.875  3472  3472 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-27 08:57:48.934  1371  1386 D BluetoothHeadset: Proxy object connected
,07-27 08:57:48.936  1371  1371 D HeadsetProfile: Bluetooth service connected
,07-27 08:57:49.041  3472  3472 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-27 08:57:49.041  3472  3472 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.041  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.042  3472  3472 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.042  3472  3472 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.042  3472  3472 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.k.d(PG:583)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.042  3472  3472 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.042  3472  3472 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.File.exists(File.java:361)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.042  3472  3472 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 08:57:49.042  3472  3472 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 08:57:49.061  3449  3449 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 08:57:49.069   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88d02aa:true
,07-27 08:57:49.087  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-27 08:57:49.089  1371  1371 D BluetoothPbap: Proxy object connected
07-27 08:57:49.090  1371  1371 D PbapServerProfile: Bluetooth service connected
07-27 08:57:49.091  3449  3449 D LocalBluetoothProfileManager: Adding local A2DP profile
07-27 08:57:49.092  3395  3499 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 08:57:49.107  3449  3449 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-27 08:57:49.117  3449  3449 D LocalBluetoothProfileManager: Adding local MAP profile
07-27 08:57:49.118  3449  3449 D BluetoothMap: Create BluetoothMap proxy object
,07-27 08:57:49.129  3449  3449 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-27 08:57:49.145  3449  3449 D DockEventReceiver: finishStartingService: stopping service
,07-27 08:57:49.146  3395  3506 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 08:57:49.148  3395  3506 I BtOppRfcommListener: Accept thread started.
,07-27 08:57:49.149  3449  3449 D BluetoothA2dp: Proxy object connected
,07-27 08:57:49.152  3449  3449 D BluetoothInputDevice: Proxy object connected
,07-27 08:57:49.152  3449  3449 D HidProfile: Bluetooth service connected
,07-27 08:57:49.153  3449  3449 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 08:57:49.154  3449  3449 D PanProfile: Bluetooth service connected
07-27 08:57:49.154  3449  3449 D BluetoothMap: Proxy object connected
,07-27 08:57:49.154  3449  3449 D MapProfile: Bluetooth service connected
07-27 08:57:49.154  3449  3449 D BluetoothMap: getConnectedDevices()
,07-27 08:57:49.157  3449  3449 D BluetoothPbap: Proxy object connected
,07-27 08:57:49.157  3449  3449 D PbapServerProfile: Bluetooth service connected
,07-27 08:57:49.160   873  1742 I ActivityManager: Killing 3006:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-27 08:57:49.172  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-27 08:57:49.198  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-27 08:57:49.198  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-27 08:57:49.205   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,07-27 08:57:49.212  3449  3464 D BluetoothHeadset: Proxy object connected
,07-27 08:57:49.214  3449  3449 D HeadsetProfile: Bluetooth service connected
07-27 08:57:49.217   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-27 08:57:49.217   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:57:49.218   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-27 08:57:49.228   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 08:57:49.232   371   871 D CommandListener: Setting iface cfg
,07-27 08:57:49.237   873  1303 D WifiStateMachine: Start Dhcp Watchdog 1
,07-27 08:57:49.242   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-27 08:57:49.270   873  3512 D DhcpClient: Receive thread started
,07-27 08:57:49.303  3472  3487 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-27 08:57:49.321   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@659e42f:true
,07-27 08:57:49.352   873  1303 E native  : do suspend false
,07-27 08:57:49.362   873  3510 D DhcpClient: Broadcasting DHCPDISCOVER
,07-27 08:57:49.376   873  3512 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 167995, domain null
,07-27 08:57:49.376   873  3510 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 167995 seconds
,07-27 08:57:49.377   873  3510 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-27 08:57:49.388   873  3512 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-27 08:57:49.389   873  3510 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-27 08:57:49.390   371   871 D CommandListener: Setting iface cfg
,07-27 08:57:49.392   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-27 08:57:49.395   873  3510 D DhcpClient: Scheduling renewal in 86399s
07-27 08:57:49.395   873  1303 E native  : do suspend true
,07-27 08:57:49.405   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-27 08:57:49.405   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
07-27 08:57:49.406   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-27 08:57:49.406   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 08:57:49.413   873  1305 D ConnectivityService: Adding iface wlan0 to network 100
,07-27 08:57:49.449   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-27 08:57:49.449   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-27 08:57:49.452   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,07-27 08:57:49.453   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-27 08:57:49.455   873  1305 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-27 08:57:49.464   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-27 08:57:49.472   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 100
07-27 08:57:49.473   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
07-27 08:57:49.473   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-27 08:57:49.474   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-27 08:57:49.474   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,07-27 08:57:49.474   873  1305 D ConnectivityService:    accepting network in place of null
,07-27 08:57:49.476   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-27 08:57:49.479   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 08:57:49.510   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:57:49.532   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-27 08:57:49.534   873  1305 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,07-27 08:57:49.538   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
07-27 08:57:49.538   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:49.540   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,07-27 08:57:49.544   873   890 D Tethering: MasterInitialState.processMessage what=3
07-27 08:57:49.545   873  3508 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:802::200e
,07-27 08:57:49.545   873  1725 V BackupManagerService: Scheduling immediate backup pass
07-27 08:57:49.547   873   873 V BackupManagerService: Running a backup pass
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 08:57:49.550  3346  3346 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 08:57:49.554  3346  3346 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 08:57:49.555   873  1327 V BackupManagerService: clearing pending backups
07-27 08:57:49.557   873  1327 V PerformBackupTask: Beginning backup of 16 targets
,07-27 08:57:49.561  1809  1809 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-27 08:57:49.578   873  1327 D PerformBackupTask: invokeAgentForBackup on @pm@
,07-27 08:57:49.595   873  1680 D AlarmManagerService: Setting time of day to sec=1469602668
07-27 08:57:48.837   873  1680 W AlarmManagerService: Unable to set rtc to 1469602668: Invalid argument
,07-27 08:57:48.841   873  1327 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,07-27 08:57:48.851  1869  1869 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-27 08:57:48.860  1869  1869 D SystemUpdateService: onCreate
,07-27 08:57:48.862  1869  1869 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
07-27 08:57:48.877  1869  3534 I CheckinService: Checking schedule, now: 1469602668877 next: 1469598643225
07-27 08:57:48.877  1869  3534 I CheckinService: active receiver: enabled
07-27 08:57:48.878  1869  3534 I CheckinService: Preparing to send checkin request
07-27 08:57:48.878  1869  3534 I EventLogService: Accumulating logs since 1469602191238
,07-27 08:57:48.884  1869  3536 I SystemUpdateService: active receiver: enabled
,07-27 08:57:48.886   873  3508 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 06:57:48 GMT], X-Android-Received-Millis=[1469602668852], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469602669588]}
,07-27 08:57:48.888   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-27 08:57:48.889   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-27 08:57:48.889   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-27 08:57:48.889   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 08:57:48.892  1869  3534 I EventLogService: Opted in for usage reporting
,07-27 08:57:48.899  1869  3536 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 08:57:48.899   873  3531 D GpsLocationProvider: NTP server returned: 1469602668837 (Wed Jul 27 08:57:48 GMT+02:00 2016) reference: 347260 certainty: 10 system time offset: -62
07-27 08:57:48.900   873  3531 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,07-27 08:57:48.906  1869  3536 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-27 08:57:48.907  1869  3536 I SystemUpdateService: now status is 0 (complete)
07-27 08:57:48.907  1869  3536 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 08:57:48.907  1869  3536 I SystemUpdateService: file has been verified
,07-27 08:57:48.907  1869  3536 I SystemUpdateService: OTA package size = 12249756
,07-27 08:57:48.912  1869  3536 I SystemUpdateService: showing system update notification
,07-27 08:57:48.913   873  1327 I BackupRestoreController: Getting widget state for user: 0
,07-27 08:57:48.925  1869  3532 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-27 08:57:48.939   873  1724 I ActivityManager: Start proc 3542:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-27 08:57:48.949  1869  1869 D SystemUpdateService: onDestroy
,07-27 08:57:48.963  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:48.964  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:48.968  3542  3542 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-27 08:57:48.980  1869  3557 I iu.SyncManager: SYNC; picasa accounts
,07-27 08:57:48.990  1869  1869 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-27 08:57:48.991  1869  1869 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-27 08:57:49.006  1869  3556 I MDM     : [187] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-27 08:57:49.007  1869  3556 W BaseAppContext: Using Auth Proxy for data requests.
,07-27 08:57:49.012  3400  3541 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 08:57:49.014  1869  3556 V GoogleAuthProtoRequest: [187] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 08:57:49.018  1869  1869 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 08:57:49.019  1869  1869 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 08:57:49.030   873  1681 I ActivityManager: Start proc 3565:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-27 08:57:49.046  1771  2061 W GmsBackupTransport: Unknown package in backup request: @pm@
,07-27 08:57:49.046  1771  2061 V GmsBackupTransport: starting performBackup for @pm@
07-27 08:57:49.049  3542  3558 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-27 08:57:49.025  1869  3557 I iu.UploadsManager: num queued entries: 0
,07-27 08:57:49.056  1869  3557 I iu.UploadsManager: num updated entries: 0
07-27 08:57:49.057  1869  3557 I iu.SyncManager: NEXT; no task
,07-27 08:57:49.066  3565  3565 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-27 08:57:49.072  1771  2061 V GmsBackupTransport: performBackup done for @pm@
,07-27 08:57:49.074  3565  3565 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-27 08:57:49.087  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:49.105  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,07-27 08:57:49.105  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
07-27 08:57:49.105  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:49.105  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:49.120  1507  1518 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:49.120  1507  1518 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:49.120  1507  1518 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:49.120  1507  1518 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-27 08:57:49.120  1507  1518 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 08:57:49.120  1507  1518 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 08:57:49.120  1507  1518 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 08:57:49.124  3542  3558 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-27 08:57:49.126  1869  1869 E ConnectivityChangeReceiver: Ignoring connectivity change
,07-27 08:57:49.130  3565  3565 D SprintDMHelper: simOperator: 
,07-27 08:57:49.130  3565  3565 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-27 08:57:49.134  1771  1787 W GmsBackupTransport: Error sending final backup to server: 
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 08:57:49.134  1771  1787 W GmsBackupTransport: 	... 1 more
,07-27 08:57:49.135  1771  2061 I GmsBackupTransport: Next backup will happen in 43199993 millis.
07-27 08:57:49.135   873  1327 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,07-27 08:57:49.143   873  1725 I ActivityManager: Start proc 3587:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-27 08:57:49.143  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 08:57:49.145  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-27 08:57:49.146  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:49.146  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:49.164  3542  3558 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:57:49.186   873   884 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1869 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 08:57:49.199  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-27 08:57:49.199  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,07-27 08:57:49.199  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:57:49.199  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:49.228  3400  3541 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 08:57:49.229  3400  3541 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 08:57:49.257  3542  3542 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-27 08:57:49.270  1869  3534 W EventLogAggregator: Unknown tag: snet_gcore
,07-27 08:57:49.270  1869  3534 W EventLogAggregator: Unknown tag: snet_launch_service
,07-27 08:57:49.348  1507  1507 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:49.435   873  1327 I BackupManagerService: Backup pass finished.
,07-27 08:57:49.446  1869  3556 E MDM     : [187] SitrepService.a: Error sending sitrep.
,07-27 08:57:49.452  3542  3542 W InstanceID/Rpc: Found 10011
,07-27 08:57:49.494   873   883 I ActivityManager: Start proc 3658:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-27 08:57:49.518  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 08:57:49.518  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:57:49.518  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:49.518  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:57:49.532  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:49.537  3119  3579 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 08:57:49.537  3119  3579 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jcs.o(PG:406)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at blb.a(PG:3937)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at czp.a(PG:18188)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at czp.a(PG:9081)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:57:49.537  3119  3579 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	... 12 more
07-27 08:57:49.537  3119  3579 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at fal.a(PG:38)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:57:49.537  3119  3579 E HttpOperation: 	... 14 more
,07-27 08:57:49.583  3621  3621 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads44419008.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads44419008.dex
,07-27 08:57:49.594  3658  3658 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
07-27 08:57:49.596   873   885 I ActivityManager: Start proc 3676:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
07-27 08:57:49.610  2347  3657 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-27 08:57:49.612  3676  3676 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
07-27 08:57:49.615   873  1757 I ActivityManager: Killing 2457:com.android.providers.calendar/u0a3 (adj 15): empty #17
07-27 08:57:49.616  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-27 08:57:49.616  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:57:49.616  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:57:49.616  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:49.709  3621  3621 I dex2oat : dex2oat took 126.910ms (threads: 4) arena alloc=199KB java alloc=29KB native alloc=1642KB free=1685KB
,07-27 08:57:49.725  1869  3534 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-27 08:57:49.731   873  1304 D WifiService: New client listening to asynchronous messages
,07-27 08:57:49.732  1869  3534 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-27 08:57:49.782  1869  3535 W DriveInitializer: Awaiting to be initialized
,07-27 08:57:49.825  1869  3703 W DriveInitializer: Background init thread started
,07-27 08:57:49.826  3119  3579 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 08:57:49.826  3119  3579 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jcs.o(PG:406)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at hec.a(PG:42)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at hee.a(PG:102)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at czr.a(PG:65)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at kka.a(PG:108)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at czp.a(PG:19176)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at czp.a(PG:9081)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:57:49.826  3119  3579 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	... 15 more
07-27 08:57:49.826  3119  3579 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at fal.a(PG:38)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:57:49.826  3119  3579 E HttpOperation: 	... 17 more
,07-27 08:57:49.827  3119  3579 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 08:57:49.827  3119  3579 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at hec.a(PG:42)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at hee.a(PG:102)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at czr.a(PG:65)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at kka.a(PG:108)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	... 15 more
07-27 08:57:49.827  3119  3579 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at fal.a(PG:38)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 08:57:49.827  3119  3579 E ExperimentLoader: 	... 17 more
07-27 08:57:49.864  3676  3676 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-27 08:57:49.871  3676  3676 I BooksApp: Created application version: 3.6.9 (30609),
07-27 08:57:49.893  1507  3623 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
07-27 08:57:49.950  1869  3703 W DriveInitializer: Background init thread ended
07-27 08:57:49.975   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 23681, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:57:50.033  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-27 08:57:50.034  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
,07-27 08:57:50.034  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:57:50.034  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:50.045  3676  3718 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:57:50.050  1869  3534 W CheckinRequestBuilder: awaiting user notification for token
,07-27 08:57:50.057  3658  3658 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-27 08:57:50.057  3658  3658 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:57:50.057  3658  3658 I GAv4    :   adb logcat -s GAv4
,07-27 08:57:50.079   873  1389 I ActivityManager: Start proc 3732:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,07-27 08:57:50.082  3658  3658 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:50.088  3658  3658 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:50.109  3732  3732 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-27 08:57:50.117  3732  3732 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:57:50.117  3732  3732 I MultiDex: install
07-27 08:57:50.117  3732  3732 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:50.123  3658  3744 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:50.126  2859  3728 V KeepSync: Connecting to GoogleApiClient
,07-27 08:57:50.126   873  1703 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 08:57:50.160  3732  3732 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-27 08:57:50.183  3732  3732 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:57:50.190  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 08:57:50.190  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 08:57:50.190  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:50.190  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:57:50.205  1869  3749 V BaseAuthAsyncOperation: access token request failed
,07-27 08:57:50.212  2859  3728 V KeepSync: GoogleApiClient failed to connect with error code: 4
07-27 08:57:50.216  3732  3753 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-27 08:57:50.272   375  1275 D WVCdm   : Instantiating CDM.
07-27 08:57:50.273   375   375 I WVCdm   : CdmEngine::OpenSession
07-27 08:57:50.273   375   375 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
07-27 08:57:50.276   375   375 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
07-27 08:57:50.280   375   375 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
07-27 08:57:50.280   375   375 D DrmWidevineDash: Service_Initialize: starts!
07-27 08:57:50.280   375   375 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-27 08:57:50.280   375   375 D QSEECOMAPI: : App is not loaded in QSEE
07-27 08:57:50.288  3732  3743 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:50.426  3658  3658 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-27 08:57:50.485  3658  3658 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-27 08:57:50.492  3658  3658 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8913-8915)
07-27 08:57:50.492  3658  3658 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 08:57:50.505  3658  3658 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9c80aa0}
,07-27 08:57:50.505  3658  3658 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:57:50.505  3658  3658 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 08:57:50.519  3658  3658 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 08:57:50.530  3658  3658 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 08:57:50.541   375   375 D QSEECOMAPI: : Loaded image: APP id = 3
,07-27 08:57:50.543   375   375 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-27 08:57:50.543   375   375 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2b26000
07-27 08:57:50.543   375   375 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2b26000
,07-27 08:57:50.550   332   339 D DrmLibTime: got the req here! ret=0
,07-27 08:57:50.550   332   339 D DrmLibTime: command id, time_cmd_id = 770
07-27 08:57:50.550   332   339 D DrmLibTime: time_getutcsec starts!
,07-27 08:57:50.550   332   339 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-27 08:57:50.550   332   339 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,07-27 08:57:50.550   332   339 D DrmLibTime: QSEE Time Listener: seconds: 1469602670
07-27 08:57:50.550   332   339 D DrmLibTime: QSEE Time Listener: nano seconds: 550813139
07-27 08:57:50.550   332   339 D DrmLibTime: time_getutcsec returns 0, sec = 1469602670; nsec = 550813139
07-27 08:57:50.550   332   339 D DrmLibTime: time_getutcsec finished! 
,07-27 08:57:50.551   332   339 D DrmLibTime: iotcl_continue_command finished! and return 0 
07-27 08:57:50.551   332   339 D DrmLibTime: before calling ioctl to read the next time_cmd
,07-27 08:57:50.557   375   375 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-27 08:57:50.557   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-27 08:57:50.558   375   375 D DrmWidevineDash: hlos api version =  10
07-27 08:57:50.558   375   375 D DrmWidevineDash: tz api version =  10
07-27 08:57:50.558   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-27 08:57:50.558   375   375 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-27 08:57:50.561  3658  3658 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-27 08:57:50.577   375   375 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-27 08:57:50.577   375   375 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-27 08:57:50.578   375   375 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbe854214
07-27 08:57:50.578   375   375 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-27 08:57:50.578   375   375 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,07-27 08:57:50.578   375   375 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604cb88, dataLength=8
07-27 08:57:50.579   375   375 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-27 08:57:50.585  3658  3658 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-27 08:57:50.585  3658  3658 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-27 08:57:50.585  3658  3658 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 08:57:50.585  3658  3658 I Adreno  : Build Date                       : 10/20/15
07-27 08:57:50.585  3658  3658 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 08:57:50.585  3658  3658 I Adreno  : Local Branch                     : M14
07-27 08:57:50.585  3658  3658 I Adreno  : Remote Branch                    : 
07-27 08:57:50.585  3658  3658 I Adreno  : Remote Branch                    : 
07-27 08:57:50.585  3658  3658 I Adreno  : Reconstruct Branch               : 
,07-27 08:57:50.636   375   375 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb607e200, wrapped_rsa_key_length=1280
,07-27 08:57:50.644   375   375 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-27 08:57:50.644   375   375 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-27 08:57:50.646   375  1839 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:57:50.647   375  1839 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,07-27 08:57:50.647   375  1839 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-27 08:57:50.647   375  1839 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2c66a00, idLength=0xb1c3ef2c
,07-27 08:57:50.669   375  1839 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-27 08:57:50.669   375  1839 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-27 08:57:50.670   375  1839 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,07-27 08:57:50.670   375  1839 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,07-27 08:57:50.670   375  1839 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,07-27 08:57:50.670   375  1839 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
07-27 08:57:50.671   375  1839 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
07-27 08:57:50.671   375  1839 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-27 08:57:50.672   375  1839 D DrmWidevineDash: hlos api version =  10
07-27 08:57:50.672   375  1839 D DrmWidevineDash: tz api version =  10
07-27 08:57:50.672   375  1839 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-27 08:57:50.672   375  1839 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
07-27 08:57:50.673   375  1839 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,07-27 08:57:50.673   375  1839 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-27 08:57:50.673   375  1839 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
07-27 08:57:50.674   375  1839 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-27 08:57:50.674   375  1839 D WVCdm   : PrepareKeyRequest: nonce=3319636748
07-27 08:57:50.674   375  1839 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2d71000
07-27 08:57:50.674   375  1839 D DrmWidevineDash: message_length=1624, signature=0xb3a9a8c0, signature_length=2982408196
,07-27 08:57:50.715  3658  3658 I NSApplication: Starting up...
,07-27 08:57:50.776  3658  3785 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 08:57:50.784   375  1839 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-27 08:57:50.785   375  1311 I WVCdm   : CdmEngine::CloseSession
07-27 08:57:50.785   375  1311 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-27 08:57:50.786   375  1311 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-27 08:57:50.786   873  1757 I ActivityManager: Start proc 3793:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
07-27 08:57:50.786   375  1311 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-27 08:57:50.787   375  1311 D DrmWidevineDash: Service_Uninitialize: starts!
07-27 08:57:50.787   375  1311 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-27 08:57:50.787   375  1311 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
07-27 08:57:50.787   375  1311 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-27 08:57:50.788   375  1311 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-27 08:57:50.836  3793  3793 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-27 08:57:50.919  3676  3808 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 08:57:50.962  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 08:57:50.963  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 08:57:50.963  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:50.963  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:57:50.993  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 08:57:50.993  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 08:57:50.993  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:50.993  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:50.996  3809  3809 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
07-27 08:57:51.003  3676  3808 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:57:51.004  3676  3718 E BooksSync: Soft error
07-27 08:57:51.004  3676  3718 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:57:51.004  3676  3718 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 08:57:51.004  3676  3718 E BooksSync: Sync error
07-27 08:57:51.004  3676  3718 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:57:51.004  3676  3718 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 08:57:51.004  3676  3718 I BooksSync: Finished books sync
07-27 08:57:51.007   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23688, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:57:51.008   873  1755 I ActivityManager: Killing 2732:android.process.acore/u0a5 (adj 15): empty #17
,07-27 08:57:51.051  3809  3809 I dex2oat : dex2oat took 55.338ms (threads: 4) arena alloc=200KB java alloc=47KB native alloc=1664KB free=1407KB
07-27 08:57:51.054  3732  3743 W System  : ClassLoader referenced unknown path: 
07-27 08:57:51.070  3732  3743 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 08:57:51.070  3732  3743 I Adreno  : Build Date                       : 10/20/15
07-27 08:57:51.070  3732  3743 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 08:57:51.070  3732  3743 I Adreno  : Local Branch                     : M14
07-27 08:57:51.070  3732  3743 I Adreno  : Remote Branch                    : 
07-27 08:57:51.070  3732  3743 I Adreno  : Remote Branch                    : 
07-27 08:57:51.070  3732  3743 I Adreno  : Reconstruct Branch               : 
,07-27 08:57:51.152  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 08:57:51.153  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 08:57:51.153  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:51.153  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:51.168  3732  3743 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-27 08:57:51.168  3732  3743 I Adreno  : Build Date                       : 10/20/15
07-27 08:57:51.168  3732  3743 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-27 08:57:51.168  3732  3743 I Adreno  : Local Branch                     : M14
07-27 08:57:51.168  3732  3743 I Adreno  : Remote Branch                    : 
07-27 08:57:51.168  3732  3743 I Adreno  : Remote Branch                    : 
07-27 08:57:51.168  3732  3743 I Adreno  : Reconstruct Branch               : 
,07-27 08:57:51.174  2859  3728 E KeepSync: IOException
07-27 08:57:51.174  2859  3728 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 08:57:51.174  2859  3728 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 08:57:51.174  2859  3728 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 08:57:51.174  2859  3728 E KeepSync: 	... 10 more
,07-27 08:57:51.174  2859  3728 W KeepSync: Sync result 2
,07-27 08:57:51.194   873   884 I ActivityManager: Killing 3207:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-27 08:57:51.192   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23688, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:57:51.295   375   375 I WVCdm   : CdmEngine::OpenSession
,07-27 08:57:51.295   375   375 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,07-27 08:57:51.297   375   375 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-27 08:57:51.298   375   375 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,07-27 08:57:51.298   375   375 D DrmWidevineDash: Service_Initialize: starts!
07-27 08:57:51.298   375   375 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-27 08:57:51.298   375   375 D QSEECOMAPI: : App is not loaded in QSEE
,07-27 08:57:51.363   873   883 I ActivityManager: Killing 3224:com.android.musicfx/u0a18 (adj 15): empty #17
,07-27 08:57:51.440   873  1389 I ActivityManager: Start proc 3828:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-27 08:57:51.474  3828  3828 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,07-27 08:57:51.500   375   375 D QSEECOMAPI: : Loaded image: APP id = 3
,07-27 08:57:51.501   375   375 D DrmWidevineDash: Service_Initialize: ends! returns 0
,07-27 08:57:51.501   375   375 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2b26000
07-27 08:57:51.501   375   375 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2b26000
,07-27 08:57:51.507   332   339 D DrmLibTime: got the req here! ret=0
,07-27 08:57:51.507   332   339 D DrmLibTime: command id, time_cmd_id = 770
07-27 08:57:51.507   332   339 D DrmLibTime: time_getutcsec starts!
07-27 08:57:51.507   332   339 D DrmLibTime: QSEE Time Listener: time_getutcsec
07-27 08:57:51.507   332   339 D DrmLibTime: QSEE Time Listener: get_utc_seconds
07-27 08:57:51.507   332   339 D DrmLibTime: QSEE Time Listener: seconds: 1469602671
07-27 08:57:51.507   332   339 D DrmLibTime: QSEE Time Listener: nano seconds: 507673703
07-27 08:57:51.507   332   339 D DrmLibTime: time_getutcsec returns 0, sec = 1469602671; nsec = 507673703
07-27 08:57:51.507   332   339 D DrmLibTime: time_getutcsec finished! 
07-27 08:57:51.507   332   339 D DrmLibTime: iotcl_continue_command finished! and return 0 
,07-27 08:57:51.507   332   339 D DrmLibTime: before calling ioctl to read the next time_cmd
,07-27 08:57:51.513   375   375 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,07-27 08:57:51.513   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
07-27 08:57:51.514   375   375 D DrmWidevineDash: hlos api version =  10
07-27 08:57:51.514   375   375 D DrmWidevineDash: tz api version =  10
07-27 08:57:51.514   375   375 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
07-27 08:57:51.514   375   375 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
07-27 08:57:51.516  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-27 08:57:51.516  3346  3392 I jxcore-log: 
,07-27 08:57:51.524   375   375 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,07-27 08:57:51.524   375   375 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-27 08:57:51.524   375   375 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbe854214
07-27 08:57:51.525   375   375 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,07-27 08:57:51.525   375   375 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,07-27 08:57:51.527   375   375 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb604cbe8, dataLength=8
,07-27 08:57:51.528   375   375 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
07-27 08:57:51.528   375   375 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb607dc00, wrapped_rsa_key_length=1280
,07-27 08:57:51.531   375   375 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,07-27 08:57:51.531   375   375 I WVCdm   : CdmEngine::QueryKeyControlInfo
07-27 08:57:51.532   375  1275 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-27 08:57:51.532   375  1275 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
07-27 08:57:51.532   375  1275 I WVCdm   : CdmEngine::GenerateKeyRequest
07-27 08:57:51.532   375  1275 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2c66ba0, idLength=0xb2f7ff2c
,07-27 08:57:51.541   873  1681 I ActivityManager: Start proc 3843:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,07-27 08:57:51.545   375  1275 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,07-27 08:57:51.545   375  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
07-27 08:57:51.546   375  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-27 08:57:51.546   375  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
07-27 08:57:51.546   375  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-27 08:57:51.546   375  1275 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,07-27 08:57:51.546   375  1275 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,07-27 08:57:51.546   375  1275 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-27 08:57:51.547   375  1275 D DrmWidevineDash: hlos api version =  10
,07-27 08:57:51.547   375  1275 D DrmWidevineDash: tz api version =  10
07-27 08:57:51.547   375  1275 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,07-27 08:57:51.547   375  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,07-27 08:57:51.548   375  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
07-27 08:57:51.548   375  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
07-27 08:57:51.548   375  1275 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-27 08:57:51.548   375  1275 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-27 08:57:51.548   375  1275 D WVCdm   : PrepareKeyRequest: nonce=2263946844
,07-27 08:57:51.549   375  1275 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb2d72c00
,07-27 08:57:51.549   375  1275 D DrmWidevineDash: message_length=1655, signature=0xb3a9a640, signature_length=3002597380
,07-27 08:57:51.583  3843  3843 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-27 08:57:51.608   375  1275 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-27 08:57:51.609   375  1839 I WVCdm   : CdmEngine::CloseSession
07-27 08:57:51.609   375  1839 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-27 08:57:51.609   375  1839 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-27 08:57:51.609   375  1839 D DrmWidevineDash: OEMCrypto_Terminate: starts!
07-27 08:57:51.610   375  1839 D DrmWidevineDash: Service_Uninitialize: starts!
07-27 08:57:51.610   375  1839 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-27 08:57:51.610   375  1839 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,07-27 08:57:51.611   375  1839 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,07-27 08:57:51.611   375  1839 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-27 08:57:51.620  3743  3743 W Binder_2: type=1400 audit(0.0:9): avc: denied { read } for name="/" dev="tmpfs" ino=10245 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,07-27 08:57:51.671  1869  3534 I CheckinRequestBuilder: Classify the device as Phone.
,07-27 08:57:51.681  1869  3534 I EventLogService: Opted in for usage reporting
,07-27 08:57:51.736  3843  3843 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@25921fe(com.android.providers.calendar.CalendarProvider2@c30d5f)
,07-27 08:57:51.784   873  1847 I ActivityManager: Start proc 3862:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,07-27 08:57:51.785   873  1847 I ActivityManager: Killing 3246:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-27 08:57:51.828   873  1847 I ActivityManager: Killing 3036:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,07-27 08:57:51.903  3828  3828 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-27 08:57:51.914  3862  3862 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-27 08:57:51.930  3862  3862 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-27 08:57:51.930  3862  3862 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 08:57:51.930  3862  3862 I GAv4    :   adb logcat -s GAv4
,07-27 08:57:51.941  3862  3862 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:51.946  3862  3862 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:51.954  3862  3879 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 08:57:51.983  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-27 08:57:51.983  3346  3392 I jxcore-log: 
,07-27 08:57:51.991  1869  3534 W System.err: java.lang.Exception: Error converting session
,07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
07-27 08:57:51.991  1869  3534 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
,07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
,07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
,07-27 08:57:51.992  1869  3534 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
07-27 08:57:51.992  1869  3534 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
07-27 08:57:51.993  1869  3534 W System.err: 	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
07-27 08:57:51.993  1869  3534 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
07-27 08:57:51.993  1869  3534 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,07-27 08:57:51.993  1869  3534 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:57:51.993  1869  3534 W System.err: Caused by: java.io.IOException: Invalid session data
,07-27 08:57:51.993  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
,07-27 08:57:51.993  1869  3534 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
07-27 08:57:51.993  1869  3534 W System.err: 	... 25 more
07-27 08:57:51.996   873  1389 I ActivityManager: Start proc 3882:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
07-27 08:57:52.005  1507  3892 I VacuumService: Vacuum at: now=1469602672004 tag=VacuumService
,07-27 08:57:52.014  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-27 08:57:52.014  3346  3392 I jxcore-log: 
,07-27 08:57:52.020  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-27 08:57:52.020  3346  3392 I jxcore-log: 
,07-27 08:57:52.036   873  1389 I ActivityManager: Killing 3170:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-27 08:57:52.038  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-27 08:57:52.038  3346  3392 I jxcore-log: 
07-27 08:57:52.042  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-27 08:57:52.042  3346  3392 I jxcore-log: 
,07-27 08:57:52.048  3882  3882 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-27 08:57:52.054  3882  3882 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1469602672054
,07-27 08:57:52.055  3882  3882 D         : TimeServiceNative: User Time to be set is 1469602672055
07-27 08:57:52.055  3882  3882 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-27 08:57:52.055  3882  3882 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-27 08:57:52.055  3882  3882 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1469602672055
07-27 08:57:52.055   392   998 D QC-time-services: Daemon: Connection accepted:time_genoff
07-27 08:57:52.056  3882  3882 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1469602672055
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1469602672055, operation = 0
,07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/13/70 3:8:20
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:Value read from RTC seconds = 29905700000
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:new time 1469602672055 
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon: delta 1439696972055 genoff 1439696972055 
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696972055 to memory
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-27 08:57:52.056   392  3897 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:57:52.059   392  3897 D QC-time-services: Updating the TOD offset
,07-27 08:57:52.059   392  3897 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696972055 to memory
07-27 08:57:52.059   392  3897 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-27 08:57:52.059   392  3897 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-27 08:57:52.060   392  3897 E QC-time-services: Daemon:Update to modem bit set
,07-27 08:57:52.061   392  3897 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,07-27 08:57:52.061   392  3897 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1153637872055
07-27 08:57:52.061  3882  3882 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-27 08:57:52.074   873  1389 I ActivityManager: Killing 1809:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,07-27 08:57:52.089   873  1304 D WifiService: Client connection lost with reason: 4
,07-27 08:57:52.114  1869  3534 I CheckinTask: Sending checkin request (8918 bytes)
,07-27 08:57:52.129   392   998 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-27 08:57:52.135   392   996 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-27 08:57:52.201  1507  3894 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-27 08:57:52.203  1507  3894 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-27 08:57:52.208  1507  2291 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-27 08:57:52.210  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-27 08:57:52.217  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:52.219  1869  1869 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-27 08:57:52.237   873  1742 I ActivityManager: Start proc 3907:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,07-27 08:57:52.255  1869  3918 D LocationInitializer: Restart initialization of location
,07-27 08:57:52.275  1771  1938 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:57:52.276  1507  3920 W FusedLocationProvider: location=null
,07-27 08:57:52.281  3907  3907 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-27 08:57:52.292  3907  3907 I MultiDex: VM with version 2.1.0 has multidex support
,07-27 08:57:52.292  3907  3907 I MultiDex: install
07-27 08:57:52.292  3907  3907 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-27 08:57:52.350  3907  3907 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-27 08:57:52.371  3907  3907 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:57:52.377  1507  2301 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-27 08:57:52.378  1507  1507 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-27 08:57:52.386  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:57:52.387  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-27 08:57:52.387  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
07-27 08:57:52.387  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:52.387  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:57:52.388  1869  1869 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-27 08:57:52.396  3907  3907 D WearableService: callingUid 10011, callindPid: 3907
,07-27 08:57:52.414  1869  3931 D LocationInitializer: Restart initialization of location
,07-27 08:57:52.413  2347  3902 E Babel   : UserRecoverableAuthException.
07-27 08:57:52.418  1771  2250 E MDM     : [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,07-27 08:57:52.421  2347  3902 E Babel   : efr: BadAuthentication
07-27 08:57:52.421  2347  3902 E Babel   : 	at efp.a(Unknown Source)
07-27 08:57:52.421  2347  3902 E Babel   : 	at efp.a(Unknown Source)
07-27 08:57:52.421  2347  3902 E Babel   : 	at efp.a(Unknown Source)
07-27 08:57:52.421  2347  3902 E Babel   : 	at g.a(Unknown Source)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbh.a(SourceFile:3092)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbh.a(SourceFile:1136)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cyr.a(SourceFile:4333)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cyr.a(SourceFile:1419)
07-27 08:57:52.421  2347  3902 E Babel   : 	at ctk.a(SourceFile:492)
07-27 08:57:52.421  2347  3902 E Babel   : 	at ctk.a(SourceFile:1468)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cst.a(SourceFile:4416)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbv.b(SourceFile:106)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbs.d(SourceFile:335)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbt.run(SourceFile:81)
,07-27 08:57:52.421  1771  2250 E MDM     : [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
07-27 08:57:52.421  2347  3902 E Babel   : Error getting auth token
07-27 08:57:52.421  2347  3902 E Babel   : dxq
07-27 08:57:52.421  2347  3902 E Babel   : 	at g.a(Unknown Source)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbh.a(SourceFile:3092)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbh.a(SourceFile:1136)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cyr.a(SourceFile:4333)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cyr.a(SourceFile:1419)
07-27 08:57:52.421  2347  3902 E Babel   : 	at ctk.a(SourceFile:492)
07-27 08:57:52.421  2347  3902 E Babel   : 	at ctk.a(SourceFile:1468)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cst.a(SourceFile:4416)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbv.b(SourceFile:106)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbs.d(SourceFile:335)
07-27 08:57:52.421  2347  3902 E Babel   : 	at cbt.run(SourceFile:81)
,07-27 08:57:52.423  3907  3929 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,07-27 08:57:52.427  2347  3902 E Babel   : Account registration failed 1-Redacted-21
,07-27 08:57:52.427  2347  3902 E Babel   : dao: null -- null
07-27 08:57:52.427  2347  3902 E Babel   : 	at cbh.a(SourceFile:3124)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cbh.a(SourceFile:1136)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cyr.a(SourceFile:4333)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cyr.a(SourceFile:1419)
07-27 08:57:52.427  2347  3902 E Babel   : 	at ctk.a(SourceFile:492)
07-27 08:57:52.427  2347  3902 E Babel   : 	at ctk.a(SourceFile:1468)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cst.a(SourceFile:4416)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cbv.b(SourceFile:106)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cbs.d(SourceFile:335)
07-27 08:57:52.427  2347  3902 E Babel   : 	at cbt.run(SourceFile:81)
,07-27 08:57:52.434  1771  1938 W GCoreFlp: No location to return for getLastLocation()
,07-27 08:57:52.435  1507  3932 W FusedLocationProvider: location=null
,07-27 08:57:52.437  2347  3902 I art     : Note: end time exceeds epoch: 
,07-27 08:57:52.453  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
07-27 08:57:52.453  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
07-27 08:57:52.454  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:52.454  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:52.462  2347  3936 E Babel   : Unexpected exception while authenticating.
07-27 08:57:52.462  2347  3936 E Babel   : efs: User intervention required. Notification has been pushed.
07-27 08:57:52.462  2347  3936 E Babel   : 	at efp.b(Unknown Source)
07-27 08:57:52.462  2347  3936 E Babel   : 	at efp.b(Unknown Source)
07-27 08:57:52.462  2347  3936 E Babel   : 	at g.a(Unknown Source)
07-27 08:57:52.462  2347  3936 E Babel   : 	at cbh.b(SourceFile:1151)
07-27 08:57:52.462  2347  3936 E Babel   : 	at def.run(SourceFile:5617)
07-27 08:57:52.462  2347  3936 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:57:52.462  2347  3936 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:57:52.462  2347  3936 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,07-27 08:57:52.481  1507  3894 W Uploader:  no longer exists, so no auth token.
,07-27 08:57:52.494  1869  3534 I CheckinResponseProcessor: From server: 1 gservices updates and 0 deletes
,07-27 08:57:52.577  1507  1519 I GservicesProvider: main difference update completed
,07-27 08:57:52.601   873   886 I ActivityManager: Start proc 3939:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,07-27 08:57:52.603  1507  3894 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-27 08:57:52.603  1507  3894 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 08:57:52.603  1507  3894 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:52.603  1507  3894 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:52.608  1869  3534 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,07-27 08:57:52.618  1869  3534 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,07-27 08:57:52.620  1507  3894 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:57:52.620  1507  3894 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 08:57:52.620  1507  3894 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 08:57:52.647   873  1383 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-27 08:57:52.647  2347  2347 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-27 08:57:52.648  2347  2347 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:57:52.648  2347  2347 W Babel   : BAM#gBA: invalid account id: -1
07-27 08:57:52.648  2347  2347 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-27 08:57:52.654  3939  3939 W System  : ClassLoader referenced unknown path: /system/priv-app/ConfigUpdater/lib/arm
,07-27 08:57:52.669  3939  3939 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION intent_firewall: null null
,07-27 08:57:52.685  3939  3939 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION apn_db: null null
,07-27 08:57:52.687  3939  3939 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION tzdata: null null
,07-27 08:57:52.692  3939  3939 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION selinux: null null
,07-27 08:57:52.696  3939  3939 E ConfigUpdater: Received malformed URL while handling Gservices.CHANGED_ACTION carrier_provisioning_urls: null null
,07-27 08:57:52.711  3400  3400 W InstanceID/Rpc: Found 10011
,07-27 08:57:52.728   873   883 I ActivityManager: Start proc 3965:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,07-27 08:57:52.744  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,07-27 08:57:52.744  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
07-27 08:57:52.744  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:52.744  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-27 08:57:52.752  3965  3965 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
07-27 08:57:52.754  1869  3534 W CheckinRequestBuilder: awaiting user notification for token
,07-27 08:57:52.766  1869  3534 I CheckinRequestBuilder: Classify the device as Phone.
,07-27 08:57:52.782  1869  3534 I EventLogService: Opted in for usage reporting
,07-27 08:57:52.785   873   883 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,07-27 08:57:52.805  1869  1869 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,07-27 08:57:52.808  1869  1869 D SystemUpdateService: onCreate
,07-27 08:57:52.810  1869  1869 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-27 08:57:52.816  1869  1869 D OcrModelManager: Updating downloaded model state (gservices changed)
07-27 08:57:52.821  1507  2634 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
07-27 08:57:52.822  1869  1869 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
07-27 08:57:52.822  1869  1869 I OcrUtils: Updating ocr activity enabled=false
,07-27 08:57:52.841  1771  1771 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,07-27 08:57:52.850  1771  1771 I GCoreUlr: DispatchingService.onCreate()
,07-27 08:57:52.863  1869  3534 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,07-27 08:57:52.923  3843  3843 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-27 08:57:52.929  1869  1878 E System  : Uncaught exception thrown by finalizer
07-27 08:57:52.930  1869  1878 E System  : java.lang.NullPointerException: ssl_session == null
07-27 08:57:52.930  1869  1878 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
07-27 08:57:52.930  1869  1878 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
07-27 08:57:52.930  1869  1878 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
07-27 08:57:52.930  1869  1878 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
07-27 08:57:52.930  1869  1878 E System  : 	at java.lang.Thread.run(Thread.java:818)
07-27 08:57:52.933  3843  3843 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-27 08:57:52.935  1869  3534 I CheckinService: Checking schedule, now: 1469602672935 next: 1469643815863
,07-27 08:57:52.935  1869  3534 I CheckinService: active receiver: disabled
,07-27 08:57:52.940   873  1755 I ActivityManager: Killing 2577:com.android.vending/u0a19 (adj 15): empty #17
,07-27 08:57:53.026  1869  3988 I SystemUpdateService: active receiver: enabled
,07-27 08:57:53.048   873  1742 I ActivityManager: Killing 3449:com.android.settings/1000 (adj 15): empty #17
,07-27 08:57:53.100  1869  3988 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-27 08:57:53.104  1869  3988 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-27 08:57:53.104  1869  3988 I SystemUpdateService: now status is 0 (complete)
07-27 08:57:53.104  1869  3988 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-27 08:57:53.104  1869  3988 I SystemUpdateService: file has been verified
07-27 08:57:53.104  1869  3988 I SystemUpdateService: OTA package size = 12249756
,07-27 08:57:53.107  1771  3994 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,07-27 08:57:53.112  1869  3988 I SystemUpdateService: showing system update notification
,07-27 08:57:53.163  1869  1869 D SystemUpdateService: onDestroy
,07-27 08:57:53.179  1869  3996 I CheckinService: Checking schedule, now: 1469602673179 next: 1469643815863
07-27 08:57:53.180  1869  3996 I CheckinService: active receiver: disabled
,07-27 08:57:53.184  1507  3894 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 08:57:53.184  1507  3894 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 08:57:53.184  1507  3894 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:53.185  1507  3894 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:53.205  1507  3894 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:57:53.205  1507  3894 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 08:57:53.205  1507  3894 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 08:57:53.228   873  1846 I ActivityManager: Start proc 4000:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,07-27 08:57:53.243  1771  3994 I GCoreUlr: WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,07-27 08:57:53.259  1771  3994 I GCoreUlr: Unbound from all location providers
,07-27 08:57:53.281  1771  1771 I GCoreUlr: DispatchingService.onDestroy()
,07-27 08:57:53.281  1771  1771 I GCoreUlr: Stopping handler for UlrDispSvcFast
,07-27 08:57:53.284  1771  1771 I GCoreUlr: Unbound from all location providers
,07-27 08:57:53.377  1507  3894 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 08:57:53.377  1507  3894 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 08:57:53.377  1507  3894 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:53.377  1507  3894 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:53.387  1507  3894 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:57:53.387  1507  3894 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 08:57:53.387  1507  3894 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 08:57:53.440   873   883 I ActivityManager: Killing 3472:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,07-27 08:57:53.516  4000  4030 I GservicesUpdateTask: Updating Gservices keys
,07-27 08:57:53.632  1869  1869 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-27 08:57:53.636  1869  1869 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-27 08:57:53.637  1507  2239 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,07-27 08:57:53.645  1507  3894 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 08:57:53.645  1507  3894 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-27 08:57:53.645  1507  3894 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:57:53.645  1507  3894 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:53.654  1507  3894 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:57:53.654  1507  3894 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 08:57:53.654  1507  3894 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 08:57:53.792  1507  3894 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-27 08:57:53.792  1507  3894 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,07-27 08:57:53.792  1507  3894 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:57:53.793  1507  3894 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:57:53.817  1507  3894 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 08:57:53.817  1507  3894 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-27 08:57:53.817  1507  3894 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-27 08:57:54.364  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-27 08:57:54.364  3346  3392 I jxcore-log: 
,07-27 08:57:54.376  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-27 08:57:54.376  3346  3392 I jxcore-log: 
,07-27 08:57:54.385  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-27 08:57:54.385  3346  3392 I jxcore-log: 
,07-27 08:57:54.550  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-27 08:57:54.550  3346  3392 I jxcore-log: 
,07-27 08:57:54.892  3676  3710 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:57:55.376  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-27 08:57:55.376  3346  3392 I jxcore-log: 
,07-27 08:57:55.435  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-27 08:57:55.435  3346  3392 I jxcore-log: 
,07-27 08:57:55.442  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-27 08:57:55.442  3346  3392 I jxcore-log: 
,07-27 08:57:55.647  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-27 08:57:55.647  3346  3392 I jxcore-log: 
,07-27 08:57:55.669  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-27 08:57:55.669  3346  3392 I jxcore-log: 
,07-27 08:57:55.674  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-27 08:57:55.674  3346  3392 I jxcore-log: 
,07-27 08:57:55.681  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-27 08:57:55.681  3346  3392 I jxcore-log: 
,07-27 08:57:55.697  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-27 08:57:55.697  3346  3392 I jxcore-log: 
,07-27 08:57:55.718  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
,07-27 08:57:55.718  3346  3392 I jxcore-log: 
,07-27 08:57:55.805  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-27 08:57:55.805  3346  3392 I jxcore-log: 
,07-27 08:57:55.811  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-27 08:57:55.811  3346  3392 I jxcore-log: 
,07-27 08:57:55.839  3346  3392 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-27 08:57:55.839  3346  3392 I jxcore-log: 
,07-27 08:57:55.852  3346  3392 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-27 08:57:55.853  3346  3392 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
,07-27 08:57:55.853  3346  3392 I jxcore-log: 
,07-27 08:57:55.911  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
07-27 08:57:55.911  3346  3392 I jxcore-log: 
07-27 08:57:55.912  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 08:57:55.912  3346  3392 I jxcore-log: 
,07-27 08:57:55.912  3346  3392 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 08:57:55.912  3346  3392 I jxcore-log: 
,07-27 08:57:56.642  3828  3855 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:57:56.719   873  1305 D ConnectivityService: handlePromptUnvalidated 100
,07-27 08:57:57.441   873  1681 I ActivityManager: Killing 3565:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,07-27 08:57:57.503   873  1724 I ActivityManager: Killing 3587:com.android.chrome/u0a40 (adj 15): empty #17
,07-27 08:57:58.673   873   884 I ActivityManager: Killing 3542:com.google.android.youtube/u0a86 (adj 15): empty #17
,07-27 08:57:58.750   873   884 I ActivityManager: Killing 3658:com.google.android.apps.magazines/u0a67 (adj 15): empty #18
,07-27 08:57:59.970   873  1847 I ActivityManager: Start proc 4044:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,07-27 08:58:00.077  4044  4044 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,07-27 08:58:00.172  4044  4044 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-27 08:58:00.238  4044  4044 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,07-27 08:58:00.252  4044  4044 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:58:00.253  4044  4044 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-27 08:58:00.294   873  1755 I ActivityManager: Killing 3676:com.google.android.apps.books/u0a34 (adj 15): empty #17
,07-27 08:58:00.354  4044  4044 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
07-27 08:58:00.354  4044  4044 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,07-27 08:58:00.361  4044  4077 D Ads     : Skipping gmscore version check
,07-27 08:58:00.369  4044  4044 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-27 08:58:00.382  4044  4077 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-27 08:58:00.388  4044  4044 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-27 08:58:02.958   873   896 W PackageSettings: Skipping PackageSetting{1363285 com.example.hello/10273} due to missing metadata
,07-27 08:58:02.996   873  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 08:58:03.044   873  1755 I ActivityManager: Start proc 4081:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-27 08:58:03.085  4081  4081 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-27 08:58:03.112  1771  1771 V GmsNetworkLocationProvi: DISABLE
,07-27 08:58:03.117  1771  1771 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-27 08:58:03.123  4081  4081 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-27 08:58:03.156  1869  4099 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,07-27 08:58:03.160  1869  4099 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,07-27 08:58:03.171  1869  2152 I Icing   : updateResources: need to parse f{com.google.android.gms}
,07-27 08:58:03.193  4000  4101 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,07-27 08:58:03.355  4081  4096 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,07-27 08:58:03.380  4000  4101 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 174 ms] updated apps [took 174 ms] 
,07-27 08:58:03.545  4081  4096 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,07-27 08:58:03.545  4081  4096 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,07-27 08:58:03.564   873  1846 I ActivityManager: Start proc 4106:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,07-27 08:58:03.640  4106  4106 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,07-27 08:58:03.678   873  1742 I ActivityManager: Start proc 4118:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,07-27 08:58:03.699   873   884 I ActivityManager: Start proc 4128:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,07-27 08:58:03.746   873  1847 I ActivityManager: Killing 3862:com.google.android.deskclock/u0a44 (adj 15): empty #17
,07-27 08:58:03.791   873  1724 I ActivityManager: Killing 2859:com.google.android.keep/u0a79 (adj 15): empty #17
,07-27 08:58:03.812  4118  4118 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,07-27 08:58:03.870  4128  4128 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,07-27 08:58:03.889  4118  4145 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,07-27 08:58:03.910  4128  4128 I GoogleHttpClient: GMS http client unavailable, use old client
,07-27 08:58:03.948  4081  4096 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,07-27 08:58:03.971  4081  4096 I ContactDirectoryManager: Discovered 0 contact directories in 535ms
,07-27 08:58:04.025  4118  4144 I Gmail   : getAccountsCursor
,07-27 08:58:04.031  4118  4118 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-27 08:58:04.055  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:04.100  4118  4156 E Gmail   : Error finding the version of the Email provider.....
07-27 08:58:04.100  4118  4156 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
07-27 08:58:04.100  4118  4156 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
07-27 08:58:04.100  4118  4156 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
07-27 08:58:04.100  4118  4156 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
07-27 08:58:04.100  4118  4156 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 08:58:04.100  4118  4156 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:58:04.100  4118  4156 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
07-27 08:58:04.100  4118  4156 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:58:04.101  4118  4156 W EmailMigration: We do not support migrating this version of the Email provider.
,07-27 08:58:04.131  4118  4159 I Gmail   : getAccountsCursor
,07-27 08:58:04.156  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:04.226   873  1757 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,07-27 08:58:04.229  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:04.270  4106  4106 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-27 08:58:04.281  4118  4163 I Gmail   : Observing account changes for notifications
,07-27 08:58:04.300  4106  4106 I Exchange: EasService.onCreate
,07-27 08:58:04.320  4106  4168 I Exchange: RestartPingTask
,07-27 08:58:04.357  4118  4167 I Gmail   : notifyAccountChanged
,07-27 08:58:04.362  4106  4106 I Exchange: RestartPingsTask did not start any pings.
,07-27 08:58:04.362  4106  4106 I Exchange: PSS stopIfIdle
07-27 08:58:04.362  4106  4106 I Exchange: PSS has no active accounts; stopping service.
07-27 08:58:04.369  4118  4155 I Gmail   : getAccountsCursor
,07-27 08:58:04.370  4106  4106 I Exchange: onDestroy
,07-27 08:58:04.393  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:04.396  4118  4167 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-27 08:58:04.410  4118  4167 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,07-27 08:58:04.429  4118  4167 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-27 08:58:04.430  4118  4167 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,07-27 08:58:04.439  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:04.442  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:04.613  4118  4159 I Gmail   : getAccountsCursor
,07-27 08:58:04.628  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:05.260  4044  4044 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-27 08:58:05.297  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:05.392  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-27 08:58:05.392  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-27 08:58:05.392  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:58:05.393  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:05.459  4044  4044 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-27 08:58:05.484  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:05.568  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 08:58:05.568  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-27 08:58:05.569  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:05.570  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:05.682  4044  4172 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-27 08:58:05.688  4044  4044 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,07-27 08:58:05.689  4044  4044 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,07-27 08:58:05.693  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:05.749  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 08:58:05.749  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-27 08:58:05.749  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:05.749  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:05.784  4044  4044 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-27 08:58:06.133  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:06.198  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 08:58:06.199  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-27 08:58:06.199  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:06.200  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:06.242  4044  4044 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-27 08:58:06.244  4044  4044 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-27 08:58:06.249  4044  4044 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-27 08:58:06.258  4044  4044 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,07-27 08:58:06.280  4044  4174 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-27 08:58:08.116   873  1847 I ActivityManager: Killing 3882:com.qualcomm.timeservice/1000 (adj 15): empty #17
,07-27 08:58:08.218   873  1383 I ActivityManager: Killing 3939:com.google.android.configupdater/u0a42 (adj 15): empty #17
,07-27 08:58:09.094  4118  4151 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:58:09.341  4106  4166 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:58:15.867   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=374291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:58:23.446   873   885 I ActivityManager: Start proc 4181:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,07-27 08:58:23.493  4181  4181 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,07-27 08:58:23.593  4181  4181 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-27 08:58:23.605  4181  4181 I BooksApp: Created application version: 3.6.9 (30609)
,07-27 08:58:23.644  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:23.646  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:23.667  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 08:58:23.667  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:58:23.667  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:23.667  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:23.678  3119  4196 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 08:58:23.678  3119  4196 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jcs.o(PG:406)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at blb.a(PG:3937)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at czp.a(PG:18188)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at czp.a(PG:9087)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:23.678  3119  4196 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	... 12 more
07-27 08:58:23.678  3119  4196 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at fal.a(PG:38)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:58:23.678  3119  4196 E HttpOperation: 	... 14 more
,07-27 08:58:23.736  4181  4200 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:58:23.920  1507  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 08:58:23.920  1507  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:58:23.920  1507  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:23.920  1507  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:23.951  3119  4205 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 08:58:23.951  3119  4205 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jcs.o(PG:406)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at blb.a(PG:3937)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at czp.a(PG:18188)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at czp.a(PG:9081)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:23.951  3119  4205 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	... 12 more
07-27 08:58:23.951  3119  4205 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at fal.a(PG:38)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:58:23.951  3119  4205 E HttpOperation: 	... 14 more
,07-27 08:58:24.032  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 08:58:24.032  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:58:24.032  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:24.032  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:24.057  4181  4209 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 08:58:24.175   873  1703 I ActivityManager: Start proc 4211:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-27 08:58:24.191  3400  4210 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 08:58:24.219  3119  4205 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 08:58:24.219  3119  4205 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	,at jcs.o(PG:406)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at hec.a(PG:42)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at hee.a(PG:102)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at czr.a(PG:65)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at kka.a(PG:108)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at czp.a(PG:19176)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at czp.a(PG:9081)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:24.219  3119  4205 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	... 15 more
07-27 08:58:24.219  3119  4205 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at fal.a(PG:38)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:58:24.219  3119  4205 E HttpOperation: 	... 17 more
07-27 08:58:24.220  3119  4205 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 08:58:24.220  3119  4205 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at hec.a(PG:42)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at hee.a(PG:102)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at czr.a(PG:65)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at kka.a(PG:108)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	... 15 more
07-27 08:58:24.220  3119  4205 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	at fal.a(PG:38)
07-27 08:58:24.220,  3119  4205 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 08:58:24.220  3119  4205 E ExperimentLoader: 	... 17 more
,07-27 08:58:24.235  1507  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 08:58:24.236  1507  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 08:58:24.236  1507  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:58:24.236  1507  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:24.293  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 08:58:24.293  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 08:58:24.293  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:24.293  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:24.308  4181  4209 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 08:58:24.312  4181  4200 E BooksSync: Soft error
07-27 08:58:24.312  4181  4200 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:58:24.312  4181  4200 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 08:58:24.312  4181  4200 E BooksSync: Sync error
07-27 08:58:24.312  4181  4200 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:58:24.312  4181  4200 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 08:58:24.312  4181  4200 I BooksSync: Finished books sync,
,07-27 08:58:24.325   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 379772, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:58:24.331  4211  4211 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-27 08:58:24.380   873   885 I ActivityManager: Start proc 4223:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,07-27 08:58:24.403   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 348399, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:58:24.455  4211  4228 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-27 08:58:24.483  4223  4223 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,07-27 08:58:24.491  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 08:58:24.491  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 08:58:24.492  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:58:24.492  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 08:58:24.558  3400  4210 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 08:58:24.610  4211  4228 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-27 08:58:24.772  4211  4228 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-27 08:58:24.840  4211  4211 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-27 08:58:24.929  4223  4249 V KeepSync: Connecting to GoogleApiClient
,07-27 08:58:24.931   873  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 08:58:24.956  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:25.017  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-27 08:58:25.017  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-27 08:58:25.018  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:25.018  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:25.059  4044  4044 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:58:25.060  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 08:58:25.060  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-27 08:58:25.066  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 08:58:25.066  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 08:58:25.066  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:25.067  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:25.090  1869  4273 V BaseAuthAsyncOperation: access token request failed
,07-27 08:58:25.091  4223  4249 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 08:58:25.217  4211  4211 W InstanceID/Rpc: Found 10011
,07-27 08:58:25.289  4261  4261 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1463351592.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1463351592.dex
,07-27 08:58:25.324   873   884 I ActivityManager: Killing 3965:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-27 08:58:25.449  4261  4261 I dex2oat : dex2oat took 161.028ms (threads: 4) arena alloc=261KB java alloc=37KB native alloc=1387KB free=1428KB
,07-27 08:58:25.526  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 08:58:25.526  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 08:58:25.526  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:25.526  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:25.578  4223  4249 E KeepSync: IOException
07-27 08:58:25.578  4223  4249 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 08:58:25.578  4223  4249 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 08:58:25.578  4223  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 08:58:25.578  4223  4249 E KeepSync: 	... 10 more
,07-27 08:58:25.578  4223  4249 W KeepSync: Sync result 2
,07-27 08:58:25.593   873  1383 I ActivityManager: Killing 3793:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,07-27 08:58:25.595   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 380907, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:58:25.666   873  1725 I ActivityManager: Killing 3828:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-27 08:58:28.615  4181  4198 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-27 08:58:29.482  4223  4231 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@fe7309a)
,07-27 08:58:30.373   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 08:58:33.661  4044  4054 D Finsky  : [340] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-27 08:58:33.680  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:33.693  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:33.695  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:33.748  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-27 08:58:33.748  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-27 08:58:33.748  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:33.749  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:33.795  4044  4054 D Finsky  : [340] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-27 08:58:34.429  1650  1760 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-27 08:58:34.429  1650  1760 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-27 08:58:34.490  1507  1507 I ConfigService: onCreate
,07-27 08:58:39.575  1507  1507 I ConfigService: onDestroy
,07-27 08:58:42.614   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=401037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:58:45.540  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:45.552  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:45.555  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:45.605  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-27 08:58:45.606  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-27 08:58:45.606  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:45.606  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:45.644  4044  4044 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-27 08:58:45.644  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 08:58:45.645  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-27 08:58:56.038  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:56.040  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:58:56.076  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 08:58:56.077  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:58:56.077  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:58:56.077  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:56.098  3119  4324 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 08:58:56.098  3119  4324 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jcs.o(PG:406)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at blb.a(PG:3937)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at czp.a(PG:18188)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at czp.a(PG:9081)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:56.098  3119  4324 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	... 12 more
07-27 08:58:56.098  3119  4324 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at fal.a(PG:38)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:58:56.098  3119  4324 E HttpOperation: 	... 14 more
,07-27 08:58:56.177  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 08:58:56.177  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 08:58:56.177  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:58:56.177  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:58:56.195  3119  4324 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 08:58:56.195  3119  4324 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jdm.a(PG:82)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jcs.o(PG:406)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jcn.a(PG:1379)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jcs.i(PG:143)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at hec.a(PG:42)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at hee.a(PG:102)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at czr.a(PG:65)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at kka.a(PG:108)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at czp.a(PG:19176)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at czp.a(PG:9081)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at czq.run(PG:1686)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:56.195  3119  4324 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jdj.a(PG:4091)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jdj.a(PG:1125)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jdm.a(PG:77)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	... 15 more
07-27 08:58:56.195  3119  4324 E HttpOperation: Caused by: faj: BadAuthentication
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at fal.a(PG:38)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	at jdj.a(PG:4089)
07-27 08:58:56.195  3119  4324 E HttpOperation: 	... 17 more
,07-27 08:58:56.195  3119  4324 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 08:58:56.195  3119  4324 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at hec.a(PG:42)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at hee.a(PG:102)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at czr.a(PG:65)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at kka.a(PG:108)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	... 15 more
07-27 08:58:56.195  3119  4324 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at fal.a(PG:38)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 08:58:56.195  3119  4324 E ExperimentLoader: 	... 17 more
,07-27 08:58:56.330   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 413481, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:58:57.760   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=416184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 08:59:05.927  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:05.942  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:05.948  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:06.009  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-27 08:59:06.010  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-27 08:59:06.010  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:59:06.010  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:06.072  4044  4044 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:59:06.074  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 08:59:06.081  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-27 08:59:14.854   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=433277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 08:59:26.222  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:26.227  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:26.246  3400  4329 V GoogleAuthProtoRequest: [284] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 08:59:26.356  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 08:59:26.356  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.,
,07-27 08:59:26.356  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:59:26.356  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: [284] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: [284] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 08:59:26.395  3400  4329 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 08:59:26.428  4181  4331 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 08:59:26.459  4181  4332 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 08:59:26.515  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 08:59:26.515  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 08:59:26.515  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:59:26.515  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:26.635  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 08:59:26.635  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 08:59:26.635  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:59:26.636  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:26.641  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:26.681  4181  4332 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:59:26.682  4181  4331 E BooksSync: Soft error
07-27 08:59:26.682  4181  4331 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:59:26.682  4181  4331 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 08:59:26.682  4181  4331 E BooksSync: Sync error
07-27 08:59:26.682  4181  4331 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 08:59:26.682  4181  4331 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 08:59:26.682  4181  4331 I BooksSync: Finished books sync
,07-27 08:59:26.688   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 443434, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 08:59:26.695  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-27 08:59:26.695  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-27 08:59:26.695  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:59:26.695  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:26.719  4044  4044 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:59:26.719  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 08:59:26.719  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-27 08:59:47.145  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:47.156  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:47.159  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:47.212  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-27 08:59:47.213  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-27 08:59:47.213  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:59:47.214  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:47.270  4044  4044 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 08:59:47.271  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-27 08:59:47.274  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-27 08:59:56.896  4223  4335 V KeepSync: Connecting to GoogleApiClient
07-27 08:59:56.897   873  1742 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 08:59:56.953  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:56.956  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 08:59:56.999  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 08:59:56.999  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 08:59:57.000  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 08:59:57.000  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:57.010  1869  4336 V BaseAuthAsyncOperation: access token request failed
,07-27 08:59:57.011  4223  4335 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 08:59:57.047  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 08:59:57.048  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 08:59:57.048  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 08:59:57.048  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 08:59:57.060  4223  4335 E KeepSync: IOException
07-27 08:59:57.060  4223  4335 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 08:59:57.060  4223  4335 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 08:59:57.060  4223  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 08:59:57.060  4223  4335 E KeepSync: 	... 10 more
,07-27 08:59:57.060  4223  4335 W KeepSync: Sync result 2
,07-27 08:59:57.073   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 446597, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:00:07.327   873   886 I ActivityManager: Start proc 4338:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-27 09:00:07.409  4338  4338 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-27 09:00:07.427  4338  4338 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-27 09:00:07.427  4338  4338 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-27 09:00:07.427  4338  4338 I GAv4    :   adb logcat -s GAv4
,07-27 09:00:07.442  4338  4338 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-27 09:00:07.447  4338  4338 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-27 09:00:07.461  4338  4353 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-27 09:00:07.537  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:00:07.545  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:00:07.546  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:00:07.590  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-27 09:00:07.590  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-27 09:00:07.590  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:00:07.590  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:00:07.616  4044  4044 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-27 09:00:07.617  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-27 09:00:07.617  4044  4044 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-27 09:00:07.632   873  1755 I ActivityManager: Killing 3843:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-27 09:00:27.304  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:00:27.306  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:00:27.341  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:00:27.342  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:00:27.342  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:00:27.342  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:00:27.360  3119  4355 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:00:27.360  3119  4355 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:00:27.360  3119  4355 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	... 12 more
07-27 09:00:27.360  3119  4355 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at fal.a(PG:38)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:00:27.360  3119  4355 E HttpOperation: 	... 14 more
,07-27 09:00:27.425  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:00:27.425  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:00:27.426  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:00:27.426  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:00:27.445  3119  4355 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:00:27.445  3119  4355 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at hec.a(PG:42)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at hee.a(PG:102)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at czr.a(PG:65)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at kka.a(PG:108)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:00:27.445  3119  4355 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	... 15 more
07-27 09:00:27.445  3119  4355 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at fal.a(PG:38)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:00:27.445  3119  4355 E HttpOperation: 	... 17 more
,07-27 09:00:27.445  3119  4355 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:00:27.445  3119  4355 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	... 15 more
07-27 09:00:27.445  3119  4355 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:00:27.445  3119  4355 E ExperimentLoader: 	... 17 more
,07-27 09:00:27.661   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 476062, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:01:06.095  1507  2000 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-27 09:01:26.539  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:01:26.541  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:01:26.555  3400  4360 V GoogleAuthProtoRequest: [285] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:01:26.584  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 09:01:26.584  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-27 09:01:26.584  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:01:26.584  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: [285] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: [285] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:01:26.600  3400  4360 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:01:28.098  4181  4361 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:01:28.132  4181  4362 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:01:28.168  1507  3155 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:01:28.169  1507  3155 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:01:28.169  1507  3155 I GLSUser : [GLSUser] Extracting token using key: Auth,
,07-27 09:01:28.169  1507  3155 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:01:28.225  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-27 09:01:28.225  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:01:28.226  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:01:28.226  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:01:28.246  4181  4362 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:01:28.247  4181  4361 E BooksSync: Soft error
07-27 09:01:28.247  4181  4361 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:01:28.247  4181  4361 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:01:28.247  4181  4361 E BooksSync: Sync error
07-27 09:01:28.247  4181  4361 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:01:28.247  4181  4361 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:01:28.247  4181  4361 I BooksSync: Finished books sync
,07-27 09:01:28.254   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 566480, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:01:54.028   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=592451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:02:02.563  4223  4364 V KeepSync: Connecting to GoogleApiClient
07-27 09:02:02.563   873  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:02:02.612  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:02:02.618  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:02:02.657  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 09:02:02.657  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-27 09:02:02.657  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:02:02.657  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:02:02.683  1869  4365 V BaseAuthAsyncOperation: access token request failed
,07-27 09:02:02.685  4223  4364 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:02:02.754  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 09:02:02.754  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 09:02:02.754  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:02:02.755  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:02:02.778  4223  4364 E KeepSync: IOException
07-27 09:02:02.778  4223  4364 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:02:02.778  4223  4364 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:02:02.778  4223  4364 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:02:02.778  4223  4364 E KeepSync: 	... 10 more
,07-27 09:02:02.778  4223  4364 W KeepSync: Sync result 2
,07-27 09:02:02.787   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 600653, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:02:11.121   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=609544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:02:33.130  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:02:33.132  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:02:33.152  1507  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:02:33.152  1507  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:02:33.153  1507  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:02:33.153  1507  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:02:33.172  3119  4373 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:02:33.172  3119  4373 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:02:33.172  3119  4373 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	... 12 more
07-27 09:02:33.172  3119  4373 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at fal.a(PG:38)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:02:33.172  3119  4373 E HttpOperation: 	... 14 more
,07-27 09:02:33.244  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:02:33.245  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:02:33.245  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:02:33.245  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:02:33.279  3119  4373 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:02:33.279  3119  4373 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at hec.a(PG:42)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at hee.a(PG:102)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at czr.a(PG:65)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at kka.a(PG:108)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:02:33.279  3119  4373 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	... 15 more
07-27 09:02:33.279  3119  4373 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at fal.a(PG:38)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:02:33.279  3119  4373 E HttpOperation: 	... 17 more
,07-27 09:02:33.280  3119  4373 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:02:33.280  3119  4373 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	... 15 more
07-27 09:02:33.280  3119  4373 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:02:33.280  3119  4373 E ExperimentLoader: 	... 17 more
,07-27 09:02:33.420   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 628701, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:02:53.894   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=652317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:03:00.276  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:03:00.295  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:03:00.301  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:03:00.373  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-27 09:03:00.373  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-27 09:03:00.374  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:03:00.374  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:03:00.414  1507  1898 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-27 09:03:00.414  1507  1898 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-27 09:03:00.414  1507  1898 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-27 09:03:00.414  1507  1898 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-27 09:03:00.414  1507  1898 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-27 09:03:00.414  1507  1898 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-27 09:03:00.414  1507  1898 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:03:00.427  4044  4073 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-27 09:03:00.427  4044  4073 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-27 09:03:00.427  4044  4073 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-27 09:03:00.427  4044  4073 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-27 09:03:00.427  4044  4073 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-27 09:03:00.427  4044  4073 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-27 09:03:00.427  4044  4073 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-27 09:03:17.814   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=676237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:03:23.440   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=681863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:03:43.300   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=701724, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:03:49.680   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=708103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:04:06.747   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=725170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:05:26.731  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:05:26.733  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:05:26.745  3400  4392 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:05:26.799  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-27 09:05:26.799  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-27 09:05:26.799  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:05:26.799  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:05:26.815  3400  4392 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:05:26.816  3400  4392 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:05:31.048  4181  4393 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:05:31.082  4181  4394 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:05:31.123  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:05:31.123  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:05:31.123  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:05:31.123  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:05:31.173  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:05:31.173  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-27 09:05:31.173  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:05:31.173  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:05:31.194  4181  4394 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:05:31.195  4181  4393 E BooksSync: Soft error
07-27 09:05:31.195  4181  4393 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:05:31.195  4181  4393 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 09:05:31.195  4181  4393 E BooksSync: Sync error
07-27 09:05:31.195  4181  4393 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:05:31.195  4181  4393 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 09:05:31.196  4181  4393 I BooksSync: Finished books sync
,07-27 09:05:31.211   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 809416, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:06:13.351  4223  4397 V KeepSync: Connecting to GoogleApiClient
,07-27 09:06:13.351   873  1383 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:06:13.403  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:06:13.405  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:06:13.440  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 09:06:13.440  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 09:06:13.440  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:06:13.440  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:06:13.458  1869  4398 V BaseAuthAsyncOperation: access token request failed
,07-27 09:06:13.460  4223  4397 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:06:13.510  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-27 09:06:13.510  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-27 09:06:13.510  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:06:13.510  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:06:13.527  4223  4397 E KeepSync: IOException
07-27 09:06:13.527  4223  4397 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:06:13.527  4223  4397 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:06:13.527  4223  4397 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:06:13.527  4223  4397 E KeepSync: 	... 10 more
,07-27 09:06:13.527  4223  4397 W KeepSync: Sync result 2
,07-27 09:06:13.534   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 851523, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:06:43.908  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:06:43.909  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:06:43.936  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:06:43.936  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:06:43.936  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:06:43.937  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:06:43.951  3119  4401 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:06:43.951  3119  4401 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:06:43.951  3119  4401 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	... 12 more
07-27 09:06:43.951  3119  4401 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at fal.a(PG:38)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:06:43.951  3119  4401 E HttpOperation: 	... 14 more
,07-27 09:06:43.991  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:06:43.991  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:06:43.991  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:06:43.991  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:06:44.004  3119  4401 E HttpOperation: [getmobileexperiments] Unexpected exception
07-27 09:06:44.004  3119  4401 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at hec.a(PG:42)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at hee.a(PG:102)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at czr.a(PG:65)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at kka.a(PG:108)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:06:44.004  3119  4401 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	... 15 more
07-27 09:06:44.004  3119  4401 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at fal.a(PG:38)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:06:44.004  3119  4401 E HttpOperation: 	... 17 more
,07-27 09:06:44.005  3119  4401 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:06:44.005  3119  4401 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	... 15 more
07-27 09:06:44.005  3119  4401 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:06:44.005  3119  4401 E ExperimentLoader: 	... 17 more
,07-27 09:06:44.132   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 877076, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:07:05.867   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=904291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:07:15.733   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=914157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:08:05.774   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=964197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-27 09:08:12.630   873  1286 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
,07-27 09:08:12.630   873  1286 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,07-27 09:08:15.653   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=974077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:12:20.027   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,07-27 09:13:27.840  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:13:27.842  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:13:27.858  3400  4453 V GoogleAuthProtoRequest: [287] a.<init>: mAccountName set to: thalitester@gmail.com
,07-27 09:13:27.894  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-27 09:13:27.894  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-27 09:13:27.894  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:13:27.894  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:13:27.909  3400  4453 W ExperimentUpdateService: [287] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: [287] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-27 09:13:27.910  3400  4453 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-27 09:13:31.654   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1290077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-27 09:13:36.775  4181  4455 I BooksSync: Starting books sync for 61035162, extras: ade
,07-27 09:13:36.800  4181  4456 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-27 09:13:36.810  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:13:36.813  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:13:36.839  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:13:36.839  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:13:36.839  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:13:36.839  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:13:36.864  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:13:36.865  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:13:36.885  1507  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-27 09:13:36.885  1507  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-27 09:13:36.885  1507  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:13:36.885  1507  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:13:36.899  4181  4456 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-27 09:13:36.899  4181  4455 E BooksSync: Soft error
07-27 09:13:36.899  4181  4455 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:13:36.899  4181  4455 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-27 09:13:36.900  4181  4455 E BooksSync: Sync error
07-27 09:13:36.900  4181  4455 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-27 09:13:36.900  4181  4455 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-27 09:13:36.900  4181  4455 I BooksSync: Finished books sync
,07-27 09:13:36.908   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1295108, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:13:43.013   873  3509 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1301437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-27 09:14:34.380  4223  4466 V KeepSync: Connecting to GoogleApiClient
,07-27 09:14:34.381   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-27 09:14:34.422  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:14:34.424  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:14:34.452  1507  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-27 09:14:34.452  1507  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-27 09:14:34.453  1507  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:14:34.453  1507  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:14:34.470  1869  4467 V BaseAuthAsyncOperation: access token request failed
,07-27 09:14:34.471  4223  4466 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-27 09:14:34.518  1507  2574 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-27 09:14:34.519  1507  2574 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-27 09:14:34.519  1507  2574 I GLSUser : [GLSUser] Extracting token using key: Auth
07-27 09:14:34.519  1507  2574 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:14:34.536  4223  4466 E KeepSync: IOException
07-27 09:14:34.536  4223  4466 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-27 09:14:34.536  4223  4466 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-27 09:14:34.536  4223  4466 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-27 09:14:34.536  4223  4466 E KeepSync: 	... 10 more
,07-27 09:14:34.536  4223  4466 W KeepSync: Sync result 2
,07-27 09:14:34.547   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1352581, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-27 09:15:04.935  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:15:04.936  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-27 09:15:04.970  1507  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:15:04.970  1507  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-27 09:15:04.970  1507  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:15:04.970  1507  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:15:04.986  3119  4473 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-27 09:15:04.986  3119  4473 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at blb.a(PG:3937)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at czp.a(PG:18188)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:15:04.986  3119  4473 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	... 12 more
07-27 09:15:04.986  3119  4473 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at fal.a(PG:38)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:15:04.986  3119  4473 E HttpOperation: 	... 14 more
,07-27 09:15:05.043  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-27 09:15:05.043  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-27 09:15:05.043  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-27 09:15:05.043  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-27 09:15:05.071  3119  4473 E HttpOperation: [getmobileexperiments] Unexpected exception
,07-27 09:15:05.071  3119  4473 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jdm.a(PG:82)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jcs.o(PG:406)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jcn.a(PG:1379)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jcs.i(PG:143)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at hec.a(PG:42)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at hee.a(PG:102)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at czr.a(PG:65)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at kka.a(PG:108)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at czp.a(PG:19176)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at czp.a(PG:9081)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at czq.run(PG:1686)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:15:05.071  3119  4473 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jdj.a(PG:4091)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jdj.a(PG:1125)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jdm.a(PG:77)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	... 15 more
07-27 09:15:05.071  3119  4473 E HttpOperation: Caused by: faj: BadAuthentication
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at fal.a(PG:38)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	at jdj.a(PG:4089)
07-27 09:15:05.071  3119  4473 E HttpOperation: 	... 17 more
07-27 09:15:05.071  3119  4473 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-27 09:15:05.071  3119  4473 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jdm.a(PG:82)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jcs.o(PG:406)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jcn.a(PG:1379)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jcs.i(PG:143)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at hec.a(PG:42)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at hee.a(PG:102)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at czr.a(PG:65)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at kka.a(PG:108)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at czp.a(PG:19176)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at czp.a(PG:9081)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at czq.run(PG:1686)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jdj.a(PG:4091)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jdj.a(PG:1125)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jdm.a(PG:77)
07-27 09:15:05.071,  3119  4473 E ExperimentLoader: 	... 15 more
07-27 09:15:05.071  3119  4473 E ExperimentLoader: Caused by: faj: BadAuthentication
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at fal.a(PG:38)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	at jdj.a(PG:4089)
07-27 09:15:05.071  3119  4473 E ExperimentLoader: 	... 17 more
,07-27 09:15:05.200   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1373020, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),07-27 09:21:04.598  4526  4526 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-27 09:21:04.602  4526  4526 D AndroidRuntime: CheckJNI is OFF
07-27 09:21:04.638  4526  4526 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-27 09:21:04.683  4526  4526 I Radio-JNI: register_android_hardware_Radio DONE
07-27 09:21:04.706  4526  4526 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-27 09:21:04.717   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-27 09:21:04.718   873   886 I ActivityManager: Killing 3346:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-27 09:21:04.807   873  1383 D GraphicsStats: Buffer count: 2
07-27 09:21:04.807   873  1755 I WindowState: WIN DEATH: Window{bab48c u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-27 09:21:04.808   873  1304 D WifiService: Client connection lost with reason: 4
07-27 09:21:04.844   873   896 W PackageSettings: Skipping PackageSetting{1363285 com.example.hello/10273} due to missing metadata
07-27 09:21:04.864   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-27 09:21:04.864   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-27 09:21:04.865   873   886 E ActivityManager: Failure starting process com.test.thalitest
07-27 09:21:04.865   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-27 09:21:04.865   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:21:04.865   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:04.865   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:21:04.865   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 09:21:04.866   873   886 I ActivityManager:   Force finishing activity ActivityRecord{6abf171 u0 com.test.thalitest/.MainActivity t2}
07-27 09:21:04.867   873   896 I art     : Starting a blocking GC Explicit
07-27 09:21:04.878   873  1742 W ActivityManager: Spurious death for ProcessRecord{3c524f3 0:com.test.thalitest/u0a0}, curProc for 3346: null
07-27 09:21:04.921   873   896 I art     : Explicit concurrent mark sweep GC freed 37730(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 740us total 54.170ms
07-27 09:21:04.937   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-27 09:21:04.939  4526  4526 I art     : System.exit called, status: 0
07-27 09:21:04.939  4526  4526 I AndroidRuntime: VM exiting with result code 0.
07-27 09:21:04.950   873   896 I ActivityManager: Start proc 4536:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
07-27 09:21:04.950   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-27 09:21:04.961   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-27 09:21:04.965  1650  1650 I Keyboard.Facilitator: resetDictionaries() : en_US
07-27 09:21:04.967   873  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-27 09:21:04.974  3395  3395 D BluetoothMapAppObserver: onReceive
07-27 09:21:04.974  3395  3395 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-27 09:21:04.974  1771  2018 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 09:21:04.980  3193  3193 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
07-27 09:21:04.983  1650  4548 I Keyboard.Facilitator.DecoderInitializer: run()
07-27 09:21:04.991  1650  4548 I Decoder : createOrResetDecoder
07-27 09:21:05.012  1704  1704 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-27 09:21:05.031  4081  4551 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-27 09:21:05.038   873  1755 I ActivityManager: Start proc 4553:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-27 09:21:05.051  1507  1507 I ConfigService: onCreate
07-27 09:21:05.073  4081  4551 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
07-27 09:21:05.074  4081  4551 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-27 09:21:05.074  4081  4551 E AndroidRuntime: Process: android.process.acore, PID: 4081
07-27 09:21:05.074  4081  4551 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.074  4081  4551 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:21:05.077   873  4567 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:21:05.077   873  4567 E DropBoxManagerService: 	... 5 more
07-27 09:21:05.079   873  1846 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3346 uid 10000
07-27 09:21:05.080  1650  1650 I Keyboard.Facilitator: onFinishInput()
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-27 09:21:05.079  1507  4565 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-27 09:21:05.083  1507  4565 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:21:05.086  4553  4553 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-27 09:21:05.087  4081  4551 I Process : Sending signal. PID: 4081 SIG: 9
07-27 09:21:05.090  1507  4565 W SQLiteOpenHelper: Opened config.db in read-only mode
07-27 09:21:05.093   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 09:21:05.112  1650  4548 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-27 09:21:05.120  1727  1845 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-27 09:21:05.120   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-27 09:21:05.120   873   885 E PackageManager: Failed to write settings, restoring backup
07-27 09:21:05.120   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-27 09:21:05.120   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-27 09:21:05.120   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-27 09:21:05.120   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-27 09:21:05.120   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-27 09:21:05.120   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:21:05.120   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.120   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:21:05.124   873   886 E DropBoxManagerService: Can't write: system_server_wtf
07-27 09:21:05.124   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-27 09:21:05.124   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:21:05.124   873   886 E DropBoxManagerService: 	... 13 more
07-27 09:21:05.131  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
07-27 09:21:05.131  1507  1507 D AndroidRuntime: Shutting down VM
07-27 09:21:05.132  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
07-27 09:21:05.132  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
07-27 09:21:05.132  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-27 09:21:05.132  1507  1507 E AndroidRuntime: 	... 8 more
07-27 09:21:05.133   873  1703 I ActivityManager: Start proc 4571:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
07-27 09:21:05.134  1727  1845 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-27 09:21:05.134  1727  1845 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1727
07-27 09:21:05.134  1727  1845 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.134  1727  1845 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 09:21:05.137   873  1757 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 09:21:05.138   873  4579 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:21:05.138   873  4579 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:21:05.138   873  4579 E DropBoxManagerService: 	... 5 more
07-27 09:21:05.139   279   279 E lowmemorykiller: Error writing /proc/4081/oom_score_adj; errno=22
07-27 09:21:05.140  1727  1845 I Process : Sending signal. PID: 1727 SIG: 9
07-27 09:21:05.144   279   279 E lowmemorykiller: Error writing /proc/4081/oom_score_adj; errno=22
07-27 09:21:05.144   873  4585 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:21:05.144   873  4585 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:21:05.144   873  4585 E DropBoxManagerService: 	... 5 more
07-27 09:21:05.146  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
07-27 09:21:05.181   873   884 I ActivityManager: Killing 3732:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
07-27 09:21:05.186  1650  4548 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
07-27 09:21:05.188  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-27 09:21:05.188  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-27 09:21:05.197  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-27 09:21:05.197  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-27 09:21:05.197  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-27 09:21:05.198  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-27 09:21:05.203  1650  4548 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-27 09:21:05.203  1650  4548 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-27 09:21:05.203  1650  4548 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-27 09:21:05.203  1650  4548 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-27 09:21:05.206  1650  4548 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-27 09:21:05.206  1650  4548 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-27 09:21:05.235   873  1304 D WifiService: Client connection lost with reason: 4
07-27 09:21:05.238   873  1755 D GraphicsStats: Buffer count: 1
07-27 09:21:05.238   873  1724 I WindowState: WIN DEATH: Window{529866 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-27 09:21:05.253   873  1703 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
07-27 09:21:05.253   873  1703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
07-27 09:21:05.253   873  1703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
07-27 09:21:05.254   873  1703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
07-27 09:21:05.254   873  1703 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
07-27 09:21:05.254   279   279 E lowmemorykiller: Error opening /proc/4081/oom_score_adj; errno=2
07-27 09:21:05.255   279   279 E lowmemorykiller: Error opening /proc/4081/oom_score_adj; errno=2
07-27 09:21:05.256   873  1755 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1727) has died
07-27 09:21:05.256   873  1755 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40997ms
07-27 09:21:05.257   873  1755 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-27 09:21:05.263   873  1847 I ActivityManager: Process android.process.acore (pid 4081) has died
07-27 09:21:05.263   873  1847 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40990ms
07-27 09:21:05.279   873   886 I ActivityManager: Start proc 4588:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 09:21:05.291   873  1703 I ActivityManager: Start proc 4600:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
07-27 09:21:05.294  1869  1869 W RocketImpressions: ClearcutLogger connection suspended: 1
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 09:21:05.327  4588  4588 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 09:21:05.327  4588  4588 D AndroidRuntime: Shutting down VM
07-27 09:21:05.337  4588  4588 E AndroidRuntime: FATAL EXCEPTION: main
07-27 09:21:05.337  4588  4588 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4588
07-27 09:21:05.337  4588  4588 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-27 09:21:05.337  4588  4588 E AndroidRuntime: 	... 10 more
07-27 09:21:05.341   873  1681 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-27 09:21:05.342  4588  4588 I Process : Sending signal. PID: 4588 SIG: 9
07-27 09:21:05.342   873  4616 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:21:05.342   873  4616 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:21:05.342   873  4616 E DropBoxManagerService: 	... 5 more
07-27 09:21:05.343  1869  1869 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-27 09:21:05.343  1869  1869 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-27 09:21:05.352  1869  1869 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-27 09:21:05.352  1869  1869 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-27 09:21:05.360  4600  4600 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
07-27 09:21:05.364  1869  4618 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-27 09:21:05.371   873  1847 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
07-27 09:21:05.372   873  1847 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
07-27 09:21:05.372   873  1847 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
07-27 09:21:05.372   873  1847 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
07-27 09:21:05.379  4600  4600 I MultiDex: VM with version 2.1.0 has multidex support
07-27 09:21:05.379  4600  4600 I MultiDex: install
07-27 09:21:05.379  4600  4600 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-27 09:21:05.386  1869  4618 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
07-27 09:21:05.386  1869  4618 E AndroidRuntime: Process: com.google.android.gms, PID: 1869
07-27 09:21:05.386  1869  4618 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-27 09:21:05.386  1869  4618 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
07-27 09:21:05.389   873  1847 I ActivityManager: Start proc 4620:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
07-27 09:21:05.391   873  1846 W ActivityManager: Spurious death for ProcessRecord{5333f0b 4620:com.google.android.googlequicksearchbox/u0a28}, curProc for 4588: null
07-27 09:21:05.392   873  4626 E DropBoxManagerService: Can't write: system_app_crash
07-27 09:21:05.392   873  4626 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-27 09:21:05.392   873  4626 E DropBoxManagerService: 	... 5 more
07-27 09:21:05.392  1869  4618 I Process : Sending signal. PID: 1869 SIG: 9
07-27 09:21:05.396  4000  4617 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-27 09:21:05.434  4000  4617 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-27 09:21:05.437  4600  4600 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
07-27 09:21:05.453   279   279 E lowmemorykiller: Error writing /proc/1869/oom_score_adj; errno=22

```
