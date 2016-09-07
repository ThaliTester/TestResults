#### Test 829120304bed7b1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 16:44:15.098  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:15.102  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 16:44:15.126  3803  3845 V GoogleAuthProtoRequest: [311] a.<init>: mAccountName set to: thalitester@gmail.com
09-07 16:44:15.181  1566  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-07 16:44:15.181  1566  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 16:44:15.182  1566  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:44:15.182  1566  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 16:44:15.219  3803  3845 W ExperimentUpdateService: [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 16:44:15.220  3803  3845 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
09-07 16:44:15.732  3846  3846 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 16:44:15.736  3846  3846 D AndroidRuntime: CheckJNI is OFF
09-07 16:44:15.771  3846  3846 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 16:44:15.814  3846  3846 I Radio-JNI: register_android_hardware_Radio DONE
09-07 16:44:15.833  3846  3846 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 16:44:15.838   871  2008 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 16:44:15.899   871  2008 I ActivityManager: Start proc 3855:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 16:44:15.905  3846  3846 D AndroidRuntime: Shutting down VM
09-07 16:44:16.032  3855  3855 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 16:44:16.071  3855  3855 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 16:44:16.081  3855  3855 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8344-8347)
09-07 16:44:16.081  3855  3855 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 16:44:16.098  3855  3855 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4e3fcc3}
09-07 16:44:16.099  3855  3855 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 16:44:16.099  3855  3855 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 16:44:16.106  3855  3855 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 16:44:16.108  3855  3855 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 16:44:16.134  3855  3855 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 16:44:16.148  3855  3855 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 16:44:16.148  3855  3855 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 16:44:16.148  3855  3855 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 16:44:16.148  3855  3855 I Adreno  : Build Date                       : 10/20/15
09-07 16:44:16.148  3855  3855 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 16:44:16.148  3855  3855 I Adreno  : Local Branch                     : M14
09-07 16:44:16.148  3855  3855 I Adreno  : Remote Branch                    : 
09-07 16:44:16.148  3855  3855 I Adreno  : Remote Branch                    : 
09-07 16:44:16.148  3855  3855 I Adreno  : Reconstruct Branch               : 
,09-07 16:44:16.225   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@502846a:true
,09-07 16:44:16.313  3855  3855 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 16:44:16.330  3855  3855 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 16:44:16.392  3855  3893 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 16:44:16.409  3855  3879 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 16:44:16.444  3855  3893 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 16:44:16.472  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-07 16:44:16.535   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +570ms (total +663ms)
,09-07 16:44:16.632  3855  3855 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3855
,09-07 16:44:16.827  3855  3855 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 16:44:16.969  3855  3895 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1667368656
,09-07 16:44:16.978  3855  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 16:44:16.978  3855  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 16:44:16.978  3855  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 16:44:16.978  3855  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 16:44:16.978  3855  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 16:44:16.978  3855  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc3cd56 added. We now have 1 listener(s)
,09-07 16:44:16.982  3855  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 16:44:16.983  3855  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:44:16.983  3855  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:44:16.983  3855  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 16:44:16.988  3855  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3d7dad added. We now have 1 listener(s)
,09-07 16:44:16.988  3855  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:44:16.996   871  1309 D WifiService: New client listening to asynchronous messages
,09-07 16:44:16.997  3855  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:44:16.997  3855  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 16:44:16.997  3855  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 16:44:16.997  3855  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-07 16:44:16.998  3855  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 16:44:17.001  3855  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:44:17.001  3855  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-07 16:44:17.006  3855  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:17.006  3855  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:44:17.006  3855  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 16:44:17.006  3855  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:44:17.007  3855  3895 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 16:44:17.014  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:44:17.016  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:17.038  3855  3855 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 16:44:17.501  3855  3864 I art     : Background sticky concurrent mark sweep GC freed 72543(6MB) AllocSpace objects, 17(1308KB) LOS objects, 29% free, 22MB/32MB, paused 666us total 118.446ms
,09-07 16:44:18.155  3855  3901 W jxcore-log: Initializing JXcore engine
,09-07 16:44:18.155  3855  3901 W jxcore-log: JXcore engine is ready
,09-07 16:44:18.198  3901  3901 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 16:44:18.198  3901  3901 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11654]" dev="sockfs" ino=11654 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 16:44:18.198  3901  3901 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 16:44:18.198  3901  3901 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28932]" dev="sockfs" ino=28932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 16:44:18.214  3855  3901 W jxcore-log: Starting JXcore engine
,09-07 16:44:18.296  3855  3901 W jxcore-log: Platform android
09-07 16:44:18.296  3855  3901 W jxcore-log: 
,09-07 16:44:18.297  3855  3901 W jxcore-log: Process ARCH arm
09-07 16:44:18.297  3855  3901 W jxcore-log: 
,09-07 16:44:18.502  3855  3901 I jxcore-log: JXcore Cordova bridge is ready!
09-07 16:44:18.502  3855  3901 I jxcore-log: 
,09-07 16:44:18.502  3855  3901 W jxcore-log: JXcore engine is started
,09-07 16:44:18.510  3855  3895 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 16:44:18.515  3855  3855 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 16:44:29.111  3722  3904 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:44:29.136  3722  3905 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:44:29.148  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:29.150  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:29.170  1566  3523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 16:44:29.170  1566  3523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:44:29.170  1566  3523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:44:29.170  1566  3523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:44:29.197  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:29.198  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:29.213  1566  1578 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:44:29.213  1566  1578 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:44:29.213  1566  1578 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:44:29.213  1566  1578 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:44:29.229  3722  3905 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:44:29.230  3722  3904 E BooksSync: Soft error
09-07 16:44:29.230  3722  3904 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:44:29.230  3722  3904 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:44:29.230  3722  3904 E BooksSync: Sync error
09-07 16:44:29.230  3722  3904 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:44:29.230  3722  3904 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:44:29.230  3722  3904 I BooksSync: Finished books sync
,09-07 16:44:29.237   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 321330, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:44:32.039  3855  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 16:44:32.039  3855  3901 I jxcore-log: 
,09-07 16:44:32.042  3855  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 16:44:32.042  3855  3901 I jxcore-log: 
,09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:32.059  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:44:32.062  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:44:32.065  3855  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 16:44:32.065  3855  3901 I jxcore-log: 
,09-07 16:44:32.066  3855  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 16:44:32.066  3855  3901 I jxcore-log: 
,09-07 16:44:32.412  3855  3901 I jxcore-log: Running unit tests
09-07 16:44:32.412  3855  3901 I jxcore-log: 
09-07 16:44:32.412  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:44:32.412  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66a7e29 added. We now have 2 listener(s)
,09-07 16:44:32.414  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:44:32.414  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:44:32.414  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:44:32.414  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:44:32.414  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7e65ae added. We now have 2 listener(s)
09-07 16:44:32.414  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:44:32.415  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:44:32.417  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:32.437  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:44:32.440  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:44:32.440  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:44:32.444  3855  3901 D executeNativeTests: Running unit tests
,09-07 16:44:32.449  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:32.457  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:32.503  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 16:44:32.503  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c added. We now have 3 listener(s)
09-07 16:44:32.504  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:44:32.504  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:44:32.504  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:44:32.504  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:44:32.505  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 added. We now have 3 listener(s)
09-07 16:44:32.505  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:44:32.505  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 16:44:32.508  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:32.524  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:44:32.532  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:44:32.532  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:44:32.534  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:32.537  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:32.539  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 16:44:32.540  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:44:32.540  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:44:32.540  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:44:32.545  3855  3901 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 16:44:32.546  3855  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 16:44:32.546  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 16:44:32.547  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:44:32.547  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:44:32.548  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:44:32.551  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:32.551  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:32.552  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:32.552  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:32.552  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.552  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:44:32.552  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:44:32.553  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c removed from the list
09-07 16:44:32.553  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:32.553  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 removed from the list
09-07 16:44:32.553  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:32.553  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.557  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:32.558  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.559  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:32.559  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:32.559  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:32.559  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:32.561  3855  3901 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 16:44:32.561  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:32.561  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:32.562  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:32.562  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:32.562  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.562  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.562  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:32.562  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:32.562  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:32.563  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:32.563  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.563  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.563  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.563  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.565  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:32.566  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:32.566  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:32.566  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 16:44:32.585  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 16:44:32.586  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 16:44:32.587  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 16:44:32.587  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:32.588  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:32.588  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:32.588  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:32.588  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.588  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.588  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:32.588  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:32.588  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:32.588  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:32.589  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.589  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.589  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:32.589  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:32.590  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:32.590  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:32.590  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:32.590  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:32.591  3855  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 16:44:32.593  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:32.600  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:44:32.603  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:44:32.604  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:44:32.605  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 16:44:32.606  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 16:44:32.606  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:44:32.606  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 16:44:32.606  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:44:32.606  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:44:32.609  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:32.613  3855  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 16:44:32.613  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 16:44:32.622  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:44:32.625  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 16:44:32.626  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:44:32.631  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-07 16:44:32.636  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-07 16:44:32.637  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 16:44:32.637  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 16:44:32.638  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 16:44:32.640  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:44:32.650  2707  2903 D BtGatt.GattService: registerClient() - UUID=84b8bf9c-c631-4a86-b8a6-e417fa46f7f1
,09-07 16:44:32.651  2707  2761 D BtGatt.GattService: onClientRegistered() - UUID=84b8bf9c-c631-4a86-b8a6-e417fa46f7f1, clientIf=5
,09-07 16:44:32.654  3855  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:44:32.656  2707  2721 D BtGatt.GattService: start scan with filters
,09-07 16:44:32.663  2707  2765 D BtGatt.ScanManager: handling starting scan
,09-07 16:44:32.663  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 16:44:32.663  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:44:32.664  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 16:44:32.664  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 16:44:32.665  2707  2765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:44:32.670  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:44:32.671  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:44:32.673  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:44:32.675  2707  2761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 16:44:32.676  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:32.677  2707  2765 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 16:44:32.683  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:44:32.686  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 16:44:32.687  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:32.688  2707  2765 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 16:44:32.688  2707  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:44:32.697  3855  3901 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 16:44:32.723  2707  2761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 16:44:32.723  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:32.746  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 16:44:32.747  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:33.173  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-07 16:44:33.174  3855  3855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 16:44:33.174  3855  3855 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:44:33.278   871  1929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:44:34.249  2707  2707 D BtGatt.ScanManager: awakened up at time 326515
,09-07 16:44:34.252  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:34.311  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-07 16:44:34.311  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:34.312  2707  2761 D BtGatt.GattService: current time is 326578309406
09-07 16:44:34.314  2707  2761 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -92, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -66, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -95, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:44:34.319  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 16:44:34.323  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 16:44:34.324  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-07 16:44:34.325  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:44:34.326  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 16:44:34.328  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:44:35.815  2707  2707 D BtGatt.ScanManager: awakened up at time 328081
,09-07 16:44:35.817  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:35.828  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 16:44:35.828  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:37.329  2707  2707 D BtGatt.ScanManager: awakened up at time 329595
,09-07 16:44:37.337  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:37.379  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-07 16:44:37.379  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:37.380  2707  2761 D BtGatt.GattService: current time is 329646450835
,09-07 16:44:37.381  2707  2761 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -76, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -87, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 16:44:37.383  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:44:37.385  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:44:37.386  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 16:44:37.389  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-07 16:44:37.389  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 16:44:37.391  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 16:44:37.710  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:44:37.711  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:37.711  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:44:37.711  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:37.712  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 16:44:37.712  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:44:37.712  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:44:37.712  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 16:44:37.713  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:44:37.715  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:44:37.715  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:44:37.718  3855  3901 D BluetoothAdapter: STATE_ON
09-07 16:44:37.720  2707  2720 D BtGatt.GattService: stopScan() - queue size =1
,09-07 16:44:37.722  2707  2903 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 16:44:37.724  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 16:44:37.725  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 16:44:37.725  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 16:44:37.725  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 16:44:37.726  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 16:44:37.730  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:44:37.731  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 16:44:37.732  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:44:37.732  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 16:44:37.735  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:44:37.739  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:44:37.739  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:44:37.739  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:44:37.740  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:37.741  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:37.741  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:44:37.741  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:37.741  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:37.742  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:37.742  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:37.742  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:37.750  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 16:44:37.750  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:37.751  2707  2765 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:44:37.766  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 16:44:37.766  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:37.766  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:37.775  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 16:44:37.775  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:38.241  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 16:44:42.745  3855  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 16:44:42.751  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:42.765  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:44:42.772  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:44:42.772  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:44:42.773  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:44:42.773  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 16:44:42.774  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 16:44:42.774  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:42.775  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:44:42.782  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:42.787  3855  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 16:44:42.787  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 16:44:42.790  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:42.801  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:44:42.803  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:44:42.803  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:44:42.814  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 16:44:42.815  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 16:44:42.815  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 16:44:42.819  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:44:42.827  2707  2720 D BtGatt.GattService: registerClient() - UUID=b3edcc15-0701-4d0c-924e-0e3363629055
,09-07 16:44:42.829  2707  2761 D BtGatt.GattService: onClientRegistered() - UUID=b3edcc15-0701-4d0c-924e-0e3363629055, clientIf=5
,09-07 16:44:42.831  3855  3866 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:44:42.832  2707  2895 D BtGatt.GattService: start scan with filters
,09-07 16:44:42.842  2707  2765 D BtGatt.ScanManager: handling starting scan
09-07 16:44:42.844  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 16:44:42.844  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:44:42.844  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 16:44:42.845  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 16:44:42.860  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:44:42.860  2707  2761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 16:44:42.860  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:44:42.861  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:44:42.861  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:42.861  2707  2765 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 16:44:42.867  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:44:42.878  3855  3901 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 16:44:42.883  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 16:44:42.884  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:42.885  2707  2765 D BtGatt.ScanManager: Starting BLE batch scan
09-07 16:44:42.885  2707  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:44:42.886  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-07 16:44:42.886  3855  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 16:44:42.887  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:42.887  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:44:42.887  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:42.887  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 16:44:42.887  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 16:44:42.887  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:44:42.887  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:44:42.887  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:44:42.887  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:44:42.887  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:44:42.888  3855  3901 D BluetoothAdapter: STATE_ON
09-07 16:44:42.889  2707  2720 D BtGatt.GattService: stopScan() - queue size =1
09-07 16:44:42.890  2707  2895 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 16:44:42.890  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 16:44:42.890  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 16:44:42.890  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 16:44:42.890  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 16:44:42.890  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 16:44:42.892  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:44:42.892  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 16:44:42.892  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:44:42.892  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 16:44:42.894  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:44:42.895  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:42.895  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:42.895  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:44:42.895  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
,09-07 16:44:42.895  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:44:42.895  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:42.897  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:42.897  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:42.897  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:44:42.897  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:42.898  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:44:42.898  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:42.898  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:42.901  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:42.902  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:42.902  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:42.902  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:42.903  3855  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 16:44:42.905  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:44:42.911  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:44:42.912  2707  2761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 16:44:42.912  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:42.914  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:44:42.914  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:44:42.914  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 16:44:42.914  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 16:44:42.915  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 16:44:42.915  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:42.915  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:44:42.919  3855  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 16:44:42.919  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 16:44:42.920  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 16:44:42.920  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:42.921  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:42.924  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:44:42.927  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:44:42.929  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-07 16:44:42.929  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 16:44:42.929  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 16:44:42.929  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:42.929  2707  2765 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:44:42.933  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 16:44:42.933  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 16:44:42.934  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 16:44:42.934  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:44:42.936  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 16:44:42.937  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:42.937  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 16:44:42.937  2707  2721 D BtGatt.GattService: registerClient() - UUID=2bd1ce27-fb5d-4775-a70c-268c346e2776
09-07 16:44:42.937  2707  2761 D BtGatt.GattService: onClientRegistered() - UUID=2bd1ce27-fb5d-4775-a70c-268c346e2776, clientIf=5
,09-07 16:44:42.938  3855  3865 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:44:42.939  2707  2720 D BtGatt.GattService: start scan with filters
,09-07 16:44:42.942  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 16:44:42.942  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:44:42.942  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-07 16:44:42.943  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 16:44:42.945  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 16:44:42.945  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:42.948  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:44:42.948  2707  2765 D BtGatt.ScanManager: handling starting scan
09-07 16:44:42.948  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:44:42.948  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:44:42.952  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:44:42.955  2707  2761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 16:44:42.955  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:42.956  2707  2765 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 16:44:42.958  3855  3901 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 16:44:42.961  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-07 16:44:42.962  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:42.962  2707  2765 D BtGatt.ScanManager: Starting BLE batch scan
09-07 16:44:42.962  2707  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:44:42.973  2707  2761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 16:44:42.973  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:42.979  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 16:44:42.979  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:43.449  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-07 16:44:43.450  3855  3855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:44:43.450  3855  3855 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:44:44.486  2707  2707 D BtGatt.ScanManager: awakened up at time 336752
,09-07 16:44:44.489  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:44.532  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-07 16:44:44.533  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:44.533  2707  2761 D BtGatt.GattService: current time is 336799492666
,09-07 16:44:44.534  2707  2761 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -96, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -89, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:44:44.535  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 16:44:44.536  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:44:44.537  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 16:44:44.538  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 16:44:44.538  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-07 16:44:44.539  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:44:46.037  2707  2707 D BtGatt.ScanManager: awakened up at time 338303
,09-07 16:44:46.045  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:46.067  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-07 16:44:46.067  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:44:46.067  2707  2761 D BtGatt.GattService: current time is 338334062563
09-07 16:44:46.068  2707  2761 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:44:46.068  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-07 16:44:46.068  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-07 16:44:46.069  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:44:47.572  2707  2707 D BtGatt.ScanManager: awakened up at time 339838
,09-07 16:44:47.574  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:47.625  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-07 16:44:47.626  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:47.626  2707  2761 D BtGatt.GattService: current time is 339892778916
,09-07 16:44:47.627  2707  2761 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -85, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -88, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 16:44:47.628  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 16:44:47.629  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 16:44:47.631  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-07 16:44:47.632  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-07 16:44:47.634  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 16:44:47.635  2707  2761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 16:44:47.958  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:47.959  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:47.959  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 16:44:47.959  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:47.960  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 16:44:47.960  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:44:47.961  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:44:47.961  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:44:47.961  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:44:47.962  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:44:47.962  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:44:47.964  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:44:47.966  2707  2895 D BtGatt.GattService: stopScan() - queue size =1
,09-07 16:44:47.969  2707  2721 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 16:44:47.971  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 16:44:47.971  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 16:44:47.973  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 16:44:47.974  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 16:44:47.975  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 16:44:47.978  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:44:47.978  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 16:44:47.979  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:44:47.979  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 16:44:47.979  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:44:47.981  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:44:47.981  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:44:47.981  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:44:47.986  2707  2761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 16:44:47.987  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:47.987  2707  2765 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:44:47.999  2707  2761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 16:44:48.000  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:48.000  2707  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:44:48.013  2707  2761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 16:44:48.013  2707  2761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:44:48.482  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-07 16:44:48.483  3855  3855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:48.483  3855  3855 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:44:52.368  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:52.390  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:52.398  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:44:52.485  1566  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 16:44:52.485  1566  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 16:44:52.486  1566  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:44:52.486  1566  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:44:52.536  1566  2327 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 16:44:52.536  1566  2327 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 16:44:52.536  1566  2327 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 16:44:52.536  1566  2327 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 16:44:52.536  1566  2327 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 16:44:52.536  1566  2327 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 16:44:52.536  1566  2327 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 16:44:52.550  3507  3542 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 16:44:52.550  3507  3542 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 16:44:52.550  3507  3542 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 16:44:52.550  3507  3542 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 16:44:52.550  3507  3542 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 16:44:52.550  3507  3542 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 16:44:52.550  3507  3542 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 16:44:52.983  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:52.984  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:52.984  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:52.985  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:52.986  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:52.986  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:44:52.986  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:52.987  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:52.987  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:52.987  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:52.988  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:52.993  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:52.993  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:52.998  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:52.998  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:44:52.998  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:52.999  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:53.001  3855  3901 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 16:44:53.003  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.003  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:53.004  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.004  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.004  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:53.005  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.005  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.005  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:53.005  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.006  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.006  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:53.006  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.006  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.007  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.008  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:53.009  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.009  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.009  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:53.012  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 16:44:53.012  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.013  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:53.013  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.013  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.013  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:53.014  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.014  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.014  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:53.015  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.015  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.015  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.015  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.015  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.016  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.018  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:53.018  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.018  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.019  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:53.020  3855  3901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-07 16:44:53.021  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:44:53.021  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:53.022  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.022  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:44:53.022  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.023  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.023  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
,09-07 16:44:53.023  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.024  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.024  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:44:53.024  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.024  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.024  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.025  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.026  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:53.027  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.027  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.027  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:53.029  3855  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-07 16:44:53.029  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.030  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:53.030  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.030  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.031  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:53.031  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.031  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.031  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:53.032  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.032  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.032  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.032  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.033  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.033  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.035  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:53.035  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.036  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.036  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:53.038  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 16:44:53.038  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 16:44:53.039  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:44:53.039  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 16:44:53.040  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:44:53.040  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 16:44:53.041  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 16:44:53.041  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 16:44:53.041  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 16:44:53.041  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.041  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:53.041  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:44:53.041  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 16:44:53.041  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.041  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.042  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
,09-07 16:44:53.042  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.042  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.042  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.042  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:53.042  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.042  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.042  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:53.043  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:53.044  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.044  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:53.044  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.045  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 16:44:53.045  3855  3901 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-07 16:44:53.045  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 16:44:53.050  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 16:44:53.050  3855  3901 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-07 16:44:53.050  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 16:44:53.050  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 16:44:53.050  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 16:44:53.050  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 16:44:53.051  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 16:44:53.052  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 16:44:53.053  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 16:44:53.053  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-07 16:44:53.053  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 16:44:53.053  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 16:44:53.054  3855  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 16:44:53.054  3855  3901 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 16:44:53.054  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 16:44:53.054  3855  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 16:44:53.054  3855  3901 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 16:44:53.054  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 16:44:53.054  3855  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 16:44:53.054  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 16:44:53.057  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 16:44:53.058  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 16:44:53.058  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 16:44:53.059  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 16:44:53.059  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 16:44:53.059  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 16:44:53.059  3855  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 16:44:53.059  3855  3901 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 16:44:53.060  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.060  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:53.061  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.061  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.061  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.061  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.061  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 16:44:53.061  3855  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
09-07 16:44:53.062  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.062  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.062  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.062  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.063  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.063  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.063  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.063  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.065  3855  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
09-07 16:44:53.065  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:53.065  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.065  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.065  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.066  3855  3910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:44:53.066  3855  3901 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 16:44:53.067  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.067  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:53.067  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.067  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.068  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.068  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.068  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.068  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.068  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.068  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.068  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.068  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.068  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.069  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.070  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:53.070  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.070  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.070  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.072  3855  3901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 16:44:53.072  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.073  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:53.073  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.074  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.074  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.075  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.075  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.075  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.075  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.076  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.076  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.076  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.076  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.077  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.078  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:53.078  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.078  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.079  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.079  3855  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 16:44:53.080  3855  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 16:44:53.080  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 16:44:53.080  3855  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 16:44:53.080  3855  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 16:44:53.080  3855  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 16:44:53.080  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 16:44:53.080  3855  3901 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 16:44:53.081  3855  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 16:44:53.081  3855  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 16:44:53.081  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 16:44:53.081  3855  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 16:44:53.081  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:53.081  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:53.082  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:53.082  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.082  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.082  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.082  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.082  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.082  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.082  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.082  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.083  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.083  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.083  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.084  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:53.084  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:53.084  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.084  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.085  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:53.085  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.086  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:53.086  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:53.086  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:53.086  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:53.086  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:53.086  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:53.086  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.087  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:58.088  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:58.088  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.088  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.089  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.091  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
,09-07 16:44:58.092  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:58.092  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:58.094  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:58.094  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.095  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.096  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.097  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:58.098  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.101  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:58.101  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:44:58.102  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:58.103  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.104  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:58.104  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.107  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:58.107  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:44:58.108  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.108  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.112  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 16:44:58.113  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:44:58.115  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 16:44:58.117  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 16:44:58.117  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 16:44:58.118  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 16:44:58.118  3855  3855 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 16:44:58.118  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:44:58.119  3855  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:44:58.119  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.119  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 16:44:58.120  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 16:44:58.120  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 16:44:58.120  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.121  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 16:44:58.121  3855  3855 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 16:44:58.121  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:58.121  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.121  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 16:44:58.122  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:44:58.122  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:44:58.122  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.123  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.124  3855  3912 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 16:44:58.125  3855  3912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 16:44:58.125  3855  3912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 16:44:58.125  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:44:58.125  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:44:58.125  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:44:58.125  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.125  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:44:58.126  3855  3855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 16:44:58.126  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:58.126  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:58.126  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:44:58.126  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.127  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.127  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.127  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
,09-07 16:44:58.128  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.128  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:58.128  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:44:58.128  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.129  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.129  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.129  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.132  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:58.132  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:58.132  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.132  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.135  3855  3901 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-07 16:44:58.136  3855  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 16:44:58.136  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 16:44:58.137  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 16:44:58.137  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 16:44:58.138  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:44:58.138  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 16:44:58.138  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:58.138  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.138  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.138  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.138  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:58.138  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:58.138  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:58.138  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:58.138  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.138  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.139  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.139  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.140  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:58.140  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:58.141  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.141  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.144  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:44:58.144  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:58.144  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:44:58.145  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.145  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.145  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.145  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:58.145  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:44:58.145  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
09-07 16:44:58.145  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:58.145  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.145  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.145  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.146  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.149  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:44:58.150  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:44:58.150  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.151  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.153  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:44:58.153  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:44:58.153  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:44:58.154  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:44:58.154  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:44:58.154  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:44:58.155  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b74f0c not in the list
09-07 16:44:58.155  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.155  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.155  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:44:58.155  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:58.156  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.156  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:44:58.156  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:44:58.158  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:44:58.158  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:44:58.158  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:44:58.158  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a8055 not in the list
,09-07 16:44:58.159  3855  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 16:44:58.159  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-07 16:44:58.159  3855  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 16:44:58.159  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 16:44:58.160  3855  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 16:44:58.160  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 16:44:58.162  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 16:44:58.162  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-07 16:44:58.164  3855  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-07 16:44:58.164  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 16:44:58.164  3855  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 16:44:58.164  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 16:44:58.164  3855  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 16:44:58.164  3855  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-07 16:44:58.165  3855  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 16:44:58.165  3855  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 16:44:58.165  3855  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-07 16:44:58.165  3855  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 16:44:58.166  3855  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 16:44:58.166  3855  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-07 16:44:58.167  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:44:58.167  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@efd12f added. We now have 3 listener(s)
,09-07 16:44:58.167  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:44:58.169  3855  3901 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 16:44:58.169   871  2011 D WifiService: setWifiEnabled: true pid=3855, uid=10000
09-07 16:44:58.169   871  2011 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:44:58.198  2707  2884 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-07 16:44:58.198  2707  2892 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-07 16:44:58.198  3855  3910 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
,09-07 16:44:58.627  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 16:45:03.176  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 16:45:03.177  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@132933c added. We now have 4 listener(s)
,09-07 16:45:03.177  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:45:03.195  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:45:03.195  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@132933c removed from the list
,09-07 16:45:03.195  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:45:03.196  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:45:03.196  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:45:03.198  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 16:45:03.199  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7cd28c5 added. We now have 4 listener(s)
,09-07 16:45:03.199  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:45:03.202  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:45:03.203  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7cd28c5 removed from the list
,09-07 16:45:03.203  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:45:03.203  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:45:03.204  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:45:03.207  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:45:03.207  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@224921a added. We now have 4 listener(s)
,09-07 16:45:03.207  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:45:03.214   871  1376 D WifiService: setWifiEnabled: false pid=3855, uid=10000
,09-07 16:45:03.214   871  1376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:45:03.228  2707  2757 D BluetoothAdapterState: Current state: ON, message: 23
09-07 16:45:03.228  2707  2757 D BluetoothAdapterProperties: Setting state to 13
09-07 16:45:03.229  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 16:45:03.230  2707  2757 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 16:45:03.231  2707  2757 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:03.231  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:45:03.235  2707  2761 D BluetoothAdapterProperties: Scan Mode:20
,09-07 16:45:03.236  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 16:45:03.239  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 16:45:03.241   871  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 16:45:03.241   871  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-07 16:45:03.241   871  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:45:03.241   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 16:45:03.242  2707  2707 D BluetoothMapService: onReceive
,09-07 16:45:03.242  2707  2707 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 16:45:03.243  2707  2707 D BluetoothMapService: STATE_TURNING_OFF
09-07 16:45:03.243  2707  2707 D BluetoothMapService: MAP Service closeService in
,09-07 16:45:03.244  2707  2707 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 16:45:03.244  2707  2707 D ObexServerSockets0: shutdown(block = true)
09-07 16:45:03.246  2707  2904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-07 16:45:03.246  2707  2707 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 16:45:03.248  2707  2905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 16:45:03.248  2707  2892 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 16:45:03.248  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.248  2707  2707 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 16:45:03.249  2707  2707 I BtOppRfcommListener: stopping Accept Thread
09-07 16:45:03.250  2707  3421 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 16:45:03.250  2707  3421 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 16:45:03.250   871  1308 E native  : do suspend true
,09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:03.251  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:03.251  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:45:03.252  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:03.252  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:45:03.256  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.260  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.262   871   884 I ActivityManager: Start proc 3916:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-07 16:45:03.263   871  1934 D DhcpClient: Clearing IP address
,09-07 16:45:03.264   372   869 D CommandListener: Clearing all IP addresses on wlan0
09-07 16:45:03.265  2707  2707 D HeadsetService: Received stop request...Stopping profile...
,09-07 16:45:03.266   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:03.269  1566  2164 V NativeCrypto: Read error: ssl=0x9b75a000: I/O error during system call, Connection timed out
,09-07 16:45:03.269  2707  2707 D A2dpService: Received stop request...Stopping profile...
09-07 16:45:03.270  2707  2898 D A2dpStateMachine: Exit Disconnected: -1
09-07 16:45:03.270  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.270  1976  1990 D BluetoothHeadset: Proxy object disconnected
,09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:03.270  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:45:03.271   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 16:45:03.271   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 16:45:03.271  1364  1378 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:03.271  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.271   871   871 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:03.271  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:03.271   871   871 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:03.271   871   871 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:03.273   871   871 D BluetoothA2dp: Proxy object disconnected
09-07 16:45:03.273  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.273  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:03.274   395   395 E Parcel  : Reading a NULL string not supported here.
09-07 16:45:03.274  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.274  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:03.275   871  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 16:45:03.275  2707  2707 D HidService: Received stop request...Stopping profile...
09-07 16:45:03.275  2707  2707 D HidService: Stopping Bluetooth HidService
09-07 16:45:03.275   871  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 16:45:03.275   871  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:45:03.275   871  1308 E native  : do suspend true
09-07 16:45:03.276  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.276  3855  3855 V io.jxcore.node.Connect,ivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.276  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:03.278  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.278  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:03.279  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-07 16:45:03.279  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-07 16:45:03.280  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-07 16:45:03.280  1364  1364 D HidProfile: Bluetooth service disconnected
09-07 16:45:03.280  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.280  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:03.280  2707  2707 D HealthService: Received stop request...Stopping profile...
09-07 16:45:03.281  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.281  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:03.282  2707  2707 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:03.282  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.282  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.282  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:03.283  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.283  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:03.283  2707  2707 D PanService: Received stop request...Stopping profile...
09-07 16:45:03.284  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconn,ected
09-07 16:45:03.284  1364  1364 D PanProfile: Bluetooth service disconnected
09-07 16:45:03.285  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.285  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:03.285  2707  2707 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 16:45:03.285  2707  2707 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 16:45:03.285  2707  2761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 16:45:03.286  2707  2707 D BluetoothMapService: Received stop request...Stopping profile...
09-07 16:45:03.286  2707  2707 D BluetoothMapService: stop()
09-07 16:45:03.286  1566  2164 V NativeCrypto: SSL shutdown failed: ssl=0x9b75a000: I/O error during system call, Broken pipe
09-07 16:45:03.286  2707  2707 D BluetoothMapAppObserver: deinitObservers()
09-07 16:45:03.286  2707  2707 D BluetoothMapAppObserver: removeReceiver()
09-07 16:45:03.287  2707  2884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:03.287  2707  2884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:03.287  2707  2884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:03.287  2707  2761 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 16:45:03.288  1364  1364 D BluetoothMap: Proxy object disconnected
09-07 16:45:03.288  1364  1364 D MapProfile: Bluetooth service disconnected
09-07 16:45:03.289  2707  2707 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:03.289  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.289  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.289  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:03.290  2707  2761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 16:45:03.290  2707  2884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:03.290  2707  2884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:03.290  2707  2884 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 16:45:03.290  2707  2884 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 16:45:03.290  2707  2884 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 16:45:03.290  2707  2884 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 16:45:03.290  2707  2707 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:03.290  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.290  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.290  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:03.291  2707  2707 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 16:45:03.291  2707  2761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 16:45:03.291  2707  2707 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 16:45:03.292  2707  2707 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:03.292  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.292  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.292  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:03.292  2707  2707 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 16:45:03.292  2707  2761 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 16:45:03.292  2707  2707 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 16:45:03.293  2707  2707 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:03.293  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.293  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.293  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:03.293  2707  2707 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 16:45:03.293  2707  2707 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 16:45:03.294   871  1938 D DhcpClient: Receive thread stopped
09-07 16:45:03.294  2707  2707 D BluetoothMapService: MAP Service closeService in
09-07 16:45:03.294  2707  2707 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:03.294  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.294  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.294  2707  2707 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:03.295  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 16:45:03.295  2707  2757 D BluetoothAdapterProperties: Setting state to 15
09-07 16:45:03.295  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 16:45:03.295  2707  2757 I BluetoothAdapterState: Entering BleOnState
09-07 16:45:03.295   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:45:03.295  2707  2707 D BluetoothMapService: cleanup()
09-07 16:45:03.295  2707  2707 D BluetoothMapService: MAP Service closeService in
09-07 16:45:03.296   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:03.296  1364  2081 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:03.296  1364  1377 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 16:45:03.297  1976  1989 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:03.297  1364  1378 D BluetoothMap: onBluetoothStateChange: up=false
09-07 16:45:03.297   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:03.298  1364  2081 D BluetoothPan: onBluetoothStateChange on: false
09-07 16:45:03.298  1364  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 16:45:03.298  1364  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 16:45:03.299   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:03.299  2707  2757 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 16:45:03.299  2707  2757 D BluetoothAdapterProperties: Setting state to 16
09-07 16:45:03.299  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 16:45:03.299  2707  2757 D BluetoothAdapterProperties: onBleDisable
09-07 16:45:03.299  2707  2757 I BluetoothAdapterState: Entering PendingCommandState
09-07 16:45:03.300  2707  2758 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 16:45:03.300  2707  2761 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:45:03.301  2707  2884 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 16:45:03.301  2707  2884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:03.301  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.302  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.303  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.304  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.305  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.307  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.315   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 16:45:03.336   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 16:45:03.336   372   869 D CommandListener: Clearing all IP addresses on wlan0
09-07 16:45:03.337   871  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 16:45:03.337   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 16:45:03.338   871  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 16:45:03.339   871   888 D Tethering: MasterInitialState.processMessage what=3
09-07 16:45:03.342  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.343  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.344  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:03.345  3407  3407 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8d8a4f5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-07 16:45:03.348  3916  3916 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 16:45:03.356   871  1308 D WifiConfigStore: Retrieve network priorities after PNO.
09-07 16:45:03.359  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.359  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:03.359  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.359  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:03.360   871  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 16:45:03.359  2152  2342 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 16:45:03.361  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.361  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:03.361  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.361  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:03.363  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:03.363  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:03.364  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:03.364  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:03.369  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 16:45:03.373   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad6239:true
09-07 16:45:03.374  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:45:03.387   871  1993 I ActivityManager: Start proc 3936:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 16:45:03.392   372   869 E Netd    : netlink response contains error (No such file or directory)
,09-07 16:45:03.394   871  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 16:45:03.399  3916  3916 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 16:45:03.401  3916  3916 D BluetoothMap: Create BluetoothMap proxy object
,09-07 16:45:03.411  3916  3916 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 16:45:03.416  3936  3936 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 16:45:03.426  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:45:03.438   871  1393 I ActivityManager: Killing 3062:com.google.android.talk/u0a61 (adj 15): empty #17
,09-07 16:45:03.509  2707  2761 I bt_hci  : shut_down
,09-07 16:45:03.514  2707  2767 I bt_vendor: low_power_mode_cb
,09-07 16:45:03.517  2707  2767 D bt_hwcfg: hw_epilog_process
,09-07 16:45:03.533  2707  2767 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 16:45:03.533  2707  2767 I bt_vendor: epilog_cb
09-07 16:45:03.533  2707  2767 I bt_hci  : epilog_finished_callback
,09-07 16:45:03.535  2707  2761 I bt_hci_h4: hal_close
,09-07 16:45:03.536  2707  2761 I bt_userial_vendor: device fd = 51 close
,09-07 16:45:03.617  3936  3936 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.617  3936  3936 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.617  3936  3936 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.617  3936  3936 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.617  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.618  3936  3936 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.618  3936  3936 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.618  3936  3936 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:45:03.618  3936  3936 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread$H.,handleMessage(ActivityThread.java:1405)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:45:03.618  3936  3936 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 16:45:03.647   871  2007 I ActivityManager: Start proc 3966:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-07 16:45:03.648   871  2007 I ActivityManager: Killing 3407:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 16:45:03.813  2707  2758 D bt_stack_manager: event_shut_down_stack finished.
,09-07 16:45:03.813  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-07 16:45:03.817  3966  3966 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-07 16:45:03.818  2707  2757 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 16:45:03.818  2707  2707 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 16:45:03.819  2707  2707 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 16:45:03.820  2707  2707 D BtGatt.GattService: stop()
09-07 16:45:03.820  2707  2707 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 16:45:03.824  2707  2707 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:03.824  2707  2707 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:03.824  2707  2707 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:03.825  2707  2707 V BluetoothAdapterState: isBleTurningOff()=true
09-07 16:45:03.825  2707  2757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 16:45:03.826  2707  2757 D BluetoothAdapterProperties: Setting state to 10
09-07 16:45:03.826  2707  2757 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 16:45:03.827  2707  2757 I BluetoothAdapterState: Entering OffState
,09-07 16:45:03.828   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 16:45:03.845  2707  2707 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-07 16:45:03.845  2707  2707 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 16:45:03.845  2707  2707 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 16:45:03.846  2707  2758 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 16:45:03.848  2707  2758 D bt_stack_manager: event_clean_up_stack finished.
,09-07 16:45:03.853  2707  2707 I art     : System.exit called, status: 0
09-07 16:45:03.854  2707  2707 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 16:45:03.929   871   881 I ActivityManager: Process com.android.bluetooth (pid 2707) has died
,09-07 16:45:03.975  3936  3962 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 16:45:04.061  3966  3987 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-07 16:45:04.061  3966  3987 I Babel_SMS: MmsConfig.loadMmsSettings
,09-07 16:45:04.070  3966  3987 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
09-07 16:45:04.070  3966  3987 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 16:45:04.102  3966  3987 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-07 16:45:04.102  3966  3987 I Babel_SMS: MmsConfig.loadFromResources
,09-07 16:45:04.105  3966  3987 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-07 16:45:04.106  3966  3987 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-07 16:45:04.130  3966  3966 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 16:45:04.138  3966  3966 I Babel_Crash: startup - clean
,09-07 16:45:04.166  3966  3966 I Babel_telephony: TeleModule.launchCompleted
,09-07 16:45:04.169   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a2a51:true
,09-07 16:45:04.178   871  1943 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-07 16:45:04.190  3966  3966 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-07 16:45:04.198  3966  3966 W Babel   : BAM#gBA: invalid account id: -1
09-07 16:45:04.198  3966  3966 W Babel   : BAM#gBA: invalid account id: -1
09-07 16:45:04.198  3966  3966 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-07 16:45:04.200  3966  3992 I Babel   : deleted: false for 0
,09-07 16:45:04.216   871   882 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-07 16:45:04.237  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:45:04.272   871  1943 I ActivityManager: Start proc 3995:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-07 16:45:04.274  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:45:04.288  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:45:04.354  3966  3966 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 16:45:04.359  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:45:04.368  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:45:04.381  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:45:04.391  3966  3966 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 16:45:04.401  3966  3966 I vclib   : onServiceConnected
,09-07 16:45:04.419  3995  3995 D AdapterServiceConfig: Adding HeadsetService
,09-07 16:45:04.419  3995  3995 D AdapterServiceConfig: Adding A2dpService
,09-07 16:45:04.419  3995  3995 D AdapterServiceConfig: Adding HidService
,09-07 16:45:04.419  3995  3995 D AdapterServiceConfig: Adding HealthService
,09-07 16:45:04.419  3995  3995 D AdapterServiceConfig: Adding PanService
,09-07 16:45:04.420  3995  3995 D AdapterServiceConfig: Adding GattService
,09-07 16:45:04.420  3995  3995 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 16:45:04.424   871  1993 I ActivityManager: Killing 3455:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 16:45:04.483  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 16:45:04.503  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 16:45:04.511  1752  1752 D SystemUpdateService: onCreate
,09-07 16:45:04.519  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 16:45:04.530  1752  4007 I SystemUpdateService: active receiver: enabled
,09-07 16:45:04.534  1752  4007 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 16:45:04.541  1752  4007 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 16:45:04.541  1752  4007 I SystemUpdateService: now status is 0 (complete)
09-07 16:45:04.541  1752  4007 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 16:45:04.541  1752  4007 I SystemUpdateService: file has been verified
09-07 16:45:04.541  1752  4007 I SystemUpdateService: OTA package size = 12249756
,09-07 16:45:04.547  1752  4007 I SystemUpdateService: showing system update notification
,09-07 16:45:04.574  1752  1752 D SystemUpdateService: onDestroy
,09-07 16:45:04.581  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 16:45:04.585  1752  2433 I iu.UploadsManager: num queued entries: 0
09-07 16:45:04.586  1752  2433 I iu.UploadsManager: num updated entries: 0
09-07 16:45:04.586  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 16:45:04.586  1752  2433 I iu.SyncManager: NEXT; no task
,09-07 16:45:04.588  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:45:04.606   871  1993 I ActivityManager: Start proc 4009:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 16:45:04.634  4009  4009 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 16:45:04.636  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:04.642  4009  4009 D SprintDMHelper: simOperator: 
09-07 16:45:04.642  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:45:04.670   871  1943 I ActivityManager: Start proc 4021:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 16:45:04.671   871  1943 I ActivityManager: Killing 1681:android.process.acore/u0a5 (adj 15): empty #17
,09-07 16:45:04.869   871  1943 I ActivityManager: Start proc 4036:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 16:45:04.874  3966  4035 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-07 16:45:04.883   871  2003 I ActivityManager: Killing 3625:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 16:45:04.946  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 16:45:05.009  4036  4036 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 16:45:05.009  4036  4036 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 16:45:05.009  4036  4036 I GAv4    :   adb logcat -s GAv4
,09-07 16:45:05.025  4036  4036 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 16:45:05.031  4036  4036 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 16:45:05.057  4036  4053 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 16:45:05.170  4036  4036 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 16:45:05.210  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 16:45:05.226  4036  4036 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 7482-7491)
,09-07 16:45:05.226  4036  4036 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 16:45:05.235  4036  4036 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d35dec7}
,09-07 16:45:05.235  4036  4036 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 16:45:05.236  4036  4036 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 16:45:05.244  4036  4036 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 16:45:05.245  4036  4036 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 16:45:05.263  4036  4036 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 16:45:05.278  4036  4036 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 16:45:05.278  4036  4036 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 16:45:05.278  4036  4036 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 16:45:05.278  4036  4036 I Adreno  : Build Date                       : 10/20/15
09-07 16:45:05.278  4036  4036 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 16:45:05.278  4036  4036 I Adreno  : Local Branch                     : M14
09-07 16:45:05.278  4036  4036 I Adreno  : Remote Branch                    : 
09-07 16:45:05.278  4036  4036 I Adreno  : Remote Branch                    : 
09-07 16:45:05.278  4036  4036 I Adreno  : Reconstruct Branch               : 
,09-07 16:45:05.331  4036  4082 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 16:45:05.349  4036  4036 I NSApplication: Starting up...
,09-07 16:45:05.393   871  1943 I ActivityManager: Start proc 4087:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 16:45:05.394   871  1943 I ActivityManager: Killing 3640:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 16:45:05.452  4087  4087 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 16:45:05.655   871  1993 I ActivityManager: Killing 3473:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 16:45:08.254   871  2003 D WifiService: setWifiEnabled: true pid=3855, uid=10000,
09-07 16:45:08.255   871  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:45:08.292  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:08.292  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:08.292  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:08.292  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:08.294  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:08.294  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:08.294  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:08.294  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:08.296  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:08.296  3855  3855 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-07 16:45:08.296  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:08.296  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:08.297   871  1308 D WifiConfigStore: Loading config and enabling all networks 
,09-07 16:45:08.312   871  1308 D WifiConfigStore: loaded 0 passpoint configs
,09-07 16:45:08.313   871  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 16:45:08.314   871  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 16:45:08.314   871  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 16:45:08.315   871  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 16:45:08.315   871  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 16:45:08.315   871  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 16:45:08.330   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 16:45:08.331   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:08.331   871  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:45:08.331   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 16:45:08.331   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 16:45:08.343   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 16:45:08.343   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 16:45:08.344   871  1308 E native  : do suspend true
,09-07 16:45:08.358   871  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:45:08.982   871  2008 I ActivityManager: Killing 3664:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 16:45:09.672   871  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:45:09.730   871  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.50 rxSuccessRate=14.94 delta 1000 -> 994
,09-07 16:45:09.732   871  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 16:45:09.732   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:45:09.747   871  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 16:45:09.798   871  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 16:45:09.800  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 16:45:10.544  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 16:45:10.571  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 16:45:10.571  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 16:45:10.575   871  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:45:10.583   871  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 16:45:10.583   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 16:45:10.584   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 16:45:10.607   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:45:10.619   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:10.620   871  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 16:45:10.629   871  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 16:45:10.669   871  4112 D DhcpClient: Receive thread started
,09-07 16:45:10.755   871  1308 E native  : do suspend false
,09-07 16:45:10.774   871  1934 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 16:45:10.789   871  4112 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172460, domain null
,09-07 16:45:10.790   871  1934 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172460 seconds
,09-07 16:45:10.796   871  1934 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 16:45:10.820   871  4112 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 16:45:10.821   871  1934 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 16:45:10.828   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:10.840   871  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 16:45:10.841   871  1934 D DhcpClient: Scheduling renewal in 86399s
,09-07 16:45:10.845   871  1308 E native  : do suspend true
,09-07 16:45:10.865   871  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 16:45:10.868   871  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 16:45:10.869   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 16:45:10.871   871  1310 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 16:45:10.875   871  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 16:45:10.928   871  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 16:45:10.928   871  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 16:45:10.932   871  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 16:45:10.936   871  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 16:45:10.938   871  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 16:45:10.952   871  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 16:45:10.959   871  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 16:45:10.959   871  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 16:45:10.959   871  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 16:45:10.959   871  1310 D ConnectivityService:    accepting network in place of null
,09-07 16:45:10.959   871  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 16:45:10.961   871  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 16:45:10.961   871  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 16:45:10.972   871  4110 D NetlinkSocketObserver: NeighborEvent{elapsedMs=363237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 16:45:10.995   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:45:11.025   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:45:11.030   871  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 16:45:11.030   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:11.036   871  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 16:45:11.037   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-07 16:45:11.051   871  4109 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 16:45:11.053  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:11.053  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:11.053  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:11.053  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:11.055  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:11.055  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:11.055  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:11.055  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:11.059  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:11.059  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:11.059  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:45:11.060  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:45:11.075  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 16:45:11.079  1752  1752 D SystemUpdateService: onCreate
,09-07 16:45:11.085  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 16:45:11.108  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 16:45:11.110  1752  2433 I iu.UploadsManager: num queued entries: 0
,09-07 16:45:11.114  1752  4123 I SystemUpdateService: active receiver: enabled
,09-07 16:45:11.116   871  4109 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 14:45:11 GMT], X-Android-Received-Millis=[1473259511115], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473259511093]}
,09-07 16:45:11.119   871  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 16:45:11.119   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-07 16:45:11.119   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-07 16:45:11.120   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 16:45:11.124  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 16:45:11.125  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:45:11.128  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:11.134  1752  4126 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 16:45:11.135  1752  4126 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 16:45:11.136  4009  4009 D SprintDMHelper: simOperator: 
09-07 16:45:11.136  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:45:11.142  1752  4126 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:45:11.146  1752  2433 I iu.UploadsManager: num updated entries: 0
,09-07 16:45:11.148  1752  4123 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 16:45:11.155  1752  2433 I iu.SyncManager: NEXT; no task
,09-07 16:45:11.163  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:45:11.169  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:45:11.171  1752  4123 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 16:45:11.171  1752  4123 I SystemUpdateService: now status is 0 (complete)
09-07 16:45:11.171  1752  4123 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 16:45:11.171  1752  4123 I SystemUpdateService: file has been verified
,09-07 16:45:11.183  1752  4123 I SystemUpdateService: OTA package size = 12249756
,09-07 16:45:11.212  1752  4123 I SystemUpdateService: showing system update notification
,09-07 16:45:11.234  1566  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 16:45:11.234  1566  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 16:45:11.234  1566  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:45:11.234  1566  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:45:11.245  1752  1752 D SystemUpdateService: onDestroy
,09-07 16:45:11.258  3966  4129 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 16:45:11.262  1752  4126 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-07 16:45:12.032   871  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 16:45:13.264   871  2007 D WifiService: setWifiEnabled: false pid=3855, uid=10000
,09-07 16:45:13.264   871  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:45:13.307  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 16:45:13.318   871  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 16:45:13.318   871  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 16:45:13.319   871  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 16:45:13.319   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:45:13.340   871  1308 E native  : do suspend true
,09-07 16:45:13.352   871  1934 D DhcpClient: Clearing IP address
,09-07 16:45:13.352   372   869 D CommandListener: Clearing all IP addresses on wlan0
,09-07 16:45:13.356   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:13.364   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 16:45:13.364   871  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 16:45:13.364   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-07 16:45:13.365   871  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 16:45:13.365   871  1308 E native  : do suspend true
09-07 16:45:13.366  1566  4134 V NativeCrypto: Read error: ssl=0x9a63f000: I/O error during system call, Connection timed out
,09-07 16:45:13.369  1566  4134 V NativeCrypto: SSL shutdown failed: ssl=0x9a63f000: I/O error during system call, Broken pipe
09-07 16:45:13.373   395   395 E Parcel  : Reading a NULL string not supported here.
,09-07 16:45:13.388   871  4112 D DhcpClient: Receive thread stopped
09-07 16:45:13.388   372   869 D CommandListener: Clearing all IP addresses on wlan0
,09-07 16:45:13.391   871  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 16:45:13.393   871  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:45:13.410   871  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:45:13.411  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:13.411  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:13.411  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:13.411  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:13.412  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:13.412  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:13.412  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:13.412  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:13.413  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:13.413  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:13.413  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:13.413  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:13.413  2152  2342 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 16:45:13.414   871  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 16:45:13.427   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 16:45:13.448   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-07 16:45:13.449   871  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 16:45:13.449   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:13.452   871   888 D Tethering: MasterInitialState.processMessage what=3
09-07 16:45:13.453  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:13.454  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:13.455  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:13.462  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 16:45:13.466  1752  1752 D SystemUpdateService: onCreate
09-07 16:45:13.473  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-07 16:45:13.476  1752  4145 I SystemUpdateService: active receiver: enabled
09-07 16:45:13.485  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-07 16:45:13.491  1752  4145 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-07 16:45:13.492  1752  2433 I iu.UploadsManager: num queued entries: 0
09-07 16:45:13.492  1752  2433 I iu.UploadsManager: num updated entries: 0
09-07 16:45:13.493  1752  2433 I iu.SyncManager: NEXT; no task
,09-07 16:45:13.495  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 16:45:13.496  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:45:13.499  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:13.503  4009  4009 D SprintDMHelper: simOperator: 
,09-07 16:45:13.504  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:45:13.519  1752  4145 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-07 16:45:13.519  1752  4145 I SystemUpdateService: now status is 0 (complete)
09-07 16:45:13.519  1752  4145 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 16:45:13.536  3966  4150 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 16:45:13.519  1752  4145 I SystemUpdateService: file has been verified
,09-07 16:45:13.539  1752  4145 I SystemUpdateService: OTA package size = 12249756
,09-07 16:45:13.545  1752  4145 I SystemUpdateService: showing system update notification
,09-07 16:45:13.556   372   869 E Netd    : netlink response contains error (No such file or directory)
,09-07 16:45:13.558  1752  1752 D SystemUpdateService: onDestroy
,09-07 16:45:16.512  1904  2020 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-07 16:45:16.513  1904  2020 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 16:45:16.562  1566  1566 I ConfigService: onCreate
,09-07 16:45:18.322   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e45452d:true
09-07 16:45:18.322  3995  3995 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 16:45:18.328  3995  3995 I bt_bluedroid: init
,09-07 16:45:18.328  3995  4153 I BluetoothAdapterState: Entering OffState
,09-07 16:45:18.334  3995  4154 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 16:45:18.334  3995  4154 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 16:45:18.334  3995  4154 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 16:45:18.335  3995  4154 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 16:45:18.336  3995  3995 I bt_bluedroid: get_profile_interface socket
,09-07 16:45:18.339  3995  3995 I bt_bluedroid: get_profile_interface sdp
,09-07 16:45:18.343  3995  4157 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:45:18.345  3995  4006 I bt_bluedroid: config_hci_snoop_log
09-07 16:45:18.347  3995  4157 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:45:18.348   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 16:45:18.360  3995  4153 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 16:45:18.361  3995  4153 D BluetoothAdapterProperties: Setting state to 14
09-07 16:45:18.361  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14,
,09-07 16:45:18.365  3995  4153 D BluetoothBondStateMachine: make
,09-07 16:45:18.373  3995  4158 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 16:45:18.378  3995  4153 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:18.379  3995  3995 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 16:45:18.383  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:18.384  3995  3995 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 16:45:18.385  3995  3995 D BtGatt.GattService: Received start request. Starting profile...
,09-07 16:45:18.385  3995  3995 D BtGatt.GattService: start()
,09-07 16:45:18.386  3995  3995 I bt_bluedroid: get_profile_interface gatt
09-07 16:45:18.387  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:18.387  3995  3995 D BtGatt.AdvertiseManager: advertise manager created
,09-07 16:45:18.401  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:18.402  3995  3995 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:18.402  3995  3995 V BluetoothAdapterState: isBleTurningOn()=true
09-07 16:45:18.402  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:18.403  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 16:45:18.404  3995  4153 I bt_bluedroid: enable
09-07 16:45:18.404  3995  4154 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 16:45:18.405  3995  4154 I bt_hci  : start_up
,09-07 16:45:18.427  3995  4154 I bt_vendor: alloc value 0xb39e9189
,09-07 16:45:18.427  3995  4154 I bt_vendor: init
09-07 16:45:18.428  3995  4154 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-07 16:45:18.428  3995  4154 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 16:45:18.535  3995  4154 D bt_hci  : start_up starting async portion
,09-07 16:45:18.536  3995  4161 I bt_hci  : event_finish_startup
,09-07 16:45:18.536  3995  4161 I bt_hci_h4: hal_open
,09-07 16:45:18.536  3995  4161 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 16:45:18.546  3995  4161 I bt_userial_vendor: device fd = 51 open
,09-07 16:45:18.578  3995  4161 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 16:45:18.609  3995  4161 D bt_hwcfg: Chipset BCM4354A2
,09-07 16:45:18.610  3995  4161 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 16:45:18.610  3995  4161 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 16:45:18.964   871  1310 D ConnectivityService: handlePromptUnvalidated 101
,09-07 16:45:19.270  3995  4161 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 16:45:19.272  3995  4161 D bt_hwcfg: Settlement delay -- 100 ms
09-07 16:45:19.272  3995  4161 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 16:45:19.389  3995  4161 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 16:45:19.391  3995  4161 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 16:45:19.419  3995  4161 I bt_hwcfg: vendor lib fwcfg completed
,09-07 16:45:19.420  3995  4161 I bt_vendor: firmware callback
09-07 16:45:19.420  3995  4161 I bt_hci  : firmware_config_callback
,09-07 16:45:19.433  3995  4163 I bt_btu  : btu_task pending for preload complete event
,09-07 16:45:19.433  3995  4163 I bt_btu_task: Bluetooth chip preload is complete
,09-07 16:45:19.433  3995  4163 I bt_btu  : btu_task received preload complete event
,09-07 16:45:19.444  3995  4163 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 16:45:19.445  3995  4163 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 16:45:19.445  3995  4163 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 16:45:19.446  3995  4163 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 16:45:19.447  3995  4163 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-07 16:45:19.447  3995  4163 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 16:45:19.447  3995  4163 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 16:45:19.448  3995  4163 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 16:45:19.448  3995  4163 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 16:45:19.448  3995  4163 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 16:45:19.448  3995  4163 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 16:45:19.449  3995  4163 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 16:45:19.449  3995  4163 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 16:45:19.450  3995  4163 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 16:45:19.450  3995  4163 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 16:45:19.582  3995  4163 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,09-07 16:45:19.583  3995  4163 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,09-07 16:45:19.595  3995  4157 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-07 16:45:19.598  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 16:45:19.599  3995  4157 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:45:19.604  3995  4157 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:45:19.607  3995  4157 D BluetoothAdapterProperties: Scan Mode:20
,09-07 16:45:19.613  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:19.610  3995  4157 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 16:45:19.614  3995  4157 D bt_hci  : do_postload posting postload work item
,09-07 16:45:19.614  3995  4161 I bt_hci  : event_postload
,09-07 16:45:19.614  3995  4161 I bt_vendor: sco_config_cb
,09-07 16:45:19.615  3995  4161 I bt_hci  : sco_config_callback postload finished.
09-07 16:45:19.617  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:19.618  3995  4157 D bt_bte_conf: Device ID record 1 : primary
09-07 16:45:19.618  3995  4157 D bt_bte_conf:   vendorId            = 000f
09-07 16:45:19.618  3995  4157 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 16:45:19.618  3995  4157 D bt_bte_conf:   product             = 1200
09-07 16:45:19.619  3995  4157 D bt_bte_conf:   version             = 1436
09-07 16:45:19.619  3995  4157 D bt_bte_conf:   clientExecutableURL = 
09-07 16:45:19.619  3995  4157 D bt_bte_conf:   serviceDescription  = 
09-07 16:45:19.619  3995  4157 D bt_bte_conf:   documentationURL    = 
,09-07 16:45:19.619  3995  4157 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 16:45:19.619  3995  4154 D bt_stack_manager: event_start_up_stack finished
09-07 16:45:19.619  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:19.620  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 16:45:19.620  3995  4161 I bt_vendor: low_power_mode_cb
,09-07 16:45:19.621  3995  4153 D BluetoothAdapterProperties: Setting state to 15
09-07 16:45:19.621  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 16:45:19.622  3995  4153 I BluetoothAdapterState: Entering BleOnState
09-07 16:45:19.625  3995  4153 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 16:45:19.625  3995  4153 D BluetoothAdapterProperties: Setting state to 11
09-07 16:45:19.626  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 16:45:19.631  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:19.632  3995  3995 D HeadsetService: Received start request. Starting profile...
,09-07 16:45:19.635  3995  3995 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
,09-07 16:45:19.635  3995  3995 D HeadsetStateMachine: make
,09-07 16:45:19.638  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:19.640  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:19.643  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:19.649  3995  4153 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:19.650  3995  3995 D HeadsetStateMachine: max_hf_connections = 1
,09-07 16:45:19.650  3995  3995 I bt_bluedroid: get_profile_interface handsfree
,09-07 16:45:19.651  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 16:45:19.651  3995  4157 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 16:45:19.655  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:19.656  3995  3995 D A2dpService: Received start request. Starting profile...
,09-07 16:45:19.656  3995  3995 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 16:45:19.657  3995  3995 I bt_bluedroid: get_profile_interface avrcp
,09-07 16:45:19.663  3995  3995 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 16:45:19.663  3995  3995 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 16:45:19.663  3995  3995 D A2dpStateMachine: make
09-07 16:45:19.665  3995  3995 I bt_bluedroid: get_profile_interface a2dp
,09-07 16:45:19.665  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 16:45:19.667  3995  4172 D A2dpStateMachine: Enter Disconnected: -2
,09-07 16:45:19.668  3995  3995 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 16:45:19.669  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:19.670  3995  3995 D HidService: Received start request. Starting profile...
09-07 16:45:19.670  3916  3916 D BluetoothInputDevice: Proxy object connected
09-07 16:45:19.671  3995  3995 I bt_bluedroid: get_profile_interface hidhost
09-07 16:45:19.671  3995  4157 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
,09-07 16:45:19.671  3995  3995 D HidService: setHidService(): set to: null
09-07 16:45:19.671  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 16:45:19.672  3916  3916 D HidProfile: Bluetooth service connected
09-07 16:45:19.673  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:45:19.673  3995  3995 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 16:45:19.674  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
09-07 16:45:19.675  3995  3995 D HealthService: Received start request. Starting profile...
,09-07 16:45:19.676  3995  3995 I bt_bluedroid: get_profile_interface health
,09-07 16:45:19.677  3995  3995 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 16:45:19.678  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:19.679  3995  3995 D PanService: Received start request. Starting profile...
,09-07 16:45:19.679  3916  3916 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 16:45:19.679  3995  3995 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 16:45:19.679  3995  3995 I bt_bluedroid: get_profile_interface pan
,09-07 16:45:19.680  3995  4157 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 16:45:19.681  3916  3916 D PanProfile: Bluetooth service connected
,09-07 16:45:19.684  3995  3995 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:19.685  3916  3916 D BluetoothMap: Proxy object connected
09-07 16:45:19.685  3995  3995 D BluetoothMapService: Received start request. Starting profile...
,09-07 16:45:19.685  3995  3995 D BluetoothMapService: start()
09-07 16:45:19.686  3916  3916 D MapProfile: Bluetooth service connected
09-07 16:45:19.686  3916  3916 D BluetoothMap: getConnectedDevices()
09-07 16:45:19.687  3916  3916 D BluetoothMap: Bluetooth is Not enabled
,09-07 16:45:19.688  3995  3995 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-07 16:45:19.689  3995  3995 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 16:45:19.689  3995  3995 D BluetoothMapAppObserver: createReceiver()
,09-07 16:45:19.691  3995  3995 D BluetoothMapAppObserver: initObservers()
,09-07 16:45:19.691  3995  3995 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 16:45:19.702  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:19.702  3995  3995 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:19.702  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:19.702  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:19.704  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isTurningOn()=true
,09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:19.705  3995  4170 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:19.705  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:19.706  3995  3995 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:19.706  3995  3995 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:19.706  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:19.706  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:45:19.706  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isTurningOn()=true
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isTurningOn()=true
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:19.707  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:19.708  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2,
09-07 16:45:19.708  3995  4153 D BluetoothAdapterProperties: ScanMode =  20
09-07 16:45:19.708  3995  4153 D BluetoothAdapterProperties: State =  11
,09-07 16:45:19.710  3995  4153 D BluetoothAdapterProperties: Setting state to 12
09-07 16:45:19.710  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 16:45:19.711   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:45:19.711  3995  4153 I BluetoothAdapterState: Entering OnState
,09-07 16:45:19.714  3995  4157 D BluetoothAdapterProperties: Scan Mode:21
09-07 16:45:19.715  3995  4157 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 16:45:19.715   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:19.716  1364  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:19.717   871   871 D BluetoothA2dp: Proxy object connected
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:19.719  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:19.720  3916  3928 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:45:19.721  3995  3995 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 16:45:19.721  1364  2081 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:45:19.721  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:19.723  3916  3929 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 16:45:19.723  3995  3995 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 16:45:19.725  3995  3995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:45:19.725  1976  2111 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:19.726  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:19.726  1364  1378 D BluetoothMap: onBluetoothStateChange: up=true
09-07 16:45:19.728   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:19.728  1364  1364 D BluetoothMap: Proxy object connected
,09-07 16:45:19.728  1364  1364 D MapProfile: Bluetooth service connected
,09-07 16:45:19.728  1364  1364 D BluetoothMap: getConnectedDevices()
09-07 16:45:19.728  1364  2081 D BluetoothPan: onBluetoothStateChange on: true
,09-07 16:45:19.728  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:19.730  3995  3995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:45:19.730  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 16:45:19.730  1364  1364 D PanProfile: Bluetooth service connected
09-07 16:45:19.731  3916  3928 D BluetoothMap: onBluetoothStateChange: up=true,
09-07 16:45:19.731  1364  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:45:19.731  3995  3995 D ObexServerSockets: Succeed to create listening sockets ,
09-07 16:45:19.732  3995  3995 D ObexServerSockets0: startAccept()
09-07 16:45:19.732  3995  3995 D ObexServerSockets0: prepareForNewConnect()
,09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:19.733  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:19.733  1364  1364 D BluetoothInputDevice: Proxy object connected
09-07 16:45:19.733  1364  1364 D HidProfile: Bluetooth service connected
09-07 16:45:19.733  1364  2081 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 16:45:19.735  3995  3995 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 16:45:19.735  3995  3995 D BluetoothSdpJni: SDP Create record success - handle: 0,
09-07 16:45:19.735  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:19.736  3916  3929 D BluetoothPan: onBluetoothStateChange on: true
09-07 16:45:19.736  1364  1364 D BluetoothA2dp: Proxy object connected
,09-07 16:45:19.736   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:45:19.736  3995  4180 D ObexServerSockets0: Accepting socket connection...
09-07 16:45:19.737  3995  4179 D ObexServerSockets0: Accepting socket connection...
,09-07 16:45:19.738   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 16:45:19.738  3995  3995 D BluetoothMapService: onReceive
,09-07 16:45:19.738  3995  3995 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 16:45:19.739  3995  3995 D BluetoothMapService: STATE_ON
09-07 16:45:19.739  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 16:45:19.740  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:19.741  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:19.742  3916  3916 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-07 16:45:19.746  3916  3916 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 16:45:19.751  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:45:19.757  3916  3916 D BluetoothA2dp: Proxy object connected
09-07 16:45:19.760  3995  3995 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 16:45:19.760  3995  3995 D ObexServerSockets0: prepareForNewConnect(),
09-07 16:45:19.761  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:45:19.768  3916  3916 D DockEventReceiver: finishStartingService: stopping service,
,09-07 16:45:19.772  1364  1364 D BluetoothPbap: Proxy object connected
,09-07 16:45:19.772  1364  1364 D PbapServerProfile: Bluetooth service connected
09-07 16:45:19.772  3916  3916 D BluetoothPbap: Proxy object connected
09-07 16:45:19.772  3916  3916 D PbapServerProfile: Bluetooth service connected
,09-07 16:45:19.780  3995  4184 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:45:19.791  3995  4189 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:45:19.792  3995  4189 I BtOppRfcommListener: Accept thread started.
,09-07 16:45:19.817  1976  1990 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.818  1364  1377 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.818  1364  1364 D HeadsetProfile: Bluetooth service connected
09-07 16:45:19.818   871   871 D BluetoothHeadset: Proxy object connected
09-07 16:45:19.818   871   871 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.818   871   871 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.825  1976  1989 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.828   871   888 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.836   871   888 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.848  3916  3928 D BluetoothHeadset: Proxy object connected
,09-07 16:45:19.849  3916  3916 D HeadsetProfile: Bluetooth service connected
,09-07 16:45:21.641  1566  1566 I ConfigService: onDestroy
,09-07 16:45:23.284  3995  4153 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 16:45:23.284  3995  4153 D BluetoothAdapterProperties: Setting state to 13
,09-07 16:45:23.284  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 16:45:23.286  3995  4153 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 16:45:23.289  3995  4153 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:23.298  3995  3995 D BluetoothMapService: onReceive
,09-07 16:45:23.298  3995  3995 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 16:45:23.299  3995  3995 D BluetoothMapService: STATE_TURNING_OFF
09-07 16:45:23.299  3995  3995 D BluetoothMapService: MAP Service closeService in
09-07 16:45:23.300  3995  3995 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 16:45:23.301  3995  3995 D ObexServerSockets0: shutdown(block = true)
09-07 16:45:23.303  3995  4179 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-07 16:45:23.304  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:23.305  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:23.305  3995  3995 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 16:45:23.306  3995  4180 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-07 16:45:23.307  3995  4165 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 16:45:23.307  3995  3995 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 16:45:23.308  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 16:45:23.308  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:23.308  3995  3995 I BtOppRfcommListener: stopping Accept Thread
09-07 16:45:23.309  3995  4157 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:45:23.309  3995  4189 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 16:45:23.310  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 16:45:23.315  3995  4189 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 16:45:23.316  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:23.316  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:23.317  3995  3995 D HeadsetService: Received stop request...Stopping profile...
,09-07 16:45:23.318  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:23.318  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:23.320  1976  2111 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:23.320  1364  1378 D BluetoothHeadset: Proxy object disconnected
,09-07 16:45:23.320  3995  3995 D A2dpService: Received stop request...Stopping profile...
,09-07 16:45:23.321   871   871 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:23.321  3995  4172 D A2dpStateMachine: Exit Disconnected: -1
,09-07 16:45:23.321  3916  3929 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:23.321   871   871 D BluetoothHeadset: Proxy object disconnected
09-07 16:45:23.321  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:23.321   871   871 D BluetoothHeadset: Proxy object disconnected
,09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:23.321  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:23.322  3855  3855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 16:45:23.322  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:23.323   871   871 D BluetoothA2dp: Proxy object disconnected
09-07 16:45:23.323  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 16:45:23.324  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:23.324  3995  3995 D HidService: Received stop request...Stopping profile...
,09-07 16:45:23.324  3995  3995 D HidService: Stopping Bluetooth HidService
09-07 16:45:23.325  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:23.327  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:23.328  3916  3916 D HeadsetProfile: Bluetooth service disconnected
,09-07 16:45:23.328  3916  3916 D BluetoothA2dp: Proxy object disconnected
09-07 16:45:23.329  3995  3995 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:23.329  3995  3995 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:23.329  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:23.329  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:45:23.330  3995  3995 D HealthService: Received stop request...Stopping profile...
09-07 16:45:23.332  3916  3916 D DockEventReceiver: finishStartingService: stopping service
09-07 16:45:23.332  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-07 16:45:23.332  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-07 16:45:23.333  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-07 16:45:23.333  1364  1364 D HidProfile: Bluetooth service disconnected
09-07 16:45:23.333  3995  3995 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 16:45:23.333  3916  3916 D BluetoothInputDevice: Proxy object disconnected
09-07 16:45:23.333  3916  3916 D HidProfile: Bluetooth service disconnected
09-07 16:45:23.333  3995  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:23.333  3995  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 16:45:23.333  3995  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:23.334  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 16:45:23.334  3995  4157 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 16:45:23.334  3995  3995 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 16:45:23.335  3995  3995 D PanService: Received stop request...Stopping profile...
,09-07 16:45:23.337  3916  3916 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 16:45:23.337  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 16:45:23.337  3916  3916 D PanProfile: Bluetooth service disconnected
09-07 16:45:23.337  1364  1364 D PanProfile: Bluetooth service disconnected
09-07 16:45:23.338  3995  3995 D BluetoothMapService: Received stop request...Stopping profile...
09-07 16:45:23.338  3995  3995 D BluetoothMapService: stop()
09-07 16:45:23.339  3995  3995 D BluetoothMapAppObserver: deinitObservers()
09-07 16:45:23.339  3995  3995 D BluetoothMapAppObserver: removeReceiver()
09-07 16:45:23.340  3916  3916 D BluetoothMap: Proxy object disconnected
09-07 16:45:23.340  3916  3916 D MapProfile: Bluetooth service disconnected
09-07 16:45:23.340  1364  1364 D BluetoothMap: Proxy object disconnected
09-07 16:45:23.340  1364  1364 D MapProfile: Bluetooth service disconnected
09-07 16:45:23.341  3995  3995 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:23.341  3995  3995 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:23.341  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:23.341  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:23.342  3995  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:23.342  3995  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:23.343  3995  4163 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 16:45:23.343  3995  4163 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
09-07 16:45:23.343  3995  4163 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 16:45:23.343  3995  4163 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 16:45:23.343  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-07 16:45:23.343  3995  3995 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:23.343  3995  3995 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:23.343  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:23.343  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false,
09-07 16:45:23.347  3995  3995 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 16:45:23.348  3995  4157 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 16:45:23.348  3995  3995 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-07 16:45:23.351  3995  3995 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:23.351  3995  3995 V BluetoothAdapterState: isTurningOn()=false
,09-07 16:45:23.351  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:23.351  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:45:23.352  3995  3995 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 16:45:23.352  3995  4157 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 16:45:23.352  3995  3995 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-07 16:45:23.352  3995  3995 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:23.352  3995  3995 V BluetoothAdapterState: isTurningOn()=false
,09-07 16:45:23.352  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:23.352  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 16:45:23.353  3995  3995 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 16:45:23.353  3995  3995 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 16:45:23.354  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 16:45:23.354  3995  3995 D BluetoothMapService: MAP Service closeService in
,09-07 16:45:23.354  3995  3995 V BluetoothAdapterState: isTurningOff()=true
09-07 16:45:23.354  3995  3995 V BluetoothAdapterState: isTurningOn()=false
,09-07 16:45:23.354  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:23.354  3995  3995 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:23.355  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-07 16:45:23.355  3995  4153 D BluetoothAdapterProperties: Setting state to 15
09-07 16:45:23.355  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 16:45:23.355  3995  3995 D BluetoothMapService: cleanup()
,09-07 16:45:23.355  3995  3995 D BluetoothMapService: MAP Service closeService in
09-07 16:45:23.355  3995  4153 I BluetoothAdapterState: Entering BleOnState
09-07 16:45:23.355   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 16:45:23.355   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:23.356  1364  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:23.356  3916  3928 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 16:45:23.357  1364  2081 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 16:45:23.359  3916  3929 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 16:45:23.360  1976  1990 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:23.361  3916  3928 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 16:45:23.362  1364  1377 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 16:45:23.362   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:23.364  1364  1378 D BluetoothPan: onBluetoothStateChange on: false
09-07 16:45:23.364  3916  3929 D BluetoothMap: onBluetoothStateChange: up=false,
09-07 16:45:23.365  1364  2081 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 16:45:23.365  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 16:45:23.366  3916  3928 D BluetoothPan: onBluetoothStateChange on: false
,09-07 16:45:23.367  3916  4193 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 16:45:23.367   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 16:45:23.368  3995  4153 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-07 16:45:23.368  3995  4153 D BluetoothAdapterProperties: Setting state to 16
09-07 16:45:23.368  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-07 16:45:23.368  3995  4153 D BluetoothAdapterProperties: onBleDisable
09-07 16:45:23.368  3995  4153 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:23.369  3995  4154 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-07 16:45:23.371  3995  4157 D BluetoothAdapterProperties: Scan Mode:20
09-07 16:45:23.371  3995  4163 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 16:45:23.371  3995  4163 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 16:45:23.372  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:23.373  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:23.375  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:23.376  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:45:23.376  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:23.377  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:23.380  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:23.380  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 16:45:23.382  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:45:23.573  3995  4157 I bt_hci  : shut_down
,09-07 16:45:23.574  3995  4161 D bt_hwcfg: hw_epilog_process
,09-07 16:45:23.586  3995  4161 I bt_vendor: low_power_mode_cb
,09-07 16:45:23.613  3995  4161 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 16:45:23.613  3995  4161 I bt_vendor: epilog_cb
,09-07 16:45:23.614  3995  4161 I bt_hci  : epilog_finished_callback
,09-07 16:45:23.621  3995  4157 I bt_hci_h4: hal_close
,09-07 16:45:23.622  3995  4157 I bt_userial_vendor: device fd = 51 close
,09-07 16:45:23.742  3995  4154 D bt_stack_manager: event_shut_down_stack finished.
,09-07 16:45:23.743  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 16:45:23.749  3995  4153 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 16:45:23.749  3995  3995 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 16:45:23.751  3995  3995 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 16:45:23.751  3995  3995 D BtGatt.GattService: stop()
,09-07 16:45:23.751  3995  3995 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 16:45:23.756  3995  3995 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:23.757  3995  3995 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:23.757  3995  3995 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:23.757  3995  3995 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 16:45:23.758  3995  4153 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 16:45:23.759  3995  4153 D BluetoothAdapterProperties: Setting state to 10
,09-07 16:45:23.759  3995  4153 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 16:45:23.761  3995  4153 I BluetoothAdapterState: Entering OffState
09-07 16:45:23.762   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 16:45:23.791  3995  3995 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 16:45:23.791  3995  3995 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-07 16:45:23.792  3995  4154 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 16:45:23.801  3995  4154 D bt_stack_manager: event_clean_up_stack finished.
,09-07 16:45:23.801  3995  3995 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 16:45:23.808  3995  3995 I art     : System.exit called, status: 0
,09-07 16:45:23.808  3995  3995 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 16:45:23.858   871  1998 I ActivityManager: Process com.android.bluetooth (pid 3995) has died
,09-07 16:45:28.281  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:45:28.281  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:45:28.286  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:45:28.286  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@224921a removed from the list
09-07 16:45:28.286  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:45:28.287  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:45:28.287  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:45:28.290  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:45:28.290  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d33a728 added. We now have 4 listener(s)
09-07 16:45:28.291  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:45:28.292  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:45:28.293  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d33a728 removed from the list
09-07 16:45:28.293  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:45:28.294  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:45:28.294  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:45:28.296  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 16:45:28.297  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdc8c41 added. We now have 4 listener(s)
,09-07 16:45:28.297  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:45:33.310  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:33.358   871   888 I ActivityManager: Start proc 4200:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 16:45:33.491  4200  4200 D AdapterServiceConfig: Adding HeadsetService
,09-07 16:45:33.491  4200  4200 D AdapterServiceConfig: Adding A2dpService
,09-07 16:45:33.491  4200  4200 D AdapterServiceConfig: Adding HidService
,09-07 16:45:33.492  4200  4200 D AdapterServiceConfig: Adding HealthService
09-07 16:45:33.492  4200  4200 D AdapterServiceConfig: Adding PanService
09-07 16:45:33.492  4200  4200 D AdapterServiceConfig: Adding GattService
09-07 16:45:33.492  4200  4200 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 16:45:33.507   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4c1996:true
09-07 16:45:33.507  4200  4200 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 16:45:33.512  4200  4200 I bt_bluedroid: init
,09-07 16:45:33.513  4200  4212 I BluetoothAdapterState: Entering OffState
,09-07 16:45:33.519  4200  4213 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 16:45:33.519  4200  4213 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 16:45:33.520  4200  4213 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 16:45:33.520  4200  4213 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 16:45:33.522  4200  4200 I bt_bluedroid: get_profile_interface socket
,09-07 16:45:33.525  4200  4200 I bt_bluedroid: get_profile_interface sdp
09-07 16:45:33.526  4200  4216 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:45:33.529  4200  4211 I bt_bluedroid: config_hci_snoop_log
,09-07 16:45:33.529  4200  4216 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:45:33.532   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 16:45:33.543  4200  4212 D BluetoothAdapterState: Current state: OFF, message: 0
09-07 16:45:33.544  4200  4212 D BluetoothAdapterProperties: Setting state to 14
,09-07 16:45:33.544  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 16:45:33.549  4200  4212 D BluetoothBondStateMachine: make
,09-07 16:45:33.554  4200  4217 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 16:45:33.563  4200  4212 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:33.564  4200  4200 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 16:45:33.569  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:33.571  4200  4200 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 16:45:33.572  4200  4200 D BtGatt.GattService: Received start request. Starting profile...
,09-07 16:45:33.573  4200  4200 D BtGatt.GattService: start()
,09-07 16:45:33.573  4200  4200 I bt_bluedroid: get_profile_interface gatt
,09-07 16:45:33.575  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:33.576  4200  4200 D BtGatt.AdvertiseManager: advertise manager created
,09-07 16:45:33.587  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:33.588  4200  4200 V BluetoothAdapterState: isTurningOn()=false
09-07 16:45:33.588  4200  4200 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 16:45:33.588  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:33.589  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 16:45:33.590  4200  4212 I bt_bluedroid: enable
,09-07 16:45:33.590  4200  4213 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 16:45:33.591  4200  4213 I bt_hci  : start_up
,09-07 16:45:33.611  4200  4213 I bt_vendor: alloc value 0xb3a48189
09-07 16:45:33.611  4200  4213 I bt_vendor: init
,09-07 16:45:33.611  4200  4213 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 16:45:33.612  4200  4213 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 16:45:33.719  4200  4213 D bt_hci  : start_up starting async portion
,09-07 16:45:33.720  4200  4220 I bt_hci  : event_finish_startup
,09-07 16:45:33.720  4200  4220 I bt_hci_h4: hal_open
09-07 16:45:33.720  4200  4220 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 16:45:33.731  4200  4220 I bt_userial_vendor: device fd = 51 open
,09-07 16:45:33.762  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,09-07 16:45:33.794  4200  4220 D bt_hwcfg: Chipset BCM4354A2
,09-07 16:45:33.794  4200  4220 D bt_hwcfg: Target name = [BCM4354A2]
09-07 16:45:33.795  4200  4220 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 16:45:34.629  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 16:45:34.631  4200  4220 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 16:45:34.632  4200  4220 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 16:45:34.750  4200  4220 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-07 16:45:34.751  4200  4220 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 16:45:34.778  4200  4220 I bt_hwcfg: vendor lib fwcfg completed
,09-07 16:45:34.778  4200  4220 I bt_vendor: firmware callback
09-07 16:45:34.779  4200  4220 I bt_hci  : firmware_config_callback
,09-07 16:45:34.792  4200  4222 I bt_btu  : btu_task pending for preload complete event
,09-07 16:45:34.792  4200  4222 I bt_btu_task: Bluetooth chip preload is complete
,09-07 16:45:34.793  4200  4222 I bt_btu  : btu_task received preload complete event
,09-07 16:45:34.804  4200  4222 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 16:45:34.804  4200  4222 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 16:45:34.804  4200  4222 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 16:45:34.805  4200  4222 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 16:45:34.805  4200  4222 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 16:45:34.805  4200  4222 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 16:45:34.805  4200  4222 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 16:45:34.806  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 16:45:34.806  4200  4222 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 16:45:34.806  4200  4222 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 16:45:34.807  4200  4222 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 16:45:34.807  4200  4222 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 16:45:34.807  4200  4222 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 16:45:34.808  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 16:45:34.808  4200  4222 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 16:45:34.956  4200  4222 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c5d9d
,09-07 16:45:34.956  4200  4222 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c5d9d 
,09-07 16:45:34.969  4200  4216 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 16:45:34.971  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 16:45:34.972  4200  4216 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 16:45:34.976  4200  4216 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 16:45:34.981  4200  4216 D BluetoothAdapterProperties: Scan Mode:20
,09-07 16:45:34.981  4200  4216 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 16:45:34.982  4200  4216 D bt_hci  : do_postload posting postload work item
09-07 16:45:34.982  4200  4220 I bt_hci  : event_postload
,09-07 16:45:34.982  4200  4220 I bt_vendor: sco_config_cb
09-07 16:45:34.982  4200  4220 I bt_hci  : sco_config_callback postload finished.
,09-07 16:45:34.986  4200  4216 D bt_bte_conf: Device ID record 1 : primary
09-07 16:45:34.986  4200  4216 D bt_bte_conf:   vendorId            = 000f
09-07 16:45:34.986  4200  4216 D bt_bte_conf:   vendorIdSource      = 0001
09-07 16:45:34.987  4200  4216 D bt_bte_conf:   product             = 1200
09-07 16:45:34.987  4200  4216 D bt_bte_conf:   version             = 1436
09-07 16:45:34.987  4200  4216 D bt_bte_conf:   clientExecutableURL = 
09-07 16:45:34.987  4200  4216 D bt_bte_conf:   serviceDescription  = 
09-07 16:45:34.987  4200  4216 D bt_bte_conf:   documentationURL    = 
09-07 16:45:34.988  4200  4220 I bt_vendor: low_power_mode_cb
09-07 16:45:34.988  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:34.991  4200  4216 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 16:45:34.992  4200  4213 D bt_stack_manager: event_start_up_stack finished
09-07 16:45:34.994  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:45:34.994  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 16:45:34.995  4200  4212 D BluetoothAdapterProperties: Setting state to 15
09-07 16:45:34.996  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-07 16:45:34.998  4200  4212 I BluetoothAdapterState: Entering BleOnState
,09-07 16:45:35.003  4200  4212 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 16:45:35.003  4200  4212 D BluetoothAdapterProperties: Setting state to 11
09-07 16:45:35.003  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 16:45:35.008  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:35.009  4200  4200 D HeadsetService: Received start request. Starting profile...
,09-07 16:45:35.012  4200  4200 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 16:45:35.013  4200  4200 D HeadsetStateMachine: make
,09-07 16:45:35.018  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:35.020  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:35.025  4200  4212 I BluetoothAdapterState: Entering PendingCommandState
,09-07 16:45:35.028  4200  4200 D HeadsetStateMachine: max_hf_connections = 1
09-07 16:45:35.028  4200  4200 I bt_bluedroid: get_profile_interface handsfree
09-07 16:45:35.029  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 16:45:35.029  4200  4216 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 16:45:35.033  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:35.034  4200  4200 D A2dpService: Received start request. Starting profile...
09-07 16:45:35.034  4200  4200 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 16:45:35.035  4200  4200 I bt_bluedroid: get_profile_interface avrcp
,09-07 16:45:35.042  4200  4200 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 16:45:35.042  4200  4200 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 16:45:35.042  4200  4200 D A2dpStateMachine: make
,09-07 16:45:35.045  4200  4200 I bt_bluedroid: get_profile_interface a2dp
,09-07 16:45:35.046  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 16:45:35.047  4200  4200 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 16:45:35.047  4200  4232 D A2dpStateMachine: Enter Disconnected: -2
,09-07 16:45:35.048  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
09-07 16:45:35.048  4200  4200 D HidService: Received start request. Starting profile...
09-07 16:45:35.049  4200  4200 I bt_bluedroid: get_profile_interface hidhost
09-07 16:45:35.049  4200  4200 D HidService: setHidService(): set to: null
09-07 16:45:35.049  4200  4200 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 16:45:35.049  4200  4216 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a73e5
09-07 16:45:35.049  4200  4216 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 16:45:35.050  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
09-07 16:45:35.050  4200  4200 D HealthService: Received start request. Starting profile...
,09-07 16:45:35.053  4200  4200 I bt_bluedroid: get_profile_interface health
,09-07 16:45:35.054  4200  4200 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 16:45:35.055  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:45:35.055  4200  4200 D PanService: Received start request. Starting profile...
09-07 16:45:35.055  4200  4200 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 16:45:35.055  4200  4200 I bt_bluedroid: get_profile_interface pan
,09-07 16:45:35.056  4200  4216 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 16:45:35.059  4200  4200 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
09-07 16:45:35.059  4200  4200 D BluetoothMapService: Received start request. Starting profile...
09-07 16:45:35.059  4200  4200 D BluetoothMapService: start()
09-07 16:45:35.061  4200  4200 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-07 16:45:35.062  4200  4200 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 16:45:35.062  4200  4200 D BluetoothMapAppObserver: createReceiver()
09-07 16:45:35.063  4200  4200 D BluetoothMapAppObserver: initObservers()
,09-07 16:45:35.063  4200  4200 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 16:45:35.070  4200  4200 V BluetoothAdapterState: isTurningOff()=false
,09-07 16:45:35.070  4200  4200 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:35.070  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:35.070  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:35.070  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 16:45:35.072  4200  4228 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:35.073  4200  4200 V BluetoothAdapterState: isTurningOn()=true,
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isTurningOff()=false
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isTurningOn()=true
09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 16:45:35.074  4200  4200 V BluetoothAdapterState: isBleTurningOff()=false
09-07 16:45:35.075  4200  4212 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 16:45:35.075  4200  4212 D BluetoothAdapterProperties: ScanMode =  20
09-07 16:45:35.075  4200  4212 D BluetoothAdapterProperties: State =  11
09-07 16:45:35.077  4200  4212 D BluetoothAdapterProperties: Setting state to 12
09-07 16:45:35.077  4200  4212 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
,09-07 16:45:35.077  4200  4212 I BluetoothAdapterState: Entering OnState
09-07 16:45:35.077   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:45:35.081  4200  4216 D BluetoothAdapterProperties: Scan Mode:21
09-07 16:45:35.081  4200  4216 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 16:45:35.081   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:45:35.082  1364  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:45:35.083   871   871 D BluetoothA2dp: Proxy object connected
09-07 16:45:35.084  3916  3928 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:35.085  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:35.086  1364  1378 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:45:35.087  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 16:45:35.088  3916  3929 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 16:45:35.088  4200  4200 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 16:45:35.089  4200  4200 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 16:45:35.090  1976  1989 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:35.090  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 16:45:35.090  3916  3928 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:35.091  1364  2081 D BluetoothMap: onBluetoothStateChange: up=true
09-07 16:45:35.091  3916  3916 D BluetoothInputDevice: Proxy object connected
09-07 16:45:35.091  3916  3916 D HidProfile: Bluetooth service connected
09-07 16:45:35.092  4200  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:45:35.092  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:35.094  4200  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:45:35.095  4200  4200 D ObexServerSockets: Succeed to create listening sockets 
,09-07 16:45:35.095  4200  4200 D ObexServerSockets0: startAccept()
09-07 16:45:35.095  4200  4200 D ObexServerSockets0: prepareForNewConnect()
09-07 16:45:35.097   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 16:45:35.097  1364  1377 D BluetoothPan: onBluetoothStateChange on: true
09-07 16:45:35.098  4200  4200 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 16:45:35.098  4200  4200 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-07 16:45:35.099  4200  4239 D ObexServerSockets0: Accepting socket connection...
09-07 16:45:35.099  4200  4238 D ObexServerSockets0: Accepting socket connection...
09-07 16:45:35.099  1364  1364 D BluetoothMap: Proxy object connected
09-07 16:45:35.099  1364  1364 D MapProfile: Bluetooth service connected
09-07 16:45:35.099  1364  1364 D BluetoothMap: getConnectedDevices()
09-07 16:45:35.101  3916  4193 D BluetoothMap: onBluetoothStateChange: up=true
09-07 16:45:35.101  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 16:45:35.101  1364  1364 D PanProfile: Bluetooth service connected
,09-07 16:45:35.102  1364  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 16:45:35.102  3916  3916 D BluetoothMap: Proxy object connected
09-07 16:45:35.102  3916  3916 D MapProfile: Bluetooth service connected
09-07 16:45:35.102  3916  3916 D BluetoothMap: getConnectedDevices()
,09-07 16:45:35.104  1364  1364 D BluetoothInputDevice: Proxy object connected
09-07 16:45:35.104  1364  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:45:35.104  1364  1364 D HidProfile: Bluetooth service connected
,09-07 16:45:35.105  1364  1364 D BluetoothA2dp: Proxy object connected
,09-07 16:45:35.105  3916  3928 D BluetoothPan: onBluetoothStateChange on: true
,09-07 16:45:35.108  3916  3916 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 16:45:35.108  3916  4193 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 16:45:35.108  3916  3916 D PanProfile: Bluetooth service connected
,09-07 16:45:35.110  3916  3916 D BluetoothA2dp: Proxy object connected
,09-07 16:45:35.110   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 16:45:35.111  4200  4200 D BluetoothMapService: onReceive
,09-07 16:45:35.111   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 16:45:35.111  4200  4200 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 16:45:35.111  4200  4200 D BluetoothMapService: STATE_ON
09-07 16:45:35.113  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:35.114  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:35.118  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 16:45:35.123  3916  3916 D DockEventReceiver: finishStartingService: stopping service
,09-07 16:45:35.124  1566  1566 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 16:45:35.130  3916  3916 D BluetoothPbap: Proxy object connected
09-07 16:45:35.130  3916  3916 D PbapServerProfile: Bluetooth service connected
,09-07 16:45:35.135  1364  1364 D BluetoothPbap: Proxy object connected
09-07 16:45:35.135  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-07 16:45:35.136  4200  4200 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 16:45:35.136  4200  4200 D ObexServerSockets0: prepareForNewConnect()
,09-07 16:45:35.140  4200  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:45:35.153  4200  4247 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 16:45:35.154  4200  4247 I BtOppRfcommListener: Accept thread started.
,09-07 16:45:35.185  1976  2111 D BluetoothHeadset: Proxy object connected
,09-07 16:45:35.186  1364  2081 D BluetoothHeadset: Proxy object connected
09-07 16:45:35.186  1364  1364 D HeadsetProfile: Bluetooth service connected
,09-07 16:45:35.186   871   871 D BluetoothHeadset: Proxy object connected
09-07 16:45:35.187  3916  3929 D BluetoothHeadset: Proxy object connected
,09-07 16:45:35.187   871   871 D BluetoothHeadset: Proxy object connected
,09-07 16:45:35.187   871   871 D BluetoothHeadset: Proxy object connected
09-07 16:45:35.188  3916  3916 D HeadsetProfile: Bluetooth service connected
,09-07 16:45:35.191  1976  1990 D BluetoothHeadset: Proxy object connected
,09-07 16:45:35.191  3916  4193 D BluetoothHeadset: Proxy object connected
09-07 16:45:35.192  3916  3916 D HeadsetProfile: Bluetooth service connected
,09-07 16:45:35.197   871   888 D BluetoothHeadset: Proxy object connected
,09-07 16:45:35.211   871   888 D BluetoothHeadset: Proxy object connected
,09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:38.329  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:38.336  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:38.337  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:45:38.338  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdc8c41 removed from the list
,09-07 16:45:38.338  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:45:38.338  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:45:38.339  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:45:38.341  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:45:38.342  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e9b5e6 added. We now have 4 listener(s)
,09-07 16:45:38.342  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:45:38.346   871   882 D WifiService: setWifiEnabled: false pid=3855, uid=10000
09-07 16:45:38.346   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:45:43.360  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:45:43.361   871   882 D WifiService: setWifiEnabled: true pid=3855, uid=10000
,09-07 16:45:43.362   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 16:45:43.375   871  1308 D WifiConfigStore: Loading config and enabling all networks 
,09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:43.395  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:43.399  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 16:45:43.403  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 16:45:43.405   871  1308 D WifiConfigStore: loaded 0 passpoint configs
,09-07 16:45:43.405  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 16:45:43.406   871  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-07 16:45:43.407   871  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 16:45:43.408   871  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 16:45:43.408   871  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 16:45:43.408   871  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 16:45:43.409   871  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 16:45:43.423   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-07 16:45:43.423   871  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:45:43.424   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:43.476   871  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-07 16:45:43.477   871  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 16:45:43.483   871  1308 E native  : do suspend true
,09-07 16:45:43.491   871  1305 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 16:45:43.509   871  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 16:45:43.527   871  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:45:44.851   871  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 16:45:45.016   871  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.25 rxSuccessRate=16.38 delta 1000 -> 994
,09-07 16:45:45.021   871  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 16:45:45.021   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:45:45.043   871  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 16:45:45.140   871  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 16:45:45.146  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 16:45:45.586  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 16:45:45.631  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 16:45:45.632  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-07 16:45:45.636   871  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 16:45:45.658   871  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 16:45:45.659   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 16:45:45.660   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:45:45.692   871  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 16:45:45.718   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:45.720   871  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 16:45:45.729   871  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 16:45:45.762   871  4258 D DhcpClient: Receive thread started
,09-07 16:45:45.858   871  1308 E native  : do suspend false
,09-07 16:45:45.883   871  1934 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 16:45:45.896   871  4258 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-07 16:45:45.897   871  1934 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-07 16:45:45.902   871  1934 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 16:45:45.914   871  4258 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 16:45:45.916   871  1934 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 16:45:45.922   372   869 D CommandListener: Setting iface cfg
,09-07 16:45:45.933   871  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 16:45:45.934   871  1934 D DhcpClient: Scheduling renewal in 86399s
,09-07 16:45:45.936   871  1308 E native  : do suspend true
,09-07 16:45:45.959   871  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 16:45:45.962   871  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 16:45:45.964   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 16:45:45.966   871  1310 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 16:45:45.973   871  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 16:45:46.029   871  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 16:45:46.029   871  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-07 16:45:46.032   871  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 16:45:46.035   871  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 16:45:46.037   871  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 16:45:46.057   871  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 16:45:46.065   871  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-07 16:45:46.065   871  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-07 16:45:46.065   871  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-07 16:45:46.065   871  1310 D ConnectivityService:    accepting network in place of null
09-07 16:45:46.065   871  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-07 16:45:46.066   871  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 16:45:46.067   871  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 16:45:46.079   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=398344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 16:45:46.103   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:45:46.145   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 16:45:46.154   871  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 16:45:46.154   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:46.164   871   888 D Tethering: MasterInitialState.processMessage what=3
,09-07 16:45:46.175   871  4256 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-07 16:45:46.175   871  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:46.184  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:46.186  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:46.192  3855  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 16:45:46.195  3855  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:46.197  1752  1752 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 16:45:46.203  1752  1752 D SystemUpdateService: onCreate
09-07 16:45:46.209  1752  1752 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-07 16:45:46.229  1752  4267 I SystemUpdateService: active receiver: enabled
,09-07 16:45:46.235  1752  1752 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 16:45:46.236  1752  2433 I iu.UploadsManager: num queued entries: 0
,09-07 16:45:46.244  1752  4267 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 16:45:46.246  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 16:45:46.247  1752  1752 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 16:45:46.249  4009  4009 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 16:45:46.254  1752  4269 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 16:45:46.254  1752  4269 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 16:45:46.256  1752  4269 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:45:46.257   871  4256 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 14:45:46 GMT], X-Android-Received-Millis=[1473259546256], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473259546231]}
,09-07 16:45:46.258   871  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 16:45:46.258   871  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-07 16:45:46.258   871  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 16:45:46.259   871  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 16:45:46.259  4009  4009 D SprintDMHelper: simOperator: 
,09-07 16:45:46.259  4009  4009 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 16:45:46.271  1752  4267 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 16:45:46.271  1752  4267 I SystemUpdateService: now status is 0 (complete)
09-07 16:45:46.271  1752  4267 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 16:45:46.271  1752  4267 I SystemUpdateService: file has been verified
09-07 16:45:46.271  1752  4267 I SystemUpdateService: OTA package size = 12249756
09-07 16:45:46.272  1752  2433 I iu.UploadsManager: num updated entries: 0
,09-07 16:45:46.278  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:45:46.282  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:45:46.273  1752  2433 I iu.SyncManager: NEXT; no task
,09-07 16:45:46.338  1752  4267 I SystemUpdateService: showing system update notification
,09-07 16:45:46.419  3966  4273 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 16:45:46.434  1566  2402 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 16:45:46.434  1566  2402 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 16:45:46.434  1566  2402 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:45:46.434  1566  2402 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:45:46.436  1752  1752 D SystemUpdateService: onDestroy
,09-07 16:45:46.456  1752  4269 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-07 16:45:47.152   871  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:45:48.387  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:45:48.395  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:45:48.396  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:45:48.396  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e9b5e6 removed from the list
,09-07 16:45:48.397  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:45:48.397  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:45:48.398  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:45:48.412  3855  4279 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-07 16:45:48.412  3855  4279 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 16:45:51.420  3855  4280 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-07 16:45:51.422  3855  4280 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-07 16:45:51.422  3855  4279 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-07 16:45:51.422  3855  4279 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 16:45:51.423  3855  4279 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:45:51.424  3855  4280 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:45:51.425  3855  4279 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:45:51.426  3855  4280 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:45:51.429  3855  4279 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 16:45:51.430  3855  4282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 421, name: OutgoingSocketThread/Sender)
,09-07 16:45:51.432  3855  4280 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 16:45:51.432  3855  4283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: IncomingSocketThread/Sender)
,09-07 16:45:51.435  3855  4284 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: OutgoingSocketThread/Receiver)
,09-07 16:45:51.436  3855  4284 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 423, thread name: OutgoingSocketThread/Receiver)
,09-07 16:45:51.436  3855  4284 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 16:45:51.437  3855  4284 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 423, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 16:45:51.437  3855  4285 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: IncomingSocketThread/Receiver)
,09-07 16:45:51.439  3855  4285 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 424, thread name: IncomingSocketThread/Receiver)
,09-07 16:45:51.439  3855  4285 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 16:45:51.439  3855  4285 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 424, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 16:45:54.073   871  1310 D ConnectivityService: handlePromptUnvalidated 102
,09-07 16:45:54.419  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 16:45:54.421  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 16:45:54.430  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@80055b1 Bundle[{}]
,09-07 16:45:54.430  3855  3901 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 16:45:54.430  3855  3901 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 16:45:54.431  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 16:45:54.431  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 16:45:54.432  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-07 16:45:54.433  3855  3901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-07 16:45:54.437  3855  3901 I System.out: Running OutgoingSocketThread,
09-07 16:45:54.440  3855  4286 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 16:45:54.441  3855  4286 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 16:45:57.450  3855  4287 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-07 16:45:57.450  3855  4287 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 16:45:57.451  3855  4287 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:45:57.451  3855  4286 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-07 16:45:57.452  3855  4286 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 16:45:57.454  3855  4286 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 16:45:57.456  3855  4286 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:45:57.456  3855  4287 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 16:45:57.457  3855  4286 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 16:45:57.462  3855  4289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: IncomingSocketThread/Sender)
,09-07 16:45:57.462  3855  4287 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 16:45:57.465  3855  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
,09-07 16:45:57.466  3855  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: OutgoingSocketThread/Sender)
,09-07 16:45:57.467  3855  4292 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Receiver)
,09-07 16:45:57.467  3855  4291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
09-07 16:45:57.467  3855  4291 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 16:45:57.467  3855  4292 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: IncomingSocketThread/Receiver)
09-07 16:45:57.467  3855  4292 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 16:45:57.468  3855  4292 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-07 16:45:57.467  3855  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 16:46:00.452  3855  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,09-07 16:46:00.455  3855  3901 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 16:46:00.456  3855  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 446)
,09-07 16:46:00.461  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 16:46:00.461  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d2b727 added. We now have 3 listener(s)
,09-07 16:46:00.463  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:46:00.463  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:46:00.463  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:46:00.463  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:46:00.463  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b00dd4 added. We now have 4 listener(s)
09-07 16:46:00.464  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:46:00.464  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:46:00.468  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:46:00.479  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:46:00.484  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 16:46:00.484  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:46:00.485  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 16:46:00.485  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:46:00.485  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 16:46:00.485  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:46:00.485  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:00.485  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:46:00.485  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:46:00.485  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d2b727 removed from the list
09-07 16:46:00.485  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:00.485  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b00dd4 removed from the list
,09-07 16:46:00.490  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:46:00.495  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:46:00.495  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:46:00.495  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:46:00.496  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:00.496  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:46:00.498  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:46:00.499  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:46:00.499  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:00.499  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b00dd4 not in the list
09-07 16:46:00.499  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:00.499  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:00.501  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:46:00.502  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:46:00.502  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:46:00.502  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b00dd4 not in the list
09-07 16:46:00.502  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:46:00.503  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:00.503  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:00.503  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d2b727 not in the list
,09-07 16:46:00.505  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:46:00.505  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58b4a72 added. We now have 3 listener(s)
,09-07 16:46:00.511  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 16:46:00.512  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:46:00.512  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:46:00.512  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:46:00.513  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3299ec3 added. We now have 4 listener(s)
09-07 16:46:00.513  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 16:46:00.514  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:46:00.522  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:46:00.535  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:46:00.541  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:46:00.542  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 16:46:00.543  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 16:46:00.543  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 16:46:00.543  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 16:46:00.543  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:46:00.544  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 16:46:00.549  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:46:00.553  3855  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 16:46:00.553  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 16:46:00.555  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 16:46:00.566  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:46:00.568  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:46:00.568  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:46:00.578  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 16:46:00.578  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 16:46:00.578  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 16:46:00.580  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:46:00.588  4200  4210 D BtGatt.GattService: registerClient() - UUID=dda2e619-ed81-402a-9127-5bad97dba192
,09-07 16:46:00.589  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=dda2e619-ed81-402a-9127-5bad97dba192, clientIf=5
09-07 16:46:00.591  3855  3866 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 16:46:00.594  4200  4229 D BtGatt.GattService: start scan with filters
,09-07 16:46:00.605  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 16:46:00.605  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 16:46:00.605  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 16:46:00.606  4200  4219 D BtGatt.ScanManager: handling starting scan
09-07 16:46:00.606  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 16:46:00.611  4200  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a3b35
,09-07 16:46:00.614  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 16:46:00.614  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:46:00.615  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 16:46:00.618  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:46:00.625  3855  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 16:46:00.625  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 16:46:00.626  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 16:46:00.626  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:00.626  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 16:46:00.626  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 16:46:00.626  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:46:00.626  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 16:46:00.626  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 16:46:00.628  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 16:46:00.628  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 16:46:00.629  3855  3901 D BluetoothAdapter: STATE_ON
09-07 16:46:00.629  4200  4216 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-07 16:46:00.629  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:46:00.631  4200  4210 D BtGatt.GattService: stopScan() - queue size =1
,09-07 16:46:00.631  4200  4219 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 16:46:00.633  4200  4229 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 16:46:00.635  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 16:46:00.635  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 16:46:00.636  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 16:46:00.636  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 16:46:00.636  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 16:46:00.639  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:46:00.640  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 16:46:00.640  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:46:00.640  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 16:46:00.641  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:46:00.644  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 16:46:00.645  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 16:46:00.646  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 16:46:00.652  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 16:46:00.652  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:46:00.653  4200  4219 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 16:46:00.654  4200  4219 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 16:46:00.702  4200  4216 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 16:46:00.703  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:46:00.724  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 16:46:00.724  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:46:00.746  4200  4216 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 16:46:00.747  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:46:00.748  4200  4219 D BtGatt.ScanManager: stopping BLe Batch
,09-07 16:46:00.762  4200  4216 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 16:46:00.763  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 16:46:00.763  4200  4219 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 16:46:00.773  4200  4216 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 16:46:00.773  4200  4216 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 16:46:00.807   871   880 I art     : Background partial concurrent mark sweep GC freed 45855(2MB) AllocSpace objects, 8(232KB) LOS objects, 33% free, 29MB/43MB, paused 1.198ms total 137.684ms
,09-07 16:46:01.148  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 16:46:01.149  3855  3855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:46:01.149  3855  3855 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:46:03.645  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:46:03.645  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:46:03.646  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 16:46:03.646  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:46:03.646  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:03.647  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:46:03.647  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:46:03.648  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58b4a72 removed from the list
,09-07 16:46:03.648  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:03.648  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3299ec3 removed from the list
,09-07 16:46:03.649  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 16:46:03.649  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:46:03.651  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 16:46:03.651  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:46:03.655  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:46:03.655  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 16:46:03.655  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:03.656  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3299ec3 not in the list
09-07 16:46:03.656  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:03.656  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:03.659  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:46:03.660  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:46:03.660  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:03.660  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3299ec3 not in the list
09-07 16:46:03.660  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:46:03.661  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:03.661  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:03.661  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58b4a72 not in the list
09-07 16:46:03.664  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:46:03.664  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdf436c added. We now have 3 listener(s)
,09-07 16:46:03.667  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:46:03.667  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 16:46:03.667  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:46:03.668  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:46:03.668  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322cd35 added. We now have 4 listener(s)
09-07 16:46:03.668  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:46:03.669  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:46:03.672  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 16:46:03.679  3855  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 16:46:03.683  3855  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 16:46:03.684  3855  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 16:46:03.684  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 16:46:03.686  3855  3901 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-07 16:46:03.687  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-07 16:46:03.687  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 16:46:03.687  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 16:46:03.687  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 16:46:03.687  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:46:03.688  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:46:03.689  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 16:46:03.689  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 16:46:03.690  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 16:46:03.690  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 16:46:03.690  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 16:46:03.690  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 16:46:03.690  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 16:46:03.690  3855  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 16:46:03.691  3855  3855 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 16:46:03.694  3855  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 16:46:03.697  3855  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 16:46:03.697  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 16:46:03.697  3855  4294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 16:46:03.701  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 16:46:03.701  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 16:46:03.702  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 16:46:03.704  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 16:46:03.704  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:46:03.705  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-07 16:46:03.706  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 16:46:03.706  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 16:46:03.706  3855  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 16:46:03.707  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:46:03.709  4200  4230 D BtGatt.GattService: registerClient() - UUID=f9f793a6-a2d2-4298-846f-f73c7f6c0e5d
09-07 16:46:03.710  4200  4216 D BtGatt.GattService: onClientRegistered() - UUID=f9f793a6-a2d2-4298-846f-f73c7f6c0e5d, clientIf=5
,09-07 16:46:03.710  3855  3950 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 16:46:03.712  4200  4218 D BtGatt.AdvertiseManager: message : 0
,09-07 16:46:03.715  4200  4218 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 16:46:03.727  4200  4216 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 16:46:03.734  4200  4216 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 16:46:03.736  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 16:46:03.736  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 16:46:03.738  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 16:46:03.740  3855  3855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 16:46:03.740  3855  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-07 16:46:03.740  3855  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 16:46:03.740  3855  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 16:46:03.740  3855  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-07 16:46:03.740  3855  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 16:46:03.743  3855  3855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 16:46:03.744  3855  3855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 16:46:03.745  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 16:46:03.745  3855  3901 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 16:46:04.245  3855  3855 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 16:46:06.747  3855  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 16:46:06.748  3855  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 16:46:06.748  3855  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 16:46:06.748  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 16:46:06.749  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 16:46:06.749  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 16:46:06.750  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-07 16:46:06.751  3855  4294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 16:46:06.751  3855  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 16:46:06.751  3855  4294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 16:46:06.751  3855  4294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 16:46:06.752  3855  3855 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 16:46:06.752  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 16:46:06.752  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 16:46:06.753  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 16:46:06.753  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 16:46:06.753  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 16:46:06.756  3855  3901 D BluetoothAdapter: STATE_ON
,09-07 16:46:06.757  3855  3901 D BluetoothLeScanner: could not find callback wrapper
09-07 16:46:06.757  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 16:46:06.757  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 16:46:06.760  4200  4218 D BtGatt.AdvertiseManager: message : 1
,09-07 16:46:06.761  4200  4218 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 16:46:06.767  4200  4216 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 16:46:06.768  4200  4216 D BtGatt.GattService: Client app is not null!
,09-07 16:46:06.769  4200  4230 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 16:46:06.771  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 16:46:06.772  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 16:46:06.772  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 16:46:06.772  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 16:46:06.772  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 16:46:06.775  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 16:46:06.775  3855  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 16:46:06.775  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 16:46:06.776  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 16:46:06.779  3855  3855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 16:46:06.779  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:46:06.779  3855  3855 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 16:46:06.779  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:06.779  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 16:46:06.779  3855  3855 D AndroidRuntime: Shutting down VM
09-07 16:46:06.780  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 16:46:06.780  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdf436c removed from the list
,--------- beginning of crash
09-07 16:46:06.780  3855  3855 E AndroidRuntime: FATAL EXCEPTION: main
09-07 16:46:06.780  3855  3855 E AndroidRuntime: Process: com.test.thalitest, PID: 3855
09-07 16:46:06.780  3855  3855 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 16:46:06.780  3855  3855 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 16:46:06.780  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:06.780  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322cd35 removed from the list
09-07 16:46:06.781  3855  3901 D io.jxcore.node.ConnectivityMonitor: stop
09-07 16:46:06.781  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 16:46:06.782  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:06.782  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:06.784  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 16:46:06.784  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:46:06.784  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 16:46:06.785  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322cd35 not in the list
09-07 16:46:06.785  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:06.785  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:06.789  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 16:46:06.789  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 16:46:06.789  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 16:46:06.789   871  1869 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
09-07 16:46:06.789  3855  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322cd35 not in the list
09-07 16:46:06.790  3855  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 16:46:06.790  3855  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 16:46:06.790  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 16:46:06.791  3855  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdf436c not in the list
,09-07 16:46:06.792  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 16:46:06.792  3855  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c016496 added. We now have 3 listener(s)
09-07 16:46:06.798  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 16:46:06.799  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 16:46:06.799  3855  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 16:46:06.799  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 16:46:06.800  3855  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b41b817 added. We now have 4 listener(s)
,09-07 16:46:06.800  3855  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 16:46:06.801  3855  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 16:46:06.807  3855  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 16:46:06.807   871   884 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{9e720c1 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{498b1cb 3855 com.test.thalitest/10000/u0 remote:d9e249a}: process crashing
,09-07 16:46:06.808   871   884 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{9a9f066 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{498b1cb 3855 com.test.thalitest/10000/u0 remote:d9e249a}: process crashing
09-07 16:46:06.809  3855  3855 I Process : Sending signal. PID: 3855 SIG: 9
,09-07 16:46:06.919   871  2008 I WindowState: WIN DEATH: Window{7fcdc1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 16:46:06.919   871  1943 D GraphicsStats: Buffer count: 2
09-07 16:46:06.920   871  1309 D WifiService: Client connection lost with reason: 4
,09-07 16:46:06.945   871  2006 I ActivityManager: Process com.test.thalitest (pid 3855) has died
,09-07 16:46:07.009   871  1869 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3855 uid 10000
,09-07 16:46:07.012  1904  1904 I Keyboard.Facilitator: onFinishInput()
,09-07 16:46:12.498   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=424763, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:46:15.331  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:46:15.334  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:46:15.348  3803  4298 V GoogleAuthProtoRequest: [313] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:46:15.373  1566  3523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 16:46:15.373  1566  3523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,09-07 16:46:15.373  1566  3523 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:46:15.373  1566  3523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: [313] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: [313] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 16:46:15.392  3803  4298 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 16:47:07.054  1904  2020 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-07 16:47:07.055  1904  2020 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 16:47:07.088  1566  1566 I ConfigService: onCreate
,09-07 16:47:12.163  1566  1566 I ConfigService: onDestroy
,09-07 16:47:23.739  3043  4303 V KeepSync: Connecting to GoogleApiClient
,09-07 16:47:23.740   871  1998 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:47:23.798  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:47:23.801  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:47:23.834  1566  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:47:23.834  1566  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 16:47:23.834  1566  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:47:23.834  1566  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:47:23.857  1752  4304 V BaseAuthAsyncOperation: access token request failed
,09-07 16:47:23.858  3043  4303 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:47:23.925  1566  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-07 16:47:23.925  1566  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-07 16:47:23.925  1566  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:47:23.925  1566  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:47:23.954  3043  4303 E KeepSync: IOException
09-07 16:47:23.954  3043  4303 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:47:23.954  3043  4303 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:47:23.954  3043  4303 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:47:23.954  3043  4303 E KeepSync: 	... 10 more
09-07 16:47:23.955  3043  4303 W KeepSync: Sync result 2
,09-07 16:47:23.968   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 495838, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:47:56.517  3043  4306 V KeepSync: Connecting to GoogleApiClient
09-07 16:47:56.517   871  1376 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:47:56.579  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:47:56.582  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:47:56.631  1566  1578 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:47:56.631  1566  1578 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 16:47:56.631  1566  1578 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:47:56.632  1566  1578 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:47:56.668  1752  4307 V BaseAuthAsyncOperation: access token request failed
,09-07 16:47:56.671  3043  4306 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:47:56.750  1566  2402 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 16:47:56.750  1566  2402 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-07 16:47:56.750  1566  2402 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:47:56.750  1566  2402 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:47:56.775  3043  4306 E KeepSync: IOException
09-07 16:47:56.775  3043  4306 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:47:56.775  3043  4306 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:47:56.775  3043  4306 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:47:56.775  3043  4306 E KeepSync: 	... 10 more
09-07 16:47:56.775  3043  4306 W KeepSync: Sync result 2
,09-07 16:47:56.789   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 528675, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:48:27.242  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:27.245  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:27.302  1566  3523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 16:48:27.302  1566  3523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 16:48:27.302  1566  3523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:48:27.302  1566  3523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:48:27.335  2998  4312 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:48:27.335  2998  4312 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:48:27.335  2998  4312 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	... 12 more
09-07 16:48:27.335  2998  4312 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at fal.a(PG:38)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:48:27.335  2998  4312 E HttpOperation: 	... 14 more
,09-07 16:48:27.431  1566  2040 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:48:27.431  1566  2040 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:48:27.431  1566  2040 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:48:27.431  1566  2040 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:48:27.472  2998  4312 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:48:27.472  2998  4312 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at hec.a(PG:42)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at hee.a(PG:102)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at czr.a(PG:65)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at kka.a(PG:108)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:48:27.472  2998  4312 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	... 15 more
09-07 16:48:27.472  2998  4312 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at fal.a(PG:38)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:48:27.472  2998  4312 E HttpOperation: 	... 17 more
,09-07 16:48:27.472  2998  4312 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:48:27.472  2998  4312 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	... 15 more
09-07 16:48:27.472  2998  4312 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:48:27.472  2998  4312 E ExperimentLoader: 	... 17 more
,09-07 16:48:27.678   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 533118, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:48:57.781  3722  4315 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:48:57.825  3722  4316 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:48:57.851  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:57.853  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:57.882  1566  2402 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 16:48:57.882  1566  2402 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 16:48:57.882  1566  2402 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:48:57.882  1566  2402 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:48:57.917  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:57.919  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:57.952  1566  3523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 16:48:57.953  1566  3523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 16:48:57.953  1566  3523 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:48:57.953  1566  3523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:48:57.973  3722  4316 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 16:48:57.974  3722  4315 E BooksSync: Soft error
09-07 16:48:57.974  3722  4315 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:48:57.974  3722  4315 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:48:57.975  3722  4315 E BooksSync: Sync error
09-07 16:48:57.975  3722  4315 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:48:57.975  3722  4315 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:48:57.975  3722  4315 I BooksSync: Finished books sync
,09-07 16:48:57.991   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 584079, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:48:58.144   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:48:58.194  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:58.198  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:48:58.228  1566  1578 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:48:58.229  1566  1578 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:48:58.229  1566  1578 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:48:58.229  1566  1578 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:48:58.262  2998  4318 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 16:48:58.262  2998  4318 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at blb.a(PG:3937)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at czp.a(PG:18188)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:48:58.262  2998  4318 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	... 12 more
09-07 16:48:58.262  2998  4318 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at fal.a(PG:38)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:48:58.262  2998  4318 E HttpOperation: 	... 14 more
,09-07 16:48:58.337  1566  3523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 16:48:58.337  1566  3523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 16:48:58.337  1566  3523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:48:58.337  1566  3523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:48:58.350  2998  4318 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 16:48:58.350  2998  4318 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jdm.a(PG:82)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jcs.o(PG:406)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jcn.a(PG:1379)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jcs.i(PG:143)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at hec.a(PG:42)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at hee.a(PG:102)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at czr.a(PG:65)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at kka.a(PG:108)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at czp.a(PG:19176)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at czp.a(PG:9081)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at czq.run(PG:1686)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:48:58.350  2998  4318 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jdj.a(PG:4091)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jdj.a(PG:1125)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jdm.a(PG:77)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	... 15 more
09-07 16:48:58.350  2998  4318 E HttpOperation: Caused by: faj: BadAuthentication
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at fal.a(PG:38)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	at jdj.a(PG:4089)
09-07 16:48:58.350  2998  4318 E HttpOperation: 	... 17 more
,09-07 16:48:58.350  2998  4318 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 16:48:58.350  2998  4318 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at hec.a(PG:42)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at hee.a(PG:102)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at czr.a(PG:65)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at kka.a(PG:108)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	... 15 more
09-07 16:48:58.350  2998  4318 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at fal.a(PG:38)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 16:48:58.350  2998  4318 E ExperimentLoader: 	... 17 more
,09-07 16:48:58.453   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 590110, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:49:24.000   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=616265, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:49:28.742  3043  4321 V KeepSync: Connecting to GoogleApiClient
,09-07 16:49:28.742   871   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 16:49:28.782  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:49:28.786  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:49:28.818  1566  1580 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 16:49:28.818  1566  1580 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 16:49:28.818  1566  1580 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:49:28.818  1566  1580 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:49:28.834  1752  4322 V BaseAuthAsyncOperation: access token request failed
,09-07 16:49:28.835  3043  4321 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 16:49:28.892  1566  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 16:49:28.893  1566  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-07 16:49:28.893  1566  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:49:28.893  1566  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:49:28.909  3043  4321 E KeepSync: IOException
09-07 16:49:28.909  3043  4321 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 16:49:28.909  3043  4321 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 16:49:28.909  3043  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 16:49:28.909  3043  4321 E KeepSync: 	... 10 more
09-07 16:49:28.909  3043  4321 W KeepSync: Sync result 2
,09-07 16:49:28.923   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 593938, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:49:28.962  3722  4323 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 16:49:28.979  3722  4324 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 16:49:29.004  1566  3523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
09-07 16:49:29.004  1566  3523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:49:29.004  1566  3523 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:49:29.004  1566  3523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:49:29.050  1566  2327 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
09-07 16:49:29.050  1566  2327 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 16:49:29.050  1566  2327 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:49:29.050  1566  2327 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:49:29.076  3722  4324 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
09-07 16:49:29.077  3722  4323 E BooksSync: Soft error
09-07 16:49:29.077  3722  4323 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:49:29.077  3722  4323 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 16:49:29.077  3722  4323 E BooksSync: Sync error
09-07 16:49:29.077  3722  4323 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 16:49:29.077  3722  4323 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 16:49:29.077  3722  4323 I BooksSync: Finished books sync
,09-07 16:49:29.088   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 620898, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 16:49:51.426   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=643692, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:50:15.588  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:50:15.589  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:50:15.602  3803  4333 V GoogleAuthProtoRequest: [314] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:50:15.631  1566  1580 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-07 16:50:15.631  1566  1580 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 16:50:15.631  1566  1580 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 16:50:15.631  1566  1580 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 16:50:15.656  3803  4333 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 16:50:17.333   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=669599, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:50:51.266   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=703532, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:51:17.173   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=729438, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:51:22.505   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=734770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:51:48.426   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=760692, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:51:53.758   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=766023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 16:52:19.680   871  4257 D NetlinkSocketObserver: NeighborEvent{elapsedMs=791945, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 16:58:15.831  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:58:15.833  1566  1566 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 16:58:15.849  3803  4356 V GoogleAuthProtoRequest: [315] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 16:58:15.877  1566  2402 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 16:58:15.877  1566  2402 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 16:58:15.877  1566  2402 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 16:58:15.877  1566  2402 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: [315] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: [315] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 16:58:15.897  3803  4356 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 16:59:27.004   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 17:00:35.002  4200  4215 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,TIME-OUT KILL (timeout was 1400000ms),09-07 17:07:46.768  4382  4382 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 17:07:46.772  4382  4382 D AndroidRuntime: CheckJNI is OFF
09-07 17:07:46.808  4382  4382 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 17:07:46.849  4382  4382 I Radio-JNI: register_android_hardware_Radio DONE
09-07 17:07:46.869  4382  4382 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 17:07:46.893   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-07 17:07:47.012   871   894 W PackageSettings: Skipping PackageSetting{6bd0d8e com.example.hello/10273} due to missing metadata
09-07 17:07:47.041   871   894 I art     : Starting a blocking GC Explicit
09-07 17:07:47.097   871   894 I art     : Explicit concurrent mark sweep GC freed 44228(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 652us total 47.200ms
09-07 17:07:47.129   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-07 17:07:47.134  4382  4382 I art     : System.exit called, status: 0
09-07 17:07:47.134  4382  4382 I AndroidRuntime: VM exiting with result code 0.
09-07 17:07:47.137   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-07 17:07:47.159  4200  4200 D BluetoothMapAppObserver: onReceive
09-07 17:07:47.159  4200  4200 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-07 17:07:47.162  2152  2307 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 17:07:47.163   871  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 17:07:47.166  1904  1904 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 17:07:47.168  3611  3611 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 17:07:47.181  1904  4397 I Keyboard.Facilitator.DecoderInitializer: run()
09-07 17:07:47.186  1904  4397 I Decoder : createOrResetDecoder
09-07 17:07:47.206  1976  1976 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-07 17:07:47.207   871  1869 I ActivityManager: Start proc 4400:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-07 17:07:47.242  4400  4400 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-07 17:07:47.249  1566  1566 I ConfigService: onCreate
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 17:07:47.257  1566  4413 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 17:07:47.257  1566  4413 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-07 17:07:47.264  1566  4413 W SQLiteOpenHelper: Opened config.db in read-only mode
09-07 17:07:47.272   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 17:07:47.277  1904  4397 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-07 17:07:47.283  1991  2080 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-07 17:07:47.285   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 17:07:47.286   871   883 E PackageManager: Failed to write settings, restoring backup
09-07 17:07:47.286   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 17:07:47.286   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 17:07:47.286   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 17:07:47.286   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 17:07:47.286   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 17:07:47.286   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.286   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.286   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.291   871   884 E DropBoxManagerService: Can't write: system_server_wtf
09-07 17:07:47.291   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 17:07:47.291   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 17:07:47.291   871   884 E DropBoxManagerService: 	... 13 more
09-07 17:07:47.296   871  1993 I ActivityManager: Start proc 4414:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-07 17:07:47.296  1991  2080 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 17:07:47.296  1991  2080 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1991
09-07 17:07:47.296  1991  2080 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.296  1991  2080 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.297   871  1998 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 17:07:47.298   871  4420 E DropBoxManagerService: Can't write: system_app_crash
09-07 17:07:47.298   871  4420 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 17:07:47.298   871  4420 E DropBoxManagerService: 	... 5 more
09-07 17:07:47.301  1991  2080 I Process : Sending signal. PID: 1991 SIG: 9
09-07 17:07:47.305  1904  4397 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 17:07:47.307  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 17:07:47.307  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 17:07:47.309  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 17:07:47.309  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 17:07:47.309  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 17:07:47.309  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 17:07:47.319  1904  4397 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 17:07:47.319  1904  4397 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 17:07:47.319  1904  4397 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 17:07:47.319  1904  4397 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 17:07:47.319  1904  4397 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 17:07:47.319  1904  4397 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 17:07:47.348  4400  4400 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-07 17:07:47.361  4400  4433 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 17:07:47.364   871  2008 I ActivityManager: Start proc 4434:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-07 17:07:47.369   871  1393 D GraphicsStats: Buffer count: 1
09-07 17:07:47.369   871   882 I WindowState: WIN DEATH: Window{d3d06a0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-07 17:07:47.380   871  1393 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1991) has died
09-07 17:07:47.381   871  1393 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-07 17:07:47.382   871  1393 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 17:07:47.397   871   884 I ActivityManager: Start proc 4447:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 17:07:47.429  4434  4434 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.442  4400  4425 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.443  4400  4425 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 17:07:47.447  4447  4447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 17:07:47.447  4447  4447 D AndroidRuntime: Shutting down VM
09-07 17:07:47.453  1566  1566 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-07 17:07:47.454  1566  1566 D AndroidRuntime: Shutting down VM
09-07 17:07:47.455  4447  4447 E AndroidRuntime: FATAL EXCEPTION: main
09-07 17:07:47.455  4447  4447 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4447
09-07 17:07:47.455  4447  4447 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 17:07:47.455  4447  4447 E AndroidRuntime: 	... 10 more
09-07 17:07:47.456  1566  1566 E AndroidRuntime: FATAL EXCEPTION: main
09-07 17:07:47.456  1566  1566 E AndroidRuntime: Process: com.google.process.gapps, PID: 1566
09-07 17:07:47.456  1566  1566 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 17:07:47.456  1566  1566 E AndroidRuntime: 	... 8 more
09-07 17:07:47.458  1752  4459 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 17:07:47.460  1752  4459 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 17:07:47.465   871  4464 E DropBoxManagerService: Can't write: system_app_crash
09-07 17:07:47.465   871  4464 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 17:07:47.465   871  4464 E DropBoxManagerService: 	... 5 more
09-07 17:07:47.466   871  4463 E DropBoxManagerService: Can't write: system_app_crash
09-07 17:07:47.466   871  4463 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 17:07:47.466   871  4463 E DropBoxManagerService: 	... 5 more
09-07 17:07:47.466   871  2007 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 17:07:47.467  4447  4447 I Process : Sending signal. PID: 4447 SIG: 9
09-07 17:07:47.468  1566  1566 I Process : Sending signal. PID: 1566 SIG: 9
09-07 17:07:47.477  1752  4459 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 17:07:47.478  1752  4459 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 17:07:47.501   871  2007 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4447) has died
09-07 17:07:47.502   871  2007 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 17:07:47.512  4400  4425 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-07 17:07:47.516   871   884 I ActivityManager: Start proc 4465:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 17:07:47.517   871  1309 D WifiService: Client connection lost with reason: 4
09-07 17:07:47.527   871  1943 I ActivityManager: Process com.google.process.gapps (pid 1566) has died
09-07 17:07:47.528   871  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-07 17:07:47.528   871  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-07 17:07:47.528   871  1943 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
09-07 17:07:47.539  1752  1752 W RocketImpressions: ClearcutLogger connection suspended: 1
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.545  4400  4433 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 17:07:47.545  4400  4433 E AndroidRuntime: Process: android.process.acore, PID: 4400
09-07 17:07:47.545  4400  4433 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.545  4400  4433 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 17:07:47.546  4400  4425 I Process : Sending signal. PID: 4400 SIG: 9
09-07 17:07:47.551   871   881 I ActivityManager: Start proc 4477:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-07 17:07:47.554   871  4483 E DropBoxManagerService: Can't write: system_app_crash
09-07 17:07:47.554   871  4483 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 17:07:47.554   871  4483 E DropBoxManagerService: 	... 5 more
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 17:07:47.567  4465  4465 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 17:07:47.567  4465  4465 D AndroidRuntime: Shutting down VM
09-07 17:07:47.578  4465  4465 E AndroidRuntime: FATAL EXCEPTION: main
09-07 17:07:47.578  4465  4465 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4465
09-07 17:07:47.578  4465  4465 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 17:07:47.578  4465  4465 E AndroidRuntime: 	... 10 more
09-07 17:07:47.581   871  1376 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 17:07:47.582  4465  4465 I Process : Sending signal. PID: 4465 SIG: 9
09-07 17:07:47.583   871  4492 E DropBoxManagerService: Can't write: system_app_crash
09-07 17:07:47.583   871  4492 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 17:07:47.583   871  4492 E DropBoxManagerService: 	... 5 more
09-07 17:07:47.601   871  1393 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4465) has died
09-07 17:07:47.602   871  1393 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 17:07:47.605  4477  4477 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
09-07 17:07:47.616  4477  4477 I MultiDex: VM with version 2.1.0 has multidex support
09-07 17:07:47.616  4477  4477 I MultiDex: install
09-07 17:07:47.616  4477  4477 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-07 17:07:47.622   871   884 I ActivityManager: Start proc 4493:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 17:07:47.626  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 17:07:47.626  1752  1752 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 17:07:47.637  1752  1752 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-07 17:07:47.637  1752  1752 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-07 17:07:47.638  1752  4459 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 17:07:47.638  1752  4459 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 17:07:47.643  4477  4477 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm

```
