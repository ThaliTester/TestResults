#### Test 83084099807e426_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 16:54:23.527  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 16:54:23.548  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 16:54:23.552  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-31 16:54:23.629  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-31 16:54:23.630  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-31 16:54:23.630  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:23.630  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 16:54:23.660  1526  1538 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 16:54:23.660  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 16:54:23.660  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 16:54:23.660  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 16:54:23.660  1526  1538 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 16:54:23.660  1526  1538 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 16:54:23.660  1526  1538 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:23.675  2725  2754 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 16:54:23.675  2725  2754 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 16:54:23.675  2725  2754 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 16:54:23.675  2725  2754 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 16:54:23.675  2725  2754 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 16:54:23.675  2725  2754 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 16:54:23.675  2725  2754 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:24.175  3480  3480 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 16:54:24.179  3480  3480 D AndroidRuntime: CheckJNI is OFF
08-31 16:54:24.215  3480  3480 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 16:54:24.257  3480  3480 I Radio-JNI: register_android_hardware_Radio DONE
08-31 16:54:24.277  3480  3480 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 16:54:24.283   872  1730 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 16:54:24.342   872  1730 I ActivityManager: Start proc 3490:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 16:54:24.347  3480  3480 D AndroidRuntime: Shutting down VM
08-31 16:54:24.423  3490  3490 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 16:54:24.455  3490  3490 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 16:54:24.536  3490  3490 I LibraryLoader: Time to load native libraries: 75 ms (timestamps 2050-2125)
08-31 16:54:24.536  3490  3490 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:54:24.565  3490  3490 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {aa83c98}
08-31 16:54:24.566  3490  3490 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:54:24.566  3490  3490 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 16:54:24.573  3490  3490 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 16:54:24.574  3490  3490 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 16:54:24.650  3490  3506 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-31 16:54:24.659  3490  3490 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 16:54:24.669  3490  3490 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 16:54:24.669  3490  3490 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:54:24.669  3490  3490 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 16:54:24.669  3490  3490 I Adreno  : Build Date                       : 10/20/15
08-31 16:54:24.669  3490  3490 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 16:54:24.669  3490  3490 I Adreno  : Local Branch                     : M14
08-31 16:54:24.669  3490  3490 I Adreno  : Remote Branch                    : 
08-31 16:54:24.669  3490  3490 I Adreno  : Remote Branch                    : 
08-31 16:54:24.669  3490  3490 I Adreno  : Reconstruct Branch               : 
,08-31 16:54:24.756   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aa81aeb:true
,08-31 16:54:24.805  3490  3490 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:54:24.820  3490  3490 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 16:54:24.873  3490  3528 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 16:54:24.873   872   885 W ActivityManager: Activity pause timeout for ActivityRecord{c8576c4 u0 com.test.thalitest/.MainActivity t2}
,08-31 16:54:24.884  3490  3515 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 16:54:24.918  3490  3528 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:54:24.931  1887  1887 I Keyboard.Facilitator: onFinishInput()
,08-31 16:54:24.977   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +604ms (total +679ms)
,08-31 16:54:25.028  3490  3490 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3490
,08-31 16:54:25.183  3490  3490 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:54:25.401  3490  3529 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1658324688
,08-31 16:54:25.409  3490  3529 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:54:25.409  3490  3529 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:54:25.409  3490  3529 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:54:25.409  3490  3529 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:54:25.409  3490  3529 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 16:54:25.410  3490  3529 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0360f added. We now have 1 listener(s)
,08-31 16:54:25.414  3490  3529 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 16:54:25.415  3490  3529 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 16:54:25.416  3490  3529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 16:54:25.416  3490  3529 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 16:54:25.421  3490  3529 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@140647a added. We now have 1 listener(s)
08-31 16:54:25.422  3490  3529 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:54:25.427   872  1315 D WifiService: New client listening to asynchronous messages
,08-31 16:54:25.428  3490  3529 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:54:25.428  3490  3529 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 16:54:25.429  3490  3529 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:54:25.429  3490  3529 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:54:25.430  3490  3529 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 16:54:25.432  3490  3529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 16:54:25.432  3490  3529 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 16:54:25.436  3490  3529 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:25.436  3490  3529 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:54:25.436  3490  3529 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:54:25.436  3490  3529 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 16:54:25.437  3490  3529 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:54:25.438  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:25.484  3490  3490 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:54:26.639  3490  3537 W jxcore-log: Initializing JXcore engine
,08-31 16:54:26.639  3490  3537 W jxcore-log: JXcore engine is ready
,08-31 16:54:26.690  3537  3537 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8930 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 16:54:26.690  3537  3537 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11864]" dev="sockfs" ino=11864 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 16:54:26.690  3537  3537 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 16:54:26.690  3537  3537 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24901]" dev="sockfs" ino=24901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,08-31 16:54:26.706  3490  3537 W jxcore-log: Starting JXcore engine
,08-31 16:54:26.792  3490  3537 W jxcore-log: Platform android
08-31 16:54:26.792  3490  3537 W jxcore-log: 
,08-31 16:54:26.792  3490  3537 W jxcore-log: Process ARCH arm
08-31 16:54:26.792  3490  3537 W jxcore-log: 
,08-31 16:54:26.997  3490  3537 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:54:26.997  3490  3537 I jxcore-log: 
,08-31 16:54:26.998  3490  3537 W jxcore-log: JXcore engine is started
,08-31 16:54:27.010  3490  3529 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 16:54:27.015  3490  3490 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 16:54:40.549  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 16:54:40.549  3490  3537 I jxcore-log: 
,08-31 16:54:40.553  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 16:54:40.553  3490  3537 I jxcore-log: 
,08-31 16:54:40.554  3490  3537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:40.554  3490  3537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:54:40.555  3490  3537 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:54:40.555  3490  3537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:54:40.557  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 16:54:40.557  3490  3537 I jxcore-log: 
08-31 16:54:40.561  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 16:54:40.561  3490  3537 I jxcore-log: 
,08-31 16:54:40.906  3490  3537 I jxcore-log: Running unit tests
08-31 16:54:40.906  3490  3537 I jxcore-log: 
,08-31 16:54:40.907  3490  3537 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 16:54:40.907  3490  3537 I jxcore-log: Failed to execute UT.
08-31 16:54:40.907  3490  3537 I jxcore-log: 
,08-31 16:54:40.909  3490  3537 I jxcore-log: Unit Test app is loaded
08-31 16:54:40.909  3490  3537 I jxcore-log: 
,08-31 16:54:40.915  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 16:54:40.915  3490  3537 I jxcore-log: 
,08-31 16:54:40.920   872  1968 D WifiService: setWifiEnabled: true pid=3490, uid=10000
,08-31 16:54:40.920   872  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 16:54:40.927  3490  3537 I jxcore-log: My device name is: motorola-Nexus 6
08-31 16:54:40.927  3490  3537 I jxcore-log: 
,08-31 16:54:40.930  3490  3537 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 16:54:40.930  3490  3537 I jxcore-log: 
,08-31 16:54:40.943  3490  3490 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 16:54:40.965   872   889 I ActivityManager: Start proc 3540:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 16:54:40.966   872  1314 D WifiConfigStore: Loading config and enabling all networks 
08-31 16:54:40.977  3490  3490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:40.977  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:54:40.977  3490  3490 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:54:40.977  3490  3490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:54:40.991   872   885 I ActivityManager: Start proc 3547:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-31 16:54:40.993   872  1314 D WifiConfigStore: loaded 0 passpoint configs
08-31 16:54:40.994   872  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 16:54:40.995   872  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 16:54:40.996   872  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 16:54:40.996   872  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 16:54:40.996   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 16:54:40.996   872  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 16:54:41.055   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 16:54:41.056   872  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-31 16:54:41.057   371   870 D CommandListener: Setting iface cfg
,08-31 16:54:41.058   872  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
08-31 16:54:41.058   872  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 16:54:41.068   872  1314 E native  : do suspend true
,08-31 16:54:41.068  3547  3547 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 16:54:41.080   872  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 16:54:41.093   872  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 16:54:41.097   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 16:54:41.102  3540  3540 D AdapterServiceConfig: Adding HeadsetService
,08-31 16:54:41.102  3540  3540 D AdapterServiceConfig: Adding A2dpService
,08-31 16:54:41.104  3540  3540 D AdapterServiceConfig: Adding HidService
,08-31 16:54:41.104  3540  3540 D AdapterServiceConfig: Adding HealthService
,08-31 16:54:41.105  3540  3540 D AdapterServiceConfig: Adding PanService
,08-31 16:54:41.105  3540  3540 D AdapterServiceConfig: Adding GattService
08-31 16:54:41.105  3540  3540 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 16:54:41.128  3547  3547 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 16:54:41.130   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4356acb:true
08-31 16:54:41.131  3540  3540 D BluetoothAdapterState: make() - Creating AdapterState
08-31 16:54:41.134  3540  3540 I bt_bluedroid: init
08-31 16:54:41.134  3540  3574 I BluetoothAdapterState: Entering OffState
08-31 16:54:41.137  3540  3577 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 16:54:41.138  3540  3577 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 16:54:41.138  3540  3577 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 16:54:41.138  3540  3577 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 16:54:41.140  3540  3540 I bt_bluedroid: get_profile_interface socket
08-31 16:54:41.141  3540  3540 I bt_bluedroid: get_profile_interface sdp
08-31 16:54:41.144  3540  3557 I bt_bluedroid: config_hci_snoop_log
08-31 16:54:41.145   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-31 16:54:41.146  3540  3580 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 16:54:41.148  3540  3574 D BluetoothAdapterState: Current state: OFF, message: 0
08-31 16:54:41.149  3540  3580 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 16:54:41.150  3540  3574 D BluetoothAdapterProperties: Setting state to 14
08-31 16:54:41.150  3540  3574 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-31 16:54:41.151  3540  3574 D BluetoothBondStateMachine: make
08-31 16:54:41.153  3540  3582 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 16:54:41.154  3540  3574 I BluetoothAdapterState: Entering PendingCommandState
08-31 16:54:41.155  3540  3540 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-31 16:54:41.158  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
08-31 16:54:41.158   872  1401 I ActivityManager: Killing 2811:com.google.android.calendar/u0a37 (adj 15): empty #17
08-31 16:54:41.159  3540  3540 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 16:54:41.159  3540  3540 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:54:41.159  3540  3540 D BtGatt.GattService: start()
08-31 16:54:41.159  3540  3540 I bt_bluedroid: get_profile_interface gatt
08-31 16:54:41.160  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
08-31 16:54:41.160  3540  3540 D BtGatt.AdvertiseManager: advertise manager created
,08-31 16:54:41.194  3540  3540 V BluetoothAdapterState: isTurningOff()=false
,08-31 16:54:41.194  3540  3540 V BluetoothAdapterState: isTurningOn()=false
08-31 16:54:41.194  3540  3540 V BluetoothAdapterState: isBleTurningOn()=true
08-31 16:54:41.194  3540  3540 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:41.194  3540  3574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 16:54:41.194  3540  3574 I bt_bluedroid: enable
08-31 16:54:41.195  3540  3577 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 16:54:41.195  3540  3577 I bt_hci  : start_up
,08-31 16:54:41.203  3540  3577 I bt_vendor: alloc value 0xb39fa189
,08-31 16:54:41.203  3540  3577 I bt_vendor: init
08-31 16:54:41.204  3540  3577 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 16:54:41.204  3540  3577 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 16:54:41.311  3540  3577 D bt_hci  : start_up starting async portion
,08-31 16:54:41.312  3540  3586 I bt_hci  : event_finish_startup
,08-31 16:54:41.312  3540  3586 I bt_hci_h4: hal_open
,08-31 16:54:41.312  3540  3586 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 16:54:41.319  3540  3586 I bt_userial_vendor: device fd = 51 open
,08-31 16:54:41.361  3540  3586 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 16:54:41.388  3540  3586 D bt_hwcfg: Chipset BCM4354A2
,08-31 16:54:41.388  3540  3586 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 16:54:41.389  3540  3586 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 16:54:42.125  3540  3586 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-31 16:54:42.126  3540  3586 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 16:54:42.126  3540  3586 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 16:54:42.242  3540  3586 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-31 16:54:42.242  3540  3586 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 16:54:42.275  3540  3586 I bt_hwcfg: vendor lib fwcfg completed
08-31 16:54:42.275  3540  3586 I bt_vendor: firmware callback
08-31 16:54:42.275  3540  3586 I bt_hci  : firmware_config_callback
,08-31 16:54:42.286  3540  3589 I bt_btu  : btu_task pending for preload complete event
,08-31 16:54:42.286  3540  3589 I bt_btu_task: Bluetooth chip preload is complete
08-31 16:54:42.287  3540  3589 I bt_btu  : btu_task received preload complete event
,08-31 16:54:42.296  3540  3589 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 16:54:42.296  3540  3589 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:54:42.296  3540  3589 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 16:54:42.296  3540  3589 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 16:54:42.297  3540  3589 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:54:42.297  3540  3589 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 16:54:42.297  3540  3589 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 16:54:42.297  3540  3589 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 16:54:42.298  3540  3589 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:54:42.298  3540  3589 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 16:54:42.298  3540  3589 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 16:54:42.298  3540  3589 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 16:54:42.298  3540  3589 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:54:42.298  3540  3589 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 16:54:42.299  3540  3589 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 16:54:42.431   872  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-31 16:54:42.436   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,08-31 16:54:42.437   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:54:42.439  3540  3589 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3977d9d
08-31 16:54:42.439  3540  3589 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3977d9d 
,08-31 16:54:42.450  3540  3580 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 16:54:42.454  3540  3580 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 16:54:42.454  3540  3580 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 16:54:42.456  3540  3580 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 16:54:42.457  3540  3580 D BluetoothAdapterProperties: Scan Mode:20
,08-31 16:54:42.457  3540  3580 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 16:54:42.457  3540  3580 D bt_hci  : do_postload posting postload work item
,08-31 16:54:42.457  3540  3586 I bt_hci  : event_postload
08-31 16:54:42.457  3540  3586 I bt_vendor: sco_config_cb
08-31 16:54:42.458  3540  3586 I bt_hci  : sco_config_callback postload finished.
08-31 16:54:42.458  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:42.459  3540  3580 D bt_bte_conf: Device ID record 1 : primary
,08-31 16:54:42.459  3540  3580 D bt_bte_conf:   vendorId            = 000f
,08-31 16:54:42.459  3540  3580 D bt_bte_conf:   vendorIdSource      = 0001
08-31 16:54:42.459  3540  3580 D bt_bte_conf:   product             = 1200
08-31 16:54:42.459  3540  3580 D bt_bte_conf:   version             = 1436
,08-31 16:54:42.459  3540  3580 D bt_bte_conf:   clientExecutableURL = 
,08-31 16:54:42.459  3540  3580 D bt_bte_conf:   serviceDescription  = 
08-31 16:54:42.459  3540  3580 D bt_bte_conf:   documentationURL    = 
08-31 16:54:42.460  3540  3580 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 16:54:42.460   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 16:54:42.461  3540  3577 D bt_stack_manager: event_start_up_stack finished
,08-31 16:54:42.461  3540  3574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 16:54:42.461  3540  3574 D BluetoothAdapterProperties: Setting state to 15
,08-31 16:54:42.461  3540  3574 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 16:54:42.463  3540  3574 I BluetoothAdapterState: Entering BleOnState
,08-31 16:54:42.465  3540  3574 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 16:54:42.465  3540  3574 D BluetoothAdapterProperties: Setting state to 11
08-31 16:54:42.465  3540  3574 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 16:54:42.468  3540  3586 I bt_vendor: low_power_mode_cb
,08-31 16:54:42.468  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
,08-31 16:54:42.471  3540  3540 D HeadsetService: Received start request. Starting profile...
08-31 16:54:42.474  3540  3540 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:54:42.474  3540  3540 D HeadsetStateMachine: make
,08-31 16:54:42.482  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:54:42.495   872   885 I ActivityManager: Start proc 3596:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-31 16:54:42.498  3540  3540 D HeadsetStateMachine: max_hf_connections = 1
,08-31 16:54:42.498  3540  3540 I bt_bluedroid: get_profile_interface handsfree
,08-31 16:54:42.499  3540  3580 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 16:54:42.499  3540  3580 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-31 16:54:42.502  3540  3574 I BluetoothAdapterState: Entering PendingCommandState
,08-31 16:54:42.502  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
,08-31 16:54:42.503   872   872 D BluetoothA2dp: Proxy object connected
08-31 16:54:42.503  3540  3540 D A2dpService: Received start request. Starting profile...
,08-31 16:54:42.504  3540  3540 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 16:54:42.504  3540  3540 I bt_bluedroid: get_profile_interface avrcp
08-31 16:54:42.510  3540  3540 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 16:54:42.511  3540  3540 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 16:54:42.511  3540  3540 D A2dpStateMachine: make
08-31 16:54:42.515  3540  3540 I bt_bluedroid: get_profile_interface a2dp
,08-31 16:54:42.518  3540  3580 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-31 16:54:42.519  3540  3540 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 16:54:42.521  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
,08-31 16:54:42.521  3540  3608 D A2dpStateMachine: Enter Disconnected: -2
08-31 16:54:42.522  1371  1371 D BluetoothInputDevice: Proxy object connected
,08-31 16:54:42.522  1371  1371 D HidProfile: Bluetooth service connected
08-31 16:54:42.523  3540  3540 D HidService: Received start request. Starting profile...
08-31 16:54:42.523  3540  3540 I bt_bluedroid: get_profile_interface hidhost
,08-31 16:54:42.523  3540  3580 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39593e5
08-31 16:54:42.523  3540  3540 D HidService: setHidService(): set to: null
,08-31 16:54:42.524  3540  3580 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 16:54:42.524  3540  3540 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 16:54:42.525  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
08-31 16:54:42.526  3540  3540 D HealthService: Received start request. Starting profile...
,08-31 16:54:42.528  3540  3540 I bt_bluedroid: get_profile_interface health
08-31 16:54:42.530  3540  3540 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 16:54:42.532  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
08-31 16:54:42.535  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:54:42.535  1371  1371 D PanProfile: Bluetooth service connected
08-31 16:54:42.536  3540  3540 D PanService: Received start request. Starting profile...
08-31 16:54:42.536  3540  3540 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 16:54:42.536  3540  3540 I bt_bluedroid: get_profile_interface pan
08-31 16:54:42.536  3540  3580 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 16:54:42.538  3540  3594 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 16:54:42.539  3540  3540 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:42.539  3540  3540 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:42.539  3540  3540 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:42.539  3540  3540 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:42.542  3540  3540 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6f9b462
08-31 16:54:42.542   872  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
08-31 16:54:42.543  1371  1371 D BluetoothMap: Proxy object connected
08-31 16:54:42.543  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
08-31 16:54:42.543  1371  1371 D MapProfile: Bluetooth service connected
08-31 16:54:42.543  1371  1371 D BluetoothMap: getConnectedDevices()
08-31 16:54:42.545  1371  1371 D BluetoothMap: Bluetooth is Not enabled
08-31 16:54:42.545  3540  3540 D BluetoothMapService: Received start request. Starting profile...
08-31 16:54:42.545  3540  3540 D BluetoothMapService: start()
08-31 16:54:42.548  3540  3540 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 16:54:42.549  3540  3540 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 16:54:42.549  3540  3540 D BluetoothMapAppObserver: createReceiver()
08-31 16:54:42.550  3540  3540 D BluetoothMapAppObserver: initObservers()
08-31 16:54:42.550  3540  3540 D BluetoothMapAppObserver: getEnabledAccountItems()
08-31 16:54:42.562  3540  3540 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:42.562  3540  3540 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:42.562  3540  3540 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:42.562  3540  3540 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:42.563  3540  3540 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:42.563  3540  3540 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:42.563  3540  3540 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:42.563  3596  3596 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-31 16:54:42.563  3540  3540 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:42.563  3540  3540 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:42.563  3540  3540 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isBleTurningOff()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isTurningOff()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isTurningOn()=true
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isBleTurningOn()=false
08-31 16:54:42.564  3540  3540 V BluetoothAdapterState: isB,leTurningOff()=false
08-31 16:54:42.565  3540  3574 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 16:54:42.565  3540  3574 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:54:42.565  3540  3574 D BluetoothAdapterProperties: State =  11
08-31 16:54:42.565  3540  3574 D BluetoothAdapterProperties: Setting state to 12
08-31 16:54:42.566  3540  3574 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 16:54:42.566  3540  3574 I BluetoothAdapterState: Entering OnState
08-31 16:54:42.566   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:54:42.566  3540  3580 D BluetoothAdapterProperties: Scan Mode:21
08-31 16:54:42.567  1371  2050 D BluetoothMap: onBluetoothStateChange: up=true
08-31 16:54:42.567  3540  3580 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:54:42.567  1371  2036 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 16:54:42.567   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:54:42.568  1371  1385 D BluetoothPan: onBluetoothStateChange on: true
08-31 16:54:42.568   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:54:42.569  1371  1383 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 16:54:42.569  3490  3490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 16:54:42.570   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:54:42.570  1961  2105 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 16:54:42.571  3490  3490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 16:54:42.573   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:54:42.573  3490  3490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 16:54:42.573  3540  3540 D BluetoothMapService: onReceive
08-31 16:54:42.574  3540  3540 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:54:42.574  3540  3540 D BluetoothMapService: STATE_ON
08-31 16:54:42.577  1371  1678 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:54:42.577  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:54:42.580  3490  3490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:54:42.580  1371  1371 D BluetoothA2dp: Proxy object connected
08-31 16:54:42.582  3540  3540 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 16:54:42.582  3540  3540 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-31 16:54:42.582  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:54:42.583  1371  1678 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 16:54:42.583  3540  3540 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:54:42.586  3540  3540 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:54:42.586   872  2824 I ActivityManager: Killing 2983:com.google.android.gm/u0a78 (adj 15): empty #17
,08-31 16:54:42.661  3540  3540 D ObexServerSockets: Succeed to create listening sockets 
08-31 16:54:42.661  3540  3540 D ObexServerSockets0: startAccept()
08-31 16:54:42.661  3540  3540 D ObexServerSockets0: prepareForNewConnect()
08-31 16:54:42.663  3540  3540 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-31 16:54:42.663  3540  3540 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 16:54:42.663  3540  3540 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 16:54:42.664  3540  3540 D ObexServerSockets0: prepareForNewConnect()
08-31 16:54:42.666  3540  3617 D ObexServerSockets0: Accepting socket connection...
08-31 16:54:42.666  3540  3616 D ObexServerSockets0: Accepting socket connection...
08-31 16:54:42.669   872   889 D BluetoothHeadset: Proxy object connected
08-31 16:54:42.671   872   889 D BluetoothHeadset: Proxy object connected
08-31 16:54:42.671   872   889 D BluetoothHeadset: Proxy object connected
,08-31 16:54:42.674  1961  1974 D BluetoothHeadset: Proxy object connected
,08-31 16:54:42.676  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 16:54:42.688  1371  2050 D BluetoothHeadset: Proxy object connected
,08-31 16:54:42.689  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-31 16:54:42.695   872  1992 I ActivityManager: Start proc 3618:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 16:54:42.736  3618  3618 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.866  3618  3618 D StrictMode: StrictMode policy violation; ~duration=45 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:42.866  3618  3618 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:42.877  3596  3596 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 16:54:42.885   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cd4c811:true
08-31 16:54:42.892  1526  1526 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 16:54:42.895  1371  1371 D BluetoothPbap: Proxy object connected
08-31 16:54:42.895  1371  1371 D PbapServerProfile: Bluetooth service connected
08-31 16:54:42.904  3540  3642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:54:42.906  3596  3596 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:54:42.922  3596  3596 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 16:54:42.934  3596  3596 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 16:54:42.936  3596  3596 D BluetoothMap: Create BluetoothMap proxy object
08-31 16:54:42.942  3596  3596 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-31 16:54:42.947  3540  3650 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 16:54:42.948  3540  3650 I BtOppRfcommListener: Accept thread started.
08-31 16:54:42.950  3596  3596 D DockEventReceiver: finishStartingService: stopping service
08-31 16:54:42.952  3596  3596 D BluetoothA2dp: Proxy object connected
,08-31 16:54:42.959  3596  3596 D BluetoothInputDevice: Proxy object connected
,08-31 16:54:42.959  3596  3596 D HidProfile: Bluetooth service connected
,08-31 16:54:42.962  3596  3596 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:54:42.962  3596  3596 D PanProfile: Bluetooth service connected
08-31 16:54:42.962  3596  3596 D BluetoothMap: Proxy object connected
08-31 16:54:42.962  3596  3596 D MapProfile: Bluetooth service connected
,08-31 16:54:42.962  3596  3596 D BluetoothMap: getConnectedDevices()
,08-31 16:54:42.965  3596  3596 D BluetoothPbap: Proxy object connected
,08-31 16:54:42.965  3596  3596 D PbapServerProfile: Bluetooth service connected
,08-31 16:54:42.968   872  1730 I ActivityManager: Killing 3180:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 16:54:43.009  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 16:54:43.024  3596  3609 D BluetoothHeadset: Proxy object connected
,08-31 16:54:43.025  3596  3596 D HeadsetProfile: Bluetooth service connected
,08-31 16:54:43.038  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:54:43.038  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 16:54:43.039   872  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 16:54:43.045   872  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 16:54:43.045   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 16:54:43.045   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 16:54:43.056   872  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 16:54:43.062   371   870 D CommandListener: Setting iface cfg
,08-31 16:54:43.066   872  1314 D WifiStateMachine: Start Dhcp Watchdog 1
,08-31 16:54:43.071   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-31 16:54:43.093   872  3657 D DhcpClient: Receive thread started
,08-31 16:54:43.177  3618  3638 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 16:54:43.177   872  1314 E native  : do suspend false
,08-31 16:54:43.192   872  3656 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 16:54:43.201   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4568f1a:true
,08-31 16:54:43.205   872  3657 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170982, domain null
,08-31 16:54:43.206   872  3656 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170982 seconds
,08-31 16:54:43.208   872  3656 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 16:54:43.229   872  3657 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 16:54:43.229   872  3656 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 16:54:43.231   371   870 D CommandListener: Setting iface cfg
,08-31 16:54:43.233   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 16:54:43.239   872  1314 E native  : do suspend true
,08-31 16:54:43.239   872  3656 D DhcpClient: Scheduling renewal in 86399s
,08-31 16:54:43.250   872  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 16:54:43.250   872  1314 D WifiConfigStore: No blacklist allowed without epno enabled
08-31 16:54:43.251   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-31 16:54:43.251   872  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:54:43.252   872  1316 D ConnectivityService: Adding iface wlan0 to network 100
,08-31 16:54:43.318   872  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 16:54:43.318   872  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-31 16:54:43.320   872  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-31 16:54:43.321   872  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-31 16:54:43.322   872  1316 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-31 16:54:43.327   872  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 16:54:43.330   872  1316 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-31 16:54:43.331   872  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-31 16:54:43.331   872  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 16:54:43.332   872  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-31 16:54:43.332   872  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 16:54:43.332   872  1316 D ConnectivityService:    accepting network in place of null
,08-31 16:54:43.333   872  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 16:54:43.350   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 16:54:43.358   872  3655 D NetlinkSocketObserver: NeighborEvent{elapsedMs=350945, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 16:54:43.372   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 16:54:43.373   872  1316 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-31 16:54:43.376   872  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-31 16:54:43.376   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:54:43.378   872  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-31 16:54:43.380   872   889 D Tethering: MasterInitialState.processMessage what=3
08-31 16:54:43.382   872  1990 V BackupManagerService: Scheduling immediate backup pass
08-31 16:54:43.382   872   872 V BackupManagerService: Running a backup pass
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:54:43.383  3490  3490 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 16:54:43.384  3490  3490 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 16:54:43.385   872  1338 V BackupManagerService: clearing pending backups
08-31 16:54:43.389   872  1338 V PerformBackupTask: Beginning backup of 16 targets
,08-31 16:54:43.402   872  1338 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-31 16:54:43.407   872  1338 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
08-31 16:54:43.414  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 16:54:43.427  1731  1731 D SystemUpdateService: onCreate
08-31 16:54:43.430  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-31 16:54:43.432   872  3654 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:810::200e
08-31 16:54:43.438   872  1929 D AlarmManagerService: Setting time of day to sec=1472655283
08-31 16:54:43.107   872  1929 W AlarmManagerService: Unable to set rtc to 1472655283: Invalid argument
08-31 16:54:43.108  1731  3678 I SystemUpdateService: active receiver: enabled
,08-31 16:54:43.112  1731  3678 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 16:54:43.112   872  3679 D GpsLocationProvider: NTP server returned: 1472655283109 (Wed Aug 31 16:54:43 GMT+02:00 2016) reference: 351030 certainty: 10 system time offset: -3
08-31 16:54:43.112   872  3679 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-31 16:54:43.113  1731  3678 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 16:54:43.113  1731  3678 I SystemUpdateService: now status is 0 (complete)
,08-31 16:54:43.113  1731  3678 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 16:54:43.113  1731  3678 I SystemUpdateService: file has been verified
08-31 16:54:43.113  1731  3678 I SystemUpdateService: OTA package size = 12249756
,08-31 16:54:43.116   872  1338 I BackupRestoreController: Getting widget state for user: 0
,08-31 16:54:43.117  1731  3678 I SystemUpdateService: showing system update notification
,08-31 16:54:43.153  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 16:54:43.154  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 16:54:43.158  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 16:54:43.193   872  3654 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 14:54:43 GMT], X-Android-Received-Millis=[1472655283190], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472655283156]}
,08-31 16:54:43.194  1731  3691 I iu.SyncManager: SYNC; picasa accounts
08-31 16:54:43.196   872  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-31 16:54:43.196   872  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-31 16:54:43.196   872  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-31 16:54:43.197   872  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-31 16:54:43.203  1731  1731 D NetworkLogImpl: Loaded NetworkSpeedPredictor
08-31 16:54:43.206  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 16:54:43.216  1731  1731 D SystemUpdateService: onDestroy
,08-31 16:54:43.220  3547  3684 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
08-31 16:54:43.221  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 16:54:43.222  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 16:54:43.223  1731  3691 I iu.UploadsManager: num queued entries: 0
08-31 16:54:43.224  1731  3691 I iu.UploadsManager: num updated entries: 0
08-31 16:54:43.224  1731  3691 I iu.SyncManager: NEXT; no task
,08-31 16:54:43.233   872   882 I ActivityManager: Start proc 3694:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 16:54:43.235  1731  3689 I MDM     : [150] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 16:54:43.235  1731  3689 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 16:54:43.241  1526  1526 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 16:54:43.249  1731  3689 V GoogleAuthProtoRequest: [150] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 16:54:43.284  1911  2220 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-31 16:54:43.284  1911  2220 V GmsBackupTransport: starting performBackup for @pm@
,08-31 16:54:43.289  3694  3694 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 16:54:43.290  1911  2220 V GmsBackupTransport: performBackup done for @pm@
,08-31 16:54:43.296  3694  3694 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:54:43.311  1731  3677 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-31 16:54:43.314  3694  3694 D SprintDMHelper: simOperator: 
,08-31 16:54:43.314  3694  3694 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 16:54:43.326  1526  2720 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 16:54:43.327  1526  2720 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 16:54:43.327  1526  2720 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 16:54:43.327  1526  2720 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:43.330   872  2824 I ActivityManager: Start proc 3713:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 16:54:43.340  1526  1526 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 16:54:43.358  1526  2070 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-31 16:54:43.367  1526  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-31 16:54:43.368  1526  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-31 16:54:43.368  1526  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:43.368  1526  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:43.358  1526  2070 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-31 16:54:43.372  1526  2070 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:43.372  1526  2070 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:43.375  1526  1538 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 16:54:43.375  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 16:54:43.375  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 16:54:43.375  1526  1538 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 16:54:43.375  1526  1538 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 16:54:43.375  1526  1538 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 16:54:43.375  1526  1538 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 16:54:43.384  1911  1925 W GmsBackupTransport: Error sending final backup to server: 
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 16:54:43.384  1911  1925 W GmsBackupTransport: 	... 1 more
,08-31 16:54:43.384  1911  2220 I GmsBackupTransport: Next backup will happen in 43199998 millis.
,08-31 16:54:43.385   872  1338 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-31 16:54:43.388  1731  3689 E MDM     : [150] SitrepService.a: Error sending sitrep.
,08-31 16:54:43.399  3547  3684 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	,at com.a.a.a.g.a(SourceFile:79)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-31 16:54:43.427  3547  3684 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-31 16:54:43.477  3490  3537 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:54:43.477  3490  3537 I jxcore-log: 
,08-31 16:54:43.504   872  1728 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1731 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:54:43.540   872  1338 I BackupManagerService: Backup pass finished.
,08-31 16:54:43.630  1731  3682 W DriveInitializer: Awaiting to be initialized
,08-31 16:54:43.631  1731  3737 W DriveInitializer: Background init thread started
,08-31 16:54:43.656  1526  3743 I VacuumService: Vacuum at: now=1472655283656 tag=VacuumService
,08-31 16:54:43.665  1526  3729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 16:54:43.665  1526  3729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-31 16:54:43.665  1526  3729 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 16:54:43.665  1526  3729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:43.682  3261  3700 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 16:54:43.682  3261  3700 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jdm.a(PG:82)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jcs.o(PG:406)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jcn.a(PG:1379)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jcs.i(PG:143)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at blb.a(PG:3937)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at czp.a(PG:18188)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at czp.a(PG:9081)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at czq.run(PG:1686)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:43.682  3261  3700 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jdj.a(PG:4091)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jdj.a(PG:1125)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jdm.a(PG:77)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	... 12 more
08-31 16:54:43.682  3261  3700 E HttpOperation: Caused by: faj: BadAuthentication
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at fal.a(PG:38)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	at jdj.a(PG:4089)
08-31 16:54:43.682  3261  3700 E HttpOperation: 	... 14 more
,08-31 16:54:43.697  1731  3737 W DriveInitializer: Background init thread ended
,08-31 16:54:43.709  1526  3706 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-31 16:54:43.723  1526  2070 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-31 16:54:43.723  1526  2070 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 16:54:43.723  1526  2070 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:43.724  1526  2070 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:43.750   872  1990 I ActivityManager: Start proc 3756:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 16:54:43.773  3261  3700 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 16:54:43.773  3261  3700 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jdm.a(PG:82)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jcs.o(PG:406)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jcn.a(PG:1379)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jcs.i(PG:143)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at hec.a(PG:42)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at hee.a(PG:102)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at czr.a(PG:65)
,08-31 16:54:43.773  3261  3700 E HttpOperation: 	at kka.a(PG:108)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at czp.a(PG:19176)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at czp.a(PG:9081)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at czq.run(PG:1686)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:43.773  3261  3700 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jdj.a(PG:4091)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jdj.a(PG:1125)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jdm.a(PG:77)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	... 15 more
08-31 16:54:43.773  3261  3700 E HttpOperation: Caused by: faj: BadAuthentication
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at fal.a(PG:38)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	at jdj.a(PG:4089)
08-31 16:54:43.773  3261  3700 E HttpOperation: 	... 17 more
,08-31 16:54:43.773  3261  3700 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 16:54:43.773  3261  3700 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at hec.a(PG:42)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at hee.a(PG:102)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at czr.a(PG:65)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at kka.a(PG:108)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	... 15 more
08-31 16:54:43.773  3261  3700 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at fal.a(PG:38)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 16:54:43.773  3261  3700 E ExperimentLoader: 	... 17 more
,08-31 16:54:43.820  3756  3756 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 16:54:43.894  3015  3739 V KeepSync: Connecting to GoogleApiClient
,08-31 16:54:43.895   872  1727 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 16:54:43.908  1526  3769 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-31 16:54:43.910  1526  3769 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 16:54:43.922  2864  3754 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-31 16:54:43.944  1526  3769 W Uploader:  no longer exists, so no auth token.
,08-31 16:54:43.955   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 25797, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-31 16:54:43.976   872   884 I ActivityManager: Start proc 3775:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-31 16:54:44.008  1526  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-31 16:54:44.008  1526  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 16:54:44.008  1526  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:44.008  1526  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:44.015  3775  3775 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-31 16:54:44.020  1731  3773 V BaseAuthAsyncOperation: access token request failed
,08-31 16:54:44.022  3015  3739 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 16:54:44.119  3756  3756 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 16:54:44.119  3756  3756 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 16:54:44.119  3756  3756 I GAv4    :   adb logcat -s GAv4
,08-31 16:54:44.126  3490  3537 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:54:44.126  3490  3537 I jxcore-log: 
,08-31 16:54:44.131  3756  3756 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:54:44.136  3756  3756 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:54:44.153  3490  3537 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:54:44.153  3490  3537 I jxcore-log: 
,08-31 16:54:44.166  3756  3793 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 16:54:44.209  3775  3775 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-31 16:54:44.216  3775  3775 I BooksApp: Created application version: 3.6.9 (30609)
,08-31 16:54:44.314  3775  3801 I BooksSync: Starting books sync for 61035162, extras: ade
,08-31 16:54:44.345  3756  3756 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 16:54:44.386  3756  3756 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 16:54:44.395  3756  3756 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2314-2316)
,08-31 16:54:44.395  3756  3756 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 16:54:44.496  3756  3756 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6bae02a}
,08-31 16:54:44.496  3756  3756 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:54:44.497  3756  3756 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:54:44.544  3756  3756 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 16:54:44.546  3756  3756 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 16:54:44.588  3756  3756 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 16:54:44.600  3756  3756 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 16:54:44.600  3756  3756 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 16:54:44.600  3756  3756 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 16:54:44.600  3756  3756 I Adreno  : Build Date                       : 10/20/15
08-31 16:54:44.600  3756  3756 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 16:54:44.600  3756  3756 I Adreno  : Local Branch                     : M14
08-31 16:54:44.600  3756  3756 I Adreno  : Remote Branch                    : 
08-31 16:54:44.600  3756  3756 I Adreno  : Remote Branch                    : 
08-31 16:54:44.600  3756  3756 I Adreno  : Reconstruct Branch               : 
,08-31 16:54:44.668  1526  3729 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-31 16:54:44.681  1526  3729 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-31 16:54:44.681  1526  3729 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:44.681  1526  3729 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:44.704  3015  3739 E KeepSync: IOException
08-31 16:54:44.704  3015  3739 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 16:54:44.704  3015  3739 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 16:54:44.704  3015  3739 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 16:54:44.704  3015  3739 E KeepSync: 	... 10 more
08-31 16:54:44.705  3015  3739 W KeepSync: Sync result 2
,08-31 16:54:44.723  3756  3756 I NSApplication: Starting up...
,08-31 16:54:44.747   872  1401 I ActivityManager: Start proc 3836:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 16:54:44.748   872  1401 I ActivityManager: Killing 2620:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 16:54:44.766  3756  3831 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 16:54:44.806  3775  3850 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-31 16:54:44.848  3836  3836 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 16:54:44.852  1526  2070 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 16:54:44.853  1526  2070 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 16:54:44.853  1526  2070 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-31 16:54:44.853  1526  2070 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:44.886  1526  2038 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 16:54:44.886  1526  2038 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 16:54:44.886  1526  2038 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 16:54:44.887  1526  2038 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:44.902  3775  3850 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 16:54:44.903  3775  3801 E BooksSync: Soft error
08-31 16:54:44.903  3775  3801 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 16:54:44.903  3775  3801 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 16:54:44.903  3775  3801 E BooksSync: Sync error
08-31 16:54:44.903  3775  3801 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 16:54:44.903  3775  3801 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 16:54:44.903  3775  3801 I BooksSync: Finished books sync
,08-31 16:54:45.005   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 25810, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 16:54:45.007   872   882 I ActivityManager: Killing 2961:android.process.acore/u0a5 (adj 15): empty #17
,08-31 16:54:45.136   872  1728 I ActivityManager: Killing 3340:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 16:54:45.137   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 25811, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 16:54:45.228  1526  3769 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-31 16:54:45.228  1526  3769 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-31 16:54:45.228  1526  3769 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:45.228  1526  3769 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:45.241  1526  3769 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 16:54:45.241  1526  3769 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-31 16:54:45.241  1526  3769 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-31 16:54:45.412   872  2825 I ActivityManager: Killing 3355:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 16:54:45.698  3490  3537 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:54:45.698  3490  3537 I jxcore-log: 
,08-31 16:54:45.729  1526  3769 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-31 16:54:45.730  1526  3769 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-31 16:54:45.730  1526  3769 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:45.730  1526  3769 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:45.770  1526  3769 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 16:54:45.770  1526  3769 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-31 16:54:45.770  1526  3769 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-31 16:54:45.946  3490  3537 I jxcore-log: ERROR runTests: 
08-31 16:54:45.946  3490  3537 I jxcore-log: 
,08-31 16:54:45.947  1526  3769 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-31 16:54:45.947  1526  3769 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-31 16:54:45.947  1526  3769 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 16:54:45.947  1526  3769 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 16:54:45.949  3490  3537 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:54:45.949  3490  3537 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:54:45.950  3490  3537 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:54:45.950  3490  3537 I jxcore-log: 
,08-31 16:54:45.960  3490  3537 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _functionName: 'loadFile',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _lineNumber: '26',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _columnNumber: '11',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:54:45.960  3490  3537 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _functionName: '',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _lineNumber: '38',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _columnNumber: '7',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:54:45.960  3490  3537 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _functionName: '',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _lineNumber: '35',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _columnNumber: '3',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:54:45.960  3490  3537 I jxcore-log:   { _fileName: 'module.js',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _lineNumber: '621',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _columnNumber: '8',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:54:45.960  3490  3537 I jxcore-log:   { _fileName: 'module.js',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _lineNumber: '651',
08-31 16:54:45.960  3490  3537 I jxcore-log:     _columnNumber: '1',
08-31 16:54:45.960  3490  3537 I jxcore-log:    
,08-31 16:54:45.960  3490  3537 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:54:45.960  3490  3537 I jxcore-log: 
,08-31 16:54:45.960  3490  3537 E jxcore-log: Error: 
08-31 16:54:45.960  3490  3537 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:54:45.960  3490  3537 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:54:45.960  3490  3537 E jxcore-log: 
08-31 16:54:45.963  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:54:45.963  3490  3537 I jxcore-log: 
08-31 16:54:45.965  1526  3769 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-31 16:54:45.965  1526  3769 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-31 16:54:45.965  1526  3769 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-31 16:54:45.965  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:54:45.965  3490  3537 I jxcore-log: 
08-31 16:54:45.967  3490  3537 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:54:45.967  3490  3537 I jxcore-log: 
,08-31 16:54:46.577  3865  3865 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 16:54:46.581  3865  3865 D AndroidRuntime: CheckJNI is OFF
,08-31 16:54:46.624  3865  3865 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 16:54:46.671  3865  3865 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 16:54:46.694  3865  3865 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:54:46.706   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 16:54:46.707   872   885 I ActivityManager: Killing 3490:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 16:54:46.809   872   895 W PackageSettings: Skipping PackageSetting{b348e7 com.example.hello/10273} due to missing metadata
,08-31 16:54:46.819   872  1315 D WifiService: Client connection lost with reason: 4
08-31 16:54:46.820   872  1401 D GraphicsStats: Buffer count: 2
08-31 16:54:46.820   872   882 I WindowState: WIN DEATH: Window{ee994db u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-31 16:54:46.858   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 16:54:46.858   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 16:54:46.859   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-31 16:54:46.859   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 16:54:46.859   872   885 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 16:54:46.859   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:46.859   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:46.859   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:54:46.859   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 16:54:46.859   872   885 I ActivityManager:   Force finishing activity ActivityRecord{c8576c4 u0 com.test.thalitest/.MainActivity t2}
,08-31 16:54:46.860   872   895 I art     : Starting a blocking GC Explicit
,08-31 16:54:46.867   872   883 W ActivityManager: Spurious death for ProcessRecord{4a0b855 0:com.test.thalitest/u0a0}, curProc for 3490: null
,08-31 16:54:46.901   872   895 I art     : Explicit concurrent mark sweep GC freed 29639(2015KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 720us total 39.710ms
,08-31 16:54:46.924   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 16:54:46.926  3865  3865 I art     : System.exit called, status: 0
08-31 16:54:46.926  3865  3865 I AndroidRuntime: VM exiting with result code 0.
,08-31 16:54:46.933   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 16:54:46.942   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-31 16:54:46.949  3540  3540 D BluetoothMapAppObserver: onReceive
,08-31 16:54:46.948  1911  2282 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 16:54:46.971  3540  3540 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-31 16:54:46.955   872  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 16:54:46.973  1887  1887 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 16:54:46.956  3326  3326 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 16:54:46.990  1961  1961 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-31 16:54:47.007   872   882 I ActivityManager: Start proc 3880:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-31 16:54:47.014  1887  3885 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 16:54:47.027  1887  3885 I Decoder : createOrResetDecoder
,08-31 16:54:47.033   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 16:54:47.038  1526  1526 I ConfigService: onCreate
,08-31 16:54:47.052  3880  3880 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 16:54:47.054  1887  3885 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 16:54:47.074   872  1992 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3490 uid 10000
,08-31 16:54:47.075  1887  1887 I Keyboard.Facilitator: onFinishInput()
,08-31 16:54:47.077  1887  3885 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 16:54:47.078  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 16:54:47.078  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 16:54:47.081  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 16:54:47.081  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-31 16:54:47.089  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 16:54:47.089  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 16:54:47.090  1887  3885 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 16:54:47.090  1887  3885 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 16:54:47.090  1887  3885 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-31 16:54:47.092  1887  3885 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 16:54:47.092  1887  3885 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-31 16:54:47.093  1887  3885 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 16:54:47.115  3880  3880 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 16:54:47.135   872  2824 I ActivityManager: Start proc 3900:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 16:54:47.138  3880  3904 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 16:54:47.164  3900  3900 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 16:54:47.176  1526  1526 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-31 16:54:47.177  1526  1526 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-31 16:54:47.178  1526  1526 E AndroidRuntime: FATAL EXCEPTION: main
08-31 16:54:47.178  1526  1526 E AndroidRuntime: Process: com.google.process.gapps, PID: 1526
08-31 16:54:47.178  1526  1526 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 16:54:47.178  1526  1526 E AndroidRuntime: 	... 8 more
,08-31 16:54:47.183  1526  1526 I Process : Sending signal. PID: 1526 SIG: 9
,08-31 16:54:47.184   872  3916 E DropBoxManagerService: Can't write: system_app_crash
08-31 16:54:47.184   872  3916 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.184   872  3916 E DropBoxManagerService: 	... 5 more
,08-31 16:54:47.190   872   883 I ActivityManager: Killing 2196:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-31 16:54:47.209  3880  3896 W FileUtils: Failed to chmod(/data/user/0/com.android.providers.contacts/databases/contacts2.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-31 16:54:47.220  3880  3904 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-31 16:54:47.221  3880  3904 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 16:54:47.221  3880  3904 E AndroidRuntime: Process: android.process.acore, PID: 3880
08-31 16:54:47.221  3880  3904 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.221  3880  3904 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 16:54:47.228  3880  3896 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,08-31 16:54:47.232   872  1315 D WifiService: Client connection lost with reason: 4
,08-31 16:54:47.235   872  1382 I ActivityManager: Process com.google.process.gapps (pid 1526) has died
,08-31 16:54:47.236  1731  1731 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-31 16:54:47.236   872  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-31 16:54:47.237   872  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-31 16:54:47.237   872  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-31 16:54:47.237   872  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
08-31 16:54:47.237   872  1382 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 40999ms
,08-31 16:54:47.240  3261  3261 E GcoreClearcutLogger: ClearcutLogger connection suspended: 1
,08-31 16:54:47.241   872  3917 E DropBoxManagerService: Can't write: system_app_crash
08-31 16:54:47.241   872  3917 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.241   872  3917 E DropBoxManagerService: 	... 5 more
08-31 16:54:47.246  3880  3904 I Process : Sending signal. PID: 3880 SIG: 9
,08-31 16:54:47.259   872   883 I ActivityManager: Start proc 3920:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-31 16:54:47.261  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-31 16:54:47.261  1731  1731 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 16:54:47.265  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 16:54:47.265  1731  1731 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 16:54:47.273  1731  3930 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 16:54:47.282  1731  3930 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-31 16:54:47.282  1731  3930 E AndroidRuntime: Process: com.google.android.gms, PID: 1731
08-31 16:54:47.282  1731  3930 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:47.282  1731  3930 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-31 16:54:47.284  1731  3930 I Process : Sending signal. PID: 1731 SIG: 9
,08-31 16:54:47.286   278   278 E lowmemorykiller: Error writing /proc/3880/oom_score_adj; errno=22
08-31 16:54:47.286   872  3935 E DropBoxManagerService: Can't write: system_app_crash
08-31 16:54:47.286   872  3935 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.286   872  3935 E DropBoxManagerService: 	... 5 more
08-31 16:54:47.287   278   278 E lowmemorykiller: Error writing /proc/3880/oom_score_adj; errno=22
,08-31 16:54:47.299  3920  3920 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-31 16:54:47.299  2023  3933 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-31 16:54:47.301   872  2820 I ActivityManager: Start proc 3937:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-31 16:54:47.308  1978  2489 E ReflectionEngine: Failed to save models
08-31 16:54:47.308  1978  2489 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.308  1978  2489 E ReflectionEngine: 	... 16 more
,08-31 16:54:47.321  3920  3920 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 16:54:47.321  3920  3920 I MultiDex: install
08-31 16:54:47.321  3920  3920 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:54:47.325  3920  3920 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-31 16:54:47.326  1978  2489 E ObservedEventLogger: Failed to write the stream file
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.326  1978  2489 E ObservedEventLogger: 	... 16 more
,08-31 16:54:47.327  1978  2489 E ObservedEventLogger: Failed to write the stream file
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.327  1978  2489 E ObservedEventLogger: 	... 16 more
,08-31 16:54:47.330  3920  3920 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:47.332  3920  3920 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:47.332  3920  3920 D AndroidRuntime: Shutting down VM
08-31 16:54:47.333  3920  3920 E AndroidRuntime: FATAL EXCEPTION: main
08-31 16:54:47.333  3920  3920 E AndroidRuntime: Process: com.google.process.gapps, PID: 3920
08-31 16:54:47.333  3920  3920 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 16:54:47.333  3920  3920 E AndroidRuntime: 	... 10 more
08-31 16:54:47.335   872  1966 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-31 16:54:47.335   872  1966 I ActivityManager: Killing 3920:com.google.process.gapps/u0a11 (adj 0): crash
08-31 16:54:47.336   872  3949 E DropBoxManagerService: Can't write: system_app_crash
08-31 16:54:47.336   872  3949 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.336   872  3949 E DropBoxManagerService: 	... 5 more
08-31 16:54:47.340   872  1382 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5a5148a)
08-31 16:54:47.341   872  1316 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:47.341   872  1316 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:54:47.348  3937  3937 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-31 16:54:47.354  2023  3933 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 16:54:47.357  3937  3937 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-31 16:54:47.373   872  1966 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.auth.GetToken} to connection android.os.BinderProxy@7699e2a (in com.google.android.gms)
08-31 16:54:47.373   872  1966 W ActivityManager: android.os.DeadObjectException
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:47.373   872  1966 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@911d592 (in com.google.android.gms)
08-31 16:54:47.373   872  1966 W ActivityManager: android.os.DeadObjectException
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-31 16:54:47.373   872  1966 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:47.374   872  1966 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@911d592 (in com.google.android.gms)
08-31 16:54:47.374   872  1966 W ActivityManager: android.os.DeadObjectException
08-31 16:54:47.374   872  1966 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-31 16:54:47.374   872  1966 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:47.375   872  1966 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService} to connection android.os.BinderProxy@1d772ee (in com.google.android.gms)
08-31 16:54:47.375   872  1966 W ActivityManager: android.os.DeadObjectException
08-31 16:54:47.375   872  1966 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-31 16:54:47.375   872  1966 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 16:54:47.375   872  1730 I ActivityManager: Process com.google.android.gms (pid 1731) has died
08-31 16:54:47.375   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-31 16:54:47.376   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.ApiService in 1000ms
08-31 16:54:47.376   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.signin.service.SignInBrokerService in 11000ms
08-31 16:54:47.376   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.usagereporting.service.UsageReportingService in 20999ms
08-31 16:54:47.376   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 30999ms
08-31 16:54:47.376   872  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.people.service.PeopleService in 40999ms
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.389  3937  3951 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-31 16:54:47.390  3937  3951 E AndroidRuntime: Process: com.android.keychain, PID: 3937
08-31 16:54:47.390  3937  3951 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.390  3937  3951 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 16:54:47.399   872  1990 I ActivityManager: Start proc 3953:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-31 16:54:47.400   872  1727 W ActivityManager: Spurious death for ProcessRecord{6408718 0:com.google.process.gapps/u0a11}, curProc for 3920: null
08-31 16:54:47.402   872  2820 I ActivityManager: Process android.process.acore (pid 3880) has died
08-31 16:54:47.402   872  2820 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 50973ms
08-31 16:54:47.405   872  3963 E DropBoxManagerService: Can't write: system_app_crash
08-31 16:54:47.405   872  3963 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.405   872  3963 E DropBoxManagerService: 	... 5 more
08-31 16:54:47.406  2023  3933 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-31 16:54:47.407  2023  3933 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-31 16:54:47.407  2023  3933 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2023
08-31 16:54:47.407  2023  3933 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 16:54:47.407  2023  3933 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 16:54:47.410  2023  3933 I Process : Sending signal. PID: 2023 SIG: 9
08-31 16:54:47.410   872  3965 E DropBoxManagerService: Can't write: system_app_crash
08-31 16:54:47.410   872  3965 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 16:54:47.410   872  3965 E DropBoxManagerService: 	... 5 more
08-31 16:54:47.426  3937  3951 I Process : Sending signal. PID: 3937 SIG: 9
,08-31 16:54:47.472   872   872 I ActivityManager: Start proc 3969:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-31 16:54:47.491   278   278 E lowmemorykiller: Error writing /proc/2023/oom_score_adj; errno=22
,08-31 16:54:47.493   872  1968 I ActivityManager: Process com.android.keychain (pid 3937) has died
,08-31 16:54:47.493   872  1968 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 50882ms
08-31 16:54:47.494   278   278 E lowmemorykiller: Error writing /proc/2023/oom_score_adj; errno=22
,08-31 16:54:47.510  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-31 16:54:47.522   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
