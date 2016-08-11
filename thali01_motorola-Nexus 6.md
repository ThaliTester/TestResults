#### Test 8076137433f931a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-11 17:50:49.333  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:50:49.345  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 17:50:49.350  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 17:50:49.400  1492  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-11 17:50:49.402  1492  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 17:50:49.403  1492  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 17:50:49.403  1492  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 17:50:49.432  1492  2050 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 17:50:49.432  1492  2050 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 17:50:49.432  1492  2050 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 17:50:49.432  1492  2050 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 17:50:49.432  1492  2050 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 17:50:49.432  1492  2050 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 17:50:49.432  1492  2050 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-11 17:50:49.435  3370  3401 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 17:50:49.435  3370  3401 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 17:50:49.435  3370  3401 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 17:50:49.435  3370  3401 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 17:50:49.435  3370  3401 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 17:50:49.435  3370  3401 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 17:50:49.435  3370  3401 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-11 17:50:49.967  3682  3682 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 17:50:49.972  3682  3682 D AndroidRuntime: CheckJNI is OFF
08-11 17:50:50.010  3682  3682 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 17:50:50.052  3682  3682 I Radio-JNI: register_android_hardware_Radio DONE
08-11 17:50:50.071  3682  3682 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 17:50:50.077   873  1752 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 17:50:50.143   873  1752 I ActivityManager: Start proc 3694:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 17:50:50.148  3682  3682 D AndroidRuntime: Shutting down VM
08-11 17:50:50.303  3694  3694 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 17:50:50.331  3694  3694 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 17:50:50.347  3694  3694 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 2874-2887)
08-11 17:50:50.347  3694  3694 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 17:50:50.394  3694  3694 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5f4ba5b}
,08-11 17:50:50.395  3694  3694 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 17:50:50.395  3694  3694 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 17:50:50.404  3694  3694 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 17:50:50.406  3694  3694 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 17:50:50.436  3694  3694 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 17:50:50.460  3694  3694 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 17:50:50.460  3694  3694 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 17:50:50.460  3694  3694 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 17:50:50.460  3694  3694 I Adreno  : Build Date                       : 10/20/15
08-11 17:50:50.460  3694  3694 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 17:50:50.460  3694  3694 I Adreno  : Local Branch                     : M14
08-11 17:50:50.460  3694  3694 I Adreno  : Remote Branch                    : 
08-11 17:50:50.460  3694  3694 I Adreno  : Remote Branch                    : 
08-11 17:50:50.460  3694  3694 I Adreno  : Reconstruct Branch               : 
,08-11 17:50:50.559   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad26414:true
,08-11 17:50:50.641  3694  3694 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 17:50:50.659  3694  3694 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 17:50:50.742   873   886 W ActivityManager: Activity pause timeout for ActivityRecord{cf50249 u0 com.test.thalitest/.MainActivity t2}
,08-11 17:50:50.774  3694  3732 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 17:50:50.792  3694  3718 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 17:50:50.846  3694  3732 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 17:50:50.910   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +669ms (total +799ms)
,08-11 17:50:50.913  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-11 17:50:50.979  3694  3694 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3694
,08-11 17:50:51.061  3694  3694 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 17:50:51.276  3694  3734 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1696728784
,08-11 17:50:51.286  3694  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 17:50:51.286  3694  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 17:50:51.286  3694  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 17:50:51.286  3694  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 17:50:51.286  3694  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 17:50:51.286  3694  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@943c8ce added. We now have 1 listener(s)
,08-11 17:50:51.289  3694  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 17:50:51.290  3694  3734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 17:50:51.290  3694  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 17:50:51.291  3694  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-11 17:50:51.294  3694  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fe6985 added. We now have 1 listener(s)
,08-11 17:50:51.294  3694  3734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:50:51.301   873  1309 D WifiService: New client listening to asynchronous messages
,08-11 17:50:51.304  3694  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:50:51.305  3694  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 17:50:51.305  3694  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 17:50:51.306  3694  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 17:50:51.306  3694  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 17:50:51.314  3694  3734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:50:51.314  3694  3734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 17:50:51.322  3694  3734 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:50:51.322  3694  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:50:51.322  3694  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-11 17:50:51.322  3694  3734 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:50:51.323  3694  3734 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 17:50:51.328  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:50:51.334  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:50:51.366  3694  3694 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 17:50:53.331  3694  3740 W jxcore-log: Initializing JXcore engine
,08-11 17:50:53.331  3694  3740 W jxcore-log: JXcore engine is ready
,08-11 17:50:53.365  3740  3740 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-11 17:50:53.365  3740  3740 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10836]" dev="sockfs" ino=10836 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 17:50:53.365  3740  3740 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 17:50:53.365  3740  3740 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27669]" dev="sockfs" ino=27669 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 17:50:53.377  3694  3740 W jxcore-log: Starting JXcore engine
,08-11 17:50:53.455  3694  3740 W jxcore-log: Platform android
08-11 17:50:53.455  3694  3740 W jxcore-log: 
08-11 17:50:53.455  3694  3740 W jxcore-log: Process ARCH arm
08-11 17:50:53.455  3694  3740 W jxcore-log: 
,08-11 17:50:53.665  3694  3740 I jxcore-log: JXcore Cordova bridge is ready!
08-11 17:50:53.665  3694  3740 I jxcore-log: 
08-11 17:50:53.666  3694  3740 W jxcore-log: JXcore engine is started
,08-11 17:50:53.676  3694  3734 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 17:50:53.682  3694  3694 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 17:51:09.060  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 17:51:09.060  3694  3740 I jxcore-log: 
,08-11 17:51:09.062  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 17:51:09.062  3694  3740 I jxcore-log: 
,08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:09.082  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:09.089  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:09.095  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 17:51:09.095  3694  3740 I jxcore-log: 
,08-11 17:51:09.103  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 17:51:09.103  3694  3740 I jxcore-log: 
,08-11 17:51:09.464  3694  3740 I jxcore-log: Running unit tests
08-11 17:51:09.464  3694  3740 I jxcore-log: 
,08-11 17:51:09.464  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:51:09.464  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a39ffbf added. We now have 2 listener(s)
08-11 17:51:09.466  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 17:51:09.466  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:51:09.466  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:51:09.466  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:51:09.466  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358468c added. We now have 2 listener(s)
08-11 17:51:09.466  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:51:09.467  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:51:09.470  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:09.481  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:09.485  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:09.485  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:51:09.486  3694  3740 D ExecuteNativeTests: Running unit tests
,08-11 17:51:09.492  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:09.499  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:10.446   873  2100 D NetlinkSocketObserver: NeighborEvent{elapsedMs=362985, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 17:51:14.552  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 17:51:14.553  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a added. We now have 3 listener(s)
,08-11 17:51:14.562  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 17:51:14.562  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:51:14.563  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:51:14.563  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:51:14.564  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb added. We now have 3 listener(s)
,08-11 17:51:14.565  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:51:14.567  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:51:14.574  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:14.583  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:14.586  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:14.587  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 17:51:14.590  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 17:51:14.593  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 17:51:14.593  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 17:51:14.593  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:51:14.594  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:14.596  3694  3740 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-11 17:51:14.597  3694  3740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-11 17:51:14.597  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 17:51:14.597  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
,08-11 17:51:14.597  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 17:51:14.597  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 17:51:14.598  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:14.600  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:14.601  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:14.601  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:14.602  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.602  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:51:14.602  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:51:14.602  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a removed from the list
08-11 17:51:14.602  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:14.602  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb removed from the list
08-11 17:51:14.603  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:14.603  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:14.603  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.604  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.604  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.605  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:14.605  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:14.605  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:14.606  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:14.608  3694  3740 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-11 17:51:14.609  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:14.609  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:14.609  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:14.610  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:14.610  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.611  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.611  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:14.611  3694  3740 I org.thaliproj,ect.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:14.611  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:14.611  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:14.611  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.611  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.611  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.611  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.614  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:14.615  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:14.615  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:14.615  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 17:51:14.636  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 17:51:14.637  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 17:51:14.638  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 17:51:14.638  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:14.638  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:14.638  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:14.639  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:14.639  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.639  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.639  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:14.639  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:14.639  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:14.639  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:14.639  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.639  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.639  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:14.639  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:14.641  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:14.641  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:14.641  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:14.641  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:14.643  3694  3740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 17:51:14.647  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:14.653  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:51:14.657  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:14.658  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:51:14.658  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:51:14.659  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:51:14.659  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:51:14.659  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:51:14.659  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:51:14.661  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:14.664  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:14.665  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 17:51:14.665  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 17:51:14.673  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-11 17:51:14.675  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 17:51:14.676  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-11 17:51:14.680  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-11 17:51:14.683  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-11 17:51:14.683  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 17:51:14.683  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 17:51:14.684  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 17:51:14.687  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:51:14.692  2553  2757 D BtGatt.GattService: registerClient() - UUID=2e35ecde-b0e2-48b8-810a-5c8b4c09bebe
08-11 17:51:14.696  2553  2609 D BtGatt.GattService: onClientRegistered() - UUID=2e35ecde-b0e2-48b8-810a-5c8b4c09bebe, clientIf=5
,08-11 17:51:14.698  3694  3705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 17:51:14.700  2553  2568 D BtGatt.GattService: start scan with filters
,08-11 17:51:14.707  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 17:51:14.708  2553  2613 D BtGatt.ScanManager: handling starting scan
08-11 17:51:14.708  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 17:51:14.708  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 17:51:14.708  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 17:51:14.710  2553  2613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:51:14.712  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 17:51:14.712  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 17:51:14.714  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:51:14.714  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 17:51:14.718  3694  3740 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 17:51:14.724  2553  2609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 17:51:14.724  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:14.725  2553  2613 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 17:51:14.742  2553  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 17:51:14.742  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:14.744  2553  2613 D BtGatt.ScanManager: Starting BLE batch scan
,08-11 17:51:14.744  2553  2613 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 17:51:14.772  2553  2609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 17:51:14.772  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:14.792  2553  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 17:51:14.792  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:15.219  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-11 17:51:15.220  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 17:51:15.220  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 17:51:16.299  2553  2553 D BtGatt.ScanManager: awakened up at time 368839
,08-11 17:51:16.304  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:16.350  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-11 17:51:16.351  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:16.351  2553  2609 D BtGatt.GattService: current time is 368891525947
08-11 17:51:16.353  2553  2609 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -97, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 116, -43, -111, -91, -20, -29, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 17:51:16.357  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 17:51:16.359  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 17:51:16.360  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
08-11 17:51:16.360  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 17:51:16.361  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 17:51:16.361  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-11 17:51:16.362  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 17:51:17.855  2553  2553 D BtGatt.ScanManager: awakened up at time 370395
,08-11 17:51:17.858  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:17.890  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-11 17:51:17.890  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:17.891  2553  2609 D BtGatt.GattService: current time is 370431035445
08-11 17:51:17.891  2553  2609 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-11 17:51:17.892  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 17:51:19.395  2553  2553 D BtGatt.ScanManager: awakened up at time 371935
,08-11 17:51:19.401  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:19.450  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-11 17:51:19.450  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:19.451  2553  2609 D BtGatt.GattService: current time is 371991042585
,08-11 17:51:19.452  2553  2609 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -84, 8, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -93, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -93, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-11 17:51:19.454  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-11 17:51:19.455  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 17:51:19.456  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-11 17:51:19.457  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-11 17:51:19.458  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 17:51:19.459  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 17:51:19.461  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-11 17:51:19.732  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:19.732  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:19.732  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 17:51:19.733  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:51:19.733  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 17:51:19.733  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:51:19.734  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 17:51:19.734  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 17:51:19.734  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 17:51:19.737  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 17:51:19.738  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 17:51:19.740  3694  3740 D BluetoothAdapter: STATE_ON
,08-11 17:51:19.743  2553  2757 D BtGatt.GattService: stopScan() - queue size =1
,08-11 17:51:19.746  2553  2765 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 17:51:19.748  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 17:51:19.748  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 17:51:19.749  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 17:51:19.749  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-11 17:51:19.750  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 17:51:19.755  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 17:51:19.758  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 17:51:19.759  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 17:51:19.760  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 17:51:19.761  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 17:51:19.766  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 17:51:19.766  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:19.766  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:51:19.766  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 17:51:19.767  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:19.767  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:19.767  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:19.767  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:19.767  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:51:19.768  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:19.768  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:51:19.769  2553  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 17:51:19.769  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:19.770  2553  2613 D BtGatt.ScanManager: stopping BLe Batch
,08-11 17:51:19.787  2553  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 17:51:19.787  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:19.787  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:19.805  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 17:51:19.805  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:20.271  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:51:24.771  3694  3740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 17:51:24.780  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:24.798  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:24.807  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:24.808  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:51:24.809  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:51:24.809  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:51:24.809  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 17:51:24.810  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:51:24.810  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 17:51:24.817  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:24.824  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 17:51:24.824  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 17:51:24.826  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:24.838  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:51:24.840  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 17:51:24.840  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 17:51:24.850  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 17:51:24.851  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 17:51:24.852  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 17:51:24.854  3694  3740 D BluetoothAdapter: STATE_ON
,08-11 17:51:24.861  2553  2565 D BtGatt.GattService: registerClient() - UUID=8fa2ce6b-1e98-43f1-acc8-c450c149ffd4
,08-11 17:51:24.862  2553  2609 D BtGatt.GattService: onClientRegistered() - UUID=8fa2ce6b-1e98-43f1-acc8-c450c149ffd4, clientIf=5
,08-11 17:51:24.863  3694  3704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 17:51:24.863  2553  2765 D BtGatt.GattService: start scan with filters
,08-11 17:51:24.869  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 17:51:24.869  2553  2613 D BtGatt.ScanManager: handling starting scan
,08-11 17:51:24.869  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-11 17:51:24.869  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,08-11 17:51:24.869  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 17:51:24.878  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:51:24.878  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 17:51:24.880  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:51:24.883  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-11 17:51:24.885  2553  2609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 17:51:24.885  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:24.886  2553  2613 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 17:51:24.891  3694  3740 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 17:51:24.896  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:24.896  3694  3740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-11 17:51:24.896  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:24.896  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 17:51:24.896  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:24.896  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 17:51:24.897  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:51:24.897  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 17:51:24.897  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 17:51:24.897  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 17:51:24.897  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 17:51:24.897  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-11 17:51:24.899  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:51:24.900  2553  2568 D BtGatt.GattService: stopScan() - queue size =1
,08-11 17:51:24.901  2553  2757 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 17:51:24.902  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:51:24.902  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 17:51:24.902  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-11 17:51:24.902  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 17:51:24.902  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 17:51:24.903  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:51:24.904  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-11 17:51:24.904  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 17:51:24.904  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 17:51:24.904  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:51:24.904  2553  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 17:51:24.905  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:24.905  2553  2613 D BtGatt.ScanManager: Starting BLE batch scan
08-11 17:51:24.905  2553  2613 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-11 17:51:24.905  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:24.905  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:24.905  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:51:24.906  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:24.906  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:24.905  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:51:24.907  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:24.907  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:24.907  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:24.907  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:51:24.907  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:51:24.908  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:24.908  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:24.909  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:24.910  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:24.910  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:24.910  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:24.911  3694  3740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 17:51:24.913  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:24.927  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:24.928  2553  2609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 17:51:24.928  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:24.931  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:24.932  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:51:24.932  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 17:51:24.932  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 17:51:24.932  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:51:24.932  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:51:24.932  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 17:51:24.940  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 17:51:24.940  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 17:51:24.941  2553  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 17:51:24.941  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:24.943  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:24.948  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:51:24.949  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 17:51:24.949  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 17:51:24.951  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:24.953  2553  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 17:51:24.953  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:24.953  2553  2613 D BtGatt.ScanManager: stopping BLe Batch
,08-11 17:51:24.958  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 17:51:24.958  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 17:51:24.959  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 17:51:24.961  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:51:24.961  2553  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 17:51:24.962  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:24.962  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:24.966  2553  2757 D BtGatt.GattService: registerClient() - UUID=657840be-95f3-4517-a81c-ec135b058689
,08-11 17:51:24.966  2553  2609 D BtGatt.GattService: onClientRegistered() - UUID=657840be-95f3-4517-a81c-ec135b058689, clientIf=5
08-11 17:51:24.967  3694  3704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 17:51:24.969  2553  2568 D BtGatt.GattService: start scan with filters
,08-11 17:51:24.970  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 17:51:24.970  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:24.976  2553  2613 D BtGatt.ScanManager: handling starting scan
,08-11 17:51:24.976  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 17:51:24.976  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-11 17:51:24.976  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 17:51:24.977  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 17:51:24.982  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:51:24.982  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 17:51:24.982  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 17:51:24.983  2553  2609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 17:51:24.984  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:24.984  2553  2613 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 17:51:24.985  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 17:51:24.989  3694  3740 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 17:51:24.993  2553  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 17:51:24.993  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:24.993  2553  2613 D BtGatt.ScanManager: Starting BLE batch scan
08-11 17:51:24.993  2553  2613 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 17:51:25.005  2553  2609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 17:51:25.006  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:25.019  2553  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 17:51:25.019  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:25.484  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 17:51:25.485  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:51:25.485  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 17:51:26.526  2553  2553 D BtGatt.ScanManager: awakened up at time 379066
,08-11 17:51:26.528  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:26.582  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-11 17:51:26.583  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:26.583  2553  2609 D BtGatt.GattService: current time is 379123233607
08-11 17:51:26.584  2553  2609 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 85, -113, -37, 31, -33, 8, 0, -128, -98, 29, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0, 35, 97, 126, -92, 22, -56, 1, -128, -94, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 17:51:26.585  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 17:51:26.586  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-11 17:51:26.587  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 17:51:26.589  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 17:51:26.590  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 17:51:26.592  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 17:51:28.089  2553  2553 D BtGatt.ScanManager: awakened up at time 380629
,08-11 17:51:28.092  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:28.150  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-11 17:51:28.151  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:51:28.151  2553  2609 D BtGatt.GattService: current time is 380691401525
,08-11 17:51:28.152  2553  2609 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 85, -113, -37, 31, -33, 8, 0, 4, -86, 6, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 17:51:28.153  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 17:51:28.154  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-11 17:51:28.155  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 17:51:29.657  2553  2553 D BtGatt.ScanManager: awakened up at time 382197
,08-11 17:51:29.661  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:29.692  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-11 17:51:29.692  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:29.693  2553  2609 D BtGatt.GattService: current time is 382232762916
,08-11 17:51:29.693  2553  2609 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -85, 15, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-11 17:51:29.694  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-11 17:51:29.695  2553  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-11 17:51:29.992  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:29.992  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:51:29.993  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 17:51:29.993  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:29.994  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 17:51:29.994  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:51:29.994  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 17:51:29.994  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 17:51:29.995  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 17:51:29.995  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 17:51:29.996  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 17:51:29.999  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:51:30.002  2553  2757 D BtGatt.GattService: stopScan() - queue size =1
08-11 17:51:30.004  2553  2568 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 17:51:30.006  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:51:30.006  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 17:51:30.007  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 17:51:30.007  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-11 17:51:30.008  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 17:51:30.013  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:51:30.013  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 17:51:30.013  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 17:51:30.014  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 17:51:30.015  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 17:51:30.018  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 17:51:30.018  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:51:30.018  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 17:51:30.023  2553  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 17:51:30.023  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:30.024  2553  2613 D BtGatt.ScanManager: stopping BLe Batch
,08-11 17:51:30.041  2553  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 17:51:30.042  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:30.042  2553  2613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:51:30.060  2553  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 17:51:30.060  2553  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:51:30.521  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:51:30.521  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:30.521  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 17:51:34.393   873  2100 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386932, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 17:51:35.021  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:35.022  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.023  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.025  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 17:51:35.025  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.025  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 17:51:35.026  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.026  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.026  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.026  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:51:35.027  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.029  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.029  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:35.034  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.034  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:51:35.034  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.035  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.037  3694  3740 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-11 17:51:35.039  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:35.039  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.040  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.041  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 17:51:35.041  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.041  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.042  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
,08-11 17:51:35.042  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.042  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.043  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:51:35.043  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.043  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.044  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:51:35.044  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.048  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.048  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.048  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:35.049  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:35.052  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 17:51:35.052  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.053  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.053  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:51:35.054  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.054  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.055  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.055  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.055  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.056  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.056  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:51:35.056  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.056  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.058  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.058  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.059  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.059  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.059  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.059  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:35.060  3694  3740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-11 17:51:35.060  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.061  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.061  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.061  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.061  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.061  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.061  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.061  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.061  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.061  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.061  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.062  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.062  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.062  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:35.063  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.063  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.063  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.063  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.064  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-11 17:51:35.064  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.064  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.064  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.064  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.064  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.064  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:35.065  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.065  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.065  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.065  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.065  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.065  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.065  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.065  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.066  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.066  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.066  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.066  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:35.067  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 17:51:35.069  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:51:35.069  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:51:35.069  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 17:51:35.069  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:51:35.069  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:51:35.070  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 17:51:35.070  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:51:35.070  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 17:51:35.070  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.070  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:51:35.070  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.071  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.071  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.071  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.071  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.071  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.071  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.071  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.071  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.071  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:35.071  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.071  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.073  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.074  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.074  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.074  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:35.077  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:51:35.078  3694  3740 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-11 17:51:35.078  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-11 17:51:35.091  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 17:51:35.091  3694  3740 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-11 17:51:35.091  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 17:51:35.091  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 17:51:35.091  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 17:51:35.091  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 17:51:35.091  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 17:51:35.092  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 17:51:35.093  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 17:51:35.094  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 17:51:35.094  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-11 17:51:35.094  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-11 17:51:35.094  3694  3740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-11 17:51:35.094  3694  3740 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-11 17:51:35.095  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:51:35.095  3694  3740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 17:51:35.095  3694  3740 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-11 17:51:35.095  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:51:35.095  3694  3740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 17:51:35.095  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-11 17:51:35.098  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-11 17:51:35.099  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-11 17:51:35.099  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-11 17:51:35.100  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-11 17:51:35.100  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-11 17:51:35.100  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-11 17:51:35.101  3694  3740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 17:51:35.101  3694  3740 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-11 17:51:35.101  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.102  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.102  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.102  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.102  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.102  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.102  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-11 17:51:35.102  3694  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
08-11 17:51:35.103  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.103  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.103  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.103  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.103  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.103  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.103  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.103  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.105  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.105  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.105  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.105  3694  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-11 17:51:35.105  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.105  3694  3743 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:51:35.106  3694  3740 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-11 17:51:35.106  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.107  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.107  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: ,The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.107  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.107  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.107  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.107  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.107  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.107  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.107  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.107  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.107  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.108  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.108  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.109  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.109  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.109  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.109  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.110  3694  3740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-11 17:51:35.112  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.112  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.113  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.113  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.113  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.113  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.113  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
,08-11 17:51:35.113  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.113  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.113  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.113  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.113  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.113  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.113  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.115  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:35.115  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.115  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.116  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.116  3694  3740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-11 17:51:35.117  3694  3740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-11 17:51:35.117  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 17:51:35.117  3694  3740 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-11 17:51:35.117  3694  3740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 17:51:35.117  3694  3740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-11 17:51:35.117  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 17:51:35.117  3694  3740 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55,
08-11 17:51:35.117  3694  3740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 17:51:35.118  3694  3740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 17:51:35.118  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 17:51:35.118  3694  3740 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-11 17:51:35.118  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:35.120  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:35.120  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:35.120  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.121  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:51:35.121  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.121  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.121  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.121  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.121  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.121  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.121  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.121  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.121  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.122  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 17:51:35.122  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:35.122  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.123  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:35.123  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:35.123  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.124  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:35.124  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:35.124  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:35.124  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:35.124  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:35.124  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:35.124  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:40.126  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:40.133  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:40.133  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.134  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:51:40.134  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:40.134  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
,08-11 17:51:40.136  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:40.137  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:40.137  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:51:40.137  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.138  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.138  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:40.138  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:40.139  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:40.139  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:40.139  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:51:40.139  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.140  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:40.140  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-11 17:51:40.140  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:40.144  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 17:51:40.145  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:40.145  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:40.145  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:40.149  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-11 17:51:40.150  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:51:40.154  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-11 17:51:40.157  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 17:51:40.157  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 17:51:40.158  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 17:51:40.158  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:51:40.159  3694  3694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 17:51:40.159  3694  3745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:51:40.159  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.160  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 17:51:40.160  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 17:51:40.160  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 17:51:40.160  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.161  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 17:51:40.161  3694  3694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 17:51:40.161  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:40.161  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.161  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 17:51:40.161  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 17:51:40.162  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 17:51:40.162  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.162  3694  3745 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 17:51:40.162  3694  3745 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 17:51:40.162  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.162  3694  3745 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 17:51:40.168  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:51:40.168  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:40.168  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:40.168  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:51:40.168  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:40.168  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:51:40.168  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:51:40.169  3694  3694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 17:51:40.169  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.169  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:51:40.169  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.169  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.169  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:40.169  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.169  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:40.169  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:40.169  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.170  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.170  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.170  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.171  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:40.171  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:40.171  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.171  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:40.173  3694  3740 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-11 17:51:40.173  3694  3740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 17:51:40.173  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 17:51:40.173  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:51:40.174  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 17:51:40.174  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:51:40.174  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:40.174  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:40.174  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.174  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.174  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.175  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:40.175  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.175  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:40.176  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:40.176  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.176  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.176  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.176  3694  374,0 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.177  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:40.177  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:40.177  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.177  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:40.182  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-11 17:51:40.182  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:40.182  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:40.182  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.183  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.183  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.183  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
,08-11 17:51:40.183  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.183  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:40.183  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:40.183  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.183  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.183  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.183  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:40.186  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:40.186  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:40.186  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.187  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:40.188  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:51:40.189  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:51:40.189  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:51:40.189  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:51:40.189  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.189  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.189  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af4f59a not in the list
08-11 17:51:40.189  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:40.189  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
08-11 17:51:40.189  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:40.189  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.189  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.189  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:40.190  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:40.191  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:51:40.192  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:51:40.192  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:40.192  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3daecb not in the list
,08-11 17:51:40.242  2553  2744 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-11 17:51:40.243  2553  2754 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-11 17:51:40.244  3694  3743 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
,08-11 17:51:40.671  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:51:45.195  3694  3740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-11 17:51:45.196  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-11 17:51:45.197  3694  3740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-11 17:51:45.197  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-11 17:51:45.197  3694  3740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-11 17:51:45.198  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-11 17:51:45.206  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-11 17:51:45.206  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-11 17:51:45.212  3694  3740 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-11 17:51:45.212  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 17:51:45.213  3694  3740 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-11 17:51:45.213  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 17:51:45.213  3694  3740 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-11 17:51:45.213  3694  3740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-11 17:51:45.214  3694  3740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-11 17:51:45.214  3694  3740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-11 17:51:45.215  3694  3740 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-11 17:51:45.215  3694  3740 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-11 17:51:45.215  3694  3740 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-11 17:51:45.215  3694  3740 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-11 17:51:50.219  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:51:50.219  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de3eeb5 added. We now have 3 listener(s)
08-11 17:51:50.220  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:51:50.228  3694  3740 D BluetoothAdapter: enable(): BT is already enabled..!
,08-11 17:51:50.229   873  1401 D WifiService: setWifiEnabled: true pid=3694, uid=10000
,08-11 17:51:50.229   873  1401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 17:51:50.233  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:51:50.233  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c5f94a added. We now have 4 listener(s)
08-11 17:51:50.234  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:51:50.253  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:51:50.254  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c5f94a removed from the list
,08-11 17:51:50.254  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:51:50.255  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:51:50.255  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:51:50.259  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:51:50.259  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7be0bb added. We now have 4 listener(s)
08-11 17:51:50.260  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:51:50.265  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:51:50.265  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7be0bb removed from the list
,08-11 17:51:50.265  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:51:50.266  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:51:50.266  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:51:50.268  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:51:50.269  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad9d9d8 added. We now have 4 listener(s)
,08-11 17:51:50.269  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:51:50.277   873  1696 D WifiService: setWifiEnabled: false pid=3694, uid=10000
,08-11 17:51:50.278   873  1696 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:51:50.294  2553  2605 D BluetoothAdapterState: Current state: ON, message: 23
,08-11 17:51:50.294  2553  2605 D BluetoothAdapterProperties: Setting state to 13
,08-11 17:51:50.295  2553  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-11 17:51:50.296  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:51:50.297  2553  2605 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 17:51:50.299  2553  2605 I BluetoothAdapterState: Entering PendingCommandState
08-11 17:51:50.303  2553  2609 D BluetoothAdapterProperties: Scan Mode:20
,08-11 17:51:50.304  2553  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 17:51:50.311  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:50.312  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:51:50.317  2553  2553 D HeadsetService: Received stop request...Stopping profile...
08-11 17:51:50.320  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:50.321  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:50.323  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:51:50.326  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-11 17:51:50.326  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:50.329   873  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-11 17:51:50.329   873  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 17:51:50.330   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 17:51:50.330   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 17:51:50.330  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:50.333  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:50.333  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:51:50.334  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.334  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:50.337  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:50.338  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:51:50.338  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.338  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:50.341   873  1308 E native  : do suspend true
,08-11 17:51:50.341  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.343  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.345   873   886 I ActivityManager: Start proc 3749:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-11 17:51:50.346  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.349  1367  1392 D BluetoothHeadset: Proxy object disconnected
,08-11 17:51:50.349   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 17:51:50.350  1760  1771 D BluetoothHeadset: Proxy object disconnected
,08-11 17:51:50.350   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 17:51:50.350   873   873 D BluetoothHeadset: Proxy object disconnected
,08-11 17:51:50.352  2553  2553 D BluetoothMapService: onReceive
,08-11 17:51:50.352  2553  2553 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:51:50.353  2553  2553 D BluetoothMapService: STATE_TURNING_OFF
,08-11 17:51:50.354  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-11 17:51:50.354  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:50.354  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.354  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.354  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:51:50.354  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-11 17:51:50.355   873  2101 D DhcpClient: Clearing IP address
08-11 17:51:50.355  2553  2553 D A2dpService: Received stop request...Stopping profile...
08-11 17:51:50.355   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-11 17:51:50.355  2553  2760 D A2dpStateMachine: Exit Disconnected: -1
08-11 17:51:50.357   873   873 D BluetoothA2dp: Proxy object disconnected
08-11 17:51:50.358  1367  1367 D BluetoothA2dp: Proxy object disconnected
,08-11 17:51:50.358   372   872 D CommandListener: Setting iface cfg
08-11 17:51:50.360  2553  2553 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 17:51:50.360  2553  2553 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:51:50.361  2553  2553 D HidService: Received stop request...Stopping profile...
08-11 17:51:50.361  2553  2553 D HidService: Stopping Bluetooth HidService
08-11 17:51:50.361  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-11 17:51:50.361  1367  1367 D HidProfile: Bluetooth service disconnected
08-11 17:51:50.361  2553  2609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-11 17:51:50.361  2553  2744 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 17:51:50.362  2553  2744 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 17:51:50.362  2553  2744 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:51:50.362  2553  2609 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-11 17:51:50.367  2553  2553 D HealthService: Received stop request...Stopping profile...
08-11 17:51:50.367   873  2115 D DhcpClient: Receive thread stopped
08-11 17:51:50.370   873  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-11 17:51:50.370  2553  2553 D PanService: Received stop request...Stopping profile...
,08-11 17:51:50.368  1492  2301 V NativeCrypto: Read error: ssl=0x9b771c00: I/O error during system call, Connection timed out
,08-11 17:51:50.371   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 17:51:50.371   873  1308 E native  : do suspend true
08-11 17:51:50.371   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-11 17:51:50.372   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-11 17:51:50.372  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 17:51:50.372  1367  1367 D PanProfile: Bluetooth service disconnected
,08-11 17:51:50.373  1492  2301 V NativeCrypto: SSL shutdown failed: ssl=0x9b771c00: I/O error during system call, Broken pipe
08-11 17:51:50.374  2553  2553 D BluetoothMapService: Received stop request...Stopping profile...
08-11 17:51:50.374  2553  2553 D BluetoothMapService: stop()
08-11 17:51:50.377   395   395 E Parcel  : Reading a NULL string not supported here.
08-11 17:51:50.377  2553  2553 D BluetoothMapAppObserver: deinitObservers()
08-11 17:51:50.377  2553  2553 D BluetoothMapAppObserver: removeReceiver()
08-11 17:51:50.379  1367  1367 D BluetoothMap: Proxy object disconnected
08-11 17:51:50.379  1367  1367 D MapProfile: Bluetooth service disconnected,
08-11 17:51:50.379  2553  2553 I BtOppRfcommListener: stopping Accept Thread
08-11 17:51:50.379   873  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-11 17:51:50.380  2553  3267 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-11 17:51:50.380  2553  3267 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-11 17:51:50.382  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-11 17:51:50.382  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.382  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.382  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:51:50.383  2553  2609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-11 17:51:50.383  2553  2744 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:51:50.383  2553  2744 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:51:50.383  2553  2744 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:51:50.383  2553  2744 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:51:50.383  2553  2744 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:51:50.383  2553  2744 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-11 17:51:50.384  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-11 17:51:50.384  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.384  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.384  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:51:50.385  2553  2553 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 17:51:50.385  2553  2553 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-11 17:51:50.385  2553  2609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 17:51:50.385  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-11 17:51:50.385  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.385  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.385  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:51:50.385  2553  2553 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-11 17:51:50.386  2553  2609 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 17:51:50.386  2553  2553 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 17:51:50.386  2553  2553 V BluetoothAdapterState: isTurningOff()=true
08-11 17:51:50.386  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.386  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.387  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:51:50.387  2553  2553 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-11 17:51:50.388  2553  2553 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 17:51:50.389  2553  2553 D BluetoothMapService: MAP Service closeService in
08-11 17:51:50.389  2553  2553 D BluetoothMapMasInstance0: MAP Service shutdown
,08-11 17:51:50.389  2553  2553 D ObexServerSockets0: shutdown(block = true)
08-11 17:51:50.389  2553  2766 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-11 17:51:50.391  2553  2553 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 17:51:50.391  2553  2553 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 17:51:50.391  2553  2754 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 17:51:50.391  2553  2767 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 17:51:50.391  2553  2553 V BluetoothAdapterState: isTurningOff()=true
,08-11 17:51:50.392  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.392  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.392  2553  2553 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:51:50.392  2553  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-11 17:51:50.392  2553  2553 D BluetoothMapService: cleanup()
08-11 17:51:50.392  2553  2605 D BluetoothAdapterProperties: Setting state to 15
,08-11 17:51:50.392  2553  2553 D BluetoothMapService: MAP Service closeService in
08-11 17:51:50.392  2553  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 17:51:50.393  2553  2605 I BluetoothAdapterState: Entering BleOnState
08-11 17:51:50.394  1367  1393 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:51:50.394  1367  1392 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:51:50.394  1367  1380 D BluetoothPbap: onBluetoothStateChange: up=false
,08-11 17:51:50.395   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:51:50.395  1367  1393 D BluetoothPan: onBluetoothStateChange on: false
08-11 17:51:50.396  1367  1392 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 17:51:50.396   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:51:50.396   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 17:51:50.396  1760  1939 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:51:50.396   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 17:51:50.396  1367  1380 D BluetoothMap: onBluetoothStateChange: up=false
08-11 17:51:50.397  2553  2605 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-11 17:51:50.397  2553  2605 D BluetoothAdapterProperties: Setting state to 16
08-11 17:51:50.397  2553  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-11 17:51:50.398  2553  2605 D BluetoothAdapterProperties: onBleDisable
,08-11 17:51:50.398  2553  2606 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-11 17:51:50.399  2553  2744 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 17:51:50.399  2553  2744 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:51:50.399  2553  2609 D BluetoothAdapterProperties: Scan Mode:20
08-11 17:51:50.399  2553  2605 I BluetoothAdapterState: Entering PendingCommandState
08-11 17:51:50.401  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:50.401  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:50.404  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:50.404  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:51:50.406  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:50.407  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:50.407  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.407  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:51:50.409  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:50.409  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:50.409  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.409  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:51:50.411  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:50.412  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:51:50.414  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.425  3749  3749 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-11 17:51:50.427   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:51:50.435  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 17:51:50.440  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:51:50.443   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc2ea3c:true
,08-11 17:51:50.446   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-11 17:51:50.446   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-11 17:51:50.447   873  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-11 17:51:50.447   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:51:50.458   873  1700 I ActivityManager: Start proc 3766:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-11 17:51:50.461   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 17:51:50.464   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 17:51:50.468  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.469  3259  3259 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f184dcd and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-11 17:51:50.473  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.475  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:51:50.481  3749  3749 D LocalBluetoothProfileManager: Adding local MAP profile
,08-11 17:51:50.483  3749  3749 D BluetoothMap: Create BluetoothMap proxy object
,08-11 17:51:50.487   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 17:51:50.491  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:50.491  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:50.491  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.492  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:51:50.493   873  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-11 17:51:50.493  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:50.493  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:51:50.494  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.494  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:51:50.495  3749  3749 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-11 17:51:50.496  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:50.496  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:50.496  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:50.497  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:51:50.503  3749  3749 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:51:50.504  1704  2062 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 17:51:50.518  3766  3766 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-11 17:51:50.520   873  1780 I ActivityManager: Killing 2845:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-11 17:51:50.540   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-11 17:51:50.600  2553  2609 I bt_hci  : shut_down
,08-11 17:51:50.601  2553  2615 D bt_hwcfg: hw_epilog_process
,08-11 17:51:50.602  2553  2615 I bt_vendor: low_power_mode_cb
,08-11 17:51:50.629  2553  2615 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 17:51:50.629  2553  2615 I bt_vendor: epilog_cb
,08-11 17:51:50.629  2553  2615 I bt_hci  : epilog_finished_callback
,08-11 17:51:50.636  2553  2609 I bt_hci_h4: hal_close
,08-11 17:51:50.636  2553  2609 I bt_userial_vendor: device fd = 51 close
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.k.d(PG:583)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.718  3766  3766 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.718  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.719  3766  3766 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:51:50.719  3766  3766 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:51:50.753  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 17:51:50.787  3749  3749 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:51:50.788  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:51:50.792   873  1703 I ActivityManager: Killing 2390:com.google.android.talk/u0a61 (adj 15): empty #17
,08-11 17:51:50.837  2553  2606 D bt_stack_manager: event_shut_down_stack finished.
,08-11 17:51:50.838  2553  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 17:51:50.844  2553  2605 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-11 17:51:50.844  2553  2553 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 17:51:50.850  2553  2553 D BtGatt.GattService: Received stop request...Stopping profile...
08-11 17:51:50.850  2553  2553 D BtGatt.GattService: stop()
08-11 17:51:50.850  2553  2553 D BtGatt.AdvertiseManager: advertise clients cleared
,08-11 17:51:50.878   873  1696 I ActivityManager: Start proc 3802:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-11 17:51:50.881  2553  2553 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:51:50.881  2553  2553 V BluetoothAdapterState: isTurningOn()=false
08-11 17:51:50.881  2553  2553 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:51:50.881  2553  2553 V BluetoothAdapterState: isBleTurningOff()=true
,08-11 17:51:50.881  2553  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-11 17:51:50.882  2553  2605 D BluetoothAdapterProperties: Setting state to 10
08-11 17:51:50.882  2553  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-11 17:51:50.883   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-11 17:51:50.883  2553  2605 I BluetoothAdapterState: Entering OffState
,08-11 17:51:50.894  2553  2553 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-11 17:51:50.895  2553  2553 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-11 17:51:50.895  2553  2606 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 17:51:50.895  2553  2553 I BluetoothServiceJni: cleanupNative: return from cleanup
08-11 17:51:50.899  2553  2606 D bt_stack_manager: event_clean_up_stack finished.
,08-11 17:51:50.901  2553  2553 I art     : System.exit called, status: 0
,08-11 17:51:50.902  2553  2553 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 17:51:50.933   873  1401 I ActivityManager: Process com.android.bluetooth (pid 2553) has died
,08-11 17:51:50.950  3802  3802 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-11 17:51:50.953  1662  1794 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-11 17:51:50.953  1662  1794 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 17:51:50.965  1492  1492 I ConfigService: onCreate
,08-11 17:51:51.124  3766  3790 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-11 17:51:51.149  3802  3822 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-11 17:51:51.149  3802  3822 I Babel_SMS: MmsConfig.loadMmsSettings
08-11 17:51:51.150  3802  3822 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-11 17:51:51.150  3802  3822 I Babel_SMS: MmsConfig.loadFromDatabase
,08-11 17:51:51.188  3802  3822 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-11 17:51:51.188  3802  3822 I Babel_SMS: MmsConfig.loadFromResources
08-11 17:51:51.189  3802  3822 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-11 17:51:51.189  3802  3822 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-11 17:51:51.234  3802  3802 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 17:51:51.241  3802  3802 I Babel_Crash: startup - clean
,08-11 17:51:51.322  3802  3802 I Babel_telephony: TeleModule.launchCompleted
,08-11 17:51:51.335   873  1703 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-11 17:51:51.345  3802  3802 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-11 17:51:51.355  3802  3802 W Babel   : BAM#gBA: invalid account id: -1
08-11 17:51:51.355  3802  3802 W Babel   : BAM#gBA: invalid account id: -1
08-11 17:51:51.355  3802  3802 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-11 17:51:51.359   873   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-11 17:51:51.362  3802  3827 I Babel   : deleted: false for 0
,08-11 17:51:51.384  1803  1803 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 17:51:51.387  1803  1803 D SystemUpdateService: onCreate
,08-11 17:51:51.398  1803  1803 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 17:51:51.411  1803  3829 I SystemUpdateService: active receiver: enabled
,08-11 17:51:51.424  1803  1803 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-11 17:51:51.430  1803  2365 I iu.UploadsManager: num queued entries: 0
,08-11 17:51:51.431  1803  2365 I iu.UploadsManager: num updated entries: 0
,08-11 17:51:51.433  1803  2365 I iu.SyncManager: NEXT; no task
,08-11 17:51:51.439  1803  3829 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-11 17:51:51.440  1803  1803 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 17:51:51.444  1803  1803 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 17:51:51.454  1803  3829 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-11 17:51:51.454  1803  3829 I SystemUpdateService: now status is 0 (complete)
,08-11 17:51:51.455  1803  3829 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 17:51:51.455  1803  3829 I SystemUpdateService: file has been verified
08-11 17:51:51.455  1803  3829 I SystemUpdateService: OTA package size = 12249756
,08-11 17:51:51.461   873  1752 I ActivityManager: Start proc 3831:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-11 17:51:51.463  1803  3829 I SystemUpdateService: showing system update notification
,08-11 17:51:51.478  1803  1803 D SystemUpdateService: onDestroy
,08-11 17:51:51.484  3802  3802 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 17:51:51.523  3802  3802 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-11 17:51:51.529  3831  3831 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-11 17:51:51.532  3802  3802 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 17:51:51.534   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@545515:true
,08-11 17:51:51.535  3831  3831 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:51:51.538  3802  3802 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 17:51:51.544  3831  3831 D SprintDMHelper: simOperator: 
08-11 17:51:51.544  3831  3831 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 17:51:51.546  3802  3802 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 17:51:51.550  3802  3802 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 17:51:51.570   873   884 I ActivityManager: Start proc 3843:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-11 17:51:51.574   873  1752 I ActivityManager: Killing 3259:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-11 17:51:51.635  3802  3802 I vclib   : onServiceConnected
,08-11 17:51:51.747   873  1780 I ActivityManager: Start proc 3858:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-11 17:51:51.750  3802  3857 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-11 17:51:51.753   873  1703 I ActivityManager: Killing 3306:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-11 17:51:51.800  3858  3858 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-11 17:51:51.849  3858  3858 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-11 17:51:51.849  3858  3858 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 17:51:51.849  3858  3858 I GAv4    :   adb logcat -s GAv4
,08-11 17:51:51.873  3858  3858 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 17:51:51.878  3858  3858 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 17:51:51.904  3858  3876 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 17:51:52.000  3858  3858 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-11 17:51:52.038  3858  3858 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 17:51:52.044  3858  3858 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4582-4584)
,08-11 17:51:52.045  3858  3858 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 17:51:52.053  3858  3858 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {57b36df}
,08-11 17:51:52.053  3858  3858 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 17:51:52.053  3858  3858 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 17:51:52.059  3858  3858 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,08-11 17:51:52.062  3858  3858 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 17:51:52.086  3858  3858 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 17:51:52.095  3858  3858 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 17:51:52.095  3858  3858 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 17:51:52.096  3858  3858 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 17:51:52.096  3858  3858 I Adreno  : Build Date                       : 10/20/15
08-11 17:51:52.096  3858  3858 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 17:51:52.096  3858  3858 I Adreno  : Local Branch                     : M14
08-11 17:51:52.096  3858  3858 I Adreno  : Remote Branch                    : 
08-11 17:51:52.096  3858  3858 I Adreno  : Remote Branch                    : 
08-11 17:51:52.096  3858  3858 I Adreno  : Reconstruct Branch               : 
,08-11 17:51:52.154  3858  3905 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-11 17:51:52.164  3858  3858 I NSApplication: Starting up...
,08-11 17:51:52.205   873   884 I ActivityManager: Start proc 3910:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-11 17:51:52.207   873   884 I ActivityManager: Killing 2958:android.process.acore/u0a5 (adj 15): empty #17
,08-11 17:51:52.309  3910  3910 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-11 17:51:52.485   873  1780 I ActivityManager: Killing 3504:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-11 17:51:52.541   873  1374 I ActivityManager: Start proc 3922:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-11 17:51:52.636  3922  3922 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-11 17:51:52.702  3922  3922 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-11 17:51:52.774   873  1749 I ActivityManager: Killing 3523:com.android.musicfx/u0a18 (adj 15): empty #17
,08-11 17:51:55.330   873  1700 D WifiService: setWifiEnabled: true pid=3694, uid=10000
,08-11 17:51:55.331   873  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:51:55.354   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-11 17:51:55.355  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-11 17:51:55.356  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:51:55.356  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:55.356  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:51:55.359  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:55.359  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:55.359  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:55.359  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:51:55.362  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:51:55.362  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:51:55.362  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:55.363  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:51:55.369   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-11 17:51:55.370   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 17:51:55.371   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-11 17:51:55.373   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-11 17:51:55.373   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-11 17:51:55.373   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-11 17:51:55.373   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 17:51:55.398   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-11 17:51:55.398   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 17:51:55.400   372   872 D CommandListener: Setting iface cfg
,08-11 17:51:55.411   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-11 17:51:55.411   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-11 17:51:55.413   873  1308 E native  : do suspend true
08-11 17:51:55.414   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 17:51:55.421   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 17:51:55.452   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 17:51:56.028  1492  1492 I ConfigService: onDestroy
,08-11 17:51:56.087   873  1401 I ActivityManager: Killing 3324:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-11 17:51:56.815   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 17:51:56.885   873  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.81 rxSuccessRate=15.38 delta 1000 -> 994
,08-11 17:51:56.888   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-11 17:51:56.888   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:51:56.901   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 17:51:56.940   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 17:51:56.941  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700',
,08-11 17:51:57.361  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 17:51:57.398  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-11 17:51:57.398  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 17:51:57.399   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 17:51:57.408   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 17:51:57.408   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:51:57.408   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-11 17:51:57.422   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:51:57.434   372   872 D CommandListener: Setting iface cfg
,08-11 17:51:57.434   873  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-11 17:51:57.440   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 17:51:57.487   873  3957 D DhcpClient: Receive thread started
,08-11 17:51:57.591   873  1308 E native  : do suspend false
,08-11 17:51:57.623   873  2101 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 17:51:57.636   873  3957 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172413, domain null
,08-11 17:51:57.638   873  2101 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172413 seconds
,08-11 17:51:57.643   873  2101 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 17:51:57.659   873  3957 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 17:51:57.661   873  2101 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-11 17:51:57.667   372   872 D CommandListener: Setting iface cfg
,08-11 17:51:57.677   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 17:51:57.679   873  1308 E native  : do suspend true
08-11 17:51:57.680   873  2101 D DhcpClient: Scheduling renewal in 86399s
,08-11 17:51:57.697   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-11 17:51:57.698   873  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-11 17:51:57.699   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-11 17:51:57.701   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-11 17:51:57.701   873  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-11 17:51:57.746   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 17:51:57.747   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-11 17:51:57.749   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-11 17:51:57.750   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-11 17:51:57.753   873  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-11 17:51:57.767   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-11 17:51:57.777   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-11 17:51:57.778   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-11 17:51:57.778   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-11 17:51:57.778   873  1310 D ConnectivityService:    accepting network in place of null
,08-11 17:51:57.778   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-11 17:51:57.779   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 17:51:57.779   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 17:51:57.795   873  3956 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410334, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 17:51:57.822   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:51:57.864   873  3955 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:801::200e
,08-11 17:51:57.868   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:51:57.876   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-11 17:51:57.876   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:51:57.888   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 17:51:57.884   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-11 17:51:57.893  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:57.893  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:51:57.894  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:57.894  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:57.898  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:57.898  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:57.898  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:57.899  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:57.902  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:51:57.902  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:51:57.902  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:51:57.902  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:51:57.915  1803  1803 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 17:51:57.918  1803  1803 D SystemUpdateService: onCreate
,08-11 17:51:57.923  1803  1803 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 17:51:57.944   873  3955 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 15:51:57 GMT], X-Android-Received-Millis=[1470930717943], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470930717915]}
,08-11 17:51:57.945   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 17:51:57.946  1803  3967 I SystemUpdateService: active receiver: enabled
08-11 17:51:57.946   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-11 17:51:57.946   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-11 17:51:57.949  1803  1803 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 17:51:57.951   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-11 17:51:57.956  1803  2365 I iu.UploadsManager: num queued entries: 0
,08-11 17:51:57.956  1803  2365 I iu.UploadsManager: num updated entries: 0
,08-11 17:51:57.956  1803  2365 I iu.SyncManager: NEXT; no task
,08-11 17:51:57.964  1803  3967 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 17:51:57.965  1803  1803 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 17:51:57.969  1803  1803 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 17:51:57.970  1803  3967 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 17:51:57.970  1803  3967 I SystemUpdateService: now status is 0 (complete)
,08-11 17:51:57.970  1803  3967 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 17:51:57.970  1803  3967 I SystemUpdateService: file has been verified
,08-11 17:51:57.971  1803  3967 I SystemUpdateService: OTA package size = 12249756
,08-11 17:51:57.972  3831  3831 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:51:57.981  1803  3967 I SystemUpdateService: showing system update notification
,08-11 17:51:57.983  3831  3831 D SprintDMHelper: simOperator: 
,08-11 17:51:57.983  3831  3831 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 17:51:57.997  1803  3971 I MDM     : [207] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-11 17:51:57.997  1803  3971 W BaseAppContext: Using Auth Proxy for data requests.
08-11 17:51:57.999  1803  3971 V GoogleAuthProtoRequest: [207] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 17:51:58.025  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:51:58.033  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:51:58.084  1803  1803 D SystemUpdateService: onDestroy
,08-11 17:51:58.129  3802  3975 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 17:51:58.133  1492  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-11 17:51:58.133  1492  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-11 17:51:58.133  1492  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 17:51:58.133  1492  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 17:51:58.146  1803  3971 E MDM     : [207] SitrepService.a: Error sending sitrep.
,08-11 17:51:58.877   873  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-11 17:52:00.344   873  1401 D WifiService: setWifiEnabled: false pid=3694, uid=10000
,08-11 17:52:00.345   873  1401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:52:00.383  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-11 17:52:00.389   873  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-11 17:52:00.390   873  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 17:52:00.391   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 17:52:00.391   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:52:00.416   873  1308 E native  : do suspend true
,08-11 17:52:00.433   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-11 17:52:00.433   873  2101 D DhcpClient: Clearing IP address
,08-11 17:52:00.437   372   872 D CommandListener: Setting iface cfg
,08-11 17:52:00.449   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-11 17:52:00.465   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-11 17:52:00.456   395   395 E Parcel  : Reading a NULL string not supported here.
,08-11 17:52:00.446  1492  3979 V NativeCrypto: Read error: ssl=0x9ac37c00: I/O error during system call, Connection timed out
,08-11 17:52:00.461   873  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-11 17:52:00.468   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 17:52:00.468   873  1308 E native  : do suspend true
08-11 17:52:00.462   873  3957 D DhcpClient: Receive thread stopped
08-11 17:52:00.471   873  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-11 17:52:00.479  1492  3979 V NativeCrypto: SSL shutdown failed: ssl=0x9ac37c00: I/O error during system call, Broken pipe
,08-11 17:52:00.534   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:52:00.578   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:52:00.578   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-11 17:52:00.580   873  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-11 17:52:00.581   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:52:00.595  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:00.595   873   890 D Tethering: MasterInitialState.processMessage what=3
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:00.596  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:00.596  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:00.596  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-11 17:52:00.599  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:00.599  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:00.601  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:00.601  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:00.605   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-11 17:52:00.610  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:00.610  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
08-11 17:52:00.610  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:00.611  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:52:00.622  1803  1803 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 17:52:00.629   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 17:52:00.629  1803  1803 D SystemUpdateService: onCreate
08-11 17:52:00.632  1704  2062 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 17:52:00.633  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:00.633  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:00.633  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.633  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:52:00.634  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:00.634  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:00.634  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.634  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:00.634  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:00.635  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:00.635  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:00.635  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:00.636  1803  1803 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-11 17:52:00.637   873  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-11 17:52:00.648  1803  3990 I SystemUpdateService: active receiver: enabled
,08-11 17:52:00.648  1803  1803 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-11 17:52:00.650  1803  2365 I iu.UploadsManager: num queued entries: 0
08-11 17:52:00.651  1803  2365 I iu.UploadsManager: num updated entries: 0
08-11 17:52:00.651  1803  2365 I iu.SyncManager: NEXT; no task
,08-11 17:52:00.657  1803  1803 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 17:52:00.658  1803  1803 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 17:52:00.660  3831  3831 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:52:00.664  1803  3990 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 17:52:00.665  3831  3831 D SprintDMHelper: simOperator: 
08-11 17:52:00.665  3831  3831 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 17:52:00.677   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-11 17:52:00.678  1803  3990 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-11 17:52:00.678  1803  3990 I SystemUpdateService: now status is 0 (complete)
08-11 17:52:00.678  1803  3990 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 17:52:00.678  1803  3990 I SystemUpdateService: file has been verified
08-11 17:52:00.678  1803  3990 I SystemUpdateService: OTA package size = 12249756
,08-11 17:52:00.687  3802  3994 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-11 17:52:00.706  1803  3990 I SystemUpdateService: showing system update notification
,08-11 17:52:00.715  1803  1803 D SystemUpdateService: onDestroy
,08-11 17:52:05.400   873   890 I ActivityManager: Start proc 4000:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 17:52:05.545  4000  4000 D AdapterServiceConfig: Adding HeadsetService
,08-11 17:52:05.545  4000  4000 D AdapterServiceConfig: Adding A2dpService
08-11 17:52:05.545  4000  4000 D AdapterServiceConfig: Adding HidService
08-11 17:52:05.545  4000  4000 D AdapterServiceConfig: Adding HealthService
08-11 17:52:05.546  4000  4000 D AdapterServiceConfig: Adding PanService
,08-11 17:52:05.546  4000  4000 D AdapterServiceConfig: Adding GattService
08-11 17:52:05.546  4000  4000 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 17:52:05.564   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@697b9fd:true
,08-11 17:52:05.564  4000  4000 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 17:52:05.570  4000  4000 I bt_bluedroid: init
,08-11 17:52:05.571  4000  4012 I BluetoothAdapterState: Entering OffState
,08-11 17:52:05.577  4000  4013 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 17:52:05.578  4000  4013 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-11 17:52:05.578  4000  4013 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 17:52:05.578  4000  4013 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-11 17:52:05.581  4000  4000 I bt_bluedroid: get_profile_interface socket
08-11 17:52:05.583  4000  4000 I bt_bluedroid: get_profile_interface sdp
,08-11 17:52:05.589  4000  4016 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 17:52:05.591  4000  4011 I bt_bluedroid: config_hci_snoop_log
,08-11 17:52:05.593  4000  4016 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 17:52:05.594   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-11 17:52:05.608  4000  4012 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 17:52:05.609  4000  4012 D BluetoothAdapterProperties: Setting state to 14
08-11 17:52:05.609  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-11 17:52:05.614  4000  4012 D BluetoothBondStateMachine: make
,08-11 17:52:05.622  4000  4017 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 17:52:05.630  4000  4012 I BluetoothAdapterState: Entering PendingCommandState
,08-11 17:52:05.633  4000  4000 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 17:52:05.641  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:05.643  4000  4000 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 17:52:05.644  4000  4000 D BtGatt.GattService: Received start request. Starting profile...
,08-11 17:52:05.645  4000  4000 D BtGatt.GattService: start()
,08-11 17:52:05.645  4000  4000 I bt_bluedroid: get_profile_interface gatt
08-11 17:52:05.648  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:52:05.648  4000  4000 D BtGatt.AdvertiseManager: advertise manager created
,08-11 17:52:05.656  4000  4000 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:52:05.656  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:05.656  4000  4000 V BluetoothAdapterState: isBleTurningOn()=true
08-11 17:52:05.656  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:05.657  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 17:52:05.658  4000  4012 I bt_bluedroid: enable
08-11 17:52:05.659  4000  4013 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-11 17:52:05.660  4000  4013 I bt_hci  : start_up
,08-11 17:52:05.681  4000  4013 I bt_vendor: alloc value 0xb3a67189
,08-11 17:52:05.681  4000  4013 I bt_vendor: init
08-11 17:52:05.681  4000  4013 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 17:52:05.682  4000  4013 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 17:52:05.783   873  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-11 17:52:05.789  4000  4013 D bt_hci  : start_up starting async portion
,08-11 17:52:05.790  4000  4020 I bt_hci  : event_finish_startup
08-11 17:52:05.790  4000  4020 I bt_hci_h4: hal_open
08-11 17:52:05.791  4000  4020 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 17:52:05.802  4000  4020 I bt_userial_vendor: device fd = 51 open
,08-11 17:52:05.832  4000  4020 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 17:52:05.865  4000  4020 D bt_hwcfg: Chipset BCM4354A2
,08-11 17:52:05.865  4000  4020 D bt_hwcfg: Target name = [BCM4354A2]
08-11 17:52:05.866  4000  4020 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 17:52:06.948  4000  4020 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 17:52:06.950  4000  4020 D bt_hwcfg: Settlement delay -- 100 ms
08-11 17:52:06.950  4000  4020 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 17:52:07.072  4000  4020 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 17:52:07.073  4000  4020 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 17:52:07.099  4000  4020 I bt_hwcfg: vendor lib fwcfg completed
08-11 17:52:07.100  4000  4020 I bt_vendor: firmware callback
,08-11 17:52:07.100  4000  4020 I bt_hci  : firmware_config_callback
,08-11 17:52:07.114  4000  4022 I bt_btu  : btu_task pending for preload complete event
,08-11 17:52:07.114  4000  4022 I bt_btu_task: Bluetooth chip preload is complete
08-11 17:52:07.114  4000  4022 I bt_btu  : btu_task received preload complete event
,08-11 17:52:07.125  4000  4022 I         : BTE_InitTraceLevels -- TRC_HCI
08-11 17:52:07.125  4000  4022 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-11 17:52:07.126  4000  4022 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 17:52:07.126  4000  4022 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 17:52:07.126  4000  4022 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-11 17:52:07.126  4000  4022 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 17:52:07.126  4000  4022 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 17:52:07.127  4000  4022 I         : BTE_InitTraceLevels -- TRC_BTM
,08-11 17:52:07.127  4000  4022 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 17:52:07.127  4000  4022 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 17:52:07.127  4000  4022 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 17:52:07.127  4000  4022 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 17:52:07.127  4000  4022 I         : BTE_InitTraceLevels -- TRC_SMP
,08-11 17:52:07.128  4000  4022 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 17:52:07.128  4000  4022 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 17:52:07.276  4000  4022 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e4d9d
,08-11 17:52:07.277  4000  4022 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e4d9d 
,08-11 17:52:07.290  4000  4016 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 17:52:07.294  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 17:52:07.295  4000  4016 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 17:52:07.299  4000  4016 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 17:52:07.304  4000  4016 D BluetoothAdapterProperties: Scan Mode:20
,08-11 17:52:07.305  4000  4016 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-11 17:52:07.305  4000  4016 D bt_hci  : do_postload posting postload work item
08-11 17:52:07.306  4000  4020 I bt_hci  : event_postload
,08-11 17:52:07.306  4000  4020 I bt_vendor: sco_config_cb
08-11 17:52:07.306  4000  4020 I bt_hci  : sco_config_callback postload finished.
08-11 17:52:07.310  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:07.312  4000  4020 I bt_vendor: low_power_mode_cb
08-11 17:52:07.313  4000  4016 D bt_bte_conf: Device ID record 1 : primary
08-11 17:52:07.313  4000  4016 D bt_bte_conf:   vendorId            = 000f
08-11 17:52:07.313  4000  4016 D bt_bte_conf:   vendorIdSource      = 0001
08-11 17:52:07.313  4000  4016 D bt_bte_conf:   product             = 1200
08-11 17:52:07.313  4000  4016 D bt_bte_conf:   version             = 1436
,08-11 17:52:07.314  4000  4016 D bt_bte_conf:   clientExecutableURL = 
08-11 17:52:07.314  4000  4016 D bt_bte_conf:   serviceDescription  = 
08-11 17:52:07.314  4000  4016 D bt_bte_conf:   documentationURL    = 
08-11 17:52:07.314  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:07.314  4000  4016 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 17:52:07.315  4000  4013 D bt_stack_manager: event_start_up_stack finished
08-11 17:52:07.316  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 17:52:07.316  4000  4012 D BluetoothAdapterProperties: Setting state to 15
08-11 17:52:07.318  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 17:52:07.319  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:07.320  4000  4012 I BluetoothAdapterState: Entering BleOnState
,08-11 17:52:07.324  4000  4012 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-11 17:52:07.324  4000  4012 D BluetoothAdapterProperties: Setting state to 11
08-11 17:52:07.324  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 17:52:07.332  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:07.333  4000  4000 D HeadsetService: Received start request. Starting profile...
08-11 17:52:07.337  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:07.338  4000  4000 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 17:52:07.338  4000  4000 D HeadsetStateMachine: make
,08-11 17:52:07.339  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:07.341  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:07.353  4000  4012 I BluetoothAdapterState: Entering PendingCommandState
,08-11 17:52:07.354  4000  4000 D HeadsetStateMachine: max_hf_connections = 1
08-11 17:52:07.354  4000  4000 I bt_bluedroid: get_profile_interface handsfree
08-11 17:52:07.354  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-11 17:52:07.357  4000  4016 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
,08-11 17:52:07.362  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:07.363  4000  4000 D A2dpService: Received start request. Starting profile...
,08-11 17:52:07.363  4000  4000 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 17:52:07.364  4000  4000 I bt_bluedroid: get_profile_interface avrcp
,08-11 17:52:07.372  4000  4000 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 17:52:07.372  4000  4000 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 17:52:07.373  4000  4000 D A2dpStateMachine: make
,08-11 17:52:07.374  4000  4000 I bt_bluedroid: get_profile_interface a2dp
,08-11 17:52:07.375  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 17:52:07.376  4000  4031 D A2dpStateMachine: Enter Disconnected: -2
,08-11 17:52:07.379  4000  4000 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 17:52:07.380  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:07.381  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:52:07.383  4000  4000 D HidService: Received start request. Starting profile...
08-11 17:52:07.383  3749  3749 D BluetoothInputDevice: Proxy object connected
08-11 17:52:07.383  4000  4000 I bt_bluedroid: get_profile_interface hidhost
08-11 17:52:07.384  4000  4016 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c63e5
08-11 17:52:07.384  3749  3749 D HidProfile: Bluetooth service connected
08-11 17:52:07.384  4000  4000 D HidService: setHidService(): set to: null
08-11 17:52:07.384  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 17:52:07.385  4000  4000 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-11 17:52:07.387  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:52:07.388  4000  4000 D HealthService: Received start request. Starting profile...
,08-11 17:52:07.392  4000  4000 I bt_bluedroid: get_profile_interface health
,08-11 17:52:07.396  4000  4000 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 17:52:07.399  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:07.402  3749  3749 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 17:52:07.402  3749  3749 D PanProfile: Bluetooth service connected
08-11 17:52:07.403  4000  4000 D PanService: Received start request. Starting profile...
08-11 17:52:07.403  4000  4000 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 17:52:07.403  4000  4000 I bt_bluedroid: get_profile_interface pan
,08-11 17:52:07.405  4000  4016 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-11 17:52:07.412  4000  4000 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:07.414  3749  3749 D BluetoothMap: Proxy object connected
08-11 17:52:07.414  4000  4000 D BluetoothMapService: Received start request. Starting profile...
08-11 17:52:07.414  4000  4000 D BluetoothMapService: start()
,08-11 17:52:07.414  3749  3749 D MapProfile: Bluetooth service connected
,08-11 17:52:07.415  3749  3749 D BluetoothMap: getConnectedDevices()
08-11 17:52:07.416  3749  3749 D BluetoothMap: Bluetooth is Not enabled
08-11 17:52:07.417  4000  4000 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-11 17:52:07.418  4000  4000 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-11 17:52:07.418  4000  4000 D BluetoothMapAppObserver: createReceiver()
,08-11 17:52:07.419  4000  4000 D BluetoothMapAppObserver: initObservers()
08-11 17:52:07.419  4000  4000 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 17:52:07.426  4000  4000 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:07.426  4000  4000 V BluetoothAdapterState: isTurningOn()=true
,08-11 17:52:07.426  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:07.426  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:07.429  4000  4000 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:52:07.429  4000  4000 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:07.429  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:07.429  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:07.429  4000  4028 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-11 17:52:07.432  4000  4000 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:52:07.432  4000  4000 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:07.433  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 17:52:07.433  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:07.433  4000  4000 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:07.433  4000  4000 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:07.434  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:07.434  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:07.434  4000  4000 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:07.434  4000  4000 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:07.434  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:07.434  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:07.435  4000  4000 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:07.435  4000  4000 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:07.435  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:07.435  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:07.435  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 17:52:07.436  4000  4012 D BluetoothAdapterProperties: ScanMode =  20
08-11 17:52:07.436  4000  4012 D BluetoothAdapterProperties: State =  11
08-11 17:52:07.438  4000  4016 D BluetoothAdapterProperties: Scan Mode:21
08-11 17:52:07.438  4000  4016 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 17:52:07.439  4000  4012 D BluetoothAdapterProperties: Setting state to 12
,08-11 17:52:07.439  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 17:52:07.440  4000  4012 I BluetoothAdapterState: Entering OnState
08-11 17:52:07.441  1367  1380 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:07.442  1367  1392 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:07.443  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:07.447  4000  4000 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 17:52:07.447  1367  1393 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 17:52:07.447  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:52:07.447  4000  4000 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-11 17:52:07.449  4000  4000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 17:52:07.450  3749  3759 D BluetoothMap: onBluetoothStateChange: up=true
,08-11 17:52:07.452  3749  3760 D BluetoothPan: onBluetoothStateChange on: true
,08-11 17:52:07.453   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-11 17:52:07.454  4000  4000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:07.454  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:07.455  3749  3759 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 17:52:07.455  1367  1380 D BluetoothPan: onBluetoothStateChange on: true
08-11 17:52:07.457  4000  4000 D ObexServerSockets: Succeed to create listening sockets 
08-11 17:52:07.457  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:07.457  4000  4000 D ObexServerSockets0: startAccept()
,08-11 17:52:07.458  4000  4000 D ObexServerSockets0: prepareForNewConnect()
08-11 17:52:07.458  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 17:52:07.459  1367  1367 D PanProfile: Bluetooth service connected
,08-11 17:52:07.459  1367  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 17:52:07.460  4000  4000 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-11 17:52:07.460  4000  4000 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-11 17:52:07.461  1367  1367 D BluetoothInputDevice: Proxy object connected
,08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:07.461  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:07.461  1367  1367 D HidProfile: Bluetooth service connected
08-11 17:52:07.462   873   873 D BluetoothA2dp: Proxy object connected
08-11 17:52:07.463  3749  3760 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 17:52:07.463  1367  1367 D BluetoothA2dp: Proxy object connected
,08-11 17:52:07.464   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:07.464  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:07.464   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 17:52:07.464  1760  1771 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:07.465   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:07.465  1367  1393 D BluetoothMap: onBluetoothStateChange: up=true
08-11 17:52:07.466  4000  4037 D ObexServerSockets0: Accepting socket connection...
08-11 17:52:07.467  4000  4038 D ObexServerSockets0: Accepting socket connection...
08-11 17:52:07.467  1367  1367 D BluetoothMap: Proxy object connected
08-11 17:52:07.467  1367  1367 D MapProfile: Bluetooth service connected
,08-11 17:52:07.467  1367  1367 D BluetoothMap: getConnectedDevices()
08-11 17:52:07.470   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 17:52:07.472  4000  4000 D BluetoothMapService: onReceive
,08-11 17:52:07.472  4000  4000 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:52:07.472  4000  4000 D BluetoothMapService: STATE_ON
08-11 17:52:07.472  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:07.474  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:07.474  3749  3749 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 17:52:07.475  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:07.478  3749  3749 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-11 17:52:07.487  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 17:52:07.490  3749  3749 D BluetoothA2dp: Proxy object connected
,08-11 17:52:07.493  4000  4000 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-11 17:52:07.494  4000  4000 D ObexServerSockets0: prepareForNewConnect()
,08-11 17:52:07.495  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:52:07.502  3749  3749 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:52:07.506  1367  1367 D BluetoothPbap: Proxy object connected
,08-11 17:52:07.506  3749  3749 D BluetoothPbap: Proxy object connected
08-11 17:52:07.506  1367  1367 D PbapServerProfile: Bluetooth service connected
08-11 17:52:07.506  3749  3749 D PbapServerProfile: Bluetooth service connected
,08-11 17:52:07.515  4000  4043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 17:52:07.538  4000  4047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 17:52:07.540  4000  4047 I BtOppRfcommListener: Accept thread started.
,08-11 17:52:07.544  1367  1380 D BluetoothHeadset: Proxy object connected
,08-11 17:52:07.544  1367  1367 D HeadsetProfile: Bluetooth service connected
08-11 17:52:07.545   873   873 D BluetoothHeadset: Proxy object connected
08-11 17:52:07.545  1760  1773 D BluetoothHeadset: Proxy object connected
08-11 17:52:07.546   873   873 D BluetoothHeadset: Proxy object connected
,08-11 17:52:07.546   873   873 D BluetoothHeadset: Proxy object connected
,08-11 17:52:07.565   873   890 D BluetoothHeadset: Proxy object connected
,08-11 17:52:07.565   873   890 D BluetoothHeadset: Proxy object connected
08-11 17:52:07.566  1760  2030 D BluetoothHeadset: Proxy object connected
08-11 17:52:07.566   873   890 D BluetoothHeadset: Proxy object connected
,08-11 17:52:07.582  3749  3759 D BluetoothHeadset: Proxy object connected
,08-11 17:52:07.583  3749  3749 D HeadsetProfile: Bluetooth service connected
,08-11 17:52:10.366  4000  4012 D BluetoothAdapterState: Current state: ON, message: 23
,08-11 17:52:10.367  4000  4012 D BluetoothAdapterProperties: Setting state to 13
,08-11 17:52:10.367  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-11 17:52:10.369  4000  4012 D BluetoothAdapterProperties: onBluetoothDisable()
,08-11 17:52:10.378  4000  4012 I BluetoothAdapterState: Entering PendingCommandState
,08-11 17:52:10.386  4000  4000 D BluetoothMapService: onReceive
08-11 17:52:10.386  4000  4000 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:52:10.386  4000  4000 D BluetoothMapService: STATE_TURNING_OFF
08-11 17:52:10.386  4000  4000 D BluetoothMapService: MAP Service closeService in
08-11 17:52:10.386  4000  4000 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 17:52:10.386  4000  4000 D ObexServerSockets0: shutdown(block = true)
08-11 17:52:10.387  4000  4000 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 17:52:10.387  4000  4000 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 17:52:10.387  4000  4037 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-11 17:52:10.388  4000  4038 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 17:52:10.389  4000  4025 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 17:52:10.391  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:10.391  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:10.392  4000  4016 D BluetoothAdapterProperties: Scan Mode:20
08-11 17:52:10.393  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 17:52:10.393  4000  4000 I BtOppRfcommListener: stopping Accept Thread
08-11 17:52:10.397  4000  4047 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 17:52:10.397  4000  4047 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 17:52:10.399  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:10.399  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:10.402  4000  4000 D HeadsetService: Received stop request...Stopping profile...
08-11 17:52:10.405  1367  1393 D BluetoothHeadset: Proxy object disconnected
08-11 17:52:10.406   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 17:52:10.407  1760  1939 D BluetoothHeadset: Proxy object disconnected
,08-11 17:52:10.410   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 17:52:10.410   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 17:52:10.412  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:10.413  4000  4000 D A2dpService: Received stop request...Stopping profile...
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:10.413  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:10.413  4000  4031 D A2dpStateMachine: Exit Disconnected: -1
,08-11 17:52:10.414  3749  3759 D BluetoothHeadset: Proxy object disconnected
,08-11 17:52:10.415  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:10.415  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:10.416  4000  4000 D HidService: Received stop request...Stopping profile...
,08-11 17:52:10.416  4000  4000 D HidService: Stopping Bluetooth HidService
08-11 17:52:10.417  1367  1367 D HeadsetProfile: Bluetooth service disconnected
08-11 17:52:10.417   873   873 D BluetoothA2dp: Proxy object disconnected
08-11 17:52:10.417  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-11 17:52:10.418  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-11 17:52:10.418  1367  1367 D HidProfile: Bluetooth service disconnected
,08-11 17:52:10.418  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 17:52:10.419  4000  4000 V BluetoothAdapterState: isTurningOff()=true
,08-11 17:52:10.419  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:10.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:10.419  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:10.420  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:10.421  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:10.421  3694  3694 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 17:52:10.421  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:10.422  4000  4000 D HealthService: Received stop request...Stopping profile...
08-11 17:52:10.422  3749  3749 D HeadsetProfile: Bluetooth service disconnected
08-11 17:52:10.422  3749  3749 D BluetoothA2dp: Proxy object disconnected
,08-11 17:52:10.423  3749  3749 D BluetoothInputDevice: Proxy object disconnected
08-11 17:52:10.423  3749  3749 D HidProfile: Bluetooth service disconnected
,08-11 17:52:10.424  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:10.426  4000  4000 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 17:52:10.426  4000  4000 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 17:52:10.426  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-11 17:52:10.426  4000  4022 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:52:10.427  4000  4022 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:52:10.427  4000  4022 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 17:52:10.427  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:10.428  4000  4016 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-11 17:52:10.429  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:10.429  4000  4000 D PanService: Received stop request...Stopping profile...
,08-11 17:52:10.431  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 17:52:10.431  1367  1367 D PanProfile: Bluetooth service disconnected
08-11 17:52:10.431  3749  3749 D DockEventReceiver: finishStartingService: stopping service
08-11 17:52:10.431  4000  4000 D BluetoothMapService: Received stop request...Stopping profile...
08-11 17:52:10.431  4000  4000 D BluetoothMapService: stop()
08-11 17:52:10.434  3749  3749 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-11 17:52:10.434  3749  3749 D PanProfile: Bluetooth service disconnected
08-11 17:52:10.434  4000  4000 D BluetoothMapAppObserver: deinitObservers()
08-11 17:52:10.435  4000  4000 D BluetoothMapAppObserver: removeReceiver()
,08-11 17:52:10.436  3749  3749 D BluetoothMap: Proxy object disconnected
08-11 17:52:10.436  1367  1367 D BluetoothMap: Proxy object disconnected
08-11 17:52:10.436  3749  3749 D MapProfile: Bluetooth service disconnected
08-11 17:52:10.436  1367  1367 D MapProfile: Bluetooth service disconnected
08-11 17:52:10.437  4000  4000 V BluetoothAdapterState: isTurningOff()=true
08-11 17:52:10.437  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:10.437  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 17:52:10.437  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:10.438  4000  4022 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:52:10.438  4000  4022 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:52:10.438  4000  4000 V BluetoothAdapterState: isTurningOff()=true
08-11 17:52:10.438  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:10.439  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 17:52:10.439  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:10.439  4000  4022 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:52:10.439  4000  4022 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 17:52:10.439  4000  4000 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 17:52:10.439  4000  4022 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 17:52:10.439  4000  4022 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-11 17:52:10.439  4000  4000 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 17:52:10.439  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 17:52:10.439  4000  4000 V BluetoothAdapterState: isTurningOff()=true
08-11 17:52:10.439  4000  4016 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 17:52:10.439  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:10.440  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:10.440  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:10.442  4000  4000 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-11 17:52:10.442  4000  4016 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-11 17:52:10.442  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:52:10.443  4000  4000 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 17:52:10.443  4000  4000 V BluetoothAdapterState: isTurningOff()=true
08-11 17:52:10.443  4000  4000 V BluetoothAdapterState: isTurningOn()=false,
08-11 17:52:10.443  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:10.443  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:10.444  4000  4000 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 17:52:10.444  4000  4000 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 17:52:10.445  4000  4000 D BluetoothMapService: MAP Service closeService in
08-11 17:52:10.446  4000  4000 V BluetoothAdapterState: isTurningOff()=true,
08-11 17:52:10.446  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:10.446  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 17:52:10.446  4000  4000 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:10.446  4000  4000 D BluetoothMapService: cleanup()
08-11 17:52:10.446  4000  4000 D BluetoothMapService: MAP Service closeService in
08-11 17:52:10.446  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-11 17:52:10.446  4000  4012 D BluetoothAdapterProperties: Setting state to 15
,08-11 17:52:10.446  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 17:52:10.448  1367  1380 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:52:10.448  4000  4012 I BluetoothAdapterState: Entering BleOnState
08-11 17:52:10.448  1367  1367 D BluetoothPbap: Proxy object disconnected
,08-11 17:52:10.448  1367  1367 D PbapServerProfile: Bluetooth service disconnected
08-11 17:52:10.449  3749  3749 D BluetoothPbap: Proxy object disconnected
,08-11 17:52:10.449  3749  3749 D PbapServerProfile: Bluetooth service disconnected
08-11 17:52:10.449  1367  1392 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:52:10.449  1367  1393 D BluetoothPbap: onBluetoothStateChange: up=false
,08-11 17:52:10.454  3749  3760 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:52:10.454  3749  3759 D BluetoothMap: onBluetoothStateChange: up=false
08-11 17:52:10.457  3749  3760 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:52:10.458  3749  3759 D BluetoothPan: onBluetoothStateChange on: false
08-11 17:52:10.458   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 17:52:10.459  3749  3760 D BluetoothInputDevice: onBluetoothStateChange: up=false,
08-11 17:52:10.459  1367  1380 D BluetoothPan: onBluetoothStateChange on: false
08-11 17:52:10.460  1367  1392 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 17:52:10.461  3749  3759 D BluetoothPbap: onBluetoothStateChange: up=false
,08-11 17:52:10.461   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:52:10.461   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:52:10.462  1760  1771 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:52:10.462   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 17:52:10.462  1367  1393 D BluetoothMap: onBluetoothStateChange: up=false
,08-11 17:52:10.463  4000  4012 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-11 17:52:10.463  4000  4012 D BluetoothAdapterProperties: Setting state to 16
,08-11 17:52:10.463  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-11 17:52:10.464  4000  4012 D BluetoothAdapterProperties: onBleDisable
08-11 17:52:10.465  4000  4013 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-11 17:52:10.466  4000  4022 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 17:52:10.466  4000  4022 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 17:52:10.468  4000  4012 I BluetoothAdapterState: Entering PendingCommandState
08-11 17:52:10.468  4000  4016 D BluetoothAdapterProperties: Scan Mode:20
,08-11 17:52:10.469  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:10.471  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:10.472  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:10.474  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:10.475  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 17:52:10.476  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:10.478  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:10.482  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:52:10.484  3749  3749 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:52:10.668  4000  4016 I bt_hci  : shut_down
,08-11 17:52:10.694  4000  4020 I bt_vendor: low_power_mode_cb
,08-11 17:52:10.701  4000  4020 D bt_hwcfg: hw_epilog_process
,08-11 17:52:10.716  4000  4020 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 17:52:10.717  4000  4020 I bt_vendor: epilog_cb
08-11 17:52:10.717  4000  4020 I bt_hci  : epilog_finished_callback
,08-11 17:52:10.725  4000  4016 I bt_hci_h4: hal_close
,08-11 17:52:10.727  4000  4016 I bt_userial_vendor: device fd = 51 close
,08-11 17:52:10.866  4000  4013 D bt_stack_manager: event_shut_down_stack finished.
,08-11 17:52:10.868  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 17:52:10.874  4000  4000 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 17:52:10.874  4000  4012 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-11 17:52:10.876  4000  4000 D BtGatt.GattService: Received stop request...Stopping profile...
,08-11 17:52:10.877  4000  4000 D BtGatt.GattService: stop()
08-11 17:52:10.877  4000  4000 D BtGatt.AdvertiseManager: advertise clients cleared
,08-11 17:52:10.883  4000  4000 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:52:10.883  4000  4000 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:10.883  4000  4000 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 17:52:10.884  4000  4000 V BluetoothAdapterState: isBleTurningOff()=true
,08-11 17:52:10.884  4000  4012 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-11 17:52:10.885  4000  4012 D BluetoothAdapterProperties: Setting state to 10
,08-11 17:52:10.885  4000  4012 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-11 17:52:10.887  4000  4012 I BluetoothAdapterState: Entering OffState
08-11 17:52:10.889   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-11 17:52:10.916  4000  4000 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-11 17:52:10.916  4000  4000 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-11 17:52:10.917  4000  4013 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 17:52:10.924  4000  4013 D bt_stack_manager: event_clean_up_stack finished.
08-11 17:52:10.925  4000  4000 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-11 17:52:10.930  4000  4000 I art     : System.exit called, status: 0
08-11 17:52:10.931  4000  4000 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 17:52:10.983   873   883 I ActivityManager: Process com.android.bluetooth (pid 4000) has died
,08-11 17:52:15.365  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:52:15.365  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:52:20.373  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:52:20.373  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad9d9d8 removed from the list
08-11 17:52:20.373  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:52:20.374  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:52:20.374  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:52:20.378  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:52:20.378  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef26016 added. We now have 4 listener(s)
08-11 17:52:20.378  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:52:20.380  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:52:20.381  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef26016 removed from the list
08-11 17:52:20.381  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:52:20.381  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:52:20.381  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:52:20.384  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:52:20.384  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7dcd97 added. We now have 4 listener(s)
,08-11 17:52:20.385  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:52:22.394  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:22.448   873   890 I ActivityManager: Start proc 4056:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 17:52:22.553  4056  4056 D AdapterServiceConfig: Adding HeadsetService
08-11 17:52:22.553  4056  4056 D AdapterServiceConfig: Adding A2dpService
08-11 17:52:22.553  4056  4056 D AdapterServiceConfig: Adding HidService
08-11 17:52:22.553  4056  4056 D AdapterServiceConfig: Adding HealthService
08-11 17:52:22.553  4056  4056 D AdapterServiceConfig: Adding PanService
08-11 17:52:22.554  4056  4056 D AdapterServiceConfig: Adding GattService
08-11 17:52:22.554  4056  4056 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 17:52:22.566   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1199d26:true
,08-11 17:52:22.566  4056  4056 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 17:52:22.569  4056  4056 I bt_bluedroid: init
,08-11 17:52:22.569  4056  4068 I BluetoothAdapterState: Entering OffState
,08-11 17:52:22.572  4056  4069 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 17:52:22.572  4056  4069 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-11 17:52:22.572  4056  4069 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 17:52:22.572  4056  4069 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 17:52:22.573  4056  4056 I bt_bluedroid: get_profile_interface socket
08-11 17:52:22.574  4056  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 17:52:22.575  4056  4056 I bt_bluedroid: get_profile_interface sdp
08-11 17:52:22.576  4056  4072 D BluetoothAdapterProperties: Name is: Nexus 6
08-11 17:52:22.578  4056  4067 I bt_bluedroid: config_hci_snoop_log
,08-11 17:52:22.580   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-11 17:52:22.585  4056  4068 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 17:52:22.585  4056  4068 D BluetoothAdapterProperties: Setting state to 14
,08-11 17:52:22.585  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-11 17:52:22.587  4056  4068 D BluetoothBondStateMachine: make
,08-11 17:52:22.588  4056  4073 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 17:52:22.590  4056  4068 I BluetoothAdapterState: Entering PendingCommandState
08-11 17:52:22.592  4056  4056 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 17:52:22.594  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:22.595  4056  4056 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 17:52:22.595  4056  4056 D BtGatt.GattService: Received start request. Starting profile...
08-11 17:52:22.595  4056  4056 D BtGatt.GattService: start()
08-11 17:52:22.595  4056  4056 I bt_bluedroid: get_profile_interface gatt
08-11 17:52:22.596  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:52:22.596  4056  4056 D BtGatt.AdvertiseManager: advertise manager created
,08-11 17:52:22.603  4056  4056 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:52:22.604  4056  4056 V BluetoothAdapterState: isTurningOn()=false
08-11 17:52:22.604  4056  4056 V BluetoothAdapterState: isBleTurningOn()=true
08-11 17:52:22.604  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:22.604  4056  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 17:52:22.604  4056  4068 I bt_bluedroid: enable
08-11 17:52:22.604  4056  4069 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-11 17:52:22.605  4056  4069 I bt_hci  : start_up
,08-11 17:52:22.610  4056  4069 I bt_vendor: alloc value 0xb3a67189
08-11 17:52:22.610  4056  4069 I bt_vendor: init
08-11 17:52:22.610  4056  4069 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 17:52:22.610  4056  4069 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 17:52:22.719  4056  4069 D bt_hci  : start_up starting async portion
,08-11 17:52:22.719  4056  4076 I bt_hci  : event_finish_startup
08-11 17:52:22.719  4056  4076 I bt_hci_h4: hal_open
,08-11 17:52:22.720  4056  4076 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 17:52:22.729  4056  4076 I bt_userial_vendor: device fd = 51 open
,08-11 17:52:22.762  4056  4076 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 17:52:22.795  4056  4076 D bt_hwcfg: Chipset BCM4354A2
,08-11 17:52:22.796  4056  4076 D bt_hwcfg: Target name = [BCM4354A2]
08-11 17:52:22.797  4056  4076 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 17:52:23.839  4056  4076 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 17:52:23.841  4056  4076 D bt_hwcfg: Settlement delay -- 100 ms
08-11 17:52:23.841  4056  4076 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 17:52:23.962  4056  4076 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 17:52:23.964  4056  4076 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 17:52:23.989  4056  4076 I bt_hwcfg: vendor lib fwcfg completed
08-11 17:52:23.990  4056  4076 I bt_vendor: firmware callback
08-11 17:52:23.990  4056  4076 I bt_hci  : firmware_config_callback
,08-11 17:52:24.003  4056  4080 I bt_btu  : btu_task pending for preload complete event
,08-11 17:52:24.003  4056  4080 I bt_btu_task: Bluetooth chip preload is complete
08-11 17:52:24.003  4056  4080 I bt_btu  : btu_task received preload complete event
,08-11 17:52:24.015  4056  4080 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 17:52:24.015  4056  4080 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 17:52:24.015  4056  4080 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-11 17:52:24.016  4056  4080 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 17:52:24.016  4056  4080 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-11 17:52:24.016  4056  4080 I         : BTE_InitTraceLevels -- TRC_A2D
,08-11 17:52:24.017  4056  4080 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 17:52:24.017  4056  4080 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 17:52:24.017  4056  4080 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 17:52:24.018  4056  4080 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 17:52:24.018  4056  4080 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 17:52:24.018  4056  4080 I         : BTE_InitTraceLevels -- TRC_GATT
,08-11 17:52:24.019  4056  4080 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 17:52:24.020  4056  4080 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 17:52:24.020  4056  4080 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 17:52:24.180  4056  4080 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e4d9d
08-11 17:52:24.180  4056  4080 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e4d9d 
,08-11 17:52:24.209  4056  4072 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 17:52:24.212  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 17:52:24.212  4056  4072 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
08-11 17:52:24.217  4056  4072 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 17:52:24.221  4056  4072 D BluetoothAdapterProperties: Scan Mode:20
,08-11 17:52:24.221  4056  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-11 17:52:24.222  4056  4072 D bt_hci  : do_postload posting postload work item
08-11 17:52:24.222  4056  4076 I bt_hci  : event_postload
08-11 17:52:24.222  4056  4076 I bt_vendor: sco_config_cb
,08-11 17:52:24.223  4056  4076 I bt_hci  : sco_config_callback postload finished.
08-11 17:52:24.228  4056  4072 D bt_bte_conf: Device ID record 1 : primary
,08-11 17:52:24.228  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:24.228  4056  4072 D bt_bte_conf:   vendorId            = 000f
,08-11 17:52:24.228  4056  4072 D bt_bte_conf:   vendorIdSource      = 0001
08-11 17:52:24.231  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:24.228  4056  4072 D bt_bte_conf:   product             = 1200
08-11 17:52:24.232  4056  4072 D bt_bte_conf:   version             = 1436
08-11 17:52:24.232  4056  4076 I bt_vendor: low_power_mode_cb
08-11 17:52:24.232  4056  4072 D bt_bte_conf:   clientExecutableURL = 
08-11 17:52:24.234  4056  4072 D bt_bte_conf:   serviceDescription  = 
08-11 17:52:24.234  4056  4072 D bt_bte_conf:   documentationURL    = 
08-11 17:52:24.234  4056  4072 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 17:52:24.235  4056  4069 D bt_stack_manager: event_start_up_stack finished
08-11 17:52:24.236  4056  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 17:52:24.236  4056  4068 D BluetoothAdapterProperties: Setting state to 15
08-11 17:52:24.236  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 17:52:24.237  4056  4068 I BluetoothAdapterState: Entering BleOnState
,08-11 17:52:24.241  4056  4068 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-11 17:52:24.241  4056  4068 D BluetoothAdapterProperties: Setting state to 11
08-11 17:52:24.241  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 17:52:24.252  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:24.254  4056  4056 D HeadsetService: Received start request. Starting profile...
08-11 17:52:24.259  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:24.261  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:52:24.263  4056  4056 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 17:52:24.263  4056  4056 D HeadsetStateMachine: make
,08-11 17:52:24.274  4056  4068 I BluetoothAdapterState: Entering PendingCommandState
,08-11 17:52:24.277  4056  4056 D HeadsetStateMachine: max_hf_connections = 1
08-11 17:52:24.277  4056  4056 I bt_bluedroid: get_profile_interface handsfree
,08-11 17:52:24.278  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-11 17:52:24.278  4056  4072 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-11 17:52:24.282  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:24.283  4056  4056 D A2dpService: Received start request. Starting profile...
08-11 17:52:24.283  4056  4056 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 17:52:24.284  4056  4056 I bt_bluedroid: get_profile_interface avrcp
,08-11 17:52:24.291  4056  4056 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 17:52:24.291  4056  4056 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 17:52:24.291  4056  4056 D A2dpStateMachine: make
08-11 17:52:24.292  4056  4056 I bt_bluedroid: get_profile_interface a2dp
,08-11 17:52:24.294  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 17:52:24.295  4056  4089 D A2dpStateMachine: Enter Disconnected: -2
08-11 17:52:24.296  4056  4056 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 17:52:24.296  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:52:24.297  4056  4056 D HidService: Received start request. Starting profile...
,08-11 17:52:24.297  4056  4056 I bt_bluedroid: get_profile_interface hidhost
08-11 17:52:24.297  4056  4056 D HidService: setHidService(): set to: null
,08-11 17:52:24.298  4056  4072 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c63e5
08-11 17:52:24.298  4056  4072 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 17:52:24.298  4056  4056 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-11 17:52:24.299  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:52:24.299  4056  4056 D HealthService: Received start request. Starting profile...
08-11 17:52:24.301  4056  4056 I bt_bluedroid: get_profile_interface health
,08-11 17:52:24.304  4056  4056 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 17:52:24.305  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:52:24.305  4056  4056 D PanService: Received start request. Starting profile...
,08-11 17:52:24.305  4056  4056 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 17:52:24.306  4056  4056 I bt_bluedroid: get_profile_interface pan
,08-11 17:52:24.306  4056  4072 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-11 17:52:24.310  4056  4056 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
08-11 17:52:24.310  4056  4056 D BluetoothMapService: Received start request. Starting profile...
,08-11 17:52:24.310  4056  4056 D BluetoothMapService: start()
,08-11 17:52:24.313  4056  4056 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-11 17:52:24.313  4056  4056 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-11 17:52:24.313  4056  4056 D BluetoothMapAppObserver: createReceiver()
08-11 17:52:24.314  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 17:52:24.315  4056  4056 D BluetoothMapAppObserver: initObservers()
08-11 17:52:24.315  4056  4056 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 17:52:24.322  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:24.322  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:24.322  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:24.322  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:24.325  4056  4086 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-11 17:52:24.325  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:24.325  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 17:52:24.326  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:24.327  4056  4056 V BluetoothAdapterState: isTurningOff()=false
,08-11 17:52:24.327  4056  4056 V BluetoothAdapterState: isTurningOn()=true
,08-11 17:52:24.327  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:24.327  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:24.329  4056  4056 V BluetoothAdapterState: isTurningOff()=false
08-11 17:52:24.329  4056  4056 V BluetoothAdapterState: isTurningOn()=true
08-11 17:52:24.329  4056  4056 V BluetoothAdapterState: isBleTurningOn()=false
08-11 17:52:24.329  4056  4056 V BluetoothAdapterState: isBleTurningOff()=false
08-11 17:52:24.330  4056  4068 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 17:52:24.330  4056  4068 D BluetoothAdapterProperties: ScanMode =  20
,08-11 17:52:24.330  4056  4068 D BluetoothAdapterProperties: State =  11
08-11 17:52:24.330  4056  4068 D BluetoothAdapterProperties: Setting state to 12
08-11 17:52:24.330  4056  4068 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 17:52:24.331  1367  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:24.331  4056  4068 I BluetoothAdapterState: Entering OnState
08-11 17:52:24.332  1367  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 17:52:24.335  4056  4072 D BluetoothAdapterProperties: Scan Mode:21
08-11 17:52:24.335  4056  4072 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 17:52:24.336  1367  1392 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 17:52:24.338  1367  1367 D BluetoothA2dp: Proxy object connected
,08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:24.341  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:24.341  3749  3759 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:24.342  3749  3760 D BluetoothMap: onBluetoothStateChange: up=true
08-11 17:52:24.343  4056  4056 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 17:52:24.343  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:52:24.344  3749  3759 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-11 17:52:24.345  4056  4056 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-11 17:52:24.347  3749  3760 D BluetoothPan: onBluetoothStateChange on: true
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:24.347  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:24.347  4056  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:52:24.348   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 17:52:24.349  3749  3759 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 17:52:24.349   873   873 D BluetoothA2dp: Proxy object connected
08-11 17:52:24.349  3749  3749 D BluetoothA2dp: Proxy object connected
08-11 17:52:24.349  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:24.353  4056  4056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:52:24.353  1367  1380 D BluetoothPan: onBluetoothStateChange on: true
,08-11 17:52:24.355  1367  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 17:52:24.356  4056  4056 D ObexServerSockets: Succeed to create listening sockets 
08-11 17:52:24.356  4056  4056 D ObexServerSockets0: startAccept()
08-11 17:52:24.356  4056  4056 D ObexServerSockets0: prepareForNewConnect()
08-11 17:52:24.357  3749  3760 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 17:52:24.359   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 17:52:24.359   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:24.359  1760  1773 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:24.359   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 17:52:24.360  1367  1392 D BluetoothMap: onBluetoothStateChange: up=true
,08-11 17:52:24.360  4056  4056 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-11 17:52:24.361  4056  4056 D BluetoothSdpJni: SDP Create record success - handle: 0
08-11 17:52:24.361  4056  4096 D ObexServerSockets0: Accepting socket connection...
,08-11 17:52:24.363  1367  1367 D BluetoothMap: Proxy object connected
,08-11 17:52:24.363  1367  1367 D MapProfile: Bluetooth service connected
08-11 17:52:24.363  1367  1367 D BluetoothMap: getConnectedDevices()
08-11 17:52:24.363  3749  3749 D BluetoothMap: Proxy object connected
08-11 17:52:24.363  3749  3749 D MapProfile: Bluetooth service connected
,08-11 17:52:24.363   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-11 17:52:24.368  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 17:52:24.363  3749  3749 D BluetoothMap: getConnectedDevices()
08-11 17:52:24.368  1367  1367 D PanProfile: Bluetooth service connected
08-11 17:52:24.368  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:24.368  1367  1367 D BluetoothInputDevice: Proxy object connected
08-11 17:52:24.368  1367  1367 D HidProfile: Bluetooth service connected
,08-11 17:52:24.367  4056  4056 D BluetoothMapService: onReceive
08-11 17:52:24.369  4056  4056 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 17:52:24.369  4056  4056 D BluetoothMapService: STATE_ON
08-11 17:52:24.369  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:24.365  4056  4097 D ObexServerSockets0: Accepting socket connection...
,08-11 17:52:24.376  3749  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 17:52:24.381  3749  3749 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 17:52:24.381  3749  3749 D PanProfile: Bluetooth service connected
08-11 17:52:24.381  3749  3749 D BluetoothInputDevice: Proxy object connected
08-11 17:52:24.381  3749  3749 D HidProfile: Bluetooth service connected
,08-11 17:52:24.384  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 17:52:24.389  3749  3749 D DockEventReceiver: finishStartingService: stopping service
,08-11 17:52:24.393  3749  3749 D BluetoothPbap: Proxy object connected
08-11 17:52:24.393  3749  3749 D PbapServerProfile: Bluetooth service connected
,08-11 17:52:24.399  1367  1367 D BluetoothPbap: Proxy object connected
08-11 17:52:24.399  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-11 17:52:24.401  4056  4056 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-11 17:52:24.401  4056  4056 D ObexServerSockets0: prepareForNewConnect()
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:24.401  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:24.403  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:52:24.403  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:52:24.403  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7dcd97 removed from the list
08-11 17:52:24.403  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:52:24.403  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:52:24.403  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:52:24.404  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:52:24.404  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfebb84 added. We now have 4 listener(s)
,08-11 17:52:24.404  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:52:24.405  4056  4102 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:52:24.406   873  1703 D WifiService: setWifiEnabled: false pid=3694, uid=10000
08-11 17:52:24.406   873  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 17:52:24.410  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:52:24.410   873  1696 D WifiService: setWifiEnabled: true pid=3694, uid=10000
08-11 17:52:24.410   873  1696 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 17:52:24.413   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:24.419  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:24.422  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:24.428  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 17:52:24.430  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:24.430  4056  4110 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 17:52:24.433  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 17:52:24.434  1367  1392 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.434  1367  1367 D HeadsetProfile: Bluetooth service connected
08-11 17:52:24.434   873   873 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.434  1760  1939 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.435   873   873 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.435   873   873 D BluetoothHeadset: Proxy object connected
,08-11 17:52:24.435  4056  4110 I BtOppRfcommListener: Accept thread started.
08-11 17:52:24.435  3749  3759 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.437  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 17:52:24.437  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:52:24.437  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfebb84 removed from the list
08-11 17:52:24.437  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:52:24.437  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:52:24.437  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:52:24.438   873  1308 D WifiConfigStore: loaded 0 passpoint configs
08-11 17:52:24.439   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 17:52:24.440   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-11 17:52:24.441   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 17:52:24.441   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-11 17:52:24.441   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-11 17:52:24.441   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 17:52:24.441  3749  3760 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.442  3749  3749 D HeadsetProfile: Bluetooth service connected
08-11 17:52:24.444  3749  3749 D HeadsetProfile: Bluetooth service connected
08-11 17:52:24.452   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-11 17:52:24.453   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-11 17:52:24.454   372   872 D CommandListener: Setting iface cfg
08-11 17:52:24.454   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-11 17:52:24.454   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 17:52:24.459   873   890 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.459   873   890 D BluetoothHeadset: Proxy object connected
,08-11 17:52:24.459  1760  1771 D BluetoothHeadset: Proxy object connected
08-11 17:52:24.460   873   890 D BluetoothHeadset: Proxy object connected
,08-11 17:52:24.508   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 17:52:24.508   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 17:52:24.512   873  1308 E native  : do suspend true
,08-11 17:52:24.548   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 17:52:25.912   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 17:52:26.060   873  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.62 rxSuccessRate=17.00 delta 1000 -> 994
,08-11 17:52:26.061   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-11 17:52:26.061   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:52:26.080   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 17:52:26.141   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 17:52:26.143  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 17:52:26.588  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 17:52:26.632  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 17:52:26.633  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 17:52:26.636   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 17:52:26.647   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 17:52:26.648   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-11 17:52:26.648   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:52:26.669   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 17:52:26.685   372   872 D CommandListener: Setting iface cfg
,08-11 17:52:26.686   873  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-11 17:52:26.700   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 17:52:26.738   873  4115 D DhcpClient: Receive thread started
,08-11 17:52:26.841   873  1308 E native  : do suspend false
,08-11 17:52:26.873   873  2101 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 17:52:26.889   873  4115 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172771, domain null
,08-11 17:52:26.891   873  2101 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172771 seconds
,08-11 17:52:26.894   873  2101 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 17:52:26.909   873  4115 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 17:52:26.911   873  2101 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 17:52:26.916   372   872 D CommandListener: Setting iface cfg
,08-11 17:52:26.928   873  2101 D DhcpClient: Scheduling renewal in 86399s
,08-11 17:52:26.928   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 17:52:26.932   873  1308 E native  : do suspend true
,08-11 17:52:26.958   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-11 17:52:26.960   873  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-11 17:52:26.962   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-11 17:52:26.966   873  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-11 17:52:26.977   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 17:52:27.013   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 17:52:27.013   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-11 17:52:27.015   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-11 17:52:27.016   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-11 17:52:27.018   873  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-11 17:52:27.026   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-11 17:52:27.031   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-11 17:52:27.031   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-11 17:52:27.032   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-11 17:52:27.032   873  1310 D ConnectivityService:    accepting network in place of null
08-11 17:52:27.032   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-11 17:52:27.032   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 17:52:27.032   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 17:52:27.046   873  4113 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439586, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 17:52:27.100   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:52:27.132   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 17:52:27.140   873  4112 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
08-11 17:52:27.142   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-11 17:52:27.142   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:52:27.155   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 17:52:27.155   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:52:27.163  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:52:27.167  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:52:27.173  3694  3694 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:52:27.176  3694  3694 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:52:27.180  1803  1803 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 17:52:27.186  1803  1803 D SystemUpdateService: onCreate
,08-11 17:52:27.192  1803  1803 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 17:52:27.217   873  4112 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 15:52:26 GMT], X-Android-Received-Millis=[1470930747215], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470930747187]}
,08-11 17:52:27.218   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 17:52:27.219   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-11 17:52:27.219   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-11 17:52:27.220  1803  1803 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 17:52:27.223   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 17:52:27.227  1803  2365 I iu.UploadsManager: num queued entries: 0
,08-11 17:52:27.232  1803  4124 I SystemUpdateService: active receiver: enabled
,08-11 17:52:27.235  1803  1803 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 17:52:27.236  1803  1803 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-11 17:52:27.238  3831  3831 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 17:52:27.250  1803  4126 I MDM     : [212] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-11 17:52:27.250  1803  4126 W BaseAppContext: Using Auth Proxy for data requests.
,08-11 17:52:27.257  1803  4126 V GoogleAuthProtoRequest: [212] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 17:52:27.259  3831  3831 D SprintDMHelper: simOperator: 
,08-11 17:52:27.259  3831  3831 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 17:52:27.264  1803  2365 I iu.UploadsManager: num updated entries: 0
,08-11 17:52:27.265  1803  2365 I iu.SyncManager: NEXT; no task
,08-11 17:52:27.266  1803  4124 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 17:52:27.270  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:52:27.271  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:52:27.286  1803  4124 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 17:52:27.286  1803  4124 I SystemUpdateService: now status is 0 (complete)
,08-11 17:52:27.286  1803  4124 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 17:52:27.286  1803  4124 I SystemUpdateService: file has been verified
,08-11 17:52:27.287  1803  4124 I SystemUpdateService: OTA package size = 12249756
,08-11 17:52:27.307  1803  4124 I SystemUpdateService: showing system update notification
,08-11 17:52:27.399  1492  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-11 17:52:27.399  1492  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-11 17:52:27.399  1492  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 17:52:27.399  1492  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 17:52:27.415  3802  4130 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-11 17:52:27.423  1803  1803 D SystemUpdateService: onDestroy
,08-11 17:52:27.449  1803  4126 E MDM     : [212] SitrepService.a: Error sending sitrep.
,08-11 17:52:28.143   873  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-11 17:52:29.451  3694  4136 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-11 17:52:29.451  3694  4136 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 17:52:32.461  3694  4137 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-11 17:52:32.461  3694  4136 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-11 17:52:32.462  3694  4137 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:52:32.462  3694  4136 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:52:32.464  3694  4136 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:52:32.464  3694  4137 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:52:32.467  3694  4136 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 17:52:32.468  3694  4137 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 17:52:32.469  3694  4139 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: OutgoingSocketThread/Sender)
,08-11 17:52:32.475  3694  4136 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 17:52:32.479  3694  4137 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-11 17:52:32.481  3694  4140 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: IncomingSocketThread/Sender)
,08-11 17:52:32.483  3694  4141 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: OutgoingSocketThread/Receiver)
,08-11 17:52:32.484  3694  4141 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: OutgoingSocketThread/Receiver)
08-11 17:52:32.485  3694  4141 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 17:52:32.485  3694  4141 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 17:52:32.485  3694  4142 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: IncomingSocketThread/Receiver)
08-11 17:52:32.487  3694  4142 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 420, thread name: IncomingSocketThread/Receiver)
08-11 17:52:32.487  3694  4142 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 17:52:32.487  3694  4142 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 17:52:35.040   873  1310 D ConnectivityService: handlePromptUnvalidated 102
,08-11 17:52:40.464  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-11 17:52:40.466  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-11 17:52:40.473  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4339c09 Bundle[{}]
,08-11 17:52:40.475  3694  3740 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 17:52:40.476  3694  3740 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-11 17:52:40.478  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-11 17:52:40.481  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-11 17:52:40.482  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-11 17:52:40.483  3694  3740 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-11 17:52:48.283   873  4113 D NetlinkSocketObserver: NeighborEvent{elapsedMs=460822, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 17:52:50.503  3694  3740 I System.out: Running OutgoingSocketThread
,08-11 17:52:50.509  3694  4145 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-11 17:52:50.509  3694  4145 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 17:52:53.516  3694  4147 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-11 17:52:53.517  3694  4147 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:52:53.517  3694  4147 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:52:53.517  3694  4145 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-11 17:52:53.518  3694  4145 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 17:52:53.518  3694  4145 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:52:53.518  3694  4147 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 17:52:53.520  3694  4145 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 17:52:53.523  3694  4149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Sender)
,08-11 17:52:53.526  3694  4145 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 17:52:53.526  3694  4147 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 17:52:53.531  3694  4150 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Sender)
,08-11 17:52:53.532  3694  4151 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Receiver)
08-11 17:52:53.532  3694  4151 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: OutgoingSocketThread/Receiver)
08-11 17:52:53.532  3694  4151 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 17:52:53.532  3694  4151 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 17:52:53.534  3694  4152 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Receiver)
08-11 17:52:53.536  3694  4152 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: IncomingSocketThread/Receiver)
08-11 17:52:53.536  3694  4152 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 17:52:53.537  3694  4152 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-11 17:53:01.523  3694  3740 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-11 17:53:01.526  3694  3740 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-11 17:53:01.526  3694  3740 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-11 17:53:06.537  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 17:53:06.538  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b03f6d added. We now have 3 listener(s)
,08-11 17:53:06.545  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 17:53:06.546  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:53:06.546  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:53:06.547  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:53:06.547  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ac67a2 added. We now have 4 listener(s)
08-11 17:53:06.547  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:53:06.549  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:53:06.558  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:53:06.567  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:53:06.570  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:53:06.570  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:53:06.571  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:53:06.571  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:53:06.571  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:53:06.571  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:06.571  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:06.571  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:06.572  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 17:53:06.572  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b03f6d removed from the list
08-11 17:53:06.572  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:06.572  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ac67a2 removed from the list
08-11 17:53:06.577  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:53:06.578  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:53:06.578  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:06.578  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:06.578  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:53:06.587  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:06.587  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:53:06.587  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:53:06.589  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:53:06.589  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ac67a2 not in the list
,08-11 17:53:06.590  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:06.590  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:53:06.592  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:53:06.592  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:06.593  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:06.593  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ac67a2 not in the list
,08-11 17:53:06.593  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:06.594  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:53:06.594  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:06.594  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b03f6d not in the list
08-11 17:53:06.596  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:53:06.596  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6e0bf0 added. We now have 3 listener(s)
,08-11 17:53:06.601  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 17:53:06.601  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:53:06.602  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:53:06.602  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:53:06.602  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51e6569 added. We now have 4 listener(s)
,08-11 17:53:06.602  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:53:06.603  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:53:06.609  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:53:06.618  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:53:06.623  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:53:06.624  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:53:06.625  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 17:53:06.625  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:53:06.625  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 17:53:06.625  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:53:06.625  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:53:06.627  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:53:06.630  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:53:06.634  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 17:53:06.634  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 17:53:06.647  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:53:06.649  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 17:53:06.649  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 17:53:06.660  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 17:53:06.661  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 17:53:06.661  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 17:53:06.663  3694  3740 D BluetoothAdapter: STATE_ON
,08-11 17:53:06.671  4056  4067 D BtGatt.GattService: registerClient() - UUID=de296d49-5da3-4a02-91d7-9447ddd5d95f
,08-11 17:53:06.672  4056  4072 D BtGatt.GattService: onClientRegistered() - UUID=de296d49-5da3-4a02-91d7-9447ddd5d95f, clientIf=5
08-11 17:53:06.673  3694  3704 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 17:53:06.675  4056  4094 D BtGatt.GattService: start scan with filters
,08-11 17:53:06.682  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 17:53:06.682  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 17:53:06.682  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-11 17:53:06.683  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-11 17:53:06.683  4056  4075 D BtGatt.ScanManager: handling starting scan
,08-11 17:53:06.687  4056  4075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fb14c0d
,08-11 17:53:06.696  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:53:06.696  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 17:53:06.697  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:53:06.704  4056  4072 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 17:53:06.704  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:53:06.705  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 17:53:06.705  4056  4075 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 17:53:06.716  3694  3740 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-11 17:53:06.716  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:53:06.717  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
,08-11 17:53:06.717  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:53:06.717  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 17:53:06.718  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-11 17:53:06.718  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 17:53:06.718  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-11 17:53:06.718  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 17:53:06.719  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 17:53:06.719  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:06.719  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 17:53:06.720  4056  4075 D BtGatt.ScanManager: Starting BLE batch scan
08-11 17:53:06.720  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-11 17:53:06.721  4056  4075 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-11 17:53:06.721  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:53:06.722  4056  4094 D BtGatt.GattService: stopScan() - queue size =1
08-11 17:53:06.723  4056  4066 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 17:53:06.723  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:53:06.724  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 17:53:06.724  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 17:53:06.724  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 17:53:06.724  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 17:53:06.727  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:53:06.727  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 17:53:06.728  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 17:53:06.728  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 17:53:06.729  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:06.730  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:53:06.730  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:53:06.730  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:53:06.743  4056  4072 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 17:53:06.743  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:06.751  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 17:53:06.751  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:06.760  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 17:53:06.761  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:06.761  4056  4075 D BtGatt.ScanManager: stopping BLe Batch
,08-11 17:53:06.767  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 17:53:06.768  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:06.768  4056  4075 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:53:06.776  4056  4072 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 17:53:06.776  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:07.233  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:53:07.234  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:53:07.234  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 17:53:09.733  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:53:09.734  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:53:09.734  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 17:53:09.735  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 17:53:09.735  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:09.736  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:09.736  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:53:09.736  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6e0bf0 removed from the list
08-11 17:53:09.737  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:53:09.737  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51e6569 removed from the list
08-11 17:53:09.737  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:53:09.738  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:53:09.739  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:09.740  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:09.743  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:09.743  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:53:09.744  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:53:09.744  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51e6569 not in the list
08-11 17:53:09.744  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:09.744  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:09.748  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:53:09.748  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:09.748  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:53:09.748  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51e6569 not in the list
08-11 17:53:09.749  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:09.749  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:09.749  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:09.749  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6e0bf0 not in the list
08-11 17:53:09.752  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:53:09.752  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7748fa added. We now have 3 listener(s)
08-11 17:53:09.754  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 17:53:09.754  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:53:09.754  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:53:09.754  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:53:09.754  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2626eab added. We now have 4 listener(s)
08-11 17:53:09.754  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:53:09.755  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:53:09.761  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:53:09.771  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:53:09.777  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:09.778  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 17:53:09.778  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 17:53:09.779  3694  3740 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-11 17:53:09.779  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-11 17:53:09.780  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 17:53:09.780  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-11 17:53:09.780  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 17:53:09.780  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:53:09.781  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-11 17:53:09.782  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-11 17:53:09.782  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-11 17:53:09.783  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:53:09.782  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 17:53:09.783  3694  4153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 17:53:09.783  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 17:53:09.784  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:53:09.784  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 17:53:09.787  3694  4153 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-11 17:53:09.787  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:53:09.788  3694  3694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-11 17:53:09.793  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 17:53:09.793  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 17:53:09.798  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:53:09.799  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 17:53:09.799  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 17:53:09.802  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-11 17:53:09.802  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 17:53:09.803  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-11 17:53:09.804  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 17:53:09.804  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 17:53:09.804  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-11 17:53:09.805  3694  3740 D BluetoothAdapter: STATE_ON
,08-11 17:53:09.808  4056  4067 D BtGatt.GattService: registerClient() - UUID=3926b4ed-86fc-4fbf-a6b1-140560629c5d
08-11 17:53:09.808  4056  4072 D BtGatt.GattService: onClientRegistered() - UUID=3926b4ed-86fc-4fbf-a6b1-140560629c5d, clientIf=5
08-11 17:53:09.809  3694  3705 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-11 17:53:09.811  4056  4074 D BtGatt.AdvertiseManager: message : 0
,08-11 17:53:09.816  4056  4074 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 17:53:09.827  4056  4072 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 17:53:09.834  4056  4072 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 17:53:09.836  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-11 17:53:09.836  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 17:53:09.838  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 17:53:09.840  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 17:53:09.840  3694  3694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-11 17:53:09.840  3694  3694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-11 17:53:09.841  3694  3694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-11 17:53:09.841  3694  3694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 17:53:09.841  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-11 17:53:09.844  3694  3694 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-11 17:53:09.844  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 17:53:10.345  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-11 17:53:10.346  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-11 17:53:10.346  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 17:53:12.842  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-11 17:53:12.842  3694  3740 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 17:53:12.843  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:53:12.844  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-11 17:53:12.844  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 17:53:12.844  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 17:53:12.845  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 17:53:12.845  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-11 17:53:12.849  3694  4153 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 17:53:12.849  3694  4153 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 17:53:12.850  3694  4153 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 17:53:12.850  3694  3694 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 17:53:12.852  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 17:53:12.852  3694  3740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-11 17:53:12.853  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:53:12.853  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 17:53:12.853  3694  3694 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 17:53:12.853  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 17:53:12.854  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 17:53:12.854  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 17:53:12.857  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:53:12.857  3694  3740 D BluetoothLeScanner: could not find callback wrapper
08-11 17:53:12.858  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 17:53:12.858  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-11 17:53:12.861  4056  4074 D BtGatt.AdvertiseManager: message : 1
08-11 17:53:12.862  4056  4074 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-11 17:53:12.871  4056  4072 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-11 17:53:12.871  4056  4072 D BtGatt.GattService: Client app is not null!
08-11 17:53:12.872  4056  4066 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 17:53:12.872  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 17:53:12.873  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-11 17:53:12.873  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 17:53:12.873  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-11 17:53:12.874  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-11 17:53:12.876  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 17:53:12.876  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 17:53:12.876  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 17:53:12.877  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:12.878  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:53:12.878  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 17:53:12.878  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:53:12.878  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:53:12.879  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:53:12.879  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:12.879  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:53:12.879  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:12.879  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:53:12.879  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7748fa removed from the list
08-11 17:53:12.879  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:12.879  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2626eab removed from the list
08-11 17:53:12.879  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 17:53:12.879  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:12.880  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:12.881  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 17:53:12.883  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 17:53:12.884  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:53:12.884  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:53:12.884  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2626eab not in the list
08-11 17:53:12.884  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:12.885  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:12.888  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 17:53:12.888  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:12.890  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 17:53:12.890  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2626eab not in the list
08-11 17:53:12.891  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:12.891  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:12.891  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:12.891  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7748fa not in the list
,08-11 17:53:12.893  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 17:53:12.893  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca0db4 added. We now have 3 listener(s)
,08-11 17:53:12.899  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 17:53:12.899  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:53:12.900  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:53:12.900  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 17:53:12.901  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdddd added. We now have 4 listener(s)
08-11 17:53:12.901  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 17:53:12.902  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 17:53:12.905  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:53:12.914  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 17:53:12.919  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 17:53:12.919  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:53:12.919  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:53:12.919  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 17:53:12.919  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 17:53:12.919  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:53:12.919  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 17:53:12.924  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:53:12.931  3694  3740 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 17:53:12.932  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 17:53:12.932  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 17:53:12.940  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 17:53:12.940  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 17:53:12.941  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 17:53:12.948  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-11 17:53:12.948  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-11 17:53:12.948  3694  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 17:53:12.949  3694  3740 D BluetoothAdapter: STATE_ON
,08-11 17:53:12.954  4056  4066 D BtGatt.GattService: registerClient() - UUID=a3024f00-0b9a-4254-ac26-131897df10b6
08-11 17:53:12.954  4056  4072 D BtGatt.GattService: onClientRegistered() - UUID=a3024f00-0b9a-4254-ac26-131897df10b6, clientIf=5
,08-11 17:53:12.955  3694  3705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 17:53:12.955  4056  4098 D BtGatt.GattService: start scan with filters
,08-11 17:53:12.960  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 17:53:12.960  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 17:53:12.960  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 17:53:12.960  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 17:53:12.961  4056  4075 D BtGatt.ScanManager: handling starting scan
08-11 17:53:12.964  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 17:53:12.964  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 17:53:12.965  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 17:53:12.967  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 17:53:12.971  4056  4072 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 17:53:12.972  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:12.972  4056  4075 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 17:53:12.983  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 17:53:12.984  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:53:12.984  4056  4075 D BtGatt.ScanManager: Starting BLE batch scan
08-11 17:53:12.985  4056  4075 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 17:53:13.012  4056  4072 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 17:53:13.012  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:13.040  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 17:53:13.041  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:13.380  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:53:13.466  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 17:53:13.467  3694  3694 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 17:53:13.467  3694  3694 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 17:53:14.549  4056  4056 D BtGatt.ScanManager: awakened up at time 487089
,08-11 17:53:14.551  4056  4075 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 17:53:14.602  4056  4072 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-11 17:53:14.602  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 17:53:14.602  4056  4072 D BtGatt.GattService: current time is 487142213484
,08-11 17:53:14.602  4056  4072 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 17:53:14.604  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 17:53:14.605  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 17:53:14.605  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 17:53:14.605  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 17:53:15.985  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 17:53:15.986  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:53:15.986  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 17:53:15.987  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:15.987  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 17:53:15.987  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 17:53:15.987  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 17:53:15.988  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 17:53:15.988  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 17:53:15.990  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 17:53:15.991  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 17:53:15.993  3694  3740 D BluetoothAdapter: STATE_ON
08-11 17:53:15.995  4056  4067 D BtGatt.GattService: stopScan() - queue size =1
,08-11 17:53:16.001  4056  4087 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 17:53:16.003  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 17:53:16.004  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 17:53:16.004  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 17:53:16.004  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 17:53:16.007  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 17:53:16.008  4056  4056 D BtGatt.ScanManager: awakened up at time 488548
,08-11 17:53:16.014  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:53:16.015  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-11 17:53:16.015  3694  3740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 17:53:16.016  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 17:53:16.017  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 17:53:16.020  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:16.021  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:53:16.021  4056  4072 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 17:53:16.021  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:16.021  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 17:53:16.021  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:53:16.021  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:53:16.022  4056  4075 D BtGatt.ScanManager: stopping BLe Batch
,08-11 17:53:16.022  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca0db4 removed from the list
08-11 17:53:16.023  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:16.022  3694  3694 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 17:53:16.023  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdddd removed from the list
08-11 17:53:16.023  3694  3694 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 17:53:16.023  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:53:16.024  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.025  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:16.025  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.027  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:16.027  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:53:16.028  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:16.028  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdddd not in the list
,08-11 17:53:16.028  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:16.028  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.030  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:53:16.030  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:16.030  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:16.031  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cdddd not in the list
08-11 17:53:16.031  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:16.031  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:16.031  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.031  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca0db4 not in the list
08-11 17:53:16.031  4056  4072 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 17:53:16.032  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:53:16.032  4056  4075 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-11 17:53:16.033  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 17:53:16.033  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fe9c9e added. We now have 3 listener(s)
,08-11 17:53:16.038  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 17:53:16.038  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 17:53:16.038  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 17:53:16.039  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 17:53:16.039  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755037f added. We now have 4 listener(s)
08-11 17:53:16.039  3694  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 17:53:16.041  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 17:53:16.045  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 17:53:16.053  3694  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 17:53:16.055  4056  4072 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
08-11 17:53:16.056  4056  4072 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 17:53:16.056  4056  4072 D BtGatt.GattService: current time is 488596198054
08-11 17:53:16.057  4056  4072 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 17:53:16.057  3694  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 17:53:16.058  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 17:53:16.058  3694  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 17:53:16.058  3694  3740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 17:53:16.058  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 17:53:16.060  3694  3740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 17:53:16.058  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-11 17:53:16.060  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:16.060  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:16.060  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 17:53:16.060  3694  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 17:53:16.060  3694  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fe9c9e removed from the list
08-11 17:53:16.060  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:16.061  3694  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755037f removed from the list
08-11 17:53:16.060  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 17:53:16.061  4056  4072 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 17:53:16.062  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:53:16.066  3694  3694 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 17:53:16.067  3694  3740 D io.jxcore.node.ConnectivityMonitor: stop
08-11 17:53:16.067  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.068  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 17:53:16.068  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.069  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:16.069  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:53:16.069  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:16.070  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755037f not in the list
08-11 17:53:16.070  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:16.070  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.072  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 17:53:16.072  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 17:53:16.072  3694  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 17:53:16.072  3694  3740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@755037f not in the list
08-11 17:53:16.072  3694  3740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 17:53:16.073  3694  3740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 17:53:16.073  3694  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 17:53:16.073  3694  3740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fe9c9e not in the list
,08-11 17:53:16.526  3694  3694 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 17:53:18.160   873  1703 I ActivityManager: Start proc 4155:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-11 17:53:18.259  4155  4155 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-11 17:53:18.354  4155  4167 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 17:53:18.509  4155  4167 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 17:53:18.557  4155  4167 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 17:53:18.602  4155  4155 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-11 17:53:18.789  4184  4184 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1258731584.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1258731584.dex
,08-11 17:53:18.813  4155  4155 W InstanceID/Rpc: Found 10011
,08-11 17:53:18.982  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:53:18.984  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 17:53:19.023  3922  4231 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 17:53:19.067  1492  1897 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 17:53:19.067  1492  1897 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 17:53:19.067  1492  1897 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 17:53:19.067  1492  1897 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 17:53:19.072  4184  4184 I dex2oat : dex2oat took 308.853ms (threads: 4) arena alloc=179KB java alloc=33KB native alloc=1258KB free=1557KB
,08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 17:53:19.125  3922  4231 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 17:53:19.129   873  1696 I ActivityManager: Killing 3552:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-11 17:53:21.076  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-11 17:53:21.077  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-11 17:53:21.078  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-11 17:53:21.078  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 17:53:21.078  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-11 17:53:21.079  3694  3740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-11 17:53:23.835  2877  4238 V KeepSync: Connecting to GoogleApiClient
08-11 17:53:23.836   873  1696 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 17:53:23.879  1492  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 17:53:23.879  1492  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 17:53:23.879  1492  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 17:53:23.879  1492  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 17:53:23.893  1803  4239 V BaseAuthAsyncOperation: access token request failed
,08-11 17:53:23.894  2877  4238 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 17:53:23.929  1492  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 17:53:23.930  1492  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 17:53:23.930  1492  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 17:53:23.930  1492  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 17:53:23.945  2877  4238 E KeepSync: IOException
08-11 17:53:23.945  2877  4238 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 17:53:23.945  2877  4238 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 17:53:23.945  2877  4238 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 17:53:23.945  2877  4238 E KeepSync: 	... 10 more
08-11 17:53:23.945  2877  4238 W KeepSync: Sync result 2
,08-11 17:53:23.959   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 496272, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 17:53:23.965   873  4113 D NetlinkSocketObserver: NeighborEvent{elapsedMs=496504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE},
,08-11 17:53:28.108  3694  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
,08-11 17:53:30.106  3694  3740 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 451
,08-11 17:53:30.107  3694  3740 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 451, name: My test thread name)
,08-11 17:53:30.113  3694  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
08-11 17:53:30.114  3694  4241 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: My test thread name)
,08-11 17:53:30.114  3694  4241 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-11 17:53:30.118  3694  3740 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 17:53:30.127  3694  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,08-11 17:53:30.128  3694  4242 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 456, thread name: My test thread name): Test exception.
,08-11 17:53:30.128  3694  4242 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-11 17:53:30.131  3694  4240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-11 17:53:30.137  3694  3740 I jxcore-log: Total number of executed tests:  82
08-11 17:53:30.137  3694  3740 I jxcore-log: 
,08-11 17:53:30.137  3694  3740 I jxcore-log: Number of passed tests:  82
08-11 17:53:30.137  3694  3740 I jxcore-log: 
,08-11 17:53:30.138  3694  3740 I jxcore-log: Number of failed tests:  0
08-11 17:53:30.138  3694  3740 I jxcore-log: 
,08-11 17:53:30.138  3694  3740 I jxcore-log: Number of ignored tests:  0
08-11 17:53:30.138  3694  3740 I jxcore-log: 
,08-11 17:53:30.141  3694  3740 I jxcore-log: Total duration:  140584
08-11 17:53:30.141  3694  3740 I jxcore-log: 
,08-11 17:53:30.142  3694  3740 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 17:53:30.142  3694  3740 I jxcore-log: 
,08-11 17:53:30.150  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.150  3694  3740 I jxcore-log: 
08-11 17:53:30.153  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.153  3694  3740 I jxcore-log: 
08-11 17:53:30.155  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.155  3694  3740 I jxcore-log: 
08-11 17:53:30.157  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.157  3694  3740 I jxcore-log: 
08-11 17:53:30.158  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 17:53:30.158  3694  3740 I jxcore-log: 
08-11 17:53:30.160  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:53:30.160  3694  3740 I jxcore-log: 
08-11 17:53:30.163  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.163  3694  3740 I jxcore-log: 
08-11 17:53:30.165  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.165  3694  3740 I jxcore-log: 
08-11 17:53:30.166  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 17:53:30.166  3694  3740 I jxcore-log: 
08-11 17:53:30.167  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:53:30.167  3694  3740 I jxcore-log: 
08-11 17:53:30.168  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:53:30.168  3694  3740 I jxcore-log: 
08-11 17:53:30.169  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.169  3694  3740 I jxcore-log: 
08-11 17:53:30.170  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.170  3694  3740 I jxcore-log: 
08-11 17:53:30.171  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.171  3694  3740 I jxcore-log: 
08-11 17:53:30.172  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.172  3694  3740 I jxcore-log: 
,08-11 17:53:30.173  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.173  3694  3740 I jxcore-log: 
,08-11 17:53:30.174  3694  3694 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-11 17:53:30.174  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.174  3694  3740 I jxcore-log: 
08-11 17:53:30.175  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.175  3694  3740 I jxcore-log: 
08-11 17:53:30.176  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.176  3694  3740 I jxcore-log: 
08-11 17:53:30.177  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.177  3694  3740 I jxcore-log: 
,08-11 17:53:30.178  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.178  3694  3740 I jxcore-log: 
08-11 17:53:30.179  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.179  3694  3740 I jxcore-log: 
08-11 17:53:30.179  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.179  3694  3740 I jxcore-log: 
,08-11 17:53:30.180  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.180  3694  3740 I jxcore-log: 
,08-11 17:53:30.181  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.181  3694  3740 I jxcore-log: 
08-11 17:53:30.182  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.182  3694  3740 I jxcore-log: 
,08-11 17:53:30.183  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.183  3694  3740 I jxcore-log: 
08-11 17:53:30.184  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.184  3694  3740 I jxcore-log: 
,08-11 17:53:30.184  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.184  3694  3740 I jxcore-log: 
,08-11 17:53:30.185  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.185  3694  3740 I jxcore-log: 
08-11 17:53:30.186  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.186  3694  3740 I jxcore-log: 
08-11 17:53:30.186  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.186  3694  3740 I jxcore-log: 
,08-11 17:53:30.188  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.188  3694  3740 I jxcore-log: 
,08-11 17:53:30.189  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.189  3694  3740 I jxcore-log: 
08-11 17:53:30.189  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.189  3694  3740 I jxcore-log: 
,08-11 17:53:30.190  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.190  3694  3740 I jxcore-log: 
,08-11 17:53:30.191  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.191  3694  3740 I jxcore-log: 
08-11 17:53:30.191  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.191  3694  3740 I jxcore-log: 
08-11 17:53:30.192  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.192  3694  3740 I jxcore-log: 
08-11 17:53:30.192  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.192  3694  3740 I jxcore-log: 
08-11 17:53:30.192  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-11 17:53:30.192  3694  3740 I jxcore-log: 
,08-11 17:53:30.193  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.193  3694  3740 I jxcore-log: 
,08-11 17:53:30.193  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.193  3694  3740 I jxcore-log: 
,08-11 17:53:30.194  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-11 17:53:30.194  3694  3740 I jxcore-log: 
08-11 17:53:30.194  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.194  3694  3740 I jxcore-log: 
08-11 17:53:30.195  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.195  3694  3740 I jxcore-log: 
08-11 17:53:30.196  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.196  3694  3740 I jxcore-log: 
,08-11 17:53:30.196  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.196  3694  3740 I jxcore-log: 
08-11 17:53:30.197  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:53:30.197  3694  3740 I jxcore-log: 
08-11 17:53:30.197  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.197  3694  3740 I jxcore-log: 
08-11 17:53:30.198  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-11 17:53:30.198  3694  3740 I jxcore-log: 
08-11 17:53:30.198  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.198  3694  3740 I jxcore-log: 
,08-11 17:53:30.198  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:53:30.198  3694  3740 I jxcore-log: 
08-11 17:53:30.199  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-11 17:53:30.199  3694  3740 I jxcore-log: 
08-11 17:53:30.199  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 17:53:30.199  3694  3740 I jxcore-log: 
08-11 17:53:30.200  3694  3740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-11 17:53:30.200  3694  3740 I jxcore-log: 
,08-11 17:53:30.818  4243  4243 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 17:53:30.823  4243  4243 D AndroidRuntime: CheckJNI is OFF
,08-11 17:53:30.858  4243  4243 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 17:53:30.900  4243  4243 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 17:53:30.922  4243  4243 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 17:53:30.933   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-11 17:53:30.934   873   886 I ActivityManager: Killing 3694:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-11 17:53:31.052   873  1374 D GraphicsStats: Buffer count: 2
,08-11 17:53:31.052   873  1696 I WindowState: WIN DEATH: Window{60fa44 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 17:53:31.053   873  1309 D WifiService: Client connection lost with reason: 4
,08-11 17:53:31.069   873   896 W PackageSettings: Skipping PackageSetting{203fc06 com.example.hello/10273} due to missing metadata
,08-11 17:53:31.114   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-11 17:53:31.114   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-11 17:53:31.115   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-11 17:53:31.115   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-11 17:53:31.115   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:53:31.115   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.115   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 17:53:31.115   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 17:53:31.115   873   886 I ActivityManager:   Force finishing activity ActivityRecord{cf50249 u0 com.test.thalitest/.MainActivity t2}
,08-11 17:53:31.122   873  1374 W ActivityManager: Spurious death for ProcessRecord{bfaa566 0:com.test.thalitest/u0a0}, curProc for 3694: null
,08-11 17:53:31.124   873   896 I art     : Starting a blocking GC Explicit
,08-11 17:53:31.164   873   896 I art     : Explicit concurrent mark sweep GC freed 27511(1752KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 695us total 39.333ms
,08-11 17:53:31.183   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 17:53:31.191  4243  4243 I art     : System.exit called, status: 0
,08-11 17:53:31.191   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-11 17:53:31.191  4243  4243 I AndroidRuntime: VM exiting with result code 0.
,08-11 17:53:31.223   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-11 17:53:31.230  4056  4056 D BluetoothMapAppObserver: onReceive
,08-11 17:53:31.230  4056  4056 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 17:53:31.233  1704  2014 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 17:53:31.242  3487  3487 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-11 17:53:31.244   873  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 17:53:31.260  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-11 17:53:31.263  1662  4256 I Keyboard.Facilitator.DecoderInitializer: run()
,08-11 17:53:31.270   873  1693 I ActivityManager: Start proc 4257:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-11 17:53:31.278  1760  1760 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 17:53:31.288  1662  4256 I Decoder : createOrResetDecoder
,08-11 17:53:31.304  4257  4257 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-11 17:53:31.318  1492  1492 I ConfigService: onCreate
,08-11 17:53:31.328  1492  4269 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 17:53:31.328  1492  4269 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 17:53:31.328  1492  4269 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-11 17:53:31.331  1492  4269 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-11 17:53:31.332   873  1780 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3694 uid 10000
,08-11 17:53:31.333  1662  1662 I Keyboard.Facilitator: onFinishInput()
,08-11 17:53:31.336   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 17:53:31.349  1772  1865 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-11 17:53:31.350   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 17:53:31.350   873   885 E PackageManager: Failed to write settings, restoring backup
08-11 17:53:31.350   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 17:53:31.350   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 17:53:31.350   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 17:53:31.350   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 17:53:31.350   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 17:53:31.350   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:53:31.350   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.350   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 17:53:31.353  1662  4256 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-11 17:53:31.355   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-11 17:53:31.355   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 17:53:31.355   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 17:53:31.355   873   886 E DropBoxManagerService: 	... 13 more
,08-11 17:53:31.361   873  1749 I ActivityManager: Start proc 4271:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-11 17:53:31.362  1772  1865 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 17:53:31.362  1772  1865 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1772
08-11 17:53:31.362  1772  1865 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.362  1772  1865 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 17:53:31.364   873  1374 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 17:53:31.364   873  4276 E DropBoxManagerService: Can't write: system_app_crash
08-11 17:53:31.364   873  4276 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 17:53:31.364   873  4276 E DropBoxManagerService: 	... 5 more
,08-11 17:53:31.371  1772  1865 I Process : Sending signal. PID: 1772 SIG: 9
,08-11 17:53:31.513  1662  4256 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-11 17:53:31.515  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-11 17:53:31.515  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-11 17:53:31.519  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-11 17:53:31.519  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-11 17:53:31.520  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-11 17:53:31.520  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-11 17:53:31.525  1662  4256 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-11 17:53:31.525  1662  4256 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 17:53:31.525  1662  4256 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 17:53:31.526  1662  4256 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-11 17:53:31.526  1662  4256 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 17:53:31.526  1662  4256 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-11 17:53:31.540   873   883 D GraphicsStats: Buffer count: 1
,08-11 17:53:31.540   873  1703 I WindowState: WIN DEATH: Window{7c90eb9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-11 17:53:31.556   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1772) has died
,08-11 17:53:31.556   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-11 17:53:31.558   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-11 17:53:31.576  4257  4257 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-11 17:53:31.578   873   886 I ActivityManager: Start proc 4290:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 17:53:31.584  1803  4289 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-11 17:53:31.585  1803  4289 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 17:53:31.595  4257  4285 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.595  4257  4285 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.595  4257  4285 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 17:53:31.607   873  1696 I ActivityManager: Start proc 4301:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-11 17:53:31.617  4257  4307 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-11 17:53:31.643  4290  4290 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:53:31.643  4290  4290 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 17:53:31.644  4290  4290 D AndroidRuntime: Shutting down VM
,08-11 17:53:31.650  4301  4301 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-11 17:53:31.654  4290  4290 E AndroidRuntime: FATAL EXCEPTION: main
08-11 17:53:31.654  4290  4290 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4290
08-11 17:53:31.654  4290  4290 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 17:53:31.654  4290  4290 E AndroidRuntime: 	... 10 more
08-11 17:53:31.656   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-11 17:53:31.657  4290  4290 I Process : Sending signal. PID: 4290 SIG: 9
08-11 17:53:31.658   873  4315 E DropBoxManagerService: Can't write: system_app_crash
08-11 17:53:31.658   873  4315 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 17:53:31.658   873  4315 E DropBoxManagerService: 	... 5 more
08-11 17:53:31.665  1803  4289 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-11 17:53:31.665  1803  4289 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-11 17:53:31.682  1492  1492 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-11 17:53:31.684   873  1700 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4290) has died
,08-11 17:53:31.686   873  1700 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
