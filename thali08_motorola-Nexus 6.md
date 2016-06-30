#### Test 72145431fdae11f_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
06-30 10:39:39.800  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:39:39.809  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:39:39.812  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 10:39:39.849  1520  1943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 10:39:39.849  1520  1943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:39:39.849  1520  1943 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:39:39.849  1520  1943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
06-30 10:39:39.886  1520  1943 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:39:39.886  1520  1943 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:39:39.886  1520  1943 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:39:39.886  1520  1943 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:39:39.886  1520  1943 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:39:39.886  1520  1943 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:39:39.886  1520  1943 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
06-30 10:39:39.899  2592  2625 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:39:39.899  2592  2625 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:39:39.899  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:39:39.899  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:39:39.899  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:39:39.899  2592  2625 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:39:39.899  2592  2625 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
06-30 10:39:40.427  3326  3326 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:39:40.432  3326  3326 D AndroidRuntime: CheckJNI is OFF
06-30 10:39:40.467  3326  3326 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:39:40.509  3326  3326 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:39:40.529  3326  3326 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 10:39:40.532   874  1945 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:39:40.600   874  1945 I ActivityManager: Start proc 3336:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 10:39:40.604  3326  3326 D AndroidRuntime: Shutting down VM
06-30 10:39:40.687  3336  3336 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-30 10:39:40.720  3336  3336 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 10:39:40.798  3336  3336 I LibraryLoader: Time to load native libraries: 71 ms (timestamps 2023-2094)
06-30 10:39:40.799  3336  3336 I LibraryLoader: Expected native library version number "",actual native library version number ""
,06-30 10:39:40.836  3336  3336 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d7c554}
,06-30 10:39:40.836  3336  3336 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 10:39:40.837  3336  3336 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 10:39:40.846  3336  3336 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 10:39:40.847  3336  3336 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 10:39:40.914  3336  3352 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,06-30 10:39:40.921  3336  3336 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,06-30 10:39:40.931  3336  3336 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,06-30 10:39:40.931  3336  3336 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:39:40.931  3336  3336 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 10:39:40.931  3336  3336 I Adreno  : Build Date                       : 10/20/15
06-30 10:39:40.931  3336  3336 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 10:39:40.931  3336  3336 I Adreno  : Local Branch                     : M14
06-30 10:39:40.931  3336  3336 I Adreno  : Remote Branch                    : 
06-30 10:39:40.931  3336  3336 I Adreno  : Remote Branch                    : 
06-30 10:39:40.931  3336  3336 I Adreno  : Reconstruct Branch               : 
,06-30 10:39:41.002   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5b0ee72:true
,06-30 10:39:41.067  3336  3336 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-30 10:39:41.083  3336  3336 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,06-30 10:39:41.139   874   887 W ActivityManager: Activity pause timeout for ActivityRecord{91ae52f u0 com.test.thalitest/.MainActivity t78}
,06-30 10:39:41.149  3336  3374 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:39:41.164  3336  3361 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,06-30 10:39:41.197  3336  3374 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:39:41.218  1670  1670 I Keyboard.Facilitator: onFinishInput()
,06-30 10:39:41.303   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +664ms (total +747ms)
,06-30 10:39:41.338  3336  3336 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3336
,06-30 10:39:41.484  3336  3336 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-30 10:39:41.784  3336  3375 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1665140432
,06-30 10:39:41.813  3336  3375 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:39:41.813  3336  3375 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:39:41.813  3336  3375 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:39:41.813  3336  3375 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:39:41.813  3336  3375 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 10:39:41.814  3336  3375 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1707b added. We now have 1 listener(s)
,06-30 10:39:41.828  3336  3375 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,06-30 10:39:41.838  3336  3375 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,06-30 10:39:41.840  3336  3375 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 10:39:41.841  3336  3375 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,06-30 10:39:41.854  3336  3375 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6202d6 added. We now have 1 listener(s)
06-30 10:39:41.855  3336  3375 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 10:39:41.861  3336  3375 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:39:41.861   874  1321 D WifiService: New client listening to asynchronous messages
06-30 10:39:41.862  3336  3375 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 10:39:41.863  3336  3375 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:39:41.863  3336  3375 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:39:41.864  3336  3375 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:39:41.864  3336  3375 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 10:39:41.866  3336  3375 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 10:39:41.868  3336  3375 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,06-30 10:39:41.871  3336  3375 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:39:41.871  3336  3375 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:39:41.872  3336  3375 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:39:41.872  3336  3375 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:39:41.873  3336  3336 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 10:39:41.873  3336  3375 I io.jxcore.node.LifeCycleMonitor: start: OK,
,06-30 10:39:41.905  3336  3336 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 10:39:42.455  3336  3345 I art     : Background sticky concurrent mark sweep GC freed 76886(7MB) AllocSpace objects, 16(1564KB) LOS objects, 27% free, 23MB/32MB, paused 865us total 166.505ms
,06-30 10:39:42.897  3336  3383 W jxcore-log: Initializing JXcore engine
,06-30 10:39:42.897  3336  3383 W jxcore-log: JXcore engine is ready
,06-30 10:39:42.940  3383  3383 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
06-30 10:39:42.940  3383  3383 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11655]" dev="sockfs" ino=11655 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 10:39:42.940  3383  3383 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:39:42.940  3383  3383 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24411]" dev="sockfs" ino=24411 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,06-30 10:39:42.951  3336  3383 W jxcore-log: Starting JXcore engine
,06-30 10:39:43.031  3336  3383 W jxcore-log: Platform android
06-30 10:39:43.031  3336  3383 W jxcore-log: 
,06-30 10:39:43.031  3336  3383 W jxcore-log: Process ARCH arm
06-30 10:39:43.031  3336  3383 W jxcore-log: 
,06-30 10:39:43.221  3336  3383 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:39:43.221  3336  3383 I jxcore-log: 
,06-30 10:39:43.222  3336  3383 W jxcore-log: JXcore engine is started
,06-30 10:39:43.233  3336  3375 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:39:43.237   874  1697 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-30 10:39:43.294   874  1697 I ActivityManager: Start proc 3385:com.android.packageinstaller/u0a69 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 10:39:43.301  3336  3375 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 67ms. Plugin should use CordovaInterface.getThreadPool().
,06-30 10:39:43.417  3385  3385 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 10:39:43.562  3385  3397 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:39:43.681  3385  3397 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 10:39:43.681  3385  3397 I Adreno  : Build Date                       : 10/20/15
06-30 10:39:43.681  3385  3397 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 10:39:43.681  3385  3397 I Adreno  : Local Branch                     : M14
06-30 10:39:43.681  3385  3397 I Adreno  : Remote Branch                    : 
06-30 10:39:43.681  3385  3397 I Adreno  : Remote Branch                    : 
06-30 10:39:43.681  3385  3397 I Adreno  : Reconstruct Branch               : 
,06-30 10:39:43.698  3385  3397 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:39:43.736  1670  1670 I Keyboard.Facilitator: onFinishInput()
,06-30 10:39:43.806   874   892 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +436ms (total +554ms)
,06-30 10:39:44.076  1520  2005 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:40:43.777  1670  1725 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 10:40:43.777  1670  1725 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 10:40:43.833  1520  1520 I ConfigService: onCreate
,06-30 10:40:48.927  1520  1520 I ConfigService: onDestroy
,06-30 10:44:40.042  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:40.056  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:40.058  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:44:40.127  1520  1944 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:44:40.127  1520  1944 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:44:40.128  1520  1944 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:44:40.128  1520  1944 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:44:40.181  1520  1944 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:44:40.181  1520  1944 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:44:40.181  1520  1944 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:44:40.181  1520  1944 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:44:40.181  1520  1944 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:44:40.181  1520  1944 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:44:40.181  1520  1944 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:44:40.197  2592  2625 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:44:40.197  2592  2625 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:44:40.197  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:44:40.197  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:44:40.197  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:44:40.197  2592  2625 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:44:40.197  2592  2625 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:40.245  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:40.266  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:40.273  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:49:40.361  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:49:40.362  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 10:49:40.362  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:49:40.363  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:49:40.409  1520  1532 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:49:40.409  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:49:40.409  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:49:40.409  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:49:40.409  1520  1532 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:49:40.409  1520  1532 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:49:40.409  1520  1532 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:49:40.419  2592  2625 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:49:40.419  2592  2625 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:49:40.419  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:49:40.419  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:49:40.419  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:49:40.419  2592  2625 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:49:40.419  2592  2625 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:27.250   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:54:40.553  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:40.564  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:40.570  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:54:40.631  1520  1943 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:54:40.632  1520  1943 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:54:40.632  1520  1943 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:54:40.632  1520  1943 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:54:40.675  1520  1943 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:54:40.675  1520  1943 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:54:40.675  1520  1943 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:54:40.675  1520  1943 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:54:40.675  1520  1943 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:54:40.675  1520  1943 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:54:40.675  1520  1943 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:54:40.688  2592  2625 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:54:40.688  2592  2625 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:54:40.688  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:54:40.688  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:54:40.688  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:54:40.688  2592  2625 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:54:40.688  2592  2625 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:59:40.736  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:59:40.757  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:59:40.764  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 10:59:40.851  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 10:59:40.851  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 10:59:40.851  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 10:59:40.852  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 10:59:40.894  1520  1532 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 10:59:40.894  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 10:59:40.894  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 10:59:40.894  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 10:59:40.894  1520  1532 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 10:59:40.894  1520  1532 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 10:59:40.894  1520  1532 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 10:59:40.905  2592  2625 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 10:59:40.905  2592  2625 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 10:59:40.905  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 10:59:40.905  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 10:59:40.905  2592  2625 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 10:59:40.905  2592  2625 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 10:59:40.905  2592  2625 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
