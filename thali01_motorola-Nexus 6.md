#### Test 807613740d5db28_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 14:43:57.325   875  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=328919, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 14:43:59.122  3828  3828 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 14:43:59.127  3828  3828 D AndroidRuntime: CheckJNI is OFF
08-16 14:43:59.162  3828  3828 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 14:43:59.206  3828  3828 I Radio-JNI: register_android_hardware_Radio DONE
08-16 14:43:59.226  3828  3828 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 14:43:59.231   875  1709 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 14:43:59.297   875  1709 I ActivityManager: Start proc 3837:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 14:43:59.303  3828  3828 D AndroidRuntime: Shutting down VM
08-16 14:43:59.454  3837  3837 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 14:43:59.481  3837  3837 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 14:43:59.489  3837  3837 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1081-1084)
08-16 14:43:59.489  3837  3837 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:43:59.507  3837  3837 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd020c8}
08-16 14:43:59.507  3837  3837 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:43:59.507  3837  3837 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:43:59.513  3837  3837 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 14:43:59.519  3837  3837 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 14:43:59.541  3837  3837 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 14:43:59.551  3837  3837 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:43:59.551  3837  3837 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:43:59.551  3837  3837 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 14:43:59.551  3837  3837 I Adreno  : Build Date                       : 10/20/15
08-16 14:43:59.551  3837  3837 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 14:43:59.551  3837  3837 I Adreno  : Local Branch                     : M14
08-16 14:43:59.551  3837  3837 I Adreno  : Remote Branch                    : 
08-16 14:43:59.551  3837  3837 I Adreno  : Remote Branch                    : 
08-16 14:43:59.551  3837  3837 I Adreno  : Reconstruct Branch               : 
,08-16 14:43:59.652   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f37749:true
,08-16 14:43:59.714  3837  3837 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 14:43:59.736  3837  3837 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 14:43:59.835  3837  3874 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 14:43:59.858  3837  3861 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 14:43:59.903  3837  3874 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 14:43:59.997   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +623ms (total +719ms)
,08-16 14:44:00.000  1857  1857 I Keyboard.Facilitator: onFinishInput()
,08-16 14:44:00.117  3837  3837 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3837
,08-16 14:44:00.254  3837  3837 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 14:44:00.439  3837  3877 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1682306768
,08-16 14:44:00.447  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 14:44:00.447  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 14:44:00.447  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 14:44:00.447  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 14:44:00.447  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 14:44:00.447  3837  3877 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c409ff added. We now have 1 listener(s)
,08-16 14:44:00.452  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-16 14:44:00.453  3837  3877 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:44:00.454  3837  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:44:00.454  3837  3877 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 14:44:00.459  3837  3877 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f797d2a added. We now have 1 listener(s)
08-16 14:44:00.459  3837  3877 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:44:00.465   875  1305 D WifiService: New client listening to asynchronous messages
,08-16 14:44:00.469  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:44:00.469  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 14:44:00.469  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 14:44:00.470  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 14:44:00.470  3837  3877 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 14:44:00.478  3837  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:00.479  3837  3877 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 14:44:00.491  3837  3877 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:00.492  3837  3877 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:00.492  3837  3877 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-16 14:44:00.492  3837  3877 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:44:00.495  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:00.495  3837  3877 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 14:44:00.497  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:00.534  3837  3837 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 14:44:00.989  3837  3846 I art     : Background sticky concurrent mark sweep GC freed 71833(6MB) AllocSpace objects, 17(1116KB) LOS objects, 27% free, 23MB/32MB, paused 735us total 101.879ms
,08-16 14:44:01.961  3837  3884 W jxcore-log: Initializing JXcore engine
,08-16 14:44:01.961  3837  3884 W jxcore-log: JXcore engine is ready
,08-16 14:44:01.996  3884  3884 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 14:44:01.996  3884  3884 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11887]" dev="sockfs" ino=11887 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 14:44:01.996  3884  3884 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 14:44:01.996  3884  3884 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28210]" dev="sockfs" ino=28210 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 14:44:02.011  3837  3884 W jxcore-log: Starting JXcore engine
,08-16 14:44:02.087  3837  3884 W jxcore-log: Platform android
08-16 14:44:02.087  3837  3884 W jxcore-log: 
,08-16 14:44:02.088  3837  3884 W jxcore-log: Process ARCH arm
08-16 14:44:02.088  3837  3884 W jxcore-log: 
,08-16 14:44:02.296  3837  3884 I jxcore-log: JXcore Cordova bridge is ready!
08-16 14:44:02.296  3837  3884 I jxcore-log: 
,08-16 14:44:02.297  3837  3884 W jxcore-log: JXcore engine is started
,08-16 14:44:02.308  3837  3877 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 14:44:02.315  3837  3837 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 14:44:10.909  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:44:10.919  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:44:10.925  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:44:10.986  1503  2033 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-16 14:44:10.986  1503  2033 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-16 14:44:10.987  1503  2033 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:44:10.987  1503  2033 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:44:11.027  1503  2033 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 14:44:11.027  1503  2033 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 14:44:11.027  1503  2033 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 14:44:11.027  1503  2033 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 14:44:11.027  1503  2033 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 14:44:11.027  1503  2033 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 14:44:11.027  1503  2033 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 14:44:11.032  3525  3556 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 14:44:11.032  3525  3556 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-16 14:44:11.032  3525  3556 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-16 14:44:11.032  3525  3556 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-16 14:44:11.032  3525  3556 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-16 14:44:11.032  3525  3556 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-16 14:44:11.032  3525  3556 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 14:44:17.861  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 14:44:17.861  3837  3884 I jxcore-log: 
,08-16 14:44:17.864  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 14:44:17.864  3837  3884 I jxcore-log: 
,08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:17.882  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:17.889  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:17.895  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 14:44:17.895  3837  3884 I jxcore-log: 
,08-16 14:44:17.902  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 14:44:17.902  3837  3884 I jxcore-log: 
,08-16 14:44:18.273  3837  3884 I jxcore-log: Running unit tests
08-16 14:44:18.273  3837  3884 I jxcore-log: 
,08-16 14:44:18.273  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:44:18.273  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@624f7e1 added. We now have 2 listener(s)
,08-16 14:44:18.275  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:44:18.275  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:44:18.275  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:44:18.275  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:44:18.275  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4a4906 added. We now have 2 listener(s)
08-16 14:44:18.275  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:44:18.276  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:44:18.278  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:18.288  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:18.290  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:18.290  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:44:18.291  3837  3884 D ExecuteNativeTests: Running unit tests
,08-16 14:44:18.297  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:18.305  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:18.350  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:44:18.350  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 added. We now have 3 listener(s)
,08-16 14:44:18.351  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:44:18.351  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:44:18.351  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:44:18.351  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:44:18.351  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d added. We now have 3 listener(s)
08-16 14:44:18.351  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:44:18.352  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:44:18.353  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:18.368  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:18.369  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:18.369  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:44:18.371  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:44:18.373  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 14:44:18.373  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:44:18.373  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:44:18.374  3837  3884 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 14:44:18.375  3837  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:44:18.375  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:44:18.375  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:44:18.375  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:44:18.375  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 14:44:18.375  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:18.376  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:18.376  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:18.376  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:18.376  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:18.376  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:44:18.376  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:44:18.376  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 removed from the list
08-16 14:44:18.376  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:18.377  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d removed from the list
08-16 14:44:18.379  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:18.391  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:18.392  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:18.392  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:18.393  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.393  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.394  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:18.394  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:18.394  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:18.394  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:18.396  3837  3884 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 14:44:18.396  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:18.396  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:18.396  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:18.397  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:18.397  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.397  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.397  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:18.397  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:18.397  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:18.397  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:44:18.397  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.397  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.397  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.397  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.398  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:18.398  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:18.398  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:18.398  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:18.402  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:44:18.402  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 14:44:18.402  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:44:18.402  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:44:18.402  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:44:18.403  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:44:18.404  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:44:18.404  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:44:18.404  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:44:18.404  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:44:18.404  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:44:18.404  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 14:44:18.404  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:18.404  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:18.404  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:18.404  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:18.404  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.404  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.404  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:18.404  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:18.404  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:18.405  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:18.405  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.405  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.405  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:18.405  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:18.406  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:18.406  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:18.406  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:18.406  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:18.407  3837  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:44:18.409  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:18.414  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:18.416  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:18.416  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:44:18.417  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:44:18.417  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:44:18.417  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 14:44:18.418  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:44:18.418  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:44:18.420  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:18.425  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:18.428  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 14:44:18.428  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:44:18.434  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:44:18.436  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:44:18.436  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:44:18.440  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 14:44:18.442  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 14:44:18.443  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 14:44:18.443  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:44:18.443  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:44:18.444  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:44:18.449  2666  2794 D BtGatt.GattService: registerClient() - UUID=5da0b27a-307f-454d-8f0b-3c8aee53a3e0
08-16 14:44:18.450  2666  2686 D BtGatt.GattService: onClientRegistered() - UUID=5da0b27a-307f-454d-8f0b-3c8aee53a3e0, clientIf=5
,08-16 14:44:18.452  3837  3876 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 14:44:18.453  2666  2678 D BtGatt.GattService: start scan with filters
,08-16 14:44:18.459  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 14:44:18.459  2666  2701 D BtGatt.ScanManager: handling starting scan
08-16 14:44:18.459  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:44:18.459  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:44:18.459  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:44:18.463  2666  2701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:44:18.465  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:44:18.465  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:44:18.466  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:44:18.468  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:44:18.473  2666  2686 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 14:44:18.473  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:18.475  2666  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:44:18.477  3837  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 14:44:18.487  2666  2686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:44:18.488  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:18.488  2666  2701 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:44:18.489  2666  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:44:18.502  2666  2686 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:44:18.503  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:18.513  2666  2686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:44:18.514  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:18.969  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 14:44:18.970  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-16 14:44:18.970  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:44:20.023  2666  2666 D BtGatt.ScanManager: awakened up at time 351618
08-16 14:44:20.025  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:20.060  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-16 14:44:20.060  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:20.060  2666  2686 D BtGatt.GattService: current time is 351655930994
08-16 14:44:20.061  2666  2686 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -90, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 85, -113, -37, 31, -33, 8, 0, -128, -85, 0, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
08-16 14:44:20.062  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 14:44:20.064  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 14:44:20.065  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 14:44:20.065  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-16 14:44:20.066  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-16 14:44:20.066  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-16 14:44:21.569  2666  2666 D BtGatt.ScanManager: awakened up at time 353164
,08-16 14:44:21.573  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-16 14:44:21.582  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:44:21.583  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:23.089  2666  2666 D BtGatt.ScanManager: awakened up at time 354683
,08-16 14:44:23.092  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:23.105  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:44:23.105  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:23.490  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:44:23.490  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:23.491  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:44:23.491  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:23.492  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:44:23.493  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 14:44:23.493  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:44:23.493  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:44:23.493  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:44:23.495  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:44:23.495  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:44:23.498  3837  3884 D BluetoothAdapter: STATE_ON
08-16 14:44:23.501  2666  2678 D BtGatt.GattService: stopScan() - queue size =1
08-16 14:44:23.503  2666  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:44:23.505  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:44:23.505  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:44:23.505  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:44:23.506  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:44:23.506  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:44:23.510  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:44:23.513  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:44:23.513  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 14:44:23.514  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:44:23.516  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:44:23.518  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:44:23.519  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:44:23.519  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:44:23.519  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:44:23.519  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:23.519  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:44:23.519  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:23.519  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:23.519  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:23.519  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:23.519  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:23.523  2666  2686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 14:44:23.523  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:23.524  2666  2701 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:44:23.531  2666  2686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:44:23.532  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:23.532  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:23.542  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:44:23.542  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:24.023  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:44:28.521  3837  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 14:44:28.528  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:28.547  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:28.557  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:28.558  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:44:28.559  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:44:28.559  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 14:44:28.560  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:44:28.561  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:44:28.561  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:44:28.567  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:28.577  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 14:44:28.577  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:44:28.577  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:28.589  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:44:28.591  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 14:44:28.591  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:44:28.600  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:44:28.600  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:44:28.600  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:44:28.602  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:44:28.607  2666  2794 D BtGatt.GattService: registerClient() - UUID=0db78a3b-0919-405d-be75-67a749084bae
,08-16 14:44:28.608  2666  2686 D BtGatt.GattService: onClientRegistered() - UUID=0db78a3b-0919-405d-be75-67a749084bae, clientIf=5
,08-16 14:44:28.609  3837  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:44:28.609  2666  2676 D BtGatt.GattService: start scan with filters
,08-16 14:44:28.617  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 14:44:28.617  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:44:28.617  2666  2701 D BtGatt.ScanManager: handling starting scan
08-16 14:44:28.618  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 14:44:28.618  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:44:28.629  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:44:28.630  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:44:28.630  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:44:28.635  2666  2686 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 14:44:28.636  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:28.637  2666  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:44:28.639  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:44:28.646  3837  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 14:44:28.654  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:44:28.654  3837  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 14:44:28.654  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:28.655  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 14:44:28.655  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:28.656  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:44:28.656  2666  2686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 14:44:28.656  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:28.657  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,08-16 14:44:28.657  2666  2701 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 14:44:28.657  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:44:28.657  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:44:28.657  2666  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:44:28.657  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:44:28.659  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:44:28.659  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:44:28.662  3837  3884 D BluetoothAdapter: STATE_ON
08-16 14:44:28.664  2666  2794 D BtGatt.GattService: stopScan() - queue size =1
08-16 14:44:28.668  2666  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:44:28.669  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:44:28.669  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:44:28.670  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:44:28.670  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:44:28.670  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:44:28.674  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:44:28.674  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 14:44:28.675  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 14:44:28.675  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:44:28.676  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:44:28.679  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:44:28.679  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:44:28.680  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:28.680  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:44:28.680  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:44:28.680  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:28.680  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:44:28.680  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:28.681  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:28.681  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:28.681  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:28.682  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:28.683  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:28.687  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:28.687  2666  2686 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:44:28.687  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:28.687  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:28.688  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:28.688  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:28.691  3837  3884 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 14:44:28.694  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:28.703  2666  2686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:44:28.703  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:28.703  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:28.708  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:28.708  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:44:28.709  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:44:28.709  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 14:44:28.709  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:44:28.709  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:28.709  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:44:28.713  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:28.716  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 14:44:28.717  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 14:44:28.720  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:28.721  2666  2686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:44:28.721  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:28.722  2666  2701 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:44:28.728  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:44:28.730  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 14:44:28.730  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:44:28.735  2666  2686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 14:44:28.736  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:28.736  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:28.738  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 14:44:28.738  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 14:44:28.739  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:44:28.741  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:44:28.747  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:44:28.747  2666  2676 D BtGatt.GattService: registerClient() - UUID=41c056bf-10ea-45a2-9662-a3c099be46ce
08-16 14:44:28.747  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:28.748  2666  2686 D BtGatt.GattService: onClientRegistered() - UUID=41c056bf-10ea-45a2-9662-a3c099be46ce, clientIf=5
08-16 14:44:28.749  3837  3876 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:44:28.749  2666  2794 D BtGatt.GattService: start scan with filters
,08-16 14:44:28.757  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:44:28.757  2666  2701 D BtGatt.ScanManager: handling starting scan
,08-16 14:44:28.757  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:44:28.758  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:44:28.758  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:44:28.763  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:44:28.764  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:44:28.764  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:44:28.768  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:44:28.771  2666  2686 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 14:44:28.772  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:28.772  2666  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:44:28.773  3837  3884 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 14:44:28.785  2666  2686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 14:44:28.785  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:28.786  2666  2701 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:44:28.786  2666  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:44:28.810  2666  2686 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:44:28.810  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:28.824  2666  2686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:44:28.824  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:29.268  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-16 14:44:29.269  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:44:29.269  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:44:30.333  2666  2666 D BtGatt.ScanManager: awakened up at time 361927
,08-16 14:44:30.336  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:30.387  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 14:44:30.387  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:30.388  2666  2686 D BtGatt.GattService: current time is 361983026205
,08-16 14:44:30.389  2666  2686 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -88, 8, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -91, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 14:44:30.390  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-16 14:44:30.391  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 14:44:30.392  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 14:44:30.393  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 14:44:31.892  2666  2666 D BtGatt.ScanManager: awakened up at time 363487
,08-16 14:44:31.894  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:31.906  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:44:31.906  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:33.411  2666  2666 D BtGatt.ScanManager: awakened up at time 365006
,08-16 14:44:33.413  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:33.432  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:44:33.432  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:44:33.777  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:33.778  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:33.778  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:44:33.779  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:33.779  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:44:33.779  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:44:33.779  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:44:33.780  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:44:33.780  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:44:33.781  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:44:33.781  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:44:33.784  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:44:33.787  2666  2676 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:44:33.791  2666  2678 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:44:33.792  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:44:33.793  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:44:33.793  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:44:33.793  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:44:33.794  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 14:44:33.797  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:44:33.798  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 14:44:33.798  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:44:33.798  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:44:33.799  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:44:33.803  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:44:33.803  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:44:33.804  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:44:33.809  2666  2686 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 14:44:33.809  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:33.809  2666  2701 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:44:33.826  2666  2686 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 14:44:33.826  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:33.827  2666  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:44:33.864  2666  2686 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-16 14:44:33.865  2666  2686 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:44:33.865  2666  2686 D BtGatt.GattService: current time is 365460746902
,08-16 14:44:33.866  2666  2686 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, -128, -87, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 0]
08-16 14:44:33.867  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 14:44:33.868  2666  2686 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103]
,08-16 14:44:34.305  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 14:44:34.306  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:34.306  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:44:35.924   875  2074 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367519, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 14:44:38.806  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:44:38.806  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.807  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.808  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:44:38.808  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.809  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:44:38.810  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.810  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.811  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.811  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:44:38.812  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:38.815  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.815  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:38.819  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 14:44:38.819  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:44:38.820  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.820  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:38.822  3837  3884 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 14:44:38.824  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.826  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:38.826  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.827  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.827  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.827  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:38.827  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.827  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.827  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:38.827  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.827  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.827  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.827  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:38.827  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.830  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.830  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:44:38.830  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.830  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.831  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 14:44:38.831  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.831  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:38.831  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.832  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.832  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.832  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.832  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.832  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.832  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.832  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.832  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.832  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.832  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.832  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.835  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.835  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.835  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.835  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.836  3837  3884 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 14:44:38.836  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.836  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.836  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.836  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.836  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.836  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.836  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.836  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.837  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.837  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.837  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not ,exist in the list - probably already removed
08-16 14:44:38.837  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.837  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.837  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.838  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.838  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.838  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.838  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.839  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 14:44:38.839  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.839  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.839  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.840  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.840  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.840  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.840  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.840  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.840  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.840  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.840  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.840  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.840  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.840  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.842  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.843  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.843  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.843  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.843  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:44:38.844  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:44:38.844  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:44:38.844  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:44:38.844  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:44:38.844  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:44:38.844  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:44:38.844  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:44:38.844  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:44:38.844  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.844  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.845  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.845  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.845  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.845  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.845  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.845  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.845  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.845  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.845  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.845  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.845  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.845  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.847  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.847  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.847  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.847  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.848  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:44:38.848  3837  3884 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:44:38.848  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:44:38.853  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:44:38.853  3837  3884 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:44:38.853  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:44:38.854  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:44:38.855  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:44:38.856  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:44:38.856  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:44:38.856  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:44:38.856  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:44:38.856  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 14:44:38.856  3837  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:44:38.856  3837  3884 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 14:44:38.857  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:44:38.857  3837  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:44:38.857  3837  3884 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 14:44:38.857  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:44:38.857  3837  3884 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:44:38.857  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 14:44:38.862  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 14:44:38.864  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 14:44:38.864  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 14:44:38.866  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 14:44:38.866  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 14:44:38.867  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 14:44:38.867  3837  3884 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:44:38.868  3837  3884 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 14:44:38.868  3837  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
08-16 14:44:38.870  3837  3890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:44:38.872  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.872  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.872  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.874  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:44:38.874  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.875  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.876  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 14:44:38.878  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.878  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.878  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.878  3837  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
08-16 14:44:38.878  3837  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
08-16 14:44:38.878  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.879  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.879  3837  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
08-16 14:44:38.879  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.879  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.879  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.880  2666  2791 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-16 14:44:38.880  3837  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
08-16 14:44:38.882  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.882  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.882  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.882  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.883  3837  3884 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 14:44:38.884  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.884  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.884  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.884  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.885  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.885  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.885  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.885  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.885  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.885  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.885  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.885  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.885  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.885  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.887  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.887  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.887  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.888  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.888  3837  3884 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 14:44:38.888  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.889  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.889  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.889  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.889  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.889  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.889  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.889  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.889  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.889  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.889  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.890  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.890  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.890  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.891  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.891  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.891  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.891  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.892  3837  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 14:44:38.892  3837  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 14:44:38.892  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:44:38.892  3837  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 14:44:38.892  3837  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:44:38.892  3837  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 14:44:38.892  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:44:38.892  3837  3884 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 14:44:38.893  3837  3884 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:44:38.893  3837  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:44:38.893  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:44:38.893  3837  3884 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 14:44:38.893  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:38.893  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:38.893  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:38.893  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.893  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.894  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.894  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.894  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.894  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.894  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.894  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.894  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.894  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.894  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.895  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:38.895  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:38.895  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.895  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.896  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:38.896  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.896  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:38.896  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:38.896  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:38.896  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:38.896  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:38.896  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:38.897  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:43.898  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.898  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.899  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:43.899  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.899  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.900  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:43.900  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:44:43.900  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:43.901  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:43.902  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:43.902  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.903  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:43.903  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:43.903  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.904  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.904  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:43.904  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:43.904  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.905  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.905  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:43.909  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:43.910  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:43.910  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:43.910  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:43.915  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 14:44:43.916  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:44:43.919  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 14:44:43.921  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 14:44:43.922  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 14:44:43.922  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 14:44:43.923  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 14:44:43.923  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:44:43.924  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:44:43.924  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:44:43.924  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 14:44:43.924  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 14:44:43.925  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.925  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 14:44:43.925  3837  3892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:44:43.925  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:43.926  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 14:44:43.926  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.926  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:44:43.926  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 14:44:43.926  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:44:43.927  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.927  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.929  3837  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 14:44:43.929  3837  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-16 14:44:43.929  3837  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 14:44:43.930  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:44:43.930  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:44:43.930  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:44:43.931  3837  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 14:44:43.931  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:44:43.932  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:43.932  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:43.932  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:43.932  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:43.933  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:43.933  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:43.933  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.933  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:43.934  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.934  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:43.934  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:43.934  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.934  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.935  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:43.935  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.938  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:43.938  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:43.938  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:43.939  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.942  3837  3884 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 14:44:43.942  3837  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:44:43.942  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 14:44:43.944  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:44:43.944  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:44:43.945  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:43.945  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:43.945  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:43.945  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:43.945  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.945  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.945  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
,08-16 14:44:43.945  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.945  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.946  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:43.946  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.946  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:43.946  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.946  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.947  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:43.947  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:43.947  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.947  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.953  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:43.953  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:44:43.953  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:43.953  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:43.953  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:43.953  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.953  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:43.953  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.953  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.953  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:43.954  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.954  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.954  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.954  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.958  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:43.959  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:43.959  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:44:43.959  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.960  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:44:43.960  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:44:43.960  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:44:43.960  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:44:43.960  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.960  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.960  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3607424 not in the list
08-16 14:44:43.960  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.960  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
08-16 14:44:43.961  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:43.961  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:43.961  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.961  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:43.961  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:43.963  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:44:43.963  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:44:43.963  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:43.963  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4c9b8d not in the list
,08-16 14:44:43.964  3837  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 14:44:43.964  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:44:43.964  3837  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 14:44:43.965  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:44:43.965  3837  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 14:44:43.965  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 14:44:43.967  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 14:44:43.967  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 14:44:43.969  3837  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 14:44:43.969  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:44:43.969  3837  3884 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 14:44:43.969  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-16 14:44:43.969  3837  3884 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 14:44:43.969  3837  3884 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 14:44:43.970  3837  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 14:44:43.970  3837  3884 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-16 14:44:43.970  3837  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 14:44:43.971  3837  3884 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 14:44:43.971  3837  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 14:44:43.971  3837  3884 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 14:44:43.972  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:44:43.972  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2c09a7 added. We now have 3 listener(s)
08-16 14:44:43.972  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:44:43.974  3837  3884 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 14:44:43.974   875  1938 D WifiService: setWifiEnabled: true pid=3837, uid=10000
08-16 14:44:43.974   875  1938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:44:44.001  2666  2760 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-16 14:44:44.001  2666  2760 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 14:44:44.434  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:44:48.986  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:44:48.987  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7db2e54 added. We now have 4 listener(s)
,08-16 14:44:48.987  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:44:49.009  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:49.010  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7db2e54 removed from the list
,08-16 14:44:49.010  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:44:49.010  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:44:49.010  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:44:49.013  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:44:49.013  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96881fd added. We now have 4 listener(s)
,08-16 14:44:49.013  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:44:49.017  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:44:49.017  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96881fd removed from the list
,08-16 14:44:49.017  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:44:49.017  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:44:49.018  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:44:49.021  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:44:49.021  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc89ef2 added. We now have 4 listener(s)
,08-16 14:44:49.022  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:44:49.031   875   886 D WifiService: setWifiEnabled: false pid=3837, uid=10000
,08-16 14:44:49.031   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:44:49.044  2666  2682 D BluetoothAdapterState: Current state: ON, message: 23
08-16 14:44:49.045  2666  2682 D BluetoothAdapterProperties: Setting state to 13
08-16 14:44:49.045  2666  2682 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:44:49.045  2666  2682 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:44:49.046  2666  2682 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:44:49.047  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:44:49.050  2666  2686 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:44:49.050  2666  2682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 14:44:49.056  2666  2666 D BluetoothMapService: onReceive
,08-16 14:44:49.056  2666  2666 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:44:49.056  2666  2666 D BluetoothMapService: STATE_TURNING_OFF
08-16 14:44:49.057  2666  2666 D BluetoothMapService: MAP Service closeService in
08-16 14:44:49.057  2666  2666 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 14:44:49.057  2666  2666 D ObexServerSockets0: shutdown(block = true)
08-16 14:44:49.058  2666  2804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 14:44:49.058  2666  2666 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 14:44:49.060  2666  2805 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 14:44:49.060  2666  2666 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 14:44:49.060  2666  2666 I BtOppRfcommListener: stopping Accept Thread
,08-16 14:44:49.060  2666  2791 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 14:44:49.061  2666  3469 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:44:49.061  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:49.061  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:44:49.061  2666  3469 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:44:49.062  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.062  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:49.062  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:44:49.065  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.067  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.069  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:49.069  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:49.070  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:49.070  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:49.071  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 14:44:49.073   875  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 14:44:49.073   875  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 14:44:49.073   875   888 I ActivityManager: Start proc 3897:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 14:44:49.073   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:44:49.073   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:44:49.078  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:49.078  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:44:49.079  2666  2666 D HeadsetService: Received stop request...Stopping profile...
,08-16 14:44:49.079  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:49.079  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:49.081  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.081  1364  2020 D BluetoothHeadset: Proxy object disconnected
08-16 14:44:49.081   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 14:44:49.082   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 14:44:49.082  1933  1946 D BluetoothHeadset: Proxy object disconnected
08-16 14:44:49.082   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 14:44:49.083  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.083  1364  1364 D HeadsetProfile: Bluetooth service disconnected
08-16 14:44:49.084  2666  2666 D A2dpService: Received stop request...Stopping profile...
08-16 14:44:49.084  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.085  2666  2797 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:44:49.086  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.087  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-16 14:44:49.088   875   875 D BluetoothA2dp: Proxy object disconnected
08-16 14:44:49.088  2666  2666 D HidService: Received stop request...Stopping profile...
08-16 14:44:49.088  2666  2666 D HidService: Stopping Bluetooth HidService
08-16 14:44:49.089   875  1304 E native  : do suspend true
08-16 14:44:49.089  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-16 14:44:49.089  1364  1364 D HidProfile: Bluetooth service disconnected
08-16 14:44:49.089  2666  2666 D HealthService: Received stop request...Stopping profile...
08-16 14:44:49.092  2666  2666 D PanService: Received stop request...Stopping profile...
08-16 14:44:49.092  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:44:49.092  1364  1364 D PanProfile: Bluetooth service disconnected
08-16 14:44:49.093  2666  2666 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:44:49.093  2666  2666 D BluetoothMapService: stop()
08-16 14:44:49.093  2666  2666 D BluetoothMapAppObserver: deinitObservers()
08-16 14:44:49.093  2666  2666 D BluetoothMapAppObserver: removeReceiver()
08-16 14:44:49.094  1364  1364 D BluetoothMap: Proxy object disconnected
08-16 14:44:49.094  1364  1364 D MapProfile: Bluetooth service disconnected
08-16 14:44:49.095  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-16 14:44:49.095  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.095  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:44:49.095  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:44:49.096  2666  2666 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 14:44:49.096  2666  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:44:49.097  2666  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:44:49.097  2666  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:44:49.097  2666  2686 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 14:44:49.097  2666  2686 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 14:44:49.097  2666  2666 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 14:44:49.098  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-16 14:44:49.099  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.099  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:44:49.099  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:44:49.100   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:44:49.103  2666  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:44:49.103  2666  2760 D bt_bta_sys,_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:44:49.103  2666  2760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:44:49.103  2666  2760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:44:49.103  2666  2760 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:44:49.103  2666  2760 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:44:49.103  2666  2686 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 14:44:49.103   875  2079 D DhcpClient: Clearing IP address
08-16 14:44:49.103  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-16 14:44:49.104  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.104  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:44:49.104  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:44:49.104  2666  2666 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:44:49.104  2666  2686 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 14:44:49.104  2666  2666 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:44:49.105  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-16 14:44:49.105  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.105  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:44:49.105  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:44:49.105  2666  2666 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:44:49.105  2666  2686 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 14:44:49.106  2666  2666 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:44:49.106  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-16 14:44:49.106  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.106  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false,
08-16 14:44:49.106  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:44:49.106  2666  2666 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:44:49.107  2666  2666 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:44:49.107  2666  2666 D BluetoothMapService: MAP Service closeService in
08-16 14:44:49.107  2666  2666 V BluetoothAdapterState: isTurningOff()=true
08-16 14:44:49.107  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.108  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:44:49.108  2666  2666 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:44:49.105   373   873 D CommandListener: Setting iface cfg
08-16 14:44:49.108  2666  2682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 14:44:49.108  2666  2682 D BluetoothAdapterProperties: Setting state to 15
08-16 14:44:49.108  2666  2682 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 14:44:49.109   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:44:49.109  1364  1375 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:44:49.109   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 14:44:49.110  2666  2682 I BluetoothAdapterState: Entering BleOnState
08-16 14:44:49.110   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 14:44:49.110   875  1304 D WifiStateMachine: Start Disconnecting Watchdog 1,
08-16 14:44:49.110   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:44:49.111   875  1304 E native  : do suspend true
08-16 14:44:49.113  1364  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:44:49.113  1933  1946 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:44:49.114  2666  2666 D BluetoothMapService: cleanup()
08-16 14:44:49.114  2666  2666 D BluetoothMapService: MAP Service closeService in
08-16 14:44:49.115  1364  1387 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:44:49.115   396   396 E Parcel  : Reading a NULL string not supported here.
08-16 14:44:49.115   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:44:49.115   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:44:49.116  1364  1987 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:44:49.116  1364  2020 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:44:49.116   875  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-16 14:44:49.117  1364  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:44:49.117   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:44:49.117  2666  2682 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 14:44:49.117  2666  2682 D BluetoothAdapterProperties: Setting state to 16
08-16 14:44:49.117  2666  2682 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 14:44:49.118  2666  2682 D BluetoothAdapterProperties: onBleDisable
08-16 14:44:49.118  2666  2682 I BluetoothAdapterState: Entering PendingCommandState
08-16 14:44:49.118  2666  2683 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 14:44:49.119  2666  2686 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:44:49.119  2666  2760 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 14:44:49.119  2666  2760 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:44:49.123  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:49.123  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:49.123  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.124  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:44:49.125   875  2148 D DhcpClient: Receive thread stopped
08-16 14:44:49.125  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:49.125  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:49.126  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:49.126  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:49.127  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:49.127  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:49.128  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.128  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:49.129  1503  2544 V NativeCrypto: Read error: ssl=0x9ab4f000: I/O error during system call, Connection timed out
08-16 14:44:49.131  1503  2544 V NativeCrypto: SSL shutdown failed: ssl=0x9ab4f000: I/O error during system call, Broken pipe
08-16 14:44:49.143  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:49.144  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.145  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:44:49.148   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:44:49.156  3897  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 14:44:49.164   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:44:49.165   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:44:49.165   875  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 14:44:49.165   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:44:49.167   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:44:49.170   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 14:44:49.170  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.171  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.172  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:44:49.174  1994  1994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-16 14:44:49.173  3404  3404 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5be23cc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 14:44:49.184   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 14:44:49.186   875  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:44:49.187  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:49.187  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:49.187  1885  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:44:49.188  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.188  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:49.189  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:49.189  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:49.189  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.189  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:44:49.191  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:49.191  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:49.191  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:49.192  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:44:49.195  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:44:49.200  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:44:49.203   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@981221a:true
,08-16 14:44:49.213   875  1938 I ActivityManager: Start proc 3918:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 14:44:49.220   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-16 14:44:49.222  3897  3897 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 14:44:49.224  3897  3897 D BluetoothMap: Create BluetoothMap proxy object
,08-16 14:44:49.228  3897  3897 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 14:44:49.233  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:44:49.236   875   886 I ActivityManager: Killing 3221:com.google.android.gm/u0a78 (adj 15): empty #17
,08-16 14:44:49.284  3918  3918 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 14:44:49.323  2666  2686 I bt_hci  : shut_down
,08-16 14:44:49.324  2666  2702 D bt_hwcfg: hw_epilog_process
,08-16 14:44:49.325  2666  2702 I bt_vendor: low_power_mode_cb
,08-16 14:44:49.344  2666  2702 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-16 14:44:49.344  2666  2702 I bt_vendor: epilog_cb
08-16 14:44:49.344  2666  2702 I bt_hci  : epilog_finished_callback
,08-16 14:44:49.351  2666  2686 I bt_hci_h4: hal_close
,08-16 14:44:49.352  2666  2686 I bt_userial_vendor: device fd = 51 close
,08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.415  3918  3918 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:44:49.415  3918  3918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:44:49.425  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:44:49.450  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:44:49.474  3897  3897 D DockEventReceiver: finishStartingService: stopping service
08-16 14:44:49.477   875  1943 I ActivityManager: Killing 3404:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 14:44:49.528  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:44:49.562  1725  1725 D SystemUpdateService: onCreate
,08-16 14:44:49.563  2666  2683 D bt_stack_manager: event_shut_down_stack finished.
,08-16 14:44:49.564  2666  2682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-16 14:44:49.575  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-16 14:44:49.575  2666  2666 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:44:49.575  2666  2682 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 14:44:49.582  2666  2666 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:44:49.582  2666  2666 D BtGatt.GattService: stop()
08-16 14:44:49.583  2666  2666 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 14:44:49.595  2666  2666 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:44:49.596  2666  2666 V BluetoothAdapterState: isTurningOn()=false
08-16 14:44:49.596  2666  2666 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:44:49.596  2666  2666 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 14:44:49.597  2666  2682 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 14:44:49.597  2666  2682 D BluetoothAdapterProperties: Setting state to 10
08-16 14:44:49.597  2666  2682 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 14:44:49.602  2666  2682 I BluetoothAdapterState: Entering OffState
08-16 14:44:49.602   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 14:44:49.613  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 14:44:49.630  1725  2522 I iu.UploadsManager: num queued entries: 0
,08-16 14:44:49.630  1725  2522 I iu.UploadsManager: num updated entries: 0
,08-16 14:44:49.637  2666  2666 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 14:44:49.637  2666  2666 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 14:44:49.637  2666  2683 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 14:44:49.639  2666  2683 D bt_stack_manager: event_clean_up_stack finished.
08-16 14:44:49.639  2666  2666 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 14:44:49.641  2666  2666 I art     : System.exit called, status: 0
,08-16 14:44:49.641  2666  2666 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 14:44:49.644  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:44:49.646  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 14:44:49.652  1725  3949 I SystemUpdateService: active receiver: enabled
,08-16 14:44:49.663  1725  2522 I iu.SyncManager: NEXT; no task
,08-16 14:44:49.669   875  1390 I ActivityManager: Start proc 3952:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 14:44:49.673  1725  3949 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:44:49.674  1725  3949 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 14:44:49.674  1725  3949 I SystemUpdateService: now status is 0 (complete)
08-16 14:44:49.675  1725  3949 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 14:44:49.675  1725  3949 I SystemUpdateService: file has been verified
08-16 14:44:49.675  1725  3949 I SystemUpdateService: OTA package size = 12249756
,08-16 14:44:49.688  1725  3949 I SystemUpdateService: showing system update notification
,08-16 14:44:49.698   875  2189 I ActivityManager: Process com.android.bluetooth (pid 2666) has died
,08-16 14:44:49.722  3952  3952 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 14:44:49.724  3952  3952 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:44:49.740  3952  3952 D SprintDMHelper: simOperator: 
08-16 14:44:49.740  3952  3952 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:44:49.765   875  2174 I ActivityManager: Start proc 3965:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 14:44:49.772  1725  1725 D SystemUpdateService: onDestroy
,08-16 14:44:49.871  2271  3980 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 14:44:49.886   875  1709 I ActivityManager: Start proc 3981:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 14:44:49.891   875  1709 I ActivityManager: Killing 2779:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 14:44:49.902  3918  3935 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 14:44:49.915   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44b0f21:true
,08-16 14:44:49.988  3981  3981 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 14:44:50.050  3981  3981 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 14:44:50.050  3981  3981 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 14:44:50.050  3981  3981 I GAv4    :   adb logcat -s GAv4
,08-16 14:44:50.079  3981  3981 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 14:44:50.085  3981  3981 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 14:44:50.111  3981  3999 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 14:44:50.207  3981  3981 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 14:44:50.260  3981  3981 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 14:44:50.267  3981  3981 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1860-1862)
08-16 14:44:50.267  3981  3981 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:44:50.277  3981  3981 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4f817fc}
08-16 14:44:50.278  3981  3981 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:44:50.278  3981  3981 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 14:44:50.284  3981  3981 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 14:44:50.285  3981  3981 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 14:44:50.304  3981  3981 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 14:44:50.318  3981  3981 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:44:50.318  3981  3981 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 14:44:50.318  3981  3981 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 14:44:50.318  3981  3981 I Adreno  : Build Date                       : 10/20/15
08-16 14:44:50.318  3981  3981 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 14:44:50.318  3981  3981 I Adreno  : Local Branch                     : M14
08-16 14:44:50.318  3981  3981 I Adreno  : Remote Branch                    : 
08-16 14:44:50.318  3981  3981 I Adreno  : Remote Branch                    : 
08-16 14:44:50.318  3981  3981 I Adreno  : Reconstruct Branch               : 
,08-16 14:44:50.370  3981  3981 I NSApplication: Starting up...
,08-16 14:44:50.378  3981  4027 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 14:44:50.416   875  1938 I ActivityManager: Start proc 4032:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 14:44:50.417   875  1938 I ActivityManager: Killing 1694:android.process.acore/u0a5 (adj 15): empty #17
,08-16 14:44:50.519  4032  4032 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 14:44:50.774   875  1914 I ActivityManager: Killing 3655:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 14:44:50.832   875  1938 I ActivityManager: Start proc 4046:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-16 14:44:50.921  4046  4046 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 14:44:50.979  4046  4046 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 14:44:51.003   875  1709 I ActivityManager: Killing 3670:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 14:44:54.066   875   886 D WifiService: setWifiEnabled: true pid=3837, uid=10000
08-16 14:44:54.066   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:44:54.080   875  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-16 14:44:54.089  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:54.089  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:54.090  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:54.090  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:54.093  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:54.093  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:54.094  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:54.109  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:54.111  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:54.111  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:54.111  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:54.111  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:54.123   875  1304 D WifiConfigStore: loaded 0 passpoint configs
08-16 14:44:54.124   875  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 14:44:54.124   875  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 14:44:54.125   875  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:44:54.126   875  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 14:44:54.126   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 14:44:54.126   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 14:44:54.136   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 14:44:54.138   373   873 D CommandListener: Setting iface cfg
08-16 14:44:54.138   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 14:44:54.138   875  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 14:44:54.139   875  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 14:44:54.142   875  1303 D WifiNative-HAL: p2pGetDeviceAddress
08-16 14:44:54.142   875  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 14:44:54.154   875  1304 E native  : do suspend true
,08-16 14:44:54.190   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:44:55.026   875  1938 I ActivityManager: Killing 3429:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 14:44:55.563   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 14:44:55.616   875  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.06 rxSuccessRate=13.38 delta 1000 -> 994
,08-16 14:44:55.619   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 14:44:55.619   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:44:55.640   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 14:44:55.696   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 14:44:55.698  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 14:44:56.204  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 14:44:56.256  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 14:44:56.257  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 14:44:56.263   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:44:56.279   875  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 14:44:56.280   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 14:44:56.280   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:44:56.307   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:44:56.327   373   873 D CommandListener: Setting iface cfg
,08-16 14:44:56.327   875  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 14:44:56.342   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 14:44:56.364   875  4080 D DhcpClient: Receive thread started
,08-16 14:44:56.472   875  1304 E native  : do suspend false
,08-16 14:44:56.504   875  2079 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 14:44:56.517   875  4080 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172435, domain null
,08-16 14:44:56.520   875  2079 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172435 seconds
,08-16 14:44:56.524   875  2079 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 14:44:56.540   875  4080 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 14:44:56.542   875  2079 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 14:44:56.548   373   873 D CommandListener: Setting iface cfg
,08-16 14:44:56.560   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 14:44:56.561   875  2079 D DhcpClient: Scheduling renewal in 86399s
08-16 14:44:56.561   875  1304 E native  : do suspend true
,08-16 14:44:56.581   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 14:44:56.582   875  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 14:44:56.582   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 14:44:56.585   875  1306 D ConnectivityService: Adding iface wlan0 to network 101
08-16 14:44:56.589   875  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 14:44:56.681   875  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 14:44:56.682   875  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 14:44:56.684   875  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 14:44:56.687   875  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 14:44:56.688   875  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 14:44:56.700   875  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 14:44:56.709   875  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 14:44:56.709   875  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-16 14:44:56.709   875  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 14:44:56.709   875  1306 D ConnectivityService:    accepting network in place of null
08-16 14:44:56.710   875  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 14:44:56.712   875  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 14:44:56.712   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 14:44:56.720   875  4078 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388315, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 14:44:56.792   875  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:803::200e
,08-16 14:44:56.797   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:44:56.858   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:44:56.867   875  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 14:44:56.867   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:44:56.874   875  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 14:44:56.877   875   892 D Tethering: MasterInitialState.processMessage what=3
08-16 14:44:56.880   875  4077 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:44:56 GMT], X-Android-Received-Millis=[1471351496878], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471351496843]}
,08-16 14:44:56.899   875  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 14:44:56.899  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:56.899   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:56.899  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:44:56.899  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:56.899   875  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 14:44:56.899  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:56.900   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 14:44:56.902  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:56.902  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:44:56.902  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:56.902  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:56.904  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:44:56.904  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:44:56.904  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:56.904  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:44:56.911  1994  1994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 14:44:56.919  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:44:56.922  1725  1725 D SystemUpdateService: onCreate
,08-16 14:44:56.926  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:44:56.942  1725  4091 I SystemUpdateService: active receiver: enabled
,08-16 14:44:56.947  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 14:44:56.950  1725  2522 I iu.UploadsManager: num queued entries: 0
,08-16 14:44:56.950  1725  2522 I iu.UploadsManager: num updated entries: 0
08-16 14:44:56.951  1725  2522 I iu.SyncManager: NEXT; no task
,08-16 14:44:56.955  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 14:44:56.956  1725  4091 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:44:56.957  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 14:44:56.960  3952  3952 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:44:56.965  1725  4093 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 14:44:56.965  1725  4093 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 14:44:56.967  3952  3952 D SprintDMHelper: simOperator: 
,08-16 14:44:56.967  3952  3952 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:44:56.977  1725  4093 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 14:44:56.994  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 14:44:57.003  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 14:44:56.983  1725  4091 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 14:44:57.003  1725  4091 I SystemUpdateService: now status is 0 (complete)
08-16 14:44:57.003  1725  4091 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 14:44:57.003  1725  4091 I SystemUpdateService: file has been verified
08-16 14:44:57.003  1725  4091 I SystemUpdateService: OTA package size = 12249756
,08-16 14:44:57.030  1725  4091 I SystemUpdateService: showing system update notification
,08-16 14:44:57.062  1725  1725 D SystemUpdateService: onDestroy
,08-16 14:44:57.095  1503  2294 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 14:44:57.095  1503  2294 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 14:44:57.096  1503  2294 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:44:57.096  1503  2294 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:44:57.109  2271  4098 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 14:44:57.122  1725  4093 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-16 14:44:57.868   875  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 14:44:59.074   875  2174 D WifiService: setWifiEnabled: false pid=3837, uid=10000
,08-16 14:44:59.075   875  2174 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:44:59.116  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 14:44:59.123   875  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 14:44:59.124   875  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 14:44:59.124   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:44:59.125   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:44:59.153   875  1304 E native  : do suspend true
,08-16 14:44:59.174   875  2079 D DhcpClient: Clearing IP address
,08-16 14:44:59.174   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-16 14:44:59.178   373   873 D CommandListener: Setting iface cfg
,08-16 14:44:59.180   875  4080 D DhcpClient: Receive thread stopped
,08-16 14:44:59.187   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 14:44:59.189   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 14:44:59.192   875  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 14:44:59.199   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 14:44:59.199   875  1304 E native  : do suspend true
08-16 14:44:59.201   396   396 E Parcel  : Reading a NULL string not supported here.
08-16 14:44:59.186  1503  4102 V NativeCrypto: Read error: ssl=0x9ab4f000: I/O error during system call, Connection timed out
,08-16 14:44:59.207  1503  4102 V NativeCrypto: SSL shutdown failed: ssl=0x9ab4f000: I/O error during system call, Broken pipe
,08-16 14:44:59.211   875  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 14:44:59.214   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-16 14:44:59.245   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:44:59.272   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:44:59.273   875  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 14:44:59.274   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:44:59.277   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 14:44:59.281  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:59.281  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:59.281  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.281   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 14:44:59.281  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:59.283  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:59.283  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:59.283  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.283  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:59.284  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:59.284  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:59.285  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.285  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:59.293  1994  1994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-16 14:44:59.304   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:44:59.305  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 14:44:59.308  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:59.308  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:59.308  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.308  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:59.309  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:59.309  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:59.309  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:44:59.309  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:59.309   875  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:44:59.310  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:44:59.310  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:44:59.310  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:44:59.310  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:44:59.311  1725  1725 D SystemUpdateService: onCreate
08-16 14:44:59.315  1885  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:44:59.317  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:44:59.330  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 14:44:59.336  1725  2522 I iu.UploadsManager: num queued entries: 0
,08-16 14:44:59.338  1725  4112 I SystemUpdateService: active receiver: enabled
,08-16 14:44:59.339  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:44:59.340  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 14:44:59.342  3952  3952 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:44:59.346  3952  3952 D SprintDMHelper: simOperator: 
,08-16 14:44:59.346  3952  3952 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:44:59.376  1725  2522 I iu.UploadsManager: num updated entries: 0
08-16 14:44:59.376  1725  2522 I iu.SyncManager: NEXT; no task
,08-16 14:44:59.381  2271  4116 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 14:44:59.389  1725  4112 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:44:59.391  1725  4112 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 14:44:59.391  1725  4112 I SystemUpdateService: now status is 0 (complete)
08-16 14:44:59.391  1725  4112 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 14:44:59.391  1725  4112 I SystemUpdateService: file has been verified
08-16 14:44:59.391  1725  4112 I SystemUpdateService: OTA package size = 12249756
,08-16 14:44:59.395  1725  4112 I SystemUpdateService: showing system update notification
,08-16 14:44:59.405   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-16 14:44:59.407   875  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 14:44:59.408  1725  1725 D SystemUpdateService: onDestroy
,08-16 14:45:00.041  1857  1962 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 14:45:00.041  1857  1962 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 14:45:00.148  1503  1503 I ConfigService: onCreate
,08-16 14:45:04.126   875   892 I ActivityManager: Start proc 4124:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 14:45:04.272  4124  4124 D AdapterServiceConfig: Adding HeadsetService
,08-16 14:45:04.272  4124  4124 D AdapterServiceConfig: Adding A2dpService
08-16 14:45:04.272  4124  4124 D AdapterServiceConfig: Adding HidService
,08-16 14:45:04.272  4124  4124 D AdapterServiceConfig: Adding HealthService
08-16 14:45:04.273  4124  4124 D AdapterServiceConfig: Adding PanService
08-16 14:45:04.273  4124  4124 D AdapterServiceConfig: Adding GattService
,08-16 14:45:04.273  4124  4124 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 14:45:04.289   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f7a0a8:true
,08-16 14:45:04.290  4124  4124 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 14:45:04.299  4124  4124 I bt_bluedroid: init
,08-16 14:45:04.299  4124  4136 I BluetoothAdapterState: Entering OffState
,08-16 14:45:04.306  4124  4137 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 14:45:04.306  4124  4137 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:45:04.307  4124  4137 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:45:04.307  4124  4137 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 14:45:04.310  4124  4124 I bt_bluedroid: get_profile_interface socket
,08-16 14:45:04.315  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 14:45:04.316  4124  4124 I bt_bluedroid: get_profile_interface sdp
08-16 14:45:04.318  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:45:04.323  4124  4135 I bt_bluedroid: config_hci_snoop_log
,08-16 14:45:04.326   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 14:45:04.338  4124  4136 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 14:45:04.338  4124  4136 D BluetoothAdapterProperties: Setting state to 14
08-16 14:45:04.339  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-16 14:45:04.341  4124  4136 D BluetoothBondStateMachine: make
,08-16 14:45:04.347  4124  4141 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 14:45:04.352  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:45:04.355  4124  4124 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 14:45:04.361  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:04.362  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:45:04.364  4124  4124 D BtGatt.GattService: Received start request. Starting profile...
,08-16 14:45:04.365  4124  4124 D BtGatt.GattService: start()
08-16 14:45:04.366  4124  4124 I bt_bluedroid: get_profile_interface gatt
,08-16 14:45:04.368  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:04.368  4124  4124 D BtGatt.AdvertiseManager: advertise manager created
,08-16 14:45:04.379  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:45:04.379  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:04.379  4124  4124 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 14:45:04.379  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:04.380  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 14:45:04.380  4124  4136 I bt_bluedroid: enable
,08-16 14:45:04.381  4124  4137 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 14:45:04.382  4124  4137 I bt_hci  : start_up
,08-16 14:45:04.402  4124  4137 I bt_vendor: alloc value 0xb39b9189
,08-16 14:45:04.402  4124  4137 I bt_vendor: init
08-16 14:45:04.403  4124  4137 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 14:45:04.403  4124  4137 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 14:45:04.513  4124  4137 D bt_hci  : start_up starting async portion
,08-16 14:45:04.514  4124  4144 I bt_hci  : event_finish_startup
08-16 14:45:04.514  4124  4144 I bt_hci_h4: hal_open
08-16 14:45:04.514  4124  4144 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 14:45:04.530  4124  4144 I bt_userial_vendor: device fd = 51 open
,08-16 14:45:04.555  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:45:04.587  4124  4144 D bt_hwcfg: Chipset BCM4354A2
,08-16 14:45:04.588  4124  4144 D bt_hwcfg: Target name = [BCM4354A2]
08-16 14:45:04.588  4124  4144 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 14:45:04.715   875  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-16 14:45:05.223  1503  1503 I ConfigService: onDestroy
,08-16 14:45:05.630  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 14:45:05.632  4124  4144 D bt_hwcfg: Settlement delay -- 100 ms
08-16 14:45:05.632  4124  4144 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 14:45:05.754  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:45:05.755  4124  4144 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 14:45:05.781  4124  4144 I bt_hwcfg: vendor lib fwcfg completed
08-16 14:45:05.781  4124  4144 I bt_vendor: firmware callback
,08-16 14:45:05.782  4124  4144 I bt_hci  : firmware_config_callback
,08-16 14:45:05.795  4124  4146 I bt_btu  : btu_task pending for preload complete event
,08-16 14:45:05.795  4124  4146 I bt_btu_task: Bluetooth chip preload is complete
08-16 14:45:05.796  4124  4146 I bt_btu  : btu_task received preload complete event
,08-16 14:45:05.807  4124  4146 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 14:45:05.807  4124  4146 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:45:05.808  4124  4146 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:45:05.808  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 14:45:05.808  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:45:05.809  4124  4146 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:45:05.809  4124  4146 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:45:05.809  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 14:45:05.810  4124  4146 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:45:05.810  4124  4146 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 14:45:05.811  4124  4146 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:45:05.811  4124  4146 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:45:05.811  4124  4146 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:45:05.813  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:45:05.813  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 14:45:05.966  4124  4146 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
08-16 14:45:05.966  4124  4146 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-16 14:45:05.982  4124  4140 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 14:45:05.984  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 14:45:05.985  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 14:45:05.988  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:45:05.990  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:45:05.991  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:45:05.992  4124  4140 D bt_hci  : do_postload posting postload work item
,08-16 14:45:05.992  4124  4144 I bt_hci  : event_postload
08-16 14:45:05.992  4124  4144 I bt_vendor: sco_config_cb
08-16 14:45:05.992  4124  4144 I bt_hci  : sco_config_callback postload finished.
08-16 14:45:05.994  4124  4140 D bt_bte_conf: Device ID record 1 : primary
08-16 14:45:05.994  4124  4140 D bt_bte_conf:   vendorId            = 000f
08-16 14:45:05.994  4124  4140 D bt_bte_conf:   vendorIdSource      = 0001
08-16 14:45:05.995  4124  4140 D bt_bte_conf:   product             = 1200
,08-16 14:45:05.995  4124  4140 D bt_bte_conf:   version             = 1436
08-16 14:45:05.995  4124  4140 D bt_bte_conf:   clientExecutableURL = 
08-16 14:45:05.996  4124  4140 D bt_bte_conf:   serviceDescription  = 
08-16 14:45:05.996  4124  4140 D bt_bte_conf:   documentationURL    = 
08-16 14:45:05.996  4124  4140 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 14:45:05.996  4124  4137 D bt_stack_manager: event_start_up_stack finished
08-16 14:45:05.997  4124  4144 I bt_vendor: low_power_mode_cb
08-16 14:45:05.997  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 14:45:05.997  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:05.998  4124  4136 D BluetoothAdapterProperties: Setting state to 15
08-16 14:45:05.998  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 14:45:06.002  4124  4136 I BluetoothAdapterState: Entering BleOnState
08-16 14:45:06.002  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.016  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.018  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 14:45:06.018  4124  4136 D BluetoothAdapterProperties: Setting state to 11
,08-16 14:45:06.018  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 14:45:06.023  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:06.024  4124  4124 D HeadsetService: Received start request. Starting profile...
,08-16 14:45:06.030  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.031  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.032  4124  4124 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:45:06.033  4124  4124 D HeadsetStateMachine: make
08-16 14:45:06.033  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:06.036  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:45:06.042  4124  4124 D HeadsetStateMachine: max_hf_connections = 1
,08-16 14:45:06.042  4124  4124 I bt_bluedroid: get_profile_interface handsfree
08-16 14:45:06.042  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 14:45:06.042  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 14:45:06.046  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:06.046  4124  4124 D A2dpService: Received start request. Starting profile...
08-16 14:45:06.047  4124  4124 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 14:45:06.047  4124  4124 I bt_bluedroid: get_profile_interface avrcp
,08-16 14:45:06.055  4124  4124 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:45:06.055  4124  4124 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:45:06.055  4124  4124 D A2dpStateMachine: make
,08-16 14:45:06.058  4124  4124 I bt_bluedroid: get_profile_interface a2dp
,08-16 14:45:06.059  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 14:45:06.061  4124  4124 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 14:45:06.062  4124  4156 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:45:06.062  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
08-16 14:45:06.063  4124  4124 D HidService: Received start request. Starting profile...
,08-16 14:45:06.063  3897  3897 D BluetoothInputDevice: Proxy object connected
08-16 14:45:06.064  4124  4124 I bt_bluedroid: get_profile_interface hidhost
,08-16 14:45:06.064  4124  4140 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-16 14:45:06.064  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 14:45:06.064  4124  4124 D HidService: setHidService(): set to: null
08-16 14:45:06.064  3897  3897 D HidProfile: Bluetooth service connected
08-16 14:45:06.065  4124  4124 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 14:45:06.066  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
08-16 14:45:06.067  4124  4124 D HealthService: Received start request. Starting profile...
,08-16 14:45:06.069  4124  4124 I bt_bluedroid: get_profile_interface health
,08-16 14:45:06.070  4124  4124 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 14:45:06.071  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:06.073  4124  4124 D PanService: Received start request. Starting profile...
,08-16 14:45:06.073  3897  3897 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:45:06.073  4124  4124 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:45:06.073  4124  4124 I bt_bluedroid: get_profile_interface pan
08-16 14:45:06.074  3897  3897 D PanProfile: Bluetooth service connected
,08-16 14:45:06.074  4124  4140 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 14:45:06.078  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:06.079  4124  4124 D BluetoothMapService: Received start request. Starting profile...
08-16 14:45:06.079  4124  4124 D BluetoothMapService: start()
,08-16 14:45:06.079  3897  3897 D BluetoothMap: Proxy object connected
08-16 14:45:06.080  3897  3897 D MapProfile: Bluetooth service connected
,08-16 14:45:06.081  3897  3897 D BluetoothMap: getConnectedDevices()
,08-16 14:45:06.081  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-16 14:45:06.082  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 14:45:06.082  4124  4124 D BluetoothMapAppObserver: createReceiver()
,08-16 14:45:06.083  4124  4124 D BluetoothMapAppObserver: initObservers()
08-16 14:45:06.083  3897  3897 D BluetoothMap: Bluetooth is Not enabled
08-16 14:45:06.083  4124  4124 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 14:45:06.093  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:45:06.093  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:06.093  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:06.093  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:06.093  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:06.098  4124  4154 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 14:45:06.098  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:06.098  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:06.098  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:06.098  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:06.099  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:06.100  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:06.101  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-16 14:45:06.101  4124  4136 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:45:06.101  4124  4136 D BluetoothAdapterProperties: State =  11
08-16 14:45:06.103  4124  4136 D BluetoothAdapterProperties: Setting state to 12
08-16 14:45:06.103  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:45:06.104  4124  4136 I BluetoothAdapterState: Entering OnState
,08-16 14:45:06.104  3897  3909 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 14:45:06.106   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:45:06.108  1364  1387 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 14:45:06.108  4124  4140 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:45:06.108  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:45:06.109  1364  2020 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:45:06.110   875   875 D BluetoothA2dp: Proxy object connected
08-16 14:45:06.110  1933  2268 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:06.111  1364  1987 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:45:06.113  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:45:06.113  1364  1364 D PanProfile: Bluetooth service connected
08-16 14:45:06.113   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:06.113   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:06.113  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:45:06.113  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 14:45:06.113  1364  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:45:06.114  4124  4124 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 14:45:06.115  1364  1364 D BluetoothInputDevice: Proxy object connected
08-16 14:45:06.115  1364  1364 D HidProfile: Bluetooth service connected
08-16 14:45:06.117  3897  3907 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:45:06.117  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:45:06.117  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:45:06.118  1364  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:45:06.119  1364  1364 D BluetoothA2dp: Proxy object connected
,08-16 14:45:06.120  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:45:06.121  1364  2020 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:06.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:45:06.122  4124  4124 D ObexServerSockets: Succeed to create listening sockets 
08-16 14:45:06.122  4124  4124 D ObexServerSockets0: startAccept()
08-16 14:45:06.122  4124  4124 D ObexServerSockets0: prepareForNewConnect()
08-16 14:45:06.124  1364  1364 D BluetoothMap: Proxy object connected
08-16 14:45:06.124  1364  1364 D MapProfile: Bluetooth service connected
08-16 14:45:06.124  1364  1364 D BluetoothMap: getConnectedDevices()
08-16 14:45:06.124  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:45:06.125  3897  3909 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:45:06.125  3897  3907 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:45:06.127   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:06.127  4124  4124 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:06.128  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:45:06.128  4124  4124 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 14:45:06.130  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:45:06.131   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 14:45:06.131  4124  4163 D ObexServerSockets0: Accepting socket connection...
08-16 14:45:06.132  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.132  4124  4124 D BluetoothMapService: onReceive
08-16 14:45:06.132  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:45:06.132  4124  4124 D BluetoothMapService: STATE_ON
08-16 14:45:06.132  4124  4162 D ObexServerSockets0: Accepting socket connection...
08-16 14:45:06.133  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.134  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:06.135  3897  3897 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 14:45:06.139  3897  3897 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 14:45:06.147  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:45:06.150  3897  3897 D BluetoothA2dp: Proxy object connected
,08-16 14:45:06.152  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 14:45:06.153  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,08-16 14:45:06.155  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:45:06.160  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:45:06.165  3897  3897 D BluetoothPbap: Proxy object connected
,08-16 14:45:06.165  1364  1364 D BluetoothPbap: Proxy object connected
08-16 14:45:06.165  1364  1364 D PbapServerProfile: Bluetooth service connected
08-16 14:45:06.165  3897  3897 D PbapServerProfile: Bluetooth service connected
,08-16 14:45:06.174  4124  4167 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:45:06.198  4124  4171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:45:06.200  4124  4171 I BtOppRfcommListener: Accept thread started.
,08-16 14:45:06.213  1364  2020 D BluetoothHeadset: Proxy object connected
,08-16 14:45:06.213   875   875 D BluetoothHeadset: Proxy object connected
,08-16 14:45:06.213   875   875 D BluetoothHeadset: Proxy object connected
,08-16 14:45:06.213  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-16 14:45:06.214   875   892 D BluetoothHeadset: Proxy object connected
08-16 14:45:06.214   875   892 D BluetoothHeadset: Proxy object connected
08-16 14:45:06.214  1933  1946 D BluetoothHeadset: Proxy object connected
08-16 14:45:06.214   875   875 D BluetoothHeadset: Proxy object connected
,08-16 14:45:06.228   875   892 D BluetoothHeadset: Proxy object connected
,08-16 14:45:06.242  3897  3909 D BluetoothHeadset: Proxy object connected
,08-16 14:45:06.245  3897  3897 D HeadsetProfile: Bluetooth service connected
,08-16 14:45:09.096  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:45:09.096  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:09.099  4124  4136 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 14:45:09.099  4124  4136 D BluetoothAdapterProperties: Setting state to 13
08-16 14:45:09.099  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:45:09.101  4124  4136 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:45:09.101  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:09.102  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc89ef2 removed from the list
08-16 14:45:09.102  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:09.102  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:09.103  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:09.106  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:45:09.106  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e6dbc0 added. We now have 4 listener(s)
,08-16 14:45:09.107  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:45:09.110  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
08-16 14:45:09.112  4124  4124 D BluetoothMapService: onReceive
08-16 14:45:09.113  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:45:09.113  4124  4124 D BluetoothMapService: STATE_TURNING_OFF
,08-16 14:45:09.114  4124  4124 D BluetoothMapService: MAP Service closeService in
,08-16 14:45:09.114  4124  4124 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 14:45:09.114  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:45:09.115  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e6dbc0 removed from the list
,08-16 14:45:09.115  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:09.115  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 14:45:09.115  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:09.114  4124  4124 D ObexServerSockets0: shutdown(block = true)
,08-16 14:45:09.119  4124  4162 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 14:45:09.122  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:45:09.122  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:09.122  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:45:09.122  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c040f9 added. We now have 4 listener(s)
08-16 14:45:09.125  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:45:09.125  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 14:45:09.125  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:45:09.126  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:45:09.126  4124  4163 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097,
,08-16 14:45:09.127  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:45:09.128  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 14:45:09.129  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 14:45:09.130  4124  4148 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 14:45:09.130  4124  4124 D HeadsetService: Received stop request...Stopping profile...
,08-16 14:45:09.132  1364  1375 D BluetoothHeadset: Proxy object disconnected
,08-16 14:45:09.133  4124  4124 I BtOppRfcommListener: stopping Accept Thread
08-16 14:45:09.133   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 14:45:09.133  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,08-16 14:45:09.133   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 14:45:09.133  4124  4171 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:45:09.133  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:09.133  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:45:09.133  3897  3907 D BluetoothHeadset: Proxy object disconnected
,08-16 14:45:09.134  3837  3837 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:45:09.134  1933  2054 D BluetoothHeadset: Proxy object disconnected
08-16 14:45:09.134  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:45:09.134   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 14:45:09.135  4124  4171 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 14:45:09.136  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:09.137  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:09.138  4124  4124 D A2dpService: Received stop request...Stopping profile...
08-16 14:45:09.138  4124  4156 D A2dpStateMachine: Exit Disconnected: -1
08-16 14:45:09.138  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 23
08-16 14:45:09.139  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 14:45:09.139   875   875 D BluetoothA2dp: Proxy object disconnected
,08-16 14:45:09.140  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-16 14:45:09.140  4124  4124 V BluetoothAdapterState: isTurningOff()=true
,08-16 14:45:09.140  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-16 14:45:09.140  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:09.140  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:09.143  3897  3897 D HeadsetProfile: Bluetooth service disconnected
,08-16 14:45:09.143  3897  3897 D BluetoothA2dp: Proxy object disconnected
,08-16 14:45:09.144  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 14:45:09.144  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 14:45:09.144  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 14:45:09.144  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 14:45:09.144  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:45:09.144  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 14:45:09.145  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 14:45:09.145  4124  4124 D HidService: Received stop request...Stopping profile...
08-16 14:45:09.145  4124  4124 D HidService: Stopping Bluetooth HidService
08-16 14:45:09.147  4124  4124 D HealthService: Received stop request...Stopping profile...
,08-16 14:45:09.147  3897  3897 D DockEventReceiver: finishStartingService: stopping service
08-16 14:45:09.149  3897  3897 D BluetoothInputDevice: Proxy object disconnected
08-16 14:45:09.149  3897  3897 D HidProfile: Bluetooth service disconnected
08-16 14:45:09.153  4124  4124 D PanService: Received stop request...Stopping profile...
08-16 14:45:09.154  3897  3897 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 14:45:09.154  3897  3897 D PanProfile: Bluetooth service disconnected
08-16 14:45:09.155  4124  4124 D BluetoothMapService: Received stop request...Stopping profile...
08-16 14:45:09.155  4124  4124 D BluetoothMapService: stop()
,08-16 14:45:09.156  4124  4124 D BluetoothMapAppObserver: deinitObservers()
08-16 14:45:09.156  4124  4124 D BluetoothMapAppObserver: removeReceiver()
,08-16 14:45:09.157  3897  3897 D BluetoothMap: Proxy object disconnected
,08-16 14:45:09.158  3897  3897 D MapProfile: Bluetooth service disconnected
08-16 14:45:09.158  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 14:45:09.158  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:09.158  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:09.158  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:09.159  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:45:09.160  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:45:09.160  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:45:09.160  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 14:45:09.160  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:45:09.160  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:45:09.160  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 14:45:09.161  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-16 14:45:09.161  1364  1364 D HidProfile: Bluetooth service disconnected
08-16 14:45:09.162  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 14:45:09.162  1364  1364 D PanProfile: Bluetooth service disconnected
08-16 14:45:09.162  1364  1364 D BluetoothMap: Proxy object disconnected
08-16 14:45:09.162  1364  1364 D MapProfile: Bluetooth service disconnected
08-16 14:45:09.163  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 14:45:09.163  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:09.163  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:09.163  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:09.164  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 14:45:09.164  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 14:45:09.164  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 14:45:09.164  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:45:09.164  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 14:45:09.164  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:09.164  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:09.165  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:09.165  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 14:45:09.165  4124  4140 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 14:45:09.165  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:45:09.166  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 14:45:09.166  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:09.166  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:09.166  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:09.167  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:45:09.167  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:45:09.168  4124  4124 D BluetoothMapService: MAP Service closeService in
08-16 14:45:09.169  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 14:45:09.169  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:09.169  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:09.169  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:09.169  4124  4124 D BluetoothMapService: cleanup()
08-16 14:45:09.169  4124  4124 D BluetoothMapService: MAP Service closeService in
08-16 14:45:09.170  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 14:45:09.170  4124  4136 D BluetoothAdapterProperties: Setting state to 15
08-16 14:45:09.170  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 14:45:09.170  4124  4136 I BluetoothAdapterState: Entering BleOnState
08-16 14:45:09.171  3897  3907 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:45:09.172   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 14:45:09.172  1364  1387 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:45:09.173  3897  3897 D BluetoothPbap: Proxy object disconnected
08-16 14:45:09.173  3897  3897 D PbapServerProfile: Bluetooth service disconnected
08-16 14:45:09.173  1364  1364 D BluetoothPbap: Proxy object disconnected
08-16 14:45:09.173  1364  1364 D PbapServerProfile: Bluetooth service disconnected
08-16 14:45:09.174  1364  2020 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:45:09.175  1933  1947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:45:09.176  1364  1375 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:45:09.177  3897  3909 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:45:09.177   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:45:09.177   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:45:09.178  1364  1987 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:45:09.181  3897  3907 D BluetoothPan: onBluetoothStateChange on: false
08-16 14:45:09.182  3897  3909 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:45:09.183  1364  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:45:09.184  1364  2020 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:45:09.185  3897  3907 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:45:09.186  3897  3909 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:45:09.186   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 14:45:09.187  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 14:45:09.187  4124  4136 D BluetoothAdapterProperties: Setting state to 16
08-16 14:45:09.187  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 14:45:09.188  4124  4136 D BluetoothAdapterProperties: onBleDisable
,08-16 14:45:09.189  4124  4137 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 14:45:09.190  4124  4146 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 14:45:09.190  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 14:45:09.190  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
08-16 14:45:09.190  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:45:09.191  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:09.192  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:09.193  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:45:09.194  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:09.196  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:09.203  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:45:09.212  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:45:09.399  4124  4140 I bt_hci  : shut_down
,08-16 14:45:09.418  4124  4144 I bt_vendor: low_power_mode_cb
,08-16 14:45:09.419  4124  4144 D bt_hwcfg: hw_epilog_process
,08-16 14:45:09.435  4124  4144 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 14:45:09.435  4124  4144 I bt_vendor: epilog_cb
08-16 14:45:09.435  4124  4144 I bt_hci  : epilog_finished_callback
,08-16 14:45:09.446  4124  4140 I bt_hci_h4: hal_close
,08-16 14:45:09.447  4124  4140 I bt_userial_vendor: device fd = 51 close
,08-16 14:45:09.581  4124  4137 D bt_stack_manager: event_shut_down_stack finished.
,08-16 14:45:09.582  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 14:45:09.588  4124  4136 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 14:45:09.588  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:45:09.590  4124  4124 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 14:45:09.590  4124  4124 D BtGatt.GattService: stop()
08-16 14:45:09.591  4124  4124 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 14:45:09.596  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:45:09.596  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-16 14:45:09.596  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:09.597  4124  4124 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 14:45:09.597  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 14:45:09.598  4124  4136 D BluetoothAdapterProperties: Setting state to 10
,08-16 14:45:09.599  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 14:45:09.600  4124  4136 I BluetoothAdapterState: Entering OffState
,08-16 14:45:09.603   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 14:45:09.633  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 14:45:09.634  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 14:45:09.634  4124  4137 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 14:45:09.644  4124  4137 D bt_stack_manager: event_clean_up_stack finished.
,08-16 14:45:09.646  4124  4124 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 14:45:09.654  4124  4124 I art     : System.exit called, status: 0
,08-16 14:45:09.654  4124  4124 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 14:45:09.692   875  1708 I ActivityManager: Process com.android.bluetooth (pid 4124) has died
,08-16 14:45:14.145  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:14.189   875   892 I ActivityManager: Start proc 4181:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 14:45:14.334  4181  4181 D AdapterServiceConfig: Adding HeadsetService
08-16 14:45:14.334  4181  4181 D AdapterServiceConfig: Adding A2dpService
08-16 14:45:14.335  4181  4181 D AdapterServiceConfig: Adding HidService
08-16 14:45:14.335  4181  4181 D AdapterServiceConfig: Adding HealthService
08-16 14:45:14.335  4181  4181 D AdapterServiceConfig: Adding PanService
08-16 14:45:14.335  4181  4181 D AdapterServiceConfig: Adding GattService
08-16 14:45:14.336  4181  4181 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 14:45:14.349  4181  4181 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 14:45:14.349   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fcca605:true
,08-16 14:45:14.357  4181  4181 I bt_bluedroid: init
,08-16 14:45:14.357  4181  4193 I BluetoothAdapterState: Entering OffState
,08-16 14:45:14.363  4181  4194 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 14:45:14.364  4181  4194 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:45:14.364  4181  4194 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 14:45:14.365  4181  4194 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 14:45:14.367  4181  4181 I bt_bluedroid: get_profile_interface socket
,08-16 14:45:14.370  4181  4197 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 14:45:14.371  4181  4197 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 14:45:14.372  4181  4181 I bt_bluedroid: get_profile_interface sdp
,08-16 14:45:14.380  4181  4192 I bt_bluedroid: config_hci_snoop_log
,08-16 14:45:14.385   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 14:45:14.400  4181  4193 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 14:45:14.401  4181  4193 D BluetoothAdapterProperties: Setting state to 14
08-16 14:45:14.401  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 14:45:14.405  4181  4193 D BluetoothBondStateMachine: make
,08-16 14:45:14.410  4181  4198 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 14:45:14.416  4181  4193 I BluetoothAdapterState: Entering PendingCommandState
,08-16 14:45:14.420  4181  4181 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 14:45:14.429  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:14.431  4181  4181 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:45:14.432  4181  4181 D BtGatt.GattService: Received start request. Starting profile...
,08-16 14:45:14.433  4181  4181 D BtGatt.GattService: start()
08-16 14:45:14.433  4181  4181 I bt_bluedroid: get_profile_interface gatt
,08-16 14:45:14.436  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
08-16 14:45:14.437  4181  4181 D BtGatt.AdvertiseManager: advertise manager created
,08-16 14:45:14.456  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:45:14.456  4181  4181 V BluetoothAdapterState: isTurningOn()=false
08-16 14:45:14.457  4181  4181 V BluetoothAdapterState: isBleTurningOn()=true
08-16 14:45:14.457  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:14.459  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 14:45:14.460  4181  4193 I bt_bluedroid: enable
,08-16 14:45:14.460  4181  4194 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 14:45:14.461  4181  4194 I bt_hci  : start_up
,08-16 14:45:14.485  4181  4194 I bt_vendor: alloc value 0xb39b9189
,08-16 14:45:14.485  4181  4194 I bt_vendor: init
08-16 14:45:14.485  4181  4194 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 14:45:14.486  4181  4194 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 14:45:14.594  4181  4194 D bt_hci  : start_up starting async portion
,08-16 14:45:14.595  4181  4201 I bt_hci  : event_finish_startup
,08-16 14:45:14.595  4181  4201 I bt_hci_h4: hal_open
08-16 14:45:14.596  4181  4201 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 14:45:14.607  4181  4201 I bt_userial_vendor: device fd = 51 open
,08-16 14:45:14.637  4181  4201 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:45:14.668  4181  4201 D bt_hwcfg: Chipset BCM4354A2
,08-16 14:45:14.668  4181  4201 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 14:45:14.669  4181  4201 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 14:45:15.805  4181  4201 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 14:45:15.806  4181  4201 D bt_hwcfg: Settlement delay -- 100 ms
08-16 14:45:15.807  4181  4201 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 14:45:15.928  4181  4201 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 14:45:15.930  4181  4201 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 14:45:15.955  4181  4201 I bt_hwcfg: vendor lib fwcfg completed
,08-16 14:45:15.956  4181  4201 I bt_vendor: firmware callback
,08-16 14:45:15.956  4181  4201 I bt_hci  : firmware_config_callback
,08-16 14:45:15.970  4181  4203 I bt_btu  : btu_task pending for preload complete event
,08-16 14:45:15.970  4181  4203 I bt_btu_task: Bluetooth chip preload is complete
08-16 14:45:15.970  4181  4203 I bt_btu  : btu_task received preload complete event
,08-16 14:45:15.982  4181  4203 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 14:45:15.982  4181  4203 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:45:15.983  4181  4203 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 14:45:15.983  4181  4203 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 14:45:15.983  4181  4203 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:45:15.984  4181  4203 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 14:45:15.984  4181  4203 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:45:15.984  4181  4203 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 14:45:15.984  4181  4203 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:45:15.986  4181  4203 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 14:45:15.986  4181  4203 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:45:15.987  4181  4203 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 14:45:15.987  4181  4203 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:45:15.988  4181  4203 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:45:15.988  4181  4203 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 14:45:16.147  4181  4203 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-16 14:45:16.148  4181  4203 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-16 14:45:16.174  4181  4197 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 14:45:16.176  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 14:45:16.177  4181  4197 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 14:45:16.181  4181  4197 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 14:45:16.185  4181  4197 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:45:16.187  4181  4197 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:45:16.187  4181  4197 D bt_hci  : do_postload posting postload work item
08-16 14:45:16.188  4181  4201 I bt_hci  : event_postload
,08-16 14:45:16.189  4181  4201 I bt_vendor: sco_config_cb
08-16 14:45:16.189  4181  4201 I bt_hci  : sco_config_callback postload finished.
08-16 14:45:16.191  4181  4197 D bt_bte_conf: Device ID record 1 : primary
,08-16 14:45:16.191  4181  4197 D bt_bte_conf:   vendorId            = 000f
,08-16 14:45:16.192  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:16.192  4181  4197 D bt_bte_conf:   vendorIdSource      = 0001
08-16 14:45:16.192  4181  4197 D bt_bte_conf:   product             = 1200
,08-16 14:45:16.192  4181  4197 D bt_bte_conf:   version             = 1436
08-16 14:45:16.193  4181  4197 D bt_bte_conf:   clientExecutableURL = 
08-16 14:45:16.193  4181  4197 D bt_bte_conf:   serviceDescription  = 
,08-16 14:45:16.193  4181  4197 D bt_bte_conf:   documentationURL    = 
08-16 14:45:16.193  4181  4197 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 14:45:16.194  4181  4194 D bt_stack_manager: event_start_up_stack finished
08-16 14:45:16.196  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:16.196  4181  4201 I bt_vendor: low_power_mode_cb
08-16 14:45:16.196  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 14:45:16.197  4181  4193 D BluetoothAdapterProperties: Setting state to 15
08-16 14:45:16.197  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 14:45:16.198  4181  4193 I BluetoothAdapterState: Entering BleOnState
,08-16 14:45:16.218  4181  4193 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 14:45:16.218  4181  4193 D BluetoothAdapterProperties: Setting state to 11
08-16 14:45:16.218  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 14:45:16.224  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:16.225  4181  4181 D HeadsetService: Received start request. Starting profile...
,08-16 14:45:16.227  4181  4181 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 14:45:16.228  4181  4181 D HeadsetStateMachine: make
08-16 14:45:16.234  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:16.235  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:16.240  4181  4181 D HeadsetStateMachine: max_hf_connections = 1
,08-16 14:45:16.241  4181  4193 I BluetoothAdapterState: Entering PendingCommandState
08-16 14:45:16.241  4181  4181 I bt_bluedroid: get_profile_interface handsfree
08-16 14:45:16.241  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040,
08-16 14:45:16.241  4181  4197 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 14:45:16.248  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:16.248  4181  4181 D A2dpService: Received start request. Starting profile...
,08-16 14:45:16.249  4181  4181 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 14:45:16.249  4181  4181 I bt_bluedroid: get_profile_interface avrcp
,08-16 14:45:16.257  4181  4181 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:45:16.257  4181  4181 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:45:16.257  4181  4181 D A2dpStateMachine: make
,08-16 14:45:16.259  4181  4181 I bt_bluedroid: get_profile_interface a2dp
,08-16 14:45:16.261  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 14:45:16.263  4181  4181 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 14:45:16.264  4181  4212 D A2dpStateMachine: Enter Disconnected: -2
,08-16 14:45:16.264  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:16.265  4181  4181 D HidService: Received start request. Starting profile...
08-16 14:45:16.265  4181  4181 I bt_bluedroid: get_profile_interface hidhost
08-16 14:45:16.265  4181  4197 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
,08-16 14:45:16.265  4181  4197 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 14:45:16.266  4181  4181 D HidService: setHidService(): set to: null
08-16 14:45:16.266  4181  4181 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 14:45:16.267  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:16.268  4181  4181 D HealthService: Received start request. Starting profile...
,08-16 14:45:16.270  4181  4181 I bt_bluedroid: get_profile_interface health
,08-16 14:45:16.271  4181  4181 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 14:45:16.272  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:16.273  4181  4181 D PanService: Received start request. Starting profile...
,08-16 14:45:16.273  4181  4181 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:45:16.273  4181  4181 I bt_bluedroid: get_profile_interface pan
,08-16 14:45:16.274  4181  4197 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 14:45:16.279  4181  4181 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
,08-16 14:45:16.281  4181  4181 D BluetoothMapService: Received start request. Starting profile...
,08-16 14:45:16.281  4181  4181 D BluetoothMapService: start()
,08-16 14:45:16.285  4181  4181 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 14:45:16.286  4181  4181 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 14:45:16.286  4181  4181 D BluetoothMapAppObserver: createReceiver()
,08-16 14:45:16.287  4181  4181 D BluetoothMapAppObserver: initObservers()
,08-16 14:45:16.287  4181  4181 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 14:45:16.295  4181  4181 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:16.295  4181  4181 V BluetoothAdapterState: isTurningOn()=true
,08-16 14:45:16.295  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:16.295  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:16.295  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:45:16.298  4181  4209 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isTurningOff()=false
,08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
08-16 14:45:16.299  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isTurningOn()=true
08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isTurningOff()=false
08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isTurningOn()=true
,08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 14:45:16.300  4181  4181 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 14:45:16.300  4181  4193 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-16 14:45:16.300  4181  4193 D BluetoothAdapterProperties: ScanMode =  20
,08-16 14:45:16.300  4181  4193 D BluetoothAdapterProperties: State =  11
,08-16 14:45:16.302  4181  4197 D BluetoothAdapterProperties: Scan Mode:21
,08-16 14:45:16.302  4181  4197 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 14:45:16.303  4181  4193 D BluetoothAdapterProperties: Setting state to 12
,08-16 14:45:16.303  4181  4193 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 14:45:16.304  4181  4193 I BluetoothAdapterState: Entering OnState
,08-16 14:45:16.304  3897  3909 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 14:45:16.305   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:45:16.306  1364  1375 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:16.306  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:45:16.307   875   875 D BluetoothA2dp: Proxy object connected
,08-16 14:45:16.307  1364  1987 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:45:16.308  1933  1947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:16.308  1364  1387 D BluetoothPan: onBluetoothStateChange on: true
08-16 14:45:16.308  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:45:16.310  3897  3909 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:45:16.311   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:16.311   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 14:45:16.311  1364  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 14:45:16.311  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:45:16.311  1364  1364 D PanProfile: Bluetooth service connected
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:16.312  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:45:16.312  1364  1364 D BluetoothInputDevice: Proxy object connected
,08-16 14:45:16.312  1364  1364 D HidProfile: Bluetooth service connected
08-16 14:45:16.312  3897  3907 D BluetoothPan: onBluetoothStateChange on: true
,08-16 14:45:16.313  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:45:16.313  4181  4181 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 14:45:16.314  3897  3909 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:45:16.314  4181  4181 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 14:45:16.315  1364  1987 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:45:16.316  4181  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:45:16.315  3897  3897 D BluetoothInputDevice: Proxy object connected
,08-16 14:45:16.316  3897  3897 D HidProfile: Bluetooth service connected
08-16 14:45:16.317  1364  1364 D BluetoothA2dp: Proxy object connected
08-16 14:45:16.317  1364  1387 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:45:16.318  4181  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:45:16.318  3897  3907 D BluetoothMap: onBluetoothStateChange: up=true
08-16 14:45:16.319  3897  3909 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:45:16.320  4181  4181 D ObexServerSockets: Succeed to create listening sockets 
08-16 14:45:16.320  4181  4181 D ObexServerSockets0: startAccept()
08-16 14:45:16.320  4181  4181 D ObexServerSockets0: prepareForNewConnect()
08-16 14:45:16.320   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 14:45:16.322  4181  4181 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 14:45:16.322   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 14:45:16.323  4181  4181 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 14:45:16.323  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:16.324  4181  4220 D ObexServerSockets0: Accepting socket connection...
08-16 14:45:16.323  4181  4221 D ObexServerSockets0: Accepting socket connection...
08-16 14:45:16.324  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:16.324  3897  3897 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:45:16.324  3897  3897 D PanProfile: Bluetooth service connected
08-16 14:45:16.325  3897  3897 D BluetoothA2dp: Proxy object connected
08-16 14:45:16.325  4181  4181 D BluetoothMapService: onReceive
08-16 14:45:16.325  1364  1364 D BluetoothMap: Proxy object connected
,08-16 14:45:16.325  4181  4181 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:45:16.325  1364  1364 D MapProfile: Bluetooth service connected
08-16 14:45:16.325  1364  1364 D BluetoothMap: getConnectedDevices()
08-16 14:45:16.325  4181  4181 D BluetoothMapService: STATE_ON
08-16 14:45:16.330  3897  3897 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 14:45:16.332  3897  3897 D BluetoothMap: Proxy object connected
08-16 14:45:16.332  3897  3897 D MapProfile: Bluetooth service connected
08-16 14:45:16.332  3897  3897 D BluetoothMap: getConnectedDevices()
08-16 14:45:16.336  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 14:45:16.341  3897  3897 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:45:16.343  3897  3897 D BluetoothPbap: Proxy object connected
08-16 14:45:16.344  3897  3897 D PbapServerProfile: Bluetooth service connected
,08-16 14:45:16.350  1364  1364 D BluetoothPbap: Proxy object connected
08-16 14:45:16.350  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-16 14:45:16.352  4181  4181 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 14:45:16.352  4181  4181 D ObexServerSockets0: prepareForNewConnect()
,08-16 14:45:16.355  4181  4225 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:45:16.378  4181  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:45:16.382  4181  4229 I BtOppRfcommListener: Accept thread started.
,08-16 14:45:16.411  1364  2020 D BluetoothHeadset: Proxy object connected
,08-16 14:45:16.411   875   892 D BluetoothHeadset: Proxy object connected
,08-16 14:45:16.411   875   875 D BluetoothHeadset: Proxy object connected
,08-16 14:45:16.411  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-16 14:45:16.413   875   875 D BluetoothHeadset: Proxy object connected
08-16 14:45:16.411   875   892 D BluetoothHeadset: Proxy object connected
08-16 14:45:16.413  3897  3909 D BluetoothHeadset: Proxy object connected
08-16 14:45:16.414  3897  3897 D HeadsetProfile: Bluetooth service connected
08-16 14:45:16.415  1933  2268 D BluetoothHeadset: Proxy object connected
08-16 14:45:16.417   875   875 D BluetoothHeadset: Proxy object connected
,08-16 14:45:16.421   875   892 D BluetoothHeadset: Proxy object connected
,08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:19.168  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:45:19.177  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:45:19.178  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:19.179  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c040f9 removed from the list
08-16 14:45:19.179  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:19.179  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:45:19.180  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:19.186  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:45:19.187  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3db83e added. We now have 4 listener(s)
08-16 14:45:19.188  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:45:19.194   875  1914 D WifiService: setWifiEnabled: false pid=3837, uid=10000
,08-16 14:45:19.194   875  1914 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:45:24.206  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:24.208   875  1390 D WifiService: setWifiEnabled: true pid=3837, uid=10000
08-16 14:45:24.208   875  1390 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 14:45:24.220   875  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:24.242  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:45:24.251  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:45:24.259   875  1304 D WifiConfigStore: loaded 0 passpoint configs
08-16 14:45:24.260   875  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 14:45:24.260   875  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 14:45:24.261   875  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 14:45:24.261   875  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 14:45:24.262   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 14:45:24.262   875  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:45:24.262  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:45:24.268  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:45:24.278   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 14:45:24.279   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 14:45:24.279   373   873 D CommandListener: Setting iface cfg
,08-16 14:45:24.280   875  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-16 14:45:24.280   875  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 14:45:24.331   875  1304 E native  : do suspend true
,08-16 14:45:24.345   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:45:24.353   875  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 14:45:24.353   875  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 14:45:25.717   875  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 14:45:25.868   875  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.81 rxSuccessRate=14.94 delta 1000 -> 994
,08-16 14:45:25.869   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3,
,08-16 14:45:25.870   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:45:25.884   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 14:45:25.923   875  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 14:45:25.929  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 14:45:26.376  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 14:45:26.406  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:45:26.406  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 14:45:26.410   875  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 14:45:26.425   875  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 14:45:26.425   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:45:26.426   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 14:45:26.443   875  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:45:26.456   373   873 D CommandListener: Setting iface cfg
,08-16 14:45:26.458   875  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 14:45:26.465   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 14:45:26.496   875  4239 D DhcpClient: Receive thread started
,08-16 14:45:26.594   875  1304 E native  : do suspend false
,08-16 14:45:26.628   875  2079 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 14:45:26.649   875  4239 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172770, domain null
,08-16 14:45:26.651   875  2079 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172770 seconds
,08-16 14:45:26.659   875  2079 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 14:45:26.690   875  4239 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 14:45:26.692   875  2079 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 14:45:26.697   373   873 D CommandListener: Setting iface cfg
,08-16 14:45:26.709   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 14:45:26.712   875  2079 D DhcpClient: Scheduling renewal in 86399s
,08-16 14:45:26.714   875  1304 E native  : do suspend true
,08-16 14:45:26.741   875  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 14:45:26.744   875  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 14:45:26.746   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 14:45:26.751   875  1306 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 14:45:26.759   875  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 14:45:26.823   875  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 14:45:26.823   875  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 14:45:26.828   875  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 14:45:26.832   875  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102,
,08-16 14:45:26.836   875  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 14:45:26.851   875  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 14:45:26.860   875  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 14:45:26.860   875  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 14:45:26.860   875  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 14:45:26.860   875  1306 D ConnectivityService:    accepting network in place of null
08-16 14:45:26.861   875  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 14:45:26.862   875  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 14:45:26.863   875  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 14:45:26.872   875  4238 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418467, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 14:45:26.910   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:45:26.968   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 14:45:26.974   875  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 14:45:26.974   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:45:26.979   875  4237 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:817::200e
08-16 14:45:26.980   875  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 14:45:26.984   875   892 D Tethering: MasterInitialState.processMessage what=3
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:26.998  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:27.002  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:27.009  3837  3837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:27.013  3837  3837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:27.019  1994  1994 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 14:45:27.022  1725  1725 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 14:45:27.027  1725  1725 D SystemUpdateService: onCreate
,08-16 14:45:27.033  1725  1725 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 14:45:27.059  1725  4248 I SystemUpdateService: active receiver: enabled
,08-16 14:45:27.066   875  4237 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:45:27 GMT], X-Android-Received-Millis=[1471351527065], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471351527031]}
08-16 14:45:27.067   875  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 14:45:27.067   875  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 14:45:27.068   875  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 14:45:27.071  1725  1725 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 14:45:27.073   875  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 14:45:27.077  1725  2522 I iu.UploadsManager: num queued entries: 0
,08-16 14:45:27.078  1725  2522 I iu.UploadsManager: num updated entries: 0
,08-16 14:45:27.082  1725  4248 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 14:45:27.083  1725  1725 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 14:45:27.084  1725  1725 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 14:45:27.086  3952  3952 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:45:27.109  1725  4251 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 14:45:27.109  1725  4251 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 14:45:27.110  3952  3952 D SprintDMHelper: simOperator: 
08-16 14:45:27.110  3952  3952 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 14:45:27.125  1725  4251 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 14:45:27.129  1725  4248 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 14:45:27.129  1725  4248 I SystemUpdateService: now status is 0 (complete)
08-16 14:45:27.129  1725  4248 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 14:45:27.129  1725  4248 I SystemUpdateService: file has been verified
08-16 14:45:27.130  1725  4248 I SystemUpdateService: OTA package size = 12249756
,08-16 14:45:27.167  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:45:27.168  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 14:45:27.199  1725  2522 I iu.SyncManager: NEXT; no task
,08-16 14:45:27.236  1725  4248 I SystemUpdateService: showing system update notification
,08-16 14:45:27.270  1725  1725 D SystemUpdateService: onDestroy
,08-16 14:45:27.291  1503  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 14:45:27.291  1503  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 14:45:27.291  1503  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 14:45:27.291  1503  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 14:45:27.296  2271  4254 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 14:45:27.319  1725  4251 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-16 14:45:27.978   875  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:29.236  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:29.245  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:29.246  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:29.247  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3db83e removed from the list
08-16 14:45:29.247  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:45:29.247  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:29.247  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:29.261  3837  4260 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 14:45:29.262  3837  4260 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 14:45:32.271  3837  4261 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 14:45:32.272  3837  4261 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 14:45:32.272  3837  4260 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 14:45:32.273  3837  4260 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 14:45:32.274  3837  4260 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:45:32.274  3837  4261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 14:45:32.275  3837  4260 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:45:32.277  3837  4261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 14:45:32.280  3837  4263 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: OutgoingSocketThread/Sender)
08-16 14:45:32.281  3837  4260 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 14:45:32.285  3837  4265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: OutgoingSocketThread/Receiver)
,08-16 14:45:32.286  3837  4261 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 14:45:32.288  3837  4265 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: OutgoingSocketThread/Receiver)
08-16 14:45:32.289  3837  4265 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-16 14:45:32.289  3837  4265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 14:45:32.293  3837  4264 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: IncomingSocketThread/Sender)
,08-16 14:45:32.296  3837  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: IncomingSocketThread/Receiver)
08-16 14:45:32.299  3837  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 420, thread name: IncomingSocketThread/Receiver)
08-16 14:45:32.299  3837  4266 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 14:45:32.299  3837  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 14:45:34.865   875  1306 D ConnectivityService: handlePromptUnvalidated 102
,08-16 14:45:35.271  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 14:45:35.274  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 14:45:35.282  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@625725e Bundle[{}]
,08-16 14:45:35.284  3837  3884 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 14:45:35.286  3837  3884 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 14:45:35.287  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 14:45:35.288  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:45:35.289  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 14:45:35.290  3837  3884 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 14:45:35.294  3837  3884 I System.out: Running OutgoingSocketThread
,08-16 14:45:35.297  3837  4269 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 14:45:35.298  3837  4269 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 14:45:38.308  3837  4269 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 14:45:38.308  3837  4269 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 14:45:38.308  3837  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:45:38.309  3837  4270 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 14:45:38.310  3837  4270 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 14:45:38.310  3837  4270 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 14:45:38.310  3837  4269 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 14:45:38.313  3837  4272 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: OutgoingSocketThread/Sender)
,08-16 14:45:38.315  3837  4269 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 14:45:38.315  3837  4270 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 14:45:38.321  3837  4274 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Receiver)
,08-16 14:45:38.322  3837  4270 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 14:45:38.326  3837  4274 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: OutgoingSocketThread/Receiver)
,08-16 14:45:38.326  3837  4274 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 14:45:38.327  3837  4273 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Sender)
08-16 14:45:38.327  3837  4274 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 14:45:38.329  3837  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: IncomingSocketThread/Receiver)
,08-16 14:45:38.330  3837  4275 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: IncomingSocketThread/Receiver)
08-16 14:45:38.330  3837  4275 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 14:45:38.331  3837  4275 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-16 14:45:41.311  3837  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-16 14:45:41.313  3837  3884 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 14:45:41.314  3837  3884 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-16 14:45:41.321  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:45:41.321  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95e869f added. We now have 3 listener(s)
,08-16 14:45:41.323  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 14:45:41.323  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:45:41.323  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:45:41.324  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:45:41.324  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83df3ec added. We now have 4 listener(s)
,08-16 14:45:41.324  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:45:41.325  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:45:41.329  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:41.337  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:41.342  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:41.342  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:45:41.343  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:45:41.343  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:45:41.343  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:45:41.343  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:41.343  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:41.343  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:45:41.343  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:45:41.343  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95e869f removed from the list
08-16 14:45:41.343  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:41.343  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83df3ec removed from the list
,08-16 14:45:41.347  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:41.347  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:41.348  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:41.348  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:41.348  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:41.350  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:41.350  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:41.350  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:41.350  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83df3ec not in the list
08-16 14:45:41.350  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:41.350  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:41.355  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:41.355  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:41.355  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:41.355  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:41.356  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83df3ec not in the list
,08-16 14:45:41.356  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:41.356  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:41.356  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:41.357  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95e869f not in the list
,08-16 14:45:41.358  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:45:41.359  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d591a4a added. We now have 3 listener(s)
,08-16 14:45:41.364  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:45:41.365  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:45:41.365  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:45:41.366  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:45:41.366  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42eedbb added. We now have 4 listener(s)
08-16 14:45:41.366  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:45:41.367  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:45:41.375  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:41.388  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:41.390  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:41.390  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:45:41.391  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 14:45:41.391  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:45:41.391  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:45:41.391  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:45:41.391  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:45:41.397  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 14:45:41.397  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:45:41.406  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:41.407  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:45:41.408  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:45:41.408  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:45:41.423  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:41.423  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 14:45:41.423  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 14:45:41.424  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 14:45:41.425  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:45:41.427  4181  4217 D BtGatt.GattService: registerClient() - UUID=ba0383f4-4c28-4fe9-a31a-096891468898
08-16 14:45:41.428  4181  4197 D BtGatt.GattService: onClientRegistered() - UUID=ba0383f4-4c28-4fe9-a31a-096891468898, clientIf=5
08-16 14:45:41.430  3837  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 14:45:41.432  4181  4192 D BtGatt.GattService: start scan with filters
,08-16 14:45:41.438  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 14:45:41.438  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:45:41.439  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:45:41.439  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 14:45:41.439  4181  4200 D BtGatt.ScanManager: handling starting scan
,08-16 14:45:41.443  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:45:41.443  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:45:41.444  4181  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@792f712
08-16 14:45:41.444  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:45:41.446  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:45:41.449  3837  3884 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 14:45:41.450  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:45:41.450  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:45:41.450  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:41.450  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:45:41.450  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:45:41.450  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:45:41.450  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:45:41.450  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 14:45:41.450  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:45:41.451  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:45:41.451  3837  3884 D BluetoothAdapter: STATE_ON
08-16 14:45:41.452  4181  4217 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:45:41.454  4181  4192 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:45:41.455  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:45:41.456  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:45:41.456  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:45:41.456  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:45:41.456  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:45:41.459  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:45:41.459  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 14:45:41.459  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 14:45:41.460  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:45:41.460  4181  4197 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 14:45:41.460  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:45:41.461  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:45:41.463  4181  4200 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:45:41.464  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:45:41.464  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:45:41.464  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:45:41.478  4181  4197 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:45:41.479  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:41.480  4181  4200 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:45:41.480  4181  4200 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:45:41.504  4181  4197 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:45:41.504  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:41.521  4181  4197 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:45:41.521  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:41.542  4181  4197 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 14:45:41.542  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:45:41.543  4181  4200 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:45:41.561  4181  4197 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 14:45:41.562  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:41.563  4181  4200 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:45:41.582  4181  4197 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:45:41.582  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:41.966  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:45:41.966  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:45:41.967  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:45:44.466  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:45:44.467  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:45:44.467  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:45:44.468  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:44.469  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:44.469  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:45:44.469  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 14:45:44.470  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d591a4a removed from the list
08-16 14:45:44.470  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:44.470  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42eedbb removed from the list
08-16 14:45:44.470  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:45:44.471  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:44.473  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:44.473  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:44.477  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:44.477  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:44.477  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:45:44.478  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42eedbb not in the list
08-16 14:45:44.478  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:44.478  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:44.482  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:45:44.482  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:44.483  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:45:44.483  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42eedbb not in the list
08-16 14:45:44.483  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:44.484  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:44.484  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:44.484  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d591a4a not in the list
08-16 14:45:44.487  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:45:44.487  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b50d484 added. We now have 3 listener(s)
08-16 14:45:44.488  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:45:44.489  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:45:44.489  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:45:44.489  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:45:44.489  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@442e46d added. We now have 4 listener(s)
08-16 14:45:44.489  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:45:44.489  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:45:44.494  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:44.504  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:44.509  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:44.510  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:45:44.510  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 14:45:44.512  3837  3884 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 14:45:44.512  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-16 14:45:44.513  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:44.515  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 14:45:44.515  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 14:45:44.515  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 14:45:44.516  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:44.516  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:45:44.517  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 14:45:44.518  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 14:45:44.518  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 14:45:44.519  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 14:45:44.519  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 14:45:44.519  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 14:45:44.519  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:45:44.519  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:45:44.520  3837  4276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:45:44.524  3837  4276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-16 14:45:44.529  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 14:45:44.529  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:45:44.534  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:45:44.535  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:45:44.536  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:45:44.540  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 14:45:44.540  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:45:44.541  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-16 14:45:44.542  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 14:45:44.542  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-16 14:45:44.542  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-16 14:45:44.543  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:45:44.547  4181  4218 D BtGatt.GattService: registerClient() - UUID=d2df367e-c122-4c1e-bc3e-3ba54b4fe7b2
,08-16 14:45:44.548  4181  4197 D BtGatt.GattService: onClientRegistered() - UUID=d2df367e-c122-4c1e-bc3e-3ba54b4fe7b2, clientIf=5
08-16 14:45:44.548  3837  3876 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 14:45:44.551  4181  4199 D BtGatt.AdvertiseManager: message : 0
,08-16 14:45:44.555  4181  4199 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 14:45:44.570  4181  4197 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 14:45:44.584  4181  4197 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 14:45:44.586  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 14:45:44.588  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:45:44.597  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:45:44.600  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 14:45:44.600  3837  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 14:45:44.601  3837  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-16 14:45:44.601  3837  3837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 14:45:44.601  3837  3837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-16 14:45:44.601  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 14:45:44.609  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 14:45:44.610  3837  3837 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-16 14:45:44.611  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 14:45:45.113  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 14:45:45.113  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 14:45:45.114  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:45:47.612  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:45:47.613  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-16 14:45:47.613  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:45:47.613  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:45:47.613  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 14:45:47.614  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 14:45:47.616  3837  4276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 14:45:47.616  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:45:47.616  3837  3884 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-16 14:45:47.616  3837  4276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 14:45:47.617  3837  4276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 14:45:47.617  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 14:45:47.617  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:45:47.617  3837  3837 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 14:45:47.617  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:45:47.618  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:45:47.618  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:45:47.622  3837  3884 D BluetoothAdapter: STATE_ON
08-16 14:45:47.622  3837  3884 D BluetoothLeScanner: could not find callback wrapper
08-16 14:45:47.622  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:45:47.623  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-16 14:45:47.625  4181  4199 D BtGatt.AdvertiseManager: message : 1
08-16 14:45:47.627  4181  4199 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 14:45:47.637  4181  4197 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-16 14:45:47.638  4181  4197 D BtGatt.GattService: Client app is not null!
,08-16 14:45:47.639  4181  4210 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:45:47.640  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:45:47.640  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-16 14:45:47.640  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 14:45:47.640  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-16 14:45:47.640  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-16 14:45:47.642  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:45:47.642  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:45:47.642  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:45:47.644  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:45:47.646  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:45:47.646  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:47.646  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 14:45:47.646  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:45:47.649  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b50d484 removed from the list
08-16 14:45:47.649  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:45:47.649  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@442e46d removed from the list
08-16 14:45:47.649  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:47.649  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:47.650  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:47.650  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:47.646  3837  3837 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 14:45:47.651  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:47.651  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:47.651  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:47.651  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@442e46d not in the list
08-16 14:45:47.651  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:45:47.652  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:47.652  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:47.658  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:47.658  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:47.658  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:45:47.659  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@442e46d not in the list
08-16 14:45:47.659  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:47.659  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:47.659  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:45:47.659  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:47.659  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b50d484 not in the list
08-16 14:45:47.659  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:45:47.660  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:45:47.660  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@966acee added. We now have 3 listener(s)
08-16 14:45:47.662  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:45:47.662  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:45:47.662  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:45:47.662  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:45:47.663  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77c558f added. We now have 4 listener(s)
08-16 14:45:47.663  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:45:47.663  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:45:47.666  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:47.675  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:47.679  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:47.679  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:45:47.680  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:45:47.680  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:45:47.680  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:45:47.680  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-16 14:45:47.680  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:45:47.683  3837  3884 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 14:45:47.684  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-16 14:45:47.686  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:47.693  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:45:47.694  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 14:45:47.695  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:45:47.696  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:45:47.707  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:45:47.708  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:45:47.708  3837  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 14:45:47.710  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:45:47.716  4181  4210 D BtGatt.GattService: registerClient() - UUID=195a7e6e-a62b-4948-a686-9f79bd621013
,08-16 14:45:47.717  4181  4197 D BtGatt.GattService: onClientRegistered() - UUID=195a7e6e-a62b-4948-a686-9f79bd621013, clientIf=5
08-16 14:45:47.718  3837  3876 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:45:47.720  4181  4218 D BtGatt.GattService: start scan with filters
,08-16 14:45:47.727  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 14:45:47.727  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:45:47.727  4181  4200 D BtGatt.ScanManager: handling starting scan
08-16 14:45:47.727  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:45:47.727  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:45:47.733  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:45:47.733  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:45:47.733  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:45:47.736  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:45:47.744  4181  4197 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 14:45:47.744  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:47.745  4181  4200 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 14:45:47.765  4181  4197 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 14:45:47.765  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:47.766  4181  4200 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:45:47.766  4181  4200 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:45:47.801  4181  4197 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:45:47.801  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:47.821  4181  4197 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:45:47.821  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:48.162  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:45:48.235  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 14:45:48.236  3837  3837 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:45:48.236  3837  3837 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:45:49.327  4181  4181 D BtGatt.ScanManager: awakened up at time 440922
,08-16 14:45:49.329  4181  4200 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:45:49.385  4181  4197 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
08-16 14:45:49.385  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:49.386  4181  4197 D BtGatt.GattService: current time is 440981139814
08-16 14:45:49.387  4181  4197 D BtGatt.GattService: Batch record : [58, -59, -61, 13, 108, 125, 1, -128, -56, 21, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -90, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -78, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-16 14:45:49.391  4181  4197 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
08-16 14:45:49.393  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 14:45:49.394  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-16 14:45:49.395  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 14:45:49.396  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 14:45:49.398  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-16 14:45:49.400  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 14:45:49.401  4181  4197 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-16 14:45:49.408  3837  3837 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-16 14:45:49.410  3837  3837 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-16 14:45:50.753  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:45:50.753  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:45:50.754  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:45:50.754  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.754  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 14:45:50.755  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:45:50.755  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 14:45:50.756  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:45:50.756  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:45:50.756  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:45:50.757  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 14:45:50.759  3837  3884 D BluetoothAdapter: STATE_ON
,08-16 14:45:50.761  4181  4210 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:45:50.764  4181  4218 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:45:50.765  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 14:45:50.766  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:45:50.766  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:45:50.767  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:45:50.767  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:45:50.771  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:45:50.772  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:45:50.772  3837  3884 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 14:45:50.773  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:45:50.775  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:45:50.775  3837  3884 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-16 14:45:50.776  4181  4181 D BtGatt.ScanManager: awakened up at time 442371
08-16 14:45:50.779  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:50.779  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:45:50.780  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.780  3837  3837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:45:50.780  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:45:50.780  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 14:45:50.780  3837  3837 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:45:50.781  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@966acee removed from the list
08-16 14:45:50.781  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:50.782  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77c558f removed from the list
08-16 14:45:50.782  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:50.782  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:50.783  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.783  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:50.784  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:50.784  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:50.784  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 14:45:50.785  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77c558f not in the list
08-16 14:45:50.785  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.785  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:50.786  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:50.786  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:50.786  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:50.786  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77c558f not in the list
08-16 14:45:50.787  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:50.787  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.787  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:50.787  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@966acee not in the list
08-16 14:45:50.788  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:45:50.788  4181  4197 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:45:50.788  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f05eda1 added. We now have 3 listener(s)
08-16 14:45:50.788  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:45:50.788  4181  4200 D BtGatt.ScanManager: stopping BLe Batch
08-16 14:45:50.791  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 14:45:50.791  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:45:50.791  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:45:50.791  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:45:50.792  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f736bc6 added. We now have 4 listener(s)
08-16 14:45:50.792  3837  3884 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:45:50.792  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:45:50.798  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:45:50.801  4181  4197 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:45:50.801  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:50.801  4181  4200 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:45:50.812  3837  3884 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:45:50.813  4181  4197 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:45:50.813  4181  4197 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:45:50.816  3837  3884 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:45:50.816  3837  3884 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:45:50.816  3837  3884 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:45:50.816  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:45:50.817  3837  3884 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:45:50.817  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:50.817  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.817  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:45:50.817  3837  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:45:50.817  3837  3884 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f05eda1 removed from the list
08-16 14:45:50.817  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:50.817  3837  3884 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f736bc6 removed from the list
,08-16 14:45:50.822  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:50.822  3837  3884 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:45:50.822  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:50.823  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.823  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:50.825  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:50.825  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:45:50.825  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:50.825  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f736bc6 not in the list
,08-16 14:45:50.826  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.826  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:45:50.828  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:45:50.828  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:45:50.828  3837  3884 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:45:50.828  3837  3837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:45:50.828  3837  3884 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f736bc6 not in the list
08-16 14:45:50.828  3837  3884 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:45:50.828  3837  3884 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:45:50.828  3837  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:45:50.828  3837  3884 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f05eda1 not in the list
,08-16 14:45:50.829  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 14:45:50.830  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 14:45:50.830  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 14:45:50.830  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:45:50.830  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 14:45:50.830  3837  3884 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:45:51.284  3837  3837 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:45:52.051   875  4238 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443645, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 14:45:52.848  3837  4277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
,08-16 14:45:54.849  3837  3884 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 451
,08-16 14:45:54.850  3837  3884 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 451, name: My test thread name)
,08-16 14:45:54.857  3837  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
,08-16 14:45:54.858  3837  4278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: My test thread name)
,08-16 14:45:54.859  3837  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 14:45:54.864  3837  3884 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 14:45:54.873  3837  4279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,08-16 14:45:54.874  3837  4279 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 456, thread name: My test thread name): Test exception.
,08-16 14:45:54.874  3837  4279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 14:45:54.884  3837  3884 I jxcore-log: Total number of executed tests:  82
08-16 14:45:54.884  3837  3884 I jxcore-log: 
,08-16 14:45:54.885  3837  3884 I jxcore-log: Number of passed tests:  82
08-16 14:45:54.885  3837  3884 I jxcore-log: 
,08-16 14:45:54.886  3837  3884 I jxcore-log: Number of failed tests:  0
08-16 14:45:54.886  3837  3884 I jxcore-log: 
,08-16 14:45:54.886  3837  3884 I jxcore-log: Number of ignored tests:  0
08-16 14:45:54.886  3837  3884 I jxcore-log: 
,08-16 14:45:54.890  3837  3884 I jxcore-log: Total duration:  96529
08-16 14:45:54.890  3837  3884 I jxcore-log: 
,08-16 14:45:54.890  3837  3884 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 14:45:54.890  3837  3884 I jxcore-log: 
,08-16 14:45:54.894  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.894  3837  3884 I jxcore-log: 
08-16 14:45:54.897  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.897  3837  3884 I jxcore-log: 
08-16 14:45:54.899  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.899  3837  3884 I jxcore-log: 
08-16 14:45:54.900  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.900  3837  3884 I jxcore-log: 
08-16 14:45:54.901  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 14:45:54.901  3837  3884 I jxcore-log: 
08-16 14:45:54.903  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:45:54.903  3837  3884 I jxcore-log: 
08-16 14:45:54.906  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.906  3837  3884 I jxcore-log: 
08-16 14:45:54.908  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.908  3837  3884 I jxcore-log: 
08-16 14:45:54.909  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 14:45:54.909  3837  3884 I jxcore-log: 
08-16 14:45:54.910  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:45:54.910  3837  3884 I jxcore-log: 
08-16 14:45:54.911  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:45:54.911  3837  3884 I jxcore-log: 
08-16 14:45:54.911  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.911  3837  3884 I jxcore-log: 
08-16 14:45:54.912  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.912  3837  3884 I jxcore-log: 
08-16 14:45:54.914  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.914  3837  3884 I jxcore-log: 
08-16 14:45:54.914  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.914  3837  3884 I jxcore-log: 
08-16 14:45:54.916  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.916  3837  3884 I jxcore-log: 
08-16 14:45:54.917  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.917  3837  3884 I jxcore-log: 
08-16 14:45:54.918  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.918  3837  3884 I jxcore-log: 
08-16 14:45:54.919  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.919  3837  3884 I jxcore-log: 
08-16 14:45:54.920  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.920  3837  3884 I jxcore-log: 
08-16 14:45:54.922  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.922  3837  3884 I jxcore-log: 
,08-16 14:45:54.922  3837  3837 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 14:45:54.923  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.923  3837  3884 I jxcore-log: 
08-16 14:45:54.923  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.923  3837  3884 I jxcore-log: 
,08-16 14:45:54.924  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.924  3837  3884 I jxcore-log: 
08-16 14:45:54.925  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.925  3837  3884 I jxcore-log: 
08-16 14:45:54.926  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.926  3837  3884 I jxcore-log: 
08-16 14:45:54.927  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.927  3837  3884 I jxcore-log: 
08-16 14:45:54.929  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.929  3837  3884 I jxcore-log: 
08-16 14:45:54.930  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.930  3837  3884 I jxcore-log: 
08-16 14:45:54.930  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.930  3837  3884 I jxcore-log: 
08-16 14:45:54.931  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.931  3837  3884 I jxcore-log: 
08-16 14:45:54.931  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.931  3837  3884 I jxcore-log: 
08-16 14:45:54.932  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.932  3837  3884 I jxcore-log: 
08-16 14:45:54.932  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.932  3837  3884 I jxcore-log: 
08-16 14:45:54.933  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.933  3837  3884 I jxcore-log: 
08-16 14:45:54.933  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.933  3837  3884 I jxcore-log: 
08-16 14:45:54.934  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.934  3837  3884 I jxcore-log: 
08-16 14:45:54.934  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.934  3837  3884 I jxcore-log: 
08-16 14:45:54.935  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.935  3837  3884 I jxcore-log: 
08-16 14:45:54.935  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:45:54.935  3837  3884 I jxcore-log: 
,08-16 14:45:54.936  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.936  3837  3884 I jxcore-log: 
08-16 14:45:54.936  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:45:54.936  3837  3884 I jxcore-log: 
,08-16 14:45:54.937  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.937  3837  3884 I jxcore-log: 
08-16 14:45:54.937  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.937  3837  3884 I jxcore-log: 
,08-16 14:45:54.938  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.938  3837  3884 I jxcore-log: 
,08-16 14:45:54.939  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.939  3837  3884 I jxcore-log: 
08-16 14:45:54.939  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.939  3837  3884 I jxcore-log: 
08-16 14:45:54.940  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:45:54.940  3837  3884 I jxcore-log: 
08-16 14:45:54.940  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.940  3837  3884 I jxcore-log: 
,08-16 14:45:54.941  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 14:45:54.941  3837  3884 I jxcore-log: 
08-16 14:45:54.941  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.941  3837  3884 I jxcore-log: 
08-16 14:45:54.942  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:45:54.942  3837  3884 I jxcore-log: 
08-16 14:45:54.942  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 14:45:54.942  3837  3884 I jxcore-log: 
08-16 14:45:54.943  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-16 14:45:54.943  3837  3884 I jxcore-log: 
,08-16 14:45:54.944  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:45:54.944  3837  3884 I jxcore-log: 
08-16 14:45:54.944  3837  3884 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:45:54.944  3837  3884 I jxcore-log: 
,08-16 14:45:54.963  3837  4277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,08-16 14:45:55.535  4280  4280 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 14:45:55.539  4280  4280 D AndroidRuntime: CheckJNI is OFF
,08-16 14:45:55.575  4280  4280 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 14:45:55.616  4280  4280 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 14:45:55.639  4280  4280 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 14:45:55.651   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 14:45:55.652   875   888 I ActivityManager: Killing 3837:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 14:45:55.724   875  1295 W InputDispatcher: channel 'c8bc4b9 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-16 14:45:55.724   875  1295 E InputDispatcher: channel 'c8bc4b9 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-16 14:45:55.739   875  1708 D GraphicsStats: Buffer count: 2
08-16 14:45:55.739   875  1943 I WindowState: WIN DEATH: Window{c8bc4b9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:45:55.739   875  1943 W InputDispatcher: Attempted to unregister already unregistered input channel 'c8bc4b9 com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-16 14:45:55.740   875  1305 D WifiService: Client connection lost with reason: 4
,08-16 14:45:55.775   875   898 W PackageSettings: Skipping PackageSetting{d3a22d7 com.example.hello/10273} due to missing metadata
,08-16 14:45:55.803   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 14:45:55.804   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 14:45:55.805   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-16 14:45:55.805   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 14:45:55.805   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:55.805   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:55.805   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:45:55.805   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 14:45:55.805   875   898 I art     : Starting a blocking GC Explicit
08-16 14:45:55.806   875   888 I ActivityManager:   Force finishing activity ActivityRecord{7b2e3aa u0 com.test.thalitest/.MainActivity t2}
,08-16 14:45:55.815   875  1708 W ActivityManager: Spurious death for ProcessRecord{35340f6 0:com.test.thalitest/u0a0}, curProc for 3837: null
,08-16 14:45:55.849   875   898 I art     : Explicit concurrent mark sweep GC freed 54404(3MB) AllocSpace objects, 9(208KB) LOS objects, 33% free, 28MB/43MB, paused 766us total 42.317ms
,08-16 14:45:55.868   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 14:45:55.871  4280  4280 I art     : System.exit called, status: 0
,08-16 14:45:55.872  4280  4280 I AndroidRuntime: VM exiting with result code 0.
,08-16 14:45:55.878   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 14:45:55.902   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 14:45:55.905  4181  4181 D BluetoothMapAppObserver: onReceive
,08-16 14:45:55.906  4181  4181 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 14:45:55.910  1885  2286 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 14:45:55.912   875  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 14:45:55.913  3640  3640 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 14:45:55.914  1857  1857 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 14:45:55.925  1857  4291 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 14:45:55.931  1857  4291 I Decoder : createOrResetDecoder
,08-16 14:45:55.940  1933  1933 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 14:45:55.957  1503  1503 I ConfigService: onCreate
,08-16 14:45:55.990   875  1914 I ActivityManager: Start proc 4295:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 14:45:56.012  1857  4291 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 14:45:56.019   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 14:45:56.037   875  1943 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3837 uid 10000
,08-16 14:45:56.039  1857  1857 I Keyboard.Facilitator: onFinishInput()
,08-16 14:45:56.045  4295  4295 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 14:45:56.055  1948  2029 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 14:45:56.067  1857  4291 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 14:45:56.069   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 14:45:56.073   875  1381 I ActivityManager: Start proc 4308:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 14:45:56.073  1948  2029 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 14:45:56.073  1948  2029 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1948
08-16 14:45:56.073  1948  2029 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.073  1948  2029 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:45:56.070   875   887 E PackageManager: Failed to write settings, restoring backup
08-16 14:45:56.070   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 14:45:56.070   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 14:45:56.070   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 14:45:56.070   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 14:45:56.070   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 14:45:56.070   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.070   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.070   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:45:56.079   875   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 14:45:56.079   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-16 14:45:56.079   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 14:45:56.079   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:45:56.079   875   888 E DropBoxManagerService: 	... 13 more
,08-16 14:45:56.079   875  4314 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:45:56.079   875  4314 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:45:56.079   875  4314 E DropBoxManagerService: 	... 5 more
08-16 14:45:56.082  1948  2029 I Process : Sending signal. PID: 1948 SIG: 9
,08-16 14:45:56.093  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-16 14:45:56.093  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 14:45:56.094  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 14:45:56.094  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 14:45:56.100  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 14:45:56.100  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 14:45:56.100  1857  4291 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 14:45:56.100  1857  4291 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 14:45:56.100  1857  4291 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 14:45:56.101  1857  4291 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 14:45:56.101  1857  4291 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 14:45:56.101  1857  4291 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 14:45:56.129  4295  4295 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 14:45:56.146   875  1708 D GraphicsStats: Buffer count: 1
,08-16 14:45:56.146   875  2190 I WindowState: WIN DEATH: Window{7d8f228 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 14:45:56.157   875  1914 I ActivityManager: Start proc 4326:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 14:45:56.162  4295  4325 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 14:45:56.164   875  1708 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1948) has died
,08-16 14:45:56.164   875  1708 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 14:45:56.168   875  1708 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 14:45:56.186   875   888 I ActivityManager: Start proc 4338:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 14:45:56.198  4326  4326 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 14:45:56.215  4295  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.215  4295  4322 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102),
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.215  4295  4322 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:45:56.228  4338  4338 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:45:56.228  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 14:45:56.228  4338  4338 D AndroidRuntime: Shutting down VM
,08-16 14:45:56.236  4338  4338 E AndroidRuntime: FATAL EXCEPTION: main
08-16 14:45:56.236  4338  4338 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4338
08-16 14:45:56.236  4338  4338 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 14:45:56.236  4338  4338 E AndroidRuntime: 	... 10 more
,08-16 14:45:56.238  1503  1503 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 14:45:56.238   875  1943 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 14:45:56.238  1503  1503 D AndroidRuntime: Shutting down VM
,08-16 14:45:56.239  1503  1503 E AndroidRuntime: FATAL EXCEPTION: main
08-16 14:45:56.239  1503  1503 E AndroidRuntime: Process: com.google.process.gapps, PID: 1503
08-16 14:45:56.239  1503  1503 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: ,	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 14:45:56.239  1503  1503 E AndroidRuntime: 	... 8 more
,08-16 14:45:56.239   875  4354 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:45:56.239   875  4354 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:45:56.239   875  4354 E DropBoxManagerService: 	... 5 more
,08-16 14:45:56.243  4338  4338 I Process : Sending signal. PID: 4338 SIG: 9
08-16 14:45:56.246   875  4355 E DropBoxManagerService: Can't write: system_app_crash
08-16 14:45:56.246   875  4355 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 14:45:56.246   875  4355 E DropBoxManagerService: 	... 5 more
,08-16 14:45:56.249  1503  1503 I Process : Sending signal. PID: 1503 SIG: 9
,08-16 14:45:56.272   875  1938 I ActivityManager: Killing 3697:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 14:45:56.298  4295  4322 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 14:45:56.302   875  1305 D WifiService: Client connection lost with reason: 4
,08-16 14:45:56.304  1725  4353 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@8570200
,08-16 14:45:56.308  4295  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.308  4295  4325 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:45:56.308  4295  4325 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 14:45:56.308  4295  4325 E AndroidRuntime: Process: android.process.acore, PID: 4295
08-16 14:45:56.308  4295  4325 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 14:45:56.308  4295  4325 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 14:45:56.309  4295  4322 I Process : Sending signal. PID: 4295 SIG: 9
,08-16 14:45:56.320   875  1390 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4338) has died
,08-16 14:45:56.321   875  1390 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 14:45:56.329   875  2189 I ActivityManager: Process com.google.process.gapps (pid 1503) has died
,08-16 14:45:56.330   875  2189 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,08-16 14:45:56.330   875  2189 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
,08-16 14:45:56.330   875  2189 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
,08-16 14:45:56.346   875   888 I ActivityManager: Start proc 4357:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 14:45:56.346  1725  1725 W RocketImpressions: ClearcutLogger connection suspended: 1,
,08-16 14:45:56.353   875   886 I ActivityManager: Process android.process.acore (pid 4295) has died
,08-16 14:45:56.353   875   886 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30977ms
,08-16 14:45:56.368   875  2174 I ActivityManager: Start proc 4368:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
08-16 14:45:56.369   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 14:45:56.369   875  1942 W ActivityManager: Can't find mystery application for Crash from pid=4295 uid=10005: android.os.BinderProxy@e887e69

```
