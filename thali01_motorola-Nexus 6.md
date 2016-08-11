#### Test 797510156960f45_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 07:28:07.084  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:07.096  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 07:28:07.100  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 07:28:07.144  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-11 07:28:07.144  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 07:28:07.144  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:07.144  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 07:28:07.166  1528  1898 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:28:07.166  1528  1898 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:28:07.166  1528  1898 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:28:07.166  1528  1898 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 07:28:07.166  1528  1898 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 07:28:07.166  1528  1898 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 07:28:07.166  1528  1898 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-11 07:28:07.175  2590  2621 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:28:07.175  2590  2621 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 07:28:07.175  2590  2621 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 07:28:07.175  2590  2621 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 07:28:07.175  2590  2621 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 07:28:07.175  2590  2621 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 07:28:07.175  2590  2621 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-11 07:28:07.701  3355  3355 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 07:28:07.705  3355  3355 D AndroidRuntime: CheckJNI is OFF
08-11 07:28:07.740  3355  3355 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 07:28:07.784  3355  3355 I Radio-JNI: register_android_hardware_Radio DONE
08-11 07:28:07.803  3355  3355 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 07:28:07.806   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 07:28:07.843   873   884 I ActivityManager: Start proc 3365:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 07:28:07.857  3355  3355 D AndroidRuntime: Shutting down VM
08-11 07:28:07.989  3365  3365 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 07:28:08.012  3365  3365 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 07:28:08.107  3365  3365 I LibraryLoader: Time to load native libraries: 91 ms (timestamps 2175-2266)
08-11 07:28:08.108  3365  3365 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 07:28:08.137  3365  3365 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b01ee40}
,08-11 07:28:08.137  3365  3365 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 07:28:08.138  3365  3365 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 07:28:08.145  3365  3365 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 07:28:08.147  3365  3365 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 07:28:08.193  3365  3381 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-11 07:28:08.202  3365  3365 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 07:28:08.212  3365  3365 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 07:28:08.213  3365  3365 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 07:28:08.213  3365  3365 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 07:28:08.213  3365  3365 I Adreno  : Build Date                       : 10/20/15
08-11 07:28:08.213  3365  3365 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 07:28:08.213  3365  3365 I Adreno  : Local Branch                     : M14
08-11 07:28:08.213  3365  3365 I Adreno  : Remote Branch                    : 
08-11 07:28:08.213  3365  3365 I Adreno  : Remote Branch                    : 
08-11 07:28:08.213  3365  3365 I Adreno  : Reconstruct Branch               : 
,08-11 07:28:08.309   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ef96f4c:true
,08-11 07:28:08.348  3365  3365 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 07:28:08.365  3365  3365 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 07:28:08.408  3365  3403 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 07:28:08.419  3365  3390 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 07:28:08.467  3365  3403 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 07:28:08.537   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +596ms (total +711ms)
,08-11 07:28:08.541  1643  1643 I Keyboard.Facilitator: onFinishInput()
,08-11 07:28:08.603  3365  3365 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3365
,08-11 07:28:08.731  3365  3365 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 07:28:08.969  3365  3405 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1695614672
,08-11 07:28:08.986  3365  3405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 07:28:08.986  3365  3405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 07:28:08.986  3365  3405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 07:28:08.986  3365  3405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 07:28:08.986  3365  3405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 07:28:08.986  3365  3405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd2ead7 added. We now have 1 listener(s)
,08-11 07:28:08.998  3365  3405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 07:28:09.000  3365  3405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 07:28:09.002  3365  3405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 07:28:09.003  3365  3405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 07:28:09.013  3365  3405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9515e2 added. We now have 1 listener(s)
08-11 07:28:09.014  3365  3405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 07:28:09.018   873  1309 D WifiService: New client listening to asynchronous messages
,08-11 07:28:09.019  3365  3405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 07:28:09.020  3365  3405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 07:28:09.020  3365  3405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 07:28:09.020  3365  3405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-11 07:28:09.020  3365  3405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 07:28:09.023  3365  3405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 07:28:09.024  3365  3405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 07:28:09.028  3365  3405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 07:28:09.028  3365  3405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 07:28:09.028  3365  3405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-11 07:28:09.028  3365  3405 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 07:28:09.029  3365  3405 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 07:28:09.030  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:28:09.074  3365  3365 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 07:28:11.301  3365  3413 W jxcore-log: Initializing JXcore engine
08-11 07:28:11.301  3365  3413 W jxcore-log: JXcore engine is ready
,08-11 07:28:11.336  3413  3413 W Thread-289: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8978 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-11 07:28:11.336  3413  3413 W Thread-289: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13216]" dev="sockfs" ino=13216 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 07:28:11.336  3413  3413 W Thread-289: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 07:28:11.336  3413  3413 W Thread-289: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21477]" dev="sockfs" ino=21477 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 07:28:11.347  3365  3413 W jxcore-log: Starting JXcore engine
,08-11 07:28:11.424  3365  3413 W jxcore-log: Platform android
08-11 07:28:11.424  3365  3413 W jxcore-log: 
08-11 07:28:11.424  3365  3413 W jxcore-log: Process ARCH arm
08-11 07:28:11.424  3365  3413 W jxcore-log: 
,08-11 07:28:11.638  3365  3413 I jxcore-log: JXcore Cordova bridge is ready!
08-11 07:28:11.638  3365  3413 I jxcore-log: 
08-11 07:28:11.638  3365  3413 W jxcore-log: JXcore engine is started
,08-11 07:28:11.650  3365  3405 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 07:28:11.657  3365  3365 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 07:28:27.322  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 07:28:27.322  3365  3413 I jxcore-log: 
,08-11 07:28:27.324  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 07:28:27.324  3365  3413 I jxcore-log: 
,08-11 07:28:27.327  3365  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 07:28:27.327  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 07:28:27.328  3365  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 07:28:27.328  3365  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 07:28:27.330  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 07:28:27.330  3365  3413 I jxcore-log: 
,08-11 07:28:27.332  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 07:28:27.332  3365  3413 I jxcore-log: 
,08-11 07:28:27.672  3365  3413 I jxcore-log: Unit Test app is loaded
08-11 07:28:27.672  3365  3413 I jxcore-log: 
,08-11 07:28:27.678  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 07:28:27.678  3365  3413 I jxcore-log: 
,08-11 07:28:27.683   873  1689 D WifiService: setWifiEnabled: true pid=3365, uid=10000
,08-11 07:28:27.683   873  1689 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 07:28:27.690  3365  3365 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 07:28:27.698   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-11 07:28:27.699  3365  3365 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 07:28:27.699  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 07:28:27.699  3365  3365 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 07:28:27.699  3365  3365 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 07:28:27.722   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-11 07:28:27.722   873   886 I ActivityManager: Start proc 3416:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-11 07:28:27.726   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 07:28:27.726  3365  3413 I jxcore-log: My device name is: motorola-Nexus 6
08-11 07:28:27.726  3365  3413 I jxcore-log: 
08-11 07:28:27.727   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-11 07:28:27.728   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 07:28:27.728   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-11 07:28:27.728   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-11 07:28:27.728   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 07:28:27.728  3365  3413 I jxcore-log: WARN testUtils: myNameCallback not set!
08-11 07:28:27.728  3365  3413 I jxcore-log: 
,08-11 07:28:27.758   873   890 I ActivityManager: Start proc 3428:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 07:28:27.787  3416  3416 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-11 07:28:27.818   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-11 07:28:27.819   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 07:28:27.819   370   871 D CommandListener: Setting iface cfg
08-11 07:28:27.820   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-11 07:28:27.820   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-11 07:28:27.827   873  1308 E native  : do suspend true
08-11 07:28:27.838   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-11 07:28:27.838   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 07:28:27.850  3416  3416 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-11 07:28:27.855  3428  3428 D AdapterServiceConfig: Adding HeadsetService
08-11 07:28:27.855  3428  3428 D AdapterServiceConfig: Adding A2dpService
,08-11 07:28:27.855  3428  3428 D AdapterServiceConfig: Adding HidService
08-11 07:28:27.856  3428  3428 D AdapterServiceConfig: Adding HealthService
08-11 07:28:27.856   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-11 07:28:27.856  3428  3428 D AdapterServiceConfig: Adding PanService
08-11 07:28:27.856  3428  3428 D AdapterServiceConfig: Adding GattService
08-11 07:28:27.856  3428  3428 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 07:28:27.871   873   884 I ActivityManager: Killing 2680:com.google.android.calendar/u0a37 (adj 15): empty #17,
,08-11 07:28:27.885   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65ca875:true
,08-11 07:28:27.885  3428  3428 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 07:28:27.888  3428  3428 I bt_bluedroid: init
,08-11 07:28:27.888  3428  3453 I BluetoothAdapterState: Entering OffState
,08-11 07:28:27.891  3428  3454 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-11 07:28:27.892  3428  3454 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 07:28:27.892  3428  3454 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-11 07:28:27.892  3428  3454 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-11 07:28:27.894  3428  3428 I bt_bluedroid: get_profile_interface socket
08-11 07:28:27.895  3428  3457 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-11 07:28:27.895  3428  3428 I bt_bluedroid: get_profile_interface sdp
08-11 07:28:27.896  3428  3457 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 07:28:27.897  3428  3439 I bt_bluedroid: config_hci_snoop_log
,08-11 07:28:27.898   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-11 07:28:27.901  3428  3453 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 07:28:27.902  3428  3453 D BluetoothAdapterProperties: Setting state to 14
08-11 07:28:27.902  3428  3453 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-11 07:28:27.903  3428  3453 D BluetoothBondStateMachine: make
08-11 07:28:27.904  3428  3458 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 07:28:27.906  3428  3453 I BluetoothAdapterState: Entering PendingCommandState
,08-11 07:28:27.907  3428  3428 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 07:28:27.909  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
08-11 07:28:27.910  3428  3428 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 07:28:27.910  3428  3428 D BtGatt.GattService: Received start request. Starting profile...
08-11 07:28:27.910  3428  3428 D BtGatt.GattService: start()
08-11 07:28:27.910  3428  3428 I bt_bluedroid: get_profile_interface gatt
,08-11 07:28:27.911  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
08-11 07:28:27.911  3428  3428 D BtGatt.AdvertiseManager: advertise manager created
,08-11 07:28:27.917  3428  3428 V BluetoothAdapterState: isTurningOff()=false
08-11 07:28:27.917  3428  3428 V BluetoothAdapterState: isTurningOn()=false
,08-11 07:28:27.917  3428  3428 V BluetoothAdapterState: isBleTurningOn()=true
08-11 07:28:27.917  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
08-11 07:28:27.917  3428  3453 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 07:28:27.917  3428  3453 I bt_bluedroid: enable
08-11 07:28:27.918  3428  3454 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-11 07:28:27.918  3428  3454 I bt_hci  : start_up
,08-11 07:28:27.932  3428  3454 I bt_vendor: alloc value 0xb39ed189
,08-11 07:28:27.932  3428  3454 I bt_vendor: init
08-11 07:28:27.932  3428  3454 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 07:28:27.932  3428  3454 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 07:28:28.039  3428  3454 D bt_hci  : start_up starting async portion
,08-11 07:28:28.040  3428  3461 I bt_hci  : event_finish_startup
08-11 07:28:28.040  3428  3461 I bt_hci_h4: hal_open
08-11 07:28:28.040  3428  3461 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-11 07:28:28.044  3428  3461 I bt_userial_vendor: device fd = 51 open
,08-11 07:28:28.081  3428  3461 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 07:28:28.113  3428  3461 D bt_hwcfg: Chipset BCM4354A2
08-11 07:28:28.113  3428  3461 D bt_hwcfg: Target name = [BCM4354A2]
,08-11 07:28:28.113  3428  3461 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 07:28:28.564  3428  3461 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 07:28:28.565  3428  3461 D bt_hwcfg: Settlement delay -- 100 ms
08-11 07:28:28.565  3428  3461 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 07:28:28.682  3428  3461 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 07:28:28.682  3428  3461 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 07:28:28.714  3428  3461 I bt_hwcfg: vendor lib fwcfg completed
,08-11 07:28:28.714  3428  3461 I bt_vendor: firmware callback
08-11 07:28:28.715  3428  3461 I bt_hci  : firmware_config_callback
,08-11 07:28:28.725  3428  3463 I bt_btu  : btu_task pending for preload complete event
,08-11 07:28:28.725  3428  3463 I bt_btu_task: Bluetooth chip preload is complete
08-11 07:28:28.725  3428  3463 I bt_btu  : btu_task received preload complete event
,08-11 07:28:28.733  3428  3463 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 07:28:28.734  3428  3463 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-11 07:28:28.734  3428  3463 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-11 07:28:28.734  3428  3463 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 07:28:28.734  3428  3463 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-11 07:28:28.735  3428  3463 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 07:28:28.735  3428  3463 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-11 07:28:28.735  3428  3463 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 07:28:28.735  3428  3463 I         : BTE_InitTraceLevels -- TRC_GAP
,08-11 07:28:28.735  3428  3463 I         : BTE_InitTraceLevels -- TRC_PAN
,08-11 07:28:28.736  3428  3463 I         : BTE_InitTraceLevels -- TRC_SDP
,08-11 07:28:28.736  3428  3463 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 07:28:28.736  3428  3463 I         : BTE_InitTraceLevels -- TRC_SMP
,08-11 07:28:28.736  3428  3463 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 07:28:28.736  3428  3463 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 07:28:28.865  3428  3463 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb396ad9d
,08-11 07:28:28.865  3428  3463 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb396ad9d 
,08-11 07:28:28.873  3428  3457 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 07:28:28.874  3428  3457 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 07:28:28.875  3428  3457 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 07:28:28.879  3428  3457 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 07:28:28.884  3428  3457 D BluetoothAdapterProperties: Scan Mode:20
,08-11 07:28:28.885  3428  3457 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-11 07:28:28.886  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:28:28.886  3428  3457 D bt_hci  : do_postload posting postload work item
,08-11 07:28:28.887  3428  3461 I bt_hci  : event_postload
,08-11 07:28:28.887  3428  3461 I bt_vendor: sco_config_cb
,08-11 07:28:28.887  3428  3461 I bt_hci  : sco_config_callback postload finished.
,08-11 07:28:28.891  3428  3461 I bt_vendor: low_power_mode_cb
,08-11 07:28:28.891  3428  3457 D bt_bte_conf: Device ID record 1 : primary
,08-11 07:28:28.891  3428  3457 D bt_bte_conf:   vendorId            = 000f
,08-11 07:28:28.891  3428  3457 D bt_bte_conf:   vendorIdSource      = 0001
08-11 07:28:28.891  3428  3457 D bt_bte_conf:   product             = 1200
08-11 07:28:28.892  3428  3457 D bt_bte_conf:   version             = 1436
,08-11 07:28:28.892  3428  3457 D bt_bte_conf:   clientExecutableURL = 
08-11 07:28:28.892  3428  3457 D bt_bte_conf:   serviceDescription  = 
,08-11 07:28:28.892  3428  3457 D bt_bte_conf:   documentationURL    = 
,08-11 07:28:28.892  3428  3457 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-11 07:28:28.893  3428  3454 D bt_stack_manager: event_start_up_stack finished
,08-11 07:28:28.895  3428  3453 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 07:28:28.895  3428  3453 D BluetoothAdapterProperties: Setting state to 15
08-11 07:28:28.895  3428  3453 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 07:28:28.896  3428  3453 I BluetoothAdapterState: Entering BleOnState
,08-11 07:28:28.901  3428  3453 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-11 07:28:28.901  3428  3453 D BluetoothAdapterProperties: Setting state to 11
08-11 07:28:28.901  3428  3453 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 07:28:28.906  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:28:28.918   873   886 I ActivityManager: Start proc 3470:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-11 07:28:28.920  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
,08-11 07:28:28.921  3428  3428 D HeadsetService: Received start request. Starting profile...
,08-11 07:28:28.923  3428  3428 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 07:28:28.923  3428  3428 D HeadsetStateMachine: make
,08-11 07:28:28.932  3428  3453 I BluetoothAdapterState: Entering PendingCommandState
,08-11 07:28:28.936  3428  3428 D HeadsetStateMachine: max_hf_connections = 1
,08-11 07:28:28.936  3428  3428 I bt_bluedroid: get_profile_interface handsfree
08-11 07:28:28.937  3428  3457 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-11 07:28:28.937  3428  3457 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-11 07:28:28.941  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
,08-11 07:28:28.941   873   873 D BluetoothA2dp: Proxy object connected
08-11 07:28:28.943  3428  3428 D A2dpService: Received start request. Starting profile...
08-11 07:28:28.943  3428  3428 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 07:28:28.943  3428  3428 I bt_bluedroid: get_profile_interface avrcp
,08-11 07:28:28.949  3428  3428 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 07:28:28.949  3428  3428 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 07:28:28.949  3428  3428 D A2dpStateMachine: make
,08-11 07:28:28.951  3428  3428 I bt_bluedroid: get_profile_interface a2dp
,08-11 07:28:28.952  3428  3457 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 07:28:28.953  3428  3428 I BluetoothHidServiceJni: classInitNative: succeeds
08-11 07:28:28.954  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
08-11 07:28:28.955  1346  1346 D BluetoothInputDevice: Proxy object connected
08-11 07:28:28.956  3428  3428 D HidService: Received start request. Starting profile...
08-11 07:28:28.956  3428  3428 I bt_bluedroid: get_profile_interface hidhost
08-11 07:28:28.956  3428  3457 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb394c3e5
,08-11 07:28:28.956  3428  3457 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 07:28:28.956  1346  1346 D HidProfile: Bluetooth service connected
08-11 07:28:28.956  3428  3428 D HidService: setHidService(): set to: null
08-11 07:28:28.957  3428  3428 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 07:28:28.957  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
08-11 07:28:28.958  3428  3428 D HealthService: Received start request. Starting profile...
08-11 07:28:28.959  3428  3482 D A2dpStateMachine: Enter Disconnected: -2
,08-11 07:28:28.961  3428  3428 I bt_bluedroid: get_profile_interface health
08-11 07:28:28.962  3428  3428 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-11 07:28:28.963  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
08-11 07:28:28.964  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 07:28:28.964  1346  1346 D PanProfile: Bluetooth service connected
08-11 07:28:28.964  3428  3428 D PanService: Received start request. Starting profile...
08-11 07:28:28.966  3428  3428 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 07:28:28.967  3428  3428 I bt_bluedroid: get_profile_interface pan
08-11 07:28:28.968  3428  3457 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-11 07:28:28.970  3428  3428 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
,08-11 07:28:28.975  1346  1346 D BluetoothMap: Proxy object connected
08-11 07:28:28.975  1346  1346 D MapProfile: Bluetooth service connected
08-11 07:28:28.975  3428  3428 D BluetoothMapService: Received start request. Starting profile...
,08-11 07:28:28.975  3428  3428 D BluetoothMapService: start()
08-11 07:28:28.975  1346  1346 D BluetoothMap: getConnectedDevices()
08-11 07:28:28.976  1346  1346 D BluetoothMap: Bluetooth is Not enabled
,08-11 07:28:28.977  3428  3428 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-11 07:28:28.978  3428  3428 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-11 07:28:28.978  3428  3428 D BluetoothMapAppObserver: createReceiver()
,08-11 07:28:28.979  3428  3428 D BluetoothMapAppObserver: initObservers()
,08-11 07:28:28.979  3428  3428 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 07:28:28.985  3428  3428 V BluetoothAdapterState: isTurningOff()=false
,08-11 07:28:28.985  3428  3428 V BluetoothAdapterState: isTurningOn()=true
08-11 07:28:28.985  3428  3428 V BluetoothAdapterState: isBleTurningOn()=false
08-11 07:28:28.985  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
08-11 07:28:28.986  3428  3428 V BluetoothAdapterState: isTurningOff()=false
08-11 07:28:28.986  3428  3428 V BluetoothAdapterState: isTurningOn()=true
08-11 07:28:28.986  3428  3428 V BluetoothAdapterState: isBleTurningOn()=false
08-11 07:28:28.986  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
08-11 07:28:28.986  3428  3428 V BluetoothAdapterState: isTurningOff()=false
,08-11 07:28:28.986  3428  3428 V BluetoothAdapterState: isTurningOn()=true
,08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isTurningOff()=false
,08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isTurningOn()=true
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOn()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isTurningOff()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isTurningOn()=true
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOn()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isTurningOff()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isTurningOn()=true
,08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOn()=false
08-11 07:28:28.987  3428  3428 V BluetoothAdapterState: isBleTurningOff()=false
08-11 07:28:28.988  3470  3470 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-11 07:28:28.988  3428  3475 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 07:28:28.988  3428  3453 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 07:28:28.988  3428  3453 D BluetoothAdapterProperties: ScanMode =  20
08-11 07:28:28.988  3428  3453 D BluetoothAdapterProperties: State =  11
,08-11 07:28:28.989  3428  3453 D BluetoothAdapterProperties: Setting state to 12
08-11 07:28:28.989  3428  3453 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 07:28:28.989   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 07:28:28.989  3428  3453 I BluetoothAdapterState: Entering OnState
08-11 07:28:28.990  3428  3457 D BluetoothAdapterProperties: Scan Mode:21
08-11 07:28:28.990  3428  3457 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 07:28:28.990  1346  1367 D BluetoothPan: onBluetoothStateChange on: true
08-11 07:28:28.990   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 07:28:28.990  1346  1362 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 07:28:28.991  1346  1714 D BluetoothMap: onBluetoothStateChange: up=true
,08-11 07:28:28.992  3365  3365 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-11 07:28:28.992  1346  1367 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 07:28:28.992   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 07:28:28.992   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 07:28:28.992  1745  1894 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 07:28:28.995  3365  3365 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-11 07:28:28.995   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 07:28:28.996  3428  3428 D BluetoothMapService: onReceive
08-11 07:28:28.996  3428  3428 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 07:28:28.996  3428  3428 D BluetoothMapService: STATE_ON
08-11 07:28:28.998  3365  3365 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 07:28:29.001  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 07:28:29.002  3365  3365 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 07:28:29.003  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 07:28:29.004  3428  3428 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 07:28:29.004  3428  3428 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-11 07:28:29.005  3428  3428 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 07:28:29.007  3428  3428 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 07:28:29.008  3428  3428 D ObexServerSockets: Succeed to create listening sockets 
08-11 07:28:29.008  3428  3428 D ObexServerSockets0: startAccept()
08-11 07:28:29.008  3428  3428 D ObexServerSockets0: prepareForNewConnect()
08-11 07:28:29.010  3428  3428 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-11 07:28:29.010  3428  3428 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-11 07:28:29.011  3428  3491 D ObexServerSockets0: Accepting socket connection...
08-11 07:28:29.011  3428  3492 D ObexServerSockets0: Accepting socket connection...
08-11 07:28:29.014  1346  1614 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 07:28:29.014   873  1375 I ActivityManager: Killing 2823:com.google.android.gm/u0a78 (adj 15): empty #17
08-11 07:28:29.018  3428  3428 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 07:28:29.018  3428  3428 D ObexServerSockets0: prepareForNewConnect()
,08-11 07:28:29.050  1346  1346 D BluetoothA2dp: Proxy object connected
,08-11 07:28:29.050  1346  1614 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-11 07:28:29.054  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 07:28:29.077   873  1375 I ActivityManager: Start proc 3493:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-11 07:28:29.090   873   890 D BluetoothHeadset: Proxy object connected
,08-11 07:28:29.091   873   890 D BluetoothHeadset: Proxy object connected
,08-11 07:28:29.091   873   890 D BluetoothHeadset: Proxy object connected
08-11 07:28:29.093  1745  1755 D BluetoothHeadset: Proxy object connected
,08-11 07:28:29.113  3493  3493 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-11 07:28:29.154  1346  1367 D BluetoothHeadset: Proxy object connected
,08-11 07:28:29.154  1346  1346 D HeadsetProfile: Bluetooth service connected,
,08-11 07:28:29.166   873  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-11 07:28:29.167   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,08-11 07:28:29.167   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 07:28:29.172   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 07:28:29.214   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 07:28:29.215  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 07:28:29.300  3493  3493 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 07:28:29.300  3493  3493 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.300  3493  3493 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.300  3493  3493 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.300  3493  3493 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.k.d(PG:583)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.300  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.301  3493  3493 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.301  3493  3493 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.301  3493  3493 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:28:29.301  3493  3493 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:28:29.308  3470  3470 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 07:28:29.314   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@843f31a:true
08-11 07:28:29.318  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 07:28:29.331  3470  3470 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-11 07:28:29.333  1346  1346 D BluetoothPbap: Proxy object connected
08-11 07:28:29.334  1346  1346 D PbapServerProfile: Bluetooth service connected
08-11 07:28:29.335  3470  3470 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-11 07:28:29.345  3470  3470 D LocalBluetoothProfileManager: Adding local MAP profile
08-11 07:28:29.346  3470  3470 D BluetoothMap: Create BluetoothMap proxy object
08-11 07:28:29.350  3470  3470 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-11 07:28:29.359  3428  3523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 07:28:29.365  3470  3470 D DockEventReceiver: finishStartingService: stopping service
08-11 07:28:29.366  3470  3470 D BluetoothA2dp: Proxy object connected
,08-11 07:28:29.368  3470  3470 D BluetoothInputDevice: Proxy object connected
,08-11 07:28:29.368  3470  3470 D HidProfile: Bluetooth service connected
08-11 07:28:29.370  3470  3470 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 07:28:29.370  3470  3470 D PanProfile: Bluetooth service connected
08-11 07:28:29.370  3470  3470 D BluetoothMap: Proxy object connected
08-11 07:28:29.371  3470  3470 D MapProfile: Bluetooth service connected
,08-11 07:28:29.371  3470  3470 D BluetoothMap: getConnectedDevices()
08-11 07:28:29.377  3470  3470 D BluetoothPbap: Proxy object connected
08-11 07:28:29.377  3470  3470 D PbapServerProfile: Bluetooth service connected
08-11 07:28:29.378   873  1637 I ActivityManager: Killing 3020:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-11 07:28:29.385  3428  3528 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 07:28:29.413  3428  3528 I BtOppRfcommListener: Accept thread started.
,08-11 07:28:29.437  3470  3485 D BluetoothHeadset: Proxy object connected
,08-11 07:28:29.438  3470  3470 D HeadsetProfile: Bluetooth service connected
,08-11 07:28:29.475  3493  3513 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-11 07:28:29.504   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ebf7207:true
,08-11 07:28:29.667  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 07:28:29.706  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 07:28:29.706  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 07:28:29.712   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 07:28:29.726   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 07:28:29.726   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-11 07:28:29.727   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 07:28:29.757   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 07:28:29.769   370   871 D CommandListener: Setting iface cfg
,08-11 07:28:29.775   873  1308 D WifiStateMachine: Start Dhcp Watchdog 1
,08-11 07:28:29.782   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 07:28:29.801   873  3534 D DhcpClient: Receive thread started
,08-11 07:28:29.886   873  1308 E native  : do suspend false
,08-11 07:28:29.905   873  3533 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 07:28:29.919   873  3534 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 169470, domain null
,08-11 07:28:29.921   873  3533 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 169470 seconds
08-11 07:28:29.924   873  3533 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 07:28:29.937   873  3534 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 07:28:29.938   873  3533 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 07:28:29.942   370   871 D CommandListener: Setting iface cfg
,08-11 07:28:29.950   873  3533 D DhcpClient: Scheduling renewal in 86399s
,08-11 07:28:29.951   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 07:28:29.954   873  1308 E native  : do suspend true
,08-11 07:28:29.971   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-11 07:28:29.974   873  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-11 07:28:29.975   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-11 07:28:29.982   873  1310 D ConnectivityService: Adding iface wlan0 to network 100
,08-11 07:28:29.990   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 07:28:30.020   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 07:28:30.020   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-11 07:28:30.022   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-11 07:28:30.023   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-11 07:28:30.025   873  1310 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-11 07:28:30.034   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-11 07:28:30.039   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-11 07:28:30.039   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-11 07:28:30.040   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-11 07:28:30.040   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-11 07:28:30.040   873  1310 D ConnectivityService:    accepting network in place of null
,08-11 07:28:30.041   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 07:28:30.041   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 07:28:30.048   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=354205, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:28:30.075   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 07:28:30.100   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 07:28:30.102   873  1310 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-11 07:28:30.114   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-11 07:28:30.115   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 07:28:30.124   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 07:28:30.126   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-11 07:28:30.130   873  3531 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.88,2a00:1450:400d:803::200e
,08-11 07:28:30.134   873  1676 V BackupManagerService: Scheduling immediate backup pass
08-11 07:28:30.135   873   873 V BackupManagerService: Running a backup pass
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:28:30.136  3365  3365 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 07:28:30.138   873  1327 V BackupManagerService: clearing pending backups
,08-11 07:28:30.139  3365  3365 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 07:28:30.145  1992  1992 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 07:28:30.149  1992  1992 D SystemUpdateService: onCreate
,08-11 07:28:30.153  1992  1992 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 07:28:30.161  1992  3546 I SystemUpdateService: active receiver: enabled
,08-11 07:28:30.162   873  1327 V PerformBackupTask: Beginning backup of 16 targets
08-11 07:28:30.162   873  3531 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 05:28:30 GMT], X-Android-Received-Millis=[1470893310161], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470893310157]}
,08-11 07:28:30.179  1992  3546 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 07:28:30.182   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 07:28:30.182   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-11 07:28:30.182   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-11 07:28:30.183   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-11 07:28:30.192   873  1327 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-11 07:28:30.192  1992  3546 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 07:28:30.192  1992  3546 I SystemUpdateService: now status is 0 (complete)
08-11 07:28:30.192  1992  3546 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 07:28:30.193  1992  3546 I SystemUpdateService: file has been verified
08-11 07:28:30.193  1992  3546 I SystemUpdateService: OTA package size = 12249756
,08-11 07:28:30.211   873  1327 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-11 07:28:30.220  1992  3546 I SystemUpdateService: showing system update notification
,08-11 07:28:30.229   873   884 I ActivityManager: Start proc 3560:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-11 07:28:30.242  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:30.244  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:30.262  3560  3560 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-11 07:28:30.283  1992  1992 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-11 07:28:30.287  1992  1992 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-11 07:28:30.295  1528  1886 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
08-11 07:28:30.295  1528  1886 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud.
08-11 07:28:30.295  1528  1886 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:30.295  1528  1886 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:30.299  1992  1992 D SystemUpdateService: onDestroy
,08-11 07:28:30.307  1992  3575 I MDM     : [192] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-11 07:28:30.308  1992  3575 W BaseAppContext: Using Auth Proxy for data requests.
08-11 07:28:30.308  1992  3558 I GcmGroups: Failed to subscribe to group.
08-11 07:28:30.308  1992  3558 I GcmGroups: com.google.android.gms.auth.ae: BadAuthentication
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.auth.p.b(SourceFile:480)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:397)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.auth.p.a(SourceFile:350)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:444)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:334)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:241)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:48)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:28:30.308  1992  3558 I GcmGroups: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 07:28:30.311  1992  1992 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 07:28:30.313  1992  3558 I GcmGroups: Groups upload failed, retrying in 24000:00:00
,08-11 07:28:30.314  1992  1992 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-11 07:28:30.318  1992  3576 I iu.SyncManager: SYNC; picasa accounts
,08-11 07:28:30.326   873  1689 I ActivityManager: Start proc 3582:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
08-11 07:28:30.330  1992  3575 V GoogleAuthProtoRequest: [192] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 07:28:30.340  1992  3576 I iu.UploadsManager: num queued entries: 0
,08-11 07:28:30.350  3560  3577 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 07:28:30.353  1992  3576 I iu.UploadsManager: num updated entries: 0
08-11 07:28:30.353  1992  3576 I iu.SyncManager: NEXT; no task
,08-11 07:28:30.381  1992  3566 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-11 07:28:30.399  3416  3556 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 07:28:30.407  3560  3577 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 07:28:30.416  3582  3582 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-11 07:28:30.424  3582  3582 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 07:28:30.433  3560  3577 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 07:28:30.434   873  1327 I BackupRestoreController: Getting widget state for user: 0
,08-11 07:28:30.435  3582  3582 D SprintDMHelper: simOperator: 
,08-11 07:28:30.435  3582  3582 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 07:28:30.439   873  3605 D GpsLocationProvider: NTP server returned: 1470893310167 (Thu Aug 11 07:28:30 GMT+02:00 2016) reference: 354333 certainty: 6 system time offset: -272
,08-11 07:28:30.439   873  3605 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
08-11 07:28:30.448   873   884 I ActivityManager: Start proc 3608:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-11 07:28:30.528  3560  3560 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-11 07:28:30.551  1959  1969 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-11 07:28:30.553  1959  1969 V GmsBackupTransport: starting performBackup for @pm@
,08-11 07:28:30.558  1959  1969 V GmsBackupTransport: performBackup done for @pm@
,08-11 07:28:30.564  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:30.582  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-11 07:28:30.582  3365  3413 I jxcore-log: 
,08-11 07:28:30.598  1528  1886 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-11 07:28:30.598  1528  1886 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-11 07:28:30.598  1528  1886 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:30.598  1528  1886 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:30.604  1528  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 07:28:30.605  1528  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 07:28:30.605  1528  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:28:30.610  1528  1886 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:28:30.610  1528  1886 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:28:30.610  1528  1886 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:28:30.610  1528  1886 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 07:28:30.610  1528  1886 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 07:28:30.610  1528  1886 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 07:28:30.610  1528  1886 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 07:28:30.610  1528  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 07:28:30.612  1528  2667 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-11 07:28:30.612  1528  2667 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-11 07:28:30.612  1528  2667 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:30.612  1528  2667 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:30.614  1959  1970 W GmsBackupTransport: Error sending final backup to server: 
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 07:28:30.614  1959  1970 W GmsBackupTransport: 	... 1 more
,08-11 07:28:30.615  1959  2115 I GmsBackupTransport: Next backup will happen in 43199997 millis.
08-11 07:28:30.616   873  1327 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-11 07:28:30.668  1992  1992 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-11 07:28:30.683  1992  3575 E MDM     : [192] SitrepService.a: Error sending sitrep.
,08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 07:28:30.692  3416  3556 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 07:28:30.702   873  1637 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1992 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 07:28:30.767  3560  3560 W InstanceID/Rpc: Found 10011
,08-11 07:28:30.785  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:30.791   873  1327 I BackupManagerService: Backup pass finished.
,08-11 07:28:30.826   873  1637 I ActivityManager: Start proc 3673:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-11 07:28:30.887  3673  3673 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-11 07:28:30.896  2342  3672 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 07:28:30.897  3644  3644 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-695164378.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-695164378.dex
,08-11 07:28:30.914   873   885 I ActivityManager: Start proc 3690:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-11 07:28:30.929  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:28:30.929  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:28:30.929  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:30.930  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 07:28:30.930   873   884 I ActivityManager: Killing 2473:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-11 07:28:30.932  3690  3690 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-11 07:28:30.988  3138  3606 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:28:30.988  3138  3606 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:28:30.988  3138  3606 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	... 12 more
08-11 07:28:30.988  3138  3606 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at fal.a(PG:38)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:28:30.988  3138  3606 E HttpOperation: 	... 14 more
,08-11 07:28:30.988  3644  3644 I dex2oat : dex2oat took 96.288ms (threads: 4) arena alloc=280KB java alloc=33KB native alloc=1513KB free=1558KB
,08-11 07:28:31.048  1992  3603 W DriveInitializer: Awaiting to be initialized
,08-11 07:28:31.057  1992  3712 W DriveInitializer: Background init thread started
,08-11 07:28:31.092  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:28:31.092  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 07:28:31.092  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:28:31.093  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:31.106  3138  3606 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:28:31.106  3138  3606 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at hec.a(PG:42)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at hee.a(PG:102)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at czr.a(PG:65)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at kka.a(PG:108)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:28:31.106  3138  3606 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	... 15 more
08-11 07:28:31.106  3138  3606 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at fal.a(PG:38)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:28:31.106  3138  3606 E HttpOperation: 	... 17 more
,08-11 07:28:31.107  3138  3606 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:28:31.107  3138  3606 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	... 15 more
08-11 07:28:31.107  3138  3606 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:28:31.107  3138  3606 E ExperimentLoader: 	... 17 more
,08-11 07:28:31.157  1992  3712 W DriveInitializer: Background init thread ended
,08-11 07:28:31.169  3690  3690 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-11 07:28:31.175  3690  3690 I BooksApp: Created application version: 3.6.9 (30609)
,08-11 07:28:31.239   873  1393 I ActivityManager: Killing 2744:android.process.acore/u0a5 (adj 15): empty #17
,08-11 07:28:31.239   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 23465, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:28:31.355  3673  3673 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-11 07:28:31.355  3673  3673 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 07:28:31.355  3673  3673 I GAv4    :   adb logcat -s GAv4
,08-11 07:28:31.378  3673  3673 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 07:28:31.387  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-11 07:28:31.387  3365  3413 I jxcore-log: 
,08-11 07:28:31.395  3673  3673 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 07:28:31.412  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-11 07:28:31.412  3365  3413 I jxcore-log: 
,08-11 07:28:31.420  3690  3730 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 07:28:31.424  3673  3739 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 07:28:31.495  2875  3737 V KeepSync: Connecting to GoogleApiClient
,08-11 07:28:31.496   873  1375 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 07:28:31.574  3673  3673 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-11 07:28:31.611  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 07:28:31.611  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 07:28:31.611  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:31.611  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:31.619  3673  3673 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 07:28:31.627  3673  3673 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5782-5786)
,08-11 07:28:31.627  3673  3673 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 07:28:31.641  1992  3755 V BaseAuthAsyncOperation: access token request failed
,08-11 07:28:31.644  2875  3737 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 07:28:31.644  3673  3673 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {472bb92}
,08-11 07:28:31.645  3673  3673 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 07:28:31.646  3673  3673 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 07:28:31.656  3673  3673 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 07:28:31.657  3673  3673 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 07:28:31.685  3673  3673 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 07:28:31.706  3673  3673 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 07:28:31.706  3673  3673 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 07:28:31.706  3673  3673 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 07:28:31.706  3673  3673 I Adreno  : Build Date                       : 10/20/15
08-11 07:28:31.706  3673  3673 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 07:28:31.706  3673  3673 I Adreno  : Local Branch                     : M14
08-11 07:28:31.706  3673  3673 I Adreno  : Remote Branch                    : 
08-11 07:28:31.706  3673  3673 I Adreno  : Remote Branch                    : 
08-11 07:28:31.706  3673  3673 I Adreno  : Reconstruct Branch               : 
,08-11 07:28:31.789  3673  3772 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-11 07:28:31.805  3673  3673 I NSApplication: Starting up...
,08-11 07:28:31.854   873  1684 I ActivityManager: Start proc 3777:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-11 07:28:31.912  3777  3777 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-11 07:28:31.924  3690  3791 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 07:28:31.992  1528  2665 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:28:31.992  1528  2665 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:28:31.992  1528  2665 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:31.992  1528  2665 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:32.030  1528  2667 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:28:32.030  1528  2667 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:28:32.030  1528  2667 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:32.030  1528  2667 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:32.049  3690  3791 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 07:28:32.054  3690  3730 E BooksSync: Soft error
08-11 07:28:32.054  3690  3730 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:28:32.054  3690  3730 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:28:32.054  3690  3730 E BooksSync: Sync error
08-11 07:28:32.054  3690  3730 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:28:32.054  3690  3730 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:28:32.055  3690  3730 I BooksSync: Finished books sync
08-11 07:28:32.057   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23474, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-11 07:28:32.060   873   884 I ActivityManager: Killing 3221:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-11 07:28:32.283  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 07:28:32.283  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 07:28:32.284  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:32.284  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:32.311  2875  3737 E KeepSync: IOException
08-11 07:28:32.311  2875  3737 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 07:28:32.311  2875  3737 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:28:32.311  2875  3737 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 07:28:32.311  2875  3737 E KeepSync: 	... 10 more
,08-11 07:28:32.311  2875  3737 W KeepSync: Sync result 2
,08-11 07:28:32.338   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23474, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-11 07:28:32.338   873  1393 I ActivityManager: Killing 3235:com.android.musicfx/u0a18 (adj 15): empty #17
,08-11 07:28:32.409   873  1393 I ActivityManager: Killing 3051:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-11 07:28:32.484  1528  2314 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,08-11 07:28:32.618  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-11 07:28:32.618  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
08-11 07:28:32.618  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:32.618  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:32.639  2342  3801 E Babel   : UserRecoverableAuthException.
,08-11 07:28:32.640  2342  3801 E Babel   : efr: BadAuthentication
08-11 07:28:32.640  2342  3801 E Babel   : 	at efp.a(Unknown Source)
08-11 07:28:32.640  2342  3801 E Babel   : 	at efp.a(Unknown Source)
08-11 07:28:32.640  2342  3801 E Babel   : 	at efp.a(Unknown Source)
08-11 07:28:32.640  2342  3801 E Babel   : 	at g.a(Unknown Source)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbh.a(SourceFile:3092)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbh.a(SourceFile:1136)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cyr.a(SourceFile:4333)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cyr.a(SourceFile:1419)
08-11 07:28:32.640  2342  3801 E Babel   : 	at ctk.a(SourceFile:492)
08-11 07:28:32.640  2342  3801 E Babel   : 	at ctk.a(SourceFile:1468)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cst.a(SourceFile:4416)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbv.b(SourceFile:106)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbs.d(SourceFile:335)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbt.run(SourceFile:81)
08-11 07:28:32.640  2342  3801 E Babel   : Error getting auth token
,08-11 07:28:32.640  2342  3801 E Babel   : dxq
08-11 07:28:32.640  2342  3801 E Babel   : 	at g.a(Unknown Source)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbh.a(SourceFile:3092)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbh.a(SourceFile:1136)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cyr.a(SourceFile:4333)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cyr.a(SourceFile:1419)
08-11 07:28:32.640  2342  3801 E Babel   : 	at ctk.a(SourceFile:492)
08-11 07:28:32.640  2342  3801 E Babel   : 	at ctk.a(SourceFile:1468)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cst.a(SourceFile:4416)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbv.b(SourceFile:106)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbs.d(SourceFile:335)
08-11 07:28:32.640  2342  3801 E Babel   : 	at cbt.run(SourceFile:81)
,08-11 07:28:32.648  2342  3801 E Babel   : Account registration failed 1-Redacted-21
,08-11 07:28:32.648  2342  3801 E Babel   : dao: null -- null
08-11 07:28:32.648  2342  3801 E Babel   : 	at cbh.a(SourceFile:3124)
08-11 07:28:32.648  2342  3801 E Babel   : 	at cbh.a(SourceFile:1136)
08-11 07:28:32.648  2342  3801 E Babel   : 	at cyr.a(SourceFile:4333)
08-11 07:28:32.648  2342  3801 E Babel   : 	at cyr.a(SourceFile:1419)
08-11 07:28:32.648  2342  3801 E Babel   : 	at ctk.a(SourceFile:492)
08-11 07:28:32.648  2342  3801 E Babel   : 	at ctk.a(SourceFile:1468),
08-11 07:28:32.648  2342  3801 E Babel   : 	at cst.a(SourceFile:4416)
08-11 07:28:32.648  2342  3801 E Babel   : 	at cbv.b(SourceFile:106)
08-11 07:28:32.648  2342  3801 E Babel   : 	at cbs.d(SourceFile:335)
08-11 07:28:32.648  2342  3801 E Babel   : 	at cbt.run(SourceFile:81)
,08-11 07:28:32.658  2342  3801 I art     : Note: end time exceeds epoch: 
,08-11 07:28:32.705  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-11 07:28:32.705  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
,08-11 07:28:32.706  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:32.706  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:32.735  2342  3814 E Babel   : Unexpected exception while authenticating.
,08-11 07:28:32.736  2342  3814 E Babel   : efs: User intervention required. Notification has been pushed.
08-11 07:28:32.736  2342  3814 E Babel   : 	at efp.b(Unknown Source)
08-11 07:28:32.736  2342  3814 E Babel   : 	at efp.b(Unknown Source)
08-11 07:28:32.736  2342  3814 E Babel   : 	at g.a(Unknown Source)
08-11 07:28:32.736  2342  3814 E Babel   : 	at cbh.b(SourceFile:1151)
08-11 07:28:32.736  2342  3814 E Babel   : 	at def.run(SourceFile:5617)
08-11 07:28:32.736  2342  3814 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:28:32.736  2342  3814 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:28:32.736  2342  3814 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,08-11 07:28:33.006  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-11 07:28:33.006  3365  3413 I jxcore-log: 
,08-11 07:28:33.238  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-11 07:28:33.238  3365  3413 I jxcore-log: 
,08-11 07:28:33.244  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-11 07:28:33.244  3365  3413 I jxcore-log: 
,08-11 07:28:33.249  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-11 07:28:33.249  3365  3413 I jxcore-log: 
,08-11 07:28:33.266  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-11 07:28:33.266  3365  3413 I jxcore-log: 
,08-11 07:28:33.271  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-11 07:28:33.271  3365  3413 I jxcore-log: 
,08-11 07:28:33.956  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-11 07:28:33.956  3365  3413 I jxcore-log: 
,08-11 07:28:33.968  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-11 07:28:33.968  3365  3413 I jxcore-log: 
,08-11 07:28:33.977  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-11 07:28:33.977  3365  3413 I jxcore-log: 
,08-11 07:28:33.984  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-11 07:28:33.984  3365  3413 I jxcore-log: 
,08-11 07:28:34.041  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
08-11 07:28:34.041  3365  3413 I jxcore-log: 
,08-11 07:28:34.097  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-11 07:28:34.097  3365  3413 I jxcore-log: 
,08-11 07:28:34.105  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-11 07:28:34.105  3365  3413 I jxcore-log: 
,08-11 07:28:34.280  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-11 07:28:34.280  3365  3413 I jxcore-log: 
,08-11 07:28:34.306  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-11 07:28:34.306  3365  3413 I jxcore-log: 
,08-11 07:28:34.311  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-11 07:28:34.311  3365  3413 I jxcore-log: 
,08-11 07:28:34.317  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-11 07:28:34.317  3365  3413 I jxcore-log: 
,08-11 07:28:34.336  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-11 07:28:34.336  3365  3413 I jxcore-log: 
,08-11 07:28:34.420  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-11 07:28:34.420  3365  3413 I jxcore-log: 
,08-11 07:28:34.432  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-11 07:28:34.432  3365  3413 I jxcore-log: 
,08-11 07:28:34.460  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-11 07:28:34.460  3365  3413 I jxcore-log: 
,08-11 07:28:34.473  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-11 07:28:34.473  3365  3413 I jxcore-log: 
,08-11 07:28:34.492  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-11 07:28:34.492  3365  3413 I jxcore-log: 
,08-11 07:28:34.528  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-11 07:28:34.528  3365  3413 I jxcore-log: 
,08-11 07:28:34.535  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-11 07:28:34.535  3365  3413 I jxcore-log: 
,08-11 07:28:34.752  3365  3413 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-11 07:28:34.752  3365  3413 I jxcore-log: 
,08-11 07:28:34.762  3365  3413 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-11 07:28:34.763  3365  3413 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-11 07:28:34.763  3365  3413 I jxcore-log: 
,08-11 07:28:34.813  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
,08-11 07:28:34.813  3365  3413 I jxcore-log: 
08-11 07:28:34.815  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 07:28:34.815  3365  3413 I jxcore-log: 
,08-11 07:28:34.815  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:28:34.815  3365  3413 I jxcore-log: 
,08-11 07:28:35.680  3365  3413 I jxcore-log: TAP version 13
08-11 07:28:35.680  3365  3413 I jxcore-log: 
,08-11 07:28:35.685  3365  3413 I jxcore-log: # setup
08-11 07:28:35.685  3365  3413 I jxcore-log: 
,08-11 07:28:36.205  3690  3728 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 07:28:36.323  3365  3413 I jxcore-log: # 1. calling createNativeListener directly rejects
08-11 07:28:36.323  3365  3413 I jxcore-log: 
,08-11 07:28:36.393  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:36.393  3365  3413 I jxcore-log: 
,08-11 07:28:36.399  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 43169
08-11 07:28:36.399  3365  3413 I jxcore-log: 
,08-11 07:28:36.406  3365  3413 I jxcore-log: ok 1 Should throw
08-11 07:28:36.406  3365  3413 I jxcore-log: 
,08-11 07:28:36.410  3365  3413 I jxcore-log: # teardown
08-11 07:28:36.410  3365  3413 I jxcore-log: 
,08-11 07:28:37.444  3365  3413 I jxcore-log: # setup
08-11 07:28:37.444  3365  3413 I jxcore-log: 
,08-11 07:28:37.498  3365  3413 I jxcore-log: # 2. emits incomingConnectionState
08-11 07:28:37.498  3365  3413 I jxcore-log: 
,08-11 07:28:37.678  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:37.678  3365  3413 I jxcore-log: 
,08-11 07:28:37.682  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 39088
08-11 07:28:37.682  3365  3413 I jxcore-log: 
,08-11 07:28:37.692  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:37.692  3365  3413 I jxcore-log: 
,08-11 07:28:37.694   873   883 I ActivityManager: Killing 3181:com.android.defcontainer/u0a7 (adj 15): empty #17
08-11 07:28:37.696  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:37.696  3365  3413 I jxcore-log: 
08-11 07:28:37.705  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:37.705  3365  3413 I jxcore-log: 
,08-11 07:28:37.712  3365  3413 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-11 07:28:37.712  3365  3413 I jxcore-log: 
,08-11 07:28:37.732  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:37.732  3365  3413 I jxcore-log: 
,08-11 07:28:37.733  3365  3413 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-11 07:28:37.733  3365  3413 I jxcore-log: 
,08-11 07:28:37.738  3365  3413 I jxcore-log: # teardown
08-11 07:28:37.738  3365  3413 I jxcore-log: 
,08-11 07:28:37.842  3365  3413 I jxcore-log: # setup
08-11 07:28:37.842  3365  3413 I jxcore-log: 
,08-11 07:28:37.896  3365  3413 I jxcore-log: # 3. emits routerPortConnectionFailed
08-11 07:28:37.896  3365  3413 I jxcore-log: 
,08-11 07:28:38.009  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:38.009  3365  3413 I jxcore-log: 
,08-11 07:28:38.012  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 47991
08-11 07:28:38.012  3365  3413 I jxcore-log: 
,08-11 07:28:38.019  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:38.019  3365  3413 I jxcore-log: 
,08-11 07:28:38.020  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:38.020  3365  3413 I jxcore-log: 
,08-11 07:28:38.022  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:38.022  3365  3413 I jxcore-log: 
,08-11 07:28:38.048   873  1310 D ConnectivityService: handlePromptUnvalidated 100
,08-11 07:28:38.053  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:38.053  3365  3413 I jxcore-log: 
,08-11 07:28:38.056  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:38.056  3365  3413 I jxcore-log: 
,08-11 07:28:38.059  3365  3413 I jxcore-log: DEBUG createNativeListener: 
08-11 07:28:38.059  3365  3413 I jxcore-log: 
,08-11 07:28:38.060  3365  3413 I jxcore-log: ok 4 tried to connect to right port
08-11 07:28:38.060  3365  3413 I jxcore-log: 
08-11 07:28:38.061  3365  3413 I jxcore-log: ok 5 failed due to refused connection
08-11 07:28:38.061  3365  3413 I jxcore-log: 
,08-11 07:28:38.062  3365  3413 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-11 07:28:38.062  3365  3413 I jxcore-log: 
,08-11 07:28:38.064  3365  3413 I jxcore-log: # teardown
08-11 07:28:38.064  3365  3413 I jxcore-log: 
,08-11 07:28:38.066  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:38.066  3365  3413 I jxcore-log: 
,08-11 07:28:38.174  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:38.174  3365  3413 I jxcore-log: 
,08-11 07:28:38.189  3365  3413 I jxcore-log: # setup
08-11 07:28:38.189  3365  3413 I jxcore-log: 
,08-11 07:28:38.191  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:38.191  3365  3413 I jxcore-log: 
,08-11 07:28:38.248  3365  3413 I jxcore-log: # 4. native server connections all up
08-11 07:28:38.248  3365  3413 I jxcore-log: 
,08-11 07:28:38.327  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:38.327  3365  3413 I jxcore-log: 
,08-11 07:28:38.336  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 47483
08-11 07:28:38.336  3365  3413 I jxcore-log: 
,08-11 07:28:38.350  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:38.350  3365  3413 I jxcore-log: 
,08-11 07:28:38.352  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:38.352  3365  3413 I jxcore-log: 
,08-11 07:28:38.354  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:38.354  3365  3413 I jxcore-log: 
,08-11 07:28:38.385  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:38.385  3365  3413 I jxcore-log: 
,08-11 07:28:38.388  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:38.388  3365  3413 I jxcore-log: 
,08-11 07:28:38.392  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:38.392  3365  3413 I jxcore-log: 
,08-11 07:28:38.394  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:38.394  3365  3413 I jxcore-log: 
,08-11 07:28:38.416  3365  3413 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-11 07:28:38.416  3365  3413 I jxcore-log: 
,08-11 07:28:38.417  3365  3413 I jxcore-log: ok 8 Send/recvd #1 should be same
08-11 07:28:38.417  3365  3413 I jxcore-log: 
,08-11 07:28:38.419  3365  3413 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-11 07:28:38.419  3365  3413 I jxcore-log: 
,08-11 07:28:38.420  3365  3413 I jxcore-log: ok 10 Send/recvd #2 should be same
08-11 07:28:38.420  3365  3413 I jxcore-log: 
,08-11 07:28:38.423  3365  3413 I jxcore-log: ok 11 Should be exactly 2 client sockets
08-11 07:28:38.423  3365  3413 I jxcore-log: 
,08-11 07:28:38.430  3365  3413 I jxcore-log: # teardown
08-11 07:28:38.430  3365  3413 I jxcore-log: 
,08-11 07:28:38.481  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:38.481  3365  3413 I jxcore-log: 
,08-11 07:28:38.486  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:38.486  3365  3413 I jxcore-log: 
,08-11 07:28:38.491  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:38.491  3365  3413 I jxcore-log: 
,08-11 07:28:38.495  3365  3413 I jxcore-log: # setup
08-11 07:28:38.495  3365  3413 I jxcore-log: 
,08-11 07:28:38.496  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:38.496  3365  3413 I jxcore-log: 
,08-11 07:28:38.551  3365  3413 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-11 07:28:38.551  3365  3413 I jxcore-log: 
,08-11 07:28:38.600  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:38.600  3365  3413 I jxcore-log: 
,08-11 07:28:38.605  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 46767
08-11 07:28:38.605  3365  3413 I jxcore-log: 
,08-11 07:28:38.615  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:38.615  3365  3413 I jxcore-log: 
,08-11 07:28:38.617  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:38.617  3365  3413 I jxcore-log: 
,08-11 07:28:38.620  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:38.620  3365  3413 I jxcore-log: 
,08-11 07:28:38.640  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:38.640  3365  3413 I jxcore-log: 
,08-11 07:28:38.643  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:38.643  3365  3413 I jxcore-log: 
,08-11 07:28:38.657  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:38.657  3365  3413 I jxcore-log: 
,08-11 07:28:38.671  3365  3413 I jxcore-log: ok 12 socket shouldn't close until after stream
08-11 07:28:38.671  3365  3413 I jxcore-log: 
,08-11 07:28:38.672  3365  3413 I jxcore-log: ok 13 incoming remains open
08-11 07:28:38.672  3365  3413 I jxcore-log: 
,08-11 07:28:38.675  3365  3413 I jxcore-log: # teardown
08-11 07:28:38.675  3365  3413 I jxcore-log: 
,08-11 07:28:38.755  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:38.755  3365  3413 I jxcore-log: 
,08-11 07:28:38.759  3365  3413 I jxcore-log: # setup
08-11 07:28:38.759  3365  3413 I jxcore-log: 
,08-11 07:28:38.761  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:38.761  3365  3413 I jxcore-log: 
,08-11 07:28:38.823  3365  3413 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-11 07:28:38.823  3365  3413 I jxcore-log: 
,08-11 07:28:38.896  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:38.896  3365  3413 I jxcore-log: 
,08-11 07:28:38.907  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 47879
08-11 07:28:38.907  3365  3413 I jxcore-log: 
,08-11 07:28:38.917  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:38.917  3365  3413 I jxcore-log: 
,08-11 07:28:38.919  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:38.919  3365  3413 I jxcore-log: 
,08-11 07:28:38.920  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:38.920  3365  3413 I jxcore-log: 
,08-11 07:28:38.936  3365  3413 I jxcore-log: ok 14 we should not have gotten an error
08-11 07:28:38.936  3365  3413 I jxcore-log: 
,08-11 07:28:38.945  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:38.945  3365  3413 I jxcore-log: 
,08-11 07:28:38.950  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:38.950  3365  3413 I jxcore-log: 
,08-11 07:28:38.960  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:38.960  3365  3413 I jxcore-log: 
,08-11 07:28:38.963  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:38.963  3365  3413 I jxcore-log: 
,08-11 07:28:38.970  3365  3413 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-11 07:28:38.970  3365  3413 I jxcore-log: 
,08-11 07:28:38.971  3365  3413 I jxcore-log: ok 16 incoming is cleaned up
08-11 07:28:38.971  3365  3413 I jxcore-log: 
,08-11 07:28:38.974  3365  3413 I jxcore-log: # teardown
08-11 07:28:38.974  3365  3413 I jxcore-log: 
,08-11 07:28:39.075  3365  3413 I jxcore-log: # setup
08-11 07:28:39.075  3365  3413 I jxcore-log: 
,08-11 07:28:39.126  3365  3413 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-11 07:28:39.126  3365  3413 I jxcore-log: 
,08-11 07:28:39.170  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:39.170  3365  3413 I jxcore-log: 
,08-11 07:28:39.173  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 41242
08-11 07:28:39.173  3365  3413 I jxcore-log: 
,08-11 07:28:39.179  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.179  3365  3413 I jxcore-log: 
,08-11 07:28:39.181  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.181  3365  3413 I jxcore-log: 
,08-11 07:28:39.183  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.183  3365  3413 I jxcore-log: 
,08-11 07:28:39.198  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.198  3365  3413 I jxcore-log: 
,08-11 07:28:39.201  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.201  3365  3413 I jxcore-log: 
,08-11 07:28:39.216  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:39.216  3365  3413 I jxcore-log: 
,08-11 07:28:39.230  3365  3413 I jxcore-log: ok 17 stream was closed
08-11 07:28:39.230  3365  3413 I jxcore-log: 
,08-11 07:28:39.231  3365  3413 I jxcore-log: ok 18 incoming should survive
08-11 07:28:39.231  3365  3413 I jxcore-log: 
08-11 07:28:39.231  3365  3413 I jxcore-log: ok 19 mux should have no streams
08-11 07:28:39.231  3365  3413 I jxcore-log: 
,08-11 07:28:39.236  3365  3413 I jxcore-log: # teardown
08-11 07:28:39.236  3365  3413 I jxcore-log: 
,08-11 07:28:39.376  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:39.376  3365  3413 I jxcore-log: 
,08-11 07:28:39.382  3365  3413 I jxcore-log: # setup
08-11 07:28:39.382  3365  3413 I jxcore-log: 
,08-11 07:28:39.383  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:39.383  3365  3413 I jxcore-log: 
,08-11 07:28:39.454  3365  3413 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-11 07:28:39.454  3365  3413 I jxcore-log: 
,08-11 07:28:39.498  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:39.498  3365  3413 I jxcore-log: 
,08-11 07:28:39.501  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 47417
08-11 07:28:39.501  3365  3413 I jxcore-log: 
,08-11 07:28:39.507  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.507  3365  3413 I jxcore-log: 
,08-11 07:28:39.509  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.509  3365  3413 I jxcore-log: 
,08-11 07:28:39.510  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.510  3365  3413 I jxcore-log: 
,08-11 07:28:39.520  3365  3413 I jxcore-log: ok 20 we should not have gotten an error
08-11 07:28:39.520  3365  3413 I jxcore-log: 
,08-11 07:28:39.529  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.529  3365  3413 I jxcore-log: 
,08-11 07:28:39.532  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.532  3365  3413 I jxcore-log: 
,08-11 07:28:39.542  3365  3413 I jxcore-log: ok 21 Buffers are identical
08-11 07:28:39.542  3365  3413 I jxcore-log: 
,08-11 07:28:39.545  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:39.545  3365  3413 I jxcore-log: 
,08-11 07:28:39.547  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:39.547  3365  3413 I jxcore-log: 
,08-11 07:28:39.550  3365  3413 I jxcore-log: ok 22 native server is nulled out
08-11 07:28:39.550  3365  3413 I jxcore-log: 
,08-11 07:28:39.551  3365  3413 I jxcore-log: ok 23 native server should be closed
08-11 07:28:39.551  3365  3413 I jxcore-log: 
,08-11 07:28:39.551  3365  3413 I jxcore-log: ok 24 incoming has been removed
08-11 07:28:39.551  3365  3413 I jxcore-log: 
,08-11 07:28:39.552  3365  3413 I jxcore-log: ok 25 Incoming should be done
08-11 07:28:39.552  3365  3413 I jxcore-log: 
,08-11 07:28:39.552  3365  3413 I jxcore-log: ok 26 The mux object should be closed
08-11 07:28:39.552  3365  3413 I jxcore-log: 
08-11 07:28:39.552  3365  3413 I jxcore-log: ok 27 The mux stream should be closed
08-11 07:28:39.552  3365  3413 I jxcore-log: 
08-11 07:28:39.553  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:39.553  3365  3413 I jxcore-log: 
,08-11 07:28:39.566  3365  3413 I jxcore-log: # teardown
08-11 07:28:39.566  3365  3413 I jxcore-log: 
,08-11 07:28:39.672  3365  3413 I jxcore-log: # setup
08-11 07:28:39.672  3365  3413 I jxcore-log: 
,08-11 07:28:39.729  3365  3413 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-11 07:28:39.729  3365  3413 I jxcore-log: 
,08-11 07:28:39.806  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:39.806  3365  3413 I jxcore-log: 
,08-11 07:28:39.809  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 42093
08-11 07:28:39.809  3365  3413 I jxcore-log: 
,08-11 07:28:39.840  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.840  3365  3413 I jxcore-log: 
,08-11 07:28:39.841  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.841  3365  3413 I jxcore-log: 
,08-11 07:28:39.842  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.842  3365  3413 I jxcore-log: 
,08-11 07:28:39.846  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.846  3365  3413 I jxcore-log: 
,08-11 07:28:39.846  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.846  3365  3413 I jxcore-log: 
,08-11 07:28:39.848  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.848  3365  3413 I jxcore-log: 
,08-11 07:28:39.850  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.850  3365  3413 I jxcore-log: 
,08-11 07:28:39.851  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.851  3365  3413 I jxcore-log: 
,08-11 07:28:39.852  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.852  3365  3413 I jxcore-log: 
,08-11 07:28:39.856  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.856  3365  3413 I jxcore-log: 
,08-11 07:28:39.857  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.857  3365  3413 I jxcore-log: 
,08-11 07:28:39.858  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.858  3365  3413 I jxcore-log: 
,08-11 07:28:39.862  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.862  3365  3413 I jxcore-log: 
,08-11 07:28:39.862  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.862  3365  3413 I jxcore-log: 
,08-11 07:28:39.864  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.864  3365  3413 I jxcore-log: 
,08-11 07:28:39.866  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.866  3365  3413 I jxcore-log: 
,08-11 07:28:39.867  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.867  3365  3413 I jxcore-log: 
,08-11 07:28:39.868  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.868  3365  3413 I jxcore-log: 
,08-11 07:28:39.875  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.875  3365  3413 I jxcore-log: 
,08-11 07:28:39.877  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.877  3365  3413 I jxcore-log: 
,08-11 07:28:39.878  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.878  3365  3413 I jxcore-log: 
,08-11 07:28:39.882  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.882  3365  3413 I jxcore-log: 
,08-11 07:28:39.882  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.882  3365  3413 I jxcore-log: 
,08-11 07:28:39.883  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.883  3365  3413 I jxcore-log: 
,08-11 07:28:39.885  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.885  3365  3413 I jxcore-log: 
,08-11 07:28:39.885  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.885  3365  3413 I jxcore-log: 
,08-11 07:28:39.886  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.886  3365  3413 I jxcore-log: 
,08-11 07:28:39.887  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:39.887  3365  3413 I jxcore-log: 
,08-11 07:28:39.888  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:39.888  3365  3413 I jxcore-log: 
,08-11 07:28:39.889  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:39.889  3365  3413 I jxcore-log: 
,08-11 07:28:39.978  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.978  3365  3413 I jxcore-log: 
,08-11 07:28:39.981  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.981  3365  3413 I jxcore-log: 
,08-11 07:28:39.983  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.983  3365  3413 I jxcore-log: 
,08-11 07:28:39.984  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.984  3365  3413 I jxcore-log: 
,08-11 07:28:39.986  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.986  3365  3413 I jxcore-log: 
,08-11 07:28:39.987  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.987  3365  3413 I jxcore-log: 
,08-11 07:28:39.989  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.989  3365  3413 I jxcore-log: 
,08-11 07:28:39.991  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.991  3365  3413 I jxcore-log: 
,08-11 07:28:39.993  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.993  3365  3413 I jxcore-log: 
,08-11 07:28:39.995  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:39.995  3365  3413 I jxcore-log: 
,08-11 07:28:39.996  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:39.996  3365  3413 I jxcore-log: 
,08-11 07:28:40.000  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.000  3365  3413 I jxcore-log: 
,08-11 07:28:40.005  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.005  3365  3413 I jxcore-log: 
,08-11 07:28:40.022  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.022  3365  3413 I jxcore-log: 
,08-11 07:28:40.024  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.024  3365  3413 I jxcore-log: 
,08-11 07:28:40.026  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.026  3365  3413 I jxcore-log: 
,08-11 07:28:40.029  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.029  3365  3413 I jxcore-log: 
,08-11 07:28:40.031  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.031  3365  3413 I jxcore-log: 
,08-11 07:28:40.033  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.033  3365  3413 I jxcore-log: 
,08-11 07:28:40.035  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.035  3365  3413 I jxcore-log: 
,08-11 07:28:40.036  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.036  3365  3413 I jxcore-log: 
,08-11 07:28:40.038  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.038  3365  3413 I jxcore-log: 
,08-11 07:28:40.040  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.040  3365  3413 I jxcore-log: 
,08-11 07:28:40.042  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.042  3365  3413 I jxcore-log: 
,08-11 07:28:40.044  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.044  3365  3413 I jxcore-log: 
,08-11 07:28:40.046  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.046  3365  3413 I jxcore-log: 
,08-11 07:28:40.048  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.048  3365  3413 I jxcore-log: 
,08-11 07:28:40.049  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.049  3365  3413 I jxcore-log: 
,08-11 07:28:40.051  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.051  3365  3413 I jxcore-log: 
,08-11 07:28:40.053  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.053  3365  3413 I jxcore-log: 
,08-11 07:28:40.054  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.054  3365  3413 I jxcore-log: 
,08-11 07:28:40.056  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.056  3365  3413 I jxcore-log: 
,08-11 07:28:40.058  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.058  3365  3413 I jxcore-log: 
,08-11 07:28:40.060  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.060  3365  3413 I jxcore-log: 
,08-11 07:28:40.062  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.062  3365  3413 I jxcore-log: 
,08-11 07:28:40.063  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.063  3365  3413 I jxcore-log: 
,08-11 07:28:40.065  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.065  3365  3413 I jxcore-log: 
,08-11 07:28:40.066  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.066  3365  3413 I jxcore-log: 
,08-11 07:28:40.074  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.074  3365  3413 I jxcore-log: 
,08-11 07:28:40.076  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.076  3365  3413 I jxcore-log: 
,08-11 07:28:40.080  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.080  3365  3413 I jxcore-log: 
,08-11 07:28:40.082  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.082  3365  3413 I jxcore-log: 
,08-11 07:28:40.083  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.083  3365  3413 I jxcore-log: 
,08-11 07:28:40.085  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.085  3365  3413 I jxcore-log: 
,08-11 07:28:40.086  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.086  3365  3413 I jxcore-log: 
,08-11 07:28:40.087  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.087  3365  3413 I jxcore-log: 
,08-11 07:28:40.088  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.088  3365  3413 I jxcore-log: 
,08-11 07:28:40.089  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.089  3365  3413 I jxcore-log: 
,08-11 07:28:40.091  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.091  3365  3413 I jxcore-log: 
,08-11 07:28:40.093  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.093  3365  3413 I jxcore-log: 
,08-11 07:28:40.094  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.094  3365  3413 I jxcore-log: 
,08-11 07:28:40.096  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.096  3365  3413 I jxcore-log: 
08-11 07:28:40.097  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.097  3365  3413 I jxcore-log: 
,08-11 07:28:40.099  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.099  3365  3413 I jxcore-log: 
,08-11 07:28:40.101  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.101  3365  3413 I jxcore-log: 
,08-11 07:28:40.102  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.102  3365  3413 I jxcore-log: 
,08-11 07:28:40.105  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.105  3365  3413 I jxcore-log: 
,08-11 07:28:40.106  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.106  3365  3413 I jxcore-log: 
,08-11 07:28:40.107  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.107  3365  3413 I jxcore-log: 
,08-11 07:28:40.109  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.109  3365  3413 I jxcore-log: 
,08-11 07:28:40.110  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.110  3365  3413 I jxcore-log: 
,08-11 07:28:40.111  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.111  3365  3413 I jxcore-log: 
,08-11 07:28:40.113  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.113  3365  3413 I jxcore-log: 
,08-11 07:28:40.114  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.114  3365  3413 I jxcore-log: 
,08-11 07:28:40.116  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.116  3365  3413 I jxcore-log: 
,08-11 07:28:40.117  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.117  3365  3413 I jxcore-log: 
,08-11 07:28:40.119  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.119  3365  3413 I jxcore-log: 
,08-11 07:28:40.120  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.120  3365  3413 I jxcore-log: 
,08-11 07:28:40.121  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.121  3365  3413 I jxcore-log: 
,08-11 07:28:40.123  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.123  3365  3413 I jxcore-log: 
08-11 07:28:40.124  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.124  3365  3413 I jxcore-log: 
,08-11 07:28:40.125  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.125  3365  3413 I jxcore-log: 
,08-11 07:28:40.127  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.127  3365  3413 I jxcore-log: 
,08-11 07:28:40.129  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.129  3365  3413 I jxcore-log: 
,08-11 07:28:40.130  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.130  3365  3413 I jxcore-log: 
,08-11 07:28:40.131  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.131  3365  3413 I jxcore-log: 
,08-11 07:28:40.132  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.132  3365  3413 I jxcore-log: 
,08-11 07:28:40.134  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.134  3365  3413 I jxcore-log: 
08-11 07:28:40.135  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.135  3365  3413 I jxcore-log: 
,08-11 07:28:40.136  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.136  3365  3413 I jxcore-log: 
,08-11 07:28:40.212  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.212  3365  3413 I jxcore-log: 
,08-11 07:28:40.215  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.215  3365  3413 I jxcore-log: 
,08-11 07:28:40.216  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.216  3365  3413 I jxcore-log: 
,08-11 07:28:40.217  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.217  3365  3413 I jxcore-log: 
,08-11 07:28:40.219  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.219  3365  3413 I jxcore-log: 
,08-11 07:28:40.220  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.220  3365  3413 I jxcore-log: 
,08-11 07:28:40.221  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.221  3365  3413 I jxcore-log: 
,08-11 07:28:40.222  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.222  3365  3413 I jxcore-log: 
08-11 07:28:40.223  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.223  3365  3413 I jxcore-log: 
,08-11 07:28:40.224  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.224  3365  3413 I jxcore-log: 
,08-11 07:28:40.225  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.225  3365  3413 I jxcore-log: 
,08-11 07:28:40.228  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.228  3365  3413 I jxcore-log: 
,08-11 07:28:40.229  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.229  3365  3413 I jxcore-log: 
,08-11 07:28:40.230  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.230  3365  3413 I jxcore-log: 
,08-11 07:28:40.232  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.232  3365  3413 I jxcore-log: 
,08-11 07:28:40.237  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.237  3365  3413 I jxcore-log: 
,08-11 07:28:40.239  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.239  3365  3413 I jxcore-log: 
,08-11 07:28:40.241  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.241  3365  3413 I jxcore-log: 
,08-11 07:28:40.241  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.241  3365  3413 I jxcore-log: 
,08-11 07:28:40.242  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.242  3365  3413 I jxcore-log: 
08-11 07:28:40.243  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.243  3365  3413 I jxcore-log: 
,08-11 07:28:40.244  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.244  3365  3413 I jxcore-log: 
,08-11 07:28:40.245  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.245  3365  3413 I jxcore-log: 
08-11 07:28:40.246  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.246  3365  3413 I jxcore-log: 
,08-11 07:28:40.247  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.247  3365  3413 I jxcore-log: 
,08-11 07:28:40.248  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.248  3365  3413 I jxcore-log: 
,08-11 07:28:40.249  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.249  3365  3413 I jxcore-log: 
,08-11 07:28:40.250  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.250  3365  3413 I jxcore-log: 
08-11 07:28:40.251  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.251  3365  3413 I jxcore-log: 
,08-11 07:28:40.252  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.252  3365  3413 I jxcore-log: 
,08-11 07:28:40.253  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.253  3365  3413 I jxcore-log: 
,08-11 07:28:40.254  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.254  3365  3413 I jxcore-log: 
08-11 07:28:40.254  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.254  3365  3413 I jxcore-log: 
,08-11 07:28:40.255  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.255  3365  3413 I jxcore-log: 
,08-11 07:28:40.256  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.256  3365  3413 I jxcore-log: 
08-11 07:28:40.257  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.257  3365  3413 I jxcore-log: 
,08-11 07:28:40.258  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.258  3365  3413 I jxcore-log: 
,08-11 07:28:40.258  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.258  3365  3413 I jxcore-log: 
,08-11 07:28:40.264  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.264  3365  3413 I jxcore-log: 
,08-11 07:28:40.265  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.265  3365  3413 I jxcore-log: 
,08-11 07:28:40.266  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.266  3365  3413 I jxcore-log: 
,08-11 07:28:40.267  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.267  3365  3413 I jxcore-log: 
08-11 07:28:40.268  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.268  3365  3413 I jxcore-log: 
,08-11 07:28:40.269  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.269  3365  3413 I jxcore-log: 
,08-11 07:28:40.269  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.269  3365  3413 I jxcore-log: 
08-11 07:28:40.270  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.270  3365  3413 I jxcore-log: 
,08-11 07:28:40.271  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.271  3365  3413 I jxcore-log: 
,08-11 07:28:40.272  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.272  3365  3413 I jxcore-log: 
08-11 07:28:40.273  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.273  3365  3413 I jxcore-log: 
,08-11 07:28:40.274  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.274  3365  3413 I jxcore-log: 
,08-11 07:28:40.277  3365  3413 I jxcore-log: ok 28 native server is nulled out
08-11 07:28:40.277  3365  3413 I jxcore-log: 
,08-11 07:28:40.278  3365  3413 I jxcore-log: ok 29 native server should be closed
08-11 07:28:40.278  3365  3413 I jxcore-log: 
08-11 07:28:40.278  3365  3413 I jxcore-log: ok 30 incoming has been removed
08-11 07:28:40.278  3365  3413 I jxcore-log: 
,08-11 07:28:40.279  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.279  3365  3413 I jxcore-log: 
,08-11 07:28:40.284  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.284  3365  3413 I jxcore-log: 
,08-11 07:28:40.287  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.287  3365  3413 I jxcore-log: 
,08-11 07:28:40.290  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.290  3365  3413 I jxcore-log: 
,08-11 07:28:40.293  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.293  3365  3413 I jxcore-log: 
,08-11 07:28:40.296  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.296  3365  3413 I jxcore-log: 
,08-11 07:28:40.298  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.298  3365  3413 I jxcore-log: 
,08-11 07:28:40.301  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.301  3365  3413 I jxcore-log: 
,08-11 07:28:40.303  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.303  3365  3413 I jxcore-log: 
,08-11 07:28:40.306  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.306  3365  3413 I jxcore-log: 
,08-11 07:28:40.464  3365  3413 I jxcore-log: # teardown
08-11 07:28:40.464  3365  3413 I jxcore-log: 
,08-11 07:28:40.507  3365  3413 I jxcore-log: # setup
08-11 07:28:40.507  3365  3413 I jxcore-log: 
,08-11 07:28:40.583  3365  3413 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-11 07:28:40.583  3365  3413 I jxcore-log: 
,08-11 07:28:40.627  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:40.627  3365  3413 I jxcore-log: 
,08-11 07:28:40.629  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 42187
08-11 07:28:40.629  3365  3413 I jxcore-log: 
,08-11 07:28:40.635  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:40.635  3365  3413 I jxcore-log: 
,08-11 07:28:40.637  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:40.637  3365  3413 I jxcore-log: 
,08-11 07:28:40.638  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:40.638  3365  3413 I jxcore-log: 
,08-11 07:28:40.645  3365  3413 I jxcore-log: ok 31 we should not have gotten an error
08-11 07:28:40.645  3365  3413 I jxcore-log: 
,08-11 07:28:40.656  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.656  3365  3413 I jxcore-log: 
,08-11 07:28:40.659  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.659  3365  3413 I jxcore-log: 
,08-11 07:28:40.666  3365  3413 I jxcore-log: ok 32 Buffers are identical
08-11 07:28:40.666  3365  3413 I jxcore-log: 
,08-11 07:28:40.667  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.667  3365  3413 I jxcore-log: 
,08-11 07:28:40.669  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.669  3365  3413 I jxcore-log: 
,08-11 07:28:40.681  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.681  3365  3413 I jxcore-log: 
,08-11 07:28:40.681  3365  3413 I jxcore-log: ok 33 server should be fine
08-11 07:28:40.681  3365  3413 I jxcore-log: 
08-11 07:28:40.682  3365  3413 I jxcore-log: ok 34 server should be open
08-11 07:28:40.682  3365  3413 I jxcore-log: 
,08-11 07:28:40.682  3365  3413 I jxcore-log: ok 35 incoming has been removed
08-11 07:28:40.682  3365  3413 I jxcore-log: 
08-11 07:28:40.683  3365  3413 I jxcore-log: ok 36 The mux object should be closed
08-11 07:28:40.683  3365  3413 I jxcore-log: 
,08-11 07:28:40.683  3365  3413 I jxcore-log: ok 37 The mux stream should be closed
08-11 07:28:40.683  3365  3413 I jxcore-log: 
,08-11 07:28:40.688  3365  3413 I jxcore-log: # teardown
08-11 07:28:40.688  3365  3413 I jxcore-log: 
,08-11 07:28:40.717  3365  3413 I jxcore-log: # setup
08-11 07:28:40.717  3365  3413 I jxcore-log: 
,08-11 07:28:40.785  3365  3413 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-11 07:28:40.785  3365  3413 I jxcore-log: 
,08-11 07:28:40.833  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:40.833  3365  3413 I jxcore-log: 
,08-11 07:28:40.836  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 39694
08-11 07:28:40.836  3365  3413 I jxcore-log: 
,08-11 07:28:40.842  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:28:40.842  3365  3413 I jxcore-log: 
,08-11 07:28:40.843  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:28:40.843  3365  3413 I jxcore-log: 
,08-11 07:28:40.845  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:28:40.845  3365  3413 I jxcore-log: 
,08-11 07:28:40.851  3365  3413 I jxcore-log: ok 38 we should not have gotten an error
08-11 07:28:40.851  3365  3413 I jxcore-log: 
,08-11 07:28:40.858  3365  3413 I jxcore-log: DEBUG createNativeListener: new stream: 
08-11 07:28:40.858  3365  3413 I jxcore-log: 
,08-11 07:28:40.860  3365  3413 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-11 07:28:40.860  3365  3413 I jxcore-log: 
,08-11 07:28:40.868  3365  3413 I jxcore-log: ok 39 Buffers are identical
08-11 07:28:40.868  3365  3413 I jxcore-log: 
,08-11 07:28:40.872  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-11 07:28:40.872  3365  3413 I jxcore-log: 
,08-11 07:28:40.873  3365  3413 I jxcore-log: DEBUG createNativeListener: stream close:
08-11 07:28:40.873  3365  3413 I jxcore-log: 
,08-11 07:28:40.875  3365  3413 I jxcore-log: DEBUG createNativeListener: mux close
08-11 07:28:40.875  3365  3413 I jxcore-log: 
,08-11 07:28:40.880  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:28:40.880  3365  3413 I jxcore-log: 
,08-11 07:28:40.881  3365  3413 I jxcore-log: ok 40 server should be fine
08-11 07:28:40.881  3365  3413 I jxcore-log: 
08-11 07:28:40.881  3365  3413 I jxcore-log: ok 41 server should be open
08-11 07:28:40.881  3365  3413 I jxcore-log: 
,08-11 07:28:40.881  3365  3413 I jxcore-log: ok 42 incoming has been removed
08-11 07:28:40.881  3365  3413 I jxcore-log: 
08-11 07:28:40.882  3365  3413 I jxcore-log: ok 43 The mux object should be closed
08-11 07:28:40.882  3365  3413 I jxcore-log: 
,08-11 07:28:40.882  3365  3413 I jxcore-log: ok 44 The mux stream should be closed
08-11 07:28:40.882  3365  3413 I jxcore-log: 
,08-11 07:28:40.889  3365  3413 I jxcore-log: # teardown
08-11 07:28:40.889  3365  3413 I jxcore-log: 
,08-11 07:28:40.977  3365  3413 I jxcore-log: # setup
08-11 07:28:40.977  3365  3413 I jxcore-log: 
,08-11 07:28:41.014  3365  3413 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-11 07:28:41.014  3365  3413 I jxcore-log: 
,08-11 07:28:41.189  3365  3413 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-11 07:28:41.189  3365  3413 I jxcore-log: 
,08-11 07:28:41.190  3365  3413 I jxcore-log: ok 45 Got right error
08-11 07:28:41.190  3365  3413 I jxcore-log: 
,08-11 07:28:41.196  3365  3413 I jxcore-log: # teardown
08-11 07:28:41.196  3365  3413 I jxcore-log: 
,08-11 07:28:41.217  2590  2601 D Finsky  : [177] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-11 07:28:41.230  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:41.238  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:41.241  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:28:41.274  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 07:28:41.274  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-11 07:28:41.274  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:28:41.275  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:28:41.302  2590  2601 D Finsky  : [177] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-11 07:28:41.358  3365  3413 I jxcore-log: # setup
08-11 07:28:41.358  3365  3413 I jxcore-log: 
,08-11 07:28:41.416  3365  3413 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-11 07:28:41.416  3365  3413 I jxcore-log: 
,08-11 07:28:41.523  3365  3413 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-11 07:28:41.523  3365  3413 I jxcore-log: 
,08-11 07:28:41.525  3365  3413 I jxcore-log: ok 46 Got socket hang up
08-11 07:28:41.525  3365  3413 I jxcore-log: 
,08-11 07:28:41.529  3365  3413 I jxcore-log: # teardown
08-11 07:28:41.529  3365  3413 I jxcore-log: 
,08-11 07:28:41.626  3365  3413 I jxcore-log: # setup
08-11 07:28:41.626  3365  3413 I jxcore-log: 
,08-11 07:28:41.666  3365  3413 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-11 07:28:41.666  3365  3413 I jxcore-log: 
,08-11 07:28:41.826  3365  3413 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
08-11 07:28:41.826  3365  3413 I jxcore-log: 
,08-11 07:28:41.827  3365  3413 I jxcore-log: ok 47 Got 500 as expected
08-11 07:28:41.827  3365  3413 I jxcore-log: 
,08-11 07:28:41.830  3365  3413 I jxcore-log: # teardown
08-11 07:28:41.830  3365  3413 I jxcore-log: 
,08-11 07:28:41.991  3365  3413 I jxcore-log: # setup
08-11 07:28:41.991  3365  3413 I jxcore-log: 
,08-11 07:28:42.075  3365  3413 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
08-11 07:28:42.075  3365  3413 I jxcore-log: 
,08-11 07:28:44.001  3365  3413 I jxcore-log: ok 48 should be equal
08-11 07:28:44.001  3365  3413 I jxcore-log: 
,08-11 07:28:44.001  3365  3413 I jxcore-log: ok 49 revs are equal
08-11 07:28:44.001  3365  3413 I jxcore-log: 
,08-11 07:28:44.005  3365  3413 I jxcore-log: # teardown
08-11 07:28:44.005  3365  3413 I jxcore-log: 
,08-11 07:28:44.041  3365  3413 I jxcore-log: # setup
08-11 07:28:44.041  3365  3413 I jxcore-log: 
,08-11 07:28:44.104  3365  3413 I jxcore-log: # 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
08-11 07:28:44.104  3365  3413 I jxcore-log: 
,08-11 07:28:44.766  3365  3413 I jxcore-log: ok 50 should be equal
08-11 07:28:44.766  3365  3413 I jxcore-log: 
,08-11 07:28:44.767  3365  3413 I jxcore-log: ok 51 revs are equal
08-11 07:28:44.767  3365  3413 I jxcore-log: 
,08-11 07:28:44.771  3365  3413 I jxcore-log: # teardown
08-11 07:28:44.771  3365  3413 I jxcore-log: 
,08-11 07:28:44.807  3365  3413 I jxcore-log: # setup
08-11 07:28:44.807  3365  3413 I jxcore-log: 
,08-11 07:28:44.862  3365  3413 I jxcore-log: # 17. #_doImmediateSeqUpdate - update seq three times
08-11 07:28:44.862  3365  3413 I jxcore-log: 
,08-11 07:28:45.322  3365  3413 I jxcore-log: ok 52 should be equal
08-11 07:28:45.322  3365  3413 I jxcore-log: 
,08-11 07:28:45.323  3365  3413 I jxcore-log: ok 53 revs are equal
08-11 07:28:45.323  3365  3413 I jxcore-log: 
,08-11 07:28:45.455  3365  3413 I jxcore-log: ok 54 should be equal
08-11 07:28:45.455  3365  3413 I jxcore-log: 
,08-11 07:28:45.456  3365  3413 I jxcore-log: ok 55 revs are equal
08-11 07:28:45.456  3365  3413 I jxcore-log: 
,08-11 07:28:45.596  3365  3413 I jxcore-log: ok 56 should be equal
08-11 07:28:45.596  3365  3413 I jxcore-log: 
,08-11 07:28:45.597  3365  3413 I jxcore-log: ok 57 revs are equal
08-11 07:28:45.597  3365  3413 I jxcore-log: 
,08-11 07:28:45.601  3365  3413 I jxcore-log: # teardown
08-11 07:28:45.601  3365  3413 I jxcore-log: 
,08-11 07:28:45.637  3365  3413 I jxcore-log: # setup
08-11 07:28:45.637  3365  3413 I jxcore-log: 
,08-11 07:28:45.689  3365  3413 I jxcore-log: # 18. #_doImmediateSeqUpdate - rev got changed under us
08-11 07:28:45.689  3365  3413 I jxcore-log: 
,08-11 07:28:46.278  3365  3413 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
08-11 07:28:46.278  3365  3413 I jxcore-log: 
,08-11 07:28:46.279  3365  3413 I jxcore-log: ok 58 Our rev is old so we should fail
08-11 07:28:46.279  3365  3413 I jxcore-log: 
,08-11 07:28:46.282  3365  3413 I jxcore-log: # teardown
08-11 07:28:46.282  3365  3413 I jxcore-log: 
,08-11 07:28:46.481  3365  3413 I jxcore-log: # setup
08-11 07:28:46.481  3365  3413 I jxcore-log: 
,08-11 07:28:46.607  3365  3413 I jxcore-log: # 19. #_doImmediateSeqUpdate - fail if stop is called
08-11 07:28:46.607  3365  3413 I jxcore-log: 
,08-11 07:28:46.763  3365  3413 I jxcore-log: ok 59 confirm stop caused failure
08-11 07:28:46.763  3365  3413 I jxcore-log: 
,08-11 07:28:46.768  3365  3413 I jxcore-log: # teardown
08-11 07:28:46.768  3365  3413 I jxcore-log: 
,08-11 07:28:46.829  3365  3413 I jxcore-log: # setup
08-11 07:28:46.829  3365  3413 I jxcore-log: 
,08-11 07:28:46.863  3365  3413 I jxcore-log: # 20. #_doImmediateSeqUpdate - stop after get but before put fails right
08-11 07:28:46.863  3365  3413 I jxcore-log: 
,08-11 07:28:47.128  3365  3413 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
08-11 07:28:47.128  3365  3413 I jxcore-log: 
,08-11 07:28:47.130  3365  3413 I jxcore-log: ok 60 stop caused us to fail
08-11 07:28:47.130  3365  3413 I jxcore-log: 
,08-11 07:28:47.131  3365  3413 I jxcore-log: ok 61 We specifically failed on a stop before put
08-11 07:28:47.131  3365  3413 I jxcore-log: 
,08-11 07:28:47.134  3365  3413 I jxcore-log: # teardown
08-11 07:28:47.134  3365  3413 I jxcore-log: 
,08-11 07:28:47.285  3365  3413 I jxcore-log: # setup
08-11 07:28:47.285  3365  3413 I jxcore-log: 
,08-11 07:28:47.376  3365  3413 I jxcore-log: # 21. #update - fail if stop is called
08-11 07:28:47.376  3365  3413 I jxcore-log: 
,08-11 07:28:47.515  3365  3413 I jxcore-log: ok 62 failed due to stop
08-11 07:28:47.515  3365  3413 I jxcore-log: 
,08-11 07:28:47.519  3365  3413 I jxcore-log: ok 63 failed due to stop
08-11 07:28:47.519  3365  3413 I jxcore-log: 
,08-11 07:28:47.535  3365  3413 I jxcore-log: # teardown
08-11 07:28:47.535  3365  3413 I jxcore-log: 
,08-11 07:28:47.624  3365  3413 I jxcore-log: # setup
08-11 07:28:47.624  3365  3413 I jxcore-log: 
,08-11 07:28:47.668  3365  3413 I jxcore-log: # 22. #update - set seq for first time
08-11 07:28:47.668  3365  3413 I jxcore-log: 
,08-11 07:28:48.193  3365  3413 I jxcore-log: ok 64 should be equal
08-11 07:28:48.193  3365  3413 I jxcore-log: 
,08-11 07:28:48.198  3365  3413 I jxcore-log: # teardown
08-11 07:28:48.198  3365  3413 I jxcore-log: 
,08-11 07:28:48.248  3365  3413 I jxcore-log: # setup
08-11 07:28:48.248  3365  3413 I jxcore-log: 
,08-11 07:28:48.302  3365  3413 I jxcore-log: # 23. #update - Fail on bad seq value
08-11 07:28:48.302  3365  3413 I jxcore-log: 
,08-11 07:28:48.746  3365  3413 I jxcore-log: DEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
08-11 07:28:48.746  3365  3413 I jxcore-log: 
,08-11 07:28:48.748  3365  3413 I jxcore-log: ok 65 Expected bad seq error
08-11 07:28:48.748  3365  3413 I jxcore-log: 
,08-11 07:28:48.752  3365  3413 I jxcore-log: # teardown
08-11 07:28:48.752  3365  3413 I jxcore-log: 
,08-11 07:28:48.793  3365  3413 I jxcore-log: # setup
08-11 07:28:48.793  3365  3413 I jxcore-log: 
,08-11 07:28:48.853  3365  3413 I jxcore-log: # 24. #update - do we cancel timer properly on an immediate?
08-11 07:28:48.853  3365  3413 I jxcore-log: 
,08-11 07:28:49.275  3365  3413 I jxcore-log: ok 66 Different promises
08-11 07:28:49.275  3365  3413 I jxcore-log: 
,08-11 07:28:49.278  3365  3413 I jxcore-log: ok 67 Timer was cancelled
08-11 07:28:49.278  3365  3413 I jxcore-log: 
,08-11 07:28:49.421  3365  3413 I jxcore-log: ok 68 should be equal
08-11 07:28:49.421  3365  3413 I jxcore-log: 
,08-11 07:28:49.425  3365  3413 I jxcore-log: # teardown
08-11 07:28:49.425  3365  3413 I jxcore-log: 
,08-11 07:28:49.513  3365  3413 I jxcore-log: # setup
08-11 07:28:49.513  3365  3413 I jxcore-log: 
,08-11 07:28:49.590  3365  3413 I jxcore-log: # 25. #update - do we wait for blocked update
08-11 07:28:49.590  3365  3413 I jxcore-log: 
,08-11 07:28:49.733  3365  3413 I jxcore-log: ok 69 One go and one blocked
08-11 07:28:49.733  3365  3413 I jxcore-log: 
,08-11 07:28:49.734  3365  3413 I jxcore-log: ok 70 All blocked
08-11 07:28:49.734  3365  3413 I jxcore-log: 
,08-11 07:28:49.734  3365  3413 I jxcore-log: ok 71 Still blocked
08-11 07:28:49.734  3365  3413 I jxcore-log: 
,08-11 07:28:50.087  3365  3413 I jxcore-log: ok 72 should be equal
08-11 07:28:50.087  3365  3413 I jxcore-log: 
,08-11 07:28:50.091  3365  3413 I jxcore-log: # teardown
08-11 07:28:50.091  3365  3413 I jxcore-log: 
,08-11 07:28:50.163   873  1715 D AlarmManagerService: Setting time of day to sec=1470893330
,08-11 07:28:50.155   873  1715 W AlarmManagerService: Unable to set rtc to 1470893330: Invalid argument
,08-11 07:28:50.186  3365  3413 I jxcore-log: # setup
08-11 07:28:50.186  3365  3413 I jxcore-log: 
,08-11 07:28:50.238  3365  3413 I jxcore-log: # 26. #update - test that we wait long enough
08-11 07:28:50.238  3365  3413 I jxcore-log: 
,08-11 07:28:51.437  3365  3413 I jxcore-log: ok 73 We waited long enough
08-11 07:28:51.437  3365  3413 I jxcore-log: 
,08-11 07:28:51.589  3365  3413 I jxcore-log: ok 74 should be equal
08-11 07:28:51.589  3365  3413 I jxcore-log: 
,08-11 07:28:51.593  3365  3413 I jxcore-log: # teardown
08-11 07:28:51.593  3365  3413 I jxcore-log: 
,08-11 07:28:51.788  3365  3413 I jxcore-log: # setup
08-11 07:28:51.788  3365  3413 I jxcore-log: 
,08-11 07:28:51.849  3365  3413 I jxcore-log: # 27. #update - test that we pick up new sequences while we wait
08-11 07:28:51.849  3365  3413 I jxcore-log: 
,08-11 07:28:52.321  3365  3413 I jxcore-log: ok 75 Should have gotten same timer promise
08-11 07:28:52.321  3365  3413 I jxcore-log: 
,08-11 07:28:52.321  3365  3413 I jxcore-log: ok 76 Still same timer promise
08-11 07:28:52.321  3365  3413 I jxcore-log: 
,08-11 07:28:53.113  3365  3413 I jxcore-log: ok 77 We waited long enough
08-11 07:28:53.113  3365  3413 I jxcore-log: 
,08-11 07:28:53.193  3365  3413 I jxcore-log: ok 78 should be equal
08-11 07:28:53.193  3365  3413 I jxcore-log: 
,08-11 07:28:53.198  3365  3413 I jxcore-log: # teardown
08-11 07:28:53.198  3365  3413 I jxcore-log: 
,08-11 07:28:53.428  3365  3413 I jxcore-log: # setup
08-11 07:28:53.428  3365  3413 I jxcore-log: 
,08-11 07:28:53.547  3365  3413 I jxcore-log: # 28. Coordinated seq test
08-11 07:28:53.547  3365  3413 I jxcore-log: 
,08-11 07:28:53.756  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:28:53.756  3365  3413 I jxcore-log: 
,08-11 07:28:53.758  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 46150
08-11 07:28:53.758  3365  3413 I jxcore-log: 
,08-11 07:28:53.763  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:28:53.767  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,08-11 07:28:53.767  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-11 07:28:53.768  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 07:28:53.768  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 07:28:53.768  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 07:28:53.768  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:28:53.768  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 07:28:53.772  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 07:28:53.772  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 07:28:53.779  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:28:53.781  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 07:28:53.781  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:28:53.788  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 07:28:53.788  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:28:53.789  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 07:28:53.790  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:28:53.796  3428  3439 D BtGatt.GattService: registerClient() - UUID=a2d72030-d214-4636-9cab-954e786c194d
,08-11 07:28:53.797  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=a2d72030-d214-4636-9cab-954e786c194d, clientIf=5
,08-11 07:28:53.797  3365  3375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 07:28:53.798  3428  3490 D BtGatt.GattService: start scan with filters
,08-11 07:28:53.804  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:28:53.804  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:28:53.804  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-11 07:28:53.804  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 07:28:53.805  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:28:53.816  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:28:53.817  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:28:53.817  3428  3460 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@df798ca
08-11 07:28:53.817  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:28:53.818  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:28:53.826  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:28:53.826  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:53.826  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
08-11 07:28:53.827  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:28:53.835  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 07:28:53.835  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:53.835  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:28:53.836  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:28:53.848  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:28:53.849  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:53.854  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 07:28:53.855  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:54.319  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 07:28:54.319  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 07:28:54.320  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:28:54.331  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 07:28:54.331  3365  3413 I jxcore-log: 
,08-11 07:28:54.362  3365  3413 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-11 07:28:54.366  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 46150, start advertisements: true
,08-11 07:28:54.366  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:28:54.366  3365  3413 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-11 07:28:54.367  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 1
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-11 07:28:54.368  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 07:28:54.369  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 07:28:54.370  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:28:54.372  3428  3469 D BtGatt.GattService: stopScan() - queue size =1
08-11 07:28:54.373  3428  3489 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:28:54.373  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:28:54.373  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:28:54.373  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 07:28:54.374  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 07:28:54.374  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:28:54.374  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 07:28:54.375  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:28:54.380  3428  3469 D BtGatt.GattService: registerClient() - UUID=ed0e5760-80e7-4d19-8be8-876eceeb3582
,08-11 07:28:54.382  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=ed0e5760-80e7-4d19-8be8-876eceeb3582, clientIf=5
,08-11 07:28:54.383  3365  3376 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 07:28:54.383  3428  3489 D BtGatt.GattService: start scan with filters
,08-11 07:28:54.385  3428  3428 D BtGatt.ScanManager: awakened up at time 378554
,08-11 07:28:54.389  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 07:28:54.389  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:28:54.389  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-11 07:28:54.390  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-11 07:28:54.390  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 07:28:54.390  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:28:54.392  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 07:28:54.394  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 07:28:54.394  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-11 07:28:54.396  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 07:28:54.397  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 07:28:54.397  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-11 07:28:54.397  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 07:28:54.398  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 07:28:54.398  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:54.402  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
08-11 07:28:54.404  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 07:28:54.406  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:28:54.408  3428  3490 D BtGatt.GattService: stopScan() - queue size =0
,08-11 07:28:54.409  3365  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 07:28:54.410  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:28:54.410  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:54.410  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:28:54.411  3428  3489 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:28:54.412  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 07:28:54.412  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 07:28:54.412  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-11 07:28:54.412  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-11 07:28:54.412  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 07:28:54.415  3365  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-11 07:28:54.415  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:28:54.417  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:28:54.419  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-11 07:28:54.420  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 07:28:54.420  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-11 07:28:54.421  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-11 07:28:54.421  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:28:54.421  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-11 07:28:54.421  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:28:54.425  3428  3489 D BtGatt.GattService: registerClient() - UUID=f3255ccc-dd87-46d0-b3fd-5b7e80808356
,08-11 07:28:54.425  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=f3255ccc-dd87-46d0-b3fd-5b7e80808356, clientIf=5
08-11 07:28:54.426  3365  3375 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-11 07:28:54.426  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-11 07:28:54.426  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:54.426  3428  3457 D BtGatt.GattService: current time is 378595331369
08-11 07:28:54.427  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:28:54.428  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:28:54.428  3428  3459 D BtGatt.AdvertiseManager: message : 0
,08-11 07:28:54.429  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:28:54.430  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:28:54.430  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:28:54.430  3428  3459 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 07:28:54.437  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:28:54.437  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:54.437  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:28:54.446  3428  3457 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 07:28:54.450  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 07:28:54.450  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:54.450  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:28:54.450  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:28:54.454  3428  3457 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 07:28:54.455  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-11 07:28:54.456  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:28:54.460  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:28:54.462  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 07:28:54.462  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
08-11 07:28:54.462  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:28:54.462  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-11 07:28:54.462  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-11 07:28:54.462  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-11 07:28:54.463  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 07:28:54.463  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-11 07:28:54.463  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:28:54.463  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:54.466  3365  3365 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:28:54.466  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:28:54.470  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 07:28:54.470  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:54.476  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 07:28:54.477  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:54.477  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:28:54.483  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:28:54.483  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:28:54.483  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:28:54.487  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:28:54.487  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:28:54.967  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-11 07:28:54.967  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 07:28:54.968  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:28:54.974  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-11 07:28:54.974  3365  3413 I jxcore-log: 
,08-11 07:29:02.475  3690  3831 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 07:29:02.519  3690  3832 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 07:29:02.572  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:29:02.573  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:29:02.588  3416  3833 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 07:29:02.612  1528  1886 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 07:29:02.612  1528  1886 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:29:02.612  1528  1886 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:02.612  1528  1886 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:02.735  3560  3835 W YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1035 Unknown task tag innertube_config_fetch_charging; aborting...
,08-11 07:29:02.797  1528  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 07:29:02.797  1528  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-11 07:29:02.798  1528  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:29:02.798  1528  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:02.817  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:29:02.817  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:29:02.817  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:02.817  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:02.847  3690  3832 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 07:29:02.848  3690  3831 E BooksSync: Soft error
08-11 07:29:02.848  3690  3831 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:29:02.848  3690  3831 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:29:02.848  3690  3831 E BooksSync: Sync error
08-11 07:29:02.848  3690  3831 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:29:02.848  3690  3831 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:29:02.848  3690  3831 I BooksSync: Finished books sync
,08-11 07:29:02.862   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 386428, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:29:02.873  3416  3833 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 07:29:02.874  3416  3833 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 07:29:03.018  1528  3839 I VacuumService: Vacuum at: now=1470893343018 tag=VacuumService
,08-11 07:29:03.270  1528  3840 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-11 07:29:03.273  1528  3840 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-11 07:29:03.615  1528  3840 W Uploader:  no longer exists, so no auth token.
,08-11 07:29:03.804  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 07:29:03.804  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 07:29:03.805  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:03.805  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:03.819  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:03.819  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:03.819  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:04.728  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 07:29:04.728  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 07:29:04.728  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:04.728  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:04.741  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:04.741  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:04.741  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:05.153  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 07:29:05.153  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 07:29:05.153  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:29:05.153  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:05.177  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:05.177  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:05.177  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:05.527  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 07:29:05.527  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-11 07:29:05.527  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:29:05.527  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:05.541  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:05.541  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:05.541  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:06.157  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 07:29:06.157  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 07:29:06.158  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:29:06.158  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:06.177  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:06.177  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:06.177  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:06.612  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-11 07:29:06.613  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 07:29:06.613  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:29:06.613  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:06.629  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:06.629  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:06.629  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:07.382  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-11 07:29:07.382  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-11 07:29:07.382  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:07.382  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:07.399  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:07.399  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:07.399  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:07.736  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-11 07:29:07.736  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-11 07:29:07.736  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:07.736  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:07.749  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:07.749  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:07.749  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:08.040  1528  3840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-11 07:29:08.041  1528  3840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-11 07:29:08.041  1528  3840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:08.041  1528  3840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:08.062  1528  3840 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:29:08.062  1528  3840 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-11 07:29:08.062  1528  3840 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-11 07:29:08.573  1643  1778 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-11 07:29:08.573  1643  1778 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 07:29:08.619  1528  1528 I ConfigService: onCreate
,08-11 07:29:13.708  1528  1528 I ConfigService: onDestroy
,08-11 07:29:23.189   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:29:29.963   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=414131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:29:33.177  2875  3858 V KeepSync: Connecting to GoogleApiClient,
08-11 07:29:33.178   873  1684 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 07:29:33.210  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:29:33.212  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:29:33.245  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:29:33.245  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:29:33.245  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:33.245  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:33.257  3138  3859 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:29:33.257  3138  3859 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:29:33.257  3138  3859 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	... 12 more
08-11 07:29:33.257  3138  3859 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at fal.a(PG:38)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:29:33.257  3138  3859 E HttpOperation: 	... 14 more
,08-11 07:29:33.359  1528  2667 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 07:29:33.359  1528  2667 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 07:29:33.359  1528  2667 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:33.360  1528  2667 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:33.360  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 07:29:33.360  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:29:33.360  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:29:33.360  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:33.396  3138  3859 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:29:33.396  3138  3859 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at hec.a(PG:42)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at hee.a(PG:102)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at czr.a(PG:65)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at kka.a(PG:108)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:29:33.396  3138  3859 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jdm.a(PG:77),
08-11 07:29:33.396  3138  3859 E HttpOperation: 	... 15 more
08-11 07:29:33.396  3138  3859 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at fal.a(PG:38)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:29:33.396  3138  3859 E HttpOperation: 	... 17 more
08-11 07:29:33.397  3138  3859 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:29:33.397  3138  3859 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	... 15 more
08-11 07:29:33.397  3138  3859 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:29:33.397  3138  3859 E ExperimentLoader: 	... 17 more
,08-11 07:29:33.401  1992  3860 V BaseAuthAsyncOperation: access token request failed
,08-11 07:29:33.402  2875  3858 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 07:29:33.506  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 07:29:33.506  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 07:29:33.506  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:29:33.506  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:29:33.524  2875  3858 E KeepSync: IOException
08-11 07:29:33.524  2875  3858 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 07:29:33.524  2875  3858 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:29:33.524  2875  3858 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 07:29:33.524  2875  3858 E KeepSync: 	... 10 more
,08-11 07:29:33.524  2875  3858 W KeepSync: Sync result 2
,08-11 07:29:33.538   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 388102, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:29:33.579   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 388059, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:29:39.989   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=424157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:29:55.016   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:30:03.709  3690  3864 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 07:30:03.742  3690  3865 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 07:30:03.758  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:30:03.761  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:30:03.791  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:30:03.791  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:30:03.792  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:30:03.792  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:30:03.823  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:30:03.825  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:30:03.855  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:30:03.855  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:30:03.855  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:30:03.855  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:30:03.894  3690  3865 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 07:30:03.896  3690  3864 E BooksSync: Soft error
08-11 07:30:03.896  3690  3864 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:30:03.896  3690  3864 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:30:03.896  3690  3864 E BooksSync: Sync error
08-11 07:30:03.896  3690  3864 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:30:03.896  3690  3864 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:30:03.896  3690  3864 I BooksSync: Finished books sync
,08-11 07:30:03.914   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 447453, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:30:05.056   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=449224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:30:20.069   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=464237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:30:30.122   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=474290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:30:32.944  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:30:32.946  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:30:32.957  3416  3867 V GoogleAuthProtoRequest: [284] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 07:30:32.980  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-11 07:30:32.981  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 07:30:32.981  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:30:32.981  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: [284] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: [284] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 07:30:32.997  3416  3867 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 07:30:36.888  2875  3868 V KeepSync: Connecting to GoogleApiClient
,08-11 07:30:36.888   873  1375 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 07:30:36.947  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 07:30:36.947  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 07:30:36.947  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:30:36.947  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:30:36.974  1992  3869 V BaseAuthAsyncOperation: access token request failed
,08-11 07:30:36.975  2875  3868 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 07:30:37.024  1528  2667 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 07:30:37.024  1528  2667 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 07:30:37.024  1528  2667 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:30:37.024  1528  2667 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:30:37.040  2875  3868 E KeepSync: IOException
08-11 07:30:37.040  2875  3868 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 07:30:37.040  2875  3868 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:30:37.040  2875  3868 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 07:30:37.040  2875  3868 E KeepSync: 	... 10 more
08-11 07:30:37.040  2875  3868 W KeepSync: Sync result 2
,08-11 07:30:37.055   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 480917, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:30:45.135   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=489303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:30:55.189   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=499357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:31:02.895  1528  1955 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 07:31:07.452  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:31:07.454  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:31:07.500  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:31:07.500  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:31:07.501  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:31:07.501  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:31:07.531  3138  3872 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:31:07.531  3138  3872 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:31:07.531  3138  3872 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	... 12 more
08-11 07:31:07.531  3138  3872 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at fal.a(PG:38)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:31:07.531  3138  3872 E HttpOperation: 	... 14 more
,08-11 07:31:07.597  1528  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:31:07.597  1528  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:31:07.597  1528  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:31:07.597  1528  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:31:07.624  3138  3872 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:31:07.624  3138  3872 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at hec.a(PG:42)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at hee.a(PG:102)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at czr.a(PG:65)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at kka.a(PG:108)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:31:07.624  3138  3872 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	... 15 more
08-11 07:31:07.624  3138  3872 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at fal.a(PG:38)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:31:07.624  3138  3872 E HttpOperation: 	... 17 more
,08-11 07:31:07.625  3138  3872 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:31:07.625  3138  3872 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	... 15 more
08-11 07:31:07.625  3138  3872 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:31:07.625  3138  3872 E ExperimentLoader: 	... 17 more
,08-11 07:31:07.762   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 483068, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:31:10.189   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:31:20.229   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=524397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:31:35.242   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=539410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:31:45.295   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=549463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:32:00.309   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=564477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:32:04.806  3690  3878 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 07:32:04.852  3690  3879 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 07:32:04.891  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:04.897  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:04.965  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:32:04.965  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 07:32:04.966  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:32:04.966  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:32:05.001  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:05.004  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:05.040  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:32:05.040  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:32:05.040  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:32:05.040  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:32:05.060  3690  3879 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 07:32:05.061  3690  3878 E BooksSync: Soft error
08-11 07:32:05.061  3690  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:32:05.061  3690  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 07:32:05.061  3690  3878 E BooksSync: Sync error
08-11 07:32:05.061  3690  3878 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:32:05.061  3690  3878 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 07:32:05.061  3690  3878 I BooksSync: Finished books sync
,08-11 07:32:05.071   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 568927, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:32:10.336   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=574504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:32:25.349   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=589517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:32:33.157  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:33.159  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:33.171  3416  3881 V GoogleAuthProtoRequest: [285] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 07:32:33.213  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 07:32:33.214  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-11 07:32:33.214  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:32:33.214  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:32:33.227  3416  3881 W ExperimentUpdateService: [285] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: [285] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 07:32:33.228  3416  3881 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 07:32:35.402   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=599570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:32:43.620  2875  3883 V KeepSync: Connecting to GoogleApiClient
,08-11 07:32:43.621   873  1375 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 07:32:43.661  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:43.663  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:32:43.697  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 07:32:43.697  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 07:32:43.697  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:32:43.698  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:32:43.717  1992  3884 V BaseAuthAsyncOperation: access token request failed
,08-11 07:32:43.718  2875  3883 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 07:32:43.775  1528  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 07:32:43.775  1528  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 07:32:43.775  1528  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:32:43.776  1528  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:32:43.794  2875  3883 E KeepSync: IOException
08-11 07:32:43.794  2875  3883 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 07:32:43.794  2875  3883 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:32:43.794  2875  3883 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 07:32:43.794  2875  3883 E KeepSync: 	... 10 more
08-11 07:32:43.794  2875  3883 W KeepSync: Sync result 2
,08-11 07:32:43.805   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 607644, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:32:50.402   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=614570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:33:00.442   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=624610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:33:07.285  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:07.309  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:07.316  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:07.344  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 07:33:07.344  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 07:33:07.344  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:33:07.344  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:33:07.358  1528  2669 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 07:33:07.358  1528  2669 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 07:33:07.358  1528  2669 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 07:33:07.358  1528  2669 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 07:33:07.358  1528  2669 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 07:33:07.358  1528  2669 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 07:33:07.358  1528  2669 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 07:33:07.363  2590  2621 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 07:33:07.363  2590  2621 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 07:33:07.363  2590  2621 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 07:33:07.363  2590  2621 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 07:33:07.363  2590  2621 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 07:33:07.363  2590  2621 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 07:33:07.363  2590  2621 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 07:33:12.376   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=636543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:33:18.607  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:18.613  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:18.653  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:33:18.654  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:33:18.654  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:33:18.654  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:33:18.677  3138  3895 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:33:18.677  3138  3895 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at czp.a(PG:9087)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:18.677  3138  3895 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	... 12 more
08-11 07:33:18.677  3138  3895 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at fal.a(PG:38)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:33:18.677  3138  3895 E HttpOperation: 	... 14 more
,08-11 07:33:18.885  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:33:18.886  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:33:18.886  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:33:18.886  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:33:18.905  3138  3898 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:33:18.905  3138  3898 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:18.905  3138  3898 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	... 12 more
08-11 07:33:18.905  3138  3898 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at fal.a(PG:38)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:33:18.905  3138  3898 E HttpOperation: 	... 14 more
,08-11 07:33:18.954  1528  2667 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 07:33:18.954  1528  2667 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:33:18.954  1528  2667 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:33:18.955  1528  2667 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:33:18.973  3138  3898 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:33:18.973  3138  3898 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at hec.a(PG:42)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at hee.a(PG:102)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at czr.a(PG:65)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at kka.a(PG:108)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:18.973  3138  3898 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	... 15 more
08-11 07:33:18.973  3138  3898 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at fal.a(PG:38)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:33:18.973  3138  3898 E HttpOperation: 	... 17 more
,08-11 07:33:18.973  3138  3898 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:33:18.973  3138  3898 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	... 15 more
08-11 07:33:18.973  3138  3898 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:33:18.973  3138  3898 E ExperimentLoader: 	... 17 more
,08-11 07:33:19.093   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 511934, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:33:25.482   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=649650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:33:35.163   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=659331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:33:50.536   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=674704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:33:52.110  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:52.113  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:33:52.170  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:33:52.170  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:33:52.171  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:33:52.171  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:33:52.202  3138  3918 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:33:52.202  3138  3918 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:52.202  3138  3918 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	... 12 more
08-11 07:33:52.202  3138  3918 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at fal.a(PG:38)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:33:52.202  3138  3918 E HttpOperation: 	... 14 more
,08-11 07:33:52.279  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:33:52.279  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:33:52.280  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:33:52.280  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:33:52.318  3138  3918 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:33:52.318  3138  3918 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at hec.a(PG:42)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at hee.a(PG:102)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at czr.a(PG:65)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at kka.a(PG:108)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:52.318  3138  3918 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	... 15 more
08-11 07:33:52.318  3138  3918 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at fal.a(PG:38)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:33:52.318  3138  3918 E HttpOperation: 	... 17 more
,08-11 07:33:52.318  3138  3918 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:33:52.318  3138  3918 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: ,	at jdm.a(PG:77)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	... 15 more
08-11 07:33:52.318  3138  3918 E ExperimentLoader: Caused by: faj: BadAuthentication,
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	at jdj.a(PG:4089)
,08-11 07:33:52.318  3138  3918 E ExperimentLoader: 	... 17 more
,08-11 07:33:52.445   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 676043, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:33:53.668  3365  3413 I jxcore-log: not ok 79 We failed - Error: Test timed out
08-11 07:33:53.668  3365  3413 I jxcore-log: 
,08-11 07:33:53.669  3365  3413 I jxcore-log:   ---
08-11 07:33:53.669  3365  3413 I jxcore-log: 
08-11 07:33:53.669  3365  3413 I jxcore-log:     operator: fail
08-11 07:33:53.669  3365  3413 I jxcore-log: 
,08-11 07:33:53.670  3365  3413 I jxcore-log:   ...
08-11 07:33:53.670  3365  3413 I jxcore-log: 
,08-11 07:33:53.688  3365  3413 I jxcore-log: # teardown
08-11 07:33:53.688  3365  3413 I jxcore-log: 
,08-11 07:33:53.774  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:33:53.775  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 07:33:53.775  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-11 07:33:53.775  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 07:33:53.775  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-11 07:33:53.776  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 07:33:53.776  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 07:33:53.778  3365  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-11 07:33:53.778  3365  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 07:33:53.778  3365  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 07:33:53.779  3365  3365 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 07:33:53.779  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 07:33:53.779  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 07:33:53.780  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 07:33:53.780  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 07:33:53.780  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 07:33:53.780  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 07:33:53.780  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 07:33:53.781  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 07:33:53.782  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:33:53.782  3365  3413 D BluetoothLeScanner: could not find callback wrapper
08-11 07:33:53.782  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:33:53.782  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-11 07:33:53.784  3428  3459 D BtGatt.AdvertiseManager: message : 1
08-11 07:33:53.787  3428  3459 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 07:33:53.801  3428  3457 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-11 07:33:53.801  3428  3457 D BtGatt.GattService: Client app is not null!
08-11 07:33:53.802  3428  3439 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:33:53.802  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 07:33:53.803  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-11 07:33:53.803  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 07:33:53.803  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-11 07:33:53.804  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 07:33:53.806  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:33:53.807  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 07:33:53.807  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 07:33:53.809  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-11 07:33:53.811  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:33:53.812  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:33:53.812  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 07:33:53.812  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 07:33:53.813  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:33:53.825  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:33:53.825  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:33:53.825  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:33:53.826  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 07:33:53.829  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:33:53.829  3365  3413 I jxcore-log: 
,08-11 07:33:53.832  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:33:53.833  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:33:53.833  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-11 07:33:53.833  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:33:53.844  3365  3413 I jxcore-log: # setup
08-11 07:33:53.844  3365  3413 I jxcore-log: 
,08-11 07:33:53.982  3365  3413 I jxcore-log: # 29. closeAll can close even when connections open
08-11 07:33:53.982  3365  3413 I jxcore-log: 
,08-11 07:33:54.158  3365  3413 I jxcore-log: ok 80 not possible to connect to the server anymore
08-11 07:33:54.158  3365  3413 I jxcore-log: 
,08-11 07:33:54.167  3365  3413 I jxcore-log: # teardown
08-11 07:33:54.167  3365  3413 I jxcore-log: 
,08-11 07:33:54.273  3365  3413 I jxcore-log: # setup
08-11 07:33:54.273  3365  3413 I jxcore-log: 
,08-11 07:33:54.313  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:33:54.318  3365  3413 I jxcore-log: # 30. closeAll with promise
08-11 07:33:54.318  3365  3413 I jxcore-log: 
,08-11 07:33:54.320  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-11 07:33:54.320  3365  3413 I jxcore-log: 
,08-11 07:33:54.501  3365  3413 I jxcore-log: ok 81 not possible to connect to the server anymore
08-11 07:33:54.501  3365  3413 I jxcore-log: 
,08-11 07:33:54.508  3365  3413 I jxcore-log: # teardown
08-11 07:33:54.508  3365  3413 I jxcore-log: 
,08-11 07:33:54.562  3365  3413 I jxcore-log: # setup
08-11 07:33:54.562  3365  3413 I jxcore-log: 
,08-11 07:33:54.647  3365  3413 I jxcore-log: # 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
08-11 07:33:54.647  3365  3413 I jxcore-log: 
,08-11 07:33:54.814  3365  3413 I jxcore-log: ok 82 Got the right error
08-11 07:33:54.814  3365  3413 I jxcore-log: 
,08-11 07:33:54.826  3365  3413 I jxcore-log: # teardown
08-11 07:33:54.826  3365  3413 I jxcore-log: 
,08-11 07:33:54.905  3365  3413 I jxcore-log: # setup
08-11 07:33:54.905  3365  3413 I jxcore-log: 
,08-11 07:33:54.983  3365  3413 I jxcore-log: # 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
08-11 07:33:54.983  3365  3413 I jxcore-log: 
,08-11 07:33:55.153  3365  3413 I jxcore-log: # teardown
08-11 07:33:55.153  3365  3413 I jxcore-log: 
,08-11 07:33:55.216  3365  3413 I jxcore-log: # setup
08-11 07:33:55.216  3365  3413 I jxcore-log: 
,08-11 07:33:55.289  3365  3413 I jxcore-log: # 33. onPeerLost calls jxcore
08-11 07:33:55.289  3365  3413 I jxcore-log: 
,08-11 07:33:55.363  3365  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 07:33:55.363  3365  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6117443 added. We now have 2 listener(s)
,08-11 07:33:55.369  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 07:33:55.369  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 07:33:55.369  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 07:33:55.370  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 07:33:55.370  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ad1ac0 added. We now have 2 listener(s)
08-11 07:33:55.370  3365  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 07:33:55.370  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 07:33:55.375  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:33:55.383  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 07:33:55.386  3365  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 07:33:55.386  3365  3413 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 07:33:55.387  3365  3413 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
08-11 07:33:55.387  3365  3413 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-11 07:33:55.393  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:33:55.399  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:33:57.390  3365  3413 I jxcore-log: onPeerLost
08-11 07:33:57.390  3365  3413 I jxcore-log: 
,08-11 07:33:57.395  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:33:57.395  3365  3413 I jxcore-log: 
,08-11 07:33:57.408  3365  3413 I jxcore-log: # teardown
08-11 07:33:57.408  3365  3413 I jxcore-log: 
,08-11 07:33:57.423  3365  3413 I jxcore-log: ok 83 check if callback was fired by onPeerLost
08-11 07:33:57.423  3365  3413 I jxcore-log: 
,08-11 07:33:57.424  3365  3413 I jxcore-log: ok 84 check if peerAvailable is false
08-11 07:33:57.424  3365  3413 I jxcore-log: 
,08-11 07:33:57.992  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 07:33:57.992  3365  3413 I jxcore-log: 
,08-11 07:33:57.997  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 07:33:57.997  3365  3413 I jxcore-log: 
,08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:33:58.007  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 07:33:58.011  3365  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 07:33:58.016  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 07:33:58.016  3365  3413 I jxcore-log: 
,08-11 07:33:58.020  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 07:33:58.020  3365  3413 I jxcore-log: 
,08-11 07:33:58.032  3365  3413 I jxcore-log: # setup
08-11 07:33:58.032  3365  3413 I jxcore-log: 
,08-11 07:33:58.035  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:33:58.035  3365  3413 I jxcore-log: 
,08-11 07:33:58.098  3365  3413 I jxcore-log: # 34. onPeerDiscovered calls jxcore
08-11 07:33:58.098  3365  3413 I jxcore-log: 
,08-11 07:33:58.224  3365  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 07:33:58.225  3365  3413 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7738f3e added. We now have 3 listener(s)
,08-11 07:33:58.230  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 07:33:58.230  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 07:33:58.230  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 07:33:58.230  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 07:33:58.230  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9cd119f added. We now have 3 listener(s)
,08-11 07:33:58.231  3365  3413 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 07:33:58.232  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 07:33:58.235  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:33:58.243  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 07:33:58.247  3365  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 07:33:58.247  3365  3413 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 07:33:58.247  3365  3413 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-11 07:33:58.251  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:33:58.255  3365  3365 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 07:33:58.709   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=682877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:34:00.250  3365  3413 I jxcore-log: onPeerDiscovered
08-11 07:34:00.250  3365  3413 I jxcore-log: 
,08-11 07:34:00.255  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:34:00.255  3365  3413 I jxcore-log: 
,08-11 07:34:00.270  3365  3413 I jxcore-log: # teardown
08-11 07:34:00.270  3365  3413 I jxcore-log: 
,08-11 07:34:00.277  3365  3413 I jxcore-log: ok 85 check if callback was fired by onPeerDiscovered
08-11 07:34:00.277  3365  3413 I jxcore-log: 
,08-11 07:34:00.277  3365  3413 I jxcore-log: ok 86 check if peerAvailable is true
08-11 07:34:00.277  3365  3413 I jxcore-log: 
,08-11 07:34:00.376  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 07:34:00.376  3365  3413 I jxcore-log: 
,08-11 07:34:00.382  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 07:34:00.382  3365  3413 I jxcore-log: 
,08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 07:34:00.395  3365  3413 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 07:34:00.398  3365  3413 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 07:34:00.400  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 07:34:00.400  3365  3413 I jxcore-log: 
,08-11 07:34:00.402  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 07:34:00.402  3365  3413 I jxcore-log: 
,08-11 07:34:00.405  3365  3413 I jxcore-log: # setup
08-11 07:34:00.405  3365  3413 I jxcore-log: 
08-11 07:34:00.407  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 07:34:00.407  3365  3413 I jxcore-log: 
,08-11 07:34:00.462  3365  3413 I jxcore-log: # 35. enqueue and run in order
08-11 07:34:00.462  3365  3413 I jxcore-log: 
,08-11 07:34:00.604  3365  3413 I jxcore-log: ok 87 firstPromise setTimeout
08-11 07:34:00.604  3365  3413 I jxcore-log: 
,08-11 07:34:00.608  3365  3413 I jxcore-log: ok 88 firstPromise result
08-11 07:34:00.608  3365  3413 I jxcore-log: 
,08-11 07:34:00.610  3365  3413 I jxcore-log: ok 89 firstPromise testValue
08-11 07:34:00.610  3365  3413 I jxcore-log: 
,08-11 07:34:00.716  3365  3413 I jxcore-log: ok 90 secondPromise setTimeout
08-11 07:34:00.716  3365  3413 I jxcore-log: 
,08-11 07:34:00.720  3365  3413 I jxcore-log: ok 91 secondPromise result
08-11 07:34:00.720  3365  3413 I jxcore-log: 
,08-11 07:34:00.722  3365  3413 I jxcore-log: ok 92 secondPromise testValue
08-11 07:34:00.722  3365  3413 I jxcore-log: 
,08-11 07:34:00.726  3365  3413 I jxcore-log: ok 93 thirdPromise in promise
08-11 07:34:00.726  3365  3413 I jxcore-log: 
,08-11 07:34:00.730  3365  3413 I jxcore-log: ok 94 thirdPromise result
08-11 07:34:00.730  3365  3413 I jxcore-log: 
,08-11 07:34:00.733  3365  3413 I jxcore-log: ok 95 thirdPromise testValue
08-11 07:34:00.733  3365  3413 I jxcore-log: 
,08-11 07:34:00.747  3365  3413 I jxcore-log: # teardown
08-11 07:34:00.747  3365  3413 I jxcore-log: 
,08-11 07:34:00.844  3365  3413 I jxcore-log: # setup
08-11 07:34:00.844  3365  3413 I jxcore-log: 
,08-11 07:34:00.886  3365  3413 I jxcore-log: # 36. enqueueAtTop and run backwards
08-11 07:34:00.886  3365  3413 I jxcore-log: 
,08-11 07:34:00.952  3365  3413 I jxcore-log: ok 96 thirdPromise - first to run
08-11 07:34:00.952  3365  3413 I jxcore-log: 
,08-11 07:34:00.954  3365  3413 I jxcore-log: ok 97 thirdPromise - in resolve
08-11 07:34:00.954  3365  3413 I jxcore-log: 
,08-11 07:34:00.956  3365  3413 I jxcore-log: ok 98 secondPromise - second to run
08-11 07:34:00.956  3365  3413 I jxcore-log: 
,08-11 07:34:00.958  3365  3413 I jxcore-log: ok 99 secondPromise - in catch
08-11 07:34:00.958  3365  3413 I jxcore-log: 
,08-11 07:34:00.959  3365  3413 I jxcore-log: ok 100 firstPromise - third to run
08-11 07:34:00.959  3365  3413 I jxcore-log: 
,08-11 07:34:00.961  3365  3413 I jxcore-log: ok 101 firstPromise - in then
08-11 07:34:00.961  3365  3413 I jxcore-log: 
,08-11 07:34:00.963  3365  3413 I jxcore-log: ok 102 testing promises
08-11 07:34:00.963  3365  3413 I jxcore-log: 
,08-11 07:34:00.968  3365  3413 I jxcore-log: # teardown
08-11 07:34:00.968  3365  3413 I jxcore-log: 
,08-11 07:34:01.050  3365  3413 I jxcore-log: # setup
08-11 07:34:01.050  3365  3413 I jxcore-log: 
,08-11 07:34:01.106  3365  3413 I jxcore-log: # 37. mix enqueue and enqueueAtTop
08-11 07:34:01.106  3365  3413 I jxcore-log: 
,08-11 07:34:01.165  3365  3413 I jxcore-log: ok 103 fourth
08-11 07:34:01.165  3365  3413 I jxcore-log: 
,08-11 07:34:01.168  3365  3413 I jxcore-log: ok 104 fourth
08-11 07:34:01.168  3365  3413 I jxcore-log: 
,08-11 07:34:01.170  3365  3413 I jxcore-log: ok 105 second
08-11 07:34:01.170  3365  3413 I jxcore-log: 
,08-11 07:34:01.172  3365  3413 I jxcore-log: ok 106 secondPromise - in then
08-11 07:34:01.172  3365  3413 I jxcore-log: 
,08-11 07:34:01.276  3365  3413 I jxcore-log: ok 107 first
08-11 07:34:01.276  3365  3413 I jxcore-log: 
,08-11 07:34:01.280  3365  3413 I jxcore-log: ok 108 firstPromise - in catch
08-11 07:34:01.280  3365  3413 I jxcore-log: 
,08-11 07:34:01.283  3365  3413 I jxcore-log: ok 109 third
08-11 07:34:01.283  3365  3413 I jxcore-log: 
,08-11 07:34:01.286  3365  3413 I jxcore-log: ok 110 thirdPromise - in then
08-11 07:34:01.286  3365  3413 I jxcore-log: 
,08-11 07:34:01.289  3365  3413 I jxcore-log: ok 111 testingPromises
08-11 07:34:01.289  3365  3413 I jxcore-log: 
,08-11 07:34:01.301  3365  3413 I jxcore-log: # teardown
08-11 07:34:01.301  3365  3413 I jxcore-log: 
,08-11 07:34:01.384  3365  3413 I jxcore-log: # setup
08-11 07:34:01.384  3365  3413 I jxcore-log: 
,08-11 07:34:01.433  3365  3413 I jxcore-log: # 38. queues handled independently
08-11 07:34:01.433  3365  3413 I jxcore-log: 
,08-11 07:34:01.528  3365  3413 I jxcore-log: ok 112 all short operations completed before the long resolves
08-11 07:34:01.528  3365  3413 I jxcore-log: 
,08-11 07:34:01.533  3365  3413 I jxcore-log: # teardown
08-11 07:34:01.533  3365  3413 I jxcore-log: 
,08-11 07:34:01.604  3365  3413 I jxcore-log: # setup
08-11 07:34:01.604  3365  3413 I jxcore-log: 
,08-11 07:34:01.646  3365  3413 I jxcore-log: # 39. basic
08-11 07:34:01.646  3365  3413 I jxcore-log: 
,08-11 07:34:01.706  3365  3413 I jxcore-log: ok 113 sane
08-11 07:34:01.706  3365  3413 I jxcore-log: 
,08-11 07:34:01.710  3365  3413 I jxcore-log: # teardown
08-11 07:34:01.710  3365  3413 I jxcore-log: 
,08-11 07:34:01.764  3365  3413 I jxcore-log: # setup
08-11 07:34:01.764  3365  3413 I jxcore-log: 
,08-11 07:34:01.848  3365  3413 I jxcore-log: # 40. another
08-11 07:34:01.848  3365  3413 I jxcore-log: 
,08-11 07:34:01.882  3365  3413 I jxcore-log: ok 114 sane
08-11 07:34:01.882  3365  3413 I jxcore-log: 
,08-11 07:34:01.885  3365  3413 I jxcore-log: # teardown
08-11 07:34:01.885  3365  3413 I jxcore-log: 
,08-11 07:34:01.940  3365  3413 I jxcore-log: # setup
08-11 07:34:01.940  3365  3413 I jxcore-log: 
,08-11 07:34:01.990  3365  3413 I jxcore-log: # 41. can pass data in setup
08-11 07:34:01.990  3365  3413 I jxcore-log: 
,08-11 07:34:02.059  3365  3413 I jxcore-log: [{"uuid":"840048a9-09cf-4501-a49f-951c977aea62","data":"custom data"},{"uuid":"6e47f8f6-4ad8-4b73-b142-40385e811f28","data":"custom data"}]
08-11 07:34:02.059  3365  3413 I jxcore-log: 
,08-11 07:34:02.061  3365  3413 I jxcore-log: ok 115 test participant has uuid
08-11 07:34:02.061  3365  3413 I jxcore-log: 
,08-11 07:34:02.062  3365  3413 I jxcore-log: ok 116 participant data matches
08-11 07:34:02.062  3365  3413 I jxcore-log: 
,08-11 07:34:02.062  3365  3413 I jxcore-log: ok 117 test participant has uuid
08-11 07:34:02.062  3365  3413 I jxcore-log: 
08-11 07:34:02.063  3365  3413 I jxcore-log: ok 118 participant data matches
08-11 07:34:02.063  3365  3413 I jxcore-log: 
,08-11 07:34:02.063  3365  3413 I jxcore-log: ok 119 own UUID is found from the participants list
08-11 07:34:02.063  3365  3413 I jxcore-log: 
,08-11 07:34:02.066  3365  3413 I jxcore-log: # teardown
08-11 07:34:02.066  3365  3413 I jxcore-log: 
,08-11 07:34:02.117  3365  3413 I jxcore-log: # setup
08-11 07:34:02.117  3365  3413 I jxcore-log: 
,08-11 07:34:02.169  3365  3413 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
08-11 07:34:02.169  3365  3413 I jxcore-log: 
,08-11 07:34:02.226  3365  3413 I jxcore-log: ok 120 specific error should be returned
08-11 07:34:02.226  3365  3413 I jxcore-log: 
,08-11 07:34:02.230  3365  3413 I jxcore-log: # teardown
08-11 07:34:02.230  3365  3413 I jxcore-log: 
,08-11 07:34:02.288  3365  3413 I jxcore-log: ok 121 error should be null
08-11 07:34:02.288  3365  3413 I jxcore-log: 
,08-11 07:34:02.289  3365  3413 I jxcore-log: ok 122 error should be null
08-11 07:34:02.289  3365  3413 I jxcore-log: 
,08-11 07:34:02.293  3365  3413 I jxcore-log: # setup
08-11 07:34:02.293  3365  3413 I jxcore-log: 
,08-11 07:34:02.344  3365  3413 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
08-11 07:34:02.344  3365  3413 I jxcore-log: 
,08-11 07:34:02.397  3365  3413 I jxcore-log: ok 123 specific error should be returned
08-11 07:34:02.397  3365  3413 I jxcore-log: 
,08-11 07:34:02.401  3365  3413 I jxcore-log: # teardown
08-11 07:34:02.401  3365  3413 I jxcore-log: 
,08-11 07:34:02.450  3365  3413 I jxcore-log: ok 124 error should be null
08-11 07:34:02.450  3365  3413 I jxcore-log: 
,08-11 07:34:02.452  3365  3413 I jxcore-log: ok 125 error should be null
08-11 07:34:02.452  3365  3413 I jxcore-log: 
,08-11 07:34:02.455  3365  3413 I jxcore-log: # setup
08-11 07:34:02.455  3365  3413 I jxcore-log: 
,08-11 07:34:02.567  3365  3413 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
08-11 07:34:02.567  3365  3413 I jxcore-log: 
,08-11 07:34:02.623  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:02.623  3365  3413 I jxcore-log: 
,08-11 07:34:02.627  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 47110
08-11 07:34:02.627  3365  3413 I jxcore-log: 
,08-11 07:34:02.633  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:34:02.633  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-11 07:34:02.633  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-11 07:34:02.633  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:02.636  3365  3413 I jxcore-log: ok 126 error should be null
08-11 07:34:02.636  3365  3413 I jxcore-log: 
,08-11 07:34:02.637  3365  3413 I jxcore-log: ok 127 error should be null
08-11 07:34:02.637  3365  3413 I jxcore-log: 
,08-11 07:34:02.639  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-11 07:34:02.640  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:02.640  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-11 07:34:02.640  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 07:34:02.644  3365  3413 I jxcore-log: ok 128 error should be null
08-11 07:34:02.644  3365  3413 I jxcore-log: 
,08-11 07:34:02.644  3365  3413 I jxcore-log: ok 129 error should be null
08-11 07:34:02.644  3365  3413 I jxcore-log: 
,08-11 07:34:02.651  3365  3413 I jxcore-log: # teardown
08-11 07:34:02.651  3365  3413 I jxcore-log: 
,08-11 07:34:02.749  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:02.749  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:34:02.749  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:34:02.749  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 07:34:02.751  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:34:02.751  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:02.752  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-11 07:34:02.752  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:02.760  3365  3413 I jxcore-log: ok 130 error should be null
08-11 07:34:02.760  3365  3413 I jxcore-log: 
,08-11 07:34:02.761  3365  3413 I jxcore-log: ok 131 error should be null
08-11 07:34:02.761  3365  3413 I jxcore-log: 
,08-11 07:34:02.767  3365  3413 I jxcore-log: # setup
08-11 07:34:02.767  3365  3413 I jxcore-log: 
,08-11 07:34:03.147  3365  3413 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
08-11 07:34:03.147  3365  3413 I jxcore-log: 
,08-11 07:34:03.237  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:03.237  3365  3413 I jxcore-log: 
,08-11 07:34:03.240  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 46861
08-11 07:34:03.240  3365  3413 I jxcore-log: 
,08-11 07:34:03.245  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:34:03.251  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 46150, start advertisements: false
,08-11 07:34:03.251  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:34:03.251  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 07:34:03.251  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 07:34:03.251  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 07:34:03.251  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:03.252  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 07:34:03.254  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 07:34:03.254  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 07:34:03.260  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:34:03.261  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 07:34:03.262  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:34:03.266  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 07:34:03.266  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:34:03.266  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 07:34:03.267  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:03.271  3428  3439 D BtGatt.GattService: registerClient() - UUID=44a45a1e-03c6-48b4-accb-a72003f6d02b
,08-11 07:34:03.272  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=44a45a1e-03c6-48b4-accb-a72003f6d02b, clientIf=5
08-11 07:34:03.272  3365  3375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 07:34:03.273  3428  3438 D BtGatt.GattService: start scan with filters
,08-11 07:34:03.276  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:34:03.276  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:34:03.276  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 07:34:03.276  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-11 07:34:03.277  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:34:03.289  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:34:03.289  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:03.289  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:34:03.291  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:34:03.291  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:34:03.291  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 07:34:03.295  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:34:03.297  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 07:34:03.297  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:03.297  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:34:03.298  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:34:03.301  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:03.321  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:34:03.321  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:03.328  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 07:34:03.329  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:03.793  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-11 07:34:03.793  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:34:03.793  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:03.799  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 07:34:03.799  3365  3413 I jxcore-log: 
,08-11 07:34:03.804  3365  3413 I jxcore-log: ok 132 error should be null
08-11 07:34:03.804  3365  3413 I jxcore-log: 
,08-11 07:34:03.806  3365  3413 I jxcore-log: ok 133 error should be null
08-11 07:34:03.806  3365  3413 I jxcore-log: 
,08-11 07:34:03.815  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:34:03.820  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 46150, start advertisements: false
,08-11 07:34:03.820  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-11 07:34:03.820  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:34:03.820  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:03.820  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK,
,08-11 07:34:03.823  3365  3413 I jxcore-log: ok 134 error should be null
08-11 07:34:03.823  3365  3413 I jxcore-log: 
,08-11 07:34:03.823  3365  3413 I jxcore-log: ok 135 error should be null
08-11 07:34:03.823  3365  3413 I jxcore-log: 
,08-11 07:34:03.828  3365  3413 I jxcore-log: # teardown
08-11 07:34:03.828  3365  3413 I jxcore-log: 
,08-11 07:34:04.277  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:04.277  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:34:04.278  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:04.278  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 07:34:04.278  3365  3413 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 07:34:04.278  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 07:34:04.279  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 07:34:04.279  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 07:34:04.279  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 07:34:04.279  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 07:34:04.280  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 07:34:04.280  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 07:34:04.282  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:04.284  3428  3489 D BtGatt.GattService: stopScan() - queue size =1
08-11 07:34:04.285  3428  3469 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:34:04.286  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 07:34:04.287  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:34:04.288  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 07:34:04.288  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 07:34:04.289  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 07:34:04.293  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:34:04.293  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 07:34:04.294  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 07:34:04.294  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 07:34:04.296  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 07:34:04.298  3428  3428 D BtGatt.ScanManager: awakened up at time 688467
08-11 07:34:04.301  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 07:34:04.301  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 07:34:04.301  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:04.307  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:34:04.307  3365  3413 I jxcore-log: 
,08-11 07:34:04.308  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 07:34:04.308  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:04.309  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:34:04.324  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:34:04.325  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:04.325  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:04.350  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-11 07:34:04.350  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:04.350  3428  3457 D BtGatt.GattService: current time is 688519317243
08-11 07:34:04.351  3428  3457 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -90, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:34:04.352  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:34:04.353  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:34:04.802  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:34:04.803  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:04.803  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:04.807  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-11 07:34:04.807  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:04.807  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:34:04.808  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:04.812  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 07:34:04.812  3365  3413 I jxcore-log: 
,08-11 07:34:04.830  3365  3413 I jxcore-log: ok 136 error should be null
08-11 07:34:04.830  3365  3413 I jxcore-log: 
,08-11 07:34:04.832  3365  3413 I jxcore-log: ok 137 error should be null
08-11 07:34:04.832  3365  3413 I jxcore-log: 
,08-11 07:34:04.840  3365  3413 I jxcore-log: # setup
08-11 07:34:04.840  3365  3413 I jxcore-log: 
,08-11 07:34:04.874  3365  3413 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
08-11 07:34:04.874  3365  3413 I jxcore-log: 
,08-11 07:34:04.990  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:04.990  3365  3413 I jxcore-log: 
,08-11 07:34:04.992  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 45369
08-11 07:34:04.992  3365  3413 I jxcore-log: 
,08-11 07:34:05.004  3365  3413 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-11 07:34:05.009  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 45369, start advertisements: true
08-11 07:34:05.009  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-11 07:34:05.009  3365  3413 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
08-11 07:34:05.009  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-11 07:34:05.009  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 07:34:05.009  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 07:34:05.009  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 07:34:05.009  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:05.010  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-11 07:34:05.011  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 07:34:05.011  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 07:34:05.011  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-11 07:34:05.011  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-11 07:34:05.011  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-11 07:34:05.011  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:05.011  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 07:34:05.026  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 07:34:05.031  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 07:34:05.025  3365  3921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 07:34:05.046  3365  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-11 07:34:05.046  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 07:34:05.047  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 07:34:05.047  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:34:05.050  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-11 07:34:05.050  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 07:34:05.050  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
08-11 07:34:05.050  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:34:05.050  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:34:05.050  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-11 07:34:05.058  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:05.060  3428  3439 D BtGatt.GattService: registerClient() - UUID=5a1862eb-dc11-4e50-8219-bbbd7e2ed667
,08-11 07:34:05.060  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=5a1862eb-dc11-4e50-8219-bbbd7e2ed667, clientIf=5
08-11 07:34:05.061  3365  3376 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-11 07:34:05.062  3428  3459 D BtGatt.AdvertiseManager: message : 0
,08-11 07:34:05.068  3428  3459 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 07:34:05.080  3428  3457 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 07:34:05.088  3428  3457 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 07:34:05.089  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-11 07:34:05.090  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:34:05.094  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:34:05.095  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 07:34:05.095  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-11 07:34:05.095  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-11 07:34:05.096  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-11 07:34:05.096  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 07:34:05.096  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-11 07:34:05.096  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
08-11 07:34:05.098  3365  3365 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:34:05.099  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:34:05.600  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-11 07:34:05.600  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 07:34:05.600  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:05.609  3365  3413 I jxcore-log: ok 138 error should be null
08-11 07:34:05.609  3365  3413 I jxcore-log: 
,08-11 07:34:05.612  3365  3413 I jxcore-log: ok 139 error should be null
08-11 07:34:05.612  3365  3413 I jxcore-log: 
,08-11 07:34:05.625  3365  3413 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-11 07:34:05.632  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 45369, start advertisements: true
,08-11 07:34:05.633  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:34:05.633  3365  3413 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,08-11 07:34:05.633  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-11 07:34:05.634  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-11 07:34:05.638  3428  3459 D BtGatt.AdvertiseManager: message : 1
,08-11 07:34:05.641  3428  3459 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 07:34:05.668  3428  3457 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-11 07:34:05.669  3428  3457 D BtGatt.GattService: Client app is not null!
,08-11 07:34:05.671  3428  3490 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:34:05.672  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-11 07:34:05.673  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:34:05.674  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:34:05.674  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-11 07:34:05.675  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 07:34:05.675  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
,08-11 07:34:05.676  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-11 07:34:05.676  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:34:05.676  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-11 07:34:05.678  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:34:05.687  3428  3438 D BtGatt.GattService: registerClient() - UUID=a9ee00cd-d541-4f15-93ec-79ae5dbe0591
08-11 07:34:05.688  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=a9ee00cd-d541-4f15-93ec-79ae5dbe0591, clientIf=5
08-11 07:34:05.689  3365  3375 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5,
,08-11 07:34:05.693  3428  3459 D BtGatt.AdvertiseManager: message : 0
,08-11 07:34:05.697  3428  3459 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 07:34:05.714  3428  3457 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 07:34:05.725  3428  3457 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 07:34:05.726  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-11 07:34:05.726  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-11 07:34:05.726  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 07:34:05.726  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-11 07:34:05.726  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 07:34:05.726  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-11 07:34:05.727  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 07:34:05.727  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 07:34:05.727  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:05.742  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-11 07:34:05.742  3365  3413 I jxcore-log: 
,08-11 07:34:05.746  3365  3413 I jxcore-log: ok 140 error should be null
08-11 07:34:05.746  3365  3413 I jxcore-log: 
,08-11 07:34:05.749  3365  3413 I jxcore-log: ok 141 error should be null
08-11 07:34:05.749  3365  3413 I jxcore-log: 
,08-11 07:34:05.753  3365  3413 I jxcore-log: # teardown
08-11 07:34:05.753  3365  3413 I jxcore-log: 
,08-11 07:34:06.276  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-11 07:34:06.276  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 07:34:06.277  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-11 07:34:06.277  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 07:34:06.277  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 07:34:06.278  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 07:34:06.278  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 07:34:06.280  3365  3921 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-11 07:34:06.280  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 07:34:06.280  3365  3921 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 07:34:06.280  3365  3921 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 07:34:06.280  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 07:34:06.282  3365  3365 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-11 07:34:06.282  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 07:34:06.283  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 07:34:06.283  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 07:34:06.283  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 07:34:06.283  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 07:34:06.283  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 07:34:06.285  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:34:06.286  3365  3413 D BluetoothLeScanner: could not find callback wrapper
08-11 07:34:06.286  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:34:06.286  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-11 07:34:06.288  3428  3459 D BtGatt.AdvertiseManager: message : 1
08-11 07:34:06.289  3428  3459 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 07:34:06.306  3428  3457 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-11 07:34:06.306  3428  3457 D BtGatt.GattService: Client app is not null!
,08-11 07:34:06.307  3428  3438 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:34:06.308  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 07:34:06.309  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-11 07:34:06.309  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 07:34:06.309  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-11 07:34:06.310  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 07:34:06.311  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:34:06.311  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 07:34:06.311  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 07:34:06.312  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 07:34:06.316  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:06.316  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 07:34:06.316  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 07:34:06.316  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 07:34:06.316  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:06.318  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:34:06.318  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:06.318  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:34:06.318  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.323  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:34:06.323  3365  3413 I jxcore-log: 
,08-11 07:34:06.329  3365  3413 I jxcore-log: ok 142 error should be null
08-11 07:34:06.329  3365  3413 I jxcore-log: 
,08-11 07:34:06.329  3365  3413 I jxcore-log: ok 143 error should be null
08-11 07:34:06.329  3365  3413 I jxcore-log: 
,08-11 07:34:06.336  3365  3413 I jxcore-log: # setup
08-11 07:34:06.336  3365  3413 I jxcore-log: 
,08-11 07:34:06.374  3365  3413 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
08-11 07:34:06.374  3365  3413 I jxcore-log: 
,08-11 07:34:06.485  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:06.485  3365  3413 I jxcore-log: 
,08-11 07:34:06.487  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 46777
08-11 07:34:06.487  3365  3413 I jxcore-log: 
,08-11 07:34:06.491  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:06.492  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:34:06.492  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:06.492  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.496  3365  3413 I jxcore-log: ok 144 error should be null
08-11 07:34:06.496  3365  3413 I jxcore-log: 
,08-11 07:34:06.496  3365  3413 I jxcore-log: ok 145 error should be null
08-11 07:34:06.496  3365  3413 I jxcore-log: 
,08-11 07:34:06.499  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:06.499  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:34:06.499  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:06.499  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.503  3365  3413 I jxcore-log: ok 146 error should be null
08-11 07:34:06.503  3365  3413 I jxcore-log: 
,08-11 07:34:06.503  3365  3413 I jxcore-log: ok 147 error should be null
08-11 07:34:06.503  3365  3413 I jxcore-log: 
,08-11 07:34:06.510  3365  3413 I jxcore-log: # teardown
08-11 07:34:06.510  3365  3413 I jxcore-log: 
,08-11 07:34:06.592  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:06.592  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:34:06.592  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:34:06.593  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.597  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-11 07:34:06.597  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:06.597  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:34:06.597  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.603  3365  3413 I jxcore-log: ok 148 error should be null
08-11 07:34:06.603  3365  3413 I jxcore-log: 
,08-11 07:34:06.603  3365  3413 I jxcore-log: ok 149 error should be null
08-11 07:34:06.603  3365  3413 I jxcore-log: 
,08-11 07:34:06.609  3365  3413 I jxcore-log: # setup
08-11 07:34:06.609  3365  3413 I jxcore-log: 
,08-11 07:34:06.640  3365  3413 I jxcore-log: # 48. #start should fail if called twice in a row
08-11 07:34:06.640  3365  3413 I jxcore-log: 
,08-11 07:34:06.694  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:06.694  3365  3413 I jxcore-log: 
,08-11 07:34:06.697  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 45187
08-11 07:34:06.697  3365  3413 I jxcore-log: 
,08-11 07:34:06.700  3365  3413 I jxcore-log: ok 150 first call should succeed
08-11 07:34:06.700  3365  3413 I jxcore-log: 
,08-11 07:34:06.701  3365  3413 I jxcore-log: ok 151 first call should succeed
08-11 07:34:06.701  3365  3413 I jxcore-log: 
,08-11 07:34:06.703  3365  3413 I jxcore-log: ok 152 specific error should be returned
08-11 07:34:06.703  3365  3413 I jxcore-log: 
,08-11 07:34:06.706  3365  3413 I jxcore-log: # teardown
08-11 07:34:06.706  3365  3413 I jxcore-log: 
,08-11 07:34:06.757  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-11 07:34:06.757  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 07:34:06.757  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:06.757  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.759  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-11 07:34:06.759  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:06.759  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:34:06.759  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:06.764  3365  3413 I jxcore-log: ok 153 error should be null
08-11 07:34:06.764  3365  3413 I jxcore-log: 
,08-11 07:34:06.765  3365  3413 I jxcore-log: ok 154 error should be null
08-11 07:34:06.765  3365  3413 I jxcore-log: 
,08-11 07:34:06.770  3365  3413 I jxcore-log: # setup
08-11 07:34:06.770  3365  3413 I jxcore-log: 
,08-11 07:34:06.817  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:34:06.820  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 07:34:06.820  3365  3413 I jxcore-log: 
,08-11 07:34:06.856  3365  3413 I jxcore-log: # 49. does not emit duplicate discoveryAdvertisingStateUpdate
08-11 07:34:06.856  3365  3413 I jxcore-log: 
,08-11 07:34:06.940  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:06.940  3365  3413 I jxcore-log: 
,08-11 07:34:06.942  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 41333
08-11 07:34:06.942  3365  3413 I jxcore-log: 
,08-11 07:34:06.946  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:34:06.950  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 45369, start advertisements: false
,08-11 07:34:06.950  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:34:06.950  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:34:06.950  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 07:34:06.951  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 07:34:06.951  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:06.951  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 07:34:06.955  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:34:06.955  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 07:34:06.961  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:34:06.962  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 07:34:06.962  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:34:06.967  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 07:34:06.967  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-11 07:34:06.968  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 07:34:06.970  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:06.974  3428  3490 D BtGatt.GattService: registerClient() - UUID=3224b511-a662-4c34-abfd-bcfff222847d
,08-11 07:34:06.975  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=3224b511-a662-4c34-abfd-bcfff222847d, clientIf=5
08-11 07:34:06.976  3365  3375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 07:34:06.976  3428  3469 D BtGatt.GattService: start scan with filters
,08-11 07:34:06.980  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:34:06.980  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:34:06.980  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 07:34:06.980  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 07:34:06.980  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:34:06.983  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 07:34:06.983  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:34:06.983  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 07:34:06.985  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-11 07:34:06.988  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:06.999  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 07:34:07.000  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.000  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:34:07.014  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 07:34:07.014  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.015  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:34:07.015  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:34:07.037  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:34:07.037  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:07.051  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 07:34:07.051  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:07.484  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-11 07:34:07.485  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:34:07.485  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:07.491  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 07:34:07.491  3365  3413 I jxcore-log: 
,08-11 07:34:07.519  3365  3413 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-11 07:34:07.523  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 41333, start advertisements: true
,08-11 07:34:07.523  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-11 07:34:07.523  3365  3413 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4,
,08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
,08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-11 07:34:07.524  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:34:07.524  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 07:34:07.525  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:07.526  3428  3438 D BtGatt.GattService: stopScan() - queue size =1
,08-11 07:34:07.530  3428  3490 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:34:07.530  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:34:07.531  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:34:07.531  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:34:07.531  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 07:34:07.531  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-11 07:34:07.532  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 07:34:07.542  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:34:07.553  3428  3428 D BtGatt.ScanManager: awakened up at time 691721
08-11 07:34:07.553  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 07:34:07.553  3428  3490 D BtGatt.GattService: registerClient() - UUID=c2a21a1f-3973-4965-bbaf-f7241ed4d3c2
08-11 07:34:07.553  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.553  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
08-11 07:34:07.553  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=c2a21a1f-3973-4965-bbaf-f7241ed4d3c2, clientIf=5
08-11 07:34:07.555  3365  3376 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 07:34:07.555  3428  3439 D BtGatt.GattService: start scan with filters
,08-11 07:34:07.558  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:34:07.558  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-11 07:34:07.558  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-11 07:34:07.559  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 07:34:07.559  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 07:34:07.559  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:07.560  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 07:34:07.560  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-11 07:34:07.560  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 07:34:07.560  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 07:34:07.560  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 07:34:07.560  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 07:34:07.560  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 07:34:07.560  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 07:34:07.561  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 07:34:07.561  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:07.562  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-11 07:34:07.562  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:34:07.562  3428  3489 D BtGatt.GattService: stopScan() - queue size =0
08-11 07:34:07.563  3365  3922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 07:34:07.563  3428  3490 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:34:07.564  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:34:07.564  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 07:34:07.564  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-11 07:34:07.564  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 07:34:07.564  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 07:34:07.564  3365  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-11 07:34:07.565  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:34:07.566  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:34:07.569  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-11 07:34:07.569  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 07:34:07.569  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-11 07:34:07.569  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-11 07:34:07.569  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:34:07.569  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-11 07:34:07.570  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:07.573  3428  3490 D BtGatt.GattService: registerClient() - UUID=528f0be3-6bce-4511-99ac-6932242f79ad
,08-11 07:34:07.573  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=528f0be3-6bce-4511-99ac-6932242f79ad, clientIf=5
08-11 07:34:07.573  3365  3375 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-11 07:34:07.573  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-11 07:34:07.573  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.574  3428  3457 D BtGatt.GattService: current time is 691742574960
08-11 07:34:07.574  3428  3457 D BtGatt.GattService: Batch record : [-106, -15, -31, -128, 20, -7, 1, -128, -88, 8, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -110, 32, -43, 2, 2, -29, 21, 62, 92, -15, 58, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:07.574  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -110, 32, -43, 2, 2, -29, 21, 62, 92, -15, 58]
08-11 07:34:07.574  3428  3459 D BtGatt.AdvertiseManager: message : 0
08-11 07:34:07.574  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:07.575  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:34:07.577  3428  3459 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 07:34:07.580  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 07:34:07.581  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:07.581  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:34:07.590  3428  3457 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 07:34:07.594  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 07:34:07.594  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.595  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:34:07.595  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:34:07.599  3428  3457 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 07:34:07.600  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-11 07:34:07.600  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:34:07.601  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:34:07.602  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:07.602  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 07:34:07.602  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:34:07.603  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
08-11 07:34:07.603  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-11 07:34:07.603  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-11 07:34:07.603  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 07:34:07.603  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-11 07:34:07.606  3365  3365 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-11 07:34:07.606  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:34:07.610  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:34:07.610  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:07.615  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 07:34:07.615  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:07.620  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 07:34:07.620  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.620  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:34:07.626  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:34:07.626  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:07.626  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:07.630  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:07.630  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:08.107  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-11 07:34:08.107  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 07:34:08.108  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:08.113  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-11 07:34:08.113  3365  3413 I jxcore-log: 
,08-11 07:34:08.132  3365  3413 I jxcore-log: ok 155 called only once
08-11 07:34:08.132  3365  3413 I jxcore-log: 
,08-11 07:34:08.134  3365  3413 I jxcore-log: ok 156 discovery state matches
08-11 07:34:08.134  3365  3413 I jxcore-log: 
,08-11 07:34:08.136  3365  3413 I jxcore-log: ok 157 advertising state matches
08-11 07:34:08.136  3365  3413 I jxcore-log: 
,08-11 07:34:08.141  3365  3413 I jxcore-log: # teardown
08-11 07:34:08.141  3365  3413 I jxcore-log: 
,08-11 07:34:08.656  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:08.656  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:34:08.656  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-11 07:34:08.656  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 07:34:08.656  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 07:34:08.656  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 07:34:08.656  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 07:34:08.657  3365  3922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 07:34:08.657  3365  3922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 07:34:08.658  3365  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 07:34:08.658  3365  3365 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-11 07:34:08.659  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 07:34:08.659  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 07:34:08.659  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 07:34:08.659  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-11 07:34:08.659  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 07:34:08.659  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 07:34:08.659  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 07:34:08.659  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 07:34:08.660  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:34:08.660  3365  3413 D BluetoothLeScanner: could not find callback wrapper
08-11 07:34:08.660  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:34:08.661  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-11 07:34:08.662  3428  3459 D BtGatt.AdvertiseManager: message : 1
08-11 07:34:08.665  3428  3459 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 07:34:08.686  3428  3457 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-11 07:34:08.687  3428  3457 D BtGatt.GattService: Client app is not null!
08-11 07:34:08.689  3428  3469 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:34:08.689  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 07:34:08.689  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-11 07:34:08.690  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 07:34:08.690  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-11 07:34:08.690  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 07:34:08.695  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:34:08.695  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 07:34:08.695  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,08-11 07:34:08.696  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 07:34:08.700  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:08.700  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:08.700  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 07:34:08.701  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 07:34:08.701  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:08.704  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-11 07:34:08.704  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:34:08.705  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:34:08.705  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:08.712  3365  3413 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
08-11 07:34:08.712  3365  3413 I jxcore-log: 
,08-11 07:34:08.713  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:34:08.713  3365  3413 I jxcore-log: 
,08-11 07:34:08.716  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:34:08.716  3365  3413 I jxcore-log: 
,08-11 07:34:08.727  3365  3413 I jxcore-log: ok 158 error should be null
08-11 07:34:08.727  3365  3413 I jxcore-log: 
,08-11 07:34:08.729  3365  3413 I jxcore-log: ok 159 error should be null
08-11 07:34:08.729  3365  3413 I jxcore-log: 
,08-11 07:34:08.741  3365  3413 I jxcore-log: # setup
08-11 07:34:08.741  3365  3413 I jxcore-log: 
,08-11 07:34:08.771  3365  3413 I jxcore-log: # 50. does not send duplicate availability changes
08-11 07:34:08.771  3365  3413 I jxcore-log: 
,08-11 07:34:08.850  3365  3413 I jxcore-log: ok 160 should be called once
08-11 07:34:08.850  3365  3413 I jxcore-log: 
,08-11 07:34:08.852  3365  3413 I jxcore-log: ok 161 should not have been called more than once
08-11 07:34:08.852  3365  3413 I jxcore-log: 
,08-11 07:34:08.856  3365  3413 I jxcore-log: # teardown
08-11 07:34:08.856  3365  3413 I jxcore-log: 
,08-11 07:34:08.894  3365  3413 I jxcore-log: ok 162 error should be null
08-11 07:34:08.894  3365  3413 I jxcore-log: 
,08-11 07:34:08.895  3365  3413 I jxcore-log: ok 163 error should be null
08-11 07:34:08.895  3365  3413 I jxcore-log: 
,08-11 07:34:08.896  3365  3413 I jxcore-log: # setup
08-11 07:34:08.896  3365  3413 I jxcore-log: 
,08-11 07:34:08.970  3365  3413 I jxcore-log: # 51. can get the network status
08-11 07:34:08.970  3365  3413 I jxcore-log: 
,08-11 07:34:09.010  3365  3413 I jxcore-log: ok 164 network status should have certain non-empty properties
08-11 07:34:09.010  3365  3413 I jxcore-log: 
,08-11 07:34:09.012  3365  3413 I jxcore-log: # teardown
08-11 07:34:09.012  3365  3413 I jxcore-log: 
,08-11 07:34:09.072  3365  3413 I jxcore-log: ok 165 error should be null
08-11 07:34:09.072  3365  3413 I jxcore-log: 
,08-11 07:34:09.073  3365  3413 I jxcore-log: ok 166 error should be null
08-11 07:34:09.073  3365  3413 I jxcore-log: 
,08-11 07:34:09.076  3365  3413 I jxcore-log: # setup
08-11 07:34:09.076  3365  3413 I jxcore-log: 
,08-11 07:34:09.140  3365  3413 I jxcore-log: # 52. wifi peer is marked unavailable if announcements stop
08-11 07:34:09.140  3365  3413 I jxcore-log: 
,08-11 07:34:09.200  3365  3413 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
08-11 07:34:09.200  3365  3413 I jxcore-log: 
,08-11 07:34:09.202  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:34:09.217  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 07:34:09.217  3365  3413 I jxcore-log: 
,08-11 07:34:09.231  3365  3413 I jxcore-log: ok 167 host address should match
08-11 07:34:09.231  3365  3413 I jxcore-log: 
,08-11 07:34:09.232  3365  3413 I jxcore-log: ok 168 port should match
08-11 07:34:09.232  3365  3413 I jxcore-log: 
,08-11 07:34:11.199  3365  3413 I jxcore-log: ok 169 host address should be null
08-11 07:34:11.199  3365  3413 I jxcore-log: 
,08-11 07:34:11.202  3365  3413 I jxcore-log: ok 170 port should should be null
08-11 07:34:11.202  3365  3413 I jxcore-log: 
,08-11 07:34:11.220  3365  3413 I jxcore-log: # teardown
08-11 07:34:11.220  3365  3413 I jxcore-log: 
,08-11 07:34:11.320  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:34:11.320  3365  3413 I jxcore-log: 
,08-11 07:34:11.323  3365  3413 I jxcore-log: ok 171 error should be null
08-11 07:34:11.323  3365  3413 I jxcore-log: 
,08-11 07:34:11.323  3365  3413 I jxcore-log: ok 172 error should be null
08-11 07:34:11.323  3365  3413 I jxcore-log: 
08-11 07:34:11.325  3365  3413 I jxcore-log: # setup
08-11 07:34:11.325  3365  3413 I jxcore-log: 
,08-11 07:34:11.382  3365  3413 I jxcore-log: # 53. Can call start/stopListeningForAdvertisements
08-11 07:34:11.382  3365  3413 I jxcore-log: 
,08-11 07:34:11.434  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:34:11.440  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 41333, start advertisements: false
,08-11 07:34:11.440  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-11 07:34:11.440  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 07:34:11.441  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 07:34:11.442  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 07:34:11.442  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:11.442  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 07:34:11.451  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:34:11.451  3365  3413 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 07:34:11.463  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:34:11.465  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 07:34:11.466  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:34:11.475  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 07:34:11.475  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:34:11.475  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 07:34:11.477  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:11.482  3428  3469 D BtGatt.GattService: registerClient() - UUID=e09fb425-3b4e-48f9-ad71-c37db0f75717
,08-11 07:34:11.482  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=e09fb425-3b4e-48f9-ad71-c37db0f75717, clientIf=5
,08-11 07:34:11.483  3365  3375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 07:34:11.484  3428  3489 D BtGatt.GattService: start scan with filters
,08-11 07:34:11.492  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:34:11.492  3428  3460 D BtGatt.ScanManager: handling starting scan
08-11 07:34:11.492  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:34:11.492  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 07:34:11.492  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 07:34:11.501  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:34:11.501  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:34:11.502  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:11.502  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-11 07:34:11.502  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:34:11.503  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:34:11.509  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:34:11.517  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:11.522  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 07:34:11.522  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:11.523  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
,08-11 07:34:11.523  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:34:11.545  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 07:34:11.545  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:11.555  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 07:34:11.555  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:12.004  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 07:34:12.004  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:34:12.005  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:12.009  3365  3413 I jxcore-log: ok 173 Can call startListeningForAdvertisements without error
08-11 07:34:12.009  3365  3413 I jxcore-log: 
,08-11 07:34:12.012  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-11 07:34:12.012  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-11 07:34:12.013  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-11 07:34:12.013  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
,08-11 07:34:12.013  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 07:34:12.013  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 07:34:12.016  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:34:12.018  3428  3469 D BtGatt.GattService: stopScan() - queue size =1
08-11 07:34:12.021  3428  3489 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:34:12.022  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:34:12.022  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 07:34:12.022  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 07:34:12.023  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 07:34:12.023  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 07:34:12.026  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:12.027  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:12.031  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 07:34:12.031  3365  3413 I jxcore-log: 
,08-11 07:34:12.036  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 07:34:12.036  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:12.036  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:34:12.051  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:34:12.051  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:12.051  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:12.057  3428  3428 D BtGatt.ScanManager: awakened up at time 696225
,08-11 07:34:12.076  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:34:12.077  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:12.077  3428  3457 D BtGatt.GattService: current time is 696245856607
,08-11 07:34:12.077  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:34:12.078  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:34:12.528  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:34:12.529  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:34:12.529  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:12.534  3365  3413 I jxcore-log: ok 174 Can call stopListeningForAdvertisements without error
08-11 07:34:12.534  3365  3413 I jxcore-log: 
,08-11 07:34:12.546  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 07:34:12.546  3365  3413 I jxcore-log: 
,08-11 07:34:12.550  3365  3413 I jxcore-log: # teardown
08-11 07:34:12.550  3365  3413 I jxcore-log: 
,08-11 07:34:12.975  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:34:12.975  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements,
,08-11 07:34:12.976  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-11 07:34:12.976  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:12.981  3365  3413 I jxcore-log: ok 175 Should be able to call stopListeningForAdvertisements in teardown
08-11 07:34:12.981  3365  3413 I jxcore-log: 
,08-11 07:34:12.983  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:34:12.984  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 07:34:12.984  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:34:12.984  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:34:12.990  3365  3413 I jxcore-log: ok 176 Should be able to call stopAdvertisingAndListening in teardown
08-11 07:34:12.990  3365  3413 I jxcore-log: 
,08-11 07:34:12.996  3365  3413 I jxcore-log: # setup
08-11 07:34:12.996  3365  3413 I jxcore-log: 
,08-11 07:34:13.053  3365  3413 I jxcore-log: # 54. Client to server request coordinated
08-11 07:34:13.053  3365  3413 I jxcore-log: 
,08-11 07:34:13.162  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:34:13.162  3365  3413 I jxcore-log: 
,08-11 07:34:13.167  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 41335
08-11 07:34:13.167  3365  3413 I jxcore-log: 
,08-11 07:34:13.170  3365  3413 I jxcore-log: ok 177 error should be null
08-11 07:34:13.170  3365  3413 I jxcore-log: 
,08-11 07:34:13.171  3365  3413 I jxcore-log: ok 178 error should be null
08-11 07:34:13.171  3365  3413 I jxcore-log: 
,08-11 07:34:13.218  3365  3413 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-11 07:34:13.221  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 41335, start advertisements: true
,08-11 07:34:13.221  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-11 07:34:13.221  3365  3413 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 07:34:13.221  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 07:34:13.221  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 07:34:13.222  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 07:34:13.222  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 07:34:13.222  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-11 07:34:13.222  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:34:13.222  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 07:34:13.222  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-11 07:34:13.223  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 07:34:13.223  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 07:34:13.223  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 07:34:13.223  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 07:34:13.224  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:34:13.228  3365  3924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 07:34:13.235  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-11 07:34:13.235  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 07:34:13.235  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
08-11 07:34:13.235  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:34:13.235  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-11 07:34:13.236  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-11 07:34:13.238  3365  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-11 07:34:13.239  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:13.246  3428  3490 D BtGatt.GattService: registerClient() - UUID=dd9112e2-9ed0-4d78-9628-7e170d976758,
08-11 07:34:13.247  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=dd9112e2-9ed0-4d78-9628-7e170d976758, clientIf=5
08-11 07:34:13.248  3365  3376 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-11 07:34:13.249  3428  3459 D BtGatt.AdvertiseManager: message : 0
,08-11 07:34:13.251  3428  3459 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 07:34:13.260  3428  3457 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 07:34:13.265  3428  3457 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 07:34:13.266  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-11 07:34:13.266  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:34:13.267  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:34:13.268  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:13.268  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 07:34:13.268  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-11 07:34:13.268  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-11 07:34:13.268  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-11 07:34:13.268  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 07:34:13.268  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-11 07:34:13.271  3365  3365 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:34:13.271  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 07:34:13.772  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-11 07:34:13.772  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 07:34:13.773  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:13.782  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-11 07:34:13.782  3365  3413 I jxcore-log: 
,08-11 07:34:13.795  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:34:13.801  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 41335, start advertisements: false
,08-11 07:34:13.801  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:34:13.802  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
08-11 07:34:13.802  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 07:34:13.802  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 07:34:13.803  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 07:34:13.803  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-11 07:34:13.804  3428  3459 D BtGatt.AdvertiseManager: message : 1
08-11 07:34:13.805  3428  3459 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 07:34:13.820  3428  3457 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-11 07:34:13.821  3428  3457 D BtGatt.GattService: Client app is not null!
,08-11 07:34:13.825  3428  3469 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:34:13.826  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-11 07:34:13.827  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:34:13.827  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-11 07:34:13.827  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-11 07:34:13.828  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 07:34:13.837  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:13.838  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:34:13.841  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:34:13.851  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 07:34:13.851  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:34:13.851  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 07:34:13.853  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:34:13.856  3428  3489 D BtGatt.GattService: registerClient() - UUID=4017dced-acff-4d92-b75f-c5b81090fa59
,08-11 07:34:13.856  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=4017dced-acff-4d92-b75f-c5b81090fa59, clientIf=5
08-11 07:34:13.857  3365  3375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 07:34:13.858  3428  3439 D BtGatt.GattService: start scan with filters
,08-11 07:34:13.864  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:34:13.864  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:34:13.865  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:34:13.866  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-11 07:34:13.866  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 07:34:13.869  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 07:34:13.869  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:34:13.869  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:34:13.871  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:34:13.875  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:34:13.879  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:34:13.879  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:13.880  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:34:13.896  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 07:34:13.896  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:13.897  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:34:13.897  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:34:13.942  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 07:34:13.942  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:13.960  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 07:34:13.961  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:14.370  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 07:34:14.371  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:34:14.371  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:34:14.379  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 07:34:14.379  3365  3413 I jxcore-log: 
,08-11 07:34:14.385  3365  3413 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
08-11 07:34:14.385  3365  3413 I jxcore-log: 
,08-11 07:34:15.469  3428  3428 D BtGatt.ScanManager: awakened up at time 699637
08-11 07:34:15.471  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:15.519  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-11 07:34:15.519  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:15.520  3428  3457 D BtGatt.GattService: current time is 699688485335
,08-11 07:34:15.521  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -91, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -70, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -90, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -65, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -106, -15, -31, -128, 20, -7, 1, -128, -84, 12, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -103, 32, -43, 2, 2, -29, 21, 62, 111, -119, 0, 0]
08-11 07:34:15.522  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:34:15.523  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-11 07:34:15.524  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:34:15.525  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:34:15.526  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:34:15.527  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:15.527  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -103, 32, -43, 2, 2, -29, 21, 62, 111, -119, 0]
,08-11 07:34:17.022  3428  3428 D BtGatt.ScanManager: awakened up at time 701190
,08-11 07:34:17.026  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:17.036  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:34:17.037  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:18.540  3428  3428 D BtGatt.ScanManager: awakened up at time 702709
,08-11 07:34:18.544  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:18.556  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:18.556  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:20.056  3428  3428 D BtGatt.ScanManager: awakened up at time 704224
,08-11 07:34:20.058  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:20.110  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-11 07:34:20.110  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:20.110  3428  3457 D BtGatt.GattService: current time is 704279224022
,08-11 07:34:20.111  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -98, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -70, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -92, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:34:20.112  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:34:20.113  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:34:20.114  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:34:20.115  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:20.116  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:34:21.614  3428  3428 D BtGatt.ScanManager: awakened up at time 705782
08-11 07:34:21.616  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:21.627  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:21.627  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:23.130  3428  3428 D BtGatt.ScanManager: awakened up at time 707298
,08-11 07:34:23.135  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:23.143  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:23.143  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:24.646  3428  3428 D BtGatt.ScanManager: awakened up at time 708814
,08-11 07:34:24.651  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:24.703  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-11 07:34:24.704  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:24.704  3428  3457 D BtGatt.GattService: current time is 708873138542
,08-11 07:34:24.705  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -95, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -68, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -72, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-11 07:34:24.706  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:34:24.707  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-11 07:34:24.708  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:34:24.709  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-11 07:34:24.710  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:34:26.208  3428  3428 D BtGatt.ScanManager: awakened up at time 710376
,08-11 07:34:26.210  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:26.242  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:34:26.243  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:26.243  3428  3457 D BtGatt.GattService: current time is 710411918383
08-11 07:34:26.243  3428  3457 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -68, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-11 07:34:26.244  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-11 07:34:27.746  3428  3428 D BtGatt.ScanManager: awakened up at time 711914
,08-11 07:34:27.749  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:27.759  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:27.760  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:29.263  3428  3428 D BtGatt.ScanManager: awakened up at time 713432
,08-11 07:34:29.266  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:29.327  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-11 07:34:29.327  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:29.327  3428  3457 D BtGatt.GattService: current time is 713496122284
,08-11 07:34:29.328  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -71, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:34:29.329  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:34:29.330  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:34:29.330  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:34:29.331  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:34:29.332  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:34:30.832  3428  3428 D BtGatt.ScanManager: awakened up at time 715000
,08-11 07:34:30.834  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:30.866  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-11 07:34:30.867  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:30.867  3428  3457 D BtGatt.GattService: current time is 715036123375
08-11 07:34:30.868  3428  3457 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -65, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -65, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -90, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:34:30.869  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:30.870  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:34:30.870  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:34:32.370  3428  3428 D BtGatt.ScanManager: awakened up at time 716538
,08-11 07:34:32.374  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:32.384  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:34:32.384  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:33.886  3428  3428 D BtGatt.ScanManager: awakened up at time 718055
,08-11 07:34:33.889  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:33.914  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-11 07:34:33.914  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:33.915  3428  3457 D BtGatt.GattService: current time is 718083732428
08-11 07:34:33.915  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-11 07:34:33.917  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:34:35.420  3428  3428 D BtGatt.ScanManager: awakened up at time 719588
,08-11 07:34:35.423  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:35.478  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:34:35.478  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:35.479  3428  3457 D BtGatt.GattService: current time is 719647562011
,08-11 07:34:35.480  3428  3457 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -69, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -91, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -104, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -78, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -64, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-11 07:34:35.481  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:34:35.482  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:34:35.487  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:35.489  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:35.491  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:34:35.492  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:34:36.980  3428  3428 D BtGatt.ScanManager: awakened up at time 721149
,08-11 07:34:36.983  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:36.995  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:36.996  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:38.497  3428  3428 D BtGatt.ScanManager: awakened up at time 722666
,08-11 07:34:38.501  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:38.512  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:38.512  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:40.019  3428  3428 D BtGatt.ScanManager: awakened up at time 724187
,08-11 07:34:40.021  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:40.074  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:34:40.075  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:40.076  3428  3457 D BtGatt.GattService: current time is 724244391375
,08-11 07:34:40.076  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -96, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -68, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -89, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -91, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:40.077  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:34:40.078  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-11 07:34:40.079  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-11 07:34:40.080  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:40.081  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:34:40.082  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:40.629   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=724797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:34:41.578  3428  3428 D BtGatt.ScanManager: awakened up at time 725746
,08-11 07:34:41.580  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:41.592  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:41.593  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:43.094  3428  3428 D BtGatt.ScanManager: awakened up at time 727262
,08-11 07:34:43.099  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:43.109  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:43.110  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:44.609  3428  3428 D BtGatt.ScanManager: awakened up at time 728777
,08-11 07:34:44.610  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:44.658  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-11 07:34:44.658  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:44.659  3428  3457 D BtGatt.GattService: current time is 728827661832
08-11 07:34:44.660  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -64, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -91, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -65, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:34:44.661  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:34:44.662  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:44.663  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:34:44.664  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-11 07:34:44.665  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-11 07:34:44.665  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:34:46.161  3428  3428 D BtGatt.ScanManager: awakened up at time 730329
,08-11 07:34:46.165  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:46.199  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-11 07:34:46.199  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:46.200  3428  3457 D BtGatt.GattService: current time is 730368752610
,08-11 07:34:46.200  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -91, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:34:46.201  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:34:46.202  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:34:47.701  3428  3428 D BtGatt.ScanManager: awakened up at time 731870
,08-11 07:34:47.705  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:47.716  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:47.716  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:49.218  3428  3428 D BtGatt.ScanManager: awakened up at time 733386
,08-11 07:34:49.222  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:49.256  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-11 07:34:49.256  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:49.257  3428  3457 D BtGatt.GattService: current time is 733425580467
,08-11 07:34:49.257  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -69, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:34:49.258  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:34:49.259  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:34:50.759  3428  3428 D BtGatt.ScanManager: awakened up at time 734927
,08-11 07:34:50.763  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:50.795  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-11 07:34:50.796  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:50.796  3428  3457 D BtGatt.GattService: current time is 734964987964
,08-11 07:34:50.797  3428  3457 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -64, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -64, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -91, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -97, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:34:50.798  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-11 07:34:50.799  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:34:50.800  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:34:50.801  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:52.298  3428  3428 D BtGatt.ScanManager: awakened up at time 736466
,08-11 07:34:52.302  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:52.313  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:52.313  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:53.815  3428  3428 D BtGatt.ScanManager: awakened up at time 737983
,08-11 07:34:53.820  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:53.851  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:34:53.851  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:53.851  3428  3457 D BtGatt.GattService: current time is 738020277591
,08-11 07:34:53.852  3428  3457 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -97, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:53.852  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:55.354  3428  3428 D BtGatt.ScanManager: awakened up at time 739522
,08-11 07:34:55.359  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:55.413  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-11 07:34:55.413  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:55.414  3428  3457 D BtGatt.GattService: current time is 739582628528
,08-11 07:34:55.415  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -89, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -89, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:55.416  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:34:55.417  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:34:55.418  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:34:55.419  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:34:55.420  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:34:55.420  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:34:55.642   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=739810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:34:56.916  3428  3428 D BtGatt.ScanManager: awakened up at time 741084
,08-11 07:34:56.919  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:56.931  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:56.932  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:58.061  3428  3428 D BtGatt.ScanManager: awakened up at time 742230
,08-11 07:34:58.064  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:58.084  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:34:58.084  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:34:58.274  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:34:58.280  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:34:58.334  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:34:58.334  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:34:58.334  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:34:58.334  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:34:58.375  3138  3928 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:34:58.375  3138  3928 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:34:58.375  3138  3928 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	... 12 more
08-11 07:34:58.375  3138  3928 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at fal.a(PG:38)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:34:58.375  3138  3928 E HttpOperation: 	... 14 more
,08-11 07:34:58.465  1528  2665 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:34:58.465  1528  2665 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:34:58.465  1528  2665 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:34:58.465  1528  2665 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:34:58.491  3138  3928 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:34:58.491  3138  3928 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at hec.a(PG:42)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at hee.a(PG:102)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at czr.a(PG:65)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at kka.a(PG:108)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:34:58.491  3138  3928 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	... 15 more
,08-11 07:34:58.491  3138  3928 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at fal.a(PG:38)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:34:58.491  3138  3928 E HttpOperation: 	... 17 more
08-11 07:34:58.492  3138  3928 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:34:58.492  3138  3928 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	... 15 more
08-11 07:34:58.492  3138  3928 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:34:58.492  3138  3928 E ExperimentLoader: 	... 17 more
,08-11 07:34:58.661   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 742178, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:34:58.683  3428  3428 D BtGatt.ScanManager: awakened up at time 742851
,08-11 07:34:58.685  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:34:58.715  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-11 07:34:58.716  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:34:58.716  3428  3457 D BtGatt.GattService: current time is 742885083545
08-11 07:34:58.716  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,08-11 07:34:58.717  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:34:58.717  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:35:00.224  3428  3428 D BtGatt.ScanManager: awakened up at time 744392
,08-11 07:35:00.227  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:00.265  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:00.265  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:00.266  3428  3457 D BtGatt.GattService: current time is 744434635991
,08-11 07:35:00.266  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -87, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -91, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -81, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-11 07:35:00.267  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:00.267  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:35:00.268  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:35:00.269  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:35:00.269  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:35:00.270  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:35:01.770  3428  3428 D BtGatt.ScanManager: awakened up at time 745939
,08-11 07:35:01.773  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:01.785  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:01.785  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:03.288  3428  3428 D BtGatt.ScanManager: awakened up at time 747457
,08-11 07:35:03.293  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:03.303  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:03.304  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-11 07:35:04.808  3428  3428 D BtGatt.ScanManager: awakened up at time 748976
,08-11 07:35:04.812  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:04.864  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-11 07:35:04.865  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:04.865  3428  3457 D BtGatt.GattService: current time is 749033908376
,08-11 07:35:04.866  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -64, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -90, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -99, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,08-11 07:35:04.868  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:04.871  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:04.872  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-11 07:35:04.873  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:35:04.875  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:35:04.876  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:35:05.696   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=749864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:35:06.368  3428  3428 D BtGatt.ScanManager: awakened up at time 750537
,08-11 07:35:06.371  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:06.382  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:06.382  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:07.884  3428  3428 D BtGatt.ScanManager: awakened up at time 752052
,08-11 07:35:07.892  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:07.901  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:07.902  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:09.406  3428  3428 D BtGatt.ScanManager: awakened up at time 753574
,08-11 07:35:09.409  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:09.457  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:09.457  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:09.457  3428  3457 D BtGatt.GattService: current time is 753626330031
08-11 07:35:09.458  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -92, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -75, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -89, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,08-11 07:35:09.459  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:09.460  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:35:09.461  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-11 07:35:09.462  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:09.463  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:35:09.465  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-11 07:35:10.962  3428  3428 D BtGatt.ScanManager: awakened up at time 755131
,08-11 07:35:10.965  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:11.017  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:11.017  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:11.018  3428  3457 D BtGatt.GattService: current time is 755186590291
08-11 07:35:11.019  3428  3457 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -89, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -90, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -97, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -76, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -89, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:35:11.020  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:35:11.021  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:11.022  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:35:11.023  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-11 07:35:11.024  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:11.026  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:35:12.522  3428  3428 D BtGatt.ScanManager: awakened up at time 756690
,08-11 07:35:12.524  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:12.535  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:35:12.535  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:14.038  3428  3428 D BtGatt.ScanManager: awakened up at time 758207
,08-11 07:35:14.044  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:14.071  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:35:14.071  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:14.072  3428  3457 D BtGatt.GattService: current time is 758240573408
08-11 07:35:14.072  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-11 07:35:14.073  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:35:15.579  3428  3428 D BtGatt.ScanManager: awakened up at time 759747
,08-11 07:35:15.582  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:15.636  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-11 07:35:15.636  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:15.636  3428  3457 D BtGatt.GattService: current time is 759805253199
,08-11 07:35:15.637  3428  3457 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -87, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -91, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -91, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -106, -15, -31, -128, 20, -7, 1, -128, -85, 21, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -43, 32, -43, 2, 2, -29, 21, 62, -55, 0, 14, 0, 116, -43, -111, -91, -20, -29, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:15.638  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-11 07:35:15.639  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:35:15.641  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:35:15.642  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:35:15.643  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:35:15.644  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, -43, 32, -43, 2, 2, -29, 21, 62, -55, 0, 14]
08-11 07:35:15.646  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:35:17.139  3428  3428 D BtGatt.ScanManager: awakened up at time 761308
08-11 07:35:17.144  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:17.153  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:17.153  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:18.656  3428  3428 D BtGatt.ScanManager: awakened up at time 762825
,08-11 07:35:18.659  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:18.670  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:18.670  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:20.172  3428  3428 D BtGatt.ScanManager: awakened up at time 764340
,08-11 07:35:20.174  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:20.229  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-11 07:35:20.230  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:20.230  3428  3457 D BtGatt.GattService: current time is 764399137146
08-11 07:35:20.231  3428  3457 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -63, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -91, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -63, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -90, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:35:20.232  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:20.233  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-11 07:35:20.235  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:35:20.236  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:35:20.238  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:35:20.722   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=764890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE},
,08-11 07:35:21.734  3428  3428 D BtGatt.ScanManager: awakened up at time 765902
,08-11 07:35:21.736  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:21.747  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:21.747  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:23.250  3428  3428 D BtGatt.ScanManager: awakened up at time 767418
,08-11 07:35:23.253  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:23.266  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:35:23.266  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:24.768  3428  3428 D BtGatt.ScanManager: awakened up at time 768937
,08-11 07:35:24.774  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:24.828  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:24.828  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:24.829  3428  3457 D BtGatt.GattService: current time is 768997531667
,08-11 07:35:24.832  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -69, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -96, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -74, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -67, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -88, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -88, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,08-11 07:35:24.834  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:35:24.836  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:35:24.838  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:24.842  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-11 07:35:24.843  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-11 07:35:24.844  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-11 07:35:26.332  3428  3428 D BtGatt.ScanManager: awakened up at time 770500
,08-11 07:35:26.334  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:26.365  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-11 07:35:26.366  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:26.366  3428  3457 D BtGatt.GattService: current time is 770534662653
,08-11 07:35:26.366  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -95, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -66, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-11 07:35:26.366  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:35:26.366  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-11 07:35:27.874  3428  3428 D BtGatt.ScanManager: awakened up at time 772042
,08-11 07:35:27.877  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:27.888  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:27.888  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:29.391  3428  3428 D BtGatt.ScanManager: awakened up at time 773559
,08-11 07:35:29.393  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:29.421  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-11 07:35:29.421  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:29.421  3428  3457 D BtGatt.GattService: current time is 773590310874
08-11 07:35:29.422  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -71, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -88, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-11 07:35:29.422  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:35:29.423  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:35:29.423  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:35:29.424  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:35:30.762   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=774930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:35:30.926  3428  3428 D BtGatt.ScanManager: awakened up at time 775095
08-11 07:35:30.930  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:30.961  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:35:30.961  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:30.962  3428  3457 D BtGatt.GattService: current time is 775130634778
,08-11 07:35:30.962  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -71, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-11 07:35:30.963  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:35:32.465  3428  3428 D BtGatt.ScanManager: awakened up at time 776633
,08-11 07:35:32.470  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:32.478  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:35:32.478  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:33.981  3428  3428 D BtGatt.ScanManager: awakened up at time 778150
,08-11 07:35:33.984  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:34.020  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-11 07:35:34.020  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:34.021  3428  3457 D BtGatt.GattService: current time is 778189855291
08-11 07:35:34.022  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:35:34.023  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:34.025  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:34.026  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:35.524  3428  3428 D BtGatt.ScanManager: awakened up at time 779692
,08-11 07:35:35.526  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:35.585  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:35.585  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:35.585  3428  3457 D BtGatt.GattService: current time is 779754280811
,08-11 07:35:35.586  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -69, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -91, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:35.587  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:35:35.588  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:35:35.589  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:35:35.590  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:35.591  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-11 07:35:35.592  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:37.087  3428  3428 D BtGatt.ScanManager: awakened up at time 781255
,08-11 07:35:37.089  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:37.100  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:37.101  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:38.605  3428  3428 D BtGatt.ScanManager: awakened up at time 782774
,08-11 07:35:38.608  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:38.619  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:38.619  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:40.120  3428  3428 D BtGatt.ScanManager: awakened up at time 784288
,08-11 07:35:40.123  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:40.176  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-11 07:35:40.176  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:40.176  3428  3457 D BtGatt.GattService: current time is 784345308560
08-11 07:35:40.177  3428  3457 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -96, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -95, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -66, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -89, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -68, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:40.179  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:35:40.181  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:35:40.182  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-11 07:35:40.183  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:35:40.184  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:35:41.680  3428  3428 D BtGatt.ScanManager: awakened up at time 785849
08-11 07:35:41.683  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:41.694  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:35:41.695  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:43.198  3428  3428 D BtGatt.ScanManager: awakened up at time 787367
,08-11 07:35:43.202  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:43.211  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:43.212  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:44.713  3428  3428 D BtGatt.ScanManager: awakened up at time 788882
,08-11 07:35:44.716  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:44.769  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:44.770  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:44.770  3428  3457 D BtGatt.GattService: current time is 788938975893
08-11 07:35:44.771  3428  3457 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -69, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -72, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:35:44.772  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:35:44.773  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-11 07:35:44.774  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:35:44.775  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:35:44.776  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:35:44.777  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:35:45.775   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=789943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:35:46.273  3428  3428 D BtGatt.ScanManager: awakened up at time 790441
,08-11 07:35:46.275  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:46.286  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:46.286  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:47.790  3428  3428 D BtGatt.ScanManager: awakened up at time 791958
,08-11 07:35:47.793  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:47.806  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:47.806  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:49.309  3428  3428 D BtGatt.ScanManager: awakened up at time 793477
,08-11 07:35:49.312  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:49.360  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-11 07:35:49.360  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:49.361  3428  3457 D BtGatt.GattService: current time is 793529607288
08-11 07:35:49.362  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -69, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -73, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:35:49.362  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:35:49.363  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-11 07:35:49.364  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:35:49.365  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-11 07:35:49.366  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:35:50.864  3428  3428 D BtGatt.ScanManager: awakened up at time 795032
,08-11 07:35:50.867  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:50.899  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-11 07:35:50.899  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:35:50.899  3428  3457 D BtGatt.GattService: current time is 795068344681
,08-11 07:35:50.900  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -101, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 07:35:50.901  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:35:50.902  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:35:50.903  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:50.903  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:52.403  3428  3428 D BtGatt.ScanManager: awakened up at time 796571
,08-11 07:35:52.405  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:52.416  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:52.417  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:53.917  3428  3428 D BtGatt.ScanManager: awakened up at time 798085
,08-11 07:35:53.920  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:53.952  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:35:53.952  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:53.955  3428  3457 D BtGatt.GattService: current time is 798124229672
08-11 07:35:53.956  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:35:53.956  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:35:55.457  3428  3428 D BtGatt.ScanManager: awakened up at time 799625
,08-11 07:35:55.459  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:55.513  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:35:55.513  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:55.514  3428  3457 D BtGatt.GattService: current time is 799682418213
,08-11 07:35:55.515  3428  3457 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -86, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -68, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -91, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -68, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -94, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:55.517  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 07:35:55.519  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:35:55.520  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-11 07:35:55.520  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:35:55.521  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:35:55.522  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:35:55.829   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=799997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:35:57.015  3428  3428 D BtGatt.ScanManager: awakened up at time 801184
,08-11 07:35:57.018  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:57.034  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:35:57.034  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:35:58.538  3428  3428 D BtGatt.ScanManager: awakened up at time 802706
08-11 07:35:58.540  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:35:58.552  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:35:58.552  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:00.060  3428  3428 D BtGatt.ScanManager: awakened up at time 804229
,08-11 07:36:00.063  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-11 07:36:00.102  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-11 07:36:00.102  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:00.103  3428  3457 D BtGatt.GattService: current time is 804271535285
08-11 07:36:00.103  3428  3457 D BtGatt.GattService: Batch record : [-106, -15, -31, -128, 20, -7, 1, -128, -103, 28, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 1, 33, -43, 2, 2, -29, 21, 62, -100, 106, -106, 0, 71, -122, -77, 84, 69, -12, 1, -128, -70, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -91, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:36:00.103  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 1, 33, -43, 2, 2, -29, 21, 62, -100, 106, -106]
08-11 07:36:00.103  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-11 07:36:00.104  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:36:00.104  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:36:00.104  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:36:00.104  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-11 07:36:00.105  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:36:01.608  3428  3428 D BtGatt.ScanManager: awakened up at time 805776
,08-11 07:36:01.610  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:01.624  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:01.625  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:03.127  3428  3428 D BtGatt.ScanManager: awakened up at time 807296
,08-11 07:36:03.130  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:03.152  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:03.153  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:03.658  3428  3428 D BtGatt.ScanManager: awakened up at time 807826
,08-11 07:36:03.661  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:03.706  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:36:03.706  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:03.707  3428  3457 D BtGatt.GattService: current time is 807875438196
08-11 07:36:03.707  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-11 07:36:03.708  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 07:36:05.209  3428  3428 D BtGatt.ScanManager: awakened up at time 809377
,08-11 07:36:05.213  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:05.245  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-11 07:36:05.245  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:05.246  3428  3457 D BtGatt.GattService: current time is 809414602568
,08-11 07:36:05.247  3428  3457 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -69, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -92, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:36:05.247  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 07:36:05.248  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:36:05.249  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:36:05.250  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:36:06.749  3428  3428 D BtGatt.ScanManager: awakened up at time 810917
,08-11 07:36:06.753  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:06.763  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:36:06.764  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:06.798  3690  3935 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 07:36:06.822  3690  3936 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 07:36:06.840  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:06.842  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:06.893  1528  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:36:06.893  1528  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:36:06.893  1528  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:36:06.893  1528  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:36:06.949  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:06.954  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:07.000  1528  2666 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 07:36:07.000  1528  2666 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 07:36:07.000  1528  2666 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:36:07.000  1528  2666 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:36:07.021  3690  3936 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 07:36:07.022  3690  3935 E BooksSync: Soft error
08-11 07:36:07.022  3690  3935 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:36:07.022  3690  3935 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 07:36:07.022  3690  3935 E BooksSync: Sync error
08-11 07:36:07.022  3690  3935 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 07:36:07.022  3690  3935 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 07:36:07.022  3690  3935 I BooksSync: Finished books sync
,08-11 07:36:07.038   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 810928, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:36:07.270  3428  3428 D BtGatt.ScanManager: awakened up at time 811439
,08-11 07:36:07.273  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:07.297  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:07.297  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:08.800  3428  3428 D BtGatt.ScanManager: awakened up at time 812968
,08-11 07:36:08.802  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:08.838  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 07:36:08.838  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:08.839  3428  3457 D BtGatt.GattService: current time is 813007406259
,08-11 07:36:08.839  3428  3457 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 07:36:08.840  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:36:10.341  3428  3428 D BtGatt.ScanManager: awakened up at time 814509
,08-11 07:36:10.343  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:10.395  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 07:36:10.396  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:10.396  3428  3457 D BtGatt.GattService: current time is 814565251779
08-11 07:36:10.397  3428  3457 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -68, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -95, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -85, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -90, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -92, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:36:10.398  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-11 07:36:10.399  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 07:36:10.400  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 07:36:10.401  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:36:10.402  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 07:36:10.403  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:36:10.856   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=815023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:36:11.898  3428  3428 D BtGatt.ScanManager: awakened up at time 816066
,08-11 07:36:11.903  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:11.913  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:11.913  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:13.414  3428  3428 D BtGatt.ScanManager: awakened up at time 817582
,08-11 07:36:13.416  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:13.429  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:13.430  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:14.933  3428  3428 D BtGatt.ScanManager: awakened up at time 819101
,08-11 07:36:14.939  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:14.989  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-11 07:36:14.989  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:14.990  3428  3457 D BtGatt.GattService: current time is 819158520518
08-11 07:36:14.991  3428  3457 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -68, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -106, -15, -31, -128, 20, -7, 1, -128, -92, 15, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 17, 33, -43, 2, 1, -29, 18, 62, -80, -11, -39, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:36:14.992  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 07:36:14.993  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 07:36:14.994  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-11 07:36:14.995  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 07:36:14.996  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 17, 33, -43, 2, 1, -29, 18, 62, -80, -11, -39]
08-11 07:36:14.997  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 07:36:14.997  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 07:36:16.493  3428  3428 D BtGatt.ScanManager: awakened up at time 820661
,08-11 07:36:16.495  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:16.505  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:16.506  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:18.009  3428  3428 D BtGatt.ScanManager: awakened up at time 822177
,08-11 07:36:18.011  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:18.023  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 07:36:18.023  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:18.201  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements,
08-11 07:36:18.202  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-11 07:36:18.202  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:36:18.203  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
08-11 07:36:18.203  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 07:36:18.203  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 07:36:18.206  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:36:18.208  3428  3925 D BtGatt.GattService: stopScan() - queue size =1
,08-11 07:36:18.210  3428  3439 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:36:18.212  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:36:18.212  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 07:36:18.212  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 07:36:18.213  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 07:36:18.213  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 07:36:18.219  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:36:18.219  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:36:18.229  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 07:36:18.229  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:18.230  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:36:18.240  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:36:18.240  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:36:18.241  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:36:18.254  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:36:18.254  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:36:18.721  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:36:18.722  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:36:18.722  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:36:18.730  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 07:36:18.730  3365  3413 I jxcore-log: 
,08-11 07:36:18.744  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:36:18.744  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 07:36:18.744  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:36:18.744  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 07:36:18.744  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 07:36:18.744  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 07:36:18.744  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 07:36:18.744  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 07:36:18.745  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 07:36:18.745  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 07:36:18.745  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 07:36:18.745  3365  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 07:36:18.745  3365  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-11 07:36:18.745  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-11 07:36:18.745  3365  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 07:36:18.745  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 07:36:18.749  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:36:18.749  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 07:36:18.749  3365  3365 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-11 07:36:18.761  3365  3413 I jxcore-log: not ok 179 Peer made successful https requests to all peers
08-11 07:36:18.761  3365  3413 I jxcore-log: 
,08-11 07:36:18.761  3365  3413 I jxcore-log:   ---
08-11 07:36:18.761  3365  3413 I jxcore-log: 
08-11 07:36:18.762  3365  3413 I jxcore-log:     operator: ok
08-11 07:36:18.762  3365  3413 I jxcore-log: 
,08-11 07:36:18.762  3365  3413 I jxcore-log:     expected: true
08-11 07:36:18.762  3365  3413 I jxcore-log: 
,08-11 07:36:18.762  3365  3413 I jxcore-log:     actual:   false
08-11 07:36:18.762  3365  3413 I jxcore-log: 
08-11 07:36:18.762  3365  3413 I jxcore-log:   ...
08-11 07:36:18.762  3365  3413 I jxcore-log: 
,08-11 07:36:18.765  3365  3413 I jxcore-log: not ok 180 Peer received right amount of https requests
08-11 07:36:18.765  3365  3413 I jxcore-log: 
,08-11 07:36:18.765  3365  3413 I jxcore-log:   ---
08-11 07:36:18.765  3365  3413 I jxcore-log: 
08-11 07:36:18.765  3365  3413 I jxcore-log:     operator: ok
08-11 07:36:18.765  3365  3413 I jxcore-log: 
08-11 07:36:18.766  3365  3413 I jxcore-log:     expected: true
08-11 07:36:18.766  3365  3413 I jxcore-log: 
,08-11 07:36:18.766  3365  3413 I jxcore-log:     actual:   false
08-11 07:36:18.766  3365  3413 I jxcore-log: 
08-11 07:36:18.766  3365  3413 I jxcore-log:   ...
08-11 07:36:18.766  3365  3413 I jxcore-log: 
08-11 07:36:18.766  3365  3413 I jxcore-log: ok 181 HTTPS server received zero PSK Identities. Count:0
08-11 07:36:18.766  3365  3413 I jxcore-log: 
08-11 07:36:18.771  3365  3413 I jxcore-log: # teardown
08-11 07:36:18.771  3365  3413 I jxcore-log: 
,08-11 07:36:19.011  3365  3413 I jxcore-log: INFO testThaliNotification: Participants:2 Peers Replied to us:0 Peers requested to:0,
08-11 07:36:19.011  3365  3413 I jxcore-log: 
,08-11 07:36:19.024  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:36:19.024  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:36:19.024  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:36:19.024  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 07:36:19.027  3365  3413 I jxcore-log: # setup
08-11 07:36:19.027  3365  3413 I jxcore-log: 
,08-11 07:36:19.028  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:36:19.028  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-11 07:36:19.029  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:36:19.029  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:36:19.157  3365  3413 I jxcore-log: # 55. Test BEACONS_RETRIEVED_AND_PARSED locally
08-11 07:36:19.157  3365  3413 I jxcore-log: 
,08-11 07:36:19.792  3365  3413 I jxcore-log: ok 182 peerIdentifier should be identifier
08-11 07:36:19.792  3365  3413 I jxcore-log: 
,08-11 07:36:19.792  3365  3413 I jxcore-log: ok 183 Response should be BEACONS_RETRIEVED_AND_PARSED
08-11 07:36:19.792  3365  3413 I jxcore-log: 
08-11 07:36:19.793  3365  3413 I jxcore-log: ok 184 good beacon
08-11 07:36:19.793  3365  3413 I jxcore-log: 
08-11 07:36:19.793  3365  3413 I jxcore-log: ok 185 good preAmble
08-11 07:36:19.793  3365  3413 I jxcore-log: 
08-11 07:36:19.793  3365  3413 I jxcore-log: ok 186 public keys match!
08-11 07:36:19.793  3365  3413 I jxcore-log: 
,08-11 07:36:19.795  3365  3413 I jxcore-log: ok 187 must return null after successful call
08-11 07:36:19.795  3365  3413 I jxcore-log: 
08-11 07:36:19.795  3365  3413 I jxcore-log: ok 188 Once start returns the action should be in KILLED state
08-11 07:36:19.795  3365  3413 I jxcore-log: 
,08-11 07:36:19.811  3365  3413 I jxcore-log: # teardown
08-11 07:36:19.811  3365  3413 I jxcore-log: 
,08-11 07:36:19.842  3365  3413 I jxcore-log: # setup
08-11 07:36:19.842  3365  3413 I jxcore-log: 
,08-11 07:36:20.960  3365  3413 I jxcore-log: # 56. Test HTTP_BAD_RESPONSE locally
08-11 07:36:20.960  3365  3413 I jxcore-log: 
,08-11 07:36:21.034  3365  3413 I jxcore-log: ok 189 Response should be HTTP_BAD_RESPONSE
08-11 07:36:21.034  3365  3413 I jxcore-log: 
,08-11 07:36:21.037  3365  3413 I jxcore-log: ok 190 must return null after successful call
08-11 07:36:21.037  3365  3413 I jxcore-log: 
,08-11 07:36:21.048  3365  3413 I jxcore-log: # teardown
08-11 07:36:21.048  3365  3413 I jxcore-log: 
,08-11 07:36:21.223  3365  3413 I jxcore-log: # setup
08-11 07:36:21.223  3365  3413 I jxcore-log: 
,08-11 07:36:21.341  3365  3413 I jxcore-log: # 57. Test NETWORK_PROBLEM locally
08-11 07:36:21.341  3365  3413 I jxcore-log: 
,08-11 07:36:21.573  3365  3413 I jxcore-log: ok 191 Response should be NETWORK_PROBLEM
08-11 07:36:21.573  3365  3413 I jxcore-log: 
,08-11 07:36:21.583  3365  3413 I jxcore-log: ok 192 reject reason should be: Could not establish TCP connection
08-11 07:36:21.583  3365  3413 I jxcore-log: 
,08-11 07:36:21.589  3365  3413 I jxcore-log: # teardown
08-11 07:36:21.589  3365  3413 I jxcore-log: 
,08-11 07:36:21.617  3365  3413 I jxcore-log: # setup
08-11 07:36:21.617  3365  3413 I jxcore-log: 
,08-11 07:36:21.775  3365  3413 I jxcore-log: # 58. Call the start two times
08-11 07:36:21.775  3365  3413 I jxcore-log: 
,08-11 07:36:21.876  3365  3413 I jxcore-log: ok 193 Call start once
08-11 07:36:21.876  3365  3413 I jxcore-log: 
,08-11 07:36:21.965  3365  3413 I jxcore-log: ok 194 Response should be BEACONS_RETRIEVED_AND_PARSED
08-11 07:36:21.965  3365  3413 I jxcore-log: 
,08-11 07:36:21.967  3365  3413 I jxcore-log: ok 195 must return null after successful call.
08-11 07:36:21.967  3365  3413 I jxcore-log: 
,08-11 07:36:21.975  3365  3413 I jxcore-log: # teardown
08-11 07:36:21.975  3365  3413 I jxcore-log: 
,08-11 07:36:22.046  3365  3413 I jxcore-log: # setup
08-11 07:36:22.046  3365  3413 I jxcore-log: 
,08-11 07:36:22.193  3365  3413 I jxcore-log: # 59. Call the kill before calling the start
08-11 07:36:22.193  3365  3413 I jxcore-log: 
,08-11 07:36:22.258  3365  3413 I jxcore-log: ok 196 Should be Killed
08-11 07:36:22.258  3365  3413 I jxcore-log: 
,08-11 07:36:22.260  3365  3413 I jxcore-log: ok 197 Start after killed
08-11 07:36:22.260  3365  3413 I jxcore-log: 
,08-11 07:36:22.264  3365  3413 I jxcore-log: # teardown
08-11 07:36:22.264  3365  3413 I jxcore-log: 
,08-11 07:36:22.308  3365  3413 I jxcore-log: # setup
08-11 07:36:22.308  3365  3413 I jxcore-log: 
,08-11 07:36:22.423  3365  3413 I jxcore-log: # 60. Call the kill immediately after the start
08-11 07:36:22.423  3365  3413 I jxcore-log: 
,08-11 07:36:22.510  3365  3413 I jxcore-log: ok 198 Should be KILLED
08-11 07:36:22.510  3365  3413 I jxcore-log: 
,08-11 07:36:22.511  3365  3413 I jxcore-log: ok 199 must return null after successful kill
08-11 07:36:22.511  3365  3413 I jxcore-log: 
,08-11 07:36:22.514  3365  3413 I jxcore-log: # teardown
08-11 07:36:22.514  3365  3413 I jxcore-log: 
,08-11 07:36:22.555  3365  3413 I jxcore-log: # setup
08-11 07:36:22.555  3365  3413 I jxcore-log: 
,08-11 07:36:22.685  3365  3413 I jxcore-log: # 61. Call the kill while waiting a response from the server
08-11 07:36:22.685  3365  3413 I jxcore-log: 
,08-11 07:36:24.768  3365  3413 I jxcore-log: ok 200 Should be KILLED
08-11 07:36:24.768  3365  3413 I jxcore-log: 
,08-11 07:36:24.780  3365  3413 I jxcore-log: ok 201 must return null after successful kill
08-11 07:36:24.780  3365  3413 I jxcore-log: 
,08-11 07:36:24.797  3365  3413 I jxcore-log: # teardown
08-11 07:36:24.797  3365  3413 I jxcore-log: 
,08-11 07:36:24.936  3365  3413 I jxcore-log: # setup
08-11 07:36:24.936  3365  3413 I jxcore-log: 
,08-11 07:36:25.082  3365  3413 I jxcore-log: # 62. Test to exceed the max content size locally
08-11 07:36:25.082  3365  3413 I jxcore-log: 
,08-11 07:36:25.268  3365  3413 I jxcore-log: ok 202 HTTP_BAD_RESPONSE should be response when content size is exceeded
08-11 07:36:25.268  3365  3413 I jxcore-log: 
,08-11 07:36:25.271  3365  3413 I jxcore-log: ok 203 must return null after successful call
08-11 07:36:25.271  3365  3413 I jxcore-log: 
,08-11 07:36:25.281  3365  3413 I jxcore-log: # teardown
08-11 07:36:25.281  3365  3413 I jxcore-log: 
,08-11 07:36:25.320  3365  3413 I jxcore-log: # setup
08-11 07:36:25.320  3365  3413 I jxcore-log: 
,08-11 07:36:25.426  3365  3413 I jxcore-log: # 63. Close the server socket while the client is waiting a response from the server. Local test.
08-11 07:36:25.426  3365  3413 I jxcore-log: 
,08-11 07:36:27.606  3365  3413 I jxcore-log: ok 204 Should be NETWORK_PROBLEM caused closing server socket
08-11 07:36:27.606  3365  3413 I jxcore-log: 
,08-11 07:36:27.609  3365  3413 I jxcore-log: ok 205 Should be Could not establish TCP connection
08-11 07:36:27.609  3365  3413 I jxcore-log: 
,08-11 07:36:27.616  3365  3413 I jxcore-log: # teardown
08-11 07:36:27.616  3365  3413 I jxcore-log: 
,08-11 07:36:27.713  3365  3413 I jxcore-log: # setup
08-11 07:36:27.713  3365  3413 I jxcore-log: 
,08-11 07:36:27.846  3365  3413 I jxcore-log: # 64. Close the client socket while the client is waiting a response from the server. Local test.
08-11 07:36:27.846  3365  3413 I jxcore-log: 
,08-11 07:36:30.000  3365  3413 I jxcore-log: ok 206 Should be NETWORK_PROBLEM caused closing client socket
08-11 07:36:30.000  3365  3413 I jxcore-log: 
,08-11 07:36:30.009  3365  3413 I jxcore-log: ok 207 Should be Could not establish TCP connection
08-11 07:36:30.009  3365  3413 I jxcore-log: 
,08-11 07:36:30.019  3365  3413 I jxcore-log: # teardown
08-11 07:36:30.019  3365  3413 I jxcore-log: 
,08-11 07:36:30.134  3365  3413 I jxcore-log: # setup
08-11 07:36:30.134  3365  3413 I jxcore-log: 
,08-11 07:36:30.181  3365  3413 I jxcore-log: # 65. #generatePreambleAndBeacons bad args
08-11 07:36:30.181  3365  3413 I jxcore-log: 
,08-11 07:36:30.247  3365  3413 I jxcore-log: ok 208 publicKeysToNotify cannot be null
08-11 07:36:30.247  3365  3413 I jxcore-log: 
,08-11 07:36:30.250  3365  3413 I jxcore-log: ok 209 ecdh for local device cannot be null
08-11 07:36:30.250  3365  3413 I jxcore-log: 
,08-11 07:36:30.252  3365  3413 I jxcore-log: ok 210 milliseconds cannot be less than 0
08-11 07:36:30.252  3365  3413 I jxcore-log: 
08-11 07:36:30.253  3365  3413 I jxcore-log: ok 211 milliseconds cannot be 0
08-11 07:36:30.253  3365  3413 I jxcore-log: 
08-11 07:36:30.255  3365  3413 I jxcore-log: ok 212 milliseconds cannot be greater than one_day
08-11 07:36:30.255  3365  3413 I jxcore-log: 
,08-11 07:36:30.258  3365  3413 I jxcore-log: # teardown
08-11 07:36:30.258  3365  3413 I jxcore-log: 
,08-11 07:36:30.336  3365  3413 I jxcore-log: # setup
08-11 07:36:30.336  3365  3413 I jxcore-log: 
,08-11 07:36:30.414  3365  3413 I jxcore-log: # 66. #generatePreambleAndBeacons empty keys to notify
08-11 07:36:30.414  3365  3413 I jxcore-log: 
,08-11 07:36:30.515  3365  3413 I jxcore-log: ok 213 should be equal
08-11 07:36:30.515  3365  3413 I jxcore-log: 
,08-11 07:36:30.517  3365  3413 I jxcore-log: # teardown
08-11 07:36:30.517  3365  3413 I jxcore-log: 
,08-11 07:36:30.590  3365  3413 I jxcore-log: # setup
08-11 07:36:30.590  3365  3413 I jxcore-log: 
,08-11 07:36:30.647  3365  3413 I jxcore-log: # 67. #generatePreambleAndBeacons multiple keys to notify
08-11 07:36:30.647  3365  3413 I jxcore-log: 
,08-11 07:36:30.777  3365  3413 I jxcore-log: ok 214 should be equal
08-11 07:36:30.777  3365  3413 I jxcore-log: 
,08-11 07:36:30.777  3365  3413 I jxcore-log: ok 215 should be equal
08-11 07:36:30.777  3365  3413 I jxcore-log: 
08-11 07:36:30.778  3365  3413 I jxcore-log: ok 216 (unnamed assert)
08-11 07:36:30.778  3365  3413 I jxcore-log: 
08-11 07:36:30.778  3365  3413 I jxcore-log: ok 217 should be equal
08-11 07:36:30.778  3365  3413 I jxcore-log: 
,08-11 07:36:30.780  3365  3413 I jxcore-log: # teardown
08-11 07:36:30.780  3365  3413 I jxcore-log: 
,08-11 07:36:30.914  3365  3413 I jxcore-log: # setup
08-11 07:36:30.914  3365  3413 I jxcore-log: 
,08-11 07:36:30.985  3365  3413 I jxcore-log: # 68. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
08-11 07:36:30.985  3365  3413 I jxcore-log: 
,08-11 07:36:31.078  3365  3413 I jxcore-log: ok 218 should throw
08-11 07:36:31.078  3365  3413 I jxcore-log: 
08-11 07:36:31.080  3365  3413 I jxcore-log: # teardown
08-11 07:36:31.080  3365  3413 I jxcore-log: 
,08-11 07:36:31.145  3365  3413 I jxcore-log: # setup
08-11 07:36:31.145  3365  3413 I jxcore-log: 
,08-11 07:36:32.050  3365  3413 I jxcore-log: # 69. #parseBeacons invalid expiration in beaconStreamWithPreAmble
08-11 07:36:32.050  3365  3413 I jxcore-log: 
,08-11 07:36:32.098  3365  3413 I jxcore-log: ok 219 Preamble expiration must be a 64 bit integer
08-11 07:36:32.098  3365  3413 I jxcore-log: 
08-11 07:36:32.100  3365  3413 I jxcore-log: # teardown
08-11 07:36:32.100  3365  3413 I jxcore-log: 
,08-11 07:36:32.211  3365  3413 I jxcore-log: # setup
08-11 07:36:32.211  3365  3413 I jxcore-log: 
,08-11 07:36:32.280  3365  3413 I jxcore-log: # 70. #parseBeacons expiration out of range lower
08-11 07:36:32.280  3365  3413 I jxcore-log: 
,08-11 07:36:32.369  3365  3413 I jxcore-log: ok 220 Expiration out of range
08-11 07:36:32.369  3365  3413 I jxcore-log: 
,08-11 07:36:32.371  3365  3413 I jxcore-log: # teardown
08-11 07:36:32.371  3365  3413 I jxcore-log: 
,08-11 07:36:33.508  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:33.512  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:33.531  3416  3940 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 07:36:33.565  1528  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 07:36:33.565  1528  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 07:36:33.565  1528  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:36:33.565  1528  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 07:36:33.585  3416  3940 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 07:36:33.781  3365  3413 I jxcore-log: # setup
08-11 07:36:33.781  3365  3413 I jxcore-log: 
,08-11 07:36:33.833  3365  3413 I jxcore-log: # 71. #parseBeacons expiration out of range lower
08-11 07:36:33.833  3365  3413 I jxcore-log: 
,08-11 07:36:33.975  3365  3413 I jxcore-log: ok 221 Expiration out of range
08-11 07:36:33.975  3365  3413 I jxcore-log: 
08-11 07:36:33.977  3365  3413 I jxcore-log: # teardown
08-11 07:36:33.977  3365  3413 I jxcore-log: 
,08-11 07:36:34.043  3365  3413 I jxcore-log: # setup
08-11 07:36:34.043  3365  3413 I jxcore-log: 
,08-11 07:36:34.087  3365  3413 I jxcore-log: # 72. #parseBeacons no beacons returns null
08-11 07:36:34.087  3365  3413 I jxcore-log: 
,08-11 07:36:34.167  3365  3413 I jxcore-log: ok 222 should be equal
08-11 07:36:34.167  3365  3413 I jxcore-log: 
,08-11 07:36:34.169  3365  3413 I jxcore-log: # teardown
08-11 07:36:34.169  3365  3413 I jxcore-log: 
,08-11 07:36:34.210  3365  3413 I jxcore-log: # setup
08-11 07:36:34.210  3365  3413 I jxcore-log: 
,08-11 07:36:34.270  3365  3413 I jxcore-log: # 73. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
08-11 07:36:34.270  3365  3413 I jxcore-log: 
,08-11 07:36:34.343  3365  3413 I jxcore-log: ok 223 Malformed encrypted beacon key ID
08-11 07:36:34.343  3365  3413 I jxcore-log: 
,08-11 07:36:34.345  3365  3413 I jxcore-log: # teardown
08-11 07:36:34.345  3365  3413 I jxcore-log: 
,08-11 07:36:34.394  3365  3413 I jxcore-log: # setup
08-11 07:36:34.394  3365  3413 I jxcore-log: 
,08-11 07:36:34.468  3365  3413 I jxcore-log: # 74. #parseBeacons addressBookCallback fails decrypt
08-11 07:36:34.468  3365  3413 I jxcore-log: 
,08-11 07:36:34.652  3365  3413 I jxcore-log: ok 224 should be equal
08-11 07:36:34.652  3365  3413 I jxcore-log: 
,08-11 07:36:34.654  3365  3413 I jxcore-log: # teardown
08-11 07:36:34.654  3365  3413 I jxcore-log: 
,08-11 07:36:34.786  3365  3413 I jxcore-log: # setup
08-11 07:36:34.786  3365  3413 I jxcore-log: 
,08-11 07:36:34.849  3365  3413 I jxcore-log: # 75. #parseBeacons addressBookCallback returns no matches
08-11 07:36:34.849  3365  3413 I jxcore-log: 
,08-11 07:36:35.028  3365  3413 I jxcore-log: ok 225 should be equal
08-11 07:36:35.028  3365  3413 I jxcore-log: 
08-11 07:36:35.028  3365  3413 I jxcore-log: ok 226 should be equal
08-11 07:36:35.028  3365  3413 I jxcore-log: 
,08-11 07:36:35.030  3365  3413 I jxcore-log: # teardown
08-11 07:36:35.030  3365  3413 I jxcore-log: 
,08-11 07:36:35.109  3365  3413 I jxcore-log: # setup
08-11 07:36:35.109  3365  3413 I jxcore-log: 
,08-11 07:36:35.148  3365  3413 I jxcore-log: # 76. #parseBeacons addressBookCallback returns spurious match
08-11 07:36:35.148  3365  3413 I jxcore-log: 
,08-11 07:36:35.318  3365  3413 I jxcore-log: ok 227 should be equal
08-11 07:36:35.318  3365  3413 I jxcore-log: 
,08-11 07:36:35.319  3365  3413 I jxcore-log: ok 228 should be equal
08-11 07:36:35.319  3365  3413 I jxcore-log: 
08-11 07:36:35.320  3365  3413 I jxcore-log: # teardown
08-11 07:36:35.320  3365  3413 I jxcore-log: 
,08-11 07:36:35.443  3365  3413 I jxcore-log: # setup
08-11 07:36:35.443  3365  3413 I jxcore-log: 
,08-11 07:36:35.536  3365  3413 I jxcore-log: # 77. #parseBeacons addressBookCallback returns public key
08-11 07:36:35.536  3365  3413 I jxcore-log: 
,08-11 07:36:35.763  3365  3413 I jxcore-log: ok 229 right number of calls to address book
08-11 07:36:35.763  3365  3413 I jxcore-log: 
,08-11 07:36:35.763  3365  3413 I jxcore-log: ok 230 good preAmble
08-11 07:36:35.763  3365  3413 I jxcore-log: 
08-11 07:36:35.764  3365  3413 I jxcore-log: ok 231 good unencryptedKeyId
08-11 07:36:35.764  3365  3413 I jxcore-log: 
08-11 07:36:35.764  3365  3413 I jxcore-log: ok 232 good beacon
08-11 07:36:35.764  3365  3413 I jxcore-log: 
08-11 07:36:35.766  3365  3413 I jxcore-log: # teardown
08-11 07:36:35.766  3365  3413 I jxcore-log: 
,08-11 07:36:35.901  3365  3413 I jxcore-log: # setup
08-11 07:36:35.901  3365  3413 I jxcore-log: 
,08-11 07:36:35.971  3365  3413 I jxcore-log: # 78. validate generatePskIdentityField
08-11 07:36:35.971  3365  3413 I jxcore-log: 
,08-11 07:36:36.037  3365  3413 I jxcore-log: ok 233 decoded buffers match
08-11 07:36:36.037  3365  3413 I jxcore-log: 
,08-11 07:36:36.040  3365  3413 I jxcore-log: # teardown
08-11 07:36:36.040  3365  3413 I jxcore-log: 
,08-11 07:36:36.087  3365  3413 I jxcore-log: # setup
08-11 07:36:36.087  3365  3413 I jxcore-log: 
,08-11 07:36:36.135  3365  3413 I jxcore-log: # 79. validate generatePskSecret
08-11 07:36:36.135  3365  3413 I jxcore-log: 
,08-11 07:36:36.241  3365  3413 I jxcore-log: ok 234 secrets match
08-11 07:36:36.241  3365  3413 I jxcore-log: 
,08-11 07:36:36.243  3365  3413 I jxcore-log: # teardown
08-11 07:36:36.243  3365  3413 I jxcore-log: 
,08-11 07:36:36.320  3365  3413 I jxcore-log: # setup
08-11 07:36:36.320  3365  3413 I jxcore-log: 
,08-11 07:36:36.376  3365  3413 I jxcore-log: # 80. validate generatePskSecrets
08-11 07:36:36.376  3365  3413 I jxcore-log: 
,08-11 07:36:36.553  3365  3413 I jxcore-log: ok 235 Matching numbers
08-11 07:36:36.553  3365  3413 I jxcore-log: 
,08-11 07:36:36.560  3365  3413 I jxcore-log: ok 236 We have an entry!
08-11 07:36:36.560  3365  3413 I jxcore-log: 
,08-11 07:36:36.560  3365  3413 I jxcore-log: ok 237 keys match
08-11 07:36:36.560  3365  3413 I jxcore-log: 
08-11 07:36:36.561  3365  3413 I jxcore-log: ok 238 secrets match
08-11 07:36:36.561  3365  3413 I jxcore-log: 
,08-11 07:36:36.568  3365  3413 I jxcore-log: ok 239 We have an entry!
08-11 07:36:36.568  3365  3413 I jxcore-log: 
,08-11 07:36:36.568  3365  3413 I jxcore-log: ok 240 keys match
08-11 07:36:36.568  3365  3413 I jxcore-log: 
08-11 07:36:36.568  3365  3413 I jxcore-log: ok 241 secrets match
08-11 07:36:36.568  3365  3413 I jxcore-log: 
,08-11 07:36:36.575  3365  3413 I jxcore-log: ok 242 We have an entry!
08-11 07:36:36.575  3365  3413 I jxcore-log: 
,08-11 07:36:36.576  3365  3413 I jxcore-log: ok 243 keys match
08-11 07:36:36.576  3365  3413 I jxcore-log: 
08-11 07:36:36.576  3365  3413 I jxcore-log: ok 244 secrets match
08-11 07:36:36.576  3365  3413 I jxcore-log: 
08-11 07:36:36.578  3365  3413 I jxcore-log: # teardown
08-11 07:36:36.578  3365  3413 I jxcore-log: 
,08-11 07:36:36.729  3365  3413 I jxcore-log: # setup
08-11 07:36:36.729  3365  3413 I jxcore-log: 
,08-11 07:36:36.823  3365  3413 I jxcore-log: # 81. validate generateBeaconStreamAndSecrets
08-11 07:36:36.823  3365  3413 I jxcore-log: 
,08-11 07:36:36.995  3365  3413 I jxcore-log: ok 245 Streams have same length
08-11 07:36:36.995  3365  3413 I jxcore-log: 
,08-11 07:36:37.002  3365  3413 I jxcore-log: ok 246 matching size
08-11 07:36:37.002  3365  3413 I jxcore-log: 
,08-11 07:36:37.003  3365  3413 I jxcore-log: ok 247 keys match,
08-11 07:36:37.003  3365  3413 I jxcore-log: 
08-11 07:36:37.003  3365  3413 I jxcore-log: ok 248 secrets match
08-11 07:36:37.003  3365  3413 I jxcore-log: 
08-11 07:36:37.005  3365  3413 I jxcore-log: # teardown
08-11 07:36:37.005  3365  3413 I jxcore-log: 
,08-11 07:36:37.158  3365  3413 I jxcore-log: # setup
08-11 07:36:37.158  3365  3413 I jxcore-log: 
,08-11 07:36:37.281  3365  3413 I jxcore-log: # 82. Add two Peers.
08-11 07:36:37.281  3365  3413 I jxcore-log: 
,08-11 07:36:37.372  3365  3413 I jxcore-log: ok 249 should be equal
08-11 07:36:37.372  3365  3413 I jxcore-log: 
,08-11 07:36:37.373  3365  3413 I jxcore-log: ok 250 should be equal
08-11 07:36:37.373  3365  3413 I jxcore-log: 
,08-11 07:36:37.373  3365  3413 I jxcore-log: ok 251 should be equal
08-11 07:36:37.373  3365  3413 I jxcore-log: 
08-11 07:36:37.373  3365  3413 I jxcore-log: ok 252 should be equal
08-11 07:36:37.373  3365  3413 I jxcore-log: 
,08-11 07:36:37.374  3365  3413 I jxcore-log: ok 253 should be equal
08-11 07:36:37.374  3365  3413 I jxcore-log: 
08-11 07:36:37.379  3365  3413 I jxcore-log: # teardown
08-11 07:36:37.379  3365  3413 I jxcore-log: 
,08-11 07:36:37.412  3365  3413 I jxcore-log: # setup
08-11 07:36:37.412  3365  3413 I jxcore-log: 
,08-11 07:36:37.512  3365  3413 I jxcore-log: # 83. TCP_NATIVE peer loses DNS
08-11 07:36:37.512  3365  3413 I jxcore-log: 
,08-11 07:36:37.665  3365  3413 I jxcore-log: ok 254 should be equal
08-11 07:36:37.665  3365  3413 I jxcore-log: 
,08-11 07:36:37.668  3365  3413 I jxcore-log: ok 255 should be equal
08-11 07:36:37.668  3365  3413 I jxcore-log: 
,08-11 07:36:37.675  3365  3413 I jxcore-log: # teardown
08-11 07:36:37.675  3365  3413 I jxcore-log: 
,08-11 07:36:37.710  3365  3413 I jxcore-log: # setup
08-11 07:36:37.710  3365  3413 I jxcore-log: 
,08-11 07:36:37.893  3365  3413 I jxcore-log: # 84. Received beacons with no values for us
08-11 07:36:37.893  3365  3413 I jxcore-log: 
,08-11 07:36:38.126  3365  3413 I jxcore-log: ok 256 entry exists
08-11 07:36:38.126  3365  3413 I jxcore-log: 
,08-11 07:36:38.126  3365  3413 I jxcore-log: ok 257 entry is resolved
08-11 07:36:38.126  3365  3413 I jxcore-log: 
,08-11 07:36:38.141  3365  3413 I jxcore-log: # teardown
08-11 07:36:38.141  3365  3413 I jxcore-log: 
,08-11 07:36:38.170  3365  3413 I jxcore-log: # setup
08-11 07:36:38.170  3365  3413 I jxcore-log: 
,08-11 07:36:38.309  3365  3413 I jxcore-log: # 85. Resolves an action locally
08-11 07:36:38.309  3365  3413 I jxcore-log: 
,08-11 07:36:38.585  3365  3413 I jxcore-log: ok 258 Host address must match
08-11 07:36:38.585  3365  3413 I jxcore-log: 
,08-11 07:36:38.586  3365  3413 I jxcore-log: ok 259 suggestedTCPTimeout must match
08-11 07:36:38.586  3365  3413 I jxcore-log: 
08-11 07:36:38.586  3365  3413 I jxcore-log: ok 260 connectionType must match
08-11 07:36:38.586  3365  3413 I jxcore-log: 
,08-11 07:36:38.587  3365  3413 I jxcore-log: ok 261 portNumber must match
08-11 07:36:38.587  3365  3413 I jxcore-log: 
,08-11 07:36:38.594  3365  3413 I jxcore-log: # teardown
08-11 07:36:38.594  3365  3413 I jxcore-log: 
,08-11 07:36:38.634  3365  3413 I jxcore-log: # setup
08-11 07:36:38.634  3365  3413 I jxcore-log: 
,08-11 07:36:38.747  3365  3413 I jxcore-log: # 86. Resolves an action locally using ThaliPeerPoolDefault
08-11 07:36:38.747  3365  3413 I jxcore-log: 
,08-11 07:36:42.596  3365  3413 I jxcore-log: ok 262 Host address must match
08-11 07:36:42.596  3365  3413 I jxcore-log: 
08-11 07:36:42.596  3365  3413 I jxcore-log: ok 263 suggestedTCPTimeout must match
08-11 07:36:42.596  3365  3413 I jxcore-log: 
08-11 07:36:42.596  3365  3413 I jxcore-log: ok 264 connectionType must match
08-11 07:36:42.596  3365  3413 I jxcore-log: 
08-11 07:36:42.597  3365  3413 I jxcore-log: ok 265 portNumber must match
08-11 07:36:42.597  3365  3413 I jxcore-log: 
,08-11 07:36:42.602  3365  3413 I jxcore-log: # teardown
08-11 07:36:42.602  3365  3413 I jxcore-log: 
,08-11 07:36:42.634  3365  3413 I jxcore-log: # setup
08-11 07:36:42.634  3365  3413 I jxcore-log: 
,08-11 07:36:42.978  3365  3413 I jxcore-log: # 87. Action fails because of a bad hostname.
08-11 07:36:42.978  3365  3413 I jxcore-log: 
,08-11 07:36:48.075  3365  3413 I jxcore-log: ok 266 should be equal
08-11 07:36:48.075  3365  3413 I jxcore-log: 
,08-11 07:36:48.077  3365  3413 I jxcore-log: ok 267 should be equal
08-11 07:36:48.077  3365  3413 I jxcore-log: 
,08-11 07:36:48.080  3365  3413 I jxcore-log: ok 268 should be equal
08-11 07:36:48.080  3365  3413 I jxcore-log: 
,08-11 07:36:48.097  3365  3413 I jxcore-log: # teardown
08-11 07:36:48.097  3365  3413 I jxcore-log: 
,08-11 07:36:48.152  3365  3413 I jxcore-log: # setup
08-11 07:36:48.152  3365  3413 I jxcore-log: 
,08-11 07:36:48.337  3365  3413 I jxcore-log: # 88. hostaddress is removed when the action is running. 
08-11 07:36:48.337  3365  3413 I jxcore-log: 
,08-11 07:36:50.431  3365  3413 I jxcore-log: ok 269 should be equal
08-11 07:36:50.431  3365  3413 I jxcore-log: 
,08-11 07:36:50.462  3365  3413 I jxcore-log: # teardown
08-11 07:36:50.462  3365  3413 I jxcore-log: 
,08-11 07:36:50.544  3365  3413 I jxcore-log: # setup
08-11 07:36:50.544  3365  3413 I jxcore-log: 
,08-11 07:36:50.650  3365  3413 I jxcore-log: # 89. Client to server request locally
08-11 07:36:50.650  3365  3413 I jxcore-log: 
,08-11 07:36:50.849  3365  3413 I jxcore-log: ok 270 secrets are equal
08-11 07:36:50.849  3365  3413 I jxcore-log: 
,08-11 07:36:50.850  3365  3413 I jxcore-log: ok 271 Public key matches with the server key
08-11 07:36:50.850  3365  3413 I jxcore-log: 
08-11 07:36:50.850  3365  3413 I jxcore-log: ok 272 Host address must match
08-11 07:36:50.850  3365  3413 I jxcore-log: 
08-11 07:36:50.850  3365  3413 I jxcore-log: ok 273 suggestedTCPTimeout must match
08-11 07:36:50.850  3365  3413 I jxcore-log: 
08-11 07:36:50.851  3365  3413 I jxcore-log: ok 274 connectionType must match
08-11 07:36:50.851  3365  3413 I jxcore-log: 
,08-11 07:36:50.851  3365  3413 I jxcore-log: ok 275 portNumber must match
08-11 07:36:50.851  3365  3413 I jxcore-log: 
,08-11 07:36:50.857  3365  3413 I jxcore-log: # teardown
08-11 07:36:50.857  3365  3413 I jxcore-log: 
,08-11 07:36:50.966  3365  3413 I jxcore-log: # setup
08-11 07:36:50.966  3365  3413 I jxcore-log: 
,08-11 07:36:51.092  3365  3413 I jxcore-log: # 90. Test ThaliPskMapCache clean and expiration
08-11 07:36:51.092  3365  3413 I jxcore-log: 
,08-11 07:36:51.159  3365  3413 I jxcore-log: ok 276 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
08-11 07:36:51.159  3365  3413 I jxcore-log: 
,08-11 07:36:51.159  3365  3413 I jxcore-log: ok 277 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
08-11 07:36:51.159  3365  3413 I jxcore-log: 
,08-11 07:36:52.163  3365  3413 I jxcore-log: ok 278 All entries should be expired after 1 second
08-11 07:36:52.163  3365  3413 I jxcore-log: 
,08-11 07:36:52.174  3365  3413 I jxcore-log: # teardown
08-11 07:36:52.174  3365  3413 I jxcore-log: 
,08-11 07:36:52.252  3365  3413 I jxcore-log: # setup
08-11 07:36:52.252  3365  3413 I jxcore-log: 
,08-11 07:36:52.396  3365  3413 I jxcore-log: # 91. Test ThaliPskMapCache getSecret and getPublic
08-11 07:36:52.396  3365  3413 I jxcore-log: 
,08-11 07:36:52.537  3365  3413 I jxcore-log: ok 279 All keys need to be available in the cache
08-11 07:36:52.537  3365  3413 I jxcore-log: 
,08-11 07:36:53.541  3365  3413 I jxcore-log: ok 280 All entries should be expired after 1 second
08-11 07:36:53.541  3365  3413 I jxcore-log: 
,08-11 07:36:53.551  3365  3413 I jxcore-log: # teardown
08-11 07:36:53.551  3365  3413 I jxcore-log: 
,08-11 07:36:53.654  3365  3413 I jxcore-log: # setup
08-11 07:36:53.654  3365  3413 I jxcore-log: 
,08-11 07:36:53.752  3365  3413 I jxcore-log: # 92. Test ThaliPskMapCache multiple entries
08-11 07:36:53.752  3365  3413 I jxcore-log: 
,08-11 07:36:55.210  3365  3413 I jxcore-log: ok 281 Size of the cache should be 2
08-11 07:36:55.210  3365  3413 I jxcore-log: 
08-11 07:36:55.215  3365  3413 I jxcore-log: ok 282 Cache doesn't contain dictionary1
08-11 07:36:55.215  3365  3413 I jxcore-log: 
,08-11 07:36:56.430  3365  3413 I jxcore-log: ok 283 Size of the cache should be 1
08-11 07:36:56.430  3365  3413 I jxcore-log: 
,08-11 07:36:56.433  3365  3413 I jxcore-log: ok 284 Cache doesn't contain beaconStreamAndSecretDictionary2
08-11 07:36:56.433  3365  3413 I jxcore-log: 
,08-11 07:36:56.444  3365  3413 I jxcore-log: # teardown
08-11 07:36:56.444  3365  3413 I jxcore-log: 
,08-11 07:36:56.590  3365  3413 I jxcore-log: # setup
08-11 07:36:56.590  3365  3413 I jxcore-log: 
,08-11 07:36:56.696  3365  3413 I jxcore-log: # 93. Start and stop ThaliNotificationServer
08-11 07:36:56.696  3365  3413 I jxcore-log: 
,08-11 07:36:56.780  2875  3946 V KeepSync: Connecting to GoogleApiClient
,08-11 07:36:56.780   873  1689 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 07:36:56.837  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:56.839  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:36:56.873  3365  3413 I jxcore-log: ok 285 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
08-11 07:36:56.873  3365  3413 I jxcore-log: 
,08-11 07:36:56.874  3365  3413 I jxcore-log: ok 286 ThaliMobile.StopAdvertisingAndListeningshould be called once
08-11 07:36:56.874  3365  3413 I jxcore-log: 
08-11 07:36:56.875  3365  3413 I jxcore-log: # teardown
08-11 07:36:56.875  3365  3413 I jxcore-log: 
,08-11 07:36:56.876  1528  2669 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 07:36:56.876  1528  2669 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 07:36:56.876  1528  2669 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:36:56.876  1528  2669 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:36:56.890  1992  3947 V BaseAuthAsyncOperation: access token request failed
,08-11 07:36:56.890  2875  3946 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 07:36:56.924  1528  2668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 07:36:56.924  1528  2668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 07:36:56.924  1528  2668 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:36:56.924  1528  2668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:36:56.934  2875  3946 E KeepSync: IOException
08-11 07:36:56.934  2875  3946 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 07:36:56.934  2875  3946 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 07:36:56.934  2875  3946 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 07:36:56.934  2875  3946 E KeepSync: 	... 10 more
,08-11 07:36:56.934  2875  3946 W KeepSync: Sync result 2
,08-11 07:36:56.946   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 860814, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:36:57.434  3365  3413 I jxcore-log: # setup
08-11 07:36:57.434  3365  3413 I jxcore-log: 
,08-11 07:36:57.501  3365  3413 I jxcore-log: # 94. Pass an empty array to ThaliNotificationServer.start
08-11 07:36:57.501  3365  3413 I jxcore-log: 
,08-11 07:36:57.640  3365  3413 I jxcore-log: ok 287 StartUpdateAdvertisingAndListening should not be called
08-11 07:36:57.640  3365  3413 I jxcore-log: 
,08-11 07:36:57.653  3365  3413 I jxcore-log: ok 288 ThaliMobile.StopAdvertisingAndListening should be called once
08-11 07:36:57.653  3365  3413 I jxcore-log: 
,08-11 07:36:57.696  3365  3413 I jxcore-log: ok 289 no error
08-11 07:36:57.696  3365  3413 I jxcore-log: 
08-11 07:36:57.696  3365  3413 I jxcore-log: ok 290 should be 204
08-11 07:36:57.696  3365  3413 I jxcore-log: 
,08-11 07:36:57.700  3365  3413 I jxcore-log: # teardown
08-11 07:36:57.700  3365  3413 I jxcore-log: 
,08-11 07:36:57.740  3365  3413 I jxcore-log: # setup
08-11 07:36:57.740  3365  3413 I jxcore-log: 
,08-11 07:36:57.829  3365  3413 I jxcore-log: # 95. Pass a string to ThaliNotificationServer.start
08-11 07:36:57.829  3365  3413 I jxcore-log: 
,08-11 07:36:57.902  3365  3413 I jxcore-log: ok 291 StartUpdateAdvertisingAndListening should not be called
08-11 07:36:57.902  3365  3413 I jxcore-log: 
,08-11 07:36:57.904  3365  3413 I jxcore-log: # teardown
08-11 07:36:57.904  3365  3413 I jxcore-log: 
,08-11 07:36:57.943  3365  3413 I jxcore-log: # setup
08-11 07:36:57.943  3365  3413 I jxcore-log: 
,08-11 07:36:58.016  3365  3413 I jxcore-log: # 96. Pass an empty parameter to ThaliNotificationServer.start
08-11 07:36:58.016  3365  3413 I jxcore-log: 
,08-11 07:36:58.122  3365  3413 I jxcore-log: ok 292 StartUpdateAdvertisingAndListening should not be called
08-11 07:36:58.122  3365  3413 I jxcore-log: 
,08-11 07:36:58.124  3365  3413 I jxcore-log: # teardown
08-11 07:36:58.124  3365  3413 I jxcore-log: 
,08-11 07:36:58.178  3365  3413 I jxcore-log: # setup
08-11 07:36:58.178  3365  3413 I jxcore-log: 
,08-11 07:36:58.249  3365  3413 I jxcore-log: # 97. Make an HTTP request to /NotificationBeacons,
08-11 07:36:58.249  3365  3413 I jxcore-log: 
,08-11 07:36:58.460  3365  3413 I jxcore-log: ok 293 no error
08-11 07:36:58.460  3365  3413 I jxcore-log: 
,08-11 07:36:58.460  3365  3413 I jxcore-log: ok 294 should be 200
08-11 07:36:58.460  3365  3413 I jxcore-log: 
08-11 07:36:58.460  3365  3413 I jxcore-log: ok 295 should be equal
08-11 07:36:58.460  3365  3413 I jxcore-log: 
,08-11 07:36:58.467  3365  3413 I jxcore-log: ok 296 should be equal
08-11 07:36:58.467  3365  3413 I jxcore-log: 
,08-11 07:36:58.483  3365  3413 I jxcore-log: ok 297 (unnamed assert)
08-11 07:36:58.483  3365  3413 I jxcore-log: 
,08-11 07:36:58.517  3365  3413 I jxcore-log: ok 298 no error
08-11 07:36:58.517  3365  3413 I jxcore-log: 
08-11 07:36:58.518  3365  3413 I jxcore-log: ok 299 should be 204
08-11 07:36:58.518  3365  3413 I jxcore-log: 
,08-11 07:36:58.521  3365  3413 I jxcore-log: # teardown
08-11 07:36:58.521  3365  3413 I jxcore-log: 
,08-11 07:36:58.639  3365  3413 I jxcore-log: # setup
08-11 07:36:58.639  3365  3413 I jxcore-log: 
,08-11 07:36:58.743  3365  3413 I jxcore-log: # 98. Make an HTTP request to /NotificationBeacons (no keys)
08-11 07:36:58.743  3365  3413 I jxcore-log: 
,08-11 07:36:58.825  3365  3413 I jxcore-log: ok 300 error should be null
08-11 07:36:58.825  3365  3413 I jxcore-log: 
08-11 07:36:58.825  3365  3413 I jxcore-log: ok 301 should be 204
08-11 07:36:58.825  3365  3413 I jxcore-log: 
08-11 07:36:58.829  3365  3413 I jxcore-log: # teardown
08-11 07:36:58.829  3365  3413 I jxcore-log: 
,08-11 07:36:58.867  3365  3413 I jxcore-log: # setup
08-11 07:36:58.867  3365  3413 I jxcore-log: 
,08-11 07:36:58.944  3365  3413 I jxcore-log: # 99. Make an HTTP request to /NotificationBeaconsbefore calling start
08-11 07:36:58.944  3365  3413 I jxcore-log: 
,08-11 07:36:59.066  3365  3413 I jxcore-log: ok 302 should be 404
08-11 07:36:59.066  3365  3413 I jxcore-log: 
,08-11 07:36:59.069  3365  3413 I jxcore-log: # teardown
08-11 07:36:59.069  3365  3413 I jxcore-log: 
,08-11 07:36:59.115  3365  3413 I jxcore-log: # setup
08-11 07:36:59.115  3365  3413 I jxcore-log: 
,08-11 07:36:59.171  3365  3413 I jxcore-log: # 100. #testThaliPeerAction - test getters
08-11 07:36:59.171  3365  3413 I jxcore-log: 
,08-11 07:36:59.230  3365  3413 I jxcore-log: ok 303 getPeerIdentifier
08-11 07:36:59.230  3365  3413 I jxcore-log: 
08-11 07:36:59.231  3365  3413 I jxcore-log: ok 304 getConnectionType
08-11 07:36:59.231  3365  3413 I jxcore-log: 
,08-11 07:36:59.233  3365  3413 I jxcore-log: ok 305 getActionType
08-11 07:36:59.233  3365  3413 I jxcore-log: 
08-11 07:36:59.234  3365  3413 I jxcore-log: ok 306 getActionState
08-11 07:36:59.234  3365  3413 I jxcore-log: 
,08-11 07:36:59.236  3365  3413 I jxcore-log: ok 307 getPskIdentity
08-11 07:36:59.236  3365  3413 I jxcore-log: 
,08-11 07:36:59.238  3365  3413 I jxcore-log: ok 308 getPskKey
08-11 07:36:59.238  3365  3413 I jxcore-log: 
,08-11 07:36:59.244  3365  3413 I jxcore-log: # teardown
08-11 07:36:59.244  3365  3413 I jxcore-log: 
,08-11 07:36:59.283  3365  3413 I jxcore-log: # setup
08-11 07:36:59.283  3365  3413 I jxcore-log: 
,08-11 07:36:59.336  3365  3413 I jxcore-log: # 101. #testThaliPeerAction - start and kill
08-11 07:36:59.336  3365  3413 I jxcore-log: 
,08-11 07:36:59.389  3365  3413 I jxcore-log: ok 309 initial state
08-11 07:36:59.389  3365  3413 I jxcore-log: 
,08-11 07:36:59.391  3365  3413 I jxcore-log: ok 310 after start
08-11 07:36:59.391  3365  3413 I jxcore-log: 
,08-11 07:36:59.401  3365  3413 I jxcore-log: ok 311 after kill
08-11 07:36:59.401  3365  3413 I jxcore-log: 
,08-11 07:36:59.406  3365  3413 I jxcore-log: # teardown
08-11 07:36:59.406  3365  3413 I jxcore-log: 
,08-11 07:36:59.445  3365  3413 I jxcore-log: # setup
08-11 07:36:59.445  3365  3413 I jxcore-log: 
,08-11 07:36:59.515  3365  3413 I jxcore-log: # 102. #testThaliPeerAction - double start
08-11 07:36:59.515  3365  3413 I jxcore-log: 
,08-11 07:36:59.575  3365  3413 I jxcore-log: ok 312 should be equal
08-11 07:36:59.575  3365  3413 I jxcore-log: 
,08-11 07:36:59.577  3365  3413 I jxcore-log: # teardown
08-11 07:36:59.577  3365  3413 I jxcore-log: 
,08-11 07:36:59.645  3365  3413 I jxcore-log: # setup
08-11 07:36:59.645  3365  3413 I jxcore-log: 
,08-11 07:36:59.696  3365  3413 I jxcore-log: # 103. #testThaliPeerAction - start after kill
08-11 07:36:59.696  3365  3413 I jxcore-log: 
,08-11 07:36:59.789  3365  3413 I jxcore-log: ok 313 clean kill
08-11 07:36:59.789  3365  3413 I jxcore-log: 
,08-11 07:36:59.791  3365  3413 I jxcore-log: ok 314 should be equal
08-11 07:36:59.791  3365  3413 I jxcore-log: 
,08-11 07:36:59.793  3365  3413 I jxcore-log: # teardown
08-11 07:36:59.793  3365  3413 I jxcore-log: 
,08-11 07:36:59.875  3365  3413 I jxcore-log: # setup
08-11 07:36:59.875  3365  3413 I jxcore-log: 
,08-11 07:36:59.933  3365  3413 I jxcore-log: # 104. #testThaliPeerAction - make sure ids are unique
08-11 07:36:59.933  3365  3413 I jxcore-log: 
,08-11 07:36:59.989  3365  3413 I jxcore-log: ok 315 should not be equal
08-11 07:36:59.989  3365  3413 I jxcore-log: 
,08-11 07:36:59.994  3365  3413 I jxcore-log: # teardown
08-11 07:36:59.994  3365  3413 I jxcore-log: 
,08-11 07:37:00.031  3365  3413 I jxcore-log: # setup
08-11 07:37:00.031  3365  3413 I jxcore-log: 
,08-11 07:37:00.095  3365  3413 I jxcore-log: # 105. Test PeerConnectionInformation basics
08-11 07:37:00.095  3365  3413 I jxcore-log: 
,08-11 07:37:00.183  3365  3413 I jxcore-log: ok 316 connection type works
08-11 07:37:00.183  3365  3413 I jxcore-log: 
,08-11 07:37:00.184  3365  3413 I jxcore-log: ok 317 getHostAddress works
08-11 07:37:00.184  3365  3413 I jxcore-log: 
,08-11 07:37:00.186  3365  3413 I jxcore-log: ok 318 getPortNumber works
08-11 07:37:00.186  3365  3413 I jxcore-log: 
,08-11 07:37:00.187  3365  3413 I jxcore-log: ok 319 getSuggestedTCPTimeout works
08-11 07:37:00.187  3365  3413 I jxcore-log: 
,08-11 07:37:00.193  3365  3413 I jxcore-log: # teardown
08-11 07:37:00.193  3365  3413 I jxcore-log: 
,08-11 07:37:00.231  3365  3413 I jxcore-log: # setup
08-11 07:37:00.231  3365  3413 I jxcore-log: 
,08-11 07:37:00.282  3365  3413 I jxcore-log: # 106. Test PeerDictionary basic functionality
08-11 07:37:00.282  3365  3413 I jxcore-log: 
,08-11 07:37:00.384  3365  3413 I jxcore-log: ok 320 Entry counter must be 1
08-11 07:37:00.384  3365  3413 I jxcore-log: 
,08-11 07:37:00.385  3365  3413 I jxcore-log: ok 321 Size must be 1
08-11 07:37:00.385  3365  3413 I jxcore-log: 
,08-11 07:37:00.386  3365  3413 I jxcore-log: ok 322 Entry counter must be 2
08-11 07:37:00.386  3365  3413 I jxcore-log: 
08-11 07:37:00.386  3365  3413 I jxcore-log: ok 323 Size must be 2
08-11 07:37:00.386  3365  3413 I jxcore-log: 
,08-11 07:37:00.387  3365  3413 I jxcore-log: ok 324 Entry2 should not be found
08-11 07:37:00.387  3365  3413 I jxcore-log: 
08-11 07:37:00.387  3365  3413 I jxcore-log: ok 325 Size must be 1
08-11 07:37:00.387  3365  3413 I jxcore-log: 
,08-11 07:37:00.388  3365  3413 I jxcore-log: ok 326 Size must be 0
08-11 07:37:00.388  3365  3413 I jxcore-log: 
08-11 07:37:00.390  3365  3413 I jxcore-log: # teardown
08-11 07:37:00.390  3365  3413 I jxcore-log: 
08-11 07:37:00.436  3365  3413 I jxcore-log: # setup
08-11 07:37:00.436  3365  3413 I jxcore-log: 
,08-11 07:37:00.480  3365  3413 I jxcore-log: # 107. Test PeerDictionary with multiple entries.
08-11 07:37:00.480  3365  3413 I jxcore-log: 
,08-11 07:37:01.273  3365  3413 I jxcore-log: ok 327 Size must be100
08-11 07:37:01.273  3365  3413 I jxcore-log: 
,08-11 07:37:01.277  3365  3413 I jxcore-log: ok 328 Entries between 20 and MAXSIZE + 20 should exist
08-11 07:37:01.277  3365  3413 I jxcore-log: 
,08-11 07:37:02.048  3365  3413 I jxcore-log: ok 329 WAITING state entry should not be removed
08-11 07:37:02.048  3365  3413 I jxcore-log: 
,08-11 07:37:02.049  3365  3413 I jxcore-log: # teardown
08-11 07:37:02.049  3365  3413 I jxcore-log: 
,08-11 07:37:02.267  3365  3413 I jxcore-log: # setup
08-11 07:37:02.267  3365  3413 I jxcore-log: 
,08-11 07:37:02.321  3365  3413 I jxcore-log: # 108. RESOLVED entries are removed before WAITING state entry.
08-11 07:37:02.321  3365  3413 I jxcore-log: 
,08-11 07:37:03.033  3365  3413 I jxcore-log: ok 330 Entries between 6 and MAXSIZE + 4 should exist
08-11 07:37:03.033  3365  3413 I jxcore-log: 
08-11 07:37:03.033  3365  3413 I jxcore-log: ok 331 Size should be MAXSIZE
08-11 07:37:03.033  3365  3413 I jxcore-log: 
,08-11 07:37:03.033  3365  3413 I jxcore-log: ok 332 Size should be MAXSIZE+6
08-11 07:37:03.033  3365  3413 I jxcore-log: 
08-11 07:37:03.035  3365  3413 I jxcore-log: # teardown
08-11 07:37:03.035  3365  3413 I jxcore-log: 
,08-11 07:37:03.079  3365  3413 I jxcore-log: # setup
08-11 07:37:03.079  3365  3413 I jxcore-log: 
,08-11 07:37:03.112  3365  3413 I jxcore-log: # 109. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
08-11 07:37:03.112  3365  3413 I jxcore-log: 
,08-11 07:37:03.775  3365  3413 I jxcore-log: ok 333 WAITING state entry should not be removed
08-11 07:37:03.775  3365  3413 I jxcore-log: 
,08-11 07:37:03.777  3365  3413 I jxcore-log: ok 334 Waiting entries between 6 and MAXSIZE + 4 should exist
08-11 07:37:03.777  3365  3413 I jxcore-log: 
,08-11 07:37:03.777  3365  3413 I jxcore-log: ok 335 Size should be MAXSIZE
08-11 07:37:03.777  3365  3413 I jxcore-log: 
,08-11 07:37:03.777  3365  3413 I jxcore-log: ok 336 entryCounter should be MAXSIZE+6
08-11 07:37:03.777  3365  3413 I jxcore-log: 
,08-11 07:37:03.779  3365  3413 I jxcore-log: # teardown
08-11 07:37:03.779  3365  3413 I jxcore-log: 
,08-11 07:37:03.861  3365  3413 I jxcore-log: # setup
08-11 07:37:03.861  3365  3413 I jxcore-log: 
,08-11 07:37:03.896  3365  3413 I jxcore-log: # 110. When CONTROLLED_BY_POOL entry is removed and kill is called.
08-11 07:37:03.896  3365  3413 I jxcore-log: 
,08-11 07:37:04.616  3365  3413 I jxcore-log: ok 337 Kill should be called once
08-11 07:37:04.616  3365  3413 I jxcore-log: 
,08-11 07:37:04.617  3365  3413 I jxcore-log: ok 338 Size should be 100
08-11 07:37:04.617  3365  3413 I jxcore-log: 
,08-11 07:37:04.618  3365  3413 I jxcore-log: # teardown
08-11 07:37:04.618  3365  3413 I jxcore-log: 
,08-11 07:37:04.675  3365  3413 I jxcore-log: # setup
08-11 07:37:04.675  3365  3413 I jxcore-log: 
,08-11 07:37:04.717  3365  3413 I jxcore-log: # 111. #ThaliPeerPoolInterface - bad enqueues
08-11 07:37:04.717  3365  3413 I jxcore-log: 
,08-11 07:37:04.759  3365  3413 I jxcore-log: ok 339 null arg
08-11 07:37:04.759  3365  3413 I jxcore-log: 
,08-11 07:37:04.761  3365  3413 I jxcore-log: ok 340 wrong arg type
08-11 07:37:04.761  3365  3413 I jxcore-log: 
,08-11 07:37:04.763  3365  3413 I jxcore-log: ok 341 wrong state
08-11 07:37:04.763  3365  3413 I jxcore-log: 
,08-11 07:37:04.766  3365  3413 I jxcore-log: # teardown
08-11 07:37:04.766  3365  3413 I jxcore-log: 
,08-11 07:37:04.806  3365  3413 I jxcore-log: # setup
08-11 07:37:04.806  3365  3413 I jxcore-log: 
,08-11 07:37:04.859  3365  3413 I jxcore-log: # 112. #ThaliPeerPoolInterface - do not allow same object type
08-11 07:37:04.859  3365  3413 I jxcore-log: 
,08-11 07:37:04.900  3365  3413 I jxcore-log: ok 342 good enqueue
08-11 07:37:04.900  3365  3413 I jxcore-log: ,
,08-11 07:37:04.903  3365  3413 I jxcore-log: ok 343 should be equal
08-11 07:37:04.903  3365  3413 I jxcore-log: 
,08-11 07:37:04.905  3365  3413 I jxcore-log: # teardown
08-11 07:37:04.905  3365  3413 I jxcore-log: 
,08-11 07:37:04.991  3365  3413 I jxcore-log: # setup
08-11 07:37:04.991  3365  3413 I jxcore-log: 
,08-11 07:37:05.049  3365  3413 I jxcore-log: # 113. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
08-11 07:37:05.049  3365  3413 I jxcore-log: 
,08-11 07:37:05.096  3365  3413 I jxcore-log: ok 344 good enqueue
08-11 07:37:05.096  3365  3413 I jxcore-log: 
,08-11 07:37:05.099  3365  3413 I jxcore-log: ok 345 2nd good enqueue
08-11 07:37:05.099  3365  3413 I jxcore-log: 
,08-11 07:37:05.100  3365  3413 I jxcore-log: ok 346 we are in the pool
08-11 07:37:05.100  3365  3413 I jxcore-log: 
,08-11 07:37:05.105  3365  3413 I jxcore-log: ok 347 We are out of the pool
08-11 07:37:05.105  3365  3413 I jxcore-log: 
,08-11 07:37:05.106  3365  3413 I jxcore-log: ok 348 Action was killed
08-11 07:37:05.106  3365  3413 I jxcore-log: 
08-11 07:37:05.107  3365  3413 I jxcore-log: ok 349 The original kill was called too
08-11 07:37:05.107  3365  3413 I jxcore-log: 
,08-11 07:37:05.108  3365  3413 I jxcore-log: ok 350 second item is still in queue
08-11 07:37:05.108  3365  3413 I jxcore-log: 
,08-11 07:37:05.111  3365  3413 I jxcore-log: # teardown
08-11 07:37:05.111  3365  3413 I jxcore-log: 
,08-11 07:37:05.174  3365  3413 I jxcore-log: # setup
08-11 07:37:05.174  3365  3413 I jxcore-log: 
,08-11 07:37:05.213  3365  3413 I jxcore-log: # 114. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
08-11 07:37:05.213  3365  3413 I jxcore-log: 
,08-11 07:37:05.264  3365  3413 I jxcore-log: ok 351 good enqueue
08-11 07:37:05.264  3365  3413 I jxcore-log: 
,08-11 07:37:05.265  3365  3413 I jxcore-log: ok 352 first kill
08-11 07:37:05.265  3365  3413 I jxcore-log: 
08-11 07:37:05.266  3365  3413 I jxcore-log: ok 353 second NOOP kill
08-11 07:37:05.266  3365  3413 I jxcore-log: 
,08-11 07:37:05.269  3365  3413 I jxcore-log: # teardown
08-11 07:37:05.269  3365  3413 I jxcore-log: 
,08-11 07:37:05.322  3365  3413 I jxcore-log: # setup
08-11 07:37:05.322  3365  3413 I jxcore-log: 
,08-11 07:37:05.374  3365  3413 I jxcore-log: # 115. Make sure peerDictionaryKey is reasonable
08-11 07:37:05.374  3365  3413 I jxcore-log: 
,08-11 07:37:05.433  3365  3413 I jxcore-log: ok 354 equal keys
08-11 07:37:05.433  3365  3413 I jxcore-log: 
,08-11 07:37:05.434  3365  3413 I jxcore-log: ok 355 not equal connection type
08-11 07:37:05.434  3365  3413 I jxcore-log: 
,08-11 07:37:05.436  3365  3413 I jxcore-log: ok 356 same connection type, different buffer
08-11 07:37:05.436  3365  3413 I jxcore-log: 
,08-11 07:37:05.439  3365  3413 I jxcore-log: # teardown
08-11 07:37:05.439  3365  3413 I jxcore-log: 
,08-11 07:37:05.488  3365  3413 I jxcore-log: # setup
08-11 07:37:05.488  3365  3413 I jxcore-log: 
,08-11 07:37:05.536  3365  3413 I jxcore-log: # 116. Make sure start works
08-11 07:37:05.536  3365  3413 I jxcore-log: 
,08-11 07:37:05.613  3365  3413 I jxcore-log: ok 357 First start and on called correctly
08-11 07:37:05.613  3365  3413 I jxcore-log: 
,08-11 07:37:05.615  3365  3413 I jxcore-log: # teardown
08-11 07:37:05.615  3365  3413 I jxcore-log: 
,08-11 07:37:05.676  3365  3413 I jxcore-log: # setup
08-11 07:37:05.676  3365  3413 I jxcore-log: 
,08-11 07:37:05.841  3365  3413 I jxcore-log: # 117. Make sure stop works
08-11 07:37:05.841  3365  3413 I jxcore-log: 
,08-11 07:37:06.657  3365  3413 I jxcore-log: ok 358 second cleared dictionary
08-11 07:37:06.657  3365  3413 I jxcore-log: 
,08-11 07:37:06.677  3365  3413 I jxcore-log: ok 359 First start and on called correctly
08-11 07:37:06.677  3365  3413 I jxcore-log: 
,08-11 07:37:06.692  3365  3413 I jxcore-log: ok 360 First stop and removeListener called correctly
08-11 07:37:06.692  3365  3413 I jxcore-log: 
,08-11 07:37:06.693  3365  3413 I jxcore-log: ok 361 first action kill called
08-11 07:37:06.693  3365  3413 I jxcore-log: 
08-11 07:37:06.693  3365  3413 I jxcore-log: ok 362 second action kill called
08-11 07:37:06.693  3365  3413 I jxcore-log: 
,08-11 07:37:06.693  3365  3413 I jxcore-log: ok 363 first cleared dictionary
08-11 07:37:06.693  3365  3413 I jxcore-log: 
08-11 07:37:06.694  3365  3413 I jxcore-log: ok 364 second cleared dictionary
08-11 07:37:06.694  3365  3413 I jxcore-log: 
,08-11 07:37:06.696  3365  3413 I jxcore-log: # teardown
08-11 07:37:06.696  3365  3413 I jxcore-log: 
,08-11 07:37:06.729  3365  3413 I jxcore-log: # setup
08-11 07:37:06.729  3365  3413 I jxcore-log: 
,08-11 07:37:06.768  3365  3413 I jxcore-log: # 118. Simple peer event
08-11 07:37:06.768  3365  3413 I jxcore-log: 
,08-11 07:37:06.850  3365  3413 I jxcore-log: ok 365 listener has been set
08-11 07:37:06.850  3365  3413 I jxcore-log: 
,08-11 07:37:06.856  3365  3413 I jxcore-log: ok 366 peer dictionary has expected number of entries
08-11 07:37:06.856  3365  3413 I jxcore-log: 
,08-11 07:37:06.857  3365  3413 I jxcore-log: ok 367 Dictionary and pool have same action
08-11 07:37:06.857  3365  3413 I jxcore-log: 
,08-11 07:37:06.857  3365  3413 I jxcore-log: ok 368 ads match
08-11 07:37:06.857  3365  3413 I jxcore-log: 
08-11 07:37:06.858  3365  3413 I jxcore-log: ok 369 PouchDB matches
08-11 07:37:06.858  3365  3413 I jxcore-log: 
,08-11 07:37:06.858  3365  3413 I jxcore-log: ok 370 DB Names match
08-11 07:37:06.858  3365  3413 I jxcore-log: 
,08-11 07:37:06.859  3365  3413 I jxcore-log: ok 371 public keys match
08-11 07:37:06.859  3365  3413 I jxcore-log: 
08-11 07:37:06.863  3365  3413 I jxcore-log: ok 372 peer dictionary has expected number of entries
08-11 07:37:06.863  3365  3413 I jxcore-log: 
,08-11 07:37:06.864  3365  3413 I jxcore-log: ok 373 Dictionary and pool have same action
08-11 07:37:06.864  3365  3413 I jxcore-log: 
,08-11 07:37:06.864  3365  3413 I jxcore-log: ok 374 ads match
08-11 07:37:06.864  3365  3413 I jxcore-log: 
,08-11 07:37:06.865  3365  3413 I jxcore-log: ok 375 PouchDB matches
08-11 07:37:06.865  3365  3413 I jxcore-log: 
,08-11 07:37:06.866  3365  3413 I jxcore-log: ok 376 DB Names match
08-11 07:37:06.866  3365  3413 I jxcore-log: 
,08-11 07:37:06.866  3365  3413 I jxcore-log: ok 377 public keys match
08-11 07:37:06.866  3365  3413 I jxcore-log: 
,08-11 07:37:06.869  3365  3413 I jxcore-log: ok 378 start called once
08-11 07:37:06.869  3365  3413 I jxcore-log: 
,08-11 07:37:06.869  3365  3413 I jxcore-log: ok 379 kill never called
08-11 07:37:06.869  3365  3413 I jxcore-log: 
,08-11 07:37:06.870  3365  3413 I jxcore-log: ok 380 One entry left
08-11 07:37:06.870  3365  3413 I jxcore-log: 
08-11 07:37:06.870  3365  3413 I jxcore-log: ok 381 Dictionary and pool have same action
08-11 07:37:06.870  3365  3413 I jxcore-log: 
,08-11 07:37:06.872  3365  3413 I jxcore-log: ok 382 Start never called
08-11 07:37:06.872  3365  3413 I jxcore-log: 
08-11 07:37:06.873  3365  3413 I jxcore-log: ok 383 Kill called once
08-11 07:37:06.873  3365  3413 I jxcore-log: 
08-11 07:37:06.873  3365  3413 I jxcore-log: ok 384 no entries left
08-11 07:37:06.873  3365  3413 I jxcore-log: 
,08-11 07:37:06.886  3365  3413 I jxcore-log: ok 385 Third action is dead
08-11 07:37:06.886  3365  3413 I jxcore-log: 
,08-11 07:37:06.886  3365  3413 I jxcore-log: ok 386 peer dictionary has expected number of entries
08-11 07:37:06.886  3365  3413 I jxcore-log: 
08-11 07:37:06.887  3365  3413 I jxcore-log: ok 387 Dictionary and pool have same action
08-11 07:37:06.887  3365  3413 I jxcore-log: 
,08-11 07:37:06.887  3365  3413 I jxcore-log: ok 388 ads match
08-11 07:37:06.887  3365  3413 I jxcore-log: 
08-11 07:37:06.887  3365  3413 I jxcore-log: ok 389 PouchDB matches
08-11 07:37:06.887  3365  3413 I jxcore-log: 
08-11 07:37:06.887  3365  3413 I jxcore-log: ok 390 DB Names match
08-11 07:37:06.887  3365  3413 I jxcore-log: 
,08-11 07:37:06.888  3365  3413 I jxcore-log: ok 391 public keys match
08-11 07:37:06.888  3365  3413 I jxcore-log: 
08-11 07:37:06.890  3365  3413 I jxcore-log: # teardown
08-11 07:37:06.890  3365  3413 I jxcore-log: 
,08-11 07:37:06.979  3365  3413 I jxcore-log: # setup
08-11 07:37:06.979  3365  3413 I jxcore-log: 
,08-11 07:37:07.103  3365  3413 I jxcore-log: # 119. Coordinated pull replication from notification test
08-11 07:37:07.103  3365  3413 I jxcore-log: 
,08-11 07:37:07.349  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:37:07.349  3365  3413 I jxcore-log: 
,08-11 07:37:07.352  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 49347
08-11 07:37:07.352  3365  3413 I jxcore-log: 
,08-11 07:37:07.356  3365  3413 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-11 07:37:07.359  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 41335, start advertisements: false
,08-11 07:37:07.359  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:37:07.359  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 07:37:07.359  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 07:37:07.359  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 07:37:07.360  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:37:07.360  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 07:37:07.364  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 07:37:07.369  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 07:37:07.369  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:37:07.369  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 07:37:07.371  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:37:07.374  3428  3925 D BtGatt.GattService: registerClient() - UUID=3dd9768b-3976-4731-8c3c-bad7010c51a7
,08-11 07:37:07.375  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=3dd9768b-3976-4731-8c3c-bad7010c51a7, clientIf=5
,08-11 07:37:07.376  3365  3376 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 07:37:07.376  3428  3469 D BtGatt.GattService: start scan with filters
,08-11 07:37:07.381  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:37:07.382  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 07:37:07.382  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:37:07.382  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-11 07:37:07.382  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 07:37:07.389  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:37:07.389  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:37:07.389  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-11 07:37:07.390  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 07:37:07.390  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 07:37:07.391  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:37:07.396  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 07:37:07.397  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:37:07.397  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:37:07.397  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 07:37:07.397  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:37:07.400  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:37:07.419  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:37:07.420  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:07.428  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 07:37:07.429  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:07.892  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 07:37:07.892  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 07:37:07.893  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:37:07.918  3365  3413 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-11 07:37:07.922  3365  3413 I io.jxcore.node.ConnectionHelper: start: Port number: 49347, start advertisements: true
08-11 07:37:07.922  3365  3413 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-11 07:37:07.922  3365  3413 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-11 07:37:07.923  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 07:37:07.923  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 07:37:07.924  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:37:07.924  3428  3469 D BtGatt.GattService: stopScan() - queue size =1
,08-11 07:37:07.928  3428  3438 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:37:07.929  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 07:37:07.930  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:37:07.932  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 07:37:07.932  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 07:37:07.933  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 07:37:07.933  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 07:37:07.935  3428  3428 D BtGatt.ScanManager: awakened up at time 872104
08-11 07:37:07.936  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:37:07.944  3428  3469 D BtGatt.GattService: registerClient() - UUID=537b6cab-ee30-4594-bf76-455f112329ef
08-11 07:37:07.945  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 07:37:07.945  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:37:07.946  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:37:07.947  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=537b6cab-ee30-4594-bf76-455f112329ef, clientIf=5
08-11 07:37:07.948  3365  3375 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 07:37:07.949  3428  3932 D BtGatt.GattService: start scan with filters
,08-11 07:37:07.954  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 07:37:07.955  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 07:37:07.955  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-11 07:37:07.955  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 07:37:07.955  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 07:37:07.955  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 07:37:07.956  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-11 07:37:07.957  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-11 07:37:07.958  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-11 07:37:07.958  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 07:37:07.958  3365  3948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 07:37:07.959  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-11 07:37:07.959  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-11 07:37:07.959  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 07:37:07.959  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 07:37:07.959  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:37:07.960  3428  3490 D BtGatt.GattService: stopScan() - queue size =0
08-11 07:37:07.961  3365  3948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-11 07:37:07.962  3428  3925 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 07:37:07.962  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:37:07.962  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 07:37:07.962  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 07:37:07.962  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 07:37:07.962  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 07:37:07.963  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 07:37:07.963  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:07.963  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-11 07:37:07.964  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:37:07.965  3365  3413 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 07:37:07.967  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-11 07:37:07.967  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 07:37:07.967  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
08-11 07:37:07.968  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:37:07.969  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 07:37:07.969  3365  3413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-11 07:37:07.969  3365  3413 D BluetoothAdapter: STATE_ON
,08-11 07:37:07.973  3428  3932 D BtGatt.GattService: registerClient() - UUID=15d9b721-ef59-4791-a64f-ee6b57bce4ad
08-11 07:37:07.974  3428  3457 D BtGatt.GattService: onClientRegistered() - UUID=15d9b721-ef59-4791-a64f-ee6b57bce4ad, clientIf=5
08-11 07:37:07.974  3365  3376 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-11 07:37:07.975  3428  3459 D BtGatt.AdvertiseManager: message : 0
,08-11 07:37:07.977  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-11 07:37:07.977  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:37:07.977  3428  3457 D BtGatt.GattService: current time is 872145781317
08-11 07:37:07.977  3428  3457 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -65, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-11 07:37:07.977  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 07:37:07.977  3428  3457 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-11 07:37:07.978  3428  3459 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 07:37:07.980  3428  3460 D BtGatt.ScanManager: handling starting scan
,08-11 07:37:07.989  3428  3457 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 07:37:07.994  3428  3457 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 07:37:07.994  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:37:07.994  3428  3460 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 07:37:07.998  3428  3457 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 07:37:07.998  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-11 07:37:07.998  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 07:37:07.999  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 07:37:08.000  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 07:37:08.000  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:37:08.000  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-11 07:37:08.000  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-11 07:37:08.000  3365  3365 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-11 07:37:08.001  3365  3365 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 07:37:08.001  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-11 07:37:08.001  3365  3413 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 07:37:08.002  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 07:37:08.002  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:08.002  3428  3460 D BtGatt.ScanManager: Starting BLE batch scan
08-11 07:37:08.002  3428  3460 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-11 07:37:08.003  3365  3365 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-11 07:37:08.003  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-11 07:37:08.007  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 07:37:08.007  3365  3413 I jxcore-log: 
,08-11 07:37:08.013  3428  3457 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 07:37:08.013  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:08.017  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 07:37:08.017  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:08.023  3428  3457 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 07:37:08.023  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:08.023  3428  3460 D BtGatt.ScanManager: stopping BLe Batch
,08-11 07:37:08.028  3428  3457 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 07:37:08.028  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 07:37:08.028  3428  3460 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 07:37:08.033  3428  3457 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 07:37:08.033  3428  3457 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 07:37:08.504  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-11 07:37:08.504  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-11 07:37:08.505  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:37:08.515  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-11 07:37:08.515  3365  3413 I jxcore-log: 
,08-11 07:37:20.682   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=884850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:37:26.029   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=890197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:37:27.295  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:37:27.299  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:37:27.345  1528  1898 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:37:27.345  1528  1898 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:37:27.346  1528  1898 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:37:27.346  1528  1898 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:37:27.377  3138  3951 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:37:27.377  3138  3951 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:37:27.377  3138  3951 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	... 12 more
08-11 07:37:27.377  3138  3951 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at fal.a(PG:38)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:37:27.377  3138  3951 E HttpOperation: 	... 14 more
,08-11 07:37:27.478  1528  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:37:27.478  1528  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:37:27.478  1528  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:37:27.478  1528  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:37:27.511  3138  3951 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:37:27.511  3138  3951 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at hec.a(PG:42)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at hee.a(PG:102)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at czr.a(PG:65)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at kka.a(PG:108)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:37:27.511  3138  3951 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	... 15 more
08-11 07:37:27.511  3138  3951 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at fal.a(PG:38)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:37:27.511  3138  3951 E HttpOperation: 	... 17 more
,08-11 07:37:27.511  3138  3951 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:37:27.511  3138  3951 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	... 15 more
08-11 07:37:27.511  3138  3951 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:37:27.511  3138  3951 E ExperimentLoader: 	... 17 more
,08-11 07:37:27.649   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 873957, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:37:32.096   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=896264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:37:51.082   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=915250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:37:57.109   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=921277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:38:12.709   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=936877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:38:22.175   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:38:41.189   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=965357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:38:47.216   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=971383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:39:06.256   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=990423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:39:12.282   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=996450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:39:27.414  1528  1955 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 07:39:31.349   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1015517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:39:37.616   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1021784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:39:56.629   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1040797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:40:02.669   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1046837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:40:21.682   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1065850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:40:27.722   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:40:46.736   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1090904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:40:52.789   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1096956, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:41:11.802   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1115970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:41:17.829   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:41:36.856   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1141024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:41:42.895   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1147063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 07:41:50.435  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:41:50.440  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 07:41:50.501  1528  1886 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:41:50.501  1528  1886 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:41:50.501  1528  1886 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 07:41:50.502  1528  1886 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:41:50.542  3138  3968 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 07:41:50.542  3138  3968 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at blb.a(PG:3937)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at czp.a(PG:18188)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:41:50.542  3138  3968 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	... 12 more
08-11 07:41:50.542  3138  3968 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at fal.a(PG:38)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:41:50.542  3138  3968 E HttpOperation: 	... 14 more
,08-11 07:41:50.620  1528  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 07:41:50.620  1528  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 07:41:50.620  1528  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 07:41:50.620  1528  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 07:41:50.658  3138  3968 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 07:41:50.658  3138  3968 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jdm.a(PG:82)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jcs.o(PG:406)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jcn.a(PG:1379)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jcs.i(PG:143)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at hec.a(PG:42)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at hee.a(PG:102)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at czr.a(PG:65)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at kka.a(PG:108)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at czp.a(PG:19176)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at czp.a(PG:9081)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at czq.run(PG:1686)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:41:50.658  3138  3968 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jdj.a(PG:4091)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jdj.a(PG:1125)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jdm.a(PG:77)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	... 15 more
08-11 07:41:50.658  3138  3968 E HttpOperation: Caused by: faj: BadAuthentication
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at fal.a(PG:38)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	at jdj.a(PG:4089)
08-11 07:41:50.658  3138  3968 E HttpOperation: 	... 17 more
08-11 07:41:50.658  3138  3968 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 07:41:50.658  3138  3968 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at hec.a(PG:42)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at hee.a(PG:102)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at czr.a(PG:65)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at kka.a(PG:108)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	... 15 more
08-11 07:41:50.658  3138  3968 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at fal.a(PG:38)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 07:41:50.658  3138  3968 E ExperimentLoader: 	... 17 more
,08-11 07:41:50.789   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1154073, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 07:42:01.909   873  3532 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1166077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 07:42:07.189  3365  3413 I jxcore-log: not ok 392 failed with Error: We ran out of time
08-11 07:42:07.189  3365  3413 I jxcore-log: 
,08-11 07:42:07.190  3365  3413 I jxcore-log:   ---
08-11 07:42:07.190  3365  3413 I jxcore-log: 
08-11 07:42:07.190  3365  3413 I jxcore-log:     operator: fail
08-11 07:42:07.190  3365  3413 I jxcore-log: 
08-11 07:42:07.191  3365  3413 I jxcore-log:   ...
08-11 07:42:07.191  3365  3413 I jxcore-log: 
,08-11 07:42:07.199  3365  3413 I jxcore-log: # teardown
08-11 07:42:07.199  3365  3413 I jxcore-log: 
,08-11 07:42:07.272  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-11 07:42:07.272  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:42:07.273  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-11 07:42:07.273  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 07:42:07.273  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-11 07:42:07.273  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 07:42:07.273  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 07:42:07.275  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 07:42:07.275  3365  3948 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 07:42:07.276  3365  3413 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 07:42:07.276  3365  3948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 07:42:07.278  3365  3413 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 07:42:07.278  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 07:42:07.278  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 07:42:07.278  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 07:42:07.278  3365  3365 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 07:42:07.281  3365  3948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 07:42:07.281  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 07:42:07.284  3365  3413 D BluetoothAdapter: STATE_ON
08-11 07:42:07.284  3365  3413 D BluetoothLeScanner: could not find callback wrapper
08-11 07:42:07.284  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 07:42:07.285  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-11 07:42:07.287  3428  3459 D BtGatt.AdvertiseManager: message : 1
,08-11 07:42:07.288  3428  3459 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 07:42:07.304  3428  3457 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-11 07:42:07.305  3428  3457 D BtGatt.GattService: Client app is not null!
,08-11 07:42:07.307  3428  3439 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 07:42:07.308  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-11 07:42:07.309  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-11 07:42:07.309  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 07:42:07.309  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-11 07:42:07.309  3365  3413 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 07:42:07.313  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 07:42:07.313  3365  3413 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 07:42:07.313  3365  3413 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 07:42:07.314  3365  3413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 07:42:07.316  3365  3365 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 07:42:07.317  3365  3365 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 07:42:07.317  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 07:42:07.317  3365  3365 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 07:42:07.318  3365  3365 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 07:42:07.318  3365  3365 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 07:42:07.325  3365  3413 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-11 07:42:07.325  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 07:42:07.325  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 07:42:07.326  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 07:42:07.328  3365  3413 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-11 07:42:07.328  3365  3413 I jxcore-log: 
08-11 07:42:07.330  3365  3413 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-11 07:42:07.330  3365  3413 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-11 07:42:07.330  3365  3413 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 07:42:07.330  3365  3413 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 07:42:07.341  3365  3413 I jxcore-log: # setup
08-11 07:42:07.341  3365  3413 I jxcore-log: 
,08-11 07:42:07.476  3365  3413 I jxcore-log: # 120. Server is not there
08-11 07:42:07.476  3365  3413 I jxcore-log: 
,08-11 07:42:07.654  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
08-11 07:42:07.654  3365  3413 I jxcore-log: 
,08-11 07:42:07.656  3365  3413 I jxcore-log: ok 393 right error
08-11 07:42:07.656  3365  3413 I jxcore-log: 
,08-11 07:42:07.661  3365  3413 I jxcore-log: # teardown
08-11 07:42:07.661  3365  3413 I jxcore-log: 
,08-11 07:42:07.745  3365  3413 I jxcore-log: # setup
08-11 07:42:07.745  3365  3413 I jxcore-log: 
,08-11 07:42:07.790  3365  3413 I jxcore-log: # 121. Server accepts & closes connection
08-11 07:42:07.790  3365  3413 I jxcore-log: 
,08-11 07:42:07.820  3365  3365 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 07:42:07.824  3365  3413 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 07:42:07.824  3365  3413 I jxcore-log: 
,08-11 07:42:07.989  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
08-11 07:42:07.989  3365  3413 I jxcore-log: 
,08-11 07:42:07.991  3365  3413 I jxcore-log: ok 394 right error
08-11 07:42:07.991  3365  3413 I jxcore-log: 
,08-11 07:42:07.995  3365  3413 I jxcore-log: # teardown
08-11 07:42:07.995  3365  3413 I jxcore-log: 
,08-11 07:42:08.077  3365  3413 I jxcore-log: # setup
08-11 07:42:08.077  3365  3413 I jxcore-log: 
,08-11 07:42:08.138  3365  3413 I jxcore-log: # 122. Server always returns 500
08-11 07:42:08.138  3365  3413 I jxcore-log: 
,08-11 07:42:08.324  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-11 07:42:08.324  3365  3413 I jxcore-log: 
,08-11 07:42:08.326  3365  3413 I jxcore-log: ok 395 Got error as expected
08-11 07:42:08.326  3365  3413 I jxcore-log: 
,08-11 07:42:08.330  3365  3413 I jxcore-log: # teardown
08-11 07:42:08.330  3365  3413 I jxcore-log: 
,08-11 07:42:08.381  3365  3413 I jxcore-log: # setup
08-11 07:42:08.381  3365  3413 I jxcore-log: 
,08-11 07:42:08.429  3365  3413 I jxcore-log: # 123. Server always returns 401
08-11 07:42:08.429  3365  3413 I jxcore-log: 
,08-11 07:42:08.592  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-11 07:42:08.592  3365  3413 I jxcore-log: 
,08-11 07:42:08.595  3365  3413 I jxcore-log: ok 396 Got error as expected
08-11 07:42:08.595  3365  3413 I jxcore-log: 
,08-11 07:42:08.599  3365  3413 I jxcore-log: # teardown
08-11 07:42:08.599  3365  3413 I jxcore-log: 
,08-11 07:42:08.702  3365  3413 I jxcore-log: # setup
08-11 07:42:08.702  3365  3413 I jxcore-log: 
,08-11 07:42:08.750  3365  3413 I jxcore-log: # 124. Server always returns 403
08-11 07:42:08.750  3365  3413 I jxcore-log: 
,08-11 07:42:08.939  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-11 07:42:08.939  3365  3413 I jxcore-log: 
,08-11 07:42:08.941  3365  3413 I jxcore-log: ok 397 Got error as expected
08-11 07:42:08.941  3365  3413 I jxcore-log: 
,08-11 07:42:08.944  3365  3413 I jxcore-log: # teardown
08-11 07:42:08.944  3365  3413 I jxcore-log: 
,08-11 07:42:09.042  3365  3413 I jxcore-log: # setup
08-11 07:42:09.042  3365  3413 I jxcore-log: 
,08-11 07:42:09.081  3365  3413 I jxcore-log: # 125. Make sure docs replicate
08-11 07:42:09.081  3365  3413 I jxcore-log: 
,08-11 07:42:10.225  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Replication resumed
08-11 07:42:10.225  3365  3413 I jxcore-log: 
,08-11 07:42:10.782  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-11 07:42:10.782  3365  3413 I jxcore-log: 
,08-11 07:42:10.923  3365  3413 I jxcore-log: ok 398 should be equal
08-11 07:42:10.923  3365  3413 I jxcore-log: 
,08-11 07:42:10.924  3365  3413 I jxcore-log: ok 399 All tests passed!
08-11 07:42:10.924  3365  3413 I jxcore-log: 
,08-11 07:42:10.929  3365  3413 I jxcore-log: # teardown
08-11 07:42:10.929  3365  3413 I jxcore-log: 
,08-11 07:42:11.201  3365  3413 I jxcore-log: # setup
08-11 07:42:11.201  3365  3413 I jxcore-log: 
,08-11 07:42:12.311  3365  3413 I jxcore-log: # 126. Do nothing and make sure we time out
08-11 07:42:12.311  3365  3413 I jxcore-log: 
,08-11 07:42:12.746  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-11 07:42:12.746  3365  3413 I jxcore-log: 
,08-11 07:42:14.457  3365  3413 I jxcore-log: ok 400 action should be killed
08-11 07:42:14.457  3365  3413 I jxcore-log: 
,08-11 07:42:14.459  3365  3413 I jxcore-log: ok 401 Error should be timed out
08-11 07:42:14.459  3365  3413 I jxcore-log: 
,08-11 07:42:14.560  3365  3413 I jxcore-log: ok 402 No doc found
08-11 07:42:14.560  3365  3413 I jxcore-log: 
,08-11 07:42:14.568  3365  3413 I jxcore-log: # teardown
08-11 07:42:14.568  3365  3413 I jxcore-log: 
,08-11 07:42:14.714  3365  3413 I jxcore-log: # setup
08-11 07:42:14.714  3365  3413 I jxcore-log: 
,08-11 07:42:14.763  3365  3413 I jxcore-log: # 127. Do something and make sure we time out
08-11 07:42:14.763  3365  3413 I jxcore-log: 
,08-11 07:42:15.845  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Replication resumed
08-11 07:42:15.845  3365  3413 I jxcore-log: 
,08-11 07:42:16.346  3365  3413 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-11 07:42:16.346  3365  3413 I jxcore-log: 
,08-11 07:42:16.475  3365  3413 I jxcore-log: ok 403 should be equal
08-11 07:42:16.475  3365  3413 I jxcore-log: 
,08-11 07:42:18.056  3365  3413 I jxcore-log: ok 404 action should be killed
08-11 07:42:18.056  3365  3413 I jxcore-log: 
,08-11 07:42:18.058  3365  3413 I jxcore-log: ok 405 Error should be timed out
08-11 07:42:18.058  3365  3413 I jxcore-log: 
,08-11 07:42:18.073  3365  3413 I jxcore-log: # teardown
08-11 07:42:18.073  3365  3413 I jxcore-log: 
,08-11 07:42:18.208  3365  3413 I jxcore-log: # setup
08-11 07:42:18.208  3365  3413 I jxcore-log: 
,08-11 07:42:18.336  3365  3413 I jxcore-log: # 128. Start replicating and then catch error when server goes
08-11 07:42:18.336  3365  3413 I jxcore-log: 
,08-11 07:42:18.949  3365  3413 I jxcore-log: ok 406 socket hung up
08-11 07:42:18.949  3365  3413 I jxcore-log: 
,08-11 07:42:18.982  3365  3413 I jxcore-log: # teardown
08-11 07:42:18.982  3365  3413 I jxcore-log: 
,08-11 07:42:19.127  3365  3413 I jxcore-log: # setup
08-11 07:42:19.127  3365  3413 I jxcore-log: 
,08-11 07:42:19.174  3365  3413 I jxcore-log: # 129. compareBufferArrays
08-11 07:42:19.174  3365  3413 I jxcore-log: 
,08-11 07:42:19.240  3365  3413 I jxcore-log: ok 407 should throw
08-11 07:42:19.240  3365  3413 I jxcore-log: 
,08-11 07:42:19.241  3365  3413 I jxcore-log: ok 408 should throw
08-11 07:42:19.241  3365  3413 I jxcore-log: 
08-11 07:42:19.242  3365  3413 I jxcore-log: ok 409 (unnamed assert)
08-11 07:42:19.242  3365  3413 I jxcore-log: 
08-11 07:42:19.242  3365  3413 I jxcore-log: ok 410 (unnamed assert)
08-11 07:42:19.242  3365  3413 I jxcore-log: 
08-11 07:42:19.242  3365  3413 I jxcore-log: ok 411 (unnamed assert)
08-11 07:42:19.242  3365  3413 I jxcore-log: 
08-11 07:42:19.243  3365  3413 I jxcore-log: ok 412 (unnamed assert)
08-11 07:42:19.243  3365  3413 I jxcore-log: 
,08-11 07:42:19.243  3365  3413 I jxcore-log: ok 413 (unnamed assert)
08-11 07:42:19.243  3365  3413 I jxcore-log: 
08-11 07:42:19.245  3365  3413 I jxcore-log: # teardown
08-11 07:42:19.245  3365  3413 I jxcore-log: 
,08-11 07:42:19.281  3365  3413 I jxcore-log: # setup
08-11 07:42:19.281  3365  3413 I jxcore-log: 
,08-11 07:42:19.323  3365  3413 I jxcore-log: # 130. Call start twice and get error
08-11 07:42:19.323  3365  3413 I jxcore-log: 
,08-11 07:42:19.383  3365  3413 I jxcore-log: ok 414 should throw
08-11 07:42:19.383  3365  3413 I jxcore-log: 
,08-11 07:42:19.387  3365  3413 I jxcore-log: # teardown
08-11 07:42:19.387  3365  3413 I jxcore-log: 
,08-11 07:42:19.435  3365  3413 I jxcore-log: # setup
08-11 07:42:19.435  3365  3413 I jxcore-log: 
,08-11 07:42:19.482  3365  3413 I jxcore-log: # 131. Start and make sure it runs
08-11 07:42:19.482  3365  3413 I jxcore-log: 
,08-11 07:42:19.545  3365  3413 I jxcore-log: # teardown
08-11 07:42:19.545  3365  3413 I jxcore-log: 
,08-11 07:42:19.591  3365  3413 I jxcore-log: # setup
08-11 07:42:19.591  3365  3413 I jxcore-log: 
,08-11 07:42:19.640  3365  3413 I jxcore-log: # 132. Make sure getTimeWhenRun is right after start
08-11 07:42:19.640  3365  3413 I jxcore-log: 
,08-11 07:42:19.692  3365  3413 I jxcore-log: ok 415 (unnamed assert)
08-11 07:42:19.692  3365  3413 I jxcore-log: 
,08-11 07:42:19.696  3365  3413 I jxcore-log: # teardown
08-11 07:42:19.696  3365  3413 I jxcore-log: 
,08-11 07:42:19.745  3365  3413 I jxcore-log: # setup
08-11 07:42:19.745  3365  3413 I jxcore-log: 
,08-11 07:42:19.829  3365  3413 I jxcore-log: # 133. Make sure getTimeWhenRun is -1 after function is called
08-11 07:42:19.829  3365  3413 I jxcore-log: 
,08-11 07:42:19.892  3365  3413 I jxcore-log: ok 416 should be equal
08-11 07:42:19.892  3365  3413 I jxcore-log: 
,08-11 07:42:19.899  3365  3413 I jxcore-log: # teardown
08-11 07:42:19.899  3365  3413 I jxcore-log: 
,08-11 07:42:19.952  3365  3413 I jxcore-log: # setup
08-11 07:42:19.952  3365  3413 I jxcore-log: 
,08-11 07:42:20.019  3365  3413 I jxcore-log: # 134. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
08-11 07:42:20.019  3365  3413 I jxcore-log: 
,08-11 07:42:20.068  3365  3413 I jxcore-log: ok 417 should be equal
08-11 07:42:20.068  3365  3413 I jxcore-log: 
,08-11 07:42:20.069  3365  3413 I jxcore-log: ok 418 should be equal
08-11 07:42:20.069  3365  3413 I jxcore-log: 
,08-11 07:42:20.071  3365  3413 I jxcore-log: ok 419 should throw
08-11 07:42:20.071  3365  3413 I jxcore-log: 
08-11 07:42:20.073  3365  3413 I jxcore-log: # teardown
08-11 07:42:20.073  3365  3413 I jxcore-log: 
,08-11 07:42:20.146  3365  3413 I jxcore-log: # setup
08-11 07:42:20.146  3365  3413 I jxcore-log: 
,08-11 07:42:20.198  3365  3413 I jxcore-log: # 135. Test TransientState
08-11 07:42:20.198  3365  3413 I jxcore-log: 
,08-11 07:42:20.261  3365  3413 I jxcore-log: ok 420 should throw
08-11 07:42:20.261  3365  3413 I jxcore-log: 
,08-11 07:42:20.263  3365  3413 I jxcore-log: ok 421 should throw
08-11 07:42:20.263  3365  3413 I jxcore-log: 
08-11 07:42:20.264  3365  3413 I jxcore-log: ok 422 should be equal
08-11 07:42:20.264  3365  3413 I jxcore-log: 
08-11 07:42:20.264  3365  3413 I jxcore-log: ok 423 should be equal
08-11 07:42:20.264  3365  3413 I jxcore-log: 
,08-11 07:42:20.265  3365  3413 I jxcore-log: ok 424 should be equal
08-11 07:42:20.265  3365  3413 I jxcore-log: 
08-11 07:42:20.265  3365  3413 I jxcore-log: ok 425 should be equal
08-11 07:42:20.265  3365  3413 I jxcore-log: 
08-11 07:42:20.266  3365  3413 I jxcore-log: ok 426 (unnamed assert)
08-11 07:42:20.266  3365  3413 I jxcore-log: 
08-11 07:42:20.266  3365  3413 I jxcore-log: ok 427 (unnamed assert)
08-11 07:42:20.266  3365  3413 I jxcore-log: 
,08-11 07:42:20.269  3365  3413 I jxcore-log: # teardown
08-11 07:42:20.269  3365  3413 I jxcore-log: 
,08-11 07:42:20.346  3365  3413 I jxcore-log: # setup
08-11 07:42:20.346  3365  3413 I jxcore-log: ,
,08-11 07:42:20.405  3365  3413 I jxcore-log: # 136. No peers and empty database
08-11 07:42:20.405  3365  3413 I jxcore-log: 
,08-11 07:42:20.585  3365  3413 I jxcore-log: ok 428 verify failed
08-11 07:42:20.585  3365  3413 I jxcore-log: 
,08-11 07:42:20.586  3365  3413 I jxcore-log: ok 429 constructor called once
08-11 07:42:20.586  3365  3413 I jxcore-log: 
,08-11 07:42:20.590  3365  3413 I jxcore-log: ok 430 constructor called with right args
08-11 07:42:20.590  3365  3413 I jxcore-log: 
,08-11 07:42:20.592  3365  3413 I jxcore-log: ok 431 match start arg
08-11 07:42:20.592  3365  3413 I jxcore-log: 
,08-11 07:42:20.592  3365  3413 I jxcore-log: ok 432 start called once
08-11 07:42:20.592  3365  3413 I jxcore-log: 
,08-11 07:42:20.593  3365  3413 I jxcore-log: ok 433 stop called once
08-11 07:42:20.593  3365  3413 I jxcore-log: 
08-11 07:42:20.593  3365  3413 I jxcore-log: ok 434 stop after start
08-11 07:42:20.593  3365  3413 I jxcore-log: 
,08-11 07:42:20.599  3365  3413 I jxcore-log: # teardown
08-11 07:42:20.599  3365  3413 I jxcore-log: 
,08-11 07:42:20.689  3365  3413 I jxcore-log: # setup
08-11 07:42:20.689  3365  3413 I jxcore-log: 
,08-11 07:42:20.752  3365  3413 I jxcore-log: # 137. One peer and empty DB
08-11 07:42:20.752  3365  3413 I jxcore-log: 
,08-11 07:42:20.926  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"},
08-11 07:42:20.926  3365  3413 I jxcore-log: 
08-11 07:42:20.928  3365  3413 I jxcore-log: ok 435 verify failed
08-11 07:42:20.928  3365  3413 I jxcore-log: 
08-11 07:42:20.928  3365  3413 I jxcore-log: ok 436 constructor called once
08-11 07:42:20.928  3365  3413 I jxcore-log: 
,08-11 07:42:20.929  3365  3413 I jxcore-log: ok 437 constructor called with right args
08-11 07:42:20.929  3365  3413 I jxcore-log: 
08-11 07:42:20.929  3365  3413 I jxcore-log: ok 438 match start arg
08-11 07:42:20.929  3365  3413 I jxcore-log: 
08-11 07:42:20.929  3365  3413 I jxcore-log: ok 439 start called once,
08-11 07:42:20.929  3365  3413 I jxcore-log: 
08-11 07:42:20.930  3365  3413 I jxcore-log: ok 440 stop called once
08-11 07:42:20.930  3365  3413 I jxcore-log: 
08-11 07:42:20.930  3365  3413 I jxcore-log: ok 441 stop after start
08-11 07:42:20.930  3365  3413 I jxcore-log: 
,08-11 07:42:20.938  3365  3413 I jxcore-log: # teardown
08-11 07:42:20.938  3365  3413 I jxcore-log: 
,08-11 07:42:21.059  3365  3413 I jxcore-log: # setup
08-11 07:42:21.059  3365  3413 I jxcore-log: 
,08-11 07:42:21.121  3365  3413 I jxcore-log: # 138. One peer with _Local set behind current seq
08-11 07:42:21.121  3365  3413 I jxcore-log: 
,08-11 07:42:21.450  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:21.450  3365  3413 I jxcore-log: 
,08-11 07:42:21.453  3365  3413 I jxcore-log: ok 442 verify failed
08-11 07:42:21.453  3365  3413 I jxcore-log: 
,08-11 07:42:21.453  3365  3413 I jxcore-log: ok 443 constructor called once
08-11 07:42:21.453  3365  3413 I jxcore-log: 
,08-11 07:42:21.454  3365  3413 I jxcore-log: ok 444 constructor called with right args
08-11 07:42:21.454  3365  3413 I jxcore-log: 
,08-11 07:42:21.455  3365  3413 I jxcore-log: ok 445 match start arg
08-11 07:42:21.455  3365  3413 I jxcore-log: 
,08-11 07:42:21.455  3365  3413 I jxcore-log: ok 446 start called once
08-11 07:42:21.455  3365  3413 I jxcore-log: 
,08-11 07:42:21.456  3365  3413 I jxcore-log: ok 447 stop called once
08-11 07:42:21.456  3365  3413 I jxcore-log: 
08-11 07:42:21.456  3365  3413 I jxcore-log: ok 448 stop after start
08-11 07:42:21.456  3365  3413 I jxcore-log: 
,08-11 07:42:21.459  3365  3413 I jxcore-log: # teardown
08-11 07:42:21.459  3365  3413 I jxcore-log: 
,08-11 07:42:21.523  3365  3413 I jxcore-log: # setup
08-11 07:42:21.523  3365  3413 I jxcore-log: 
,08-11 07:42:21.588  3365  3413 I jxcore-log: # 139. One peer with _Local set equal to current seq
08-11 07:42:21.588  3365  3413 I jxcore-log: 
,08-11 07:42:21.832  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:21.832  3365  3413 I jxcore-log: 
,08-11 07:42:21.834  3365  3413 I jxcore-log: ok 449 verify failed
08-11 07:42:21.834  3365  3413 I jxcore-log: 
08-11 07:42:21.834  3365  3413 I jxcore-log: ok 450 constructor called once
08-11 07:42:21.834  3365  3413 I jxcore-log: 
,08-11 07:42:21.835  3365  3413 I jxcore-log: ok 451 constructor called with right args
08-11 07:42:21.835  3365  3413 I jxcore-log: 
08-11 07:42:21.835  3365  3413 I jxcore-log: ok 452 match start arg
08-11 07:42:21.835  3365  3413 I jxcore-log: 
08-11 07:42:21.836  3365  3413 I jxcore-log: ok 453 start called once
08-11 07:42:21.836  3365  3413 I jxcore-log: 
,08-11 07:42:21.836  3365  3413 I jxcore-log: ok 454 stop called once
08-11 07:42:21.836  3365  3413 I jxcore-log: 
08-11 07:42:21.836  3365  3413 I jxcore-log: ok 455 stop after start
08-11 07:42:21.836  3365  3413 I jxcore-log: 
,08-11 07:42:21.839  3365  3413 I jxcore-log: # teardown
08-11 07:42:21.839  3365  3413 I jxcore-log: 
,08-11 07:42:21.924  3365  3413 I jxcore-log: # setup
08-11 07:42:21.924  3365  3413 I jxcore-log: 
,08-11 07:42:21.961  3365  3413 I jxcore-log: # 140. One peer with _Local set ahead of current seq (and no this should not happen)
08-11 07:42:21.961  3365  3413 I jxcore-log: 
,08-11 07:42:22.234  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:22.234  3365  3413 I jxcore-log: 
,08-11 07:42:22.236  3365  3413 I jxcore-log: ok 456 verify failed
08-11 07:42:22.236  3365  3413 I jxcore-log: 
08-11 07:42:22.236  3365  3413 I jxcore-log: ok 457 constructor called once
08-11 07:42:22.236  3365  3413 I jxcore-log: 
,08-11 07:42:22.237  3365  3413 I jxcore-log: ok 458 constructor called with right args
08-11 07:42:22.237  3365  3413 I jxcore-log: 
,08-11 07:42:22.239  3365  3413 I jxcore-log: ok 459 match start arg
08-11 07:42:22.239  3365  3413 I jxcore-log: 
08-11 07:42:22.240  3365  3413 I jxcore-log: ok 460 start called once
08-11 07:42:22.240  3365  3413 I jxcore-log: 
08-11 07:42:22.240  3365  3413 I jxcore-log: ok 461 stop called once
08-11 07:42:22.240  3365  3413 I jxcore-log: 
08-11 07:42:22.240  3365  3413 I jxcore-log: ok 462 stop after start
08-11 07:42:22.240  3365  3413 I jxcore-log: 
,08-11 07:42:22.244  3365  3413 I jxcore-log: # teardown
08-11 07:42:22.244  3365  3413 I jxcore-log: 
,08-11 07:42:22.286  3365  3413 I jxcore-log: # setup
08-11 07:42:22.286  3365  3413 I jxcore-log: 
,08-11 07:42:22.321  3365  3413 I jxcore-log: # 141. Three peers, one not in DB, one behind and one ahead
08-11 07:42:22.321  3365  3413 I jxcore-log: 
,08-11 07:42:22.643  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:22.643  3365  3413 I jxcore-log: 
,08-11 07:42:22.646  3365  3413 I jxcore-log: ok 463 verify failed
08-11 07:42:22.646  3365  3413 I jxcore-log: 
08-11 07:42:22.647  3365  3413 I jxcore-log: ok 464 constructor called once
08-11 07:42:22.647  3365  3413 I jxcore-log: 
,08-11 07:42:22.648  3365  3413 I jxcore-log: ok 465 constructor called with right args
08-11 07:42:22.648  3365  3413 I jxcore-log: 
08-11 07:42:22.649  3365  3413 I jxcore-log: ok 466 match start arg
08-11 07:42:22.649  3365  3413 I jxcore-log: 
,08-11 07:42:22.649  3365  3413 I jxcore-log: ok 467 start called once
08-11 07:42:22.649  3365  3413 I jxcore-log: 
,08-11 07:42:22.650  3365  3413 I jxcore-log: ok 468 stop called once
08-11 07:42:22.650  3365  3413 I jxcore-log: 
08-11 07:42:22.650  3365  3413 I jxcore-log: ok 469 stop after start
08-11 07:42:22.650  3365  3413 I jxcore-log: 
08-11 07:42:22.653  3365  3413 I jxcore-log: # teardown
08-11 07:42:22.653  3365  3413 I jxcore-log: 
,08-11 07:42:22.748  3365  3413 I jxcore-log: # setup
08-11 07:42:22.748  3365  3413 I jxcore-log: 
,08-11 07:42:22.784  3365  3413 I jxcore-log: # 142. More than maximum peers, make sure we only send maximum allowed
08-11 07:42:22.784  3365  3413 I jxcore-log: 
,08-11 07:42:23.444  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:23.444  3365  3413 I jxcore-log: 
,08-11 07:42:23.446  3365  3413 I jxcore-log: ok 470 verify failed
08-11 07:42:23.446  3365  3413 I jxcore-log: 
08-11 07:42:23.447  3365  3413 I jxcore-log: ok 471 constructor called once
08-11 07:42:23.447  3365  3413 I jxcore-log: 
,08-11 07:42:23.448  3365  3413 I jxcore-log: ok 472 constructor called with right args
08-11 07:42:23.448  3365  3413 I jxcore-log: 
08-11 07:42:23.448  3365  3413 I jxcore-log: ok 473 match start arg
08-11 07:42:23.448  3365  3413 I jxcore-log: 
08-11 07:42:23.449  3365  3413 I jxcore-log: ok 474 start called once
08-11 07:42:23.449  3365  3413 I jxcore-log: 
08-11 07:42:23.449  3365  3413 I jxcore-log: ok 475 stop called once
08-11 07:42:23.449  3365  3413 I jxcore-log: 
,08-11 07:42:23.449  3365  3413 I jxcore-log: ok 476 stop after start
08-11 07:42:23.449  3365  3413 I jxcore-log: 
,08-11 07:42:23.456  3365  3413 I jxcore-log: # teardown
08-11 07:42:23.456  3365  3413 I jxcore-log: 
,08-11 07:42:23.666  3365  3413 I jxcore-log: # setup
08-11 07:42:23.666  3365  3413 I jxcore-log: 
,08-11 07:42:23.711  3365  3413 I jxcore-log: # 143. two peers with empty DB, update the doc
08-11 07:42:23.711  3365  3413 I jxcore-log: 
,08-11 07:42:23.952  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:23.952  3365  3413 I jxcore-log: 
,08-11 07:42:23.987  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:23.987  3365  3413 I jxcore-log: 
,08-11 07:42:23.989  3365  3413 I jxcore-log: ok 477 verify failed
08-11 07:42:23.989  3365  3413 I jxcore-log: 
,08-11 07:42:23.989  3365  3413 I jxcore-log: ok 478 constructor called once
08-11 07:42:23.989  3365  3413 I jxcore-log: 
08-11 07:42:23.990  3365  3413 I jxcore-log: ok 479 constructor called with right args
08-11 07:42:23.990  3365  3413 I jxcore-log: 
08-11 07:42:23.990  3365  3413 I jxcore-log: ok 480 last start before stop
08-11 07:42:23.990  3365  3413 I jxcore-log: 
,08-11 07:42:23.991  3365  3413 I jxcore-log: ok 481 empty first start
08-11 07:42:23.991  3365  3413 I jxcore-log: 
08-11 07:42:23.992  3365  3413 I jxcore-log: ok 482 full second start
08-11 07:42:23.992  3365  3413 I jxcore-log: 
08-11 07:42:23.992  3365  3413 I jxcore-log: ok 483 only 2 timers
08-11 07:42:23.992  3365  3413 I jxcore-log: 
,08-11 07:42:23.995  3365  3413 I jxcore-log: # teardown
08-11 07:42:23.995  3365  3413 I jxcore-log: 
,08-11 07:42:24.020  3365  3413 I jxcore-log: # setup
08-11 07:42:24.020  3365  3413 I jxcore-log: 
,08-11 07:42:24.054  3365  3413 I jxcore-log: # 144. add doc and make sure tokens refresh when they expire
08-11 07:42:24.054  3365  3413 I jxcore-log: 
,08-11 07:42:24.386  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:24.386  3365  3413 I jxcore-log: 
,08-11 07:42:24.519  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:24.519  3365  3413 I jxcore-log: 
,08-11 07:42:24.584  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:24.584  3365  3413 I jxcore-log: 
,08-11 07:42:24.587  3365  3413 I jxcore-log: ok 484 verify failed
08-11 07:42:24.587  3365  3413 I jxcore-log: 
,08-11 07:42:24.588  3365  3413 I jxcore-log: ok 485 constructor called once
08-11 07:42:24.588  3365  3413 I jxcore-log: 
,08-11 07:42:24.589  3365  3413 I jxcore-log: ok 486 constructor called with right args
08-11 07:42:24.589  3365  3413 I jxcore-log: 
,08-11 07:42:24.590  3365  3413 I jxcore-log: ok 487 start before stop
08-11 07:42:24.590  3365  3413 I jxcore-log: 
08-11 07:42:24.590  3365  3413 I jxcore-log: ok 488 We got at least 3 calls to start
08-11 07:42:24.590  3365  3413 I jxcore-log: 
,08-11 07:42:24.590  3365  3413 I jxcore-log: ok 489 at least 3
08-11 07:42:24.590  3365  3413 I jxcore-log: 
,08-11 07:42:24.591  3365  3413 I jxcore-log: ok 490 default 1
08-11 07:42:24.591  3365  3413 I jxcore-log: 
,08-11 07:42:24.592  3365  3413 I jxcore-log: ok 491 1 run
08-11 07:42:24.592  3365  3413 I jxcore-log: 
,08-11 07:42:24.592  3365  3413 I jxcore-log: ok 492 default 2
08-11 07:42:24.592  3365  3413 I jxcore-log: 
,08-11 07:42:24.593  3365  3413 I jxcore-log: ok 493 2 run
08-11 07:42:24.593  3365  3413 I jxcore-log: 
,08-11 07:42:24.594  3365  3413 I jxcore-log: ok 494 default 3
08-11 07:42:24.594  3365  3413 I jxcore-log: 
08-11 07:42:24.598  3365  3413 I jxcore-log: # teardown
08-11 07:42:24.598  3365  3413 I jxcore-log: 
,08-11 07:42:24.703  3365  3413 I jxcore-log: # setup
08-11 07:42:24.703  3365  3413 I jxcore-log: 
,08-11 07:42:24.747  3365  3413 I jxcore-log: # 145. start and stop and start and stop
08-11 07:42:24.747  3365  3413 I jxcore-log: 
,08-11 07:42:25.013  3365  3413 I jxcore-log: ok 495 start out null
08-11 07:42:25.013  3365  3413 I jxcore-log: 
,08-11 07:42:25.037  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:25.037  3365  3413 I jxcore-log: 
,08-11 07:42:25.038  3365  3413 I jxcore-log: ok 496 back to null
08-11 07:42:25.038  3365  3413 I jxcore-log: 
,08-11 07:42:25.060  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:25.060  3365  3413 I jxcore-log: 
,08-11 07:42:25.061  3365  3413 I jxcore-log: ok 497 still null
08-11 07:42:25.061  3365  3413 I jxcore-log: 
,08-11 07:42:25.063  3365  3413 I jxcore-log: ok 498 verify failed
08-11 07:42:25.063  3365  3413 I jxcore-log: 
,08-11 07:42:25.064  3365  3413 I jxcore-log: ok 499 constructor called once
08-11 07:42:25.064  3365  3413 I jxcore-log: 
08-11 07:42:25.064  3365  3413 I jxcore-log: ok 500 constructor called with right args
08-11 07:42:25.064  3365  3413 I jxcore-log: 
,08-11 07:42:25.065  3365  3413 I jxcore-log: ok 501 first start before first stop
08-11 07:42:25.065  3365  3413 I jxcore-log: 
,08-11 07:42:25.065  3365  3413 I jxcore-log: ok 502 first stop before second start
08-11 07:42:25.065  3365  3413 I jxcore-log: 
08-11 07:42:25.066  3365  3413 I jxcore-log: ok 503 second start before second stop
08-11 07:42:25.066  3365  3413 I jxcore-log: 
,08-11 07:42:25.074  3365  3413 I jxcore-log: # teardown
08-11 07:42:25.074  3365  3413 I jxcore-log: 
,08-11 07:42:25.192  3365  3413 I jxcore-log: # setup
08-11 07:42:25.192  3365  3413 I jxcore-log: 
,08-11 07:42:25.227  3365  3413 I jxcore-log: # 146. two identical starts in a row
08-11 07:42:25.227  3365  3413 I jxcore-log: 
,08-11 07:42:25.461  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:25.461  3365  3413 I jxcore-log: 
,08-11 07:42:25.463  3365  3413 I jxcore-log: ok 504 verify failed
08-11 07:42:25.463  3365  3413 I jxcore-log: 
,08-11 07:42:25.464  3365  3413 I jxcore-log: ok 505 constructor called once
08-11 07:42:25.464  3365  3413 I jxcore-log: 
08-11 07:42:25.464  3365  3413 I jxcore-log: ok 506 constructor called with right args
08-11 07:42:25.464  3365  3413 I jxcore-log: 
08-11 07:42:25.465  3365  3413 I jxcore-log: ok 507 (unnamed assert)
08-11 07:42:25.465  3365  3413 I jxcore-log: 
,08-11 07:42:25.470  3365  3413 I jxcore-log: # teardown
08-11 07:42:25.470  3365  3413 I jxcore-log: 
,08-11 07:42:25.535  3365  3413 I jxcore-log: # setup
08-11 07:42:25.535  3365  3413 I jxcore-log: 
,08-11 07:42:25.573  3365  3413 I jxcore-log: # 147. two different starts in a row
08-11 07:42:25.573  3365  3413 I jxcore-log: 
,08-11 07:42:25.863  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:25.863  3365  3413 I jxcore-log: 
,08-11 07:42:25.870  3365  3413 I jxcore-log: ok 508 verify failed
08-11 07:42:25.870  3365  3413 I jxcore-log: 
,08-11 07:42:25.870  3365  3413 I jxcore-log: ok 509 constructor called once
08-11 07:42:25.870  3365  3413 I jxcore-log: 
08-11 07:42:25.871  3365  3413 I jxcore-log: ok 510 constructor called with right args
08-11 07:42:25.871  3365  3413 I jxcore-log: 
,08-11 07:42:25.871  3365  3413 I jxcore-log: ok 511 (unnamed assert)
08-11 07:42:25.871  3365  3413 I jxcore-log: 
08-11 07:42:25.872  3365  3413 I jxcore-log: ok 512 (unnamed assert)
08-11 07:42:25.872  3365  3413 I jxcore-log: 
,08-11 07:42:25.877  3365  3413 I jxcore-log: # teardown
08-11 07:42:25.877  3365  3413 I jxcore-log: 
,08-11 07:42:25.917  3365  3413 I jxcore-log: # setup
08-11 07:42:25.917  3365  3413 I jxcore-log: 
,08-11 07:42:25.953  3365  3413 I jxcore-log: # 148. two stops and a start and two stops
08-11 07:42:25.953  3365  3413 I jxcore-log: 
,08-11 07:42:26.217  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:26.217  3365  3413 I jxcore-log: 
,08-11 07:42:26.220  3365  3413 I jxcore-log: ok 513 verify failed
08-11 07:42:26.220  3365  3413 I jxcore-log: 
,08-11 07:42:26.220  3365  3413 I jxcore-log: ok 514 constructor called once
08-11 07:42:26.220  3365  3413 I jxcore-log: 
,08-11 07:42:26.221  3365  3413 I jxcore-log: ok 515 constructor called with right args
08-11 07:42:26.221  3365  3413 I jxcore-log: 
,08-11 07:42:26.222  3365  3413 I jxcore-log: ok 516 start before stop
08-11 07:42:26.222  3365  3413 I jxcore-log: 
,08-11 07:42:26.229  3365  3413 I jxcore-log: # teardown
08-11 07:42:26.229  3365  3413 I jxcore-log: 
,08-11 07:42:26.270  3365  3413 I jxcore-log: # setup
08-11 07:42:26.270  3365  3413 I jxcore-log: 
,08-11 07:42:26.303  3365  3413 I jxcore-log: # 149. we properly enqueue requests so no then needed
08-11 07:42:26.303  3365  3413 I jxcore-log: 
,08-11 07:42:26.469  3365  3413 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-11 07:42:26.469  3365  3413 I jxcore-log: 
,08-11 07:42:26.470  3365  3413 I jxcore-log: ok 517 verify failed
08-11 07:42:26.470  3365  3413 I jxcore-log: 
08-11 07:42:26.471  3365  3413 I jxcore-log: ok 518 constructor called once
08-11 07:42:26.471  3365  3413 I jxcore-log: 
,08-11 07:42:26.471  3365  3413 I jxcore-log: ok 519 constructor called with right args
08-11 07:42:26.471  3365  3413 I jxcore-log: 
08-11 07:42:26.472  3365  3413 I jxcore-log: ok 520 start before stop
08-11 07:42:26.472  3365  3413 I jxcore-log: 
,08-11 07:42:26.478  3365  3413 I jxcore-log: # teardown
08-11 07:42:26.478  3365  3413 I jxcore-log: 
,08-11 07:42:26.632  3365  3413 I jxcore-log: # setup
08-11 07:42:26.632  3365  3413 I jxcore-log: 
,08-11 07:42:26.698  3365  3413 I jxcore-log: # 150. test calculateSeqPointKeyId
08-11 07:42:26.698  3365  3413 I jxcore-log: 
,08-11 07:42:26.773  3365  3413 I jxcore-log: ok 521 should be equal
08-11 07:42:26.773  3365  3413 I jxcore-log: 
,08-11 07:42:26.774  3365  3413 I jxcore-log: ok 522 should be equal
08-11 07:42:26.774  3365  3413 I jxcore-log: 
,08-11 07:42:26.776  3365  3413 I jxcore-log: # teardown
08-11 07:42:26.776  3365  3413 I jxcore-log: 
,08-11 07:42:26.874  3365  3413 I jxcore-log: # setup
08-11 07:42:26.874  3365  3413 I jxcore-log: 
,08-11 07:42:26.919  3365  3413 I jxcore-log: # 151. can create servers manager
08-11 07:42:26.919  3365  3413 I jxcore-log: 
,08-11 07:42:26.972  3365  3413 I jxcore-log: ok 523 serversManager must not be null
08-11 07:42:26.972  3365  3413 I jxcore-log: 
,08-11 07:42:26.973  3365  3413 I jxcore-log: ok 524 serversManager must be an object
08-11 07:42:26.973  3365  3413 I jxcore-log: 
,08-11 07:42:26.976  3365  3413 I jxcore-log: # teardown
08-11 07:42:26.976  3365  3413 I jxcore-log: 
,08-11 07:42:27.023  3365  3413 I jxcore-log: # setup
08-11 07:42:27.023  3365  3413 I jxcore-log: 
,08-11 07:42:27.071  3365  3413 I jxcore-log: # 152. calling stop without start causes error
08-11 07:42:27.071  3365  3413 I jxcore-log: 
,08-11 07:42:27.124  3365  3413 I jxcore-log: ok 525 We need to call start first
08-11 07:42:27.124  3365  3413 I jxcore-log: 
,08-11 07:42:27.129  3365  3413 I jxcore-log: # teardown
08-11 07:42:27.129  3365  3413 I jxcore-log: 
,08-11 07:42:27.191  3365  3413 I jxcore-log: # setup
08-11 07:42:27.191  3365  3413 I jxcore-log: 
,08-11 07:42:27.240  3365  3413 I jxcore-log: # 153. can start/stop servers manager
08-11 07:42:27.240  3365  3413 I jxcore-log: 
,08-11 07:42:27.294  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:42:27.294  3365  3413 I jxcore-log: 
,08-11 07:42:27.299  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 40094
08-11 07:42:27.299  3365  3413 I jxcore-log: 
,08-11 07:42:27.301  3365  3413 I jxcore-log: ok 526 port must be in range
08-11 07:42:27.301  3365  3413 I jxcore-log: 
,08-11 07:42:27.305  3365  3413 I jxcore-log: # teardown
08-11 07:42:27.305  3365  3413 I jxcore-log: 
,08-11 07:42:27.353  3365  3413 I jxcore-log: # setup
08-11 07:42:27.353  3365  3413 I jxcore-log: 
,08-11 07:42:27.403  3365  3413 I jxcore-log: # 154. starting twice resolves with listening port
08-11 07:42:27.403  3365  3413 I jxcore-log: 
,08-11 07:42:27.451  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:42:27.451  3365  3413 I jxcore-log: 
,08-11 07:42:27.456  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 49891
08-11 07:42:27.456  3365  3413 I jxcore-log: 
,08-11 07:42:27.459  3365  3413 I jxcore-log: ok 527 second start should return same port
08-11 07:42:27.459  3365  3413 I jxcore-log: 
,08-11 07:42:27.462  3365  3413 I jxcore-log: # teardown
08-11 07:42:27.462  3365  3413 I jxcore-log: 
,08-11 07:42:27.525  3365  3413 I jxcore-log: # setup
08-11 07:42:27.525  3365  3413 I jxcore-log: 
,08-11 07:42:27.619  3365  3413 I jxcore-log: # 155. terminateIncomingConnection will terminate a connection
08-11 07:42:27.619  3365  3413 I jxcore-log: 
,08-11 07:42:27.676  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:42:27.676  3365  3413 I jxcore-log: 
,08-11 07:42:27.678  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 46141
08-11 07:42:27.678  3365  3413 I jxcore-log: 
,08-11 07:42:27.685  3365  3413 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-11 07:42:27.685  3365  3413 I jxcore-log: 
,08-11 07:42:27.686  3365  3413 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-11 07:42:27.686  3365  3413 I jxcore-log: 
,08-11 07:42:27.688  3365  3413 I jxcore-log: DEBUG createNativeListener: new mux
08-11 07:42:27.688  3365  3413 I jxcore-log: 
,08-11 07:42:27.691  3365  3413 I jxcore-log: ok 528 we should be connected
08-11 07:42:27.691  3365  3413 I jxcore-log: 
,08-11 07:42:27.695  3365  3413 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-11 07:42:27.695  3365  3413 I jxcore-log: 
,08-11 07:42:27.695  3365  3413 I jxcore-log: ok 529 now we are disconnected
08-11 07:42:27.695  3365  3413 I jxcore-log: 
,08-11 07:42:27.708  3365  3413 I jxcore-log: # teardown
08-11 07:42:27.708  3365  3413 I jxcore-log: 
,08-11 07:42:27.769  3365  3413 I jxcore-log: # setup
08-11 07:42:27.769  3365  3413 I jxcore-log: 
,08-11 07:42:27.814  3365  3413 I jxcore-log: # 156. terminate an Outgoing connection will terminate the server
08-11 07:42:27.814  3365  3413 I jxcore-log: 
,08-11 07:42:27.864  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:42:27.864  3365  3413 I jxcore-log: 
,08-11 07:42:27.869  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 45835
08-11 07:42:27.869  3365  3413 I jxcore-log: 
,08-11 07:42:27.873  3365  3413 I jxcore-log: # teardown
08-11 07:42:27.873  3365  3413 I jxcore-log: 
,08-11 07:42:27.926  3365  3413 I jxcore-log: # setup
08-11 07:42:27.926  3365  3413 I jxcore-log: 
,08-11 07:42:27.984  3365  3413 I jxcore-log: # 157. terminate an Outgoing connection with wrong arguments is not harmful
08-11 07:42:27.984  3365  3413 I jxcore-log: 
,08-11 07:42:28.027  3365  3413 I jxcore-log: DEBUG createNativeListener: creating native server
08-11 07:42:28.027  3365  3413 I jxcore-log: 
,08-11 07:42:28.030  3365  3413 I jxcore-log: DEBUG createNativeListener: listening 43670
08-11 07:42:28.030  3365  3413 I jxcore-log: 
,08-11 07:42:28.033  3365  3413 I jxcore-log: # teardown
08-11 07:42:28.033  3365  3413 I jxcore-log: 
,08-11 07:42:28.107  3365  3413 I jxcore-log: # setup
08-11 07:42:28.107  3365  3413 I jxcore-log: 
,08-11 07:42:28.149  3365  3413 I jxcore-log: ok 530 should be in started state
08-11 07:42:28.149  3365  3413 I jxcore-log: 
,08-11 07:42:28.151  3365  3413 I jxcore-log: # 158. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
08-11 07:42:28.151  3365  3413 I jxcore-log: 
,08-11 07:42:28.224  3365  3413 I jxcore-log: ok 531 peer identifier should match
08-11 07:42:28.224  3365  3413 I jxcore-log: 
,08-11 07:42:28.224  3365  3413 I jxcore-log: ok 532 host address should match
08-11 07:42:28.224  3365  3413 I jxcore-log: 
08-11 07:42:28.225  3365  3413 I jxcore-log: ok 533 port should match
08-11 07:42:28.225  3365  3413 I jxcore-log: 
,08-11 07:42:28.231  3365  3413 I jxcore-log: ok 534 host address should be null
08-11 07:42:28.231  3365  3413 I jxcore-log: 
,08-11 07:42:28.231  3365  3413 I jxcore-log: ok 535 port should should be null
08-11 07:42:28.231  3365  3413 I jxcore-log: 
,08-11 07:42:28.235  3365  3413 I jxcore-log: # teardown
08-11 07:42:28.235  3365  3413 I jxcore-log: 
,08-11 07:42:28.319  3365  3413 I jxcore-log: ok 536 should not be in started state
08-11 07:42:28.319  3365  3413 I jxcore-log: 
,08-11 07:42:28.324  3365  3413 I jxcore-log: # setup
08-11 07:42:28.324  3365  3413 I jxcore-log: 
,08-11 07:42:28.378  3365  3413 I jxcore-log: ok 537 should be in started state
08-11 07:42:28.378  3365  3413 I jxcore-log: 
,08-11 07:42:28.381  3365  3413 I jxcore-log: # 159. #startUpdateAdvertisingAndListening should use different USN after every invocation
08-11 07:42:28.381  3365  3413 I jxcore-log: 
,08-11 07:42:28.477  3365  3413 I jxcore-log: ok 538 USN should have changed from the first one
08-11 07:42:28.477  3365  3413 I jxcore-log: 
,08-11 07:42:28.485  3365  3413 I jxcore-log: ok 539 when receiving the second byebye, the first USN should be already set
08-11 07:42:28.485  3365  3413 I jxcore-log: 
,08-11 07:42:28.489  3365  3413 I jxcore-log: # teardown
08-11 07:42:28.489  3365  3413 I jxcore-log: 
,08-11 07:42:28.564  3365  3413 I jxcore-log: ok 540 should not be in started state
08-11 07:42:28.564  3365  3413 I jxcore-log: 
,08-11 07:42:28.570  3365  3413 I jxcore-log: # setup
08-11 07:42:28.570  3365  3413 I jxcore-log: 
,08-11 07:42:28.609  3365  3413 I jxcore-log: ok 541 should be in started state
08-11 07:42:28.609  3365  3413 I jxcore-log: 
,08-11 07:42:28.611  3365  3413 I jxcore-log: # 160. messages with invalid location or USN should be ignored
08-11 07:42:28.611  3365  3413 I jxcore-log: 
,08-11 07:42:28.657  3365  3413 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
08-11 07:42:28.657  3365  3413 I jxcore-log: 
,08-11 07:42:28.658  3365  3413 I jxcore-log: ok 542 should not have emitted with invalid port
08-11 07:42:28.658  3365  3413 I jxcore-log: 
,08-11 07:42:28.660  3365  3413 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
08-11 07:42:28.660  3365  3413 I jxcore-log: 
,08-11 07:42:28.661  3365  3413 I jxcore-log: ok 543 should not have emitted with invalid USN
08-11 07:42:28.661  3365  3413 I jxcore-log: 
,08-11 07:42:28.663  3365  3413 I jxcore-log: # teardown
08-11 07:42:28.663  3365  3413 I jxcore-log: 
,08-11 07:42:28.723  3365  3413 I jxcore-log: ok 544 should not be in started state
08-11 07:42:28.723  3365  3413 I jxcore-log: 
,08-11 07:42:28.727  3365  3413 I jxcore-log: # setup
08-11 07:42:28.727  3365  3413 I jxcore-log: 
,08-11 07:42:28.797  3365  3413 I jxcore-log: ok 545 should be in started state
08-11 07:42:28.797  3365  3413 I jxcore-log: 
,08-11 07:42:28.799  3365  3413 I jxcore-log: # 161. verify that Thali-specific messages are filtered correctly
08-11 07:42:28.799  3365  3413 I jxcore-log: 
,08-11 07:42:28.881  3365  3413 I jxcore-log: ok 546 irrelevant messages should be ignored
08-11 07:42:28.881  3365  3413 I jxcore-log: 
,08-11 07:42:28.885  3365  3413 I jxcore-log: ok 547 relevant messages should not be ignored
08-11 07:42:28.885  3365  3413 I jxcore-log: 
,08-11 07:42:28.886  3365  3413 I jxcore-log: ok 548 messages from this device should be ignored
08-11 07:42:28.886  3365  3413 I jxcore-log: 
,08-11 07:42:28.892  3365  3413 I jxcore-log: # teardown
08-11 07:42:28.892  3365  3413 I jxcore-log: 
,08-11 07:42:29.067  3365  3413 I jxcore-log: ok 549 should not be in started state
08-11 07:42:29.067  3365  3413 I jxcore-log: 
,08-11 07:42:29.073  3365  3413 I jxcore-log: # setup
08-11 07:42:29.073  3365  3413 I jxcore-log: 
,08-11 07:42:29.112  3365  3413 I jxcore-log: ok 550 should be in started state
08-11 07:42:29.112  3365  3413 I jxcore-log: 
,08-11 07:42:29.114  3365  3413 I jxcore-log: # 162. #startListeningForAdvertisements should fail if start not called
08-11 07:42:29.114  3365  3413 I jxcore-log: 
,08-11 07:42:29.162  3365  3413 I jxcore-log: ok 551 specific error should be returned
08-11 07:42:29.162  3365  3413 I jxcore-log: 
,08-11 07:42:29.165  3365  3413 I jxcore-log: # teardown
08-11 07:42:29.165  3365  3413 I jxcore-log: 
,08-11 07:42:29.209  3365  3413 I jxcore-log: ok 552 should not be in started state
08-11 07:42:29.209  3365  3413 I jxcore-log: 
,08-11 07:42:29.211  3365  3413 I jxcore-log: # setup
08-11 07:42:29.211  3365  3413 I jxcore-log: 
,08-11 07:42:29.258  3365  3413 I jxcore-log: ok 553 should be in started state
08-11 07:42:29.258  3365  3413 I jxcore-log: 
,08-11 07:42:29.261  3365  3413 I jxcore-log: # 163. #startUpdateAdvertisingAndListening should fail if start not called
08-11 07:42:29.261  3365  3413 I jxcore-log: 
,08-11 07:42:29.313  3365  3413 I jxcore-log: ok 554 specific error should be returned
08-11 07:42:29.313  3365  3413 I jxcore-log: 
,08-11 07:42:29.316  3365  3413 I jxcore-log: # teardown
08-11 07:42:29.316  3365  3413 I jxcore-log: 
,08-11 07:42:29.364  3365  3413 I jxcore-log: ok 555 should not be in started state
08-11 07:42:29.364  3365  3413 I jxcore-log: 
,08-11 07:42:29.367  3365  3413 I jxcore-log: # setup
08-11 07:42:29.367  3365  3413 I jxcore-log: 
,08-11 07:42:29.430  3365  3413 I jxcore-log: ok 556 should be in started state
08-11 07:42:29.430  3365  3413 I jxcore-log: 
,08-11 07:42:29.434  3365  3413 I jxcore-log: # 164. #start should fail if called twice in a row
08-11 07:42:29.434  3365  3413 I jxcore-log: 
,08-11 07:42:29.482  3365  3413 I jxcore-log: ok 557 specific error should be received
08-11 07:42:29.482  3365  3413 I jxcore-log: 
,08-11 07:42:29.484  3365  3413 I jxcore-log: # teardown
08-11 07:42:29.484  3365  3413 I jxcore-log: 
,08-11 07:42:29.542  3365  3413 I jxcore-log: ok 558 should not be in started state
08-11 07:42:29.542  3365  3413 I jxcore-log: 
,08-11 07:42:29.546  3365  3413 I jxcore-log: # setup
08-11 07:42:29.546  3365  3413 I jxcore-log: 
,08-11 07:42:29.595  3365  3413 I jxcore-log: ok 559 should be in started state
08-11 07:42:29.595  3365  3413 I jxcore-log: 
,08-11 07:42:29.597  3365  3413 I jxcore-log: # 165. should not be started after stop is called
08-11 07:42:29.597  3365  3413 I jxcore-log: 
,08-11 07:42:29.650  3365  3413 I jxcore-log: ok 560 should not be started
08-11 07:42:29.650  3365  3413 I jxcore-log: 
,08-11 07:42:29.650  3365  3413 I jxcore-log: ok 561 should not be listening
08-11 07:42:29.650  3365  3413 I jxcore-log: 
08-11 07:42:29.651  3365  3413 I jxcore-log: ok 562 should not target listening
08-11 07:42:29.651  3365  3413 I jxcore-log: 
08-11 07:42:29.651  3365  3413 I jxcore-log: ok 563 should not be advertising
08-11 07:42:29.651  3365  3413 I jxcore-log: 
,08-11 07:42:29.652  3365  3413 I jxcore-log: ok 564 should not target advertising
08-11 07:42:29.652  3365  3413 I jxcore-log: 
,08-11 07:42:29.654  3365  3413 I jxcore-log: # teardown
08-11 07:42:29.654  3365  3413 I jxcore-log: 
,08-11 07:42:29.725  3365  3413 I jxcore-log: ok 565 should not be in started state
08-11 07:42:29.725  3365  3413 I jxcore-log: 
,08-11 07:42:29.728  3365  3413 I jxcore-log: # setup
08-11 07:42:29.728  3365  3413 I jxcore-log: 
,08-11 07:42:29.778  3365  3413 I jxcore-log: ok 566 should be in started state
08-11 07:42:29.778  3365  3413 I jxcore-log: 
,08-11 07:42:29.783  3365  3413 I jxcore-log: # 166. #startUpdateAdvertisingAndListening should fail invalid router has been passed
08-11 07:42:29.783  3365  3413 I jxcore-log: 
,08-11 07:42:29.839  3365  3413 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
08-11 07:42:29.839  3365  3413 I jxcore-log: 
,08-11 07:42:29.841  3365  3413 I jxcore-log: ok 567 specific error should be received
08-11 07:42:29.841  3365  3413 I jxcore-log: 
,08-11 07:42:29.843  3365  3413 I jxcore-log: # teardown
08-11 07:42:29.843  3365  3413 I jxcore-log: 
,08-11 07:42:29.935  3365  3413 I jxcore-log: ok 568 should not be in started state
08-11 07:42:29.935  3365  3413 I jxcore-log: 
,08-11 07:42:29.950  3365  3413 I jxcore-log: # setup
08-11 07:42:29.950  3365  3413 I jxcore-log: 
,08-11 07:42:30.002  3365  3413 I jxcore-log: ok 569 should be in started state
08-11 07:42:30.002  3365  3413 I jxcore-log: 
,08-11 07:42:30.006  3365  3413 I jxcore-log: # 167. #startUpdateAdvertisingAndListening should fail if router server starting fails
08-11 07:42:30.006  3365  3413 I jxcore-log: 
,08-11 07:42:30.105  3365  3413 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
08-11 07:42:30.105  3365  3413 I jxcore-log: 
,08-11 07:42:30.107  3365  3413 I jxcore-log: ok 570 specific error expected
08-11 07:42:30.107  3365  3413 I jxcore-log: 
,08-11 07:42:30.110  3365  3413 I jxcore-log: # teardown
08-11 07:42:30.110  3365  3413 I jxcore-log: 
,08-11 07:42:30.144  3365  3413 I jxcore-log: ok 571 should not be in started state
08-11 07:42:30.144  3365  3413 I jxcore-log: 
,08-11 07:42:30.146  3365  3413 I jxcore-log: # setup
08-11 07:42:30.146  3365  3413 I jxcore-log: 
,08-11 07:42:30.209  3365  3413 I jxcore-log: ok 572 should be in started state
08-11 07:42:30.209  3365  3413 I jxcore-log: 
,08-11 07:42:30.216  3365  3413 I jxcore-log: # 168. #startUpdateAdvertisingAndListening should start hosting given router object
08-11 07:42:30.216  3365  3413 I jxcore-log: 
,08-11 07:42:30.332  3365  3413 I jxcore-log: ok 573 server should respond with code 200
08-11 07:42:30.332  3365  3413 I jxcore-log: 
,08-11 07:42:30.338  3365  3413 I jxcore-log: # teardown
08-11 07:42:30.338  3365  3413 I jxcore-log: 
,08-11 07:42:30.461  3365  3413 I jxcore-log: ok 574 should not be in started state
08-11 07:42:30.461  3365  3413 I jxcore-log: 
,08-11 07:42:30.464  3365  3413 I jxcore-log: # setup
08-11 07:42:30.464  3365  3413 I jxcore-log: 
,08-11 07:42:30.502  3365  3413 I jxcore-log: ok 575 should be in started state
08-11 07:42:30.502  3365  3413 I jxcore-log: 
,08-11 07:42:30.504  3365  3413 I jxcore-log: # 169. #startUpdateAdvertisingAndListening bad psk should be rejected object
08-11 07:42:30.504  3365  3413 I jxcore-log: 
,08-11 07:42:30.611  3365  3413 I jxcore-log: ok 576 Connection should be rejected
08-11 07:42:30.611  3365  3413 I jxcore-log: 
,08-11 07:42:30.616  3365  3413 I jxcore-log: # teardown
08-11 07:42:30.616  3365  3413 I jxcore-log: 
,08-11 07:42:30.701  3365  3413 I jxcore-log: ok 577 should not be in started state
08-11 07:42:30.701  3365  3413 I jxcore-log: 
,08-11 07:42:30.703  3365  3413 I jxcore-log: # setup
08-11 07:42:30.703  3365  3413 I jxcore-log: 
,08-11 07:42:30.763  3365  3413 I jxcore-log: ok 578 should be in started state
08-11 07:42:30.763  3365  3413 I jxcore-log: 
,08-11 07:42:30.768  3365  3413 I jxcore-log: # 170. #stop can be called multiple times in a row
08-11 07:42:30.768  3365  3413 I jxcore-log: 
,08-11 07:42:30.809  3365  3413 I jxcore-log: ok 579 should be in stopped state
08-11 07:42:30.809  3365  3413 I jxcore-log: 
,08-11 07:42:30.811  3365  3413 I jxcore-log: ok 580 should still be in stopped state
08-11 07:42:30.811  3365  3413 I jxcore-log: 
,08-11 07:42:30.812  3365  3413 I jxcore-log: # teardown
08-11 07:42:30.812  3365  3413 I jxcore-log: 
,08-11 07:42:30.871  3365  3413 I jxcore-log: ok 581 should not be in started state
08-11 07:42:30.871  3365  3413 I jxcore-log: 
,08-11 07:42:30.874  3365  3413 I jxcore-log: # setup
08-11 07:42:30.874  3365  3413 I jxcore-log: 
,08-11 07:42:30.923  3365  3413 I jxcore-log: ok 582 should be in started state
08-11 07:42:30.923  3365  3413 I jxcore-log: 
,08-11 07:42:30.926  3365  3413 I jxcore-log: # 171. #startListeningForAdvertisements can be called multiple times in a row
08-11 07:42:30.926  3365  3413 I jxcore-log: 
,08-11 07:42:30.980  3365  3413 I jxcore-log: ok 583 should be in listening state
08-11 07:42:30.980  3365  3413 I jxcore-log: 
,08-11 07:42:30.983  3365  3413 I jxcore-log: ok 584 should still be in listening state
08-11 07:42:30.983  3365  3413 I jxcore-log: 
,08-11 07:42:30.986  3365  3413 I jxcore-log: # teardown
08-11 07:42:30.986  3365  3413 I jxcore-log: 
,08-11 07:42:31.041  3365  3413 I jxcore-log: ok 585 should not be in started state
08-11 07:42:31.041  3365  3413 I jxcore-log: 
,08-11 07:42:31.044  3365  3413 I jxcore-log: # setup
08-11 07:42:31.044  3365  3413 I jxcore-log: 
,08-11 07:42:31.100  3365  3413 I jxcore-log: ok 586 should be in started state
08-11 07:42:31.100  3365  3413 I jxcore-log: 
,08-11 07:42:31.103  3365  3413 I jxcore-log: # 172. #stopListeningForAdvertisements can be called multiple times in a row
08-11 07:42:31.103  3365  3413 I jxcore-log: 
,08-11 07:42:31.222  3365  3413 I jxcore-log: ok 587 should not be in listening state
08-11 07:42:31.222  3365  3413 I jxcore-log: 
,08-11 07:42:31.223  3365  3413 I jxcore-log: ok 588 should still not be in listening state
08-11 07:42:31.223  3365  3413 I jxcore-log: 
,08-11 07:42:31.226  3365  3413 I jxcore-log: # teardown
08-11 07:42:31.226  3365  3413 I jxcore-log: 
,08-11 07:42:31.261  3365  3413 I jxcore-log: ok 589 should not be in started state
08-11 07:42:31.261  3365  3413 I jxcore-log: 
,08-11 07:42:31.263  3365  3413 I jxcore-log: # setup
08-11 07:42:31.263  3365  3413 I jxcore-log: 
,08-11 07:42:31.338  3365  3413 I jxcore-log: ok 590 should be in started state
08-11 07:42:31.338  3365  3413 I jxcore-log: 
,08-11 07:42:31.341  3365  3413 I jxcore-log: # 173. #stopAdvertisingAndListening can be called multiple times in a row
08-11 07:42:31.341  3365  3413 I jxcore-log: 
,08-11 07:42:31.387  3365  3413 I jxcore-log: ok 591 should not be in advertising state
08-11 07:42:31.387  3365  3413 I jxcore-log: 
,08-11 07:42:31.389  3365  3413 I jxcore-log: ok 592 should still not be in advertising state
08-11 07:42:31.389  3365  3413 I jxcore-log: 
,08-11 07:42:31.392  3365  3413 I jxcore-log: # teardown
08-11 07:42:31.392  3365  3413 I jxcore-log: 
,08-11 07:42:31.450  3365  3413 I jxcore-log: ok 593 should not be in started state
08-11 07:42:31.450  3365  3413 I jxcore-log: 
,08-11 07:42:31.453  3365  3413 I jxcore-log: # setup
08-11 07:42:31.453  3365  3413 I jxcore-log: 
,08-11 07:42:31.503  3365  3413 I jxcore-log: ok 594 should be in started state
08-11 07:42:31.503  3365  3413 I jxcore-log: 
,08-11 07:42:31.507  3365  3413 I jxcore-log: # 174. functions are run from a queue in the right order
08-11 07:42:31.507  3365  3413 I jxcore-log: 
,08-11 07:42:31.593  3365  3413 I jxcore-log: ok 595 call order must match
08-11 07:42:31.593  3365  3413 I jxcore-log: 
,08-11 07:42:31.596  3365  3413 I jxcore-log: # teardown
08-11 07:42:31.596  3365  3413 I jxcore-log: 
,08-11 07:42:31.672  3365  3413 I jxcore-log: ok 596 should not be in started state
08-11 07:42:31.672  3365  3413 I jxcore-log: 
,08-11 07:42:31.675  3365  3413 I jxcore-log: # setup
08-11 07:42:31.675  3365  3413 I jxcore-log: 
,08-11 07:42:31.722  3365  3413 I jxcore-log: ok 597 should be in started state
08-11 07:42:31.722  3365  3413 I jxcore-log: 
,08-11 07:42:31.726  3365  3413 I jxcore-log: # 175. does not get peer changes from self
08-11 07:42:31.726  3365  3413 I jxcore-log: 
,08-11 07:42:32.809  3365  3413 I jxcore-log: ok 598 USN must have changed again
08-11 07:42:32.809  3365  3413 I jxcore-log: 
,08-11 07:42:33.809  3365  3413 I jxcore-log: # teardown
08-11 07:42:33.809  3365  3413 I jxcore-log: 
,08-11 07:42:33.881  3365  3413 I jxcore-log: ok 599 should not be in started state
08-11 07:42:33.881  3365  3413 I jxcore-log: 
,08-11 07:42:33.883  3365  3413 I jxcore-log: # setup
08-11 07:42:33.883  3365  3413 I jxcore-log: 
,08-11 07:42:33.960  3365  3413 I jxcore-log: # 176. #ThaliPeerPoolDefault - single action
08-11 07:42:33.960  3365  3413 I jxcore-log: 
,08-11 07:42:34.006  3365  3413 I jxcore-log: ok 600 is an agent
08-11 07:42:34.006  3365  3413 I jxcore-log: 
,08-11 07:42:34.007  3365  3413 I jxcore-log: ok 601 enqueue is fine
08-11 07:42:34.007  3365  3413 I jxcore-log: 
08-11 07:42:34.008  3365  3413 I jxcore-log: ok 602 Everything should be off the queue
08-11 07:42:34.008  3365  3413 I jxcore-log: 
,08-11 07:42:34.010  3365  3413 I jxcore-log: # teardown
08-11 07:42:34.010  3365  3413 I jxcore-log: 
,08-11 07:42:34.087  3365  3413 I jxcore-log: # setup
08-11 07:42:34.087  3365  3413 I jxcore-log: 
,08-11 07:42:34.149  3365  3413 I jxcore-log: # 177. #ThaliPeerPoolDefault - multiple actions
08-11 07:42:34.149  3365  3413 I jxcore-log: 
,08-11 07:42:34.189  3365  3413 I jxcore-log: ok 603 is an agent
08-11 07:42:34.189  3365  3413 I jxcore-log: 
,08-11 07:42:34.190  3365  3413 I jxcore-log: ok 604 first enqueue is fine
08-11 07:42:34.190  3365  3413 I jxcore-log: 
08-11 07:42:34.191  3365  3413 I jxcore-log: ok 605 is an agent
08-11 07:42:34.191  3365  3413 I jxcore-log: 
08-11 07:42:34.191  3365  3413 I jxcore-log: ok 606 second enqueue is fine
08-11 07:42:34.191  3365  3413 I jxcore-log: 
,08-11 07:42:34.193  3365  3413 I jxcore-log: ok 607 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
08-11 07:42:34.193  3365  3413 I jxcore-log: 
08-11 07:42:34.193  3365  3413 I jxcore-log: ok 608 Queue is empty
08-11 07:42:34.193  3365  3413 I jxcore-log: 
,08-11 07:42:34.195  3365  3413 I jxcore-log: # teardown
08-11 07:42:34.195  3365  3413 I jxcore-log: 
,08-11 07:42:34.272  3365  3413 I jxcore-log: # setup
08-11 07:42:34.272  3365  3413 I jxcore-log: 
,08-11 07:42:34.309  3365  3413 I jxcore-log: # 178. #ThaliPeerPoolDefault - PSK Pool works
08-11 07:42:34.309  3365  3413 I jxcore-log: 
,08-11 07:42:34.393  3365  3413 I jxcore-log: ok 609 is an agent
08-11 07:42:34.393  3365  3413 I jxcore-log: 
,08-11 07:42:34.394  3365  3413 I jxcore-log: ok 610 good enqueue
08-11 07:42:34.394  3365  3413 I jxcore-log: 
,08-11 07:42:34.436  3365  3413 I jxcore-log: ok 611 Identity should match
08-11 07:42:34.436  3365  3413 I jxcore-log: 
,08-11 07:42:34.458  3365  3413 I jxcore-log: ok 612 Got expected response
08-11 07:42:34.458  3365  3413 I jxcore-log: 
,08-11 07:42:34.459  3365  3413 I jxcore-log: ok 613 Got psk call back
08-11 07:42:34.459  3365  3413 I jxcore-log: 
,08-11 07:42:34.462  3365  3413 I jxcore-log: # teardown
08-11 07:42:34.462  3365  3413 I jxcore-log: 
,08-11 07:42:34.544  3365  3413 I jxcore-log: # setup
08-11 07:42:34.544  3365  3413 I jxcore-log: 
,08-11 07:42:34.612  3365  3413 I jxcore-log: # 179. #ThaliPeerPoolDefault - stop
08-11 07:42:34.612  3365  3413 I jxcore-log: 
,08-11 07:42:34.650  3365  3413 I jxcore-log: ok 614 is an agent
08-11 07:42:34.650  3365  3413 I jxcore-log: 
,08-11 07:42:34.651  3365  3413 I jxcore-log: ok 615 enqueue worked
08-11 07:42:34.651  3365  3413 I jxcore-log: 
08-11 07:42:34.652  3365  3413 I jxcore-log: ok 616 is an agent
08-11 07:42:34.652  3365  3413 I jxcore-log: 
08-11 07:42:34.652  3365  3413 I jxcore-log: ok 617 enqueue 2 worked
08-11 07:42:34.652  3365  3413 I jxcore-log: 
,08-11 07:42:34.654  3365  3413 I jxcore-log: ok 618 start action is killed
08-11 07:42:34.654  3365  3413 I jxcore-log: 
08-11 07:42:34.654  3365  3413 I jxcore-log: ok 619 killed action is still killed
08-11 07:42:34.654  3365  3413 I jxcore-log: 
08-11 07:42:34.655  3365  3413 I jxcore-log: ok 620 inQueue is empty
08-11 07:42:34.655  3365  3413 I jxcore-log: 
,08-11 07:42:34.657  3365  3413 I jxcore-log: ok 621 Make sure we won enqueue after stopping
08-11 07:42:34.657  3365  3413 I jxcore-log: 
,08-11 07:42:34.659  3365  3413 I jxcore-log: # teardown
08-11 07:42:34.659  3365  3413 I jxcore-log: 
,08-11 07:42:34.807  3365  3413 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 07:42:34.807  3365  3413 I jxcore-log: 
,08-11 07:42:35.480  3973  3973 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 07:42:35.485  3973  3973 D AndroidRuntime: CheckJNI is OFF
,08-11 07:42:35.528  3973  3973 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 07:42:35.579  3973  3973 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 07:42:35.603  3973  3973 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 07:42:35.615   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 07:42:35.616   873   886 I ActivityManager: Killing 3365:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 07:42:35.717   873  1375 I WindowState: WIN DEATH: Window{f5d437c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 07:42:35.717   873  1783 D GraphicsStats: Buffer count: 2
08-11 07:42:35.718   873  1309 D WifiService: Client connection lost with reason: 4
,08-11 07:42:35.756   873   896 W PackageSettings: Skipping PackageSetting{7e2f2af com.example.hello/10273} due to missing metadata
,08-11 07:42:35.788   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-11 07:42:35.788   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-11 07:42:35.789   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-11 07:42:35.789   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-11 07:42:35.789   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:35.789   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:35.789   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 07:42:35.789   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 07:42:35.790   873   886 I ActivityManager:   Force finishing activity ActivityRecord{78028a1 u0 com.test.thalitest/.MainActivity t8}
08-11 07:42:35.793   873   883 W ActivityManager: Spurious death for ProcessRecord{687e2af 0:com.test.thalitest/u0a0}, curProc for 3365: null
08-11 07:42:35.794   873   896 I art     : Starting a blocking GC Explicit
,08-11 07:42:35.836   873   896 I art     : Explicit concurrent mark sweep GC freed 34053(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 715us total 42.082ms
,08-11 07:42:35.864   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 07:42:35.866  3973  3973 I art     : System.exit called, status: 0
08-11 07:42:35.866  3973  3973 I AndroidRuntime: VM exiting with result code 0.
,08-11 07:42:35.884   873   896 I ActivityManager: Start proc 3983:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-11 07:42:35.885   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 07:42:35.905   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-11 07:42:35.918   873  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 07:42:35.920  3428  3428 D BluetoothMapAppObserver: onReceive
08-11 07:42:35.920  3428  3428 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 07:42:35.920  1959  2043 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 07:42:35.935  3205  3205 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-11 07:42:35.937  1643  1643 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-11 07:42:35.951  1643  3997 I Keyboard.Facilitator.DecoderInitializer: run()
08-11 07:42:35.956  1643  3997 I Decoder : createOrResetDecoder
,08-11 07:42:35.985  1745  1745 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 07:42:35.990   873  1637 I ActivityManager: Start proc 4000:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-11 07:42:35.996  1528  1528 I ConfigService: onCreate
,08-11 07:42:36.004   873  1306 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-11 07:42:36.007   873  2844 I ActivityManager: Killing 3264:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-11 07:42:36.014   873  1685 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3365 uid 10000
,08-11 07:42:36.016  1643  1643 I Keyboard.Facilitator: onFinishInput()
,08-11 07:42:36.021   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 07:42:36.027  1528  4011 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 07:42:36.027  1528  4011 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 07:42:36.027  1528  4011 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-11 07:42:36.029  1528  4011 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-11 07:42:36.068  1756  1829 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-11 07:42:36.069   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 07:42:36.069   873   885 E PackageManager: Failed to write settings, restoring backup
08-11 07:42:36.069   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 07:42:36.069   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 07:42:36.069   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 07:42:36.069   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 07:42:36.069   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 07:42:36.069   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.069   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.069   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 07:42:36.069  1643  3997 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-11 07:42:36.073   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-11 07:42:36.073   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 07:42:36.073   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 07:42:36.073   873   886 E DropBoxManagerService: 	... 13 more
,08-11 07:42:36.080   873  1375 I ActivityManager: Start proc 4013:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-11 07:42:36.081  1756  1829 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 07:42:36.081  1756  1829 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1756
08-11 07:42:36.081  1756  1829 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.081  1756  1829 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 07:42:36.083   873  1684 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-11 07:42:36.087   873  4018 E DropBoxManagerService: Can't write: system_app_crash
08-11 07:42:36.087   873  4018 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 07:42:36.087   873  4018 E DropBoxManagerService: 	... 5 more
,08-11 07:42:36.089  1756  1829 I Process : Sending signal. PID: 1756 SIG: 9
,08-11 07:42:36.129  4000  4000 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-11 07:42:36.150  1643  3997 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-11 07:42:36.152  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-11 07:42:36.152  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-11 07:42:36.154  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 07:42:36.154  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-11 07:42:36.154  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-11 07:42:36.154  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-11 07:42:36.155  1643  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 07:42:36.155  1643  3997 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 07:42:36.155  1643  3997 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 07:42:36.155  1643  3997 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 07:42:36.155  1643  3997 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-11 07:42:36.155  1643  3997 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-11 07:42:36.183   873  1783 D GraphicsStats: Buffer count: 1
,08-11 07:42:36.183   873   883 I WindowState: WIN DEATH: Window{b92957b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-11 07:42:36.194   873  1393 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1756) has died
,08-11 07:42:36.194   873  1393 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-11 07:42:36.196   873  1393 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-11 07:42:36.206  4000  4000 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-11 07:42:36.215   873   886 I ActivityManager: Start proc 4032:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-11 07:42:36.236  4000  4045 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 07:42:36.239   873  1783 I ActivityManager: Start proc 4046:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-11 07:42:36.272  1992  4038 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-11 07:42:36.274  1992  4038 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 07:42:36.275  4032  4032 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:42:36.275  4032  4032 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:42:36.275  4032  4032 D AndroidRuntime: Shutting down VM
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.,openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.276  4000  4028 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 07:42,:36.276  4000  4028 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.276  4000  4028 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: FATAL EXCEPTION: main
08-11 07:42:36.283  4032  4032 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4032
08-11 07:42:36.283  4032  4032 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 07:42:36.283  4032  4032 E AndroidRuntime: 	... 10 more
08-11 07:42:36.285   873  1676 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 07:42:36.286  4032  4032 I Process : Sending signal. PID: 4032 SIG: 9
08-11 07:42:36.287   873  4058 E DropBoxManagerService: Can't write: system_app_crash
08-11 07:42:36.287   873  4058 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 07:42:36.287   873  4058 E DropBoxManagerService: 	... 5 more
08-11 07:42:36.300  4046  4046 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-11 07:42:36.301  1992  4038 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-11 07:42:36.301  1992  4038 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-11 07:42:36.311   873  1676 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4032) has died
,08-11 07:42:36.313   873  1676 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-11 07:42:36.331   873   886 I ActivityManager: Start proc 4061:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 07:42:36.337   873  1689 I ActivityManager: Killing 1805:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-11 07:42:36.355  4000  4028 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-11 07:42:36.363  4000  4045 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.363  4000  4045 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 07:42:36.363  4000  4045 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-11 07:42:36.363  4000  4045 E AndroidRuntime: Process: android.process.acore, PID: 4000
08-11 07:42:36.363  4000  4045 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 07:42:36.363  4000  4045 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 07:42:36.365  4000  4028 I Process : Sending signal. PID: 4000 SIG: 9
,08-11 07:42:36.375   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
