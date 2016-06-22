#### Test 721454317367600_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main,
06-22 07:48:31.337  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:48:31.347  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:48:31.353  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-22 07:48:31.408  1506  1953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-22 07:48:31.409  1506  1953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-22 07:48:31.409  1506  1953 I GLSUser : [GLSUser] Extracting token using key: Auth
06-22 07:48:31.409  1506  1953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-22 07:48:31.446  1506  1953 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-22 07:48:31.446  1506  1953 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-22 07:48:31.446  1506  1953 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-22 07:48:31.446  1506  1953 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-22 07:48:31.446  1506  1953 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-22 07:48:31.446  1506  1953 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-22 07:48:31.446  1506  1953 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
06-22 07:48:31.450  2592  2627 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-22 07:48:31.450  2592  2627 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-22 07:48:31.450  2592  2627 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-22 07:48:31.450  2592  2627 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-22 07:48:31.450  2592  2627 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-22 07:48:31.450  2592  2627 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-22 07:48:31.450  2592  2627 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
06-22 07:48:31.966  3337  3337 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-22 07:48:31.971  3337  3337 D AndroidRuntime: CheckJNI is OFF
06-22 07:48:32.006  3337  3337 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-22 07:48:32.050  3337  3337 I Radio-JNI: register_android_hardware_Radio DONE
06-22 07:48:32.069  3337  3337 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-22 07:48:32.074   873  1700 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-22 07:48:32.156   873  1700 I ActivityManager: Start proc 3347:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-22 07:48:32.163  3337  3337 D AndroidRuntime: Shutting down VM
06-22 07:48:32.248  3347  3347 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-22 07:48:32.280  3347  3347 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-22 07:48:32.314  3347  3347 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 2431-2460)
06-22 07:48:32.314  3347  3347 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:48:32.348  3347  3347 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f76ecbb}
06-22 07:48:32.348  3347  3347 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:48:32.348  3347  3347 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:48:32.354  3347  3347 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-22 07:48:32.355  3347  3347 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-22 07:48:32.418  3347  3362 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,06-22 07:48:32.431  3347  3347 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-22 07:48:32.446  3347  3347 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-22 07:48:32.446  3347  3347 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-22 07:48:32.446  3347  3347 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-22 07:48:32.446  3347  3347 I Adreno  : Build Date                       : 10/20/15
06-22 07:48:32.446  3347  3347 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-22 07:48:32.446  3347  3347 I Adreno  : Local Branch                     : M14
06-22 07:48:32.446  3347  3347 I Adreno  : Remote Branch                    : 
06-22 07:48:32.446  3347  3347 I Adreno  : Remote Branch                    : 
06-22 07:48:32.446  3347  3347 I Adreno  : Reconstruct Branch               : 
,06-22 07:48:32.514   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f30ba15:true
,06-22 07:48:32.587  3347  3347 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-22 07:48:32.605  3347  3347 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,06-22 07:48:32.676  3347  3384 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-22 07:48:32.693  3347  3371 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-22 07:48:32.731  3347  3384 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:48:32.771  1664  1664 I Keyboard.Facilitator: onFinishInput()
,06-22 07:48:32.828   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +632ms (total +707ms)
,06-22 07:48:32.950  3347  3347 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3347
,06-22 07:48:33.134  3347  3347 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-22 07:48:33.323  3347  3386 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1665992400
,06-22 07:48:33.332  3347  3386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:48:33.332  3347  3386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:48:33.332  3347  3386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:48:33.332  3347  3386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:48:33.332  3347  3386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:48:33.332  3347  3386 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@196a2ae added. We now have 1 listener(s)
,06-22 07:48:33.334  3347  3386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
06-22 07:48:33.336  3347  3386 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,06-22 07:48:33.337  3347  3386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-22 07:48:33.337  3347  3386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:48:33.341  3347  3386 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f2f4e5 added. We now have 1 listener(s)
06-22 07:48:33.341  3347  3386 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-22 07:48:33.351   873  1315 D WifiService: New client listening to asynchronous messages
,06-22 07:48:33.351  3347  3386 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:48:33.352  3347  3386 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-22 07:48:33.353  3347  3386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:48:33.353  3347  3386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-22 07:48:33.354  3347  3386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:48:33.354  3347  3386 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-22 07:48:33.357  3347  3386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-22 07:48:33.357  3347  3386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,06-22 07:48:33.360  3347  3386 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:48:33.361  3347  3386 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-22 07:48:33.361  3347  3386 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:48:33.361  3347  3386 D io.jxcore.node.ConnectivityMonitor: start: OK
06-22 07:48:33.363  3347  3386 I io.jxcore.node.LifeCycleMonitor: start: OK
06-22 07:48:33.364  3347  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-22 07:48:33.403  3347  3347 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:48:34.813  3347  3393 W jxcore-log: Initializing JXcore engine
06-22 07:48:34.813  3347  3393 W jxcore-log: JXcore engine is ready
,06-22 07:48:34.865  3393  3393 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,06-22 07:48:34.865  3393  3393 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10983]" dev="sockfs" ino=10983 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,06-22 07:48:34.868  3393  3393 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-22 07:48:34.868  3393  3393 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24418]" dev="sockfs" ino=24418 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-22 07:48:34.883  3347  3393 W jxcore-log: Starting JXcore engine
,06-22 07:48:34.966  3347  3393 W jxcore-log: Platform android
06-22 07:48:34.966  3347  3393 W jxcore-log: 
,06-22 07:48:34.966  3347  3393 W jxcore-log: Process ARCH arm
06-22 07:48:34.966  3347  3393 W jxcore-log: 
,06-22 07:48:35.170  3347  3393 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:48:35.170  3347  3393 I jxcore-log: 
,06-22 07:48:35.171  3347  3393 W jxcore-log: JXcore engine is started,
,06-22 07:48:35.181  3347  3386 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:48:35.189   873  1748 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-22 07:48:35.217   873  1748 I ActivityManager: Start proc 3396:com.android.packageinstaller/u0a69 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-22 07:48:35.228  3347  3386 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
,06-22 07:48:35.278  3396  3396 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-22 07:48:35.394  3396  3408 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-22 07:48:35.462  3396  3408 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-22 07:48:35.462  3396  3408 I Adreno  : Build Date                       : 10/20/15
06-22 07:48:35.462  3396  3408 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-22 07:48:35.462  3396  3408 I Adreno  : Local Branch                     : M14
06-22 07:48:35.462  3396  3408 I Adreno  : Remote Branch                    : 
06-22 07:48:35.462  3396  3408 I Adreno  : Remote Branch                    : 
06-22 07:48:35.462  3396  3408 I Adreno  : Reconstruct Branch               : 
,06-22 07:48:35.468  3396  3408 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:48:35.506  1664  1664 I Keyboard.Facilitator: onFinishInput()
,06-22 07:48:35.696   873   891 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +436ms (total +502ms)
,TIME-OUT KILL (timeout was 1400000ms)
```
