#### Test 796897756520203_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-09 15:36:08.769  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:36:08.786  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 15:36:08.791  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 15:36:08.839  1521  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-09 15:36:08.839  1521  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:36:08.839  1521  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:08.839  1521  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-09 15:36:08.868  1521  1532 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:36:08.868  1521  1532 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:36:08.868  1521  1532 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:36:08.868  1521  1532 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:36:08.868  1521  1532 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:36:08.868  1521  1532 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:36:08.868  1521  1532 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 15:36:08.879  2579  2610 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:36:08.879  2579  2610 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:36:08.879  2579  2610 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:36:08.879  2579  2610 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:36:08.879  2579  2610 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:36:08.879  2579  2610 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:36:08.879  2579  2610 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 15:36:09.379  3337  3337 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 15:36:09.384  3337  3337 D AndroidRuntime: CheckJNI is OFF
08-09 15:36:09.419  3337  3337 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 15:36:09.461  3337  3337 I Radio-JNI: register_android_hardware_Radio DONE
08-09 15:36:09.481  3337  3337 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 15:36:09.485   874   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 15:36:09.530   874   885 I ActivityManager: Start proc 3347:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-09 15:36:09.537  3337  3337 D AndroidRuntime: Shutting down VM
08-09 15:36:09.652  3347  3347 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-09 15:36:09.693  3347  3347 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-09 15:36:09.798  3347  3347 I LibraryLoader: Time to load native libraries: 98 ms (timestamps 1722-1820)
08-09 15:36:09.799  3347  3347 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 15:36:09.830  3347  3347 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12d9d7a}
,08-09 15:36:09.831  3347  3347 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 15:36:09.831  3347  3347 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 15:36:09.839  3347  3347 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-09 15:36:09.841  3347  3347 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 15:36:09.891  3347  3362 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-09 15:36:09.900  3347  3347 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 15:36:09.911  3347  3347 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 15:36:09.911  3347  3347 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 15:36:09.911  3347  3347 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 15:36:09.911  3347  3347 I Adreno  : Build Date                       : 10/20/15
08-09 15:36:09.911  3347  3347 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 15:36:09.911  3347  3347 I Adreno  : Local Branch                     : M14
08-09 15:36:09.911  3347  3347 I Adreno  : Remote Branch                    : 
08-09 15:36:09.911  3347  3347 I Adreno  : Remote Branch                    : 
,08-09 15:36:09.911  3347  3347 I Adreno  : Reconstruct Branch               : 
,08-09 15:36:10.003   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60cafc6:true
,08-09 15:36:10.050  3347  3347 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-09 15:36:10.068  3347  3347 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-09 15:36:10.104   874   887 W ActivityManager: Activity pause timeout for ActivityRecord{2df8d33 u0 com.test.thalitest/.MainActivity t4}
,08-09 15:36:10.134  3347  3384 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-09 15:36:10.146  3347  3371 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-09 15:36:10.197  3347  3384 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 15:36:10.266   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +662ms (total +757ms)
,08-09 15:36:10.278  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-09 15:36:10.331  3347  3347 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3347
,08-09 15:36:10.413  3347  3347 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 15:36:10.718  3347  3387 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680930512
,08-09 15:36:10.748  3347  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 15:36:10.748  3347  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 15:36:10.748  3347  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 15:36:10.748  3347  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 15:36:10.748  3347  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-09 15:36:10.749  3347  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4ab719 added. We now have 1 listener(s)
,08-09 15:36:10.765  3347  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-09 15:36:10.768  3347  3387 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 15:36:10.770  3347  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 15:36:10.771  3347  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 15:36:10.778  3347  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@382f88c added. We now have 1 listener(s)
08-09 15:36:10.778  3347  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:36:10.781   874  1318 D WifiService: New client listening to asynchronous messages
,08-09 15:36:10.788  3347  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-09 15:36:10.788  3347  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 15:36:10.789  3347  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-09 15:36:10.789  3347  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 15:36:10.789  3347  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-09 15:36:10.801  3347  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:36:10.802  3347  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-09 15:36:10.804  3347  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:10.805  3347  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:10.805  3347  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-09 15:36:10.805  3347  3387 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 15:36:10.806  3347  3387 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-09 15:36:10.808  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:10.837  3347  3347 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 15:36:12.485  3347  3394 W jxcore-log: Initializing JXcore engine
,08-09 15:36:12.485  3347  3394 W jxcore-log: JXcore engine is ready
,08-09 15:36:12.521  3394  3394 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-09 15:36:12.521  3394  3394 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10637]" dev="sockfs" ino=10637 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-09 15:36:12.521  3394  3394 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-09 15:36:12.521  3394  3394 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24784]" dev="sockfs" ino=24784 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-09 15:36:12.534  3347  3394 W jxcore-log: Starting JXcore engine
,08-09 15:36:12.612  3347  3394 W jxcore-log: Platform android
08-09 15:36:12.612  3347  3394 W jxcore-log: 
08-09 15:36:12.612  3347  3394 W jxcore-log: Process ARCH arm
08-09 15:36:12.612  3347  3394 W jxcore-log: 
,08-09 15:36:12.821  3347  3394 I jxcore-log: JXcore Cordova bridge is ready!
08-09 15:36:12.821  3347  3394 I jxcore-log: 
08-09 15:36:12.821  3347  3394 W jxcore-log: JXcore engine is started
,08-09 15:36:12.834  3347  3387 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-09 15:36:12.840  3347  3347 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 15:36:28.225  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 15:36:28.225  3347  3394 I jxcore-log: 
,08-09 15:36:28.228  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 15:36:28.228  3347  3394 I jxcore-log: 
,08-09 15:36:28.230  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:28.231  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:28.232  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:28.232  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:28.237  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 15:36:28.237  3347  3394 I jxcore-log: 
,08-09 15:36:28.245  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 15:36:28.245  3347  3394 I jxcore-log: 
,08-09 15:36:28.601  3347  3394 I jxcore-log: Running unit tests
08-09 15:36:28.601  3347  3394 I jxcore-log: 
,08-09 15:36:28.601  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-09 15:36:28.602  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57e70f0 added. We now have 2 listener(s)
,08-09 15:36:28.603  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 15:36:28.603  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 15:36:28.603  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:36:28.603  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:36:28.603  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6df6669 added. We now have 2 listener(s)
08-09 15:36:28.603  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:36:28.604  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 15:36:28.605  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:36:28.609  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:28.609  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:28.610  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:28.610  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:28.610  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:36:28.611  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:28.612  3347  3394 D ExecuteNativeTests: Running unit tests
,08-09 15:36:28.694  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:36:28.694  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f added. We now have 3 listener(s)
,08-09 15:36:28.695  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:36:28.695  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 15:36:28.695  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:36:28.695  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:36:28.695  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c added. We now have 3 listener(s)
08-09 15:36:28.696  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:36:28.696  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 15:36:28.697  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:36:28.700  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:28.700  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:28.700  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:28.700  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:28.700  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:36:28.701  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:28.702  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-09 15:36:28.702  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 15:36:28.702  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 15:36:28.703  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 15:36:28.704  3347  3394 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-09 15:36:28.704  3347  3394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 15:36:28.704  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:36:28.704  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:28.704  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:28.704  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:28.705  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:28.705  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:28.705  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:28.706  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:28.706  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.706  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:36:28.706  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 15:36:28.706  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f removed from the list
08-09 15:36:28.706  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:28.706  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c removed from the list
08-09 15:36:28.706  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:36:28.706  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.707  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.707  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.707  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:28.707  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:28.707  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:28.707  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:28.709  3347  3394 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-09 15:36:28.709  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:28.709  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:28.709  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:28.710  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:28.710  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.710  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.710  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:28.710  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:28.710  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:28.710  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:28.710  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.710  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.710  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.710  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.710  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:28.710  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:28.711  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:28.711  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 15:36:28.715  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 15:36:28.716  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 15:36:28.716  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:28.716  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:28.717  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:36:28.717  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:28.717  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.717  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.717  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:28.717  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:28.717  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:28.717  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:28.717  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.717  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.717  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:28.717  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:28.717  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:28.718  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 15:36:28.718  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:28.718  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:28.718  3347  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 15:36:28.719  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:36:28.720  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:28.720  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:28.720  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:28.720  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:28.720  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 15:36:28.720  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 15:36:28.721  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 15:36:28.721  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 15:36:28.721  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:36:28.721  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:36:28.721  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:36:28.727  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-09 15:36:28.728  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-09 15:36:28.729  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 15:36:28.729  3347  3394 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 15:36:28.731  3347  3394 I io.jxcore.node.ConnectionHelper: start: OK
,08-09 15:36:29.231  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:36:33.734  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:33.736  3347  3394 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,08-09 15:36:33.741  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:36:33.741  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:33.742  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-09 15:36:33.742  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:33.742  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-09 15:36:33.742  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:36:33.743  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:36:33.743  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:36:33.743  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:36:33.745  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:36:33.747  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 15:36:33.750  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 15:36:33.750  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-09 15:36:33.751  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:36:33.751  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:36:33.753  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:36:33.753  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:33.753  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:36:33.753  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:33.754  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:33.754  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:33.754  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:33.754  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:33.756  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:33.756  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:33.757  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:33.757  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:33.757  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:33.758  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:33.761  3347  3394 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-09 15:36:33.765  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:36:33.767  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:33.767  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:33.767  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:33.768  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:33.768  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 15:36:33.770  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:33.771  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 15:36:33.771  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-09 15:36:33.772  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-09 15:36:33.772  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:36:33.772  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:36:33.777  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-09 15:36:33.777  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 15:36:33.778  3347  3394 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-09 15:36:33.778  3347  3394 I io.jxcore.node.ConnectionHelper: start: OK
08-09 15:36:33.778  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-09 15:36:34.279  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:36:38.779  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:38.779  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 15:36:38.779  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-09 15:36:38.780  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:38.780  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-09 15:36:38.780  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-09 15:36:38.781  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-09 15:36:38.781  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:36:38.781  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:36:38.782  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:36:38.784  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 15:36:38.786  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 15:36:38.787  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-09 15:36:38.787  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:36:38.788  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 15:36:39.290  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:36:39.290  3347  3347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:39.290  3347  3347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-09 15:36:43.788  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.789  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.789  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:36:43.789  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.790  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.790  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:36:43.790  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.790  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.791  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
,08-09 15:36:43.791  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.791  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.793  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.794  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:43.796  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.796  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.796  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.796  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
,08-09 15:36:43.799  3347  3394 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-09 15:36:43.801  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.801  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 15:36:43.802  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.802  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.802  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.803  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:43.803  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.803  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:43.804  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.804  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.804  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.804  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.805  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.806  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:43.807  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.807  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.807  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.808  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.810  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 15:36:43.810  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.810  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.811  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.811  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.811  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.811  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.811  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
,08-09 15:36:43.812  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.812  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.812  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.812  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.812  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.813  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.813  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:43.814  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.814  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.814  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.815  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
,08-09 15:36:43.816  3347  3394 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-09 15:36:43.816  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.817  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.817  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.817  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.817  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.817  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.818  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.818  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:43.818  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.818  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.818  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.819  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.819  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.819  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.820  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.820  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 15:36:43.820  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.820  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.822  3347  3394 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-09 15:36:43.822  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:36:43.822  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.822  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.823  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.823  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.823  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.823  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.823  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.824  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.824  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.824  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.824  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.824  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:36:43.824  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.825  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.825  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.826  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.826  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.826  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-09 15:36:43.828  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 15:36:43.828  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:36:43.828  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:36:43.828  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:43.828  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:43.829  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-09 15:36:43.829  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:36:43.829  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:36:43.829  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.829  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.829  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.829  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.830  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.830  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.830  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.830  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:43.830  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.830  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.830  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.830  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.830  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.831  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.832  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.832  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 15:36:43.832  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.832  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.834  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:36:43.836  3347  3394 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 15:36:43.836  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-09 15:36:43.850  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-09 15:36:43.851  3347  3394 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-09 15:36:43.851  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 15:36:43.852  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 15:36:43.853  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 15:36:43.854  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 15:36:43.854  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-09 15:36:43.855  3347  3394 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-09 15:36:43.855  3347  3394 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-09 15:36:43.855  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:36:43.855  3347  3394 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-09 15:36:43.855  3347  3394 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-09 15:36:43.855  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-09 15:36:43.855  3347  3394 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 15:36:43.855  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-09 15:36:43.857  3347  3394 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
,08-09 15:36:43.857  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-09 15:36:43.858  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-09 15:36:43.858  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-09 15:36:43.859  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-09 15:36:43.859  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-09 15:36:43.859  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-09 15:36:43.859  3347  3394 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 15:36:43.859  3347  3394 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-09 15:36:43.860  3347  3399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
,08-09 15:36:43.860  3347  3399 E BluetoothDevice: Bluetooth is not enabled
08-09 15:36:43.860  3347  3399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-09 15:36:43.860  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.860  3347  3399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-09 15:36:43.860  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.860  3347  3399 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-09 15:36:43.860  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:36:43.860  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.860  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.861  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.861  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-09 15:36:43.861  3347  3347 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-09 15:36:43.861  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.861  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.862  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.862  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.862  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.862  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.862  3347  3347 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-09 15:36:43.862  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.862  3347  3347 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:36:43.862  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.862  3347  3400 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-09 15:36:43.862  3347  3347 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-09 15:36:43.862  3347  3347 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:43.863  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.863  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.863  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.863  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.864  3347  3394 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-09 15:36:43.864  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.864  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.864  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.864  3347  3399 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
08-09 15:36:43.865  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.865  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.865  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.865  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.865  3347  3399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-09 15:36:43.865  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.865  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.865  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:36:43.865  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.865  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.865  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.865  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.866  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.866  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.866  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.866  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.867  3347  3394 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-09 15:36:43.867  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.867  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.867  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.868  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.868  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.868  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.868  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.868  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.868  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
,08-09 15:36:43.868  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.868  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.868  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.868  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.868  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.869  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.869  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.869  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.869  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.870  3347  3394 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-09 15:36:43.870  3347  3394 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-09 15:36:43.870  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 15:36:43.870  3347  3394 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-09 15:36:43.870  3347  3394 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 15:36:43.870  3347  3394 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-09 15:36:43.870  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 15:36:43.870  3347  3394 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-09 15:36:43.870  3347  3394 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 15:36:43.871  3347  3394 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 15:36:43.871  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 15:36:43.871  3347  3394 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-09 15:36:43.871  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:43.871  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:43.871  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:43.871  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.871  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.871  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.872  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.872  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.872  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.872  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.872  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.872  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:43.872  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.872  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.872  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:43.873  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:43.873  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.873  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.873  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:43.873  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.873  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:43.874  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:43.874  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:43.874  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:43.874  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:43.874  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:43.874  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:48.875  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:48.876  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.876  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:36:48.876  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.877  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.877  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:48.877  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:36:48.878  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:48.878  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:48.879  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:36:48.879  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.879  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.879  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
,08-09 15:36:48.880  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.880  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.880  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:36:48.880  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.881  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.881  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.881  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:48.883  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:48.883  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:48.883  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:48.884  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.889  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 15:36:48.890  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:36:48.891  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-09 15:36:48.891  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
,08-09 15:36:48.892  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-09 15:36:48.892  3347  3347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,08-09 15:36:48.893  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:48.893  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-09 15:36:48.893  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.893  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
,08-09 15:36:48.893  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:48.893  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:48.893  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:36:48.893  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:36:48.893  3347  3347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-09 15:36:48.893  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:36:48.894  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.894  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:48.894  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 15:36:48.894  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.894  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:48.894  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:36:48.895  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:48.897  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:48.897  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:48.897  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.898  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.897  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:36:48.902  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
,08-09 15:36:48.902  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.902  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.902  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:48.902  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:36:48.902  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.902  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.902  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.902  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.903  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:48.903  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:48.903  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:36:48.903  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.904  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 15:36:48.904  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:36:48.904  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 15:36:48.904  3347  3394 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-09 15:36:48.905  3347  3394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 15:36:48.905  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 15:36:48.905  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:48.905  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 15:36:48.905  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:48.905  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:48.905  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:36:48.906  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:48.906  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.906  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.906  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:48.906  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.906  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.906  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:48.906  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.906  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.906  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.906  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.907  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:48.907  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:48.907  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.907  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.909  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:36:48.909  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:48.909  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:36:48.910  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:36:48.910  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.910  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.910  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:48.910  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.910  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.910  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:48.910  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:36:48.910  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.910  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.911  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.911  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:48.911  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:48.911  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.911  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.912  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:36:48.912  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:36:48.912  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:36:48.913  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:36:48.913  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:36:48.913  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.913  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c44ac7f not in the list
08-09 15:36:48.913  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.913  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.913  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:48.913  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.913  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:48.913  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.914  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.914  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:36:48.914  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:36:48.914  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.914  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f06544c not in the list
08-09 15:36:48.915  3347  3394 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-09 15:36:48.916  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 15:36:48.916  3347  3394 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-09 15:36:48.916  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-09 15:36:48.916  3347  3394 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-09 15:36:48.916  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 15:36:48.919  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 15:36:48.919  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-09 15:36:48.920  3347  3394 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-09 15:36:48.920  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 15:36:48.920  3347  3394 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-09 15:36:48.920  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 15:36:48.920  3347  3394 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-09 15:36:48.920  3347  3394 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-09 15:36:48.921  3347  3394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-09 15:36:48.921  3347  3394 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-09 15:36:48.922  3347  3394 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-09 15:36:48.922  3347  3394 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-09 15:36:48.922  3347  3394 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-09 15:36:48.922  3347  3394 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-09 15:36:48.924  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 15:36:48.924  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b3cee76 added. We now have 3 listener(s)
08-09 15:36:48.924  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:36:48.925   874  1610 D WifiService: setWifiEnabled: true pid=3347, uid=10000
08-09 15:36:48.926   874  1610 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 15:36:48.929  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:36:48.929  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eddac77 added. We now have 4 listener(s)
,08-09 15:36:48.929  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:36:48.931  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.931  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.931  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.931  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eddac77 removed from the list
08-09 15:36:48.932  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:36:48.932  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.932  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:36:48.933  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:36:48.934  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f8e0e4 added. We now have 4 listener(s)
08-09 15:36:48.934  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:36:48.935  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:36:48.935  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f8e0e4 removed from the list
08-09 15:36:48.936  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:36:48.936  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:36:48.936  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:36:48.937  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:36:48.938  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d5694d added. We now have 4 listener(s)
08-09 15:36:48.938  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:36:48.939   874  1841 D WifiService: setWifiEnabled: false pid=3347, uid=10000
,08-09 15:36:48.939   874  1841 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:36:48.945   874   891 I ActivityManager: Start proc 3402:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-09 15:36:48.946   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-09 15:36:48.948  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:48.948  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:48.948  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.948  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:48.949  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:48.949  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:48.949  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.949  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:48.964   874   887 I ActivityManager: Start proc 3413:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-09 15:36:48.965  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:36:48.966  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:48.966  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:48.967  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:48.967  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:48.967  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:36:48.967  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:36:48.968   874  1317 D WifiConfigStore: loaded 0 passpoint configs
08-09 15:36:48.968   874  1317 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 15:36:48.968   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-09 15:36:48.969   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-09 15:36:48.970   874  1317 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
08-09 15:36:48.970   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-09 15:36:48.971   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
,08-09 15:36:48.971   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 15:36:48.971   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 15:36:48.971   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
,08-09 15:36:49.012  3413  3413 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-09 15:36:49.020   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 15:36:49.021   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:36:49.021   372   872 D CommandListener: Setting iface cfg
08-09 15:36:49.021   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-09 15:36:49.021   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 15:36:49.032   874  1317 E native  : do suspend true
,08-09 15:36:49.041  3402  3402 D AdapterServiceConfig: Adding HeadsetService
08-09 15:36:49.041  3402  3402 D AdapterServiceConfig: Adding A2dpService
08-09 15:36:49.041  3402  3402 D AdapterServiceConfig: Adding HidService
08-09 15:36:49.041  3402  3402 D AdapterServiceConfig: Adding HealthService
08-09 15:36:49.041  3402  3402 D AdapterServiceConfig: Adding PanService
08-09 15:36:49.042  3402  3402 D AdapterServiceConfig: Adding GattService
08-09 15:36:49.042  3402  3402 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 15:36:49.046   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
08-09 15:36:49.046   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 15:36:49.048  1469  1469 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
08-09 15:36:49.048  1469  1469 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-09 15:36:49.049   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:36:49.051  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:49.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:49.051  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:49.051  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:49.052  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:49.052  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:49.052  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:49.052  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:49.053  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:49.053  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:49.053  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:36:49.053  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:49.055  1864  2111 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 15:36:49.069   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eff24f3:true
,08-09 15:36:49.069  3402  3402 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 15:36:49.072  3402  3402 I bt_bluedroid: init
08-09 15:36:49.072  3402  3435 I BluetoothAdapterState: Entering OffState
,08-09 15:36:49.075  3402  3436 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 15:36:49.077  3402  3436 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-09 15:36:49.077  3402  3436 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 15:36:49.077  3402  3436 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-09 15:36:49.078  3402  3402 I bt_bluedroid: get_profile_interface socket
,08-09 15:36:49.079  3402  3402 I bt_bluedroid: get_profile_interface sdp
,08-09 15:36:49.082  3402  3420 I bt_bluedroid: config_hci_snoop_log
,08-09 15:36:49.082   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-09 15:36:49.083  3402  3441 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-09 15:36:49.085  3402  3435 D BluetoothAdapterState: Current state: OFF, message: 0
08-09 15:36:49.086  3413  3413 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-09 15:36:49.085  3402  3441 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:36:49.087  3402  3435 D BluetoothAdapterProperties: Setting state to 14
08-09 15:36:49.088  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 15:36:49.092  3402  3435 D BluetoothBondStateMachine: make
,08-09 15:36:49.096  3402  3444 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 15:36:49.109  3402  3402 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 15:36:49.111  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:36:49.111  3402  3402 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 15:36:49.111  3402  3435 I BluetoothAdapterState: Entering PendingCommandState
08-09 15:36:49.112  3402  3402 D BtGatt.GattService: Received start request. Starting profile...
08-09 15:36:49.112  3402  3402 D BtGatt.GattService: start()
08-09 15:36:49.112  3402  3402 I bt_bluedroid: get_profile_interface gatt
08-09 15:36:49.112  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:36:49.112  3402  3402 D BtGatt.AdvertiseManager: advertise manager created
,08-09 15:36:49.115   874  1919 I ActivityManager: Killing 2662:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-09 15:36:49.178  3402  3402 V BluetoothAdapterState: isTurningOff()=false
08-09 15:36:49.179  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:36:49.179  3402  3402 V BluetoothAdapterState: isBleTurningOn()=true
08-09 15:36:49.179  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:36:49.180  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-09 15:36:49.181  3402  3435 I bt_bluedroid: enable
08-09 15:36:49.183  3402  3436 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-09 15:36:49.183  3402  3436 I bt_hci  : start_up
,08-09 15:36:49.208  3402  3436 I bt_vendor: alloc value 0xb39ea189
08-09 15:36:49.208  3402  3436 I bt_vendor: init
08-09 15:36:49.209  3402  3436 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 15:36:49.209  3402  3436 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 15:36:49.315  3402  3436 D bt_hci  : start_up starting async portion
,08-09 15:36:49.316  3402  3448 I bt_hci  : event_finish_startup
08-09 15:36:49.316  3402  3448 I bt_hci_h4: hal_open
08-09 15:36:49.317  3402  3448 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 15:36:49.324  3402  3448 I bt_userial_vendor: device fd = 51 open
,08-09 15:36:49.359  3402  3448 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:36:49.391  3402  3448 D bt_hwcfg: Chipset BCM4354A2
08-09 15:36:49.392  3402  3448 D bt_hwcfg: Target name = [BCM4354A2]
,08-09 15:36:49.392  3402  3448 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 15:36:49.403  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:36:50.059  3402  3448 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 15:36:50.060  3402  3448 D bt_hwcfg: Settlement delay -- 100 ms
08-09 15:36:50.061  3402  3448 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 15:36:50.177  3402  3448 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:36:50.179  3402  3448 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 15:36:50.208  3402  3448 I bt_hwcfg: vendor lib fwcfg completed
,08-09 15:36:50.209  3402  3448 I bt_vendor: firmware callback
08-09 15:36:50.209  3402  3448 I bt_hci  : firmware_config_callback
,08-09 15:36:50.220  3402  3450 I bt_btu  : btu_task pending for preload complete event
,08-09 15:36:50.220  3402  3450 I bt_btu_task: Bluetooth chip preload is complete
,08-09 15:36:50.220  3402  3450 I bt_btu  : btu_task received preload complete event
,08-09 15:36:50.231  3402  3450 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 15:36:50.231  3402  3450 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-09 15:36:50.232  3402  3450 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 15:36:50.232  3402  3450 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 15:36:50.232  3402  3450 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 15:36:50.232  3402  3450 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 15:36:50.233  3402  3450 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 15:36:50.233  3402  3450 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 15:36:50.233  3402  3450 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 15:36:50.234  3402  3450 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 15:36:50.234  3402  3450 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 15:36:50.234  3402  3450 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 15:36:50.235  3402  3450 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 15:36:50.235  3402  3450 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 15:36:50.235  3402  3450 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 15:36:50.371  3402  3450 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3967d9d
08-09 15:36:50.371  3402  3450 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3967d9d 
,08-09 15:36:50.384  3402  3441 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 15:36:50.387  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 15:36:50.388  3402  3441 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:36:50.391  3402  3441 D BluetoothAdapterProperties: Name is: Nexus 6
08-09 15:36:50.394  3402  3441 D BluetoothAdapterProperties: Scan Mode:20
08-09 15:36:50.395  3402  3441 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:36:50.395  3402  3441 D bt_hci  : do_postload posting postload work item
08-09 15:36:50.396  3402  3448 I bt_hci  : event_postload
,08-09 15:36:50.396  3402  3448 I bt_vendor: sco_config_cb
,08-09 15:36:50.396  3402  3448 I bt_hci  : sco_config_callback postload finished.
,08-09 15:36:50.401  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-09 15:36:50.402  3402  3448 I bt_vendor: low_power_mode_cb
08-09 15:36:50.404  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:36:50.408  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:36:50.409  3402  3441 D bt_bte_conf: Device ID record 1 : primary
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   vendorId            = 000f
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   vendorIdSource      = 0001
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   product             = 1200
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   version             = 1436
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   clientExecutableURL = 
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   serviceDescription  = 
08-09 15:36:50.409  3402  3441 D bt_bte_conf:   documentationURL    = 
08-09 15:36:50.409  3402  3441 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 15:36:50.409  3402  3436 D bt_stack_manager: event_start_up_stack finished
,08-09 15:36:50.411  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-09 15:36:50.411  3402  3435 D BluetoothAdapterProperties: Setting state to 15
08-09 15:36:50.411  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 15:36:50.413  3402  3435 I BluetoothAdapterState: Entering BleOnState
,08-09 15:36:50.417  3402  3435 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-09 15:36:50.417  3402  3435 D BluetoothAdapterProperties: Setting state to 11
,08-09 15:36:50.417  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 15:36:50.425  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:50.427  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:50.430  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:50.459   874   887 I ActivityManager: Start proc 3457:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-09 15:36:50.463  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:36:50.464  3402  3402 D HeadsetService: Received start request. Starting profile...
,08-09 15:36:50.468  3402  3402 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-09 15:36:50.468  3402  3402 D HeadsetStateMachine: make
,08-09 15:36:50.474  3402  3435 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:36:50.477  3402  3402 D HeadsetStateMachine: max_hf_connections = 1
,08-09 15:36:50.479  3402  3402 I bt_bluedroid: get_profile_interface handsfree
,08-09 15:36:50.481  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 15:36:50.481  3402  3441 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-09 15:36:50.486  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:36:50.487   874   874 D BluetoothA2dp: Proxy object connected,
,08-09 15:36:50.488  3402  3402 D A2dpService: Received start request. Starting profile...
,08-09 15:36:50.489  3402  3402 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-09 15:36:50.490  3402  3402 I bt_bluedroid: get_profile_interface avrcp
,08-09 15:36:50.501  3402  3402 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 15:36:50.501  3402  3402 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-09 15:36:50.501  3402  3402 D A2dpStateMachine: make
,08-09 15:36:50.503  3402  3402 I bt_bluedroid: get_profile_interface a2dp
,08-09 15:36:50.503  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-09 15:36:50.505  3402  3402 I BluetoothHidServiceJni: classInitNative: succeeds
,08-09 15:36:50.506  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:36:50.506  3402  3471 D A2dpStateMachine: Enter Disconnected: -2
,08-09 15:36:50.507  3402  3402 D HidService: Received start request. Starting profile...
,08-09 15:36:50.507  3402  3402 I bt_bluedroid: get_profile_interface hidhost
,08-09 15:36:50.508  3402  3402 D HidService: setHidService(): set to: null
08-09 15:36:50.508  3402  3441 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39493e5
08-09 15:36:50.508  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-09 15:36:50.508  1355  1355 D BluetoothInputDevice: Proxy object connected
08-09 15:36:50.508  3402  3402 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 15:36:50.508  1355  1355 D HidProfile: Bluetooth service connected
,08-09 15:36:50.509  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:36:50.510  3402  3402 D HealthService: Received start request. Starting profile...
08-09 15:36:50.511  3402  3402 I bt_bluedroid: get_profile_interface health
,08-09 15:36:50.512  3402  3402 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-09 15:36:50.513  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:36:50.514  3402  3402 D PanService: Received start request. Starting profile...
08-09 15:36:50.514  3402  3402 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-09 15:36:50.515  3402  3402 I bt_bluedroid: get_profile_interface pan
08-09 15:36:50.515  3402  3441 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 15:36:50.516  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:36:50.517  1355  1355 D PanProfile: Bluetooth service connected
,08-09 15:36:50.520  3402  3402 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:36:50.521  1355  1355 D BluetoothMap: Proxy object connected
,08-09 15:36:50.522  1355  1355 D MapProfile: Bluetooth service connected
08-09 15:36:50.522  1355  1355 D BluetoothMap: getConnectedDevices()
,08-09 15:36:50.523  1355  1355 D BluetoothMap: Bluetooth is Not enabled
08-09 15:36:50.523  3402  3402 D BluetoothMapService: Received start request. Starting profile...
,08-09 15:36:50.524  3402  3402 D BluetoothMapService: start(),
08-09 15:36:50.526  3402  3402 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-09 15:36:50.527  3402  3402 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 15:36:50.528  3402  3402 D BluetoothMapAppObserver: createReceiver(),
08-09 15:36:50.529  3402  3402 D BluetoothMapAppObserver: initObservers()
08-09 15:36:50.529  3402  3402 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 15:36:50.539  3402  3402 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:36:50.539  3402  3402 V BluetoothAdapterState: isTurningOn()=true
08-09 15:36:50.540  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:36:50.540  3402  3463 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 15:36:50.540  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:36:50.541  3402  3402 V BluetoothAdapterState: isTurningOff()=false
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isTurningOn()=true
,08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isTurningOff()=false
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isTurningOn()=true
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isTurningOff()=false
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isTurningOn()=true
08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:36:50.542  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isTurningOff()=false
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isTurningOn()=true
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isTurningOff()=false
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isTurningOn()=true
08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:36:50.543  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:36:50.544  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 15:36:50.544  3402  3435 D BluetoothAdapterProperties: ScanMode =  20
08-09 15:36:50.544  3402  3435 D BluetoothAdapterProperties: State =  11
,08-09 15:36:50.547  3402  3441 D BluetoothAdapterProperties: Scan Mode:21
,08-09 15:36:50.547  3402  3441 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 15:36:50.547  3402  3435 D BluetoothAdapterProperties: Setting state to 12
08-09 15:36:50.547  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-09 15:36:50.548  3402  3435 I BluetoothAdapterState: Entering OnState
08-09 15:36:50.548  1355  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 15:36:50.550  3347  3347 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-09 15:36:50.551  3457  3457 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-09 15:36:50.551  1355  1369 D BluetoothInputDevice: onBluetoothStateChange: up=true,
,08-09 15:36:50.552   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:36:50.553  3347  3347 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-09 15:36:50.553   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:36:50.554  1355  1838 D BluetoothPan: onBluetoothStateChange on: true
,08-09 15:36:50.555  1750  1763 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:36:50.555   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:36:50.556   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 15:36:50.556  1355  1372 D BluetoothMap: onBluetoothStateChange: up=true
08-09 15:36:50.556  3347  3347 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-09 15:36:50.557   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:50.560  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:50.563  3402  3402 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 15:36:50.563  3402  3402 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-09 15:36:50.565  3402  3402 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:36:50.565  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:50.569  3402  3402 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:50.570  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:50.571  3402  3402 D ObexServerSockets: Succeed to create listening sockets 
,08-09 15:36:50.571  3402  3402 D ObexServerSockets0: startAccept()
08-09 15:36:50.571  3402  3402 D ObexServerSockets0: prepareForNewConnect()
08-09 15:36:50.572  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:50.573  3402  3402 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-09 15:36:50.573  3402  3402 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-09 15:36:50.574  3402  3477 D ObexServerSockets0: Accepting socket connection...
08-09 15:36:50.574  3402  3402 D BluetoothMapService: onReceive
08-09 15:36:50.574  3402  3402 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 15:36:50.574  3402  3402 D BluetoothMapService: STATE_ON
08-09 15:36:50.574  3402  3478 D ObexServerSockets0: Accepting socket connection...
,08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:50.576  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:50.577  1355  1678 D LocalBluetoothProfileManager: Adding local A2DP profile
08-09 15:36:50.577   874  1918 I ActivityManager: Killing 2824:com.google.android.gm/u0a78 (adj 15): empty #17
08-09 15:36:50.578  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:50.580  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:36:50.581  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:36:50.582  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:36:50.594  3402  3402 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 15:36:50.594  3402  3402 D ObexServerSockets0: prepareForNewConnect()
,08-09 15:36:50.610  1355  1355 D BluetoothA2dp: Proxy object connected
,08-09 15:36:50.616  1355  1678 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-09 15:36:50.617  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:36:50.636   874  1918 I ActivityManager: Start proc 3479:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-09 15:36:50.654   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:36:50.655   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:36:50.656  1750  1931 D BluetoothHeadset: Proxy object connected
08-09 15:36:50.657   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:36:50.704  3479  3479 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-09 15:36:50.720  1355  1369 D BluetoothHeadset: Proxy object connected
,08-09 15:36:50.722  1355  1355 D HeadsetProfile: Bluetooth service connected
,08-09 15:36:50.901  3479  3479 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.901  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:583)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.902  3479  3479 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 15:36:50.902  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 15:36:50.928  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 15:36:50.936   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@413f079:true
,08-09 15:36:50.941  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:36:50.950  3457  3457 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-09 15:36:50.954  3457  3457 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-09 15:36:50.964  3457  3457 D LocalBluetoothProfileManager: Adding local MAP profile
,08-09 15:36:50.964  3457  3457 D BluetoothMap: Create BluetoothMap proxy object
,08-09 15:36:50.966  1355  1355 D BluetoothPbap: Proxy object connected
08-09 15:36:50.967  1355  1355 D PbapServerProfile: Bluetooth service connected
,08-09 15:36:50.985  3457  3457 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-09 15:36:50.998  3402  3509 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:36:51.005  3457  3457 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:36:51.006  3457  3457 D BluetoothA2dp: Proxy object connected
,08-09 15:36:51.010  3457  3457 D BluetoothInputDevice: Proxy object connected
,08-09 15:36:51.011  3457  3457 D HidProfile: Bluetooth service connected,
,08-09 15:36:51.012  3402  3514 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:36:51.012  3457  3457 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:36:51.013  3457  3457 D PanProfile: Bluetooth service connected
08-09 15:36:51.013  3457  3457 D BluetoothMap: Proxy object connected
08-09 15:36:51.013  3457  3457 D MapProfile: Bluetooth service connected
08-09 15:36:51.013  3457  3457 D BluetoothMap: getConnectedDevices()
08-09 15:36:51.013  3402  3514 I BtOppRfcommListener: Accept thread started.
,08-09 15:36:51.014  3457  3457 D BluetoothPbap: Proxy object connected
08-09 15:36:51.015  3457  3457 D PbapServerProfile: Bluetooth service connected
08-09 15:36:51.016   874  1919 I ActivityManager: Killing 3007:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-09 15:36:51.058  3457  3469 D BluetoothHeadset: Proxy object connected
,08-09 15:36:51.059  3457  3457 D HeadsetProfile: Bluetooth service connected
,08-09 15:36:51.157  3479  3495 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-09 15:36:51.175   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49fadcc:true
,08-09 15:36:53.972   874  1610 D WifiService: setWifiEnabled: true pid=3347, uid=10000
,08-09 15:36:53.972   874  1610 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:36:53.986   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:54.001  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:54.006  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:54.016  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:54.019  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:54.024  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:54.026   874  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-09 15:36:54.026   874  1317 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 15:36:54.027   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-09 15:36:54.027   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-09 15:36:54.028   874  1317 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,08-09 15:36:54.029   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-09 15:36:54.029  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:36:54.030   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
08-09 15:36:54.030   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 15:36:54.030   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 15:36:54.030   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
08-09 15:36:54.032  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-09 15:36:54.105   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 15:36:54.108   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:36:54.108   372   872 D CommandListener: Setting iface cfg
,08-09 15:36:54.110   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-09 15:36:54.110   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 15:36:54.113  1469  1469 E wpa_supplicant: PNO: In assoc process
,08-09 15:36:54.114   874  1317 E WifiStateMachine:  Fail to set up pno, want true now false
,08-09 15:36:54.121   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 15:36:54.122   874  1317 E native  : do suspend true
,08-09 15:36:54.122   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 15:36:54.170   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:36:54.493  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 15:36:54.529  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 15:36:54.529  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-09 15:36:54.538   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:36:54.556   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 15:36:54.556   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 15:36:54.557   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-09 15:36:54.582   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 15:36:54.598   372   872 D CommandListener: Setting iface cfg
,08-09 15:36:54.612   874  1317 D WifiStateMachine: Start Dhcp Watchdog 1
,08-09 15:36:54.626   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-09 15:36:54.651   874  3525 D DhcpClient: Receive thread started
,08-09 15:36:54.739   874  1317 E native  : do suspend false
,08-09 15:36:54.762   874  3524 D DhcpClient: Broadcasting DHCPDISCOVER
,08-09 15:36:54.777   874  3525 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170889, domain null
,08-09 15:36:54.779   874  3524 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170889 seconds
,08-09 15:36:54.783   874  3524 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-09 15:36:54.798   874  3525 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-09 15:36:54.799   874  3524 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-09 15:36:54.804   372   872 D CommandListener: Setting iface cfg
,08-09 15:36:54.814   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-09 15:36:54.816   874  3524 D DhcpClient: Scheduling renewal in 86399s
,08-09 15:36:54.817   874  1317 E native  : do suspend true
,08-09 15:36:54.835   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-09 15:36:54.836   874  1317 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-09 15:36:54.837   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-09 15:36:54.839   874  1319 D ConnectivityService: Adding iface wlan0 to network 100
,08-09 15:36:54.842   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-09 15:36:54.880   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-09 15:36:54.881   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-09 15:36:54.884   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-09 15:36:54.886   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-09 15:36:54.889   874  1319 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-09 15:36:54.897   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 15:36:54.903   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-09 15:36:54.904   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-09 15:36:54.904   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-09 15:36:54.905   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-09 15:36:54.907   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-09 15:36:54.907   874  1319 D ConnectivityService:    accepting network in place of null
,08-09 15:36:54.908   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 15:36:54.919   874  3523 D NetlinkSocketObserver: NeighborEvent{elapsedMs=376935, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 15:36:54.955   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:36:54.981   874  3522 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:80a::200e
,08-09 15:36:55.003   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:36:55.008   874  1319 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-09 15:36:55.020   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-09 15:36:55.021   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:36:55.032   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-09 15:36:55.040   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100],
,08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:36:55.042  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:36:55.043   874  1756 V BackupManagerService: Scheduling immediate backup pass
08-09 15:36:55.046  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 15:36:55.047   874   874 V BackupManagerService: Running a backup pass
08-09 15:36:55.048   874  1335 V BackupManagerService: clearing pending backups
08-09 15:36:55.050   874  1335 V PerformBackupTask: Beginning backup of 16 targets
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:36:55.051  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 15:36:55.054  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:36:55.082   874  1335 D PerformBackupTask: invokeAgentForBackup on @pm@
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:36:55.082  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:36:55.084  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:36:55.085   874  1718 D AlarmManagerService: Setting time of day to sec=1470749815
08-09 15:36:55.469   874  1718 W AlarmManagerService: Unable to set rtc to 1470749815: Invalid argument
,08-09 15:36:55.471   874  3522 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 13:36:55 GMT], X-Android-Received-Millis=[1470749815470], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470749815046]}
,08-09 15:36:55.472   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-09 15:36:55.472   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-09 15:36:55.472   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-09 15:36:55.472   874  1335 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
08-09 15:36:55.473   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-09 15:36:55.488  1854  1854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 15:36:55.493  1854  1854 D SystemUpdateService: onCreate
,08-09 15:36:55.499   874  1335 I BackupRestoreController: Getting widget state for user: 0
,08-09 15:36:55.500  1854  1854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 15:36:55.502  1854  3544 I SystemUpdateService: active receiver: enabled
,08-09 15:36:55.505  1854  3544 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 15:36:55.507  1854  3544 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-09 15:36:55.507  1854  3544 I SystemUpdateService: now status is 0 (complete)
08-09 15:36:55.507  1854  3544 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-09 15:36:55.507  1854  3544 I SystemUpdateService: file has been verified
,08-09 15:36:55.517  1854  3544 I SystemUpdateService: OTA package size = 12249756
,08-09 15:36:55.520  1854  3544 I SystemUpdateService: showing system update notification
,08-09 15:36:55.560  1854  1854 D SystemUpdateService: onDestroy
,08-09 15:36:55.566   874  3552 D GpsLocationProvider: NTP server returned: 1470749815469 (Tue Aug 09 15:36:55 GMT+02:00 2016) reference: 377107 certainty: 5 system time offset: -97
,08-09 15:36:55.566   874  3552 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-09 15:36:55.578   874  1697 I ActivityManager: Start proc 3555:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-09 15:36:55.592  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:36:55.594  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:36:55.615  3555  3555 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-09 15:36:55.623  1854  3571 I iu.SyncManager: SYNC; picasa accounts
,08-09 15:36:55.628  1854  1854 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-09 15:36:55.630  1854  1854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-09 15:36:55.645  1854  1854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 15:36:55.646  1854  1854 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-09 15:36:55.646  1854  3550 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-09 15:36:55.649  1864  1883 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-09 15:36:55.651  1854  3571 I iu.UploadsManager: num queued entries: 0
,08-09 15:36:55.653  1864  1883 V GmsBackupTransport: starting performBackup for @pm@
,08-09 15:36:55.653  1854  3571 I iu.UploadsManager: num updated entries: 0
08-09 15:36:55.654  1854  3571 I iu.SyncManager: NEXT; no task
,08-09 15:36:55.661   874  1919 I ActivityManager: Start proc 3577:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-09 15:36:55.672  1864  1883 V GmsBackupTransport: performBackup done for @pm@
,08-09 15:36:55.674  1854  3570 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-09 15:36:55.675  1854  3570 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 15:36:55.677  3555  3572 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-09 15:36:55.693  1854  3570 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 15:36:55.693  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:36:55.714  1521  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-09 15:36:55.714  1521  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-09 15:36:55.715  1521  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:55.715  1521  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:55.739  1521  2657 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:36:55.739  1521  2657 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:36:55.739  1521  2657 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:36:55.739  1521  2657 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 15:36:55.739  1521  2657 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 15:36:55.739  1521  2657 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 15:36:55.739  1521  2657 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 15:36:55.742  3555  3572 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-09 15:36:55.757  3413  3549 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 15:36:55.775  1864  1878 W GmsBackupTransport: Error sending final backup to server: 
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 15:36:55.775  1864  1878 W GmsBackupTransport: 	... 1 more
08-09 15:36:55.775  1864  1883 I GmsBackupTransport: Next backup will happen in 43199973 millis.
08-09 15:36:55.776   874  1335 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-09 15:36:55.781  1521  2223 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-09 15:36:55.781  1521  2223 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-09 15:36:55.788  1521  2223 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:36:55.788  1521  2223 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:55.790  3577  3577 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
08-09 15:36:55.807  3555  3572 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-09 15:36:55.808  1854  3570 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-09 15:36:55.824  3577  3577 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:36:55.832  3577  3577 D SprintDMHelper: simOperator: 
,08-09 15:36:55.832  3577  3577 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 15:36:55.843   874  1919 I ActivityManager: Start proc 3603:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-09 15:36:55.847  1854  1854 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-09 15:36:55.858  1521  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 15:36:55.858  1521  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 15:36:55.858  1521  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:36:55.859  1521  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:55.872   874  1744 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1854 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 15:36:55.889   874  1335 I BackupManagerService: Backup pass finished.
,08-09 15:36:55.890  3555  3555 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-09 15:36:55.898  3413  3549 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 15:36:55.899  3413  3549 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 15:36:55.908  1521  1923 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 15:36:55.908  1521  1923 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 15:36:55.908  1521  1923 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:55.908  1521  1923 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:55.941  3613  3613 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1106321369.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1106321369.dex
,08-09 15:36:55.985  3126  3554 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 15:36:55.985  3126  3554 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jdm.a(PG:82)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jcs.o(PG:406)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jcn.a(PG:1379)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jcs.i(PG:143)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at blb.a(PG:3937)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at czp.a(PG:18188)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at czp.a(PG:9081)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at czq.run(PG:1686)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 15:36:55.985  3126  3554 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jdj.a(PG:4091)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jdj.a(PG:1125)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jdm.a(PG:77)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	... 12 more
08-09 15:36:55.985  3126  3554 E HttpOperation: Caused by: faj: BadAuthentication
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at fal.a(PG:38)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	at jdj.a(PG:4089)
08-09 15:36:55.985  3126  3554 E HttpOperation: 	... 14 more
,08-09 15:36:56.019   874   886 I ActivityManager: Start proc 3642:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-09 15:36:56.035  1521  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 15:36:56.035  1521  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 15:36:56.035  1521  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:56.035  1521  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:56.049  3126  3554 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 15:36:56.049  3126  3554 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jdm.a(PG:82)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jcs.o(PG:406)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jcn.a(PG:1379)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jcs.i(PG:143)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at hec.a(PG:42)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at hee.a(PG:102)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at czr.a(PG:65)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at kka.a(PG:108)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at czp.a(PG:19176)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at czp.a(PG:9081)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at czq.run(PG:1686)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 15:36:56.049  3126  3554 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jdj.a(PG:4091)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jdj.a(PG:1125)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jdm.a(PG:77)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	... 15 more
08-09 15:36:56.049  3126  3554 E HttpOperation: Caused by: faj: BadAuthentication
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at fal.a(PG:38)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	at jdj.a(PG:4089)
08-09 15:36:56.049  3126  3554 E HttpOperation: 	... 17 more
,08-09 15:36:56.049  3126  3554 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 15:36:56.049  3126  3554 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at hec.a(PG:42)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at hee.a(PG:102)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at czr.a(PG:65)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at kka.a(PG:108)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	... 15 more
08-09 15:36:56.049  3126  3554 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at fal.a(PG:38)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 15:36:56.049  3126  3554 E ExperimentLoader: 	... 17 more
08-09 15:36:56.052  3642  3642 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-09 15:36:56.059  1854  3551 W DriveInitializer: Awaiting to be initialized
,08-09 15:36:56.059  1854  3661 W DriveInitializer: Background init thread started
,08-09 15:36:56.073  3555  3555 W InstanceID/Rpc: Found 10011
,08-09 15:36:56.080  3613  3613 I dex2oat : dex2oat took 139.105ms (threads: 4) arena alloc=179KB java alloc=29KB native alloc=1259KB free=1300KB
,08-09 15:36:56.126   874  1919 I ActivityManager: Start proc 3683:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-09 15:36:56.182  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:36:56.208  1854  3661 W DriveInitializer: Background init thread ended
,08-09 15:36:56.247  1521  3715 I VacuumService: Vacuum at: now=1470749816247 tag=VacuumService
,08-09 15:36:56.273  3642  3642 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-09 15:36:56.277  3683  3683 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-09 15:36:56.281  3642  3642 I BooksApp: Created application version: 3.6.9 (30609)
,08-09 15:36:56.294   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 24577, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-09 15:36:56.374  2363  3682 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-09 15:36:56.419  3642  3722 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 15:36:56.481  2856  3724 V KeepSync: Connecting to GoogleApiClient
,08-09 15:36:56.490   874  1744 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 15:36:56.655  1521  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-09 15:36:56.655  1521  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 15:36:56.655  1521  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:56.655  1521  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:56.666  3683  3683 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-09 15:36:56.666  3683  3683 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-09 15:36:56.666  3683  3683 I GAv4    :   adb logcat -s GAv4
,08-09 15:36:56.671  1854  3731 V BaseAuthAsyncOperation: access token request failed
,08-09 15:36:56.674  2856  3724 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 15:36:56.691  3683  3683 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-09 15:36:56.701  3683  3683 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-09 15:36:56.731  3683  3737 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-09 15:36:56.913  3683  3683 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-09 15:36:56.975  3683  3683 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-09 15:36:56.984  3683  3683 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8619-8623)
,08-09 15:36:56.984  3683  3683 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 15:36:57.021  3683  3683 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {efb9cbc}
,08-09 15:36:57.021  3683  3683 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 15:36:57.022  3683  3683 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 15:36:57.033  3683  3683 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-09 15:36:57.038  3683  3683 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 15:36:57.075  3642  3762 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 15:36:57.117  3683  3683 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 15:36:57.128  1521  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 15:36:57.128  1521  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 15:36:57.128  1521  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:36:57.128  1521  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:57.179  1521  3729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 15:36:57.179  1521  3729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-09 15:36:57.179  1521  3729 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:57.179  1521  3729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:57.193  3642  3762 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 15:36:57.196  3642  3722 E BooksSync: Soft error
08-09 15:36:57.196  3642  3722 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 15:36:57.196  3642  3722 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 15:36:57.196  3642  3722 E BooksSync: Sync error
08-09 15:36:57.196  3642  3722 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 15:36:57.196  3642  3722 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 15:36:57.196  3642  3722 I BooksSync: Finished books sync
,08-09 15:36:57.201  3683  3683 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 15:36:57.201  3683  3683 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 15:36:57.202  3683  3683 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 15:36:57.202  3683  3683 I Adreno  : Build Date                       : 10/20/15
08-09 15:36:57.202  3683  3683 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 15:36:57.202  3683  3683 I Adreno  : Local Branch                     : M14
08-09 15:36:57.202  3683  3683 I Adreno  : Remote Branch                    : 
08-09 15:36:57.202  3683  3683 I Adreno  : Remote Branch                    : 
08-09 15:36:57.202  3683  3683 I Adreno  : Reconstruct Branch               : 
,08-09 15:36:57.207   874  1919 I ActivityManager: Killing 2470:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-09 15:36:57.207   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24588, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 15:36:57.314  3683  3683 I NSApplication: Starting up...
,08-09 15:36:57.329  3683  3771 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-09 15:36:57.339   874  1610 I ActivityManager: Start proc 3778:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-09 15:36:57.340   874  1610 I ActivityManager: Killing 2723:android.process.acore/u0a5 (adj 15): empty #17
,08-09 15:36:57.470  3778  3778 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-09 15:36:57.491  1521  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-09 15:36:57.491  1521  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 15:36:57.491  1521  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:57.491  1521  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:57.507  2856  3724 E KeepSync: IOException
08-09 15:36:57.507  2856  3724 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 15:36:57.507  2856  3724 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 15:36:57.507  2856  3724 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 15:36:57.507  2856  3724 E KeepSync: 	... 10 more
08-09 15:36:57.507  2856  3724 W KeepSync: Sync result 2
,08-09 15:36:57.512   874  1704 I ActivityManager: Killing 3210:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-09 15:36:57.512   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24588, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 15:36:57.722   874   886 I ActivityManager: Start proc 3798:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,08-09 15:36:57.726  1854  3797 I PeopleSync: onPerformSync() [5005f081]
,08-09 15:36:57.759  3798  3798 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,08-09 15:36:57.809   874  1919 I ActivityManager: Start proc 3813:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,08-09 15:36:57.841  3813  3813 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,08-09 15:36:57.860  3813  3813 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@12d9d7a(com.android.providers.calendar.CalendarProvider2@cc3692b)
,08-09 15:36:57.921   874   885 I ActivityManager: Killing 3223:com.android.musicfx/u0a18 (adj 15): empty #17
,08-09 15:36:57.937  3798  3798 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-09 15:36:57.945  3798  3798 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-09 15:36:58.076  1854  3831 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,08-09 15:36:58.128  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:36:58.135   874  1919 I ActivityManager: Killing 3046:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-09 15:36:58.459  1521  3837 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-09 15:36:58.464  1521  3837 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-09 15:36:58.501  1521  3729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-09 15:36:58.501  1521  3729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
,08-09 15:36:58.501  1521  3729 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:58.501  1521  3729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:58.522  2363  3841 E Babel   : UserRecoverableAuthException.
,08-09 15:36:58.522  2363  3841 E Babel   : efr: BadAuthentication
08-09 15:36:58.522  2363  3841 E Babel   : 	at efp.a(Unknown Source)
08-09 15:36:58.522  2363  3841 E Babel   : 	at efp.a(Unknown Source)
08-09 15:36:58.522  2363  3841 E Babel   : 	at efp.a(Unknown Source)
08-09 15:36:58.522  2363  3841 E Babel   : 	at g.a(Unknown Source)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbh.a(SourceFile:3092)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbh.a(SourceFile:1136)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cyr.a(SourceFile:4333)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cyr.a(SourceFile:1419)
08-09 15:36:58.522  2363  3841 E Babel   : 	at ctk.a(SourceFile:492)
08-09 15:36:58.522  2363  3841 E Babel   : 	at ctk.a(SourceFile:1468)
08-09 15:36:58.522  2363  3841 E Babel   : ,	at cst.a(SourceFile:4416)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbv.b(SourceFile:106)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbs.d(SourceFile:335)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbt.run(SourceFile:81)
08-09 15:36:58.522  2363  3841 E Babel   : Error getting auth token
,08-09 15:36:58.522  2363  3841 E Babel   : dxq
08-09 15:36:58.522  2363  3841 E Babel   : 	at g.a(Unknown Source)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbh.a(SourceFile:3092)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbh.a(SourceFile:1136)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cyr.a(SourceFile:4333)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cyr.a(SourceFile:1419)
08-09 15:36:58.522  2363  3841 E Babel   : 	at ctk.a(SourceFile:492)
08-09 15:36:58.522  2363  3841 E Babel   : 	at ctk.a(SourceFile:1468)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cst.a(SourceFile:4416)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbv.b(SourceFile:106)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbs.d(SourceFile:335)
08-09 15:36:58.522  2363  3841 E Babel   : 	at cbt.run(SourceFile:81)
,08-09 15:36:58.527  2363  3841 E Babel   : Account registration failed 1-Redacted-21
,08-09 15:36:58.528  2363  3841 E Babel   : dao: null -- null
08-09 15:36:58.528  2363  3841 E Babel   : 	at cbh.a(SourceFile:3124)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cbh.a(SourceFile:1136)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cyr.a(SourceFile:4333)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cyr.a(SourceFile:1419)
08-09 15:36:58.528  2363  3841 E Babel   : 	at ctk.a(SourceFile:492)
08-09 15:36:58.528  2363  3841 E Babel   : 	at ctk.a(SourceFile:1468)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cst.a(SourceFile:4416)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cbv.b(SourceFile:106)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cbs.d(SourceFile:335)
08-09 15:36:58.528  2363  3841 E Babel   : 	at cbt.run(SourceFile:81)
,08-09 15:36:58.545  2363  3841 I art     : Note: end time exceeds epoch: 
,08-09 15:36:58.568  1521  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-09 15:36:58.568  1521  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
,08-09 15:36:58.568  1521  2657 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-09 15:36:58.568  1521  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:58.586  2363  3854 E Babel   : Unexpected exception while authenticating.
,08-09 15:36:58.586  2363  3854 E Babel   : efs: User intervention required. Notification has been pushed.
08-09 15:36:58.586  2363  3854 E Babel   : 	at efp.b(Unknown Source)
08-09 15:36:58.586  2363  3854 E Babel   : 	at efp.b(Unknown Source)
08-09 15:36:58.586  2363  3854 E Babel   : 	at g.a(Unknown Source)
08-09 15:36:58.586  2363  3854 E Babel   : 	at cbh.b(SourceFile:1151)
08-09 15:36:58.586  2363  3854 E Babel   : 	at def.run(SourceFile:5617)
08-09 15:36:58.586  2363  3854 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 15:36:58.586  2363  3854 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 15:36:58.586  2363  3854 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,08-09 15:36:58.626  3798  3833 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-09 15:36:58.717  3798  3833 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-09 15:36:58.727  1854  3797 I PeopleSync: Setting subscription: result=true [5005f081]
08-09 15:36:58.727  1854  3797 I PeopleSync: Starting sync, feed=null [5005f081]
,08-09 15:36:58.818  1854  3797 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 15:36:58.822  1854  3797 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 15:36:58.842  1854  3797 W BaseAppContext: Using Auth Proxy for data requests.,
,08-09 15:36:58.870  1521  3837 W Uploader:  no longer exists, so no auth token.
,08-09 15:36:58.875  1854  3797 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,08-09 15:36:58.894  3798  3833 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-09 15:36:58.897  3798  3833 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,08-09 15:36:58.938  3813  3813 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
08-09 15:36:58.938  3813  3813 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,08-09 15:36:58.981  1521  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,08-09 15:36:58.981  1521  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud.
08-09 15:36:58.981  1521  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:58.981  1521  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:59.005  1521  3837 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-09 15:36:59.005  1521  3837 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-09 15:36:59.005  1521  3837 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:59.005  1521  3837 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:59.019  1521  3837 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 15:36:59.019  1521  3837 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-09 15:36:59.019  1521  3837 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-09 15:36:59.071  1854  3797 I PeopleSync: Sync finished, successful=false, took 181ms
,08-09 15:36:59.099  1854  3797 I PeopleSync: Cannot authenticate [5005f081]
08-09 15:36:59.099  1854  3797 I PeopleSync: com.google.android.gms.auth.ae: BadAuthentication
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.auth.p.b(SourceFile:480)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:397)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:342)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.people.service.g.b(SourceFile:171)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1190)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.people.sync.aa.g(SourceFile:1085)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.people.sync.aa.a(SourceFile:240)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:274)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:189)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:91)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
08-09 15:36:59.099  1854  3797 I PeopleSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,08-09 15:36:59.171  1521  2223 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,08-09 15:36:59.171  1521  2223 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud.
,08-09 15:36:59.171  1521  2223 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:36:59.172  1521  2223 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:36:59.196  1854  3797 I PeopleSync: ***Sync finished***, duration: 1468 [5005f081]
,08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: Exception in onPerformLoggedSync 
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:153)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:90)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:859)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:419)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:352)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:469)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.Utils.executeAndLog(Utils.java:555)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2853)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:2301)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffsForAccount(CalendarSyncAdapterApiary.java:2182)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:623)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:473)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.android.emailcommon.syncadapter.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:49)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.zzb(Unknown Source)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:141)
08-09 15:36:59.214  3798  3833 E CalendarSyncAdapter: 	... 13 more
,08-09 15:36:59.225  1854  1854 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-09 15:36:59.225  1854  1854 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-09 15:36:59.231  1854  1854 W PlaySystemBroadcastReceiver: Processed handlePeopleChanged at 380865
,08-09 15:36:59.235   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 24635, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-09 15:36:59.237   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 412941, reason: Periodic
,08-09 15:36:59.244  1854  1854 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-09 15:36:59.245  1854  1854 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-09 15:36:59.261  1854  3862 W DataBroker: No player ID found and calling context is not the dest app
,08-09 15:36:59.275   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 24635, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-09 15:36:59.275   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 412985, reason: Periodic
,08-09 15:36:59.304  1854  1854 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,08-09 15:36:59.337  1854  3866 I RemindersSync: Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=209:priority=5:group=main]
,08-09 15:36:59.353  1864  3865 I GCoreUlr: Uploading GCM registration ID for account#2#
,08-09 15:36:59.361   874  1610 D WifiService: setWifiEnabled: false pid=3347, uid=10000
08-09 15:36:59.361   874  1610 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:36:59.370  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-09 15:36:59.372   874  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-09 15:36:59.372   874  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-09 15:36:59.372   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-09 15:36:59.373   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 15:36:59.379   874  1317 E native  : do suspend true
,08-09 15:36:59.381  1864  3865 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 15:36:59.384   874  3524 D DhcpClient: Clearing IP address
08-09 15:36:59.385   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-09 15:36:59.387   372   872 D CommandListener: Setting iface cfg
,08-09 15:36:59.388  1521  3837 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.20.74 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-09 15:36:59.389  1521  3614 V NativeCrypto: Read error: ssl=0x9af33800: I/O error during system call, Connection timed out
,08-09 15:36:59.390  1521  3614 V NativeCrypto: SSL shutdown failed: ssl=0x9af33800: I/O error during system call, Broken pipe
,08-09 15:36:59.391   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-09 15:36:59.391   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-09 15:36:59.394   874  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
08-09 15:36:59.395   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-09 15:36:59.395   395   395 E Parcel  : Reading a NULL string not supported here.
08-09 15:36:59.395   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 15:36:59.395   874  1317 E native  : do suspend true
,08-09 15:36:59.405  1864  3865 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,08-09 15:36:59.416  1864  3865 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,08-09 15:36:59.418   874  3525 D DhcpClient: Receive thread stopped
,08-09 15:36:59.423   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:36:59.444   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:36:59.445   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-09 15:36:59.445  1521  1923 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
08-09 15:36:59.445  1521  1923 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud.
08-09 15:36:59.445  1521  1923 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-09 15:36:59.445  1521  1923 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-09 15:36:59.445   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-09 15:36:59.445   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 15:36:59.447   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:36:59.450   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:59.455  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:59.457  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:59.459  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:59.461  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:59.462  1854  1854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:59.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:59.465  1854  1854 D SystemUpdateService: onCreate
08-09 15:36:59.466  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:59.467   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:36:59.469  1854  1854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 15:36:59.470   874  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-09 15:36:59.471  1854  3884 I SystemUpdateService: active receiver: enabled
08-09 15:36:59.473  1864  2111 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:59.475  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:36:59.476  1854  3884 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 15:36:59.476  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:59.479  1854  3884 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-09 15:36:59.479  1854  3884 I SystemUpdateService: now status is 0 (complete)
08-09 15:36:59.479  1854  3884 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 15:36:59.479  1854  3884 I SystemUpdateService: file has been verified
,08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:59.479  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:59.480  1854  1854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-09 15:36:59.481  1854  3884 I SystemUpdateService: OTA package size = 12249756
,08-09 15:36:59.482  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:36:59.484  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:36:59.486  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:36:59.488  1854  3884 I SystemUpdateService: showing system update notification
,08-09 15:36:59.488  1854  3571 I iu.UploadsManager: num queued entries: 0
,08-09 15:36:59.489  1854  3571 I iu.UploadsManager: num updated entries: 0
,08-09 15:36:59.489  1854  3571 I iu.SyncManager: NEXT; no task
,08-09 15:36:59.496  1864  3865 E GCoreUlr: 
08-09 15:36:59.496  1864  3865 E GCoreUlr: com.google.android.gms.auth.ae: BadAuthentication
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.auth.p.b(SourceFile:480)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:397)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:342)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.location.reporting.d.c.a(SourceFile:164)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.location.reporting.d.g.a(SourceFile:94)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.location.reporting.service.u.b(SourceFile:220)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.location.reporting.service.u.a(SourceFile:173)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.location.reporting.service.t.a(SourceFile:151)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
08-09 15:36:59.496  1864  3865 E GCoreUlr: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,08-09 15:36:59.503   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-09 15:36:59.538  1854  1854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 15:36:59.538  1854  1854 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-09 15:36:59.539  1854  1854 D SystemUpdateService: onDestroy
,08-09 15:36:59.540   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 24635, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-09 15:36:59.541   874   886 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 411402, reason: Periodic
08-09 15:36:59.541  3577  3577 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:36:59.545  3577  3577 D SprintDMHelper: simOperator: 
,08-09 15:36:59.545  3577  3577 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 15:36:59.551  2363  3888 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-09 15:37:01.287  3642  3719 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-09 15:37:02.839  3798  3824 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-09 15:37:03.291   874  1319 D ConnectivityService: handlePromptUnvalidated 100
,08-09 15:37:03.596   874  1756 I ActivityManager: Killing 3176:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-09 15:37:04.101   874  1744 I ActivityManager: Killing 3248:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-09 15:37:04.359   874   885 I ActivityManager: Killing 1818:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-09 15:37:04.416   874  1318 D WifiService: Client connection lost with reason: 4
,08-09 15:37:04.430  3402  3435 D BluetoothAdapterState: Current state: ON, message: 23
,08-09 15:37:04.430  3402  3435 D BluetoothAdapterProperties: Setting state to 13
08-09 15:37:04.430  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 15:37:04.432  3402  3435 D BluetoothAdapterProperties: onBluetoothDisable()
08-09 15:37:04.433  3402  3435 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:37:04.443  3402  3441 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:37:04.444  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-09 15:37:04.448  3402  3402 D BluetoothMapService: onReceive
,08-09 15:37:04.449  3402  3402 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 15:37:04.449  3402  3402 D BluetoothMapService: STATE_TURNING_OFF
08-09 15:37:04.450  3402  3402 D BluetoothMapService: MAP Service closeService in
08-09 15:37:04.450  3402  3402 D BluetoothMapMasInstance0: MAP Service shutdown
,08-09 15:37:04.450  3402  3402 D ObexServerSockets0: shutdown(block = true)
08-09 15:37:04.451  3402  3477 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-09 15:37:04.454  3402  3402 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 15:37:04.455  3402  3478 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-09 15:37:04.458  3402  3453 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 15:37:04.459  3402  3402 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 15:37:04.459  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:04.460  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:37:04.460  3402  3402 I BtOppRfcommListener: stopping Accept Thread
,08-09 15:37:04.460  3402  3514 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 15:37:04.461  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:04.461  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:04.462  3402  3514 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-09 15:37:04.464  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:04.464  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:37:04.465  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:04.465  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:37:04.468  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:37:04.474  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:04.474  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:04.477  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:37:04.477  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:04.479  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:04.479  3402  3402 D HeadsetService: Received stop request...Stopping profile...
08-09 15:37:04.480  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.481  1355  1372 D BluetoothHeadset: Proxy object disconnected
,08-09 15:37:04.481  1355  1355 D HeadsetProfile: Bluetooth service disconnected
08-09 15:37:04.482  3457  3469 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:04.482  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.482  1750  1763 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:04.482   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:04.482   874   874 D BluetoothHeadset: Proxy object disconnected
,08-09 15:37:04.482   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:04.482  3402  3402 D A2dpService: Received stop request...Stopping profile...
08-09 15:37:04.483  3402  3471 D A2dpStateMachine: Exit Disconnected: -1
08-09 15:37:04.485   874   874 D BluetoothA2dp: Proxy object disconnected
08-09 15:37:04.485  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-09 15:37:04.485  3457  3457 D DockEventReceiver: finishStartingService: stopping service
08-09 15:37:04.487  3402  3402 D HidService: Received stop request...Stopping profile...
,08-09 15:37:04.487  3402  3402 D HidService: Stopping Bluetooth HidService
08-09 15:37:04.488  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:37:04.489  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-09 15:37:04.489  1355  1355 D HidProfile: Bluetooth service disconnected
08-09 15:37:04.489  3402  3402 V BluetoothAdapterState: isTurningOff()=true
,08-09 15:37:04.489  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:04.489  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.489  3457  3457 D HeadsetProfile: Bluetooth service disconnected
08-09 15:37:04.490  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:04.490  3402  3402 D HealthService: Received stop request...Stopping profile...
08-09 15:37:04.491  3457  3457 D BluetoothA2dp: Proxy object disconnected
08-09 15:37:04.491  3457  3457 D BluetoothInputDevice: Proxy object disconnected
08-09 15:37:04.492  3457  3457 D HidProfile: Bluetooth service disconnected
08-09 15:37:04.493  3402  3402 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 15:37:04.493  3402  3402 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 15:37:04.493  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-09 15:37:04.493  3402  3450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:04.494  3402  3450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:04.494  3402  3450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:04.494  3402  3441 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-09 15:37:04.494  3402  3402 D PanService: Received stop request...Stopping profile...
08-09 15:37:04.496  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 15:37:04.496  1355  1355 D PanProfile: Bluetooth service disconnected
08-09 15:37:04.496  3457  3457 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 15:37:04.496  3457  3457 D PanProfile: Bluetooth service disconnected
08-09 15:37:04.496  3402  3402 D BluetoothMapService: Received stop request...Stopping profile...
08-09 15:37:04.496  3402  3402 D BluetoothMapService: stop()
08-09 15:37:04.499  3402  3402 D BluetoothMapAppObserver: deinitObservers()
08-09 15:37:04.499  3402  3402 D BluetoothMapAppObserver: removeReceiver()
08-09 15:37:04.500  1355  1355 D BluetoothMap: Proxy object disconnected
08-09 15:37:04.500  1355  1355 D MapProfile: Bluetooth service disconnected
08-09 15:37:04.501  3457  3457 D BluetoothMap: Proxy object disconnected
08-09 15:37:04.501  3457  3457 D MapProfile: Bluetooth service disconnected
08-09 15:37:04.501  3402  3402 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:04.501  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:04.501  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.501  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:04.502  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 15:37:04.503  3402  3450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:04.503  3402  3450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:04.503  3402  3450 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 15:37:04.503  3402  3450 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:37:04.503  3402  3450 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 15:37:04.503  3402  3450 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:37:04.505  3457  3457 D BluetoothPbap: Proxy object disconnected
08-09 15:37:04.505  1355  1355 D BluetoothPbap: Proxy object disconnected
08-09 15:37:04.505  1355  1355 D PbapServerProfile: Bluetooth service disconnected
08-09 15:37:04.505  3457  3457 D PbapServerProfile: Bluetooth service disconnected
08-09 15:37:04.506  3402  3402 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:04.506  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:04.506  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.506  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:04.506  3402  3402 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 15:37:04.506  3402  3441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 15:37:04.506  3402  3402 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 15:37:04.508  3402  3402 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:04.509  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:04.509  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.509  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:04.509  3402  3402 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 15:37:04.509  3402  3441 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-09 15:37:04.509  3402  3402 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 15:37:04.510  3402  3402 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:04.510  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:04.510  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.510  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:04.510  3402  3402 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 15:37:04.510  3402  3402 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 15:37:04.512  3402  3402 D BluetoothMapService: MAP Service closeService in
08-09 15:37:04.512  3402  3402 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:04.512  3402  3402 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:04.512  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.512  3402  3402 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:04.512  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-09 15:37:04.512  3402  3435 D BluetoothAdapterProperties: Setting state to 15
08-09 15:37:04.513  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-09 15:37:04.513  3402  3402 D BluetoothMapService: cleanup()
08-09 15:37:04.513  3402  3402 D BluetoothMapService: MAP Service closeService in
08-09 15:37:04.513  3402  3435 I BluetoothAdapterState: Entering BleOnState
08-09 15:37:04.513  1355  1369 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:37:04.514  3457  3468 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:37:04.515  3457  3469 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:04.515  1355  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 15:37:04.517  1355  1838 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:04.517   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:04.517   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:04.518  3457  3468 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 15:37:04.519  1355  1369 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:37:04.519  1355  1372 D BluetoothPan: onBluetoothStateChange on: false
08-09 15:37:04.520  1750  1931 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:04.520  3457  3469 D BluetoothMap: onBluetoothStateChange: up=false
08-09 15:37:04.521   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:04.521   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:37:04.521  3457  3468 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:37:04.522  3457  3469 D BluetoothPan: onBluetoothStateChange on: false
08-09 15:37:04.523  1355  1838 D BluetoothMap: onBluetoothStateChange: up=false
08-09 15:37:04.524  3402  3435 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-09 15:37:04.524  3402  3435 D BluetoothAdapterProperties: Setting state to 16
08-09 15:37:04.524  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-09 15:37:04.525  3402  3435 D BluetoothAdapterProperties: onBleDisable
08-09 15:37:04.525  3402  3435 I BluetoothAdapterState: Entering PendingCommandState
08-09 15:37:04.525  3402  3436 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 15:37:04.526  3402  3450 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-09 15:37:04.526  3402  3450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:04.528  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.529  3402  3441 D BluetoothAdapterProperties: Scan Mode:20
08-09 15:37:04.531  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.531  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:37:04.532  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.534  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.535  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.536  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:04.539  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:37:04.546  3457  3457 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:37:04.732  3402  3441 I bt_hci  : shut_down
,08-09 15:37:04.734  3402  3448 D bt_hwcfg: hw_epilog_process
,08-09 15:37:04.736  3402  3448 I bt_vendor: low_power_mode_cb
,08-09 15:37:04.761  3402  3448 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 15:37:04.761  3402  3448 I bt_vendor: epilog_cb
08-09 15:37:04.761  3402  3448 I bt_hci  : epilog_finished_callback
,08-09 15:37:04.770  3402  3441 I bt_hci_h4: hal_close
,08-09 15:37:04.772  3402  3441 I bt_userial_vendor: device fd = 51 close
,08-09 15:37:04.893  3402  3436 D bt_stack_manager: event_shut_down_stack finished.
,08-09 15:37:04.894  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 15:37:04.902  3402  3402 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 15:37:04.904  3402  3435 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-09 15:37:04.904  3402  3402 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 15:37:04.904  3402  3402 D BtGatt.GattService: stop()
,08-09 15:37:04.906  3402  3402 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 15:37:04.912  3402  3402 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:04.912  3402  3402 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:37:04.913  3402  3402 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:04.913  3402  3402 V BluetoothAdapterState: isBleTurningOff()=true
08-09 15:37:04.914  3402  3435 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-09 15:37:04.915  3402  3435 D BluetoothAdapterProperties: Setting state to 10
,08-09 15:37:04.915  3402  3435 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-09 15:37:04.916  3402  3435 I BluetoothAdapterState: Entering OffState
,08-09 15:37:04.920   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-09 15:37:04.938  3402  3402 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-09 15:37:04.938  3402  3402 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-09 15:37:04.938  3402  3402 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-09 15:37:04.939  3402  3436 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-09 15:37:04.943  3402  3436 D bt_stack_manager: event_clean_up_stack finished.
,08-09 15:37:04.946  3402  3402 I art     : System.exit called, status: 0
,08-09 15:37:04.946  3402  3402 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-09 15:37:05.007   874  1920 I ActivityManager: Process com.android.bluetooth (pid 3402) has died
,08-09 15:37:06.330  2579  2590 D Finsky  : [173] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-09 15:37:06.350  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:37:06.361  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:37:06.364  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:37:06.431  1521  2223 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 15:37:06.432  1521  2223 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 15:37:06.432  1521  2223 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:37:06.432  1521  2223 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:37:06.500  2579  2590 D Finsky  : [173] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-09 15:37:09.467   874   891 I ActivityManager: Start proc 3905:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-09 15:37:09.569  3905  3905 D AdapterServiceConfig: Adding HeadsetService
08-09 15:37:09.569  3905  3905 D AdapterServiceConfig: Adding A2dpService
08-09 15:37:09.569  3905  3905 D AdapterServiceConfig: Adding HidService
08-09 15:37:09.569  3905  3905 D AdapterServiceConfig: Adding HealthService
08-09 15:37:09.569  3905  3905 D AdapterServiceConfig: Adding PanService
,08-09 15:37:09.570  3905  3905 D AdapterServiceConfig: Adding GattService
08-09 15:37:09.570  3905  3905 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 15:37:09.586  3905  3905 D BluetoothAdapterState: make() - Creating AdapterState
08-09 15:37:09.586   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22811ae:true
,08-09 15:37:09.590  3905  3905 I bt_bluedroid: init
,08-09 15:37:09.591  3905  3917 I BluetoothAdapterState: Entering OffState
,08-09 15:37:09.596  3905  3918 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 15:37:09.597  3905  3918 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-09 15:37:09.597  3905  3918 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 15:37:09.597  3905  3918 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-09 15:37:09.599  3905  3905 I bt_bluedroid: get_profile_interface socket
,08-09 15:37:09.601  3905  3905 I bt_bluedroid: get_profile_interface sdp
,08-09 15:37:09.605  3905  3921 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:37:09.606  3905  3916 I bt_bluedroid: config_hci_snoop_log
,08-09 15:37:09.608  3905  3921 D BluetoothAdapterProperties: Name is: Nexus 6
08-09 15:37:09.609   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-09 15:37:09.616  3905  3917 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 15:37:09.616  3905  3917 D BluetoothAdapterProperties: Setting state to 14
08-09 15:37:09.616  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 15:37:09.620  3905  3917 D BluetoothBondStateMachine: make
,08-09 15:37:09.626  3905  3922 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 15:37:09.633  3905  3917 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:37:09.636  3905  3905 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 15:37:09.645  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:09.647  3905  3905 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 15:37:09.648  3905  3905 D BtGatt.GattService: Received start request. Starting profile...
08-09 15:37:09.649  3905  3905 D BtGatt.GattService: start()
08-09 15:37:09.649  3905  3905 I bt_bluedroid: get_profile_interface gatt
,08-09 15:37:09.651  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:09.652  3905  3905 D BtGatt.AdvertiseManager: advertise manager created
,08-09 15:37:09.667  3905  3905 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:09.668  3905  3905 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:09.668  3905  3905 V BluetoothAdapterState: isBleTurningOn()=true
08-09 15:37:09.668  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:09.670  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-09 15:37:09.671  3905  3917 I bt_bluedroid: enable
,08-09 15:37:09.672  3905  3918 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-09 15:37:09.673  3905  3918 I bt_hci  : start_up
,08-09 15:37:09.693  3905  3918 I bt_vendor: alloc value 0xb39ea189
,08-09 15:37:09.693  3905  3918 I bt_vendor: init
08-09 15:37:09.694  3905  3918 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 15:37:09.694  3905  3918 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 15:37:09.803  3905  3918 D bt_hci  : start_up starting async portion,
08-09 15:37:09.804  3905  3925 I bt_hci  : event_finish_startup
08-09 15:37:09.804  3905  3925 I bt_hci_h4: hal_open
08-09 15:37:09.805  3905  3925 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 15:37:09.814  3905  3925 I bt_userial_vendor: device fd = 51 open
,08-09 15:37:09.845  3905  3925 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:37:09.877  3905  3925 D bt_hwcfg: Chipset BCM4354A2
,08-09 15:37:09.877  3905  3925 D bt_hwcfg: Target name = [BCM4354A2]
08-09 15:37:09.878  3905  3925 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 15:37:10.540  3905  3925 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 15:37:10.541  3905  3925 D bt_hwcfg: Settlement delay -- 100 ms
08-09 15:37:10.541  3905  3925 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 15:37:10.658  3905  3925 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:37:10.659  3905  3925 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 15:37:10.690  3905  3925 I bt_hwcfg: vendor lib fwcfg completed
,08-09 15:37:10.690  3905  3925 I bt_vendor: firmware callback
08-09 15:37:10.691  3905  3925 I bt_hci  : firmware_config_callback
,08-09 15:37:10.701  1662  1784 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-09 15:37:10.702  1662  1784 I Keyboard.Facilitator: flushDynamicLanguageModels()
08-09 15:37:10.703  3905  3927 I bt_btu  : btu_task pending for preload complete event
,08-09 15:37:10.704  3905  3927 I bt_btu_task: Bluetooth chip preload is complete
08-09 15:37:10.704  3905  3927 I bt_btu  : btu_task received preload complete event
,08-09 15:37:10.713  3905  3927 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 15:37:10.713  3905  3927 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-09 15:37:10.713  3905  3927 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 15:37:10.714  3905  3927 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 15:37:10.714  3905  3927 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 15:37:10.714  3905  3927 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 15:37:10.714  3905  3927 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 15:37:10.715  3905  3927 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 15:37:10.715  3905  3927 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 15:37:10.715  3905  3927 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 15:37:10.715  3905  3927 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 15:37:10.715  3905  3927 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 15:37:10.716  3905  3927 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 15:37:10.716  3905  3927 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 15:37:10.716  3905  3927 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 15:37:10.731  1521  1521 I ConfigService: onCreate
,08-09 15:37:10.851  3905  3927 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3967d9d
,08-09 15:37:10.852  3905  3927 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3967d9d 
,08-09 15:37:10.863  3905  3921 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 15:37:10.864  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 15:37:10.865  3905  3921 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:37:10.868  3905  3921 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:37:10.871  3905  3921 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:37:10.872  3905  3921 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:37:10.873  3905  3921 D bt_hci  : do_postload posting postload work item
,08-09 15:37:10.873  3905  3925 I bt_hci  : event_postload
,08-09 15:37:10.873  3905  3925 I bt_vendor: sco_config_cb
08-09 15:37:10.873  3905  3925 I bt_hci  : sco_config_callback postload finished.
,08-09 15:37:10.876  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:10.877  3905  3921 D bt_bte_conf: Device ID record 1 : primary
08-09 15:37:10.877  3905  3921 D bt_bte_conf:   vendorId            = 000f
08-09 15:37:10.878  3905  3921 D bt_bte_conf:   vendorIdSource      = 0001
08-09 15:37:10.878  3905  3921 D bt_bte_conf:   product             = 1200
08-09 15:37:10.878  3905  3921 D bt_bte_conf:   version             = 1436
08-09 15:37:10.878  3905  3921 D bt_bte_conf:   clientExecutableURL = 
08-09 15:37:10.878  3905  3921 D bt_bte_conf:   serviceDescription  = 
08-09 15:37:10.878  3905  3921 D bt_bte_conf:   documentationURL    = 
08-09 15:37:10.879  3905  3921 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 15:37:10.879  3905  3918 D bt_stack_manager: event_start_up_stack finished
08-09 15:37:10.879  3905  3925 I bt_vendor: low_power_mode_cb
08-09 15:37:10.881  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:10.881  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-09 15:37:10.882  3905  3917 D BluetoothAdapterProperties: Setting state to 15
08-09 15:37:10.882  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 15:37:10.883  3905  3917 I BluetoothAdapterState: Entering BleOnState
08-09 15:37:10.884  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:10.890  3905  3917 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-09 15:37:10.890  3905  3917 D BluetoothAdapterProperties: Setting state to 11
,08-09 15:37:10.890  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 15:37:10.902  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:10.905  3905  3905 D HeadsetService: Received start request. Starting profile...
08-09 15:37:10.908  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:10.910  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:10.910  3905  3905 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 15:37:10.911  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:10.911  3905  3905 D HeadsetStateMachine: make
,08-09 15:37:10.922  3905  3917 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:37:10.922  3905  3905 D HeadsetStateMachine: max_hf_connections = 1
08-09 15:37:10.922  3905  3905 I bt_bluedroid: get_profile_interface handsfree
08-09 15:37:10.922  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 15:37:10.923  3905  3921 E bt_btif : btif_hf_upstreams_evt: Invalid index 1027
,08-09 15:37:10.927  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:10.928  3905  3905 D A2dpService: Received start request. Starting profile...
,08-09 15:37:10.928  3905  3905 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 15:37:10.929  3905  3905 I bt_bluedroid: get_profile_interface avrcp
,08-09 15:37:10.934  3905  3905 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 15:37:10.935  3905  3905 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 15:37:10.935  3905  3905 D A2dpStateMachine: make
,08-09 15:37:10.936  3905  3905 I bt_bluedroid: get_profile_interface a2dp
08-09 15:37:10.936  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-09 15:37:10.938  3905  3937 D A2dpStateMachine: Enter Disconnected: -2
,08-09 15:37:10.939  3905  3905 I BluetoothHidServiceJni: classInitNative: succeeds
,08-09 15:37:10.940  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:37:10.941  3905  3905 D HidService: Received start request. Starting profile...
08-09 15:37:10.941  3905  3905 I bt_bluedroid: get_profile_interface hidhost
08-09 15:37:10.941  3905  3905 D HidService: setHidService(): set to: null
08-09 15:37:10.941  3905  3921 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39493e5
08-09 15:37:10.941  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-09 15:37:10.942  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:37:10.942  3905  3905 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 15:37:10.943  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:10.943  3905  3905 D HealthService: Received start request. Starting profile...
,08-09 15:37:10.944  3905  3905 I bt_bluedroid: get_profile_interface health
,08-09 15:37:10.946  3905  3905 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 15:37:10.947  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:10.947  3905  3905 D PanService: Received start request. Starting profile...
08-09 15:37:10.947  3905  3905 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-09 15:37:10.948  3905  3905 I bt_bluedroid: get_profile_interface pan
,08-09 15:37:10.948  3905  3921 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-09 15:37:10.950  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:10.951  3905  3905 D BluetoothMapService: Received start request. Starting profile...
08-09 15:37:10.951  3905  3905 D BluetoothMapService: start()
,08-09 15:37:10.953  3905  3905 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-09 15:37:10.954  3905  3905 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 15:37:10.954  3905  3905 D BluetoothMapAppObserver: createReceiver(),
08-09 15:37:10.955  3905  3905 D BluetoothMapAppObserver: initObservers()
08-09 15:37:10.955  3905  3905 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 15:37:10.961  3905  3935 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-09 15:37:10.961  3905  3905 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:10.962  3905  3905 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:10.962  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:10.962  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:10.963  3905  3905 V BluetoothAdapterState: isTurningOff()=false,
08-09 15:37:10.963  3905  3905 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:10.963  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:10.963  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:10.964  3905  3905 V BluetoothAdapterState: isTurningOff()=false,
,08-09 15:37:10.964  3905  3905 V BluetoothAdapterState: isTurningOn()=true
,08-09 15:37:10.964  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:10.964  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isTurningOff()=false
08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:10.966  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:10.967  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:10.967  3905  3905 V BluetoothAdapterState: isTurningOff()=false
08-09 15:37:10.967  3905  3905 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:10.967  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:10.967  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:10.967  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 15:37:10.967  3905  3917 D BluetoothAdapterProperties: ScanMode =  20
,08-09 15:37:10.967  3905  3917 D BluetoothAdapterProperties: State =  11
08-09 15:37:10.968  3905  3917 D BluetoothAdapterProperties: Setting state to 12
08-09 15:37:10.968  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 15:37:10.968  1355  1369 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 15:37:10.969  3905  3917 I BluetoothAdapterState: Entering OnState
08-09 15:37:10.970  3905  3921 D BluetoothAdapterProperties: Scan Mode:21
08-09 15:37:10.970  3905  3921 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 15:37:10.972  3457  3469 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:10.973  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:10.973  3457  3468 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:37:10.974  1355  1838 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 15:37:10.975  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:10.976  1355  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:37:10.977  1355  1355 D BluetoothInputDevice: Proxy object connected
,08-09 15:37:10.977  1355  1355 D HidProfile: Bluetooth service connected
08-09 15:37:10.978   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:10.978   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:10.978  3457  3469 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:10.978  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:10.980  3457  3457 D BluetoothA2dp: Proxy object connected
,08-09 15:37:10.980  1355  1369 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 15:37:10.980  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:37:10.981  3905  3905 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 15:37:10.982  3905  3905 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-09 15:37:10.982  3457  3457 D BluetoothInputDevice: Proxy object connected
08-09 15:37:10.982  3457  3457 D HidProfile: Bluetooth service connected
08-09 15:37:10.983  3905  3905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:37:10.983  1355  1355 D BluetoothA2dp: Proxy object connected
08-09 15:37:10.983  1355  1369 D BluetoothPan: onBluetoothStateChange on: true
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:10.984  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:37:10.986  3905  3905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:37:10.986  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:37:10.986  1750  1763 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:10.987  3905  3905 D ObexServerSockets: Succeed to create listening sockets 
08-09 15:37:10.987  3457  3468 D BluetoothMap: onBluetoothStateChange: up=true
,08-09 15:37:10.987  3905  3905 D ObexServerSockets0: startAccept()
,08-09 15:37:10.987  3905  3905 D ObexServerSockets0: prepareForNewConnect()
08-09 15:37:10.989   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:10.989  3905  3905 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 15:37:10.989   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 15:37:10.989  3905  3905 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 15:37:10.990  3457  3469 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 15:37:10.990   874   874 D BluetoothA2dp: Proxy object connected
08-09 15:37:10.990  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 15:37:10.991  1355  1355 D PanProfile: Bluetooth service connected
08-09 15:37:10.992  3905  3944 D ObexServerSockets0: Accepting socket connection...
08-09 15:37:10.992  3457  3942 D BluetoothPan: onBluetoothStateChange on: true
,08-09 15:37:10.992  3905  3945 D ObexServerSockets0: Accepting socket connection...
,08-09 15:37:10.993  1355  1372 D BluetoothMap: onBluetoothStateChange: up=true
08-09 15:37:10.994  3457  3457 D BluetoothMap: Proxy object connected
08-09 15:37:10.994  3457  3457 D MapProfile: Bluetooth service connected
08-09 15:37:10.994  3457  3457 D BluetoothMap: getConnectedDevices()
08-09 15:37:10.995  1355  1355 D BluetoothMap: Proxy object connected
08-09 15:37:10.995  1355  1355 D MapProfile: Bluetooth service connected
08-09 15:37:10.996  1355  1355 D BluetoothMap: getConnectedDevices()
,08-09 15:37:10.997   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-09 15:37:10.999  3905  3905 D BluetoothMapService: onReceive
08-09 15:37:10.999  3905  3905 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 15:37:10.999  3905  3905 D BluetoothMapService: STATE_ON
08-09 15:37:11.000  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:11.002  3457  3457 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:37:11.002  3457  3457 D PanProfile: Bluetooth service connected
,08-09 15:37:11.002  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:11.004  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:11.009  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 15:37:11.015  3457  3457 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:37:11.016  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:37:11.024  3457  3457 D BluetoothPbap: Proxy object connected
08-09 15:37:11.024  3457  3457 D PbapServerProfile: Bluetooth service connected
,08-09 15:37:11.026  1355  1355 D BluetoothPbap: Proxy object connected
,08-09 15:37:11.026  1355  1355 D PbapServerProfile: Bluetooth service connected
08-09 15:37:11.026  3905  3905 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 15:37:11.026  3905  3905 D ObexServerSockets0: prepareForNewConnect()
,08-09 15:37:11.035  3905  3950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:37:11.050  3905  3954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:37:11.051  3905  3954 I BtOppRfcommListener: Accept thread started.
,08-09 15:37:11.076  1355  1369 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.076  1355  1355 D HeadsetProfile: Bluetooth service connected
,08-09 15:37:11.076  3457  3468 D BluetoothHeadset: Proxy object connected
,08-09 15:37:11.077  3457  3457 D HeadsetProfile: Bluetooth service connected
08-09 15:37:11.077  1750  1931 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.077   874   874 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.077   874   874 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.077   874   874 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.077  1355  1372 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.078   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:37:11.078   874   891 D BluetoothHeadset: Proxy object connected
08-09 15:37:11.079  1355  1355 D HeadsetProfile: Bluetooth service connected
,08-09 15:37:11.086  1750  1771 D BluetoothHeadset: Proxy object connected
,08-09 15:37:11.089   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:37:14.431  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:37:14.431  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:15.804  1521  1521 I ConfigService: onDestroy
,08-09 15:37:19.437  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:37:19.437  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d5694d removed from the list
,08-09 15:37:19.438  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:37:19.438  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:19.438  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:19.441  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 15:37:19.442  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89c4d49 added. We now have 4 listener(s)
08-09 15:37:19.442  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:37:19.448  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:37:19.449  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89c4d49 removed from the list
08-09 15:37:19.449  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:37:19.449  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:19.450  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:19.452  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:37:19.452  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98f564e added. We now have 4 listener(s)
08-09 15:37:19.453  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:37:19.455  3347  3394 I System.out: IsBluetoothEnabled
,08-09 15:37:19.462  3905  3917 D BluetoothAdapterState: Current state: ON, message: 23
08-09 15:37:19.463  3905  3917 D BluetoothAdapterProperties: Setting state to 13
08-09 15:37:19.463  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 15:37:19.464  3905  3917 D BluetoothAdapterProperties: onBluetoothDisable()
,08-09 15:37:19.469  3905  3917 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:37:19.470  3905  3905 D BluetoothMapService: onReceive
,08-09 15:37:19.470  3905  3905 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-09 15:37:19.472  3905  3905 D BluetoothMapService: STATE_TURNING_OFF
,08-09 15:37:19.472  3905  3905 D BluetoothMapService: MAP Service closeService in
08-09 15:37:19.473  3905  3905 D BluetoothMapMasInstance0: MAP Service shutdown
,08-09 15:37:19.473  3905  3905 D ObexServerSockets0: shutdown(block = true),
08-09 15:37:19.475  3905  3905 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 15:37:19.475  3905  3945 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-09 15:37:19.476  3905  3944 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-09 15:37:19.476  3905  3931 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 15:37:19.477  3905  3905 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 15:37:19.477  3905  3905 I BtOppRfcommListener: stopping Accept Thread
08-09 15:37:19.477  3905  3921 D BluetoothAdapterProperties: Scan Mode:20
08-09 15:37:19.477  3905  3954 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-09 15:37:19.478  3905  3954 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 15:37:19.480  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:19.481  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:19.481  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 15:37:19.482  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:19.482  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:19.484  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 15:37:19.486  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:19.486  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:37:19.491  3347  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:37:19.491  3905  3905 D HeadsetService: Received stop request...Stopping profile...
,08-09 15:37:19.491  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:19.494  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:19.495  1355  1369 D BluetoothHeadset: Proxy object disconnected
,08-09 15:37:19.496  1355  1355 D HeadsetProfile: Bluetooth service disconnected
08-09 15:37:19.496  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:19.496  3457  3469 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:19.497  1750  2892 D BluetoothHeadset: Proxy object disconnected,
08-09 15:37:19.497   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:19.497   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:19.498   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 15:37:19.498  3905  3905 D A2dpService: Received stop request...Stopping profile...
,08-09 15:37:19.498  3905  3937 D A2dpStateMachine: Exit Disconnected: -1
,08-09 15:37:19.499   874   874 D BluetoothA2dp: Proxy object disconnected
08-09 15:37:19.500  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-09 15:37:19.500  3905  3905 D HidService: Received stop request...Stopping profile...
08-09 15:37:19.501  3905  3905 D HidService: Stopping Bluetooth HidService
,08-09 15:37:19.501  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-09 15:37:19.501  1355  1355 D HidProfile: Bluetooth service disconnected
08-09 15:37:19.502  3905  3905 V BluetoothAdapterState: isTurningOff()=true
,08-09 15:37:19.502  3905  3905 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:19.502  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:19.502  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:19.506  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:37:19.506  3905  3905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 15:37:19.506  3905  3905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-09 15:37:19.506  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-09 15:37:19.507  3905  3927 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 15:37:19.507  3905  3927 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:19.507  3905  3927 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:19.507  3905  3921 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-09 15:37:19.509  3905  3905 D HealthService: Received stop request...Stopping profile...
08-09 15:37:19.510  3905  3905 D PanService: Received stop request...Stopping profile...
08-09 15:37:19.511  3905  3905 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:19.512  3905  3905 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:37:19.512  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:19.512  3457  3457 D DockEventReceiver: finishStartingService: stopping service
08-09 15:37:19.512  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:19.512  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 15:37:19.512  1355  1355 D PanProfile: Bluetooth service disconnected
08-09 15:37:19.513  3457  3457 D HeadsetProfile: Bluetooth service disconnected
08-09 15:37:19.513  3905  3905 D BluetoothMapService: Received stop request...Stopping profile...
08-09 15:37:19.513  3905  3905 D BluetoothMapService: stop()
08-09 15:37:19.513  3457  3457 D BluetoothA2dp: Proxy object disconnected
,08-09 15:37:19.513  3457  3457 D BluetoothInputDevice: Proxy object disconnected
08-09 15:37:19.513  3905  3905 D BluetoothMapAppObserver: deinitObservers()
08-09 15:37:19.513  3457  3457 D HidProfile: Bluetooth service disconnected
08-09 15:37:19.513  3905  3905 D BluetoothMapAppObserver: removeReceiver()
08-09 15:37:19.514  3457  3457 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 15:37:19.514  3457  3457 D PanProfile: Bluetooth service disconnected
08-09 15:37:19.515  3457  3457 D BluetoothMap: Proxy object disconnected
08-09 15:37:19.515  3457  3457 D MapProfile: Bluetooth service disconnected
08-09 15:37:19.516  1355  1355 D BluetoothMap: Proxy object disconnected
,08-09 15:37:19.516  1355  1355 D MapProfile: Bluetooth service disconnected
08-09 15:37:19.518  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 15:37:19.518  3905  3927 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:19.519  3905  3927 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:19.519  3905  3927 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 15:37:19.519  3905  3927 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:37:19.519  3905  3905 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:19.519  3905  3927 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-09 15:37:19.519  3905  3905 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:19.519  3905  3927 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 15:37:19.519  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:19.519  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:19.519  3905  3905 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 15:37:19.519  3905  3921 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 15:37:19.519  3905  3905 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 15:37:19.521  1355  1355 D BluetoothPbap: Proxy object disconnected
,08-09 15:37:19.521  1355  1355 D PbapServerProfile: Bluetooth service disconnected
08-09 15:37:19.522  3457  3457 D BluetoothPbap: Proxy object disconnected
08-09 15:37:19.522  3457  3457 D PbapServerProfile: Bluetooth service disconnected
08-09 15:37:19.523  3905  3905 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:19.523  3905  3905 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:19.523  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:19.524  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:19.524  3905  3905 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:19.524  3905  3905 V BluetoothAdapterState: isTurningOn()=false
,08-09 15:37:19.524  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:19.524  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:19.525  3905  3905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 15:37:19.525  3905  3921 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-09 15:37:19.525  3905  3905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-09 15:37:19.525  3905  3905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 15:37:19.526  3905  3905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 15:37:19.526  3905  3905 D BluetoothMapService: MAP Service closeService in
08-09 15:37:19.527  3905  3905 V BluetoothAdapterState: isTurningOff()=true
08-09 15:37:19.527  3905  3905 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:19.527  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:19.527  3905  3905 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:19.527  3905  3905 D BluetoothMapService: cleanup()
,08-09 15:37:19.527  3905  3905 D BluetoothMapService: MAP Service closeService in
08-09 15:37:19.528  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-09 15:37:19.528  3905  3917 D BluetoothAdapterProperties: Setting state to 15
08-09 15:37:19.528  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-09 15:37:19.529  1355  1838 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:37:19.529  3905  3917 I BluetoothAdapterState: Entering BleOnState
,08-09 15:37:19.530  3457  3468 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:37:19.530  3457  3942 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:37:19.531  1355  1369 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-09 15:37:19.532  1355  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:19.533   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:19.533   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 15:37:19.533  3457  3469 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 15:37:19.534  1355  1838 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:37:19.535  1355  1369 D BluetoothPan: onBluetoothStateChange on: false
08-09 15:37:19.535  1750  1928 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:19.536  3457  3468 D BluetoothMap: onBluetoothStateChange: up=false,
08-09 15:37:19.536   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 15:37:19.536   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 15:37:19.536  3457  3942 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 15:37:19.537  3457  3469 D BluetoothPan: onBluetoothStateChange on: false
,08-09 15:37:19.538  1355  1372 D BluetoothMap: onBluetoothStateChange: up=false
08-09 15:37:19.538  3905  3917 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-09 15:37:19.538  3905  3917 D BluetoothAdapterProperties: Setting state to 16
,08-09 15:37:19.538  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-09 15:37:19.539  3905  3917 D BluetoothAdapterProperties: onBleDisable
08-09 15:37:19.540  3905  3918 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 15:37:19.540  3905  3927 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-09 15:37:19.540  3905  3917 I BluetoothAdapterState: Entering PendingCommandState
08-09 15:37:19.540  3905  3927 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 15:37:19.540  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:19.542  3905  3921 D BluetoothAdapterProperties: Scan Mode:20
08-09 15:37:19.542  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:19.543  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:37:19.545  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:19.546  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:19.548  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:37:19.557  3457  3457 D DockEventReceiver: finishStartingService: stopping service
,08-09 15:37:19.746  3905  3921 I bt_hci  : shut_down
,08-09 15:37:19.746  3905  3925 D bt_hwcfg: hw_epilog_process
,08-09 15:37:19.759  3905  3925 I bt_vendor: low_power_mode_cb
,08-09 15:37:19.784  3905  3925 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 15:37:19.784  3905  3925 I bt_vendor: epilog_cb
08-09 15:37:19.785  3905  3925 I bt_hci  : epilog_finished_callback
,08-09 15:37:19.792  3905  3921 I bt_hci_h4: hal_close
08-09 15:37:19.794  3905  3921 I bt_userial_vendor: device fd = 51 close
,08-09 15:37:19.928  3905  3918 D bt_stack_manager: event_shut_down_stack finished.
,08-09 15:37:19.930  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 15:37:19.937  3905  3917 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-09 15:37:19.938  3905  3905 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 15:37:19.939  3905  3905 D BtGatt.GattService: Received stop request...Stopping profile...
,08-09 15:37:19.940  3905  3905 D BtGatt.GattService: stop()
,08-09 15:37:19.940  3905  3905 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 15:37:19.944  3905  3905 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:19.945  3905  3905 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:19.945  3905  3905 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:19.945  3905  3905 V BluetoothAdapterState: isBleTurningOff()=true
08-09 15:37:19.946  3905  3917 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-09 15:37:19.947  3905  3917 D BluetoothAdapterProperties: Setting state to 10
08-09 15:37:19.947  3905  3917 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-09 15:37:19.949  3905  3917 I BluetoothAdapterState: Entering OffState
,08-09 15:37:19.951   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-09 15:37:19.981  3905  3905 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-09 15:37:19.982  3905  3905 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-09 15:37:19.983  3905  3918 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-09 15:37:19.989  3905  3918 D bt_stack_manager: event_clean_up_stack finished.
,08-09 15:37:19.991  3905  3905 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-09 15:37:19.999  3905  3905 I art     : System.exit called, status: 0
,08-09 15:37:20.000  3905  3905 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-09 15:37:20.058   874  1697 I ActivityManager: Process com.android.bluetooth (pid 3905) has died
,08-09 15:37:21.467  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:21.468  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:37:21.468  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 15:37:21.468  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:21.517   874   891 I ActivityManager: Start proc 3965:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-09 15:37:21.642  3965  3965 D AdapterServiceConfig: Adding HeadsetService
,08-09 15:37:21.642  3965  3965 D AdapterServiceConfig: Adding A2dpService
,08-09 15:37:21.642  3965  3965 D AdapterServiceConfig: Adding HidService
,08-09 15:37:21.642  3965  3965 D AdapterServiceConfig: Adding HealthService
,08-09 15:37:21.642  3965  3965 D AdapterServiceConfig: Adding PanService
,08-09 15:37:21.643  3965  3965 D AdapterServiceConfig: Adding GattService
,08-09 15:37:21.643  3965  3965 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 15:37:21.656  3965  3965 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 15:37:21.656   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d93917a:true
,08-09 15:37:21.660  3965  3965 I bt_bluedroid: init
,08-09 15:37:21.662  3965  3977 I BluetoothAdapterState: Entering OffState
,08-09 15:37:21.667  3965  3978 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 15:37:21.667  3965  3978 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 15:37:21.667  3965  3978 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 15:37:21.668  3965  3978 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-09 15:37:21.669  3965  3965 I bt_bluedroid: get_profile_interface socket
,08-09 15:37:21.672  3965  3981 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:37:21.672  3965  3965 I bt_bluedroid: get_profile_interface sdp
08-09 15:37:21.674  3965  3981 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:37:21.677  3965  3976 I bt_bluedroid: config_hci_snoop_log
,08-09 15:37:21.680   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-09 15:37:21.686  3965  3977 D BluetoothAdapterState: Current state: OFF, message: 0
08-09 15:37:21.686  3965  3977 D BluetoothAdapterProperties: Setting state to 14
,08-09 15:37:21.686  3965  3977 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 15:37:21.689  3965  3977 D BluetoothBondStateMachine: make
,08-09 15:37:21.693  3965  3982 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 15:37:21.696  3965  3977 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:37:21.698  3965  3965 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 15:37:21.703  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:21.704  3965  3965 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 15:37:21.706  3965  3965 D BtGatt.GattService: Received start request. Starting profile...
,08-09 15:37:21.706  3965  3965 D BtGatt.GattService: start()
08-09 15:37:21.706  3965  3965 I bt_bluedroid: get_profile_interface gatt
,08-09 15:37:21.708  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:37:21.708  3965  3965 D BtGatt.AdvertiseManager: advertise manager created,
,08-09 15:37:21.718  3965  3965 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:21.718  3965  3965 V BluetoothAdapterState: isTurningOn()=false
08-09 15:37:21.719  3965  3965 V BluetoothAdapterState: isBleTurningOn()=true
08-09 15:37:21.719  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:21.720  3965  3977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-09 15:37:21.721  3965  3977 I bt_bluedroid: enable
08-09 15:37:21.721  3965  3978 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-09 15:37:21.722  3965  3978 I bt_hci  : start_up
,08-09 15:37:21.741  3965  3978 I bt_vendor: alloc value 0xb39ea189
08-09 15:37:21.741  3965  3978 I bt_vendor: init
,08-09 15:37:21.741  3965  3978 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 15:37:21.742  3965  3978 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 15:37:21.850  3965  3978 D bt_hci  : start_up starting async portion
,08-09 15:37:21.850  3965  3985 I bt_hci  : event_finish_startup
08-09 15:37:21.851  3965  3985 I bt_hci_h4: hal_open
,08-09 15:37:21.852  3965  3985 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 15:37:21.863  3965  3985 I bt_userial_vendor: device fd = 51 open
,08-09 15:37:21.892  3965  3985 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:37:21.924  3965  3985 D bt_hwcfg: Chipset BCM4354A2
,08-09 15:37:21.924  3965  3985 D bt_hwcfg: Target name = [BCM4354A2]
08-09 15:37:21.925  3965  3985 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 15:37:22.586  3965  3985 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 15:37:22.587  3965  3985 D bt_hwcfg: Settlement delay -- 100 ms
08-09 15:37:22.588  3965  3985 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 15:37:22.704  3965  3985 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 15:37:22.706  3965  3985 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 15:37:22.735  3965  3985 I bt_hwcfg: vendor lib fwcfg completed
,08-09 15:37:22.736  3965  3985 I bt_vendor: firmware callback
08-09 15:37:22.736  3965  3985 I bt_hci  : firmware_config_callback
,08-09 15:37:22.747  3965  3987 I bt_btu  : btu_task pending for preload complete event
,08-09 15:37:22.747  3965  3987 I bt_btu_task: Bluetooth chip preload is complete
08-09 15:37:22.747  3965  3987 I bt_btu  : btu_task received preload complete event
,08-09 15:37:22.759  3965  3987 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 15:37:22.760  3965  3987 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 15:37:22.760  3965  3987 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-09 15:37:22.760  3965  3987 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 15:37:22.761  3965  3987 I         : BTE_InitTraceLevels -- TRC_AVRC
08-09 15:37:22.761  3965  3987 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 15:37:22.761  3965  3987 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-09 15:37:22.763  3965  3987 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 15:37:22.763  3965  3987 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 15:37:22.763  3965  3987 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 15:37:22.763  3965  3987 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 15:37:22.764  3965  3987 I         : BTE_InitTraceLevels -- TRC_GATT
,08-09 15:37:22.764  3965  3987 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 15:37:22.764  3965  3987 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 15:37:22.764  3965  3987 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 15:37:22.904  3965  3987 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3967d9d
,08-09 15:37:22.904  3965  3987 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3967d9d 
,08-09 15:37:22.912  3965  3981 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 15:37:22.914  3965  3981 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 15:37:22.915  3965  3981 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 15:37:22.922  3965  3981 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 15:37:22.926  3965  3981 D BluetoothAdapterProperties: Scan Mode:20
,08-09 15:37:22.927  3965  3981 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:37:22.929  3965  3981 D bt_hci  : do_postload posting postload work item
,08-09 15:37:22.930  3965  3985 I bt_hci  : event_postload
,08-09 15:37:22.931  3965  3985 I bt_vendor: sco_config_cb
,08-09 15:37:22.931  3965  3985 I bt_hci  : sco_config_callback postload finished.
,08-09 15:37:22.933  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:22.934  3965  3981 D bt_bte_conf: Device ID record 1 : primary
,08-09 15:37:22.935  3965  3981 D bt_bte_conf:   vendorId            = 000f
,08-09 15:37:22.935  3965  3981 D bt_bte_conf:   vendorIdSource      = 0001
,08-09 15:37:22.935  3965  3981 D bt_bte_conf:   product             = 1200
,08-09 15:37:22.935  3965  3981 D bt_bte_conf:   version             = 1436
08-09 15:37:22.936  3965  3981 D bt_bte_conf:   clientExecutableURL = 
08-09 15:37:22.936  3965  3981 D bt_bte_conf:   serviceDescription  = 
08-09 15:37:22.936  3965  3981 D bt_bte_conf:   documentationURL    = 
08-09 15:37:22.936  3965  3981 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 15:37:22.937  3965  3978 D bt_stack_manager: event_start_up_stack finished
08-09 15:37:22.937  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:22.938  3965  3977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-09 15:37:22.938  3965  3977 D BluetoothAdapterProperties: Setting state to 15
,08-09 15:37:22.939  3965  3977 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-09 15:37:22.939  3965  3985 I bt_vendor: low_power_mode_cb
08-09 15:37:22.940  3965  3977 I BluetoothAdapterState: Entering BleOnState
08-09 15:37:22.944  3965  3977 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-09 15:37:22.945  3965  3977 D BluetoothAdapterProperties: Setting state to 11
08-09 15:37:22.945  3965  3977 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-09 15:37:22.955  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:22.959  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:22.962  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
08-09 15:37:22.963  3965  3965 D HeadsetService: Received start request. Starting profile...
,08-09 15:37:22.968  3965  3965 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 15:37:22.968  3965  3965 D HeadsetStateMachine: make
,08-09 15:37:22.973  3965  3977 I BluetoothAdapterState: Entering PendingCommandState
,08-09 15:37:22.979  3965  3965 D HeadsetStateMachine: max_hf_connections = 1
,08-09 15:37:22.979  3965  3965 I bt_bluedroid: get_profile_interface handsfree
08-09 15:37:22.980  3965  3981 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-09 15:37:22.981  3965  3981 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-09 15:37:22.985  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:22.986  3965  3965 D A2dpService: Received start request. Starting profile...
,08-09 15:37:22.987  3965  3965 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 15:37:22.987  3965  3965 I bt_bluedroid: get_profile_interface avrcp
,08-09 15:37:22.999  3965  3965 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 15:37:23.000  3965  3965 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-09 15:37:23.000  3965  3965 D A2dpStateMachine: make
,08-09 15:37:23.002  3965  3965 I bt_bluedroid: get_profile_interface a2dp
,08-09 15:37:23.002  3965  3981 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-09 15:37:23.004  3965  3997 D A2dpStateMachine: Enter Disconnected: -2
,08-09 15:37:23.006  3965  3965 I BluetoothHidServiceJni: classInitNative: succeeds
,08-09 15:37:23.008  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:23.009  3965  3965 D HidService: Received start request. Starting profile...
,08-09 15:37:23.009  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 15:37:23.009  3965  3965 I bt_bluedroid: get_profile_interface hidhost
,08-09 15:37:23.011  3965  3981 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39493e5
08-09 15:37:23.011  3965  3981 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-09 15:37:23.011  3965  3965 D HidService: setHidService(): set to: null
,08-09 15:37:23.012  3965  3965 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 15:37:23.013  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:23.014  3965  3965 D HealthService: Received start request. Starting profile...
,08-09 15:37:23.016  3965  3965 I bt_bluedroid: get_profile_interface health
,08-09 15:37:23.017  3965  3965 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 15:37:23.018  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:23.019  3965  3965 D PanService: Received start request. Starting profile...
,08-09 15:37:23.020  3965  3965 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-09 15:37:23.020  3965  3965 I bt_bluedroid: get_profile_interface pan
08-09 15:37:23.020  3965  3981 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 15:37:23.024  3965  3965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:23.025  3965  3965 D BluetoothMapService: Received start request. Starting profile...
08-09 15:37:23.025  3965  3965 D BluetoothMapService: start()
,08-09 15:37:23.028  3965  3965 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-09 15:37:23.029  3965  3965 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 15:37:23.030  3965  3965 D BluetoothMapAppObserver: createReceiver()
08-09 15:37:23.031  3965  3965 D BluetoothMapAppObserver: initObservers()
08-09 15:37:23.031  3965  3965 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 15:37:23.040  3965  3965 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:23.040  3965  3965 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:23.040  3965  3995 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 15:37:23.040  3965  3965 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:23.040  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:23.042  3965  3965 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:23.042  3965  3965 V BluetoothAdapterState: isTurningOn()=true
,08-09 15:37:23.042  3965  3965 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:23.042  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:23.044  3965  3965 V BluetoothAdapterState: isTurningOff()=false
08-09 15:37:23.044  3965  3965 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:23.045  3965  3965 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:23.045  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:23.045  3965  3965 V BluetoothAdapterState: isTurningOff()=false
08-09 15:37:23.045  3965  3965 V BluetoothAdapterState: isTurningOn()=true
,08-09 15:37:23.045  3965  3965 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:23.045  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 15:37:23.046  3965  3965 V BluetoothAdapterState: isTurningOff()=false
08-09 15:37:23.046  3965  3965 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:23.046  3965  3965 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 15:37:23.046  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:23.046  3965  3965 V BluetoothAdapterState: isTurningOff()=false
,08-09 15:37:23.046  3965  3965 V BluetoothAdapterState: isTurningOn()=true
08-09 15:37:23.047  3965  3965 V BluetoothAdapterState: isBleTurningOn()=false
08-09 15:37:23.047  3965  3965 V BluetoothAdapterState: isBleTurningOff()=false
08-09 15:37:23.047  3965  3977 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 15:37:23.047  3965  3977 D BluetoothAdapterProperties: ScanMode =  20
08-09 15:37:23.047  3965  3977 D BluetoothAdapterProperties: State =  11
08-09 15:37:23.048  3965  3977 D BluetoothAdapterProperties: Setting state to 12
08-09 15:37:23.048  3965  3977 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-09 15:37:23.049  1355  1372 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 15:37:23.050  3965  3977 I BluetoothAdapterState: Entering OnState
,08-09 15:37:23.052  3457  3469 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 15:37:23.052  3965  3981 D BluetoothAdapterProperties: Scan Mode:21
,08-09 15:37:23.052  3965  3981 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 15:37:23.058  3457  3468 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:23.058  3965  3965 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:23.058  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 15:37:23.059  1355  1838 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 15:37:23.059  3965  3965 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-09 15:37:23.061  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:37:23.061  1355  1369 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:23.061   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:37:23.061  3965  3965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:37:23.061   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:37:23.062  3457  3942 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:23.064  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:23.065  1355  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 15:37:23.066  1355  1838 D BluetoothPan: onBluetoothStateChange on: true
,08-09 15:37:23.066  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 15:37:23.067  1750  2892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 15:37:23.068  3457  3469 D BluetoothMap: onBluetoothStateChange: up=true
08-09 15:37:23.069   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 15:37:23.069   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 15:37:23.070  3457  3468 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 15:37:23.071  3965  3965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:37:23.071  3457  3942 D BluetoothPan: onBluetoothStateChange on: true,
08-09 15:37:23.072  3965  3965 D ObexServerSockets: Succeed to create listening sockets 
08-09 15:37:23.072  3965  3965 D ObexServerSockets0: startAccept()
08-09 15:37:23.072  3965  3965 D ObexServerSockets0: prepareForNewConnect()
,08-09 15:37:23.073  1355  1372 D BluetoothMap: onBluetoothStateChange: up=true
08-09 15:37:23.073  3965  3965 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 15:37:23.073  3965  3965 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 15:37:23.074   874   874 D BluetoothA2dp: Proxy object connected
,08-09 15:37:23.075  1355  1355 D BluetoothA2dp: Proxy object connected
08-09 15:37:23.076  1355  1355 D BluetoothInputDevice: Proxy object connected
08-09 15:37:23.076  1355  1355 D HidProfile: Bluetooth service connected
08-09 15:37:23.077  3457  3457 D BluetoothA2dp: Proxy object connected
08-09 15:37:23.077   874   874 I Telecom : BluetoothPhoneService: queryPhoneState,
08-09 15:37:23.077  3965  4002 D ObexServerSockets0: Accepting socket connection...
08-09 15:37:23.078  3965  4003 D ObexServerSockets0: Accepting socket connection...
08-09 15:37:23.079  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:23.080  3965  3965 D BluetoothMapService: onReceive,
08-09 15:37:23.080  3965  3965 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 15:37:23.080  3965  3965 D BluetoothMapService: STATE_ON
08-09 15:37:23.080  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:37:23.080  1355  1355 D PanProfile: Bluetooth service connected
,08-09 15:37:23.081  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:23.081  1355  1355 D BluetoothMap: Proxy object connected
08-09 15:37:23.081  1355  1355 D MapProfile: Bluetooth service connected
08-09 15:37:23.081  1355  1355 D BluetoothMap: getConnectedDevices()
08-09 15:37:23.081  3457  3457 D BluetoothInputDevice: Proxy object connected
08-09 15:37:23.081  3457  3457 D HidProfile: Bluetooth service connected
08-09 15:37:23.083  3457  3457 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 15:37:23.084  3457  3457 D PanProfile: Bluetooth service connected
08-09 15:37:23.087  3457  3457 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 15:37:23.088  3457  3457 D BluetoothMap: Proxy object connected
08-09 15:37:23.089  3457  3457 D MapProfile: Bluetooth service connected,
08-09 15:37:23.089  3457  3457 D BluetoothMap: getConnectedDevices()
08-09 15:37:23.092  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 15:37:23.096  3457  3457 D DockEventReceiver: finishStartingService: stopping service
08-09 15:37:23.097  3457  3457 D BluetoothPbap: Proxy object connected
08-09 15:37:23.097  3457  3457 D PbapServerProfile: Bluetooth service connected
,08-09 15:37:23.105  1355  1355 D BluetoothPbap: Proxy object connected
,08-09 15:37:23.105  1355  1355 D PbapServerProfile: Bluetooth service connected
08-09 15:37:23.105  3965  4008 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:37:23.116  3965  3965 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 15:37:23.116  3965  3965 D ObexServerSockets0: prepareForNewConnect()
,08-09 15:37:23.121  3965  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 15:37:23.122  3965  4012 I BtOppRfcommListener: Accept thread started.
,08-09 15:37:23.161  1355  1838 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.161  1355  1355 D HeadsetProfile: Bluetooth service connected
,08-09 15:37:23.161  3457  3468 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.161  3457  3457 D HeadsetProfile: Bluetooth service connected
08-09 15:37:23.162  1750  1928 D BluetoothHeadset: Proxy object connected
08-09 15:37:23.162   874   874 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.162   874   874 D BluetoothHeadset: Proxy object connected
08-09 15:37:23.162   874   874 D BluetoothHeadset: Proxy object connected
08-09 15:37:23.162  1355  1369 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.162   874   891 D BluetoothHeadset: Proxy object connected
08-09 15:37:23.163   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.164  1355  1355 D HeadsetProfile: Bluetooth service connected
,08-09 15:37:23.168  1750  1763 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.169   874   891 D BluetoothHeadset: Proxy object connected
,08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:23.492  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:23.498  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:23.499  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:23.500  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98f564e removed from the list
08-09 15:37:23.500  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:37:23.500  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:23.501  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:23.504  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 15:37:23.505  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca7b36f added. We now have 4 listener(s)
08-09 15:37:23.506  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:37:23.515   874  1918 D WifiService: setWifiEnabled: false pid=3347, uid=10000
,08-09 15:37:23.516   874  1918 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:37:23.527  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:23.528   874  1920 D WifiService: setWifiEnabled: true pid=3347, uid=10000
,08-09 15:37:23.528   874  1920 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 15:37:23.543   874  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:23.558  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:23.563  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:23.569  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:23.572  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:23.577   874  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-09 15:37:23.578   874  1317 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 15:37:23.578   874  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-09 15:37:23.579   874  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-09 15:37:23.580   874  1317 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
08-09 15:37:23.581   874  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-09 15:37:23.582   874  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
,08-09 15:37:23.582   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 15:37:23.582   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 15:37:23.582   874  1317 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
,08-09 15:37:23.596   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-09 15:37:23.596   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:37:23.598   372   872 D CommandListener: Setting iface cfg
,08-09 15:37:23.650   874  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '61 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 61 Failed to set address (No such device)'
,08-09 15:37:23.650   874  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 15:37:23.656   874  1317 E native  : do suspend true
,08-09 15:37:23.660   874  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 15:37:23.672   874  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 15:37:23.677   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:37:25.053   874  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 3
,08-09 15:37:25.158   874  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.12 rxSuccessRate=3.81 delta 1000 -> 994
08-09 15:37:25.160   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-09 15:37:25.160   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 15:37:25.179   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-09 15:37:25.230   874  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-09 15:37:25.232  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 15:37:25.552  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 15:37:25.559  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 15:37:25.561  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:37:25.561  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca7b36f removed from the list
08-09 15:37:25.562  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:37:25.562  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:25.562  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:25.574  3347  4019 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-09 15:37:25.575  3347  4019 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-09 15:37:25.654  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 15:37:25.695  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-09 15:37:25.697  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-09 15:37:25.706   874  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 15:37:25.715   874  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 15:37:25.716   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 15:37:25.716   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-09 15:37:25.728   874  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 15:37:25.737   372   872 D CommandListener: Setting iface cfg
,08-09 15:37:25.738   874  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,08-09 15:37:25.745   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-09 15:37:25.768   874  4022 D DhcpClient: Receive thread started
,08-09 15:37:25.856   874  1317 E native  : do suspend false
,08-09 15:37:25.875   874  3524 D DhcpClient: Broadcasting DHCPDISCOVER
,08-09 15:37:25.888   874  4022 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172769, domain null
,08-09 15:37:25.889   874  3524 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172769 seconds
,08-09 15:37:25.892   874  3524 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-09 15:37:25.906   874  4022 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-09 15:37:25.907   874  3524 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-09 15:37:25.912   372   872 D CommandListener: Setting iface cfg
,08-09 15:37:25.923   874  3524 D DhcpClient: Scheduling renewal in 86399s
,08-09 15:37:25.927   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-09 15:37:25.929   874  1317 E native  : do suspend true
,08-09 15:37:25.941   874  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-09 15:37:25.942   874  1317 D WifiConfigStore: No blacklist allowed without epno enabled
08-09 15:37:25.943   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-09 15:37:25.945   874  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-09 15:37:25.945   874  1319 D ConnectivityService: Adding iface wlan0 to network 101
,08-09 15:37:26.026   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-09 15:37:26.027   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-09 15:37:26.033   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-09 15:37:26.037   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-09 15:37:26.043   874  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-09 15:37:26.059   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-09 15:37:26.066   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-09 15:37:26.066   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-09 15:37:26.066   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-09 15:37:26.066   874  1319 D ConnectivityService:    accepting network in place of null
,08-09 15:37:26.066   874  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-09 15:37:26.067   874  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 15:37:26.067   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 15:37:26.099   874  4021 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407737, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 15:37:26.126   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:37:26.161   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 15:37:26.170   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-09 15:37:26.171   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:37:26.178   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-09 15:37:26.184   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:26.191  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:37:26.195  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:26.200  3347  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:37:26.202  3347  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:37:26.213  1854  1854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 15:37:26.216  1854  1854 D SystemUpdateService: onCreate
,08-09 15:37:26.221  1854  1854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 15:37:26.236  1854  4031 I SystemUpdateService: active receiver: enabled
,08-09 15:37:26.240  1854  1854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-09 15:37:26.248  1854  4031 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 15:37:26.247  1854  3571 I iu.UploadsManager: num queued entries: 0
,08-09 15:37:26.249  1854  3571 I iu.UploadsManager: num updated entries: 0
,08-09 15:37:26.250  1854  3571 I iu.SyncManager: NEXT; no task
,08-09 15:37:26.250  1854  1854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 15:37:26.251  1854  1854 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-09 15:37:26.253  3577  3577 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 15:37:26.257  1854  4033 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-09 15:37:26.257  1854  4033 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 15:37:26.258  1854  4033 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com,
08-09 15:37:26.260  3577  3577 D SprintDMHelper: simOperator: 
08-09 15:37:26.260  3577  3577 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 15:37:26.271   874  4020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:815::200e
,08-09 15:37:26.296  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:37:26.296  1854  4031 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-09 15:37:26.297  1854  4031 I SystemUpdateService: now status is 0 (complete)
08-09 15:37:26.297  1854  4031 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 15:37:26.297  1854  4031 I SystemUpdateService: file has been verified
,08-09 15:37:26.299  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 15:37:26.308  1854  4031 I SystemUpdateService: OTA package size = 12249756
,08-09 15:37:26.324  1854  4031 I SystemUpdateService: showing system update notification
,08-09 15:37:26.335  1854  1854 D SystemUpdateService: onDestroy
,08-09 15:37:26.348  1521  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-09 15:37:26.348  1521  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-09 15:37:26.348  1521  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 15:37:26.348  1521  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:37:26.371  1854  4033 E MDM     : [215] SitrepService.a: Error sending sitrep.
,08-09 15:37:26.438   874  4020 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 13:37:26 GMT], X-Android-Received-Millis=[1470749846437], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470749846355]}
,08-09 15:37:26.439   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-09 15:37:26.439   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-09 15:37:26.440   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-09 15:37:26.441   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-09 15:37:26.472  2363  4036 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-09 15:37:26.520  3413  4043 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 15:37:26.575  1521  3791 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 15:37:26.575  1521  3791 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-09 15:37:26.575  1521  3791 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 15:37:26.575  1521  3791 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 15:37:26.592  3413  4043 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 15:37:27.171   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-09 15:37:28.583  3347  4045 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-09 15:37:28.584  3347  4019 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-09 15:37:28.584  3347  4045 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-09 15:37:28.584  3347  4019 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-09 15:37:28.586  3347  4019 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 15:37:28.586  3347  4045 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 15:37:28.587  3347  4019 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-09 15:37:28.591  3347  4045 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-09 15:37:28.591  3347  4047 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 382, name: OutgoingSocketThread/Sender)
08-09 15:37:28.592  3347  4019 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-09 15:37:28.593  3347  4045 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-09 15:37:28.598  3347  4050 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 384, name: IncomingSocketThread/Receiver)
,08-09 15:37:28.599  3347  4049 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 383, name: OutgoingSocketThread/Receiver)
,08-09 15:37:28.601  3347  4050 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 384, thread name: IncomingSocketThread/Receiver)
08-09 15:37:28.601  3347  4049 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 383, thread name: OutgoingSocketThread/Receiver)
,08-09 15:37:28.601  3347  4050 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-09 15:37:28.602  3347  4049 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-09 15:37:28.602  3347  4048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 381, name: IncomingSocketThread/Sender)
,08-09 15:37:28.616  3347  4049 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 383, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-09 15:37:28.616  3347  4050 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 384, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-09 15:37:31.581  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-09 15:37:31.584  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-09 15:37:31.589  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@16e89a0 Bundle[{}]
,08-09 15:37:31.590  3347  3394 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 15:37:31.590  3347  3394 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-09 15:37:31.590  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-09 15:37:31.591  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-09 15:37:31.592  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-09 15:37:31.592  3347  3394 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-09 15:37:31.596  3347  3394 I System.out: Running OutgoingSocketThread
,08-09 15:37:31.600  3347  4051 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-09 15:37:31.600  3347  4051 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-09 15:37:34.072   874  1319 D ConnectivityService: handlePromptUnvalidated 101
,08-09 15:37:34.609  3347  4052 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-09 15:37:34.610  3347  4052 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-09 15:37:34.610  3347  4052 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-09 15:37:34.611  3347  4051 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-09 15:37:34.611  3347  4051 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-09 15:37:34.611  3347  4052 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-09 15:37:34.612  3347  4051 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-09 15:37:34.613  3347  4052 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-09 15:37:34.614  3347  4051 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
08-09 15:37:34.618  3347  4055 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 394, name: IncomingSocketThread/Receiver)
08-09 15:37:34.619  3347  4055 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 394, thread name: IncomingSocketThread/Receiver)
08-09 15:37:34.620  3347  4055 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-09 15:37:34.620  3347  4054 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 393, name: IncomingSocketThread/Sender)
08-09 15:37:34.620  3347  4055 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 394, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-09 15:37:34.624  3347  4051 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-09 15:37:34.626  3347  4056 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 395, name: OutgoingSocketThread/Sender)
,08-09 15:37:34.629  3347  4057 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 396, name: OutgoingSocketThread/Receiver)
,08-09 15:37:34.630  3347  4057 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 396, thread name: OutgoingSocketThread/Receiver)
,08-09 15:37:34.631  3347  4057 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-09 15:37:34.632  3347  4057 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 396, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-09 15:37:37.612  3347  3394 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 405)
,08-09 15:37:37.614  3347  3394 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-09 15:37:37.615  3347  3394 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 406)
,08-09 15:37:37.621  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:37:37.621  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed687c added. We now have 3 listener(s)
,08-09 15:37:37.623  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:37:37.623  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 15:37:37.623  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:37:37.623  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:37:37.623  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37505 added. We now have 4 listener(s)
08-09 15:37:37.623  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:37:37.624  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 15:37:37.626  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:37.637  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:37:37.644  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:37:37.644  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 15:37:37.646  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:37:37.646  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:37:37.646  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:37:37.647  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:37.647  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.647  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 15:37:37.647  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:37.648  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 15:37:37.648  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed687c removed from the list
08-09 15:37:37.648  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:37:37.648  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37505 removed from the list
,08-09 15:37:37.650  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:37.650  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:37:37.650  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:37.652  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.652  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:37.653  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:37.653  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:37.653  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:37.653  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37505 not in the list
08-09 15:37:37.653  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.653  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:37.654  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:37.654  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:37.654  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:37.655  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37505 not in the list
08-09 15:37:37.655  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:37.655  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.655  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:37.655  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed687c not in the list
08-09 15:37:37.656  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:37:37.656  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@626178b added. We now have 3 listener(s)
08-09 15:37:37.658  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:37:37.658  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 15:37:37.658  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:37:37.658  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:37:37.658  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e69068 added. We now have 4 listener(s)
08-09 15:37:37.658  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:37:37.659  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 15:37:37.661  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new ,listener
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:37.666  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 15:37:37.668  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:37.669  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:37:37.671  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:37.671  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 15:37:37.672  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 15:37:37.672  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-09 15:37:37.672  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:37:37.672  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:37:37.673  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:37.681  3347  3394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
08-09 15:37:37.682  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-09 15:37:37.696  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-09 15:37:37.700  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-09 15:37:37.701  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-09 15:37:37.707  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-09 15:37:37.708  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 15:37:37.709  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-09 15:37:37.711  3347  3394 D BluetoothAdapter: STATE_ON
,08-09 15:37:37.721  3965  4004 D BtGatt.GattService: registerClient() - UUID=3979216d-9ae3-4e6c-bc1b-9fa40ad65dc4
,08-09 15:37:37.723  3965  3981 D BtGatt.GattService: onClientRegistered() - UUID=3979216d-9ae3-4e6c-bc1b-9fa40ad65dc4, clientIf=5
,08-09 15:37:37.725  3347  3357 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-09 15:37:37.727  3965  3994 D BtGatt.GattService: start scan with filters
,08-09 15:37:37.734  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-09 15:37:37.735  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-09 15:37:37.735  3965  3984 D BtGatt.ScanManager: handling starting scan
08-09 15:37:37.735  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 15:37:37.736  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-09 15:37:37.741  3965  3984 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ad9be34
,08-09 15:37:37.742  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-09 15:37:37.742  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-09 15:37:37.743  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-09 15:37:37.747  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 15:37:37.749  3347  3394 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-09 15:37:37.749  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-09 15:37:37.749  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 15:37:37.750  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:37.750  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-09 15:37:37.750  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:37:37.750  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:37:37.750  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-09 15:37:37.750  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:37:37.750  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 15:37:37.750  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 15:37:37.751  3347  3394 D BluetoothAdapter: STATE_ON
08-09 15:37:37.752  3965  3994 D BtGatt.GattService: stopScan() - queue size =1
,08-09 15:37:37.753  3965  3975 D BtGatt.GattService: unregisterClient() - clientIf=5
08-09 15:37:37.754  3965  3981 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 15:37:37.754  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 15:37:37.754  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 15:37:37.754  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:37.756  3965  3984 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 15:37:37.755  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 15:37:37.757  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 15:37:37.757  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-09 15:37:37.760  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:37:37.760  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 15:37:37.761  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 15:37:37.761  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:37:37.762  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:37:37.764  3965  3981 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-09 15:37:37.764  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:37.765  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:37:37.765  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:37:37.765  3965  3984 D BtGatt.ScanManager: Starting BLE batch scan
08-09 15:37:37.765  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:37:37.766  3965  3984 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-09 15:37:37.767  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:37:37.767  3347  3394 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 15:37:37.768  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:37:37.768  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 15:37:37.769  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:37.769  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.769  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:37:37.769  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-09 15:37:37.770  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@626178b removed from the list
08-09 15:37:37.770  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:37.770  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e69068 removed from the list
08-09 15:37:37.771  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:37:37.771  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:37.773  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.773  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:37.776  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:37.777  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:37.777  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:37.777  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e69068 not in the list
08-09 15:37:37.777  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:37.777  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:37.780  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 15:37:37.780  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:37.781  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:37:37.781  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e69068 not in the list
08-09 15:37:37.781  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:37.782  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:37.782  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:37.782  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@626178b not in the list
,08-09 15:37:37.784  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:37:37.780  3965  3981 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-09 15:37:37.784  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:37.785  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba03fbd added. We now have 3 listener(s)
,08-09 15:37:37.791  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:37:37.792  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 15:37:37.792  3965  3981 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-09 15:37:37.792  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:37.793  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:37:37.793  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:37:37.794  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd4e9b2 added. We now have 4 listener(s)
,08-09 15:37:37.794  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 15:37:37.796  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 15:37:37.799  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:37:37.802  3965  3981 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-09 15:37:37.802  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:37.803  3965  3984 D BtGatt.ScanManager: stopping BLe Batch
,08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:37.806  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:37:37.810  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:37:37.810  3965  3981 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 15:37:37.810  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:37.810  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:37:37.810  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-09 15:37:37.810  3965  3984 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-09 15:37:37.811  3347  3394 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-09 15:37:37.811  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-09 15:37:37.813  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-09 15:37:37.814  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-09 15:37:37.814  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 15:37:37.814  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:37:37.814  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:37.815  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-09 15:37:37.817  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:37.817  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-09 15:37:37.817  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-09 15:37:37.818  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-09 15:37:37.818  3347  3347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-09 15:37:37.818  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-09 15:37:37.818  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:37:37.818  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:37:37.819  3965  3981 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-09 15:37:37.819  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:37.823  3347  4058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 15:37:37.823  3347  3394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-09 15:37:37.823  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-09 15:37:37.825  3347  4058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-09 15:37:37.827  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-09 15:37:37.827  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-09 15:37:37.827  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-09 15:37:37.830  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-09 15:37:37.831  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:37:37.831  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-09 15:37:37.832  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-09 15:37:37.832  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-09 15:37:37.833  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-09 15:37:37.833  3347  3394 D BluetoothAdapter: STATE_ON
,08-09 15:37:37.838  3965  3993 D BtGatt.GattService: registerClient() - UUID=c571e359-d632-4da1-a414-4d84afc2f156
,08-09 15:37:37.839  3965  3981 D BtGatt.GattService: onClientRegistered() - UUID=c571e359-d632-4da1-a414-4d84afc2f156, clientIf=5
08-09 15:37:37.840  3347  3517 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-09 15:37:37.841  3965  3983 D BtGatt.AdvertiseManager: message : 0
,08-09 15:37:37.845  3965  3983 D BtGatt.AdvertiseManager: starting multi advertising
,08-09 15:37:37.864  3965  3981 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-09 15:37:37.875  3965  3981 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-09 15:37:37.877  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-09 15:37:37.878  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-09 15:37:37.879  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 15:37:37.881  3347  3347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-09 15:37:37.882  3347  3347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-09 15:37:37.882  3347  3347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-09 15:37:37.882  3347  3347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-09 15:37:37.883  3347  3347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-09 15:37:37.883  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-09 15:37:37.890  3347  3347 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-09 15:37:37.890  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-09 15:37:38.266  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:37:38.391  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-09 15:37:38.392  3347  3347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-09 15:37:38.392  3347  3347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-09 15:37:42.881  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:37:42.882  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-09 15:37:42.882  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-09 15:37:42.883  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 15:37:42.883  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-09 15:37:42.883  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-09 15:37:42.884  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-09 15:37:42.884  3347  4058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-09 15:37:42.885  3347  3394 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-09 15:37:42.885  3347  4058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-09 15:37:42.885  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:37:42.885  3347  4058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-09 15:37:42.885  3347  3347 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-09 15:37:42.885  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:37:42.885  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:37:42.886  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 15:37:42.886  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-09 15:37:42.889  3347  3394 D BluetoothAdapter: STATE_ON
08-09 15:37:42.889  3347  3394 D BluetoothLeScanner: could not find callback wrapper
08-09 15:37:42.890  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-09 15:37:42.890  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-09 15:37:42.893  3965  3983 D BtGatt.AdvertiseManager: message : 1
08-09 15:37:42.894  3965  3983 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-09 15:37:42.905  3965  3981 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-09 15:37:42.905  3965  3981 D BtGatt.GattService: Client app is not null!
,08-09 15:37:42.907  3965  4004 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-09 15:37:42.909  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 15:37:42.909  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-09 15:37:42.909  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-09 15:37:42.910  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-09 15:37:42.910  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-09 15:37:42.913  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:37:42.914  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-09 15:37:42.914  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:37:42.916  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 15:37:42.919  3347  3347 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:37:42.920  3347  3347 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-09 15:37:42.920  3347  3347 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-09 15:37:42.920  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:37:42.921  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:37:42.921  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:37:42.921  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:37:42.921  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:42.922  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:37:42.922  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-09 15:37:42.922  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba03fbd removed from the list
08-09 15:37:42.923  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:42.923  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd4e9b2 removed from the list
,08-09 15:37:42.923  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:37:42.923  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:42.925  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:42.925  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:42.928  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 15:37:42.928  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:42.929  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:42.929  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd4e9b2 not in the list
08-09 15:37:42.929  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:42.929  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:42.932  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:42.933  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:42.933  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 15:37:42.933  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fd4e9b2 not in the list
08-09 15:37:42.933  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:42.934  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:42.934  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:42.934  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba03fbd not in the list
08-09 15:37:42.936  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:37:42.937  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@412565f added. We now have 3 listener(s)
,08-09 15:37:42.943  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 15:37:42.943  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 15:37:42.943  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:37:42.943  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:37:42.943  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99e8ac added. We now have 4 listener(s)
08-09 15:37:42.944  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:37:42.944  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 15:37:42.947  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:42.951  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:37:42.954  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:37:42.954  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 15:37:42.954  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-09 15:37:42.954  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 15:37:42.954  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 15:37:42.954  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 15:37:42.954  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 15:37:42.956  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:42.959  3347  3394 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-09 15:37:42.959  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 15:37:42.959  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 15:37:42.963  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-09 15:37:42.964  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-09 15:37:42.965  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-09 15:37:42.968  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-09 15:37:42.968  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 15:37:42.968  3347  3394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-09 15:37:42.969  3347  3394 D BluetoothAdapter: STATE_ON
,08-09 15:37:42.971  3965  3993 D BtGatt.GattService: registerClient() - UUID=d0ce1b23-6887-4acc-833b-7ad190817fb2
,08-09 15:37:42.972  3965  3981 D BtGatt.GattService: onClientRegistered() - UUID=d0ce1b23-6887-4acc-833b-7ad190817fb2, clientIf=5
08-09 15:37:42.972  3347  3358 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-09 15:37:42.973  3965  4004 D BtGatt.GattService: start scan with filters
,08-09 15:37:42.976  3965  3984 D BtGatt.ScanManager: handling starting scan
,08-09 15:37:42.977  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-09 15:37:42.977  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-09 15:37:42.977  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 15:37:42.977  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-09 15:37:42.980  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-09 15:37:42.981  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 15:37:42.981  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-09 15:37:42.983  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 15:37:42.984  3965  3981 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 15:37:42.984  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:42.985  3965  3984 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-09 15:37:42.988  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 15:37:42.988  3347  3394 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 15:37:42.988  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-09 15:37:42.988  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 15:37:42.989  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:42.989  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-09 15:37:42.989  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 15:37:42.989  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 15:37:42.989  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 15:37:42.989  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-09 15:37:42.989  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 15:37:42.989  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 15:37:42.990  3347  3394 D BluetoothAdapter: STATE_ON
08-09 15:37:42.991  3965  3975 D BtGatt.GattService: stopScan() - queue size =1
08-09 15:37:42.992  3965  3976 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-09 15:37:42.992  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 15:37:42.992  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 15:37:42.992  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 15:37:42.992  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 15:37:42.993  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-09 15:37:42.994  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:37:42.994  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 15:37:42.994  3347  3394 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 15:37:42.994  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 15:37:42.994  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 15:37:42.996  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-09 15:37:42.996  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:42.996  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:42.996  3347  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 15:37:42.996  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:37:42.996  3347  3347 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 15:37:42.996  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 15:37:42.996  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@412565f removed from the list
,08-09 15:37:42.996  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:42.996  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99e8ac removed from the list
08-09 15:37:42.996  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
08-09 15:37:42.996  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:42.997  3965  3981 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 15:37:42.997  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:42.997  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:42.997  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:42.997  3965  3984 D BtGatt.ScanManager: Starting BLE batch scan
,08-09 15:37:42.997  3965  3984 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-09 15:37:42.998  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:42.999  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:42.999  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:42.999  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99e8ac not in the list
08-09 15:37:42.999  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:42.999  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:43.000  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:43.001  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 15:37:43.001  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:43.001  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e99e8ac not in the list
08-09 15:37:43.001  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:43.001  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:43.001  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:43.001  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@412565f not in the list
08-09 15:37:43.002  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 15:37:43.002  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f367f1 added. We now have 3 listener(s)
,08-09 15:37:43.004  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 15:37:43.004  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 15:37:43.004  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 15:37:43.004  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 15:37:43.004  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4dfd6 added. We now have 4 listener(s)
08-09 15:37:43.005  3347  3394 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 15:37:43.005  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 15:37:43.009  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 15:37:43.013  3347  3394 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 15:37:43.016  3347  3394 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 15:37:43.016  3347  3394 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 15:37:43.017  3347  3394 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 15:37:43.017  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 15:37:43.017  3347  3394 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 15:37:43.017  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 15:37:43.017  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 15:37:43.017  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 15:37:43.017  3347  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-09 15:37:43.018  3347  3394 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f367f1 removed from the list
08-09 15:37:43.018  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:43.018  3347  3394 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4dfd6 removed from the list
08-09 15:37:43.018  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:43.018  3347  3394 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 15:37:43.019  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:43.019  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:43.020  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:43.021  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 15:37:43.021  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 15:37:43.021  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:43.021  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4dfd6 not in the list
08-09 15:37:43.021  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:43.021  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 15:37:43.023  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 15:37:43.023  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 15:37:43.023  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 15:37:43.023  3347  3394 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 15:37:43.023  3347  3394 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4dfd6 not in the list
08-09 15:37:43.023  3347  3394 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 15:37:43.023  3965  3981 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-09 15:37:43.024  3347  3394 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 15:37:43.024  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:43.024  3347  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 15:37:43.024  3347  3394 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f367f1 not in the list
,08-09 15:37:43.026  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-09 15:37:43.026  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-09 15:37:43.026  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-09 15:37:43.026  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 15:37:43.027  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-09 15:37:43.027  3347  3394 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-09 15:37:43.036  3965  3981 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-09 15:37:43.036  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 15:37:43.040  3347  4059 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 415, name: My test thread name)
,08-09 15:37:43.048  3965  3981 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-09 15:37:43.048  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:43.048  3965  3984 D BtGatt.ScanManager: stopping BLe Batch
,08-09 15:37:43.059  3965  3981 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-09 15:37:43.059  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:43.060  3965  3984 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-09 15:37:43.080  3965  3981 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-09 15:37:43.080  3965  3981 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 15:37:43.080  3965  3981 D BtGatt.GattService: current time is 424719369109
,08-09 15:37:43.081  3965  3981 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-09 15:37:43.083  3965  3981 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-09 15:37:43.422  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:37:43.497  3347  3347 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 15:37:45.040  3347  3394 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 415
,08-09 15:37:45.040  3347  3394 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 415, name: My test thread name)
,08-09 15:37:45.050  3347  4062 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 416, name: My test thread name)
08-09 15:37:45.050  3347  4062 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 416, thread name: My test thread name)
08-09 15:37:45.051  3347  4062 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 416, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-09 15:37:45.057  3347  3394 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-09 15:37:45.066  3347  4063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: My test thread name)
,08-09 15:37:45.067  3347  4063 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 420, thread name: My test thread name): Test exception.
08-09 15:37:45.068  3347  4063 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-09 15:37:45.076  3347  3394 I jxcore-log: Total number of executed tests:  82
08-09 15:37:45.076  3347  3394 I jxcore-log: 
,08-09 15:37:45.077  3347  3394 I jxcore-log: Number of passed tests:  81
08-09 15:37:45.077  3347  3394 I jxcore-log: 
08-09 15:37:45.078  3347  3394 I jxcore-log: Number of failed tests:  1
08-09 15:37:45.078  3347  3394 I jxcore-log: 
08-09 15:37:45.078  3347  3394 I jxcore-log: Number of ignored tests:  0
08-09 15:37:45.078  3347  3394 I jxcore-log: 
,08-09 15:37:45.080  3347  3394 I jxcore-log: Total duration:  76377
08-09 15:37:45.080  3347  3394 I jxcore-log: 
,08-09 15:37:45.081  3347  3394 I jxcore-log: Failures: 
08-09 15:37:45.081  3347  3394 I jxcore-log:  DiscoveryManager1 isRunning should return true
08-09 15:37:45.081  3347  3394 I jxcore-log: Expected: is <true>
08-09 15:37:45.081  3347  3394 I jxcore-log:      but: was <false>
08-09 15:37:45.081  3347  3394 I jxcore-log: 
08-09 15:37:45.081  3347  3394 I jxcore-log: 
08-09 15:37:45.082  3347  3394 I jxcore-log: Failed to execute UT.
08-09 15:37:45.082  3347  3394 I jxcore-log: 
08-09 15:37:45.082  3347  3394 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-09 15:37:45.082  3347  3394 I jxcore-log: 
,08-09 15:37:45.094  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.094  3347  3394 I jxcore-log: 
08-09 15:37:45.097  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.097  3347  3394 I jxcore-log: 
08-09 15:37:45.098  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.098  3347  3394 I jxcore-log: 
08-09 15:37:45.100  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.100  3347  3394 I jxcore-log: 
08-09 15:37:45.101  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.101  3347  3394 I jxcore-log: 
08-09 15:37:45.103  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.103  3347  3394 I jxcore-log: 
08-09 15:37:45.106  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.106  3347  3394 I jxcore-log: 
,08-09 15:37:45.108  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.108  3347  3394 I jxcore-log: 
,08-09 15:37:45.110  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.110  3347  3394 I jxcore-log: 
08-09 15:37:45.110  3347  3347 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-09 15:37:45.111  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.111  3347  3394 I jxcore-log: 
,08-09 15:37:45.112  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.112  3347  3394 I jxcore-log: 
,08-09 15:37:45.122  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.122  3347  3394 I jxcore-log: 
,08-09 15:37:45.123  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.123  3347  3394 I jxcore-log: 
,08-09 15:37:45.124  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.124  3347  3394 I jxcore-log: 
,08-09 15:37:45.125  3347  4059 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 415, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,08-09 15:37:45.127  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.127  3347  3394 I jxcore-log: 
08-09 15:37:45.128  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.128  3347  3394 I jxcore-log: 
,08-09 15:37:45.128  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.128  3347  3394 I jxcore-log: 
,08-09 15:37:45.129  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.129  3347  3394 I jxcore-log: 
08-09 15:37:45.130  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.130  3347  3394 I jxcore-log: 
08-09 15:37:45.130  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.130  3347  3394 I jxcore-log: 
,08-09 15:37:45.132  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.132  3347  3394 I jxcore-log: 
08-09 15:37:45.133  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.133  3347  3394 I jxcore-log: 
,08-09 15:37:45.133  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.133  3347  3394 I jxcore-log: 
08-09 15:37:45.133  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.133  3347  3394 I jxcore-log: 
,08-09 15:37:45.134  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.134  3347  3394 I jxcore-log: 
08-09 15:37:45.135  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.135  3347  3394 I jxcore-log: 
08-09 15:37:45.135  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.135  3347  3394 I jxcore-log: 
08-09 15:37:45.135  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.135  3347  3394 I jxcore-log: 
08-09 15:37:45.136  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.136  3347  3394 I jxcore-log: 
08-09 15:37:45.136  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.136  3347  3394 I jxcore-log: 
08-09 15:37:45.137  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.137  3347  3394 I jxcore-log: 
08-09 15:37:45.137  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.137  3347  3394 I jxcore-log: 
08-09 15:37:45.138  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.138  3347  3394 I jxcore-log: 
08-09 15:37:45.138  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.138  3347  3394 I jxcore-log: 
08-09 15:37:45.139  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.139  3347  3394 I jxcore-log: 
08-09 15:37:45.139  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.139  3347  3394 I jxcore-log: 
,08-09 15:37:45.140  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.140  3347  3394 I jxcore-log: 
08-09 15:37:45.140  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.140  3347  3394 I jxcore-log: 
,08-09 15:37:45.141  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.141  3347  3394 I jxcore-log: 
08-09 15:37:45.141  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.141  3347  3394 I jxcore-log: 
,08-09 15:37:45.142  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.142  3347  3394 I jxcore-log: 
08-09 15:37:45.142  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 15:37:45.142  3347  3394 I jxcore-log: 
,08-09 15:37:45.143  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.143  3347  3394 I jxcore-log: 
,08-09 15:37:45.143  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.143  3347  3394 I jxcore-log: 
08-09 15:37:45.144  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 15:37:45.144  3347  3394 I jxcore-log: 
,08-09 15:37:45.150  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.150  3347  3394 I jxcore-log: 
,08-09 15:37:45.151  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.151  3347  3394 I jxcore-log: 
,08-09 15:37:45.151  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.151  3347  3394 I jxcore-log: 
08-09 15:37:45.152  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.152  3347  3394 I jxcore-log: 
,08-09 15:37:45.152  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.152  3347  3394 I jxcore-log: 
08-09 15:37:45.153  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.153  3347  3394 I jxcore-log: 
,08-09 15:37:45.153  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-09 15:37:45.153  3347  3394 I jxcore-log: 
08-09 15:37:45.154  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.154  3347  3394 I jxcore-log: 
,08-09 15:37:45.154  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 15:37:45.154  3347  3394 I jxcore-log: 
08-09 15:37:45.155  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.155  3347  3394 I jxcore-log: 
08-09 15:37:45.155  3347  3394 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 15:37:45.155  3347  3394 I jxcore-log: 
,08-09 15:37:45.726  4064  4064 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-09 15:37:45.732  4064  4064 D AndroidRuntime: CheckJNI is OFF
,08-09 15:37:45.774  4064  4064 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-09 15:37:45.822  4064  4064 I Radio-JNI: register_android_hardware_Radio DONE
,08-09 15:37:45.845  4064  4064 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-09 15:37:45.853   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-09 15:37:45.854   874   887 I ActivityManager: Killing 3347:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-09 15:37:45.936   874  1777 D GraphicsStats: Buffer count: 2
,08-09 15:37:45.936   874  1610 I WindowState: WIN DEATH: Window{f469676 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-09 15:37:45.937   874  1318 D WifiService: Client connection lost with reason: 4
,08-09 15:37:45.994   874   897 W PackageSettings: Skipping PackageSetting{9bfd631 com.example.hello/10273} due to missing metadata
,08-09 15:37:46.029   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-09 15:37:46.029   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-09 15:37:46.030   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-09 15:37:46.030   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-09 15:37:46.030   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:37:46.030   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:37:46.030   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 15:37:46.030   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-09 15:37:46.031   874   887 I ActivityManager:   Force finishing activity ActivityRecord{2df8d33 u0 com.test.thalitest/.MainActivity t4}
,08-09 15:37:46.036   874  1777 W ActivityManager: Spurious death for ProcessRecord{a897d25 0:com.test.thalitest/u0a0}, curProc for 3347: null
,08-09 15:37:46.036   874   897 I art     : Starting a blocking GC Explicit
,08-09 15:37:46.088   874   897 I art     : Explicit concurrent mark sweep GC freed 55587(3MB) AllocSpace objects, 7(136KB) LOS objects, 33% free, 28MB/43MB, paused 716us total 50.206ms
,08-09 15:37:46.113   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-09 15:37:46.117  4064  4064 I art     : System.exit called, status: 0
,08-09 15:37:46.117  4064  4064 I AndroidRuntime: VM exiting with result code 0.
,08-09 15:37:46.172   874   897 I ActivityManager: Start proc 4074:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-09 15:37:46.175   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-09 15:37:46.210   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-09 15:37:46.218  3965  3965 D BluetoothMapAppObserver: onReceive
,08-09 15:37:46.218  3965  3965 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-09 15:37:46.221   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 15:37:46.221  1864  2073 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-09 15:37:46.230  3196  3196 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-09 15:37:46.236  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-09 15:37:46.238  1662  4087 I Keyboard.Facilitator.DecoderInitializer: run()
,08-09 15:37:46.251  1662  4087 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-09 15:37:46.260  1750  1750 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-09 15:37:46.264  1662  4087 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-09 15:37:46.264  1662  4087 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-09 15:37:46.264  1662  4087 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-09 15:37:46.264  1662  4087 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-09 15:37:46.264  1662  4087 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-09 15:37:46.265  1662  4087 I Decoder : createOrResetDecoder
,08-09 15:37:46.289   874  1919 I ActivityManager: Start proc 4090:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-09 15:37:46.296   874  1841 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3347 uid 10000
,08-09 15:37:46.297  1662  1662 I Keyboard.Facilitator: onFinishInput()
08-09 15:37:46.298  1521  1521 I ConfigService: onCreate
,08-09 15:37:46.300   874  1744 I ActivityManager: Killing 3642:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-09 15:37:46.310  1521  4102 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-09 15:37:46.310  1521  4102 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-09 15:37:46.310  1521  4102 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-09 15:37:46.316   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-09 15:37:46.314  1521  4102 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-09 15:37:46.339   874  1315 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-09 15:37:46.400  1662  4087 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-09 15:37:46.401  1764  1842 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-09 15:37:46.401   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-09 15:37:46.402   874   886 E PackageManager: Failed to write settings, restoring backup
08-09 15:37:46.402   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-09 15:37:46.402   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-09 15:37:46.402   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-09 15:37:46.402   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-09 15:37:46.402   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-09 15:37:46.402   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:37:46.402   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:37:46.402   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 15:37:46.406   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-09 15:37:46.406   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-09 15:37:46.406   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 15:37:46.406   874   887 E DropBoxManagerService: 	... 13 more
,08-09 15:37:46.417   874  1756 I ActivityManager: Start proc 4103:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-09 15:37:46.418  1764  1842 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-09 15:37:46.418  1764  1842 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1764
08-09 15:37:46.418  1764  1842 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:37:46.418  1764  1842 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 15:37:46.420   874  1919 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-09 15:37:46.420   874  4109 E DropBoxManagerService: Can't write: system_app_crash
08-09 15:37:46.420   874  4109 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 15:37:46.420   874  4109 E DropBoxManagerService: 	... 5 more
,08-09 15:37:46.432  1764  1842 I Process : Sending signal. PID: 1764 SIG: 9
,08-09 15:37:46.472  4090  4090 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-09 15:37:46.509  1662  4087 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-09 15:37:46.512  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-09 15:37:46.512  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-09 15:37:46.515  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-09 15:37:46.515  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-09 15:37:46.516  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-09 15:37:46.516  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-09 15:37:46.516  1662  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-09 15:37:46.516  1662  4087 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-09 15:37:46.516  1662  4087 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-09 15:37:46.517  1662  4087 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-09 15:37:46.517  1662  4087 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-09 15:37:46.517  1662  4087 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-09 15:37:46.555   874  1756 D GraphicsStats: Buffer count: 1
,08-09 15:37:46.555   874  1744 I WindowState: WIN DEATH: Window{779aa12 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-09 15:37:46.566   874  1756 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1764) has died
,08-09 15:37:46.567   874  1756 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-09 15:37:46.572   874  1756 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-09 15:37:46.593  4090  4120 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:37:46.593  4090  4120 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-09 15:37:46.593  4090  4120 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-09 15:37:46.605   874   887 I ActivityManager: Start proc 4123:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-09 15:37:46.610  4090  4090 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-09 15:37:46.621  1854  4122 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-09 15:37:46.622  1854  4122 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory

```
