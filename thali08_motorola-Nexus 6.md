#### Test 7968977578906ea_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-03 20:50:16.395  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 20:50:16.407  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 20:50:16.408  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-03 20:50:16.454  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-03 20:50:16.455  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-03 20:50:16.455  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:50:16.455  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-03 20:50:16.495  1499  2455 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-03 20:50:16.495  1499  2455 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-03 20:50:16.495  1499  2455 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-03 20:50:16.495  1499  2455 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-03 20:50:16.495  1499  2455 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-03 20:50:16.495  1499  2455 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-03 20:50:16.495  1499  2455 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-03 20:50:16.503  3410  3445 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-03 20:50:16.503  3410  3445 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-03 20:50:16.503  3410  3445 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-03 20:50:16.503  3410  3445 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-03 20:50:16.503  3410  3445 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-03 20:50:16.503  3410  3445 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-03 20:50:16.503  3410  3445 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-03 20:50:17.043  3750  3750 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 20:50:17.048  3750  3750 D AndroidRuntime: CheckJNI is OFF
08-03 20:50:17.083  3750  3750 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 20:50:17.126  3750  3750 I Radio-JNI: register_android_hardware_Radio DONE
08-03 20:50:17.145  3750  3750 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 20:50:17.150   872  1730 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 20:50:17.195   872  1730 I ActivityManager: Start proc 3763:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-03 20:50:17.204  3750  3750 D AndroidRuntime: Shutting down VM
08-03 20:50:17.348  3763  3763 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-03 20:50:17.377  3763  3763 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-03 20:50:17.388  3763  3763 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 3500-3505)
08-03 20:50:17.388  3763  3763 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:50:17.405  3763  3763 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d153fa}
08-03 20:50:17.405  3763  3763 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:50:17.406  3763  3763 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 20:50:17.412  3763  3763 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 20:50:17.414  3763  3763 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 20:50:17.458  3763  3763 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 20:50:17.483  3763  3763 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-03 20:50:17.483  3763  3763 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 20:50:17.483  3763  3763 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 20:50:17.483  3763  3763 I Adreno  : Build Date                       : 10/20/15
08-03 20:50:17.483  3763  3763 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 20:50:17.483  3763  3763 I Adreno  : Local Branch                     : M14
08-03 20:50:17.483  3763  3763 I Adreno  : Remote Branch                    : 
08-03 20:50:17.483  3763  3763 I Adreno  : Remote Branch                    : 
08-03 20:50:17.483  3763  3763 I Adreno  : Reconstruct Branch               : 
,08-03 20:50:17.577   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d7464c:true
,08-03 20:50:17.637  3763  3763 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-03 20:50:17.655  3763  3763 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-03 20:50:17.723  3763  3800 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-03 20:50:17.736  3763  3787 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-03 20:50:17.768  3763  3800 I OpenGLRenderer: Initialized EGL, version 1.4
,08-03 20:50:17.803  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-03 20:50:17.839   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +556ms (total +671ms)
,08-03 20:50:17.914  3763  3763 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3763
,08-03 20:50:18.106  3763  3763 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 20:50:18.246  3763  3802 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1696728784
,08-03 20:50:18.256  3763  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 20:50:18.256  3763  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 20:50:18.256  3763  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 20:50:18.256  3763  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 20:50:18.256  3763  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 20:50:18.256  3763  3802 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c5cf99 added. We now have 1 listener(s)
,08-03 20:50:18.260  3763  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-03 20:50:18.263  3763  3802 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:50:18.263  3763  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:50:18.264  3763  3802 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 20:50:18.268  3763  3802 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3094b0c added. We now have 1 listener(s)
,08-03 20:50:18.268  3763  3802 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-03 20:50:18.272   872  1307 D WifiService: New client listening to asynchronous messages,
,08-03 20:50:18.274  3763  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:50:18.274  3763  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 20:50:18.274  3763  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 20:50:18.274  3763  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 20:50:18.274  3763  3802 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 20:50:18.280  3763  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:50:18.281  3763  3802 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-03 20:50:18.288  3763  3802 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:18.288  3763  3802 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:18.288  3763  3802 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 20:50:18.288  3763  3802 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:50:18.289  3763  3802 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 20:50:18.295  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:18.302  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:18.328  3763  3763 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 20:50:19.827  3763  3810 W jxcore-log: Initializing JXcore engine
,08-03 20:50:19.827  3763  3810 W jxcore-log: JXcore engine is ready
,08-03 20:50:19.860  3810  3810 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-03 20:50:19.864  3810  3810 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10704]" dev="sockfs" ino=10704 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-03 20:50:19.864  3810  3810 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-03 20:50:19.864  3810  3810 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27559]" dev="sockfs" ino=27559 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-03 20:50:19.877  3763  3810 W jxcore-log: Starting JXcore engine
,08-03 20:50:19.956  3763  3810 W jxcore-log: Platform android
08-03 20:50:19.956  3763  3810 W jxcore-log: 
08-03 20:50:19.956  3763  3810 W jxcore-log: Process ARCH arm
08-03 20:50:19.956  3763  3810 W jxcore-log: 
,08-03 20:50:20.170  3763  3810 I jxcore-log: JXcore Cordova bridge is ready!
08-03 20:50:20.170  3763  3810 I jxcore-log: 
,08-03 20:50:20.171  3763  3810 W jxcore-log: JXcore engine is started
,08-03 20:50:20.181  3763  3802 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 20:50:20.187  3763  3763 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 20:50:35.769  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 20:50:35.769  3763  3810 I jxcore-log: 
,08-03 20:50:35.771  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 20:50:35.771  3763  3810 I jxcore-log: 
,08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:35.781  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:35.785  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:50:35.788  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 20:50:35.788  3763  3810 I jxcore-log: 
,08-03 20:50:35.789  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 20:50:35.789  3763  3810 I jxcore-log: 
,08-03 20:50:36.127  3763  3810 D ExecuteNativeTests: Running unit tests
,08-03 20:50:36.186  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:50:36.186  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e added. We now have 2 listener(s)
08-03 20:50:36.188  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 20:50:36.188  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:50:36.188  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:50:36.188  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:50:36.188  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff added. We now have 2 listener(s)
08-03 20:50:36.188  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:50:36.188  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 20:50:36.190  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:36.207  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:36.208  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:50:36.208  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:50:36.210  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.211  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.217  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-03 20:50:36.218  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 20:50:36.218  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 20:50:36.230  3763  3810 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-03 20:50:36.230  3763  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-03 20:50:36.230  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-03 20:50:36.230  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:50:36.230  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:50:36.231  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.231  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:50:36.232  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.232  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.232  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.232  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:50:36.232  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:50:36.232  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e removed from the list
08-03 20:50:36.232  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.232  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff removed from the list
,08-03 20:50:36.233  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.233  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:50:36.233  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.234  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:50:36.236  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.236  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:50:36.236  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.237  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.241  3763  3810 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 20:50:36.243  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:50:36.243  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.243  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.244  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.244  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.244  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.245  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
,08-03 20:50:36.245  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.245  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.245  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.245  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.246  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.246  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.246  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.248  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:50:36.248  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.249  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.249  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
,08-03 20:50:36.268  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-03 20:50:36.268  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 20:50:36.268  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 20:50:36.269  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 20:50:36.269  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 20:50:36.269  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 20:50:36.269  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-03 20:50:36.269  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 20:50:36.269  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 20:50:36.270  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 20:50:36.271  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 20:50:36.271  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.271  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.271  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.271  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.271  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:50:36.271  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.272  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.272  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.272  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.272  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.272  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.272  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.272  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.272  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.273  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.273  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:50:36.273  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.273  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.274  3763  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 20:50:36.276  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:36.283  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:36.286  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.286  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:50:36.288  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.288  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 20:50:36.288  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:50:36.288  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:50:36.288  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.288  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:50:36.290  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.292  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 20:50:36.292  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:50:36.299  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:50:36.301  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 20:50:36.302  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:50:36.305  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-03 20:50:36.311  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-03 20:50:36.312  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 20:50:36.313  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:50:36.314  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 20:50:36.316  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:50:36.326  2366  2377 D BtGatt.GattService: registerClient() - UUID=3ecfc2c9-0f54-4dbc-a946-b84d8b5807cb
,08-03 20:50:36.327  2366  2385 D BtGatt.GattService: onClientRegistered() - UUID=3ecfc2c9-0f54-4dbc-a946-b84d8b5807cb, clientIf=5
08-03 20:50:36.329  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 20:50:36.331  2366  2399 D BtGatt.GattService: start scan with filters
,08-03 20:50:36.339  2366  2388 D BtGatt.ScanManager: handling starting scan
,08-03 20:50:36.340  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 20:50:36.342  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:50:36.342  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-03 20:50:36.342  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:50:36.344  2366  2388 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:36.349  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:50:36.350  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 20:50:36.350  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:50:36.352  2366  2385 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 20:50:36.353  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.354  2366  2388 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:50:36.358  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:50:36.364  2366  2385 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 20:50:36.365  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.366  2366  2388 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:50:36.366  2366  2388 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:50:36.368  3763  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 20:50:36.376  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.376  3763  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-03 20:50:36.377  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.377  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 20:50:36.377  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.377  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:50:36.378  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:50:36.378  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:50:36.378  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-03 20:50:36.378  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:50:36.380  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:50:36.380  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-03 20:50:36.382  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:50:36.385  2366  2399 D BtGatt.GattService: stopScan() - queue size =1
,08-03 20:50:36.387  2366  2385 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:50:36.387  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.387  2366  2378 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:50:36.388  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-03 20:50:36.388  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:50:36.390  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:50:36.390  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-03 20:50:36.390  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:50:36.392  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:50:36.393  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 20:50:36.393  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:50:36.393  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:50:36.394  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:50:36.396  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:50:36.396  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:50:36.396  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:50:36.397  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.397  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.397  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:50:36.397  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.397  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.397  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.397  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:50:36.397  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.398  3763  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 20:50:36.399  2366  2385 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:50:36.399  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.401  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:36.411  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:36.413  2366  2385 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:50:36.414  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.414  2366  2388 D BtGatt.ScanManager: stopping BLe Batch
,08-03 20:50:36.415  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:50:36.415  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:50:36.417  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 20:50:36.417  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-03 20:50:36.419  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-03 20:50:36.419  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 20:50:36.419  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.419  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 20:50:36.422  2366  2385 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 20:50:36.422  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.422  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.423  2366  2388 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 20:50:36.425  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:50:36.425  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:50:36.431  2366  2385 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:50:36.431  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.431  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:50:36.432  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:50:36.433  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:50:36.437  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 20:50:36.437  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:50:36.438  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-03 20:50:36.439  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:50:36.442  2366  2377 D BtGatt.GattService: registerClient() - UUID=b8119465-61e4-46b1-9763-7645c5befbc7
08-03 20:50:36.443  2366  2385 D BtGatt.GattService: onClientRegistered() - UUID=b8119465-61e4-46b1-9763-7645c5befbc7, clientIf=5
,08-03 20:50:36.443  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:50:36.444  2366  2407 D BtGatt.GattService: start scan with filters
,08-03 20:50:36.450  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:50:36.450  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:50:36.450  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:50:36.450  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 20:50:36.451  2366  2388 D BtGatt.ScanManager: handling starting scan
,08-03 20:50:36.455  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:50:36.455  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:50:36.456  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 20:50:36.458  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:50:36.463  2366  2385 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 20:50:36.463  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.463  3763  3810 I io.jxcore.node.ConnectionHelper: start: OK
08-03 20:50:36.464  2366  2388 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:50:36.467  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:50:36.468  3763  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:50:36.468  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.468  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 20:50:36.468  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.468  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:50:36.468  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:50:36.468  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-03 20:50:36.468  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:50:36.469  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:50:36.469  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:50:36.469  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-03 20:50:36.471  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:50:36.472  2366  2377 D BtGatt.GattService: stopScan() - queue size =1
08-03 20:50:36.473  2366  2378 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:50:36.474  2366  2385 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 20:50:36.474  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.473  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:50:36.474  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:50:36.474  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:50:36.474  2366  2388 D BtGatt.ScanManager: Starting BLE batch scan
,08-03 20:50:36.474  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:50:36.475  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:50:36.475  2366  2388 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 20:50:36.476  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:50:36.476  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 20:50:36.476  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:50:36.477  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 20:50:36.477  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:50:36.479  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:50:36.479  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:50:36.479  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:50:36.479  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.480  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.480  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:50:36.480  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
,08-03 20:50:36.480  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.480  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
,08-03 20:50:36.480  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.480  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.481  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.481  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:50:36.483  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.483  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.483  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:50:36.483  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.484  3763  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 20:50:36.488  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.489  2366  2385 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:50:36.489  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:36.495  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:36.497  2366  2385 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-03 20:50:36.498  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.498  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.499  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:50:36.499  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:50:36.499  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:50:36.499  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 20:50:36.500  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.500  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 20:50:36.506  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-03 20:50:36.506  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:50:36.507  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.511  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.511  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:50:36.512  2366  2385 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 20:50:36.512  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.512  2366  2388 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:50:36.512  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:50:36.512  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:50:36.516  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 20:50:36.516  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:50:36.516  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:50:36.517  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:50:36.519  2366  2385 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-03 20:50:36.519  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.519  2366  2378 D BtGatt.GattService: registerClient() - UUID=d1334146-94b4-4baa-a267-c5760a39765e
08-03 20:50:36.519  2366  2388 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 20:50:36.520  2366  2385 D BtGatt.GattService: onClientRegistered() - UUID=d1334146-94b4-4baa-a267-c5760a39765e, clientIf=5
08-03 20:50:36.521  3763  3773 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:50:36.522  2366  2377 D BtGatt.GattService: start scan with filters
,08-03 20:50:36.527  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 20:50:36.527  2366  2385 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:50:36.527  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.527  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:50:36.527  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-03 20:50:36.528  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:50:36.530  2366  2388 D BtGatt.ScanManager: handling starting scan
,08-03 20:50:36.537  2366  2385 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 20:50:36.537  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.537  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:50:36.538  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-03 20:50:36.538  2366  2388 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 20:50:36.538  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:50:36.544  2366  2385 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 20:50:36.544  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.544  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-03 20:50:36.545  2366  2388 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:50:36.545  2366  2388 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 20:50:36.551  3763  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 20:50:36.551  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.551  3763  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:50:36.551  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.551  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-03 20:50:36.551  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.551  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:50:36.551  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:50:36.552  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:50:36.552  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:50:36.552  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:50:36.552  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:50:36.552  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:50:36.553  3763  3810 D BluetoothAdapter: STATE_ON
08-03 20:50:36.554  2366  2377 D BtGatt.GattService: stopScan() - queue size =1,
08-03 20:50:36.554  2366  2407 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:50:36.555  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:50:36.555  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-03 20:50:36.555  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:50:36.555  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:50:36.555  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 20:50:36.556  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:50:36.556  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 20:50:36.557  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-03 20:50:36.557  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:50:36.557  2366  2385 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:50:36.557  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.557  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:50:36.559  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:50:36.559  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:50:36.559  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-03 20:50:36.559  3763  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:50:36.559  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:50:36.559  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.559  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 20:50:36.559  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.559  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.559  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:50:36.559  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.559  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-03 20:50:36.560  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.560  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.560  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.560  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.560  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-03 20:50:36.561  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.561  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.561  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-03 20:50:36.561  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.562  3763  3810 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-03 20:50:36.563  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.563  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.563  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 20:50:36.563  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.563  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.563  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:50:36.563  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.564  2366  2385 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:50:36.564  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:50:36.563  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.564  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.564  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.564  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:50:36.564  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.564  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.564  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.565  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.565  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.565  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.565  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.566  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 20:50:36.567  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.567  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.567  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.567  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.567  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.567  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.567  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.567  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.567  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.567  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.567  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.568  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.568  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:50:36.568  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.569  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.569  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.569  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.569  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.570  3763  3810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 20:50:36.570  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.570  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.570  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.570  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.570  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.570  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.571  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.571  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.571  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.571  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.571  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.571  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.571  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.571  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.572  2366  2385 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:50:36.572  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.572  2366  2388 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:50:36.572  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.572  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.573  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.573  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.573  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 20:50:36.573  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.574  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.574  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.574  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.574  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.574  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.574  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.574  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.574  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.574  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.574  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.574  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.575  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.575  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.576  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.576  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.576  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.576  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.577  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:50:36.577  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:50:36.577  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:50:36.577  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:50:36.577  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:50:36.577  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:50:36.577  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.577  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.577  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.578  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.578  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.578  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.578  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.578  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.578  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.578  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.578  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.579  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.579  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.579  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.580  2366  2385 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:50:36.580  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.580  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.580  2366  2388 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:50:36.580  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.580  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.580  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.581  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:50:36.581  3763  3810 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 20:50:36.581  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 20:50:36.586  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:50:36.586  3763  3810 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 20:50:36.586  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 20:50:36.586  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 20:50:36.586  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 20:50:36.587  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 20:50:36.587  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 20:50:36.587  2366  2385 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:50:36.587  2366  2385 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:50:36.587  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 20:50:36.587  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 20:50:36.587  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 20:50:36.587  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 20:50:36.588  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 20:50:36.589  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 20:50:36.590  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 20:50:36.590  3763  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:50:36.590  3763  3810 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 20:50:36.590  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:50:36.590  3763  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:50:36.590  3763  3810 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 20:50:36.590  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:50:36.590  3763  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:50:36.591  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 20:50:36.594  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 20:50:36.595  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 20:50:36.595  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 20:50:36.596  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 20:50:36.596  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 20:50:36.596  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 20:50:36.596  3763  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:50:36.597  3763  3810 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 20:50:36.597  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.597  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.597  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.597  3763  3813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-03 20:50:36.597  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.597  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.597  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.597  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 20:50:36.599  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.599  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.599  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.599  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.599  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.600  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.600  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.600  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.601  3763  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-03 20:50:36.602  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.602  3763  3813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:50:36.602  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.602  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.602  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.603  3763  3810 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 20:50:36.604  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.604  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.604  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.604  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.604  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.604  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.604  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.605  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.605  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.605  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.605  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.605  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.605  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.605  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.606  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.606  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.606  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.606  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.607  3763  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 20:50:36.607  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.607  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.607  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.607  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.607  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.607  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.607  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.607  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.607  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.607  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.607  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.607  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.608  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.608  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.608  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.608  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.608  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.609  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.609  3763  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 20:50:36.609  3763  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 20:50:36.609  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:50:36.609  3763  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 20:50:36.609  3763  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 20:50:36.610  3763  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 20:50:36.610  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:50:36.610  3763  3810 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 20:50:36.610  3763  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 20:50:36.610  3763  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-03 20:50:36.610  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:50:36.610  3763  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 20:50:36.610  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.610  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.610  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.610  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.610  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.610  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.610  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.610  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.610  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.611  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.611  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.611  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.611  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.611  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.612  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.612  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.612  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.612  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.612  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.612  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.612  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.612  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.612  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.612  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.613  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.613  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.613  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.613  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.613  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.613  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.613  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.613  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.613  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.613  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.613  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.613  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.613  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.613  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.613  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.613  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.613  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.614  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.614  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.614  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.614  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.614  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.614  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.614  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.614  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.614  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.614  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.615  3763  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 20:50:36.615  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:50:36.616  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 20:50:36.617  3763  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 20:50:36.617  3763  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 20:50:36.617  3763  3763 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 20:50:36.617  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 20:50:36.617  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:50:36.617  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.617  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 20:50:36.617  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 20:50:36.618  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 20:50:36.618  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.618  3763  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 20:50:36.618  3763  3763 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 20:50:36.618  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.618  3763  3815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:50:36.618  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.618  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:50:36.618  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:50:36.618  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:50:36.618  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.618  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.619  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:50:36.619  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:50:36.619  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:50:36.619  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:50:36.619  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.619  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.619  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.620  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.620  3763  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-03 20:50:36.620  3763  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 20:50:36.620  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.620  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.620  3763  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 20:50:36.620  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.620  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.620  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.620  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.620  3763  3763 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 20:50:36.620  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.620  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.620  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.620  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.620  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.621  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.621  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.621  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.621  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.622  3763  3810 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 20:50:36.622  3763  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 20:50:36.622  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:50:36.624  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:50:36.624  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.624  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.624  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.624  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.624  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.624  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.624  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.625  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.625  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.625  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.625  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.625  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.625  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.625  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.626  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.626  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.627  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.627  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.631  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.631  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.631  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.631  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.632  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.632  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.632  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.632  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.632  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.632  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.632  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.632  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.632  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.632  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.633  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.633  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.634  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.634  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.635  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:50:36.635  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:50:36.635  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:50:36.635  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:50:36.635  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.635  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.635  3763  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c381e not in the list
08-03 20:50:36.635  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.635  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.636  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:50:36.636  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.636  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.636  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:50:36.636  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:50:36.637  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:50:36.637  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:50:36.638  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:50:36.638  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16138ff not in the list
08-03 20:50:36.639  3763  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 20:50:36.639  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:50:36.639  3763  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 20:50:36.639  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:50:36.639  3763  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 20:50:36.639  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:50:36.64,2  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 20:50:36.642  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 20:50:36.643  3763  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 20:50:36.643  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 20:50:36.643  3763  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 20:50:36.643  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 20:50:36.643  3763  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 20:50:36.643  3763  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 20:50:36.644  3763  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 20:50:36.644  3763  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 20:50:36.645  3763  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 20:50:36.645  3763  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 20:50:36.645  3763  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 20:50:36.645  3763  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 20:50:36.646  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:50:36.646  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96d05c9 added. We now have 2 listener(s)
08-03 20:50:36.646  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:50:36.649  3763  3810 D BluetoothAdapter: enable(): BT is already enabled..!
08-03 20:50:36.649   872  1716 D WifiService: setWifiEnabled: true pid=3763, uid=10000
08-03 20:50:36.649   872  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 20:50:36.650  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:50:36.650  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da4e4ce added. We now have 3 listener(s)
08-03 20:50:36.650  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:50:36.658  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:50:36.658  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2405fef added. We now have 4 listener(s)
,08-03 20:50:36.658  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:50:36.660  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:50:36.660  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@47ddafc added. We now have 5 listener(s)
,08-03 20:50:36.660  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:50:36.662   872  1686 D WifiService: setWifiEnabled: false pid=3763, uid=10000
08-03 20:50:36.662   872  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:50:36.667  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:50:36.668  2366  2381 D BluetoothAdapterState: Current state: ON, message: 23
08-03 20:50:36.668  2366  2381 D BluetoothAdapterProperties: Setting state to 13
08-03 20:50:36.668  2366  2381 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 20:50:36.669  2366  2381 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 20:50:36.669  2366  2381 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:36.671  2366  2385 D BluetoothAdapterProperties: Scan Mode:20
,08-03 20:50:36.672  2366  2381 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 20:50:36.672  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:36.672  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:50:36.673  2366  2366 D BluetoothMapService: onReceive
,08-03 20:50:36.673  2366  2366 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:50:36.673  2366  2366 D BluetoothMapService: STATE_TURNING_OFF
08-03 20:50:36.673  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:36.673  2366  2366 D BluetoothMapService: MAP Service closeService in
,08-03 20:50:36.673  2366  2366 D BluetoothMapMasInstance0: MAP Service shutdown
08-03 20:50:36.673  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:50:36.674  2366  2366 D ObexServerSockets0: shutdown(block = true)
,08-03 20:50:36.674  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:50:36.674  2366  2366 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-03 20:50:36.674  2366  2366 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-03 20:50:36.674  2366  2396 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-03 20:50:36.675  2366  2408 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 20:50:36.675  2366  2409 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-03 20:50:36.676  2366  2366 I BtOppRfcommListener: stopping Accept Thread
,08-03 20:50:36.676  2366  3270 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-03 20:50:36.676  2366  3270 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-03 20:50:36.678  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.680  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:50:36.681  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.681   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 20:50:36.682   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-03 20:50:36.682   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 20:50:36.682   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:50:36.684  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:36.684  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:50:36.684  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:36.685  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:36.687  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.690   872   885 I ActivityManager: Start proc 3818:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-03 20:50:36.692  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.695  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.696  2366  2366 D HeadsetService: Received stop request...Stopping profile...
08-03 20:50:36.696   872  1306 E native  : do suspend true
08-03 20:50:36.698  1718  1728 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:36.699  1363  1378 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:36.699  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-03 20:50:36.699   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:36.699   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:36.700   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:36.703  2366  2366 D A2dpService: Received stop request...Stopping profile...
08-03 20:50:36.704  2366  2402 D A2dpStateMachine: Exit Disconnected: -1
08-03 20:50:36.704   872   872 D BluetoothA2dp: Proxy object disconnected
,08-03 20:50:36.705  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-03 20:50:36.706  2366  2366 D HidService: Received stop request...Stopping profile...
08-03 20:50:36.706  2366  2366 D HidService: Stopping Bluetooth HidService
08-03 20:50:36.706  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-03 20:50:36.706  1363  1363 D HidProfile: Bluetooth service disconnected
08-03 20:50:36.707  2366  2366 D HealthService: Received stop request...Stopping profile...
08-03 20:50:36.709   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:50:36.709   872  2128 D DhcpClient: Clearing IP address
08-03 20:50:36.711  2366  2366 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:36.711  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:36.711  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:36.712  2366  2366 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:36.712  2366  2366 D PanService: Received stop request...Stopping profile...
,08-03 20:50:36.713   370   870 D CommandListener: Setting iface cfg
08-03 20:50:36.714   872  2141 D DhcpClient: Receive thread stopped
08-03 20:50:36.714  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:50:36.714  1363  1363 D PanProfile: Bluetooth service disconnected
,08-03 20:50:36.718  2366  2366 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-03 20:50:36.718  2366  2385 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 20:50:36.718  2366  2366 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:50:36.718  2366  2394 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:36.718  2366  2394 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:36.718  2366  2394 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:36.718   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-03 20:50:36.719   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-03 20:50:36.721  2366  2385 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-03 20:50:36.721  2366  2366 D BluetoothMapService: Received stop request...Stopping profile...
08-03 20:50:36.721  2366  2366 D BluetoothMapService: stop()
08-03 20:50:36.722   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-03 20:50:36.722  2366  2366 D BluetoothMapAppObserver: deinitObservers()
,08-03 20:50:36.722  2366  2366 D BluetoothMapAppObserver: removeReceiver()
08-03 20:50:36.724  1363  1363 D BluetoothMap: Proxy object disconnected
08-03 20:50:36.724  1363  1363 D MapProfile: Bluetooth service disconnected
,08-03 20:50:36.725   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
08-03 20:50:36.725   394   394 E Parcel  : Reading a NULL string not supported here.
08-03 20:50:36.725   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:50:36.725   872  1306 E native  : do suspend true
08-03 20:50:36.727  2366  2366 V BluetoothAdapterState: isTurningOff()=true
,08-03 20:50:36.727  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:36.727  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:36.727  2366  2366 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:36.730  2366  2385 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-03 20:50:36.730  2366  2394 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:36.730  2366  2394 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:36.730  2366  2394 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:50:36.730  2366  2394 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-03 20:50:36.730  2366  2394 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:50:36.730  2366  2394 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:50:36.731  2366  2366 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:36.731  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:36.731  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:50:36.731  2366  2366 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:36.732  2366  2366 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 20:50:36.732  2366  2385 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-03 20:50:36.732  2366  2366 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 20:50:36.732  2366  2366 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:36.732  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:36.732  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:36.732  2366  2366 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:36.732  2366  2366 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-03 20:50:36.733  2366  2385 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-03 20:50:36.733  2366  2366 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:50:36.733  2366  2366 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:36.733  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:36.733  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:36.733  2366  2366 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:36.734  2366  2366 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 20:50:36.734  2366  2366 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 20:50:36.734  2366  2366 D BluetoothMapService: MAP Service closeService in
08-03 20:50:36.734  2366  2366 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:36.735  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:36.735  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:36.735  2366  2366 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:36.738  2366  2381 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-03 20:50:36.738  2366  2381 D BluetoothAdapterProperties: Setting state to 15
08-03 20:50:36.738  2366  2366 D BluetoothMapService: cleanup()
08-03 20:50:36.738  2366  2381 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-03 20:50:36.738  2366  2366 D BluetoothMapService: MAP Service closeService in
08-03 20:50:36.739  2366  2381 I BluetoothAdapterState: Entering BleOnState
08-03 20:50:36.739  1363  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 20:50:36.739  1363  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-03 20:50:36.740  1363  3762 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 20:50:36.740  1363  1864 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:50:36.741  1718  2059 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:36.741   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:36.742  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:36.742   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:50:36.742  1363  1378 D BluetoothPan: onBluetoothStateChange on: false
08-03 20:50:36.742   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:36.742   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:36.742  2366  2381 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-03 20:50:36.743  2366  2381 D BluetoothAdapterProperties: Setting state to 16
08-03 20:50:36.743  2366  2381 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 20:50:36.743  2366  2381 D BluetoothAdapterProperties: onBleDisable
08-03 20:50:36.743  2366  2381 I BluetoothAdapterState: Entering PendingCommandState
08-03 20:50:36.743  2366  2382 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-03 20:50:36.744  2366  2385 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:50:36.745  2366  2394 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-03 20:50:36.745  2366  2394 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:36.745  3763  3813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
08-03 20:50:36.747  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.747,  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:36.747  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:50:36.748  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.748  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:36.749  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:36.749  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:50:36.751  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.751  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:36.752  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.753  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.756  1499  2308 V NativeCrypto: Read error: ssl=0xaa28ac00: I/O error during system call, Connection timed out
08-03 20:50:36.757  1499  2308 V NativeCrypto: SSL shutdown failed: ssl=0xaa28ac00: I/O error during system call, Broken pipe
08-03 20:50:36.769   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-03 20:50:36.774  3818  3818 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-03 20:50:36.782  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:50:36.789  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:50:36.792   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad25961:true
,08-03 20:50:36.801   872  1709 I ActivityManager: Start proc 3835:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-03 20:50:36.806   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:36.807   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:50:36.807   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-03 20:50:36.808   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:50:36.809   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-03 20:50:36.814   872   889 D Tethering: MasterInitialState.processMessage what=3
08-03 20:50:36.814  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:36.815  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:36.822  3280  3280 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d0325e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-03 20:50:36.828   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
08-03 20:50:36.829  1758  2052 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:50:36.830  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:36.830  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:50:36.831  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.831  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:36.831   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 20:50:36.832  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:36.832  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:36.833  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:36.833  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:36.844  3818  3818 D LocalBluetoothProfileManager: Adding local MAP profile
,08-03 20:50:36.847  3818  3818 D BluetoothMap: Create BluetoothMap proxy object
,08-03 20:50:36.853  3835  3835 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-03 20:50:36.857  3818  3818 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 20:50:36.864   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-03 20:50:36.865   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-03 20:50:36.867  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:50:36.878   872   882 I ActivityManager: Killing 2847:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-03 20:50:36.946  2366  2385 I bt_hci  : shut_down
,08-03 20:50:36.947  2366  2389 D bt_hwcfg: hw_epilog_process
08-03 20:50:36.948  2366  2389 I bt_vendor: low_power_mode_cb
,08-03 20:50:36.968  2366  2389 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-03 20:50:36.968  2366  2389 I bt_vendor: epilog_cb
08-03 20:50:36.968  2366  2389 I bt_hci  : epilog_finished_callback
,08-03 20:50:36.972  2366  2385 I bt_hci_h4: hal_close
08-03 20:50:36.972  2366  2385 I bt_userial_vendor: device fd = 51 close
,08-03 20:50:37.046  3835  3835 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.046  3835  3835 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.046  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.047  3835  3835 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.047  3835  3835 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.047  3835  3835 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.k.d(PG:583)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.e.b(PG:170)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.047  3835  3835 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.047  3835  3835 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.File.exists(File.java:361)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.047  3835  3835 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 20:50:37.047  3835  3835 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 20:50:37.053  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-03 20:50:37.069  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:50:37.073  3818  3818 D DockEventReceiver: finishStartingService: stopping service
08-03 20:50:37.077   872  1730 I ActivityManager: Killing 3373:com.google.android.talk/u0a61 (adj 15): empty #17
,08-03 20:50:37.120  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:50:37.187   872  1730 I ActivityManager: Start proc 3870:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-03 20:50:37.191  2366  2382 D bt_stack_manager: event_shut_down_stack finished.
,08-03 20:50:37.191  2366  2381 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-03 20:50:37.193  2366  2366 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 20:50:37.193  2366  2381 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-03 20:50:37.194  2366  2366 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 20:50:37.194  2366  2366 D BtGatt.GattService: stop()
,08-03 20:50:37.194  2366  2366 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 20:50:37.198  2366  2366 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:37.198  2366  2366 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:37.198  2366  2366 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:37.198  2366  2366 V BluetoothAdapterState: isBleTurningOff()=true
08-03 20:50:37.199  2366  2381 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-03 20:50:37.199  2366  2381 D BluetoothAdapterProperties: Setting state to 10
,08-03 20:50:37.199  2366  2381 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-03 20:50:37.199  2366  2381 I BluetoothAdapterState: Entering OffState
08-03 20:50:37.200   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-03 20:50:37.205  2366  2366 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-03 20:50:37.205  2366  2366 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 20:50:37.205  2366  2366 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 20:50:37.207  2366  2382 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 20:50:37.209  2366  2382 D bt_stack_manager: event_clean_up_stack finished.
,08-03 20:50:37.213  2366  2366 I art     : System.exit called, status: 0
,08-03 20:50:37.213  2366  2366 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 20:50:37.242  3870  3870 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-03 20:50:37.263   872  1835 I ActivityManager: Process com.android.bluetooth (pid 2366) has died
,08-03 20:50:37.384  3835  3858 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-03 20:50:37.453  3870  3890 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-03 20:50:37.453  3870  3890 I Babel_SMS: MmsConfig.loadMmsSettings
,08-03 20:50:37.458  3870  3890 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-03 20:50:37.458  3870  3890 I Babel_SMS: MmsConfig.loadFromDatabase
,08-03 20:50:37.509  3870  3890 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-03 20:50:37.510  3870  3890 I Babel_SMS: MmsConfig.loadFromResources
,08-03 20:50:37.513  3870  3890 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-03 20:50:37.516  3870  3890 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-03 20:50:37.560  3870  3870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:50:37.565  3870  3870 I Babel_Crash: startup - clean
,08-03 20:50:37.594  3870  3870 I Babel_telephony: TeleModule.launchCompleted
,08-03 20:50:37.604   872  1715 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-03 20:50:37.608   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@801ebbe:true
,08-03 20:50:37.610  3870  3870 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-03 20:50:37.622  3870  3870 W Babel   : BAM#gBA: invalid account id: -1
,08-03 20:50:37.622  3870  3870 W Babel   : BAM#gBA: invalid account id: -1
,08-03 20:50:37.626  3870  3895 I Babel   : deleted: false for 0
,08-03 20:50:37.623  3870  3870 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-03 20:50:37.638   872  1686 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-03 20:50:37.655  1840  1840 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:50:37.658  1840  1840 D SystemUpdateService: onCreate
,08-03 20:50:37.669  1840  1840 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:50:37.675  1840  3897 I SystemUpdateService: active receiver: enabled
,08-03 20:50:37.705  1840  3897 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:50:37.706  1840  3897 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-03 20:50:37.709  1840  3897 I SystemUpdateService: now status is 0 (complete)
08-03 20:50:37.709  1840  3897 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 20:50:37.709  1840  3897 I SystemUpdateService: file has been verified
08-03 20:50:37.709  1840  3897 I SystemUpdateService: OTA package size = 12249756
08-03 20:50:37.709  1840  1840 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-03 20:50:37.711  1840  2432 I iu.UploadsManager: num queued entries: 0
,08-03 20:50:37.716  1840  2432 I iu.UploadsManager: num updated entries: 0
,08-03 20:50:37.717  1840  3897 I SystemUpdateService: showing system update notification
,08-03 20:50:37.723  1840  2432 I iu.SyncManager: NEXT; no task
,08-03 20:50:37.729  1840  1840 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 20:50:37.730  1840  1840 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:50:37.742   872  1709 I ActivityManager: Start proc 3899:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-03 20:50:37.779  1840  1840 D SystemUpdateService: onDestroy
,08-03 20:50:37.798  3899  3899 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-03 20:50:37.806  3870  3870 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:50:37.809  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:50:37.815  3899  3899 D SprintDMHelper: simOperator: 
,08-03 20:50:37.815  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 20:50:37.828   872  1741 I ActivityManager: Start proc 3911:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-03 20:50:37.862  3870  3870 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 20:50:37.875  3870  3870 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:50:37.876  3870  3870 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:50:37.879  3870  3870 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:50:37.903  3870  3870 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:50:37.908   872  1715 I ActivityManager: Killing 3280:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-03 20:50:38.026  3870  3870 I vclib   : onServiceConnected
,08-03 20:50:38.056   872  1398 I ActivityManager: Start proc 3926:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-03 20:50:38.058  3870  3925 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-03 20:50:38.062   872  1715 I ActivityManager: Killing 3339:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-03 20:50:38.121  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-03 20:50:38.178  3926  3926 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-03 20:50:38.178  3926  3926 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-03 20:50:38.178  3926  3926 I GAv4    :   adb logcat -s GAv4
,08-03 20:50:38.194  3926  3926 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-03 20:50:38.200  3926  3926 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-03 20:50:38.234  3926  3943 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-03 20:50:38.338  3926  3926 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-03 20:50:38.379  3926  3926 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-03 20:50:38.390  3926  3926 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4501-4507)
08-03 20:50:38.390  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 20:50:38.400  3926  3926 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {81bef0e}
08-03 20:50:38.400  3926  3926 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-03 20:50:38.401  3926  3926 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-03 20:50:38.410  3926  3926 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-03 20:50:38.411  3926  3926 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-03 20:50:38.430  3926  3926 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-03 20:50:38.446  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 20:50:38.446  3926  3926 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-03 20:50:38.446  3926  3926 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-03 20:50:38.446  3926  3926 I Adreno  : Build Date                       : 10/20/15
08-03 20:50:38.446  3926  3926 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-03 20:50:38.446  3926  3926 I Adreno  : Local Branch                     : M14
08-03 20:50:38.446  3926  3926 I Adreno  : Remote Branch                    : 
08-03 20:50:38.446  3926  3926 I Adreno  : Remote Branch                    : 
08-03 20:50:38.446  3926  3926 I Adreno  : Reconstruct Branch               : 
,08-03 20:50:38.511  3926  3926 I NSApplication: Starting up...
,08-03 20:50:38.523  3926  3972 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 20:50:38.560   872  1730 I ActivityManager: Start proc 3977:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-03 20:50:38.561   872  1730 I ActivityManager: Killing 3037:android.process.acore/u0a5 (adj 15): empty #17
,08-03 20:50:38.649  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-03 20:50:38.827   872   882 I ActivityManager: Killing 3553:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-03 20:50:38.929   872  1773 I ActivityManager: Start proc 3992:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-03 20:50:39.009  3992  3992 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-03 20:50:39.076  3992  3992 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-03 20:50:39.091   872  1375 I ActivityManager: Killing 3568:com.android.musicfx/u0a18 (adj 15): empty #17
,08-03 20:50:39.194  1840  4016 I EventLogService: Opted in for usage reporting
,08-03 20:50:39.195  1840  4016 I EventLogService: Aggregate from 1470248405047 (log), 1470248405047 (data)
,08-03 20:50:39.267  1840  4016 W EventLogAggregator: Unknown tag: snet_gcore
08-03 20:50:39.267  1840  4016 W EventLogAggregator: Unknown tag: snet_launch_service
,08-03 20:50:39.307  1840  4016 I ServiceDumpSys: dumping service [account]
,08-03 20:50:39.679   872  1398 D WifiService: setWifiEnabled: true pid=3763, uid=10000
,08-03 20:50:39.680   872  1398 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:50:39.692   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-03 20:50:39.699  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:39.700  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:39.700  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:39.701  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:39.704  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:39.704  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:39.705  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:39.705  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:39.726   872  1306 D WifiConfigStore: loaded 0 passpoint configs
08-03 20:50:39.727   872  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:50:39.727   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 20:50:39.728   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-03 20:50:39.729   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:50:39.729   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 20:50:39.729   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 20:50:39.730   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 20:50:39.746   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 20:50:39.747   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:50:39.748   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:39.749   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-03 20:50:39.749   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 20:50:39.759   872  1306 E native  : do suspend true
,08-03 20:50:39.773   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:50:39.776   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 20:50:39.786   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 20:50:41.159   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:50:41.216   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.88 rxSuccessRate=23.56 delta 1000 -> 994
08-03 20:50:41.220   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-03 20:50:41.220   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:50:41.238   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 20:50:41.303   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 20:50:41.305  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 20:50:41.729  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 20:50:41.766  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 20:50:41.766  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 20:50:41.772   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:50:41.783   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:50:41.785   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 20:50:41.786   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:50:41.811   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:50:41.825   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:41.826   872  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-03 20:50:41.836   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 20:50:41.848   872  4030 D DhcpClient: Receive thread started
,08-03 20:50:41.934   872  1306 E native  : do suspend false
,08-03 20:50:41.949   872  2128 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 20:50:41.961   872  4030 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172435, domain null
,08-03 20:50:41.961   872  2128 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172435 seconds
,08-03 20:50:41.965   872  2128 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 20:50:41.977   872  4030 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 20:50:41.978   872  2128 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 20:50:41.982   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:41.987   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 20:50:41.990   872  1306 E native  : do suspend true
,08-03 20:50:41.991   872  2128 D DhcpClient: Scheduling renewal in 86399s
,08-03 20:50:42.010   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 20:50:42.013   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 20:50:42.014   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 20:50:42.017   872  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-03 20:50:42.028   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 20:50:42.100   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 20:50:42.100   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 20:50:42.104   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-03 20:50:42.107   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-03 20:50:42.112   872  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-03 20:50:42.132   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 20:50:42.138   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-03 20:50:42.138   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-03 20:50:42.138   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-03 20:50:42.139   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-03 20:50:42.140   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-03 20:50:42.140   872  1308 D ConnectivityService:    accepting network in place of null
,08-03 20:50:42.144   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:50:42.150   872  4029 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388267, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 20:50:42.198   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:42.234   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:42.242   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 20:50:42.243   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:50:42.253   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-03 20:50:42.265   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-03 20:50:42.272  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:42.273  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:50:42.273  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.273  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:50:42.276  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:42.276  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:50:42.276  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:42.276  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:42.276   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-03 20:50:42.283  1840  1840 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:50:42.286  1840  1840 D SystemUpdateService: onCreate
,08-03 20:50:42.289  1840  1840 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:50:42.292  1840  4042 I SystemUpdateService: active receiver: enabled
,08-03 20:50:42.299  1840  4042 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:50:42.301  1840  4042 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 20:50:42.301  1840  4042 I SystemUpdateService: now status is 0 (complete)
08-03 20:50:42.301  1840  4042 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 20:50:42.302  1840  4042 I SystemUpdateService: file has been verified
08-03 20:50:42.302  1840  4042 I SystemUpdateService: OTA package size = 12249756
,08-03 20:50:42.309  1840  4042 I SystemUpdateService: showing system update notification
,08-03 20:50:42.311  1840  1840 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 20:50:42.312  1840  2432 I iu.UploadsManager: num queued entries: 0
08-03 20:50:42.313  1840  2432 I iu.UploadsManager: num updated entries: 0
08-03 20:50:42.315  1840  4045 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-03 20:50:42.315  1840  4045 W BaseAppContext: Using Auth Proxy for data requests.
,08-03 20:50:42.316  1840  4045 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 20:50:42.317  1840  2432 I iu.SyncManager: NEXT; no task
08-03 20:50:42.318  1840  1840 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-03 20:50:42.319  1840  1840 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:50:42.322  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:50:42.326  3899  3899 D SprintDMHelper: simOperator: 
,08-03 20:50:42.326  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-03 20:50:42.327  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:50:42.329  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:50:42.329  1840  1840 D SystemUpdateService: onDestroy
,08-03 20:50:42.356  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-03 20:50:42.356  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-03 20:50:42.356  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:50:42.356  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:50:42.368  1840  4045 E MDM     : [215] SitrepService.a: Error sending sitrep.
,08-03 20:50:42.371  3870  3870 I art     : Waiting for a blocking GC DisableMovingGc
,08-03 20:50:42.374  3870  3870 I art     : Starting a blocking GC DisableMovingGc
,08-03 20:50:42.391   872  4028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:50:42 GMT], X-Android-Received-Millis=[1470250242389], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470250242337]}
,08-03 20:50:42.396   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-03 20:50:42.396   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-03 20:50:42.396   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-03 20:50:42.398   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 20:50:42.686   872  1398 D WifiService: setWifiEnabled: false pid=3763, uid=10000
,08-03 20:50:42.687   872  1398 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:50:42.718  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 20:50:42.726   872  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 20:50:42.726   872  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-03 20:50:42.726   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:50:42.727   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:50:42.747   872  1306 E native  : do suspend true
,08-03 20:50:42.754   872  2128 D DhcpClient: Clearing IP address
,08-03 20:50:42.754   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:50:42.757   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:42.759  1499  4054 V NativeCrypto: Read error: ssl=0x99f3e200: I/O error during system call, Connection timed out
,08-03 20:50:42.763   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-03 20:50:42.763   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-03 20:50:42.764  1499  4054 V NativeCrypto: SSL shutdown failed: ssl=0x99f3e200: I/O error during system call, Broken pipe
,08-03 20:50:42.770   394   394 E Parcel  : Reading a NULL string not supported here.
,08-03 20:50:42.771   872  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
08-03 20:50:42.771   872  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-03 20:50:42.771   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:50:42.771   872  1306 E native  : do suspend true
,08-03 20:50:42.776   872  4030 D DhcpClient: Receive thread stopped
,08-03 20:50:42.802   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:42.826   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:42.827   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:50:42.827   872  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 20:50:42.828   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:50:42.830   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-03 20:50:42.835  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:42.835  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:42.835  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:42.835  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:42.836  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:42.836  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:42.836  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.836  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:42.843   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:50:42.848  1840  1840 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:50:42.853  1840  1840 D SystemUpdateService: onCreate
,08-03 20:50:42.856  1840  1840 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:50:42.857   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:50:42.859  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:42.859  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:42.860  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.860  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:42.860   872  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-03 20:50:42.860  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:42.860  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:42.860  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:50:42.861  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:42.866  1758  2052 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:50:42.872  1840  1840 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-03 20:50:42.874  1840  2432 I iu.UploadsManager: num queued entries: 0
,08-03 20:50:42.874  1840  2432 I iu.UploadsManager: num updated entries: 0
,08-03 20:50:42.876  1840  2432 I iu.SyncManager: NEXT; no task
,08-03 20:50:42.878  1840  4061 I SystemUpdateService: active receiver: enabled
,08-03 20:50:42.880  1840  4061 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-03 20:50:42.889  1840  1840 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 20:50:42.890  1840  1840 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:50:42.893  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:50:42.896  3899  3899 D SprintDMHelper: simOperator: 
08-03 20:50:42.896  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-03 20:50:42.913  1840  4061 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-03 20:50:42.913  1840  4061 I SystemUpdateService: now status is 0 (complete)
08-03 20:50:42.913  1840  4061 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-03 20:50:42.913  1840  4061 I SystemUpdateService: file has been verified
08-03 20:50:42.913  1840  4061 I SystemUpdateService: OTA package size = 12249756
,08-03 20:50:42.939   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-03 20:50:42.941   872  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-03 20:50:42.955  1840  4061 I SystemUpdateService: showing system update notification
,08-03 20:50:42.972  1840  1840 D SystemUpdateService: onDestroy
,08-03 20:50:43.241   872  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 20:50:45.748   872   889 I ActivityManager: Start proc 4068:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 20:50:45.872  4068  4068 D AdapterServiceConfig: Adding HeadsetService
08-03 20:50:45.873  4068  4068 D AdapterServiceConfig: Adding A2dpService
08-03 20:50:45.873  4068  4068 D AdapterServiceConfig: Adding HidService
08-03 20:50:45.873  4068  4068 D AdapterServiceConfig: Adding HealthService
08-03 20:50:45.873  4068  4068 D AdapterServiceConfig: Adding PanService
08-03 20:50:45.874  4068  4068 D AdapterServiceConfig: Adding GattService
08-03 20:50:45.874  4068  4068 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 20:50:45.890  4068  4068 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 20:50:45.890   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e6c108c:true
,08-03 20:50:45.896  4068  4068 I bt_bluedroid: init
,08-03 20:50:45.896  4068  4080 I BluetoothAdapterState: Entering OffState
,08-03 20:50:45.901  4068  4081 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 20:50:45.902  4068  4081 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 20:50:45.902  4068  4081 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 20:50:45.902  4068  4081 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-03 20:50:45.904  4068  4068 I bt_bluedroid: get_profile_interface socket
,08-03 20:50:45.907  4068  4084 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:50:45.908  4068  4068 I bt_bluedroid: get_profile_interface sdp
,08-03 20:50:45.909  4068  4084 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:50:45.916  4068  4079 I bt_bluedroid: config_hci_snoop_log
,08-03 20:50:45.921   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 20:50:45.933  4068  4080 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 20:50:45.933  4068  4080 D BluetoothAdapterProperties: Setting state to 14
,08-03 20:50:45.934  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 20:50:45.940  4068  4080 D BluetoothBondStateMachine: make
,08-03 20:50:45.946  4068  4085 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 20:50:45.956  4068  4080 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:45.958  4068  4068 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 20:50:45.968  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:45.971  4068  4068 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 20:50:45.973  4068  4068 D BtGatt.GattService: Received start request. Starting profile...
,08-03 20:50:45.974  4068  4068 D BtGatt.GattService: start()
,08-03 20:50:45.974  4068  4068 I bt_bluedroid: get_profile_interface gatt
08-03 20:50:45.975  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
08-03 20:50:45.975  4068  4068 D BtGatt.AdvertiseManager: advertise manager created
,08-03 20:50:45.985  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:45.985  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:45.985  4068  4068 V BluetoothAdapterState: isBleTurningOn()=true
08-03 20:50:45.985  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:45.986  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 20:50:45.987  4068  4080 I bt_bluedroid: enable
,08-03 20:50:45.987  4068  4081 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-03 20:50:45.988  4068  4081 I bt_hci  : start_up
,08-03 20:50:46.008  4068  4081 I bt_vendor: alloc value 0xb3a7f189
,08-03 20:50:46.008  4068  4081 I bt_vendor: init
,08-03 20:50:46.008  4068  4081 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-03 20:50:46.008  4068  4081 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 20:50:46.118  4068  4081 D bt_hci  : start_up starting async portion
,08-03 20:50:46.118  4068  4088 I bt_hci  : event_finish_startup
,08-03 20:50:46.119  4068  4088 I bt_hci_h4: hal_open
08-03 20:50:46.119  4068  4088 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 20:50:46.129  4068  4088 I bt_userial_vendor: device fd = 51 open
,08-03 20:50:46.160  4068  4088 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:50:46.192  4068  4088 D bt_hwcfg: Chipset BCM4354A2
,08-03 20:50:46.192  4068  4088 D bt_hwcfg: Target name = [BCM4354A2]
08-03 20:50:46.193  4068  4088 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 20:50:46.848  4068  4088 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 20:50:46.849  4068  4088 D bt_hwcfg: Settlement delay -- 100 ms
08-03 20:50:46.849  4068  4088 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 20:50:46.966  4068  4088 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:50:46.968  4068  4088 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 20:50:46.997  4068  4088 I bt_hwcfg: vendor lib fwcfg completed
,08-03 20:50:46.997  4068  4088 I bt_vendor: firmware callback
,08-03 20:50:46.997  4068  4088 I bt_hci  : firmware_config_callback
,08-03 20:50:47.006  4068  4092 I bt_btu  : btu_task pending for preload complete event
,08-03 20:50:47.006  4068  4092 I bt_btu_task: Bluetooth chip preload is complete
08-03 20:50:47.007  4068  4092 I bt_btu  : btu_task received preload complete event
,08-03 20:50:47.015  4068  4092 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 20:50:47.016  4068  4092 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 20:50:47.016  4068  4092 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 20:50:47.016  4068  4092 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 20:50:47.016  4068  4092 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-03 20:50:47.017  4068  4092 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 20:50:47.017  4068  4092 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-03 20:50:47.017  4068  4092 I         : BTE_InitTraceLevels -- TRC_BTM
,08-03 20:50:47.017  4068  4092 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 20:50:47.018  4068  4092 I         : BTE_InitTraceLevels -- TRC_PAN
,08-03 20:50:47.018  4068  4092 I         : BTE_InitTraceLevels -- TRC_SDP
,08-03 20:50:47.018  4068  4092 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 20:50:47.018  4068  4092 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 20:50:47.019  4068  4092 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 20:50:47.019  4068  4092 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 20:50:47.153  4068  4092 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fcd9d
,08-03 20:50:47.153  4068  4092 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fcd9d 
,08-03 20:50:47.162  4068  4084 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-03 20:50:47.166  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 20:50:47.167  4068  4084 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:50:47.171  4068  4084 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:50:47.174  4068  4084 D BluetoothAdapterProperties: Scan Mode:20
,08-03 20:50:47.175  4068  4084 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 20:50:47.175  4068  4084 D bt_hci  : do_postload posting postload work item
,08-03 20:50:47.175  4068  4088 I bt_hci  : event_postload
,08-03 20:50:47.176  4068  4088 I bt_vendor: sco_config_cb
,08-03 20:50:47.176  4068  4088 I bt_hci  : sco_config_callback postload finished.
08-03 20:50:47.179  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:47.180  4068  4084 D bt_bte_conf: Device ID record 1 : primary
08-03 20:50:47.180  4068  4084 D bt_bte_conf:   vendorId            = 000f
,08-03 20:50:47.180  4068  4084 D bt_bte_conf:   vendorIdSource      = 0001
08-03 20:50:47.181  4068  4084 D bt_bte_conf:   product             = 1200
,08-03 20:50:47.181  4068  4084 D bt_bte_conf:   version             = 1436
,08-03 20:50:47.181  4068  4084 D bt_bte_conf:   clientExecutableURL = 
,08-03 20:50:47.181  4068  4084 D bt_bte_conf:   serviceDescription  = 
08-03 20:50:47.181  4068  4084 D bt_bte_conf:   documentationURL    = 
,08-03 20:50:47.182  4068  4084 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 20:50:47.182  4068  4081 D bt_stack_manager: event_start_up_stack finished
08-03 20:50:47.183  4068  4088 I bt_vendor: low_power_mode_cb
,08-03 20:50:47.183  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 20:50:47.183  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:47.185  4068  4080 D BluetoothAdapterProperties: Setting state to 15
,08-03 20:50:47.185  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-03 20:50:47.186  4068  4080 I BluetoothAdapterState: Entering BleOnState
,08-03 20:50:47.189  4068  4080 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-03 20:50:47.190  4068  4080 D BluetoothAdapterProperties: Setting state to 11
08-03 20:50:47.191  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-03 20:50:47.208  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:47.211  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
08-03 20:50:47.214  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:47.214  4068  4068 D HeadsetService: Received start request. Starting profile...
08-03 20:50:47.218  4068  4068 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 20:50:47.218  4068  4068 D HeadsetStateMachine: make
,08-03 20:50:47.223  4068  4080 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:47.228  4068  4068 D HeadsetStateMachine: max_hf_connections = 1,
,08-03 20:50:47.228  4068  4068 I bt_bluedroid: get_profile_interface handsfree
,08-03 20:50:47.229  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 20:50:47.229  4068  4084 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-03 20:50:47.235  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:47.235  4068  4068 D A2dpService: Received start request. Starting profile...
,08-03 20:50:47.236  4068  4068 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 20:50:47.236  4068  4068 I bt_bluedroid: get_profile_interface avrcp,
,08-03 20:50:47.243  4068  4068 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 20:50:47.243  4068  4068 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:50:47.243  4068  4068 D A2dpStateMachine: make
,08-03 20:50:47.244  4068  4068 I bt_bluedroid: get_profile_interface a2dp
,08-03 20:50:47.244  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 20:50:47.246  4068  4102 D A2dpStateMachine: Enter Disconnected: -2
,08-03 20:50:47.246  4068  4068 I BluetoothHidServiceJni: classInitNative: succeeds
,08-03 20:50:47.247  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:47.249  4068  4068 D HidService: Received start request. Starting profile...
,08-03 20:50:47.249  3818  3818 D BluetoothInputDevice: Proxy object connected
,08-03 20:50:47.249  4068  4068 I bt_bluedroid: get_profile_interface hidhost
08-03 20:50:47.249  4068  4068 D HidService: setHidService(): set to: null
08-03 20:50:47.249  4068  4084 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39de3e5
08-03 20:50:47.249  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-03 20:50:47.249  4068  4068 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 20:50:47.250  3818  3818 D HidProfile: Bluetooth service connected
08-03 20:50:47.250  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:47.251  4068  4068 D HealthService: Received start request. Starting profile...
,08-03 20:50:47.252  4068  4068 I bt_bluedroid: get_profile_interface health
,08-03 20:50:47.254  4068  4068 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 20:50:47.254  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:47.255  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:50:47.255  4068  4068 D PanService: Received start request. Starting profile...
,08-03 20:50:47.256  4068  4068 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 20:50:47.256  4068  4068 I bt_bluedroid: get_profile_interface pan
,08-03 20:50:47.256  4068  4084 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-03 20:50:47.258  4068  4068 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:47.258  3818  3818 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 20:50:47.259  3818  3818 D PanProfile: Bluetooth service connected
,08-03 20:50:47.259  4068  4068 D BluetoothMapService: Received start request. Starting profile...
08-03 20:50:47.259  4068  4068 D BluetoothMapService: start()
08-03 20:50:47.259  3818  3818 D BluetoothMap: Proxy object connected
08-03 20:50:47.260  3818  3818 D MapProfile: Bluetooth service connected
,08-03 20:50:47.260  3818  3818 D BluetoothMap: getConnectedDevices()
08-03 20:50:47.260  3818  3818 D BluetoothMap: Bluetooth is Not enabled
,08-03 20:50:47.261  4068  4068 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-03 20:50:47.262  4068  4068 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-03 20:50:47.262  4068  4068 D BluetoothMapAppObserver: createReceiver()
08-03 20:50:47.263  4068  4068 D BluetoothMapAppObserver: initObservers()
08-03 20:50:47.263  4068  4068 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 20:50:47.270  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:47.270  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:47.270  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:47.271  4068  4100 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 20:50:47.271  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:47.273  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:47.274  4068  4068 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:47.274  4068  4068 V BluetoothAdapterState: isTurningOn()=true
,08-03 20:50:47.274  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:50:47.274  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:47.275  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:47.276  4068  4068 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:47.276  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:47.276  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:47.276  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-03 20:50:47.276  4068  4080 D BluetoothAdapterProperties: ScanMode =  20
08-03 20:50:47.276  4068  4080 D BluetoothAdapterProperties: State =  11
,08-03 20:50:47.277  4068  4084 D BluetoothAdapterProperties: Scan Mode:21
,08-03 20:50:47.277  4068  4084 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:50:47.277  4068  4080 D BluetoothAdapterProperties: Setting state to 12
,08-03 20:50:47.277  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-03 20:50:47.278  4068  4080 I BluetoothAdapterState: Entering OnState
,08-03 20:50:47.278  3818  3829 D BluetoothPan: onBluetoothStateChange on: true
08-03 20:50:47.279  3818  3828 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 20:50:47.279  1363  3762 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:47.281  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:47.281  1363  1363 D BluetoothInputDevice: Proxy object connected
,08-03 20:50:47.281  1363  1363 D HidProfile: Bluetooth service connected
08-03 20:50:47.282  1363  1864 D BluetoothMap: onBluetoothStateChange: up=true
08-03 20:50:47.283  1363  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 20:50:47.283  1363  1363 D BluetoothMap: Proxy object connected
08-03 20:50:47.284  1363  1363 D MapProfile: Bluetooth service connected,
,08-03 20:50:47.284  1363  1363 D BluetoothMap: getConnectedDevices()
,08-03 20:50:47.284  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:47.285  1363  3762 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 20:50:47.287  1363  1363 D BluetoothA2dp: Proxy object connected
08-03 20:50:47.287  1718  2059 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:47.288   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:47.288  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:47.288  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:47.288   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:50:47.289   872   872 D BluetoothA2dp: Proxy object connected
,08-03 20:50:47.289  3818  3829 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 20:50:47.290  4068  4068 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 20:50:47.291  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:47.291  4068  4068 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-03 20:50:47.292  1363  3762 D BluetoothPan: onBluetoothStateChange on: true
08-03 20:50:47.292  4068  4068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-03 20:50:47.293  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:50:47.293  1363  1363 D PanProfile: Bluetooth service connected
08-03 20:50:47.294   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:50:47.294  3818  3828 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 20:50:47.294   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:47.294  4068  4068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:50:47.295   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 20:50:47.297  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:47.298  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:47.299  4068  4068 D ObexServerSockets: Succeed to create listening sockets 
08-03 20:50:47.299  4068  4068 D ObexServerSockets0: startAccept()
08-03 20:50:47.300  4068  4068 D ObexServerSockets0: prepareForNewConnect()
08-03 20:50:47.302  4068  4068 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-03 20:50:47.302  4068  4068 D BluetoothSdpJni: SDP Create record success - handle: 0
08-03 20:50:47.303  4068  4108 D ObexServerSockets0: Accepting socket connection...
08-03 20:50:47.303  4068  4068 D BluetoothMapService: onReceive
,08-03 20:50:47.303  4068  4068 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:50:47.303  4068  4068 D BluetoothMapService: STATE_ON
08-03 20:50:47.304  4068  4109 D ObexServerSockets0: Accepting socket connection...
08-03 20:50:47.305  3818  3818 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-03 20:50:47.308  3818  3818 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-03 20:50:47.314  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:50:47.318  3818  3818 D BluetoothA2dp: Proxy object connected
,08-03 20:50:47.320  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:50:47.327  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:50:47.331  1363  1363 D BluetoothPbap: Proxy object connected
,08-03 20:50:47.331  1363  1363 D PbapServerProfile: Bluetooth service connected
08-03 20:50:47.331  3818  3818 D BluetoothPbap: Proxy object connected
,08-03 20:50:47.331  4068  4068 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 20:50:47.331  4068  4068 D ObexServerSockets0: prepareForNewConnect()
08-03 20:50:47.332  3818  3818 D PbapServerProfile: Bluetooth service connected
,08-03 20:50:47.340  4068  4113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:50:47.360  4068  4117 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:50:47.362  4068  4117 I BtOppRfcommListener: Accept thread started.
,08-03 20:50:47.389  1718  1940 D BluetoothHeadset: Proxy object connected
,08-03 20:50:47.390  1363  3762 D BluetoothHeadset: Proxy object connected
,08-03 20:50:47.390  1363  1363 D HeadsetProfile: Bluetooth service connected
08-03 20:50:47.390  1363  1864 D BluetoothHeadset: Proxy object connected
08-03 20:50:47.390   872   872 D BluetoothHeadset: Proxy object connected
,08-03 20:50:47.390   872   872 D BluetoothHeadset: Proxy object connected
08-03 20:50:47.390   872   872 D BluetoothHeadset: Proxy object connected
,08-03 20:50:47.394  3870  4049 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-03 20:50:47.394  3870  4049 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 20:50:47.394   872   889 D BluetoothHeadset: Proxy object connected
08-03 20:50:47.394   872   889 D BluetoothHeadset: Proxy object connected
,08-03 20:50:47.395  3870  4049 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-03 20:50:47.396  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-03 20:50:47.398   872  1715 I ActivityManager: Killing 3304:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-03 20:50:47.412  3818  3829 D BluetoothHeadset: Proxy object connected
,08-03 20:50:47.413  3818  3818 D HeadsetProfile: Bluetooth service connected
,08-03 20:50:48.707  4068  4080 D BluetoothAdapterState: Current state: ON, message: 23
,08-03 20:50:48.708  4068  4080 D BluetoothAdapterProperties: Setting state to 13
,08-03 20:50:48.708  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 20:50:48.710  4068  4080 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 20:50:48.714  4068  4080 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:48.723  4068  4068 D BluetoothMapService: onReceive
,08-03 20:50:48.723  4068  4068 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 20:50:48.724  4068  4068 D BluetoothMapService: STATE_TURNING_OFF
,08-03 20:50:48.724  4068  4068 D BluetoothMapService: MAP Service closeService in
,08-03 20:50:48.725  4068  4068 D BluetoothMapMasInstance0: MAP Service shutdown
08-03 20:50:48.726  4068  4068 D ObexServerSockets0: shutdown(block = true)
08-03 20:50:48.727  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:48.727  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:48.729  4068  4068 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 20:50:48.730  4068  4068 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-03 20:50:48.730  4068  4109 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-03 20:50:48.731  4068  4108 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-03 20:50:48.733  4068  4095 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-03 20:50:48.735  4068  4068 I BtOppRfcommListener: stopping Accept Thread
,08-03 20:50:48.736  4068  4084 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:50:48.737  4068  4117 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:50:48.736  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:48.737  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:48.737  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-03 20:50:48.737  4068  4117 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-03 20:50:48.740  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:48.740  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:50:48.741  4068  4068 D HeadsetService: Received stop request...Stopping profile...
08-03 20:50:48.741  3763  3763 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:50:48.741  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:48.743  3818  3828 D BluetoothHeadset: Proxy object disconnected
,08-03 20:50:48.743  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:48.744  1718  1738 D BluetoothHeadset: Proxy object disconnected
,08-03 20:50:48.744  4068  4068 D A2dpService: Received stop request...Stopping profile...
08-03 20:50:48.744  1363  1864 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:48.744  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:48.745   872   872 D BluetoothHeadset: Proxy object disconnected
,08-03 20:50:48.745   872   872 D BluetoothHeadset: Proxy object disconnected
,08-03 20:50:48.745   872   872 D BluetoothHeadset: Proxy object disconnected
08-03 20:50:48.745  4068  4102 D A2dpStateMachine: Exit Disconnected: -1
08-03 20:50:48.748   872   872 D BluetoothA2dp: Proxy object disconnected
08-03 20:50:48.749  4068  4068 D HidService: Received stop request...Stopping profile...
08-03 20:50:48.749  4068  4068 D HidService: Stopping Bluetooth HidService
08-03 20:50:48.749  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:50:48.750  4068  4068 V BluetoothAdapterState: isTurningOff()=true
,08-03 20:50:48.750  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:48.750  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:48.750  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:48.753  4068  4068 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 20:50:48.753  4068  4068 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-03 20:50:48.754  4068  4068 D HealthService: Received stop request...Stopping profile...
08-03 20:50:48.754  3818  3818 D HeadsetProfile: Bluetooth service disconnected
08-03 20:50:48.754  3818  3818 D BluetoothA2dp: Proxy object disconnected
08-03 20:50:48.754  3818  3818 D BluetoothInputDevice: Proxy object disconnected
08-03 20:50:48.754  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-03 20:50:48.754  3818  3818 D HidProfile: Bluetooth service disconnected
,08-03 20:50:48.754  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-03 20:50:48.755  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-03 20:50:48.755  4068  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:48.755  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-03 20:50:48.755  4068  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-03 20:50:48.755  1363  1363 D HidProfile: Bluetooth service disconnected
08-03 20:50:48.755  4068  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:48.755  4068  4084 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-03 20:50:48.756  4068  4068 D PanService: Received stop request...Stopping profile...
08-03 20:50:48.757  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:50:48.757  1363  1363 D PanProfile: Bluetooth service disconnected
,08-03 20:50:48.758  4068  4068 D BluetoothMapService: Received stop request...Stopping profile...
08-03 20:50:48.758  4068  4068 D BluetoothMapService: stop()
,08-03 20:50:48.758  4068  4068 D BluetoothMapAppObserver: deinitObservers()
08-03 20:50:48.758  3818  3818 D DockEventReceiver: finishStartingService: stopping service
08-03 20:50:48.759  4068  4068 D BluetoothMapAppObserver: removeReceiver()
08-03 20:50:48.760  1363  1363 D BluetoothMap: Proxy object disconnected
08-03 20:50:48.760  1363  1363 D MapProfile: Bluetooth service disconnected
,08-03 20:50:48.760  3818  3818 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:50:48.760  3818  3818 D PanProfile: Bluetooth service disconnected
08-03 20:50:48.760  4068  4068 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:48.760  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:48.760  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:48.760  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:48.762  4068  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:48.762  4068  4068 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:48.762  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:48.762  4068  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:48.762  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:48.762  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-03 20:50:48.762  4068  4092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:50:48.763  4068  4092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:50:48.763  4068  4092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:50:48.763  4068  4092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:50:48.763  3818  3818 D BluetoothMap: Proxy object disconnected
08-03 20:50:48.762  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:48.764  4068  4068 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 20:50:48.764  4068  4084 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 20:50:48.765  4068  4068 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 20:50:48.766  3818  3818 D MapProfile: Bluetooth service disconnected
08-03 20:50:48.767  4068  4068 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:48.767  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:48.767  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:48.767  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:48.767  4068  4068 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 20:50:48.768  4068  4084 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-03 20:50:48.768  4068  4068 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:50:48.768  4068  4068 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:48.768  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:48.768  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:50:48.768  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:48.769  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:50:48.769  4068  4068 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 20:50:48.769  4068  4068 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-03 20:50:48.773  4068  4068 D BluetoothMapService: MAP Service closeService in
08-03 20:50:48.773  4068  4068 V BluetoothAdapterState: isTurningOff()=true
08-03 20:50:48.773  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:48.773  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:50:48.774  4068  4068 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:48.774  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-03 20:50:48.774  4068  4080 D BluetoothAdapterProperties: Setting state to 15
,08-03 20:50:48.774  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-03 20:50:48.774  4068  4068 D BluetoothMapService: cleanup()
08-03 20:50:48.775  4068  4080 I BluetoothAdapterState: Entering BleOnState
08-03 20:50:48.775  3818  3829 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:48.775  4068  4068 D BluetoothMapService: MAP Service closeService in
08-03 20:50:48.776  3818  3828 D BluetoothPan: onBluetoothStateChange on: false
08-03 20:50:48.777  3818  3829 D BluetoothMap: onBluetoothStateChange: up=false
08-03 20:50:48.778  1363  1363 D BluetoothPbap: Proxy object disconnected
,08-03 20:50:48.778  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-03 20:50:48.778  1363  3762 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 20:50:48.778  3818  3818 D BluetoothPbap: Proxy object disconnected
08-03 20:50:48.778  3818  3818 D PbapServerProfile: Bluetooth service disconnected
08-03 20:50:48.781  1363  1864 D BluetoothMap: onBluetoothStateChange: up=false
08-03 20:50:48.783  1363  1374 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 20:50:48.783  1363  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:50:48.784  1718  1728 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 20:50:48.784   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:48.784  1363  3762 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:48.784   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:50:48.784  3818  3829 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 20:50:48.785  3818  3828 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 20:50:48.785  1363  1864 D BluetoothPan: onBluetoothStateChange on: false
08-03 20:50:48.786   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:50:48.786  3818  4121 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 20:50:48.786   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 20:50:48.787  4068  4080 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-03 20:50:48.787  4068  4080 D BluetoothAdapterProperties: Setting state to 16
,08-03 20:50:48.787  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-03 20:50:48.788  4068  4080 D BluetoothAdapterProperties: onBleDisable
08-03 20:50:48.789  4068  4081 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-03 20:50:48.790  4068  4080 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:48.790  4068  4084 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:50:48.791  4068  4092 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-03 20:50:48.791  4068  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-03 20:50:48.792  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:48.793  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:48.794  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:50:48.795  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:48.796  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:48.798  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:50:48.803  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:50:48.991  4068  4084 I bt_hci  : shut_down
,08-03 20:50:48.992  4068  4088 D bt_hwcfg: hw_epilog_process
08-03 20:50:48.993  4068  4088 I bt_vendor: low_power_mode_cb
,08-03 20:50:49.015  4068  4088 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-03 20:50:49.015  4068  4088 I bt_vendor: epilog_cb
08-03 20:50:49.016  4068  4088 I bt_hci  : epilog_finished_callback
,08-03 20:50:49.027  4068  4084 I bt_hci_h4: hal_close
,08-03 20:50:49.029  4068  4084 I bt_userial_vendor: device fd = 51 close
,08-03 20:50:49.147  4068  4081 D bt_stack_manager: event_shut_down_stack finished.
,08-03 20:50:49.148  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-03 20:50:49.155  4068  4080 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-03 20:50:49.155  4068  4068 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 20:50:49.157  4068  4068 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 20:50:49.157  4068  4068 D BtGatt.GattService: stop()
,08-03 20:50:49.157  4068  4068 D BtGatt.AdvertiseManager: advertise clients cleared
,08-03 20:50:49.162  4068  4068 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:49.162  4068  4068 V BluetoothAdapterState: isTurningOn()=false
08-03 20:50:49.162  4068  4068 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:49.163  4068  4068 V BluetoothAdapterState: isBleTurningOff()=true
,08-03 20:50:49.163  4068  4080 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-03 20:50:49.164  4068  4080 D BluetoothAdapterProperties: Setting state to 10
,08-03 20:50:49.164  4068  4080 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-03 20:50:49.165  4068  4080 I BluetoothAdapterState: Entering OffState
08-03 20:50:49.167   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-03 20:50:49.194  4068  4068 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-03 20:50:49.194  4068  4068 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-03 20:50:49.195  4068  4081 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-03 20:50:49.201  4068  4081 D bt_stack_manager: event_clean_up_stack finished.
,08-03 20:50:49.201  4068  4068 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-03 20:50:49.206  4068  4068 I art     : System.exit called, status: 0
,08-03 20:50:49.207  4068  4068 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 20:50:49.273   872  1773 I ActivityManager: Process com.android.bluetooth (pid 4068) has died
,08-03 20:50:50.145   872  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-03 20:50:51.704  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:50:51.704  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:50:54.712  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:50:54.713  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cae7fda added. We now have 6 listener(s)
08-03 20:50:54.713  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:50:54.718  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:50:54.718  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ddd0c0b added. We now have 7 listener(s)
08-03 20:50:54.719  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:50:54.720  3763  3810 I System.out: IsBluetoothEnabled
,08-03 20:50:54.733  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:54.783   872   889 I ActivityManager: Start proc 4129:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-03 20:50:54.911  4129  4129 D AdapterServiceConfig: Adding HeadsetService
08-03 20:50:54.912  4129  4129 D AdapterServiceConfig: Adding A2dpService
08-03 20:50:54.912  4129  4129 D AdapterServiceConfig: Adding HidService
08-03 20:50:54.912  4129  4129 D AdapterServiceConfig: Adding HealthService
08-03 20:50:54.912  4129  4129 D AdapterServiceConfig: Adding PanService
08-03 20:50:54.913  4129  4129 D AdapterServiceConfig: Adding GattService
08-03 20:50:54.913  4129  4129 D AdapterServiceConfig: Adding BluetoothMapService
,08-03 20:50:54.929   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9d5cd9:true
,08-03 20:50:54.929  4129  4129 D BluetoothAdapterState: make() - Creating AdapterState
,08-03 20:50:54.934  4129  4129 I bt_bluedroid: init
,08-03 20:50:54.935  4129  4141 I BluetoothAdapterState: Entering OffState
,08-03 20:50:54.939  4129  4142 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-03 20:50:54.940  4129  4142 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-03 20:50:54.940  4129  4142 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-03 20:50:54.940  4129  4142 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-03 20:50:54.942  4129  4129 I bt_bluedroid: get_profile_interface socket
08-03 20:50:54.944  4129  4129 I bt_bluedroid: get_profile_interface sdp
08-03 20:50:54.947  4129  4145 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:50:54.960  4129  4145 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:50:54.963  4129  4140 I bt_bluedroid: config_hci_snoop_log
,08-03 20:50:54.967   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-03 20:50:54.978  4129  4141 D BluetoothAdapterState: Current state: OFF, message: 0
,08-03 20:50:54.978  4129  4141 D BluetoothAdapterProperties: Setting state to 14
,08-03 20:50:54.979  4129  4141 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-03 20:50:54.982  4129  4141 D BluetoothBondStateMachine: make
,08-03 20:50:54.986  4129  4146 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-03 20:50:54.990  4129  4141 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:54.992  4129  4129 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-03 20:50:54.996  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:54.998  4129  4129 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 20:50:54.999  4129  4129 D BtGatt.GattService: Received start request. Starting profile...
,08-03 20:50:54.999  4129  4129 D BtGatt.GattService: start()
,08-03 20:50:54.999  4129  4129 I bt_bluedroid: get_profile_interface gatt
,08-03 20:50:55.001  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:55.001  4129  4129 D BtGatt.AdvertiseManager: advertise manager created
,08-03 20:50:55.011  4129  4129 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:55.012  4129  4129 V BluetoothAdapterState: isTurningOn()=false
,08-03 20:50:55.012  4129  4129 V BluetoothAdapterState: isBleTurningOn()=true
,08-03 20:50:55.012  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:55.013  4129  4141 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-03 20:50:55.013  4129  4141 I bt_bluedroid: enable
08-03 20:50:55.014  4129  4142 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-03 20:50:55.014  4129  4142 I bt_hci  : start_up
,08-03 20:50:55.034  4129  4142 I bt_vendor: alloc value 0xb3a7f189
,08-03 20:50:55.034  4129  4142 I bt_vendor: init
08-03 20:50:55.034  4129  4142 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-03 20:50:55.035  4129  4142 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-03 20:50:55.145  4129  4142 D bt_hci  : start_up starting async portion
,08-03 20:50:55.145  4129  4149 I bt_hci  : event_finish_startup
08-03 20:50:55.146  4129  4149 I bt_hci_h4: hal_open
,08-03 20:50:55.146  4129  4149 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-03 20:50:55.154  4129  4149 I bt_userial_vendor: device fd = 51 open
,08-03 20:50:55.186  4129  4149 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:50:55.218  4129  4149 D bt_hwcfg: Chipset BCM4354A2
,08-03 20:50:55.219  4129  4149 D bt_hwcfg: Target name = [BCM4354A2]
,08-03 20:50:55.220  4129  4149 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-03 20:50:55.878  4129  4149 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-03 20:50:55.880  4129  4149 D bt_hwcfg: Settlement delay -- 100 ms
08-03 20:50:55.880  4129  4149 I bt_hwcfg: Setting fw settlement delay to 100 
,08-03 20:50:55.997  4129  4149 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-03 20:50:55.998  4129  4149 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-03 20:50:56.028  4129  4149 I bt_hwcfg: vendor lib fwcfg completed
08-03 20:50:56.028  4129  4149 I bt_vendor: firmware callback
,08-03 20:50:56.028  4129  4149 I bt_hci  : firmware_config_callback
,08-03 20:50:56.040  4129  4151 I bt_btu  : btu_task pending for preload complete event
,08-03 20:50:56.040  4129  4151 I bt_btu_task: Bluetooth chip preload is complete
,08-03 20:50:56.040  4129  4151 I bt_btu  : btu_task received preload complete event
,08-03 20:50:56.050  4129  4151 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 20:50:56.051  4129  4151 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 20:50:56.051  4129  4151 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 20:50:56.051  4129  4151 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 20:50:56.052  4129  4151 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 20:50:56.052  4129  4151 I         : BTE_InitTraceLevels -- TRC_A2D
,08-03 20:50:56.052  4129  4151 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 20:50:56.053  4129  4151 I         : BTE_InitTraceLevels -- TRC_BTM
,08-03 20:50:56.053  4129  4151 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 20:50:56.053  4129  4151 I         : BTE_InitTraceLevels -- TRC_PAN
,08-03 20:50:56.053  4129  4151 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 20:50:56.054  4129  4151 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 20:50:56.054  4129  4151 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 20:50:56.054  4129  4151 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 20:50:56.054  4129  4151 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 20:50:56.188  4129  4151 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39fcd9d
,08-03 20:50:56.188  4129  4151 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39fcd9d 
,08-03 20:50:56.212  4129  4145 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-03 20:50:56.214  4129  4145 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-03 20:50:56.215  4129  4145 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-03 20:50:56.221  4129  4145 D BluetoothAdapterProperties: Name is: Nexus 6
,08-03 20:50:56.227  4129  4145 D BluetoothAdapterProperties: Scan Mode:20
,08-03 20:50:56.227  4129  4145 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-03 20:50:56.229  4129  4145 D bt_hci  : do_postload posting postload work item
,08-03 20:50:56.230  4129  4149 I bt_hci  : event_postload
,08-03 20:50:56.230  4129  4149 I bt_vendor: sco_config_cb
,08-03 20:50:56.230  4129  4149 I bt_hci  : sco_config_callback postload finished.
08-03 20:50:56.233  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:56.234  4129  4145 D bt_bte_conf: Device ID record 1 : primary
08-03 20:50:56.234  4129  4145 D bt_bte_conf:   vendorId            = 000f
08-03 20:50:56.235  4129  4145 D bt_bte_conf:   vendorIdSource      = 0001
,08-03 20:50:56.235  4129  4145 D bt_bte_conf:   product             = 1200
08-03 20:50:56.235  4129  4145 D bt_bte_conf:   version             = 1436
08-03 20:50:56.235  4129  4145 D bt_bte_conf:   clientExecutableURL = 
,08-03 20:50:56.236  4129  4145 D bt_bte_conf:   serviceDescription  = 
08-03 20:50:56.236  4129  4145 D bt_bte_conf:   documentationURL    = 
08-03 20:50:56.236  4129  4145 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-03 20:50:56.236  4129  4142 D bt_stack_manager: event_start_up_stack finished,
08-03 20:50:56.238  4129  4149 I bt_vendor: low_power_mode_cb
08-03 20:50:56.238  4129  4141 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-03 20:50:56.239  4129  4141 D BluetoothAdapterProperties: Setting state to 15
08-03 20:50:56.239  4129  4141 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15,
08-03 20:50:56.239  4129  4141 I BluetoothAdapterState: Entering BleOnState
08-03 20:50:56.244  4129  4141 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-03 20:50:56.244  4129  4141 D BluetoothAdapterProperties: Setting state to 11
08-03 20:50:56.244  4129  4141 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-03 20:50:56.251  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
08-03 20:50:56.252  4129  4129 D HeadsetService: Received start request. Starting profile...
08-03 20:50:56.256  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:56.256  4129  4129 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 20:50:56.256  4129  4129 D HeadsetStateMachine: make
,08-03 20:50:56.268  4129  4129 D HeadsetStateMachine: max_hf_connections = 1
,08-03 20:50:56.268  4129  4129 I bt_bluedroid: get_profile_interface handsfree
,08-03 20:50:56.268  4129  4145 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-03 20:50:56.269  4129  4145 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-03 20:50:56.274  4129  4141 I BluetoothAdapterState: Entering PendingCommandState
,08-03 20:50:56.280  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:56.281  4129  4129 D A2dpService: Received start request. Starting profile...
,08-03 20:50:56.283  4129  4129 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-03 20:50:56.284  4129  4129 I bt_bluedroid: get_profile_interface avrcp
,08-03 20:50:56.293  4129  4129 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 20:50:56.293  4129  4129 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:50:56.293  4129  4129 D A2dpStateMachine: make
,08-03 20:50:56.296  4129  4129 I bt_bluedroid: get_profile_interface a2dp
,08-03 20:50:56.297  4129  4145 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-03 20:50:56.300  4129  4160 D A2dpStateMachine: Enter Disconnected: -2
,08-03 20:50:56.301  4129  4129 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 20:50:56.302  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:56.303  4129  4129 D HidService: Received start request. Starting profile...
,08-03 20:50:56.304  4129  4129 I bt_bluedroid: get_profile_interface hidhost
,08-03 20:50:56.304  4129  4129 D HidService: setHidService(): set to: null
,08-03 20:50:56.304  4129  4145 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39de3e5
,08-03 20:50:56.304  4129  4145 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-03 20:50:56.308  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:50:56.309  4129  4129 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 20:50:56.310  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:56.311  4129  4129 D HealthService: Received start request. Starting profile...
,08-03 20:50:56.313  4129  4129 I bt_bluedroid: get_profile_interface health
08-03 20:50:56.315  4129  4129 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-03 20:50:56.317  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:56.318  4129  4129 D PanService: Received start request. Starting profile...
08-03 20:50:56.318  4129  4129 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-03 20:50:56.318  4129  4129 I bt_bluedroid: get_profile_interface pan
,08-03 20:50:56.319  4129  4145 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 20:50:56.324  4129  4129 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
,08-03 20:50:56.325  4129  4129 D BluetoothMapService: Received start request. Starting profile...
08-03 20:50:56.325  4129  4129 D BluetoothMapService: start()
,08-03 20:50:56.328  4129  4129 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-03 20:50:56.330  4129  4129 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-03 20:50:56.330  4129  4129 D BluetoothMapAppObserver: createReceiver()
,08-03 20:50:56.331  4129  4129 D BluetoothMapAppObserver: initObservers()
08-03 20:50:56.331  4129  4129 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-03 20:50:56.340  4129  4129 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:56.340  4129  4129 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:56.340  4129  4157 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 20:50:56.340  4129  4129 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:56.340  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:56.342  4129  4129 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isBleTurningOn()=false,
08-03 20:50:56.343  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:56.344  4129  4129 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:56.344  4129  4129 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:56.344  4129  4129 V BluetoothAdapterState: isBleTurningOn()=false,
08-03 20:50:56.344  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isTurningOff()=false
08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isTurningOn()=true
,08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isBleTurningOn()=false
,08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isTurningOff()=false
,08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isTurningOn()=true
08-03 20:50:56.345  4129  4129 V BluetoothAdapterState: isBleTurningOn()=false
08-03 20:50:56.346  4129  4129 V BluetoothAdapterState: isBleTurningOff()=false
,08-03 20:50:56.346  4129  4141 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-03 20:50:56.346  4129  4141 D BluetoothAdapterProperties: ScanMode =  20
08-03 20:50:56.346  4129  4141 D BluetoothAdapterProperties: State =  11
08-03 20:50:56.348  4129  4145 D BluetoothAdapterProperties: Scan Mode:21
08-03 20:50:56.348  4129  4145 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:50:56.348  4129  4141 D BluetoothAdapterProperties: Setting state to 12
,08-03 20:50:56.348  4129  4141 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 20:50:56.349  3818  3829 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:56.349  4129  4141 I BluetoothAdapterState: Entering OnState
08-03 20:50:56.351  3818  3828 D BluetoothPan: onBluetoothStateChange on: true
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:56.354  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:50:56.354  3818  4121 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 20:50:56.356  1363  1864 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 20:50:56.357  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:50:56.359  1363  3762 D BluetoothMap: onBluetoothStateChange: up=true
08-03 20:50:56.359  1363  1363 D BluetoothInputDevice: Proxy object connected
08-03 20:50:56.359  1363  1363 D HidProfile: Bluetooth service connected
,08-03 20:50:56.360  1363  1378 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 20:50:56.361  4129  4129 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-03 20:50:56.361  1363  1363 D BluetoothMap: Proxy object connected
,08-03 20:50:56.361  1363  1363 D MapProfile: Bluetooth service connected
08-03 20:50:56.361  1363  1363 D BluetoothMap: getConnectedDevices()
08-03 20:50:56.362  4129  4129 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-03 20:50:56.362  1363  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:50:56.364  4129  4129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:50:56.364  1718  1728 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:56.365   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:56.365  1363  1864 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:50:56.365   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:50:56.366  3818  3829 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:50:56.366  4129  4129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:50:56.368  3818  4121 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 20:50:56.369  3818  3818 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:50:56.369  3818  3818 D PanProfile: Bluetooth service connected
08-03 20:50:56.369  4129  4129 D ObexServerSockets: Succeed to create listening sockets 
,08-03 20:50:56.370  1363  3762 D BluetoothPan: onBluetoothStateChange on: true
,08-03 20:50:56.369  4129  4129 D ObexServerSockets0: startAccept()
,08-03 20:50:56.370  4129  4129 D ObexServerSockets0: prepareForNewConnect()
08-03 20:50:56.371  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,08-03 20:50:56.372   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:50:56.372  1363  1363 D PanProfile: Bluetooth service connected
,08-03 20:50:56.372  3818  3828 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 20:50:56.374   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:50:56.375  3818  3818 D BluetoothMap: Proxy object connected,
08-03 20:50:56.375  3818  3818 D MapProfile: Bluetooth service connected
08-03 20:50:56.375  3818  3818 D BluetoothMap: getConnectedDevices()
08-03 20:50:56.377  4129  4129 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-03 20:50:56.377  4129  4129 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-03 20:50:56.378  4129  4165 D ObexServerSockets0: Accepting socket connection...
08-03 20:50:56.378  4129  4166 D ObexServerSockets0: Accepting socket connection...
08-03 20:50:56.379   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-03 20:50:56.381  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:50:56.383  1363  1363 D BluetoothA2dp: Proxy object connected
,08-03 20:50:56.384  4129  4129 D BluetoothMapService: onReceive
08-03 20:50:56.383   872   872 D BluetoothA2dp: Proxy object connected
,08-03 20:50:56.384  4129  4129 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:50:56.384  4129  4129 D BluetoothMapService: STATE_ON
08-03 20:50:56.384  3818  3818 D BluetoothInputDevice: Proxy object connected
,08-03 20:50:56.384  3818  3818 D HidProfile: Bluetooth service connected
,08-03 20:50:56.394  3818  3818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-03 20:50:56.397  3818  3818 D BluetoothA2dp: Proxy object connected
,08-03 20:50:56.401  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 20:50:56.407  3818  3818 D DockEventReceiver: finishStartingService: stopping service
,08-03 20:50:56.410  3818  3818 D BluetoothPbap: Proxy object connected
,08-03 20:50:56.410  3818  3818 D PbapServerProfile: Bluetooth service connected
,08-03 20:50:56.412  4129  4129 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-03 20:50:56.413  4129  4129 D ObexServerSockets0: prepareForNewConnect()
08-03 20:50:56.413  1363  1363 D BluetoothPbap: Proxy object connected
08-03 20:50:56.413  1363  1363 D PbapServerProfile: Bluetooth service connected
,08-03 20:50:56.421  4129  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:50:56.438  4129  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:50:56.439  4129  4176 I BtOppRfcommListener: Accept thread started.
,08-03 20:50:56.452  3818  3829 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.452  3818  3818 D HeadsetProfile: Bluetooth service connected
08-03 20:50:56.453  1718  2059 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.453  1363  1374 D BluetoothHeadset: Proxy object connected
08-03 20:50:56.454  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-03 20:50:56.454   872   872 D BluetoothHeadset: Proxy object connected
08-03 20:50:56.454   872   872 D BluetoothHeadset: Proxy object connected
08-03 20:50:56.454   872   872 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.465  1718  1940 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.465   872   889 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.466  1363  1864 D BluetoothHeadset: Proxy object connected
08-03 20:50:56.466  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-03 20:50:56.472   872   889 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.473   872   889 D BluetoothHeadset: Proxy object connected
,08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:56.753  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:56.760  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:56.764  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:50:56.764  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c4baae8 added. We now have 8 listener(s)
08-03 20:50:56.765  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:50:56.770   872   882 D WifiService: setWifiEnabled: false pid=3763, uid=10000
,08-03 20:50:56.770   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:50:56.781  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:50:56.782   872  1715 D WifiService: setWifiEnabled: true pid=3763, uid=10000
08-03 20:50:56.783   872  1715 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:50:56.794   872  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:56.812  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:56.819  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:56.821   872  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-03 20:50:56.822   872  1306 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 20:50:56.822   872  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-03 20:50:56.823   872  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-03 20:50:56.824   872  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-03 20:50:56.824   872  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-03 20:50:56.824   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-03 20:50:56.825   872  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-03 20:50:56.840   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:50:56.840   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-03 20:50:56.842   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:56.893   872  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-03 20:50:56.894   872  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-03 20:50:56.899   872  1306 E native  : do suspend true
,08-03 20:50:56.906   872  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-03 20:50:56.919   872  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-03 20:50:56.930   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:50:57.803  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:50:57.810  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:50:57.822  3763  4182 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-03 20:50:57.822  3763  4182 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 20:50:58.331   872  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-03 20:50:58.477   872  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.25 rxSuccessRate=24.94 delta 1000 -> 994
,08-03 20:50:58.479   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-03 20:50:58.479   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:50:58.492   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-03 20:50:58.544   872  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-03 20:50:58.550  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-03 20:50:58.968  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 20:50:59.012  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 20:50:59.013  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-03 20:50:59.022   872  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-03 20:50:59.037   872  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:50:59.038   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 20:50:59.039   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:50:59.069   872  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-03 20:50:59.090   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:59.091   872  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-03 20:50:59.106   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-03 20:50:59.150   872  4185 D DhcpClient: Receive thread started
,08-03 20:50:59.243   872  1306 E native  : do suspend false
,08-03 20:50:59.264   872  2128 D DhcpClient: Broadcasting DHCPDISCOVER
,08-03 20:50:59.278   872  4185 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-03 20:50:59.279   872  2128 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-03 20:50:59.282   872  2128 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-03 20:50:59.296   872  4185 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-03 20:50:59.297   872  2128 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-03 20:50:59.302   370   870 D CommandListener: Setting iface cfg
,08-03 20:50:59.314   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-03 20:50:59.314   872  2128 D DhcpClient: Scheduling renewal in 86399s
,08-03 20:50:59.319   872  1306 E native  : do suspend true
,08-03 20:50:59.343   872  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-03 20:50:59.347   872  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-03 20:50:59.349   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-03 20:50:59.352   872  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-03 20:50:59.360   872  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 20:50:59.422   872  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-03 20:50:59.423   872  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-03 20:50:59.426   872  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-03 20:50:59.432   872  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-03 20:50:59.436   872  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-03 20:50:59.447   872  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 20:50:59.454   872  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-03 20:50:59.454   872  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-03 20:50:59.454   872  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-03 20:50:59.454   872  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-03 20:50:59.454   872  1308 D ConnectivityService:    accepting network in place of null
08-03 20:50:59.455   872  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-03 20:50:59.456   872  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-03 20:50:59.467   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-03 20:50:59.515   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:59.548   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-03 20:50:59.554   872  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-03 20:50:59.554   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:50:59.555   872  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-03 20:50:59.563   872   889 D Tethering: MasterInitialState.processMessage what=3
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:50:59.586  3763  3763 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:50:59.588  3763  3763 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:50:59.593   872  4183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-03 20:50:59.596  1840  1840 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-03 20:50:59.603  1840  1840 D SystemUpdateService: onCreate
,08-03 20:50:59.607  1840  1840 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-03 20:50:59.634  1840  4194 I SystemUpdateService: active receiver: enabled
,08-03 20:50:59.637  1840  1840 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-03 20:50:59.648  1840  4194 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-03 20:50:59.648  1840  2432 I iu.UploadsManager: num queued entries: 0
08-03 20:50:59.648  1840  2432 I iu.UploadsManager: num updated entries: 0
,08-03 20:50:59.650  1840  1840 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-03 20:50:59.652  1840  1840 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-03 20:50:59.655  3899  3899 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:50:59.660  1840  4197 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-03 20:50:59.661  1840  4197 W BaseAppContext: Using Auth Proxy for data requests.
,08-03 20:50:59.662  1840  4197 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 20:50:59.664  1840  4194 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-03 20:50:59.664  1840  4194 I SystemUpdateService: now status is 0 (complete)
08-03 20:50:59.664  1840  4194 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-03 20:50:59.664  3899  3899 D SprintDMHelper: simOperator: 
,08-03 20:50:59.664  3899  3899 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-03 20:50:59.664  1840  4194 I SystemUpdateService: file has been verified
08-03 20:50:59.664  1840  4194 I SystemUpdateService: OTA package size = 12249756
,08-03 20:50:59.665  1840  2432 I iu.SyncManager: NEXT; no task
08-03 20:50:59.671  1840  4194 I SystemUpdateService: showing system update notification
,08-03 20:50:59.675  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:50:59.678  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:50:59.707   872  4183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:50:59 GMT], X-Android-Received-Millis=[1470250259707], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470250259658]}
,08-03 20:50:59.708   872  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-03 20:50:59.709   872  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-03 20:50:59.709   872  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-03 20:50:59.713   872  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-03 20:50:59.743  1840  1840 D SystemUpdateService: onDestroy
,08-03 20:50:59.748  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-03 20:50:59.748  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-03 20:50:59.749  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:50:59.749  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:50:59.763  1840  4197 E MDM     : [220] SitrepService.a: Error sending sitrep.
,08-03 20:50:59.889  3870  4199 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-03 20:51:00.830  3763  4182 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-03 20:51:00.830  3763  4207 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-03 20:51:00.832  3763  4182 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-03 20:51:00.833  3763  4207 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-03 20:51:00.834  3763  4182 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:51:00.835  3763  4207 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:51:00.836  3763  4182 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:51:00.837  3763  4209 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Sender)
,08-03 20:51:00.837  3763  4207 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:51:00.838  3763  4182 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-03 20:51:00.838  3763  4207 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 20:51:00.842  3763  4211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: OutgoingSocketThread/Receiver)
08-03 20:51:00.843  3763  4210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: IncomingSocketThread/Sender)
08-03 20:51:00.844  3763  4211 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: OutgoingSocketThread/Receiver)
08-03 20:51:00.844  3763  4212 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: IncomingSocketThread/Receiver)
08-03 20:51:00.845  3763  4211 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 20:51:00.845  3763  4211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-03 20:51:00.846  3763  4212 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: IncomingSocketThread/Receiver)
08-03 20:51:00.846  3763  4212 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 20:51:00.847  3763  4212 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 20:51:03.829  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
08-03 20:51:03.831  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-03 20:51:03.837  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@50e3420 Bundle[{}]
,08-03 20:51:03.837  3763  3810 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-03 20:51:03.838  3763  3810 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-03 20:51:03.838  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 20:51:03.839  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-03 20:51:03.839  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 20:51:03.840  3763  3810 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-03 20:51:03.844  3763  3810 I System.out: Running OutgoingSocketThread
,08-03 20:51:03.848  3763  4213 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-03 20:51:03.848  3763  4213 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-03 20:51:06.856  3763  4214 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-03 20:51:06.856  3763  4214 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:51:06.857  3763  4213 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-03 20:51:06.857  3763  4214 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:51:06.857  3763  4213 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:51:06.857  3763  4213 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:51:06.858  3763  4214 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:51:06.859  3763  4214 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 20:51:06.860  3763  4213 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:51:06.864  3763  4218 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: IncomingSocketThread/Receiver)
,08-03 20:51:06.865  3763  4218 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: IncomingSocketThread/Receiver)
,08-03 20:51:06.865  3763  4218 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-03 20:51:06.866  3763  4218 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-03 20:51:06.867  3763  4217 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: OutgoingSocketThread/Sender)
08-03 20:51:06.870  3763  4213 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 20:51:06.874  3763  4216 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: IncomingSocketThread/Sender)
,08-03 20:51:06.876  3763  4219 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: OutgoingSocketThread/Receiver)
08-03 20:51:06.877  3763  4219 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: OutgoingSocketThread/Receiver)
08-03 20:51:06.877  3763  4219 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 20:51:06.877  3763  4219 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-03 20:51:07.462   872  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-03 20:51:09.859  3763  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 456)
,08-03 20:51:09.862  3763  3810 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 20:51:09.862  3763  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 457)
,08-03 20:51:09.869  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:51:09.869  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1baa501 added. We now have 2 listener(s)
08-03 20:51:09.871  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:09.871  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:51:09.871  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:09.871  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:09.871  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84bfa6 added. We now have 9 listener(s)
08-03 20:51:09.871  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:09.872  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 20:51:09.875  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:51:09.885  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:51:09.886  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:51:09.887  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:51:09.887  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:51:09.887  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a48d94 added. We now have 3 listener(s)
08-03 20:51:09.889  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:09.889  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:09.889  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 20:51:09.889  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:09.890  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab903d added. We now have 10 listener(s)
,08-03 20:51:09.890  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:09.890  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:51:09.890  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:51:09.890  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 20:51:09.890  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:09.891  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.891  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:51:09.891  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:09.891  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1baa501 removed from the list
08-03 20:51:09.891  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:09.891  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84bfa6 removed from the list
08-03 20:51:09.895  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:51:09.900  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:51:09.900  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:51:09.901  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:09.901  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.901  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:51:09.902  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:09.902  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:09.902  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:09.902  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a84bfa6 not in the list
,08-03 20:51:09.902  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.902  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:09.903  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:09.903  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:09.903  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:51:09.903  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ab903d removed from the list
08-03 20:51:09.903  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:09.904  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.904  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:09.904  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:09.904  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a48d94 removed from the list
08-03 20:51:09.905  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:09.905  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62d3032 added. We now have 2 listener(s)
08-03 20:51:09.907  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:09.907  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:09.907  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:09.907  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:09.907  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e98f183 added. We now have 9 listener(s)
08-03 20:51:09.907  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:09.908  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:51:09.911  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:51:09.921  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:51:09.924  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:51:09.924  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:51:09.925  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:09.927  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:51:09.927  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc5f339 added. We now have 3 listener(s)
08-03 20:51:09.929  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:51:09.929  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:09.929  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:09.929  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:09.930  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:09.930  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77a1d7e added. We now have 10 listener(s)
08-03 20:51:09.930  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:09.930  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:51:09.930  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:51:09.930  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:51:09.930  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:51:09.930  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-03 20:51:09.934  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:51:09.934  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:51:09.938  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:51:09.939  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-03 20:51:09.939  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:51:09.942  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-03 20:51:09.942  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:51:09.942  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:51:09.944  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:51:09.947  4129  4158 D BtGatt.GattService: registerClient() - UUID=253d3a4a-3f25-4b78-9ff8-58f60f19d103
,08-03 20:51:09.948  4129  4145 D BtGatt.GattService: onClientRegistered() - UUID=253d3a4a-3f25-4b78-9ff8-58f60f19d103, clientIf=5
08-03 20:51:09.948  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-03 20:51:09.949  4129  4140 D BtGatt.GattService: start scan with filters
,08-03 20:51:09.953  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:51:09.953  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 20:51:09.953  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-03 20:51:09.953  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-03 20:51:09.954  4129  4148 D BtGatt.ScanManager: handling starting scan
,08-03 20:51:09.957  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:51:09.957  4129  4148 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1bc0b4
08-03 20:51:09.958  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:51:09.958  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 20:51:09.960  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:51:09.966  4129  4145 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 20:51:09.966  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:09.967  4129  4148 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:51:09.972  3763  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-03 20:51:09.972  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:51:09.972  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-03 20:51:09.973  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.973  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:51:09.973  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:51:09.973  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:51:09.974  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:51:09.974  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:51:09.975  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-03 20:51:09.975  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:51:09.976  4129  4145 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 20:51:09.976  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:09.977  4129  4148 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:51:09.977  3763  3810 D BluetoothAdapter: STATE_ON
08-03 20:51:09.977  4129  4148 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 20:51:09.979  4129  4168 D BtGatt.GattService: stopScan() - queue size =1
,08-03 20:51:09.983  4129  4140 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-03 20:51:09.984  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:51:09.984  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:51:09.984  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:51:09.985  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:51:09.985  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-03 20:51:09.988  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:51:09.988  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-03 20:51:09.988  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:51:09.988  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:51:09.989  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:51:09.991  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:51:09.991  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:51:09.992  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:51:09.996  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:51:09.996  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:51:09.996  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:51:09.997  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:09.997  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:51:09.997  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:51:09.997  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:09.997  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62d3032 removed from the list
08-03 20:51:09.997  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:09.997  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e98f183 removed from the list
,08-03 20:51:09.997  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:51:09.997  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:09.998  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.998  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:09.998  4129  4145 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:51:09.998  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:09.999  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:09.999  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:09.999  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:09.999  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e98f183 not in the list
,08-03 20:51:09.999  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:09.999  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.000  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:10.000  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:10.000  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.000  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77a1d7e removed from the list
08-03 20:51:10.000  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:51:10.000  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.001  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.001  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:10.001  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc5f339 removed from the list
08-03 20:51:10.001  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:10.002  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f16938a added. We now have 2 listener(s)
08-03 20:51:10.003  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 20:51:10.003  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:10.004  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:10.004  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:10.004  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d0dfb added. We now have 9 listener(s)
08-03 20:51:10.004  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:10.004  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:51:10.005  4129  4145 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:51:10.005  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.008  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:51:10.013  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:51:10.013  4129  4145 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:51:10.013  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.014  4129  4148 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:51:10.015  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:10.016  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:51:10.016  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:10.017  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5d071 added. We now have 3 listener(s)
08-03 20:51:10.018  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:51:10.021  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:51:10.021  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:10.021  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:10.022  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:10.022  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:10.022  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b525e56 added. We now have 10 listener(s)
08-03 20:51:10.022  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:10.022  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:51:10.023  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:51:10.023  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-03 20:51:10.023  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:51:10.023  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:51:10.024  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:51:10.025  4129  4145 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:51:10.025  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.026  4129  4148 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:51:10.027  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:51:10.027  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:51:10.032  4129  4145 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-03 20:51:10.032  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.033  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:51:10.034  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:51:10.034  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:51:10.042  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 20:51:10.042  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:51:10.042  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:51:10.043  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:51:10.046  4129  4158 D BtGatt.GattService: registerClient() - UUID=29701f43-0425-4d94-9d7c-aa155ec4ed97
08-03 20:51:10.047  4129  4145 D BtGatt.GattService: onClientRegistered() - UUID=29701f43-0425-4d94-9d7c-aa155ec4ed97, clientIf=5
,08-03 20:51:10.047  3763  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 20:51:10.048  4129  4139 D BtGatt.GattService: start scan with filters
,08-03 20:51:10.052  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-03 20:51:10.052  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-03 20:51:10.052  4129  4148 D BtGatt.ScanManager: handling starting scan
,08-03 20:51:10.052  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-03 20:51:10.053  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 20:51:10.056  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:51:10.056  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 20:51:10.057  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:51:10.059  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:51:10.060  4129  4145 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-03 20:51:10.060  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:51:10.060  4129  4148 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-03 20:51:10.066  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 20:51:10.066  3763  3810 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-03 20:51:10.067  4129  4145 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-03 20:51:10.067  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.067  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:51:10.067  4129  4148 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:51:10.067  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:51:10.067  4129  4148 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-03 20:51:10.067  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:51:10.067  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:10.067  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.067  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:51:10.068  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:10.068  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f16938a removed from the list
08-03 20:51:10.068  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.068  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d0dfb removed from the list
08-03 20:51:10.068  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:51:10.068  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:51:10.069  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.070  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 20:51:10.070  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.070  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:51:10.071  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:10.071  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:10.071  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.071  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d0dfb not in the list
08-03 20:51:10.071  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:51:10.072  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:51:10.072  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-03 20:51:10.072  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:51:10.072  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:51:10.073  3763  3810 D BluetoothAdapter: STATE_ON
08-03 20:51:10.074  4129  4139 D BtGatt.GattService: stopScan() - queue size =1
08-03 20:51:10.075  4129  4168 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:51:10.076  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:51:10.076  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:51:10.076  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:51:10.076  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:51:10.077  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:51:10.077  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:51:10.078  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 20:51:10.078  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:51:10.078  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:51:10.078  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.080  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:10.080  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:10.080  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.080  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:51:10.080  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b525e56 removed from the list
08-03 20:51:10.080  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:10.080  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:51:10.080  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.081  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-03 20:51:10.081  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.081  4129  4145 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:51:10.081  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:10.081  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.081  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5d071 removed from the list
08-03 20:51:10.081  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:10.082  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae09e2 added. We now have 2 listener(s)
08-03 20:51:10.083  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:10.084  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:10.084  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:10.084  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:51:10.084  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e94173 added. We now have 9 listener(s)
08-03 20:51:10.084  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:10.084  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:51:10.088  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:51:10.089  4129  4145 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:51:10.089  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:51:10.094  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:51:10.096  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:10.096  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:51:10.097  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:10.097  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ad1ca9 added. We now have 3 listener(s)
08-03 20:51:10.098  4129  4145 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-03 20:51:10.098  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:51:10.098  4129  4148 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:51:10.100  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:51:10.100  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:10.101  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:51:10.101  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:10.101  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:10.101  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26e22e added. We now have 10 listener(s)
08-03 20:51:10.102  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:10.102  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:51:10.102  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:51:10.102  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:51:10.102  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:51:10.102  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:51:10.102  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:51:10.106  3763  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-03 20:51:10.106  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:51:10.107  4129  4145 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:51:10.107  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.107  4129  4148 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-03 20:51:10.111  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:51:10.112  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-03 20:51:10.112  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:51:10.116  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-03 20:51:10.116  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-03 20:51:10.116  3763  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-03 20:51:10.117  3763  3810 D BluetoothAdapter: STATE_ON
,08-03 20:51:10.120  4129  4140 D BtGatt.GattService: registerClient() - UUID=d440aa5e-8407-4706-ba3e-80bd4a9452d4
,08-03 20:51:10.121  4129  4145 D BtGatt.GattService: onClientRegistered() - UUID=d440aa5e-8407-4706-ba3e-80bd4a9452d4, clientIf=5
08-03 20:51:10.121  3763  3773 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-03 20:51:10.121  4129  4145 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-03 20:51:10.121  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.122  4129  4168 D BtGatt.GattService: start scan with filters
08-03 20:51:10.122  4129  4145 D BtGatt.GattService: current time is 416239507359
,08-03 20:51:10.122  4129  4145 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -89, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-03 20:51:10.123  4129  4145 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-03 20:51:10.125  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-03 20:51:10.125  4129  4148 D BtGatt.ScanManager: handling starting scan
08-03 20:51:10.125  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-03 20:51:10.126  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-03 20:51:10.126  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-03 20:51:10.130  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-03 20:51:10.130  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-03 20:51:10.131  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-03 20:51:10.133  4129  4145 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-03 20:51:10.133  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.134  4129  4148 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-03 20:51:10.134  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-03 20:51:10.140  4129  4145 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-03 20:51:10.140  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:51:10.140  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.140  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:51:10.140  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:51:10.140  4129  4148 D BtGatt.ScanManager: Starting BLE batch scan
08-03 20:51:10.140  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:51:10.140  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.140  4129  4148 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-03 20:51:10.140  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-03 20:51:10.141  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:10.141  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dae09e2 removed from the list
,08-03 20:51:10.142  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.142  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e94173 removed from the list
08-03 20:51:10.142  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:51:10.142  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:51:10.143  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.143  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-03 20:51:10.143  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.143  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-03 20:51:10.145  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:10.145  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:10.145  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.145  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e94173 not in the list
08-03 20:51:10.145  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-03 20:51:10.145  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:51:10.145  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:51:10.146  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-03 20:51:10.146  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-03 20:51:10.147  3763  3810 D BluetoothAdapter: STATE_ON
08-03 20:51:10.147  4129  4139 D BtGatt.GattService: stopScan() - queue size =1
08-03 20:51:10.148  4129  4140 D BtGatt.GattService: unregisterClient() - clientIf=5
08-03 20:51:10.148  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-03 20:51:10.148  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-03 20:51:10.148  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-03 20:51:10.148  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-03 20:51:10.149  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-03 20:51:10.150  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:51:10.150  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-03 20:51:10.150  3763  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:51:10.150  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:51:10.151  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.151  4129  4145 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-03 20:51:10.151  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-03 20:51:10.152  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:51:10.152  3763  3763 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-03 20:51:10.152  3763  3763 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:51:10.153  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:51:10.153  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:51:10.153  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.153  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d26e22e removed from the list
08-03 20:51:10.153  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:10.153  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.153  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.153  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 20:51:10.153  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ad1ca9 removed from the list
08-03 20:51:10.154  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:10.154  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142f33a added. We now have 2 listener(s)
08-03 20:51:10.156  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-03 20:51:10.156  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:10.156  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:10.157  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:51:10.157  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8796beb added. We now have 9 listener(s)
08-03 20:51:10.157  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:51:10.157  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:51:10.160  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:51:10.160  4129  4145 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-03 20:51:10.160  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:51:10.164  3763  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:51:10.168  3763  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:51:10.169  3763  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:51:10.169  4129  4145 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-03 20:51:10.169  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.170  4129  4148 D BtGatt.ScanManager: stopping BLe Batch
08-03 20:51:10.170  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:51:10.171  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:51:10.170  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ab7e1 added. We now have 3 listener(s)
08-03 20:51:10.174  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-03 20:51:10.174  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:51:10.174  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:51:10.174  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:51:10.174  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd0906 added. We now have 10 listener(s)
08-03 20:51:10.174  3763  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:51:10.174  3763  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:51:10.174  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:51:10.175  3763  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:51:10.175  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:10.175  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:51:10.175  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:51:10.175  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:10.175  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142f33a removed from the list
08-03 20:51:10.175  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:51:10.175  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8796beb removed from the list
08-03 20:51:10.176  3763  3763 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:51:10.176  3763  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:51:10.176  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.177  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:51:10.177  4129  4145 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-03 20:51:10.177  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.177  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-03 20:51:10.177  4129  4148 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-03 20:51:10.178  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:10.178  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:51:10.178  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:51:10.178  3763  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8796beb not in the list
08-03 20:51:10.179  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.179  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:51:10.180  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:51:10.180  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:51:10.180  3763  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:51:10.180  3763  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dd0906 removed from the list
08-03 20:51:10.180  3763  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:51:10.180  3763  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:51:10.181  3763  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:51:10.181  3763  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:51:10.181  3763  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ab7e1 removed from the list
08-03 20:51:10.182  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-03 20:51:10.182  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 20:51:10.182  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 20:51:10.182  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:51:10.182  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 20:51:10.183  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 20:51:10.183  4129  4145 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-03 20:51:10.183  4129  4145 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-03 20:51:10.190  3763  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: My test thread name)
,08-03 20:51:10.492  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:51:10.581  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:51:10.653  3763  3763 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:51:12.189  3763  3810 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 465
,08-03 20:51:12.190  3763  3810 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 465, name: My test thread name)
,08-03 20:51:12.196  3763  4221 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: My test thread name)
,08-03 20:51:12.197  3763  4221 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 466, thread name: My test thread name)
,08-03 20:51:12.197  3763  4221 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 466, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-03 20:51:12.201  3763  3810 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:51:12.210  3763  4222 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 470, name: My test thread name)
,08-03 20:51:12.212  3763  4222 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 470, thread name: My test thread name): Test exception.
,08-03 20:51:12.213  3763  4222 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 470, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-03 20:51:12.215  3763  3810 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
,08-03 20:51:12.216  3763  3810 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
08-03 20:51:12.216  3763  3810 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-03 20:51:12.216  3763  3810 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-03 20:51:12.217  3763  3810 D com.test.thalitest.ThaliTestRunner: Total duration: 36030 ms
,08-03 20:51:12.222  3763  3810 I jxcore-log: Total number of executed tests:  82
08-03 20:51:12.222  3763  3810 I jxcore-log: 
,08-03 20:51:12.223  3763  3810 I jxcore-log: Number of passed tests:  82
08-03 20:51:12.223  3763  3810 I jxcore-log: 
,08-03 20:51:12.224  3763  3810 I jxcore-log: Number of failed tests:  0
08-03 20:51:12.224  3763  3810 I jxcore-log: 
,08-03 20:51:12.224  3763  3810 I jxcore-log: Number of ignored tests:  0
08-03 20:51:12.224  3763  3810 I jxcore-log: 
08-03 20:51:12.225  3763  3810 I jxcore-log: Total duration:  36030
08-03 20:51:12.225  3763  3810 I jxcore-log: 
,08-03 20:51:12.233  3763  3810 I jxcore-log: Unit Test app is loaded
08-03 20:51:12.233  3763  3810 I jxcore-log: 
,08-03 20:51:12.241  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.241  3763  3810 I jxcore-log: 
,08-03 20:51:12.246  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.246  3763  3810 I jxcore-log: 
,08-03 20:51:12.248  3763  3763 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 20:51:12.248  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.248  3763  3810 I jxcore-log: 
08-03 20:51:12.249  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.249  3763  3810 I jxcore-log: 
,08-03 20:51:12.250  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.250  3763  3810 I jxcore-log: 
,08-03 20:51:12.251  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.251  3763  3810 I jxcore-log: 
,08-03 20:51:12.254  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.254  3763  3810 I jxcore-log: 
,08-03 20:51:12.255  3763  4220 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 465, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
08-03 20:51:12.256  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.256  3763  3810 I jxcore-log: 
,08-03 20:51:12.257  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.257  3763  3810 I jxcore-log: 
08-03 20:51:12.258  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.258  3763  3810 I jxcore-log: 
,08-03 20:51:12.259  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.259  3763  3810 I jxcore-log: 
,08-03 20:51:12.260  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:51:12.260  3763  3810 I jxcore-log: 
,08-03 20:51:12.261  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.261  3763  3810 I jxcore-log: 
08-03 20:51:12.262  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.262  3763  3810 I jxcore-log: 
,08-03 20:51:12.263  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.263  3763  3810 I jxcore-log: 
08-03 20:51:12.263  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.263  3763  3810 I jxcore-log: 
,08-03 20:51:12.264  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.264  3763  3810 I jxcore-log: 
08-03 20:51:12.265  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.265  3763  3810 I jxcore-log: 
,08-03 20:51:12.266  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.266  3763  3810 I jxcore-log: 
08-03 20:51:12.266  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.266  3763  3810 I jxcore-log: 
,08-03 20:51:12.267  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.267  3763  3810 I jxcore-log: 
08-03 20:51:12.268  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.268  3763  3810 I jxcore-log: 
,08-03 20:51:12.269  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.269  3763  3810 I jxcore-log: 
08-03 20:51:12.270  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.270  3763  3810 I jxcore-log: 
08-03 20:51:12.270  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.270  3763  3810 I jxcore-log: 
,08-03 20:51:12.271  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:51:12.271  3763  3810 I jxcore-log: 
08-03 20:51:12.272  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.272  3763  3810 I jxcore-log: 
,08-03 20:51:12.273  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 20:51:12.273  3763  3810 I jxcore-log: 
08-03 20:51:12.274  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.274  3763  3810 I jxcore-log: 
,08-03 20:51:12.275  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.275  3763  3810 I jxcore-log: 
08-03 20:51:12.275  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.275  3763  3810 I jxcore-log: 
08-03 20:51:12.276  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.276  3763  3810 I jxcore-log: 
,08-03 20:51:12.276  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.276  3763  3810 I jxcore-log: 
08-03 20:51:12.277  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:51:12.277  3763  3810 I jxcore-log: 
08-03 20:51:12.277  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:51:12.277  3763  3810 I jxcore-log: 
,08-03 20:51:12.278  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:51:12.278  3763  3810 I jxcore-log: 
08-03 20:51:12.278  3763  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:51:12.278  3763  3810 I jxcore-log: 
,08-03 20:51:12.281  3763  3810 I jxcore-log: My device name is: motorola-Nexus 6
08-03 20:51:12.281  3763  3810 I jxcore-log: 
,08-03 20:51:12.281  3763  3810 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 20:51:12.281  3763  3810 I jxcore-log: 
,08-03 20:51:14.537  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 20:51:14.537  3763  3810 I jxcore-log: 
,08-03 20:51:15.178  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 20:51:15.178  3763  3810 I jxcore-log: 
,08-03 20:51:15.203  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 20:51:15.203  3763  3810 I jxcore-log: 
,08-03 20:51:16.553  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 20:51:16.553  3763  3810 I jxcore-log: 
,08-03 20:51:16.780  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-03 20:51:16.780  3763  3810 I jxcore-log: 
,08-03 20:51:16.786  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-03 20:51:16.786  3763  3810 I jxcore-log: 
,08-03 20:51:16.790  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-03 20:51:16.790  3763  3810 I jxcore-log: 
,08-03 20:51:16.806  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-03 20:51:16.806  3763  3810 I jxcore-log: 
,08-03 20:51:16.811  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-03 20:51:16.811  3763  3810 I jxcore-log: 
,08-03 20:51:17.486  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-03 20:51:17.486  3763  3810 I jxcore-log: 
,08-03 20:51:17.499  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-03 20:51:17.499  3763  3810 I jxcore-log: 
,08-03 20:51:17.510  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-03 20:51:17.510  3763  3810 I jxcore-log: 
,08-03 20:51:17.517  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-03 20:51:17.517  3763  3810 I jxcore-log: 
,08-03 20:51:17.566  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-03 20:51:17.566  3763  3810 I jxcore-log: 
,08-03 20:51:17.622  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-03 20:51:17.622  3763  3810 I jxcore-log: 
,08-03 20:51:17.630  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-03 20:51:17.630  3763  3810 I jxcore-log: 
,08-03 20:51:17.795  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-03 20:51:17.795  3763  3810 I jxcore-log: 
,08-03 20:51:17.822  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-03 20:51:17.822  3763  3810 I jxcore-log: 
,08-03 20:51:17.828  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-03 20:51:17.828  3763  3810 I jxcore-log: 
,08-03 20:51:17.834  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-03 20:51:17.834  3763  3810 I jxcore-log: 
,08-03 20:51:17.843  1653  1769 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-03 20:51:17.844  1653  1769 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-03 20:51:17.854  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-03 20:51:17.854  3763  3810 I jxcore-log: 
,08-03 20:51:17.878  1499  1499 I ConfigService: onCreate
,08-03 20:51:17.943  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-03 20:51:17.943  3763  3810 I jxcore-log: 
,08-03 20:51:17.955  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-03 20:51:17.955  3763  3810 I jxcore-log: 
,08-03 20:51:17.981  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-03 20:51:17.981  3763  3810 I jxcore-log: 
,08-03 20:51:17.993  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-03 20:51:17.993  3763  3810 I jxcore-log: 
,08-03 20:51:18.012  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-03 20:51:18.012  3763  3810 I jxcore-log: 
,08-03 20:51:18.047  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-03 20:51:18.047  3763  3810 I jxcore-log: 
,08-03 20:51:18.247  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-03 20:51:18.247  3763  3810 I jxcore-log: 
,08-03 20:51:18.275  3763  3810 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-03 20:51:18.275  3763  3810 I jxcore-log: 
,08-03 20:51:18.285  3763  3810 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-03 20:51:18.286  3763  3810 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-03 20:51:18.286  3763  3810 I jxcore-log: 
,08-03 20:51:18.332  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:51:18.332  3763  3810 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-03 20:51:18.332  3763  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:51:18.332  3763  3810 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-03 20:51:22.953  1499  1499 I ConfigService: onDestroy
,08-03 20:51:42.007   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=448123, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 20:52:47.732  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:52:47.734  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:52:47.780  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-03 20:52:47.781  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 20:52:47.781  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:52:47.781  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:52:47.803  3455  4230 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 20:52:47.803  3455  4230 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at blb.a(PG:3937)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at czp.a(PG:18188)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:52:47.803  3455  4230 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	... 12 more
08-03 20:52:47.803  3455  4230 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at fal.a(PG:38)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:52:47.803  3455  4230 E HttpOperation: 	... 14 more
,08-03 20:52:47.905  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 20:52:47.905  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 20:52:47.905  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:52:47.905  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:52:47.927  3455  4230 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 20:52:47.927  3455  4230 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at hec.a(PG:42)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at hee.a(PG:102)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at czr.a(PG:65)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at kka.a(PG:108)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at czp.a(PG:19176)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:52:47.927  3455  4230 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	... 15 more
08-03 20:52:47.927  3455  4230 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at fal.a(PG:38)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:52:47.927  3455  4230 E HttpOperation: 	... 17 more
,08-03 20:52:47.928  3455  4230 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 20:52:47.928  3455  4230 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at hec.a(PG:42)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at hee.a(PG:102)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at czr.a(PG:65)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at kka.a(PG:108)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	... 15 more
08-03 20:52:47.928  3455  4230 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at fal.a(PG:38)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 20:52:47.928  3455  4230 E ExperimentLoader: 	... 17 more
,08-03 20:52:48.008   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 513463, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:53:19.403  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:53:19.405  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:53:19.447  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-03 20:53:19.447  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 20:53:19.447  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:53:19.448  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:53:19.473  3455  4235 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 20:53:19.473  3455  4235 E HttpOperation: java.io.IOException: Cannot obtain authentication token
,08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at blb.a(PG:3937)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at czp.a(PG:18188)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:53:19.473  3455  4235 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	... 12 more
08-03 20:53:19.473  3455  4235 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at fal.a(PG:38)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:53:19.473  3455  4235 E HttpOperation: 	... 14 more
,08-03 20:53:19.520  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-03 20:53:19.520  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 20:53:19.520  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:53:19.520  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:53:19.556  3455  4235 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 20:53:19.556  3455  4235 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at hec.a(PG:42)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at hee.a(PG:102)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at czr.a(PG:65)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at kka.a(PG:108)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at czp.a(PG:19176)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:53:19.556  3455  4235 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	... 15 more
08-03 20:53:19.556  3455  4235 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at fal.a(PG:38)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:53:19.556  3455  4235 E HttpOperation: 	... 17 more
08-03 20:53:19.556  3455  4235 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 20:53:19.556  3455  4235 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at hec.a(PG:42)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at hee.a(PG:102)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at czr.a(PG:65)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at kka.a(PG:108)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: ,	at java.lang.Thread.run(Thread.java:818)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	... 15 more
08-03 20:53:19.556  3455  4235 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at fal.a(PG:38)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 20:53:19.556  3455  4235 E ExperimentLoader: 	... 17 more
,08-03 20:53:19.696   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 545178, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:53:49.824  2879  4239 V KeepSync: Connecting to GoogleApiClient
08-03 20:53:49.825   872  1773 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 20:53:49.883  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:53:49.888  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:53:49.918  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
08-03 20:53:49.918  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-03 20:53:49.918  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:53:49.918  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:53:49.938  1840  4240 V BaseAuthAsyncOperation: access token request failed,
08-03 20:53:49.939  2879  4239 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 20:53:49.984  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 20:53:49.984  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 20:53:49.984  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:53:49.984  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:53:49.998  2879  4239 E KeepSync: IOException
08-03 20:53:49.998  2879  4239 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152),
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 20:53:49.998  2879  4239 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:53:49.998  2879  4239 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 20:53:49.998  2879  4239 E KeepSync: 	... 10 more
,08-03 20:53:49.998  2879  4239 W KeepSync: Sync result 2
,08-03 20:53:50.014   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 552301, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:54:20.233  3649  4242 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 20:54:20.255  3649  4243 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 20:54:20.267  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:20.269  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:20.306  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 20:54:20.307  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 20:54:20.307  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:20.307  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:20.341  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:20.344  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:20.381  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 20:54:20.382  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 20:54:20.382  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:20.382  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:20.404  3649  4243 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 20:54:20.406  3649  4242 E BooksSync: Soft error
08-03 20:54:20.406  3649  4242 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:54:20.406  3649  4242 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 20:54:20.406  3649  4242 E BooksSync: Sync error
08-03 20:54:20.406  3649  4242 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:54:20.406  3649  4242 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 20:54:20.406  3649  4242 I BooksSync: Finished books sync
,08-03 20:54:20.419   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 594144, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:54:20.586  2879  4244 V KeepSync: Connecting to GoogleApiClient
,08-03 20:54:20.587   872  1730 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011,
,08-03 20:54:20.643  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:20.645  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:20.665  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 20:54:20.666  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 20:54:20.666  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:20.666  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:20.681  1840  4245 V BaseAuthAsyncOperation: access token request failed
,08-03 20:54:20.682  2879  4244 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 20:54:20.730  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-03 20:54:20.730  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-03 20:54:20.730  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:20.730  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:20.742  2879  4244 E KeepSync: IOException
08-03 20:54:20.742  2879  4244 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 20:54:20.742  2879  4244 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:54:20.742  2879  4244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 20:54:20.742  2879  4244 E KeepSync: 	... 10 more
,08-03 20:54:20.743  2879  4244 W KeepSync: Sync result 2
,08-03 20:54:20.754   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 606361, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:54:22.147   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=608263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 20:54:51.089  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:51.090  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:54:51.113  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 20:54:51.114  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 20:54:51.114  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:51.114  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:51.128  3455  4253 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 20:54:51.128  3455  4253 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at blb.a(PG:3937)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at czp.a(PG:18188)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:54:51.128  3455  4253 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	... 12 more
08-03 20:54:51.128  3455  4253 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at fal.a(PG:38)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:54:51.128  3455  4253 E HttpOperation: 	... 14 more
,08-03 20:54:51.174  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 20:54:51.174  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 20:54:51.174  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:51.174  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:51.200  3455  4253 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 20:54:51.200  3455  4253 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at hec.a(PG:42)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at hee.a(PG:102)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at czr.a(PG:65)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at kka.a(PG:108)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at czp.a(PG:19176)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:54:51.200  3455  4253 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	... 15 more
08-03 20:54:51.200  3455  4253 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at fal.a(PG:38)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:54:51.200  3455  4253 E HttpOperation: 	... 17 more
,08-03 20:54:51.200  3455  4253 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 20:54:51.200  3455  4253 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at hec.a(PG:42)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at hee.a(PG:102)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at czr.a(PG:65)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at kka.a(PG:108)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	... 15 more
08-03 20:54:51.200  3455  4253 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at fal.a(PG:38)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 20:54:51.200  3455  4253 E ExperimentLoader: 	... 17 more
,08-03 20:54:51.334   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 607919, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:54:51.394  3649  4255 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 20:54:51.410  3649  4256 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 20:54:51.435  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 20:54:51.435  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 20:54:51.435  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:51.435  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:51.494  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 20:54:51.494  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 20:54:51.494  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:54:51.494  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:54:51.509  3649  4256 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 20:54:51.510  3649  4255 E BooksSync: Soft error
08-03 20:54:51.510  3649  4255 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:54:51.510  3649  4255 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 20:54:51.510  3649  4255 E BooksSync: Sync error
08-03 20:54:51.510  3649  4255 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:54:51.510  3649  4255 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 20:54:51.510  3649  4255 I BooksSync: Finished books sync
,08-03 20:54:51.522   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 636937, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:55:04.173   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 20:55:21.775  2879  4258 V KeepSync: Connecting to GoogleApiClient
,08-03 20:55:21.775   872  1709 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 20:55:21.828  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:55:21.830  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:55:21.854  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 20:55:21.854  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-03 20:55:21.854  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:55:21.854  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:55:21.883  1840  4259 V BaseAuthAsyncOperation: access token request failed
,08-03 20:55:21.884  2879  4258 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 20:55:21.939  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-03 20:55:21.939  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 20:55:21.939  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:55:21.939  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:55:21.955  2879  4258 E KeepSync: IOException
08-03 20:55:21.955  2879  4258 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 20:55:21.955  2879  4258 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:55:21.955  2879  4258 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 20:55:21.955  2879  4258 E KeepSync: 	... 10 more
,08-03 20:55:21.956  2879  4258 W KeepSync: Sync result 2
,08-03 20:55:21.963   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 667332, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:55:52.416  3649  4261 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 20:55:52.448  3649  4262 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 20:55:52.459  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:55:52.461  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:55:52.488  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 20:55:52.488  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 20:55:52.488  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:55:52.488  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:55:52.512  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:55:52.517  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:55:52.547  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 20:55:52.547  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 20:55:52.548  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:55:52.548  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:55:52.569  3649  4262 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 20:55:52.570  3649  4261 E BooksSync: Soft error
08-03 20:55:52.570  3649  4261 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:55:52.570  3649  4261 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 20:55:52.570  3649  4261 E BooksSync: Sync error
08-03 20:55:52.570  3649  4261 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:55:52.570  3649  4261 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 20:55:52.570  3649  4261 I BooksSync: Finished books sync
,08-03 20:55:52.583   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 698448, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:56:04.721   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=710837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 20:56:46.787   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=752904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 20:56:55.894  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:56:55.899  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:56:55.934  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 20:56:55.934  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 20:56:55.934  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:56:55.934  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:56:55.962  3455  4266 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 20:56:55.962  3455  4266 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at blb.a(PG:3937)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at czp.a(PG:18188)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:56:55.962  3455  4266 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	... 12 more
08-03 20:56:55.962  3455  4266 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at fal.a(PG:38)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:56:55.962  3455  4266 E HttpOperation: 	... 14 more
,08-03 20:56:56.059  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 20:56:56.059  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 20:56:56.059  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:56:56.059  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:56:56.080  3455  4266 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 20:56:56.080  3455  4266 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jdm.a(PG:82)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jcs.o(PG:406)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jcn.a(PG:1379)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jcs.i(PG:143)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at hec.a(PG:42)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at hee.a(PG:102)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at czr.a(PG:65)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at kka.a(PG:108)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at czp.a(PG:19176)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at czp.a(PG:9081)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at czq.run(PG:1686)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:56:56.080  3455  4266 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jdj.a(PG:4091)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jdj.a(PG:1125)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jdm.a(PG:77)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	... 15 more
08-03 20:56:56.080  3455  4266 E HttpOperation: Caused by: faj: BadAuthentication
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at fal.a(PG:38)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	at jdj.a(PG:4089)
08-03 20:56:56.080  3455  4266 E HttpOperation: 	... 17 more
,08-03 20:56:56.081  3455  4266 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 20:56:56.081  3455  4266 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at hec.a(PG:42)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at hee.a(PG:102)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at czr.a(PG:65)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at kka.a(PG:108)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	... 15 more
08-03 20:56:56.081  3455  4266 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at fal.a(PG:38)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 20:56:56.081  3455  4266 E ExperimentLoader: 	... 17 more
,08-03 20:56:56.203   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 761663, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:57:09.934   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=776051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 20:57:26.508  2879  4270 V KeepSync: Connecting to GoogleApiClient
08-03 20:57:26.508   872  1773 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 20:57:26.589  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:57:26.592  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:57:26.626  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 20:57:26.626  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 20:57:26.626  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:57:26.626  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:57:26.645  1840  4271 V BaseAuthAsyncOperation: access token request failed
,08-03 20:57:26.646  2879  4270 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 20:57:26.709  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 20:57:26.709  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 20:57:26.709  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:57:26.709  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:57:26.727  2879  4270 E KeepSync: IOException
08-03 20:57:26.727  2879  4270 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 20:57:26.727  2879  4270 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 20:57:26.727  2879  4270 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 20:57:26.727  2879  4270 E KeepSync: 	... 10 more
,08-03 20:57:26.728  2879  4270 W KeepSync: Sync result 2
,08-03 20:57:26.744   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 789001, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 20:57:51.853   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=817970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 20:57:56.872  3649  4273 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 20:57:56.901  3649  4274 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 20:57:56.911  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:57:56.914  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:57:56.947  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 20:57:56.947  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 20:57:56.948  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 20:57:56.948  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:57:56.981  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:57:56.984  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 20:57:57.025  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 20:57:57.025  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 20:57:57.026  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 20:57:57.026  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 20:57:57.057  3649  4274 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 20:57:57.060  3649  4273 E BooksSync: Soft error
08-03 20:57:57.060  3649  4273 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:57:57.060  3649  4273 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 20:57:57.060  3649  4273 E BooksSync: Sync error
08-03 20:57:57.060  3649  4273 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 20:57:57.060  3649  4273 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 20:57:57.060  3649  4273 I BooksSync: Finished books sync
,08-03 20:57:57.076   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 820305, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:01:05.004  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:01:05.006  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:01:05.042  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:01:05.042  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 21:01:05.043  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:01:05.043  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:01:05.066  3455  4283 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:01:05.066  3455  4283 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:01:05.066  3455  4283 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	... 12 more
08-03 21:01:05.066  3455  4283 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at fal.a(PG:38)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:01:05.066  3455  4283 E HttpOperation: 	... 14 more
,08-03 21:01:05.131  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:01:05.131  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:01:05.131  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:01:05.131  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:01:05.145  3455  4283 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:01:05.145  3455  4283 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at hec.a(PG:42)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at hee.a(PG:102)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at czr.a(PG:65)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at kka.a(PG:108)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:01:05.145  3455  4283 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	... 15 more
08-03 21:01:05.145  3455  4283 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at fal.a(PG:38)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:01:05.145  3455  4283 E HttpOperation: 	... 17 more
,08-03 21:01:05.145  3455  4283 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:01:05.145  3455  4283 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	... 15 more
08-03 21:01:05.145  3455  4283 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:01:05.145  3455  4283 E ExperimentLoader: 	... 17 more
,08-03 21:01:05.288   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1010744, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:01:35.430  2879  4287 V KeepSync: Connecting to GoogleApiClient
,08-03 21:01:35.431   872  1715 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:01:35.486  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:01:35.488  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-03 21:01:35.524  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 21:01:35.525  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 21:01:35.525  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:01:35.525  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:01:35.545  1840  4288 V BaseAuthAsyncOperation: access token request failed
,08-03 21:01:35.547  2879  4287 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:01:35.607  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 21:01:35.607  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:01:35.607  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:01:35.607  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:01:35.637  2879  4287 E KeepSync: IOException
08-03 21:01:35.637  2879  4287 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:01:35.637  2879  4287 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:01:35.637  2879  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:01:35.637  2879  4287 E KeepSync: 	... 10 more
,08-03 21:01:35.637  2879  4287 W KeepSync: Sync result 2
,08-03 21:01:35.657   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1034702, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:02:05.854  3649  4291 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:02:05.912  3649  4292 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:02:05.943  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:02:05.950  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:02:06.042  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:02:06.043  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:02:06.043  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:02:06.044  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:02:06.125  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:02:06.132  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:02:06.184  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-03 21:02:06.185  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:02:06.185  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:02:06.185  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:02:06.224  3649  4292 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:02:06.226  3649  4291 E BooksSync: Soft error
08-03 21:02:06.226  3649  4291 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:02:06.226  3649  4291 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 21:02:06.227  3649  4291 E BooksSync: Sync error,
08-03 21:02:06.227  3649  4291 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:02:06.227  3649  4291 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:02:06.227  3649  4291 I BooksSync: Finished books sync
,08-03 21:02:06.243   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1066402, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:03:35.672  1499  1970 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-03 21:04:32.108   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,08-03 21:06:00.267   872  1375 I ActivityManager: Start proc 4305:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-03 21:06:00.338  4305  4305 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-03 21:06:00.342  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:06:00.352  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:06:00.385  3992  4315 V GoogleAuthProtoRequest: [358] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:06:00.505  4305  4318 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-03 21:06:00.566  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-03 21:06:00.566  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-03 21:06:00.566  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:06:00.566  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:06:00.627  4305  4318 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: [358] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: [358] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:06:00.646  3992  4315 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 21:06:00.681  4305  4318 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-03 21:06:00.754  4305  4305 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-03 21:06:00.930  4305  4305 W InstanceID/Rpc: Found 10011
,08-03 21:06:01.044  4342  4342 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1257046555.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1257046555.dex
,08-03 21:06:01.092  4342  4342 I dex2oat : dex2oat took 48.976ms (threads: 4) arena alloc=244KB java alloc=29KB native alloc=1515KB free=1556KB
,08-03 21:06:01.129   872  1730 I ActivityManager: Killing 3518:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-03 21:06:05.320   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1311437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-03 21:06:20.853   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1326970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-03 21:06:31.100  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:06:31.101  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:06:31.113  3992  4389 V GoogleAuthProtoRequest: [359] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:06:31.152  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-03 21:06:31.152  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-03 21:06:31.153  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:06:31.153  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: [359] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: [359] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:06:31.182  3992  4389 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 21:07:31.364  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:07:31.366  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:07:31.375  3992  4394 V GoogleAuthProtoRequest: [360] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:07:31.396  1499  2455 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-03 21:07:31.396  1499  2455 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-03 21:07:31.396  1499  2455 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:07:31.396  1499  2455 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: [360] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: [360] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:07:31.411  3992  4394 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 21:09:22.567  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:09:22.572  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:09:22.628  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:09:22.628  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-03 21:09:22.628  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:09:22.628  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:09:22.666  3455  4400 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-03 21:09:22.666  3455  4400 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at blb.a(PG:3937)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at czp.a(PG:18188)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:09:22.666  3455  4400 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	... 12 more
08-03 21:09:22.666  3455  4400 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at fal.a(PG:38)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:09:22.666  3455  4400 E HttpOperation: 	... 14 more
,08-03 21:09:22.747  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-03 21:09:22.747  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-03 21:09:22.748  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-03 21:09:22.748  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:09:22.769  3455  4400 E HttpOperation: [getmobileexperiments] Unexpected exception
08-03 21:09:22.769  3455  4400 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jdm.a(PG:82)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jcs.o(PG:406)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jcn.a(PG:1379)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jcs.i(PG:143)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at hec.a(PG:42)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at hee.a(PG:102)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at czr.a(PG:65)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at kka.a(PG:108)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at czp.a(PG:19176)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at czp.a(PG:9081)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at czq.run(PG:1686)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:09:22.769  3455  4400 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jdj.a(PG:4091)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jdj.a(PG:1125)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jdm.a(PG:77)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	... 15 more
08-03 21:09:22.769  3455  4400 E HttpOperation: Caused by: faj: BadAuthentication
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at fal.a(PG:38)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	at jdj.a(PG:4089)
08-03 21:09:22.769  3455  4400 E HttpOperation: 	... 17 more
,08-03 21:09:22.769  3455  4400 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-03 21:09:22.769  3455  4400 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jdm.a(PG:82)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jcs.o(PG:406)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jcn.a(PG:1379)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jcs.i(PG:143)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at hec.a(PG:42)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at hee.a(PG:102)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at czr.a(PG:65)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at kka.a(PG:108)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at czp.a(PG:19176)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at czp.a(PG:9081)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at czq.run(PG:1686)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jdj.a(PG:4091)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jdj.a(PG:1125)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jdm.a(PG:77)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	... 15 more
08-03 21:09:22.769  3455  4400 E ExperimentLoader: Caused by: faj: BadAuthentication
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at fal.a(PG:38)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	at jdj.a(PG:4089)
08-03 21:09:22.769  3455  4400 E ExperimentLoader: 	... 17 more
,08-03 21:09:22.904   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1508253, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:09:53.087  2879  4406 V KeepSync: Connecting to GoogleApiClient
,08-03 21:09:53.088   872  1741 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-03 21:09:53.139  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:09:53.142  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:09:53.173  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-03 21:09:53.173  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-03 21:09:53.173  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:09:53.173  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:09:53.193  1840  4407 V BaseAuthAsyncOperation: access token request failed
,08-03 21:09:53.195  2879  4406 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-03 21:09:53.247  1499  1992 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-03 21:09:53.247  1499  1992 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-03 21:09:53.247  1499  1992 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:09:53.248  1499  1992 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:09:53.266  2879  4406 E KeepSync: IOException
08-03 21:09:53.266  2879  4406 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-03 21:09:53.266  2879  4406 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-03 21:09:53.266  2879  4406 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-03 21:09:53.266  2879  4406 E KeepSync: 	... 10 more
08-03 21:09:53.266  2879  4406 W KeepSync: Sync result 2
,08-03 21:09:53.279   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1525456, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-03 21:10:01.517  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:10:01.519  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:10:01.534  3992  4408 V GoogleAuthProtoRequest: [361] a.<init>: mAccountName set to: thalitester@gmail.com
,08-03 21:10:01.562  1499  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-03 21:10:01.562  1499  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-03 21:10:01.562  1499  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:10:01.562  1499  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: [361] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: [361] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-03 21:10:01.584  3992  4408 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-03 21:10:23.473  3649  4410 I BooksSync: Starting books sync for 61035162, extras: ade
,08-03 21:10:23.504  3649  4411 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-03 21:10:23.514  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:10:23.516  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:10:23.542  1499  3680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:10:23.543  1499  3680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-03 21:10:23.543  1499  3680 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:10:23.543  1499  3680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:10:23.574  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:10:23.578  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-03 21:10:23.607  1499  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-03 21:10:23.608  1499  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-03 21:10:23.608  1499  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-03 21:10:23.608  1499  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-03 21:10:23.628  3649  4411 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-03 21:10:23.629  3649  4410 E BooksSync: Soft error
08-03 21:10:23.629  3649  4410 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:10:23.629  3649  4410 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-03 21:10:23.629  3649  4410 E BooksSync: Sync error
08-03 21:10:23.629  3649  4410 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-03 21:10:23.629  3649  4410 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-03 21:10:23.629  3649  4410 I BooksSync: Finished books sync
,08-03 21:10:23.638   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1558777, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),08-03 21:13:48.073  4418  4418 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 21:13:48.077  4418  4418 D AndroidRuntime: CheckJNI is OFF
08-03 21:13:48.113  4418  4418 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 21:13:48.153  4418  4418 I Radio-JNI: register_android_hardware_Radio DONE
08-03 21:13:48.173  4418  4418 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-03 21:13:48.190   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-03 21:13:48.190   872   885 I ActivityManager: Killing 3763:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-03 21:13:48.281   872  1730 D GraphicsStats: Buffer count: 2
08-03 21:13:48.281   872  1398 I WindowState: WIN DEATH: Window{4deda7c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 21:13:48.286   872  1307 D WifiService: Client connection lost with reason: 4
08-03 21:13:48.306   872   895 W PackageSettings: Skipping PackageSetting{b3dbeb1 com.example.hello/10273} due to missing metadata
08-03 21:13:48.346   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-03 21:13:48.346   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-03 21:13:48.348   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-03 21:13:48.348   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-03 21:13:48.348   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.348   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.348   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.348   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 21:13:48.349   872   885 I ActivityManager:   Force finishing activity ActivityRecord{17fa3a1 u0 com.test.thalitest/.MainActivity t2}
08-03 21:13:48.351   872   895 I art     : Starting a blocking GC Explicit
08-03 21:13:48.368   872  1730 W ActivityManager: Spurious death for ProcessRecord{efdbdb8 0:com.test.thalitest/u0a0}, curProc for 3763: null
08-03 21:13:48.396   872   895 I art     : Explicit concurrent mark sweep GC freed 40288(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 714us total 44.636ms
08-03 21:13:48.445   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-03 21:13:48.448  4418  4418 I art     : System.exit called, status: 0
08-03 21:13:48.448  4418  4418 I AndroidRuntime: VM exiting with result code 0.
08-03 21:13:48.460   872   895 I ActivityManager: Start proc 4429:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-03 21:13:48.461   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-03 21:13:48.481   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-03 21:13:48.485  4129  4129 D BluetoothMapAppObserver: onReceive
08-03 21:13:48.485  4129  4129 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-03 21:13:48.489  1758  2018 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 21:13:48.490   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 21:13:48.503  1653  1653 I Keyboard.Facilitator: resetDictionaries() : en_US
08-03 21:13:48.515  3539  3539 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-03 21:13:48.517  1653  4443 I Keyboard.Facilitator.DecoderInitializer: run()
08-03 21:13:48.546  1718  1718 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-03 21:13:48.556   872  1730 I ActivityManager: Start proc 4445:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-03 21:13:48.560   872  1835 I ActivityManager: Killing 3592:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-03 21:13:48.571  1653  4443 I Decoder : createOrResetDecoder
08-03 21:13:48.586   872  1709 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3763 uid 10000
08-03 21:13:48.587  1653  1653 I Keyboard.Facilitator: onFinishInput()
08-03 21:13:48.598   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 21:13:48.609  1499  1499 I ConfigService: onCreate
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-03 21:13:48.618  1499  4458 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-03 21:13:48.618  1499  4458 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-03 21:13:48.621  4445  4445 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-03 21:13:48.624  1499  4458 W SQLiteOpenHelper: Opened config.db in read-only mode
08-03 21:13:48.625  1733  1820 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-03 21:13:48.627   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-03 21:13:48.628   872   884 E PackageManager: Failed to write settings, restoring backup
08-03 21:13:48.628   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-03 21:13:48.628   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-03 21:13:48.628   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-03 21:13:48.628   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 21:13:48.628   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 21:13:48.628   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.628   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.628   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.632   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-03 21:13:48.632   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 21:13:48.632   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:13:48.632   872   885 E DropBoxManagerService: 	... 13 more
08-03 21:13:48.638   872  1730 I ActivityManager: Start proc 4459:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-03 21:13:48.638  1733  1820 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 21:13:48.638  1733  1820 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1733
08-03 21:13:48.638  1733  1820 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.638  1733  1820 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.640   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:13:48.640   872  4468 E DropBoxManagerService: Can't write: system_app_crash
08-03 21:13:48.640   872  4468 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:13:48.640   872  4468 E DropBoxManagerService: 	... 5 more
08-03 21:13:48.652  1733  1820 I Process : Sending signal. PID: 1733 SIG: 9
08-03 21:13:48.656  1653  4443 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-03 21:13:48.690  1653  4443 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-03 21:13:48.696  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-03 21:13:48.696  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-03 21:13:48.701  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-03 21:13:48.701  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-03 21:13:48.702  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-03 21:13:48.702  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-03 21:13:48.703  1653  4443 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-03 21:13:48.703  1653  4443 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-03 21:13:48.703  1653  4443 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-03 21:13:48.703  1653  4443 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-03 21:13:48.703  1653  4443 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-03 21:13:48.703  1653  4443 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-03 21:13:48.735  4445  4445 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-03 21:13:48.737   872   882 D GraphicsStats: Buffer count: 1
08-03 21:13:48.741   872  1716 I WindowState: WIN DEATH: Window{7f23fea u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-03 21:13:48.747   872   883 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1733) has died
08-03 21:13:48.748   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-03 21:13:48.749   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.762  4445  4475 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.765  4445  4475 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.770   872   885 I ActivityManager: Start proc 4480:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:13:48.778  4445  4488 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-03 21:13:48.784   872  1741 I ActivityManager: Start proc 4492:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-03 21:13:48.793  1840  4479 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-03 21:13:48.794  1840  4479 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-03 21:13:48.816  4492  4492 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:13:48.833  4480  4480 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 21:13:48.833  4480  4480 D AndroidRuntime: Shutting down VM
08-03 21:13:48.837  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-03 21:13:48.838  1499  1499 D AndroidRuntime: Shutting down VM
08-03 21:13:48.839  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
08-03 21:13:48.839  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
08-03 21:13:48.839  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-03 21:13:48.839  1499  1499 E AndroidRuntime: 	... 8 more
08-03 21:13:48.846   872  4508 E DropBoxManagerService: Can't write: system_app_crash
08-03 21:13:48.846   872  4508 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:13:48.846   872  4508 E DropBoxManagerService: 	... 5 more
08-03 21:13:48.849  4480  4480 E AndroidRuntime: FATAL EXCEPTION: main
08-03 21:13:48.849  4480  4480 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4480
08-03 21:13:48.849  4480  4480 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 21:13:48.849  4480  4480 E AndroidRuntime: 	... 10 more
08-03 21:13:48.850  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
08-03 21:13:48.850   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 21:13:48.851  4480  4480 I Process : Sending signal. PID: 4480 SIG: 9
08-03 21:13:48.852   872  4509 E DropBoxManagerService: Can't write: system_app_crash
08-03 21:13:48.852   872  4509 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:13:48.852   872  4509 E DropBoxManagerService: 	... 5 more
08-03 21:13:48.861   872  1715 I ActivityManager: Killing 1827:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-03 21:13:48.896   872  1307 D WifiService: Client connection lost with reason: 4
08-03 21:13:48.906  4445  4475 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.910  4445  4488 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-03 21:13:48.910  4445  4488 E AndroidRuntime: Process: android.process.acore, PID: 4445
08-03 21:13:48.910  4445  4488 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 21:13:48.910  4445  4488 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 21:13:48.911  4445  4475 I Process : Sending signal. PID: 4445 SIG: 9
08-03 21:13:48.914   872  1307 D WifiService: Client connection lost with reason: 4
08-03 21:13:48.916   872  1375 I ActivityManager: Process com.google.process.gapps (pid 1499) has died
08-03 21:13:48.916   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-03 21:13:48.917   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-03 21:13:48.917   872  1375 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-03 21:13:48.919   872  1398 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4480) has died
08-03 21:13:48.920   872  1398 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 21:13:48.924  1840  4479 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-03 21:13:48.924  1840  4479 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-03 21:13:48.926   872  4510 E DropBoxManagerService: Can't write: system_app_crash
08-03 21:13:48.926   872  4510 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 21:13:48.926   872  4510 E DropBoxManagerService: 	... 5 more
08-03 21:13:48.950   872   885 I ActivityManager: Start proc 4511:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
