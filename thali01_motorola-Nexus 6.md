#### Test 832688932759c28_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-30 16:54:05.594  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:05.605  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:54:05.607  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:54:05.639  1518  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-30 16:54:05.639  1518  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:54:05.639  1518  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:54:05.639  1518  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-30 16:54:05.673  3678  3678 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-30 16:54:05.673  3678  3678 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-30 16:54:05.674  3678  3678 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-30 16:54:06.225  4021  4021 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 16:54:06.230  4021  4021 D AndroidRuntime: CheckJNI is OFF
08-30 16:54:06.265  4021  4021 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 16:54:06.307  4021  4021 I Radio-JNI: register_android_hardware_Radio DONE
08-30 16:54:06.326  4021  4021 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 16:54:06.332   875  2021 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 16:54:06.389   875  2021 I ActivityManager: Start proc 4030:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 16:54:06.398  4021  4021 D AndroidRuntime: Shutting down VM
08-30 16:54:06.558  4030  4030 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 16:54:06.584  4030  4030 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 16:54:06.591  4030  4030 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2305-2307)
08-30 16:54:06.591  4030  4030 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:54:06.607  4030  4030 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6b9009f}
08-30 16:54:06.607  4030  4030 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:54:06.610  4030  4030 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 16:54:06.616  4030  4030 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 16:54:06.618  4030  4030 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 16:54:06.636  4030  4030 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 16:54:06.645  4030  4030 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 16:54:06.645  4030  4030 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:54:06.646  4030  4030 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:54:06.646  4030  4030 I Adreno  : Build Date                       : 10/20/15
08-30 16:54:06.646  4030  4030 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:54:06.646  4030  4030 I Adreno  : Local Branch                     : M14
08-30 16:54:06.646  4030  4030 I Adreno  : Remote Branch                    : 
08-30 16:54:06.646  4030  4030 I Adreno  : Remote Branch                    : 
08-30 16:54:06.646  4030  4030 I Adreno  : Reconstruct Branch               : 
,08-30 16:54:06.683   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a6f327a:true
,08-30 16:54:06.757  4030  4030 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 16:54:06.778  4030  4030 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 16:54:06.905  4030  4067 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 16:54:06.928  4030  4054 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 16:54:06.974  4030  4067 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 16:54:07.055   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +563ms (total +687ms)
,08-30 16:54:07.061  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-30 16:54:07.132  4030  4030 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4030
,08-30 16:54:07.276  4030  4030 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 16:54:07.615  4030  4069 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1695614672
,08-30 16:54:07.625  4030  4069 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 16:54:07.625  4030  4069 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 16:54:07.625  4030  4069 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 16:54:07.625  4030  4069 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 16:54:07.625  4030  4069 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 16:54:07.625  4030  4069 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2b4962 added. We now have 1 listener(s)
,08-30 16:54:07.630  4030  4069 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-30 16:54:07.631  4030  4069 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:54:07.632  4030  4069 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:54:07.632  4030  4069 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 16:54:07.638  4030  4069 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55d0229 added. We now have 1 listener(s)
,08-30 16:54:07.639  4030  4069 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:07.644   875  1317 D WifiService: New client listening to asynchronous messages
,08-30 16:54:07.646  4030  4069 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:54:07.646  4030  4069 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 16:54:07.646  4030  4069 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 16:54:07.646  4030  4069 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 16:54:07.646  4030  4069 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 16:54:07.653  4030  4069 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:07.653  4030  4069 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 16:54:07.667  4030  4069 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:07.667  4030  4069 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:07.667  4030  4069 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-30 16:54:07.667  4030  4069 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:07.668  4030  4069 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:54:07.673  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:07.680  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:07.729  4030  4030 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 16:54:08.152  4030  4039 I art     : Background sticky concurrent mark sweep GC freed 69572(6MB) AllocSpace objects, 18(1604KB) LOS objects, 29% free, 23MB/32MB, paused 694us total 101.214ms
,08-30 16:54:08.721  4030  4076 W jxcore-log: Initializing JXcore engine
,08-30 16:54:08.721  4030  4076 W jxcore-log: JXcore engine is ready
,08-30 16:54:08.754  4076  4076 W Thread-369: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 16:54:08.754  4076  4076 W Thread-369: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11890]" dev="sockfs" ino=11890 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 16:54:08.754  4076  4076 W Thread-369: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-30 16:54:08.769  4030  4076 W jxcore-log: Starting JXcore engine
,08-30 16:54:08.754  4076  4076 W Thread-369: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24340]" dev="sockfs" ino=24340 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 16:54:08.852  4030  4076 W jxcore-log: Platform android
08-30 16:54:08.852  4030  4076 W jxcore-log: 
,08-30 16:54:08.852  4030  4076 W jxcore-log: Process ARCH arm
08-30 16:54:08.852  4030  4076 W jxcore-log: 
,08-30 16:54:09.040  4030  4076 I jxcore-log: JXcore Cordova bridge is ready!
08-30 16:54:09.040  4030  4076 I jxcore-log: 
,08-30 16:54:09.041  4030  4076 W jxcore-log: JXcore engine is started
,08-30 16:54:09.052  4030  4069 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 16:54:09.056  4030  4030 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 16:54:10.293   875  1853 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 16:54:14.129  3920  4078 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 16:54:14.154  3920  4079 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 16:54:14.180  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:14.184  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:14.231  1518  2137 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 16:54:14.231  1518  2137 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 16:54:14.231  1518  2137 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:54:14.231  1518  2137 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:54:14.286  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:14.291  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:14.337  1518  2137 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-30 16:54:14.337  1518  2137 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 16:54:14.337  1518  2137 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:54:14.337  1518  2137 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:54:14.367  3920  4079 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 16:54:14.368  3920  4078 E BooksSync: Soft error
08-30 16:54:14.368  3920  4078 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:54:14.368  3920  4078 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 16:54:14.368  3920  4078 E BooksSync: Sync error
08-30 16:54:14.368  3920  4078 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 16:54:14.368  3920  4078 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 16:54:14.368  3920  4078 I BooksSync: Finished books sync
,08-30 16:54:14.377   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162259, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 16:54:18.627  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 16:54:18.627  4030  4076 I jxcore-log: 
,08-30 16:54:18.629  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 16:54:18.629  4030  4076 I jxcore-log: 
,08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:18.642  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:18.646  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:54:18.648  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 16:54:18.648  4030  4076 I jxcore-log: 
,08-30 16:54:18.650  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 16:54:18.650  4030  4076 I jxcore-log: 
,08-30 16:54:19.138  4030  4076 D executeNativeTests: Running unit tests
,08-30 16:54:19.196  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:19.196  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 added. We now have 2 listener(s)
08-30 16:54:19.197  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:54:19.197  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:19.197  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:19.197  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:54:19.197  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 added. We now have 2 listener(s)
,08-30 16:54:19.197  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:19.198  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:54:19.204  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.230  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:19.232  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.233  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:54:19.235  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 16:54:19.237  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 16:54:19.237  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:54:19.238  4030  4076 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 16:54:19.239  4030  4076 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 16:54:19.239  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 16:54:19.239  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 16:54:19.239  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 16:54:19.239  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.239  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.240  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.240  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.240  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.240  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.241  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:19.241  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:19.241  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 removed from the list
,08-30 16:54:19.241  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.241  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 removed from the list
08-30 16:54:19.246  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.247  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.247  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.248  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.248  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.251  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.251  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.251  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.251  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.257  4030  4076 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 16:54:19.259  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.259  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:54:19.259  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.260  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.260  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.260  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.260  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.261  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:19.261  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.261  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.261  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.261  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 16:54:19.262  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.262  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.263  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.264  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.264  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.264  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
,08-30 16:54:19.284  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 16:54:19.284  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:54:19.284  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-30 16:54:19.285  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:54:19.285  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 16:54:19.285  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 16:54:19.285  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:54:19.286  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:54:19.286  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:54:19.286  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-30 16:54:19.286  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 16:54:19.287  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:54:19.287  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:54:19.287  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:54:19.287  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
08-30 16:54:19.288  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:54:19.288  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:54:19.288  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 16:54:19.288  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:54:19.288  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:54:19.289  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:54:19.289  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:54:19.289  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 16:54:19.289  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:54:19.290  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:54:19.290  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:54:19.290  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 16:54:19.290  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:54:19.291  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:54:19.291  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:54:19.291  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:54:19.291  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.292  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.292  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.293  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.293  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.293  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.293  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
,08-30 16:54:19.294  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.294  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.294  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:54:19.294  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.295  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.295  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.295  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.298  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:54:19.298  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.298  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.298  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.299  4030  4076 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 16:54:19.301  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.309  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:19.312  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:54:19.312  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:19.312  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:54:19.312  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:54:19.313  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:54:19.313  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:19.313  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:54:19.318  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:54:19.318  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:54:19.318  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.321  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.325  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:54:19.327  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:54:19.327  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:54:19.330  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 16:54:19.333  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 16:54:19.334  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:54:19.335  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 16:54:19.337  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 16:54:19.342  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:19.348  2614  2759 D BtGatt.GattService: registerClient() - UUID=b7a313b9-7c13-45c1-934d-a91da45d3f55
,08-30 16:54:19.349  2614  2648 D BtGatt.GattService: onClientRegistered() - UUID=b7a313b9-7c13-45c1-934d-a91da45d3f55, clientIf=5
,08-30 16:54:19.350  4030  4040 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 16:54:19.352  2614  2625 D BtGatt.GattService: start scan with filters
,08-30 16:54:19.360  2614  2652 D BtGatt.ScanManager: handling starting scan
,08-30 16:54:19.360  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 16:54:19.361  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:54:19.361  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:54:19.361  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-30 16:54:19.362  2614  2652 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:19.364  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:19.365  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:19.365  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:54:19.366  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:54:19.370  2614  2648 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 16:54:19.370  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.370  4030  4076 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:54:19.370  2614  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:54:19.375  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.376  4030  4076 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:54:19.376  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:54:19.376  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:54:19.376  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.376  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:54:19.376  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:54:19.376  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:54:19.376  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:54:19.376  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:54:19.377  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 16:54:19.377  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:54:19.377  2614  2648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:54:19.378  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.378  4030  4076 D BluetoothAdapter: STATE_ON
08-30 16:54:19.378  2614  2652 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:54:19.378  2614  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:54:19.378  2614  2759 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:54:19.379  2614  2625 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:54:19.379  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:54:19.379  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:54:19.380  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:54:19.380  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:54:19.380  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:54:19.387  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:54:19.387  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:54:19.387  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:54:19.387  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:54:19.388  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:54:19.389  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.389  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.389  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:54:19.389  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
,08-30 16:54:19.389  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:19.389  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.389  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:54:19.389  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.389  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.389  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.389  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:19.390  4030  4076 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 16:54:19.392  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:19.394  2614  2648 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:54:19.394  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.397  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:19.399  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:54:19.399  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:19.399  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:54:19.399  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:54:19.399  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:54:19.399  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:19.399  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:54:19.403  2614  2648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 16:54:19.403  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.405  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.409  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.410  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:54:19.410  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:54:19.413  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:54:19.414  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 16:54:19.414  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:54:19.417  2614  2648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:54:19.417  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.418  2614  2652 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:54:19.419  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:54:19.419  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:54:19.419  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:54:19.419  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:19.423  2614  2759 D BtGatt.GattService: registerClient() - UUID=fb21eb02-4afd-497e-bfa9-8826ab10eda9
08-30 16:54:19.423  2614  2648 D BtGatt.GattService: onClientRegistered() - UUID=fb21eb02-4afd-497e-bfa9-8826ab10eda9, clientIf=5
,08-30 16:54:19.424  4030  4040 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:54:19.424  2614  2626 D BtGatt.GattService: start scan with filters
,08-30 16:54:19.428  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:54:19.429  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:54:19.429  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:54:19.429  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:54:19.429  2614  2648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:54:19.430  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.430  2614  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 16:54:19.435  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:19.435  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:54:19.435  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:19.436  2614  2648 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:54:19.436  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.438  2614  2652 D BtGatt.ScanManager: handling starting scan
,08-30 16:54:19.439  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:54:19.442  4030  4076 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 16:54:19.444  2614  2648 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:54:19.444  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.444  2614  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:54:19.445  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.445  4030  4076 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 16:54:19.445  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:54:19.445  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 16:54:19.445  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.445  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 16:54:19.445  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 16:54:19.445  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:54:19.445  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 16:54:19.445  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 16:54:19.445  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 16:54:19.445  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:54:19.446  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:19.446  2614  2626 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:54:19.447  2614  2740 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:54:19.447  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:54:19.447  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 16:54:19.447  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 16:54:19.447  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:54:19.447  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:54:19.448  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:19.449  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:54:19.449  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:54:19.449  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:54:19.449  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:19.450  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.450  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.453  2614  2648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:54:19.450  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 16:54:19.453  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.453  2614  2652 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:54:19.454  2614  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:54:19.453  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.450  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:19.458  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-30 16:54:19.458  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.458  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.459  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
,08-30 16:54:19.459  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.459  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.459  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.460  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.463  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:54:19.463  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.463  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.463  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.464  4030  4076 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false,
08-30 16:54:19.465  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e,
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.469  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:19.477  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:54:19.477  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:54:19.479  2614  2648 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:54:19.480  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.481  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.479  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:54:19.482  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:54:19.483  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:54:19.483  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:19.483  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:54:19.485  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.486  2614  2648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:54:19.486  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.489  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 16:54:19.489  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 16:54:19.494  2614  2648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 16:54:19.494  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:54:19.494  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.494  2614  2652 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:54:19.495  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:54:19.495  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:54:19.498  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:54:19.498  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:54:19.498  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:54:19.499  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:19.499  2614  2648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:54:19.500  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:19.500  2614  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:54:19.501  2614  2740 D BtGatt.GattService: registerClient() - UUID=f05f142d-2389-4bb8-9d2b-2d5346476ceb
,08-30 16:54:19.501  2614  2648 D BtGatt.GattService: onClientRegistered() - UUID=f05f142d-2389-4bb8-9d2b-2d5346476ceb, clientIf=5
,08-30 16:54:19.502  4030  4041 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 16:54:19.502  2614  2626 D BtGatt.GattService: start scan with filters
,08-30 16:54:19.505  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:54:19.505  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:54:19.505  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:54:19.505  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:54:19.506  2614  2648 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:54:19.506  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-30 16:54:19.507  2614  2652 D BtGatt.ScanManager: handling starting scan
,08-30 16:54:19.510  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:19.511  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:19.511  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:54:19.513  2614  2648 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:54:19.513  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.513  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 16:54:19.513  2614  2652 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:54:19.515  4030  4076 I io.jxcore.node.ConnectionHelper: start: OK
08-30 16:54:19.515  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.515  4030  4076 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:54:19.516  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.516  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:54:19.516  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.516  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:54:19.516  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:54:19.516  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:54:19.516  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:54:19.516  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:54:19.516  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:54:19.516  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:54:19.516  4030  4076 D BluetoothAdapter: STATE_ON
08-30 16:54:19.517  2614  2626 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:54:19.517  2614  2625 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:54:19.519  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:54:19.519  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:54:19.519  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:54:19.519  2614  2648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:54:19.519  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.519  2614  2652 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:54:19.519  2614  2652 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:54:19.519  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:54:19.519  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:54:19.520  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:54:19.520  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:54:19.520  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:54:19.520  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:54:19.521  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:19.522  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.522  4030  4076 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 16:54:19.522  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.522  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.522  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.522  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.522  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.522  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:19.522  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.522  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:54:19.522  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.522  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.522  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.522  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.522  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.523  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.523  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.523  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:54:19.523  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.523  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.523  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.524  4030  4076 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 16:54:19.524  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.524  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.524  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.525  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.525  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.525  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.525  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.525  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:19.525  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.525  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.525  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.525  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.525  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.525  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.526  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.526  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:54:19.526  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.526  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.527  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:54:19.527  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.527  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.527  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:54:19.527  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.527  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.527  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.527  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.527  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.527  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.527  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.527  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.527  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.527  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.528  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.528  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.528  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.528  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.528  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.529  4030  4076 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 16:54:19.529  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.529  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.529  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:54:19.530  2614  2648 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:54:19.530  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.530  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.530  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.530  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.530  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
,08-30 16:54:19.530  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.530  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.530  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.530  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.530  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.530  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.530  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.531  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.531  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:54:19.531  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.531  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.532  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 16:54:19.532  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.532  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.532  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.532  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.532  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.532  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.532  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.532  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.532  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.532  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.532  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.532  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.532  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.532  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.533  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.533  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.533  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.533  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.533  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:54:19.535  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:54:19.535  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 16:54:19.535  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 16:54:19.535  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 16:54:19.535  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 16:54:19.536  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.536  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:54:19.536  2614  2648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:54:19.536  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.536  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.538  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.538  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.539  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.539  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.539  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:19.539  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.539  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.539  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.539  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.540  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.540  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.542  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.542  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.542  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:19.542  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.543  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:54:19.543  4030  4076 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:54:19.543  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 16:54:19.544  2614  2648 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:54:19.544  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.544  2614  2652 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:54:19.547  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:54:19.547  4030  4076 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 16:54:19.547  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 16:54:19.548  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 16:54:19.548  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 16:54:19.548  4030  4076 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:54:19.549  4030  4076 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 16:54:19.549  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:54:19.549  4030  4076 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:54:19.549  4030  4076 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 16:54:19.549  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:54:19.549  4030  4076 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 16:54:19.549  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 16:54:19.549  2614  2648 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:54:19.549  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.549  2614  2652 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:54:19.551  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-30 16:54:19.552  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-30 16:54:19.552  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 16:54:19.553  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 16:54:19.553  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 16:54:19.553  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-30 16:54:19.553  4030  4076 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 16:54:19.553  4030  4076 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 16:54:19.553  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.553  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.554  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.554  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.554  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.554  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.554  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 16:54:19.555  4030  4081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 433)
,08-30 16:54:19.555  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.555  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.555  2614  2648 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:54:19.555  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.555  2614  2648 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:19.555  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.555  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.555  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.555  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.555  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.556  4030  4082 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 433
,08-30 16:54:19.557  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.557  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.557  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.557  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.558  4030  4076 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 16:54:19.558  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.558  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.558  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.558  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.558  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.558  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.559  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.559  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.559  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.559  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.559  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.559  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.559  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.559  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.559  4030  4081 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:54:19.560  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.560  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.560  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.560  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
,08-30 16:54:19.561  4030  4076 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 16:54:19.561  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.561  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:54:19.561  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.562  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.562  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.563  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.563  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.563  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.563  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.563  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.563  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.563  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.563  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.563  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.564  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.564  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.564  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.565  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.565  4030  4076 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 16:54:19.565  4030  4076 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 16:54:19.566  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 16:54:19.566  4030  4076 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 16:54:19.566  4030  4076 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-30 16:54:19.566  4030  4076 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 16:54:19.566  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 16:54:19.566  4030  4076 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 16:54:19.567  4030  4076 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 16:54:19.567  4030  4076 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 16:54:19.567  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 16:54:19.567  4030  4076 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 16:54:19.567  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.567  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.567  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.568  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.568  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.568  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.568  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
,08-30 16:54:19.568  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.568  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.568  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.568  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.568  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.568  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.568  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.569  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.569  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.569  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.569  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
,08-30 16:54:19.570  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.570  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.570  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.570  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.570  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.570  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.570  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.570  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.570  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.570  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.570  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.570  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.570  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.571  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.571  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.571  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.571  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.571  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.571  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.571  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.571  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.571  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.571  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.571  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
,08-30 16:54:19.571  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.571  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.571  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.571  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.571  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.572  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.572  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.572  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:19.572  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.573  4030  4076 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 16:54:19.574  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:19.574  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 16:54:19.575  4030  4076 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 16:54:19.575  4030  4076 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 16:54:19.575  4030  4030 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 16:54:19.575  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 16:54:19.575  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:54:19.576  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.576  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 16:54:19.576  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 16:54:19.576  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 16:54:19.576  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.576  4030  4076 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 16:54:19.576  4030  4030 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 16:54:19.576  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
,08-30 16:54:19.576  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.576  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:54:19.576  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:54:19.576  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:54:19.576  4030  4083 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:54:19.576  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.576  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.578  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:19.578  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.578  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:19.578  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:54:19.578  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.578  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.578  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.578  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:19.578  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.578  4030  4083 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 16:54:19.578  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.578  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.578  4030  4083 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 16:54:19.578  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.579  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.579  4030  4083 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 16:54:19.579  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.579  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.579  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.579  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.579  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.579  4030  4030 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 16:54:19.579  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.580  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:54:19.580  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.580  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.580  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.581  4030  4076 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 16:54:19.581  4030  4076 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 16:54:19.581  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 16:54:19.583  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 16:54:19.583  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.585  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.585  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:54:19.586  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.586  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.586  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.586  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.586  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.586  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.586  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:54:19.586  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.586  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.586  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.586  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.587  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.587  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.587  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.587  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
,08-30 16:54:19.590  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:19.590  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.590  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:54:19.590  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:19.590  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.590  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.590  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.590  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.590  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.590  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 16:54:19.590  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.591  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.591  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.591  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.592  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:54:19.592  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:19.592  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.592  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.592  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:19.592  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:19.592  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:54:19.592  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:19.593  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.593  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:19.593  4030  4076 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a603b2 not in the list
08-30 16:54:19.593  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.593  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.593  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:19.593  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:19.593  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.593  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:19.593  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:19.594  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:19.594  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:54:19.594  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:19.594  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17bff03 not in the list
08-30 16:54:19.595  4030  4076 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 16:54:19.595  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:54:19.595  4030  4076 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 16:54:19.595  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 16:54:19.595  4030  4076 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 16:54:19.595  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 16:54:19.596  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 16:54:19.596  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 16:54:19.597  4030  4076 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-30 16:54:19.597  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 16:54:19.597  4030  4076 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 16:54:19.597  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-30 16:54:19.597  4030  4076 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 16:54:19.597  4030  4076 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 16:54:19.597  4030  4076 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 16:54:19.597  4030  4076 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 16:54:19.598  4030  4076 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 16:54:19.598  4030  4076 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-30 16:54:19.598  4030  4076 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 16:54:19.598  4030  4076 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-30 16:54:19.598  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:19.599  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ff7542d added. We now have 2 listener(s)
08-30 16:54:19.599  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:19.600  4030  4076 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 16:54:19.601   875   885 D WifiService: setWifiEnabled: true pid=4030, uid=10000
,08-30 16:54:19.601   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:54:19.602  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:19.602  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fc2bd62 added. We now have 3 listener(s)
08-30 16:54:19.602  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:19.607  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:19.607  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76aaef3 added. We now have 4 listener(s)
08-30 16:54:19.607  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:19.609  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:19.609  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cacb7b0 added. We now have 5 listener(s)
08-30 16:54:19.609  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:19.611   875  2028 D WifiService: setWifiEnabled: false pid=4030, uid=10000
08-30 16:54:19.611   875  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:54:19.615  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:19.618  2614  2642 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 16:54:19.618  2614  2642 D BluetoothAdapterProperties: Setting state to 13
08-30 16:54:19.618  2614  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 16:54:19.619  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-30 16:54:19.619  2614  2642 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.620  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:54:19.620  2614  2642 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:54:19.622  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:19.622  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:54:19.623  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 16:54:19.625  2614  2614 D BluetoothMapService: onReceive
08-30 16:54:19.625  2614  2614 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-30 16:54:19.625  2614  2614 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:54:19.626  2614  2614 D BluetoothMapService: MAP Service closeService in
08-30 16:54:19.626  2614  2614 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 16:54:19.626  2614  2614 D ObexServerSockets0: shutdown(block = true)
08-30 16:54:19.626  2614  2648 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:54:19.626  2614  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-30 16:54:19.627  2614  2614 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 16:54:19.627  2614  2614 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:54:19.628  2614  2736 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 16:54:19.628  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.628  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:54:19.628  2614  2764 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 16:54:19.628  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.629  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.629  2614  2765 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 16:54:19.630  2614  2614 I BtOppRfcommListener: stopping Accept Thread
08-30 16:54:19.631  2614  3599 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:54:19.631  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.631  2614  3599 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:54:19.632  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 16:54:19.633  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:19.633  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:54:19.634  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:19.634  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:19.635   875  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 16:54:19.635  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.636   875  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 16:54:19.636   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:54:19.636   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:54:19.638  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.641  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:19.645   875  1316 E native  : do suspend true
,08-30 16:54:19.651   875   888 I ActivityManager: Start proc 4086:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-30 16:54:19.653  2614  2614 D HeadsetService: Received stop request...Stopping profile...
,08-30 16:54:19.654  1964  2126 D BluetoothHeadset: Proxy object disconnected
,08-30 16:54:19.655   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:19.655  1370  1388 D BluetoothHeadset: Proxy object disconnected
,08-30 16:54:19.655  1370  1370 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:54:19.656   875  1857 D DhcpClient: Clearing IP address
,08-30 16:54:19.656   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:54:19.657  2614  2614 D A2dpService: Received stop request...Stopping profile...
,08-30 16:54:19.658   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 16:54:19.658  2614  2746 D A2dpStateMachine: Exit Disconnected: -1
,08-30 16:54:19.658   875   875 D BluetoothHeadset: Proxy object disconnected
,08-30 16:54:19.659   875   875 D BluetoothA2dp: Proxy object disconnected
,08-30 16:54:19.659  2614  2614 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:19.659  2614  2614 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:19.659  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:54:19.659  2614  2614 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:19.660  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-30 16:54:19.660  2614  2614 D HidService: Received stop request...Stopping profile...
08-30 16:54:19.660  2614  2614 D HidService: Stopping Bluetooth HidService
08-30 16:54:19.660   373   873 D CommandListener: Setting iface cfg
08-30 16:54:19.661  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-30 16:54:19.661  1370  1370 D HidProfile: Bluetooth service disconnected
08-30 16:54:19.663  2614  2614 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 16:54:19.664  2614  2648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 16:54:19.664  2614  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:19.664  2614  2614 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:54:19.664  2614  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:19.664  2614  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:19.664  2614  2648 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 16:54:19.665  2614  2614 D HealthService: Received stop request...Stopping profile...
08-30 16:54:19.667  2614  2614 D PanService: Received stop request...Stopping profile...
08-30 16:54:19.668  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 16:54:19.668  1370  1370 D PanProfile: Bluetooth service disconnected
08-30 16:54:19.668  1518  3585 V NativeCrypto: Read error: ssl=0xaa23ca00: I/O error during system call, Connection timed out
08-30 16:54:19.669  2614  2614 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:19.669  2614  2614 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:19.669  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:19.670  2614  2614 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:19.670   875  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
08-30 16:54:19.672  2614  2648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-30 16:54:19.672  2614  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 16:54:19.672  2614  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:19.672  2614  2614 D BluetoothMapService: Received stop request...Stopping profile...
08-30 16:54:19.672  2614  2732 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:54:19.673  2614  2732 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:54:19.673  2614  2732 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:54:19.673  2614  2732 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:54:19.672  2614  2614 D BluetoothMapService: stop()
08-30 16:54:19.675   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:54:19.675   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-30 16:54:19.675  2614  2614 D BluetoothMapAppObserver: deinitObservers()
08-30 16:54:19.675  2614  2614 D BluetoothMapAppObserver: removeReceiver()
08-30 16:54:19.676   396   396 E Parcel  : Reading a NULL string not supported here.
08-30 16:54:19.677  1370  1370 D BluetoothMap: Proxy object disconnected
08-30 16:54:19.677  1370  1370 D MapProfile: Bluetooth service disconnected
,08-30 16:54:19.677  2614  2614 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:19.677  2614  2614 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:19.678  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:19.678  2614  2614 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:19.678  2614  2614 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:54:19.678  2614  2614 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:54:19.678  2614  2614 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:19.678  2614  2614 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:54:19.678  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:19.678  2614  2614 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:19.678   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:54:19.678  2614  2614 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:54:19.678   875  1316 E native  : do suspend true
08-30 16:54:19.679   875  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 16:54:19.679  2614  2648 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:54:19.679  2614  2648 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 16:54:19.680  2614  2614 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 16:54:19.681  2614  2614 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:19.681  2614  2614 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:19.681  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:54:19.681  2614  2614 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:19.681  2614  2614 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:54:19.682  2614  2614 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 16:54:19.685  2614  2614 D BluetoothMapService: MAP Service closeService in
08-30 16:54:19.685  2614  2614 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:19.685  2614  2614 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:19.686  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:19.686  2614  2614 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:19.686  2614  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 16:54:19.686  2614  2642 D BluetoothAdapterProperties: Setting state to 15
08-30 16:54:19.686  2614  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 16:54:19.687  1370  1388 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:54:19.688  1370  1383 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:54:19.688  1964  2126 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:19.689  2614  2642 I BluetoothAdapterState: Entering BleOnState
,08-30 16:54:19.689  1370  1387 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:54:19.689  2614  2614 D BluetoothMapService: cleanup()
08-30 16:54:19.689  2614  2614 D BluetoothMapService: MAP Service closeService in
08-30 16:54:19.690   875  1863 D DhcpClient: Receive thread stopped
08-30 16:54:19.690   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:19.690   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:54:19.690   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:54:19.690   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:19.690  1370  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:19.691  1370  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:54:19.692  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:54:19.692  2614  2642 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 16:54:19.692  2614  2642 D BluetoothAdapterProperties: Setting state to 16
08-30 16:54:19.693  2614  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 16:54:19.693  2614  2642 D BluetoothAdapterProperties: onBleDisable
,08-30 16:54:19.693  2614  2642 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:54:19.693  2614  2644 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 16:54:19.695  2614  2732 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 16:54:19.695  2614  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:19.696  4030  4081 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 433)
08-30 16:54:19.697  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:19.697  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:19.697  2614  2648 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:54:19.698  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.698  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:19.699  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:19.699  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:19.699  1518  3585 V NativeCrypto: SSL shutdown failed: ssl=0xaa23ca00: I/O error during system call, Broken pipe
08-30 16:54:19.699  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.700  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:19.701  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.701  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.717   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 16:54:19.722  4086  4086 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-30 16:54:19.734  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:54:19.739  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:54:19.740   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 16:54:19.740   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-30 16:54:19.741   875  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 16:54:19.741   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:54:19.744   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7fa48de:true
08-30 16:54:19.751   875   886 I ActivityManager: Start proc 4102:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-30 16:54:19.752   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:54:19.754   875   892 D Tethering: MasterInitialState.processMessage what=3
08-30 16:54:19.756  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.757  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:19.770   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 16:54:19.772  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:19.772  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:19.773  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.773  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:19.773   875  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:54:19.774  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:19.774  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:19.775  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:19.775  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:19.781  2091  2348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 16:54:19.789  4086  4086 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 16:54:19.790  4086  4086 D BluetoothMap: Create BluetoothMap proxy object
,08-30 16:54:19.801  4102  4102 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-30 16:54:19.804  4086  4086 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 16:54:19.817  4086  4086 D DockEventReceiver: finishStartingService: stopping service
08-30 16:54:19.823   373   873 E Netd    : netlink response contains error (No such file or directory)
08-30 16:54:19.825   875  2021 I ActivityManager: Killing 3397:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-30 16:54:19.899  2614  2648 I bt_hci  : shut_down
,08-30 16:54:19.900  2614  2653 D bt_hwcfg: hw_epilog_process
,08-30 16:54:19.901  2614  2653 I bt_vendor: low_power_mode_cb
,08-30 16:54:19.921  2614  2653 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 16:54:19.922  2614  2653 I bt_vendor: epilog_cb
,08-30 16:54:19.922  2614  2653 I bt_hci  : epilog_finished_callback
,08-30 16:54:19.926  2614  2648 I bt_hci_h4: hal_close
,08-30 16:54:19.926  2614  2648 I bt_userial_vendor: device fd = 51 close
,08-30 16:54:19.991  4102  4102 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
,08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.991  4102  4102 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.991  4102  4102 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.991  4102  4102 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.991  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.992  4102  4102 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.992  4102  4102 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.992  4102  4102 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:19.992  4102  4102 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:19.992  4102  4102 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:54:19.997  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:54:20.003  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:54:20.037   875  1924 I ActivityManager: Start proc 4137:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-30 16:54:20.039  4086  4086 D DockEventReceiver: finishStartingService: stopping service
08-30 16:54:20.044   875  1984 I ActivityManager: Killing 3738:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-30 16:54:20.079  4030  4030 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:54:20.102  2614  2644 D bt_stack_manager: event_shut_down_stack finished.
,08-30 16:54:20.103  2614  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 16:54:20.106  2614  2614 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:54:20.106  2614  2642 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 16:54:20.107  2614  2614 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 16:54:20.107  2614  2614 D BtGatt.GattService: stop()
08-30 16:54:20.108  2614  2614 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:54:20.110  2614  2614 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:20.111  2614  2614 V BluetoothAdapterState: isTurningOn()=false
,08-30 16:54:20.111  2614  2614 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:20.111  2614  2614 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 16:54:20.112  2614  2642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 16:54:20.112  2614  2642 D BluetoothAdapterProperties: Setting state to 10
08-30 16:54:20.113  2614  2642 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 16:54:20.115  2614  2642 I BluetoothAdapterState: Entering OffState
,08-30 16:54:20.116   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-30 16:54:20.121  4137  4137 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-30 16:54:20.135  2614  2614 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 16:54:20.135  2614  2614 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 16:54:20.135  2614  2614 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 16:54:20.136  2614  2644 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 16:54:20.139  2614  2644 D bt_stack_manager: event_clean_up_stack finished.
,08-30 16:54:20.150  2614  2614 I art     : System.exit called, status: 0
,08-30 16:54:20.150  2614  2614 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 16:54:20.212   875   885 I ActivityManager: Process com.android.bluetooth (pid 2614) has died
,08-30 16:54:20.357  4137  4155 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-30 16:54:20.357  4137  4155 I Babel_SMS: MmsConfig.loadMmsSettings
,08-30 16:54:20.359  4137  4155 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-30 16:54:20.359  4137  4155 I Babel_SMS: MmsConfig.loadFromDatabase
,08-30 16:54:20.397  4137  4155 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-30 16:54:20.397  4137  4155 I Babel_SMS: MmsConfig.loadFromResources
,08-30 16:54:20.400  4137  4155 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 16:54:20.401  4137  4155 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-30 16:54:20.446  4137  4137 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:54:20.450  4137  4137 I Babel_Crash: startup - clean
,08-30 16:54:20.504  4137  4137 I Babel_telephony: TeleModule.launchCompleted
,08-30 16:54:20.511   875  2001 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 16:54:20.521  4137  4137 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-30 16:54:20.528  4137  4137 W Babel   : BAM#gBA: invalid account id: -1
,08-30 16:54:20.528  4137  4137 W Babel   : BAM#gBA: invalid account id: -1
,08-30 16:54:20.528  4137  4137 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-30 16:54:20.539  4137  4162 I Babel   : deleted: false for 0
,08-30 16:54:20.542   875  1970 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-30 16:54:20.559  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:54:20.563  1733  1733 D SystemUpdateService: onCreate
,08-30 16:54:20.580  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:54:20.613  1733  4164 I SystemUpdateService: active receiver: enabled
,08-30 16:54:20.617  1733  4164 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:54:20.618  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 16:54:20.620  1733  4164 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 16:54:20.620  1733  4164 I SystemUpdateService: now status is 0 (complete)
08-30 16:54:20.620  1733  4164 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:54:20.620  1733  4164 I SystemUpdateService: file has been verified
08-30 16:54:20.620  1733  4164 I SystemUpdateService: OTA package size = 12249756
,08-30 16:54:20.626  1733  4164 I SystemUpdateService: showing system update notification
,08-30 16:54:20.627  1733  2314 I iu.UploadsManager: num queued entries: 0
,08-30 16:54:20.628  1733  2314 I iu.UploadsManager: num updated entries: 0
,08-30 16:54:20.629  1733  2314 I iu.SyncManager: NEXT; no task
,08-30 16:54:20.630  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:54:20.633  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:54:20.654   875   886 I ActivityManager: Start proc 4166:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 16:54:20.670  1733  1733 D SystemUpdateService: onDestroy
,08-30 16:54:20.676  4137  4137 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:54:20.717  4166  4166 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 16:54:20.719  4166  4166 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:54:20.776  4166  4166 D SprintDMHelper: simOperator: 
08-30 16:54:20.776  4166  4166 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:54:20.787  4137  4137 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 16:54:20.793  4137  4137 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:54:20.794  4137  4137 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:54:20.805  4137  4137 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:54:20.812   875   886 I ActivityManager: Start proc 4178:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 16:54:20.814  4137  4137 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 16:54:20.828  4102  4124 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 16:54:20.831   875  1992 I ActivityManager: Killing 3610:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 16:54:20.886  4137  4137 I vclib   : onServiceConnected
,08-30 16:54:20.976   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b94869:true
,08-30 16:54:21.017   875  2021 I ActivityManager: Start proc 4194:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 16:54:21.020  4137  4193 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 16:54:21.023   875  1970 I ActivityManager: Killing 3657:android.process.acore/u0a5 (adj 15): empty #17
,08-30 16:54:21.097  4194  4194 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 16:54:21.161  4194  4194 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 16:54:21.161  4194  4194 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 16:54:21.161  4194  4194 I GAv4    :   adb logcat -s GAv4
,08-30 16:54:21.181  4194  4194 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:54:21.188  4194  4194 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,08-30 16:54:21.218  4194  4211 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 16:54:21.334  4194  4194 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 16:54:21.375  4194  4194 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 16:54:21.385  4194  4194 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7098-7101)
,08-30 16:54:21.385  4194  4194 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 16:54:21.398  4194  4194 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f67d6e3}
,08-30 16:54:21.399  4194  4194 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 16:54:21.399  4194  4194 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 16:54:21.408  4194  4194 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 16:54:21.410  4194  4194 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 16:54:21.427  4194  4194 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 16:54:21.443  4194  4194 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 16:54:21.443  4194  4194 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 16:54:21.443  4194  4194 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 16:54:21.443  4194  4194 I Adreno  : Build Date                       : 10/20/15
08-30 16:54:21.443  4194  4194 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 16:54:21.443  4194  4194 I Adreno  : Local Branch                     : M14
08-30 16:54:21.443  4194  4194 I Adreno  : Remote Branch                    : 
08-30 16:54:21.443  4194  4194 I Adreno  : Remote Branch                    : 
08-30 16:54:21.443  4194  4194 I Adreno  : Reconstruct Branch               : 
,08-30 16:54:21.491  4194  4240 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 16:54:21.507  4194  4194 I NSApplication: Starting up...
,08-30 16:54:21.552   875  2018 I ActivityManager: Start proc 4245:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-30 16:54:21.553   875  2018 I ActivityManager: Killing 3820:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 16:54:21.628  4245  4245 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 16:54:21.835   875  2028 I ActivityManager: Killing 3837:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 16:54:22.635   875  1516 D WifiService: setWifiEnabled: true pid=4030, uid=10000
,08-30 16:54:22.635   875  1516 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:54:22.647   875  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:54:22.656  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:22.657  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:22.657  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:22.657  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:22.660  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:22.660  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:22.660  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:22.661  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:22.699   875  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-30 16:54:22.700   875  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 16:54:22.701   875  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 16:54:22.703   875  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 16:54:22.703   875  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 16:54:22.704   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 16:54:22.704   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 16:54:22.720   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 16:54:22.720   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 16:54:22.722   373   873 D CommandListener: Setting iface cfg
,08-30 16:54:22.731   875  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '132 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 132 Failed to set address (No such device)'
08-30 16:54:22.732   875  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 16:54:22.732   875  1316 E native  : do suspend true
,08-30 16:54:22.746   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:54:22.767   875  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 16:54:22.768   875  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 16:54:24.125   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:54:24.158   875  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.06 rxSuccessRate=10.44 delta 1000 -> 994
,08-30 16:54:24.161   875  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 16:54:24.162   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:54:24.178   875  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 16:54:24.240   875  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 16:54:24.242  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 16:54:24.672  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 16:54:24.710  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:54:24.711  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 16:54:24.715   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:54:24.723   875  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:54:24.723   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:54:24.724   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 16:54:24.742   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:54:24.759   373   873 D CommandListener: Setting iface cfg
08-30 16:54:24.760   875  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 16:54:24.767   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 16:54:24.818   875  4271 D DhcpClient: Receive thread started
,08-30 16:54:24.899   875  1316 E native  : do suspend false
,08-30 16:54:24.909   875  1857 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 16:54:24.921   875  4271 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172622, domain null
,08-30 16:54:24.921   875  1857 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172622 seconds
,08-30 16:54:24.924   875  1857 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 16:54:24.936   875  4271 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 16:54:24.936   875  1857 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 16:54:24.940   373   873 D CommandListener: Setting iface cfg
,08-30 16:54:24.945   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 16:54:24.948   875  1316 E native  : do suspend true
,08-30 16:54:24.949   875  1857 D DhcpClient: Scheduling renewal in 86399s
,08-30 16:54:24.962   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 16:54:24.963   875  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 16:54:24.963   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 16:54:24.966   875  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 16:54:24.977   875  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:54:25.031   875  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 16:54:25.032   875  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 16:54:25.035   875  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 16:54:25.037   875  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 16:54:25.040   875  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 16:54:25.052   875  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 16:54:25.059   875  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 16:54:25.060   875  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-30 16:54:25.060   875  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 16:54:25.060   875  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 16:54:25.060   875  1318 D ConnectivityService:    accepting network in place of null
,08-30 16:54:25.062   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:54:25.065   875  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 16:54:25.076   875  4270 D NetlinkSocketObserver: NeighborEvent{elapsedMs=200792, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:54:25.123   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:54:25.159   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:54:25.161   875  4269 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-30 16:54:25.168   875  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 16:54:25.168   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:54:25.170   875  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-30 16:54:25.176   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:54:25.180  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:25.180  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:25.181  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:25.181  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:25.183  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:25.183  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 16:54:25.183  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.183  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:25.195  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 16:54:25.199  1733  1733 D SystemUpdateService: onCreate
,08-30 16:54:25.204  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:54:25.206  1733  4281 I SystemUpdateService: active receiver: enabled
,08-30 16:54:25.211  1733  4281 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:54:25.214  1733  4281 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 16:54:25.214  1733  4281 I SystemUpdateService: now status is 0 (complete)
08-30 16:54:25.214  1733  4281 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:54:25.214  1733  4281 I SystemUpdateService: file has been verified
,08-30 16:54:25.214  1733  4281 I SystemUpdateService: OTA package size = 12249756,
,08-30 16:54:25.218  1733  4281 I SystemUpdateService: showing system update notification
,08-30 16:54:25.227  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 16:54:25.230  1733  2314 I iu.UploadsManager: num queued entries: 0
08-30 16:54:25.230  1733  2314 I iu.UploadsManager: num updated entries: 0
,08-30 16:54:25.231  1733  2314 I iu.SyncManager: NEXT; no task
,08-30 16:54:25.233   875  4269 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:54:25 GMT], X-Android-Received-Millis=[1472568865232], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472568865202]}
,08-30 16:54:25.233   875  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-30 16:54:25.233   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 16:54:25.234   875  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 16:54:25.235   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 16:54:25.236  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:54:25.237  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:54:25.239  4166  4166 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:54:25.241  1733  1733 D SystemUpdateService: onDestroy
,08-30 16:54:25.241  1733  4284 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 16:54:25.241  1733  4284 W BaseAppContext: Using Auth Proxy for data requests.
08-30 16:54:25.242  1733  4284 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:54:25.243  4166  4166 D SprintDMHelper: simOperator: 
,08-30 16:54:25.244  4166  4166 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 16:54:25.249  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-30 16:54:25.250  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:25.274  1518  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 16:54:25.274  1518  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 16:54:25.274  1518  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:54:25.274  1518  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:54:25.286  4137  4137 I art     : Waiting for a blocking GC DisableMovingGc
,08-30 16:54:25.287  1733  4284 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-30 16:54:25.290  4137  4137 I art     : Starting a blocking GC DisableMovingGc
,08-30 16:54:25.381  4137  4290 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 16:54:25.642   875  2028 D WifiService: setWifiEnabled: false pid=4030, uid=10000
,08-30 16:54:25.642   875  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:54:25.677  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 16:54:25.687   875  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 16:54:25.687   875  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 16:54:25.688   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 16:54:25.689   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:54:25.706   875  1316 E native  : do suspend true
,08-30 16:54:25.716   875  1857 D DhcpClient: Clearing IP address
,08-30 16:54:25.716   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:54:25.720   373   873 D CommandListener: Setting iface cfg
08-30 16:54:25.722  1518  4295 V NativeCrypto: Read error: ssl=0x9a1bc000: I/O error during system call, Connection timed out
,08-30 16:54:25.723  1518  4295 V NativeCrypto: SSL shutdown failed: ssl=0x9a1bc000: I/O error during system call, Broken pipe
,08-30 16:54:25.725   875  1989 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-30 16:54:25.726   875  4269 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-30 16:54:25.728   875  4269 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-30 16:54:25.736   875  4271 D DhcpClient: Receive thread stopped
08-30 16:54:25.738   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 16:54:25.738   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 16:54:25.743   875  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 16:54:25.745   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:54:25.745   875  1316 E native  : do suspend true
08-30 16:54:25.749   875  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 16:54:25.749   875  4269 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-30 16:54:25.750   396   396 E Parcel  : Reading a NULL string not supported here.
,08-30 16:54:25.778   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:54:25.806   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 16:54:25.807   875  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 16:54:25.808   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 16:54:25.807   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-30 16:54:25.813   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:54:25.825  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:25.825  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:25.825  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.825  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:25.829  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:25.829  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:25.829  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.829  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:25.830   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:54:25.835  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 16:54:25.838  1733  1733 D SystemUpdateService: onCreate
,08-30 16:54:25.843  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 16:54:25.846  1733  4305 I SystemUpdateService: active receiver: enabled
,08-30 16:54:25.850  1733  4305 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:54:25.850   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:54:25.857  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:25.857  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:25.857  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 16:54:25.857  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:25.858  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:25.858  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:25.858  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:25.858  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:25.858   875  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 16:54:25.860  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-30 16:54:25.860  2091  2348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 16:54:25.868  1733  2314 I iu.UploadsManager: num queued entries: 0
,08-30 16:54:25.868  1733  2314 I iu.UploadsManager: num updated entries: 0
08-30 16:54:25.869  1733  4305 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-30 16:54:25.869  1733  4305 I SystemUpdateService: now status is 0 (complete)
08-30 16:54:25.869  1733  4305 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 16:54:25.869  1733  4305 I SystemUpdateService: file has been verified
,08-30 16:54:25.871  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 16:54:25.872  1733  4305 I SystemUpdateService: OTA package size = 12249756
,08-30 16:54:25.872  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 16:54:25.875  4166  4166 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:54:25.884  4166  4166 D SprintDMHelper: simOperator: 
,08-30 16:54:25.884  4166  4166 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:54:25.898   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-30 16:54:25.899   875  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 16:54:25.899   875  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 16:54:25.910  1733  2314 I iu.SyncManager: NEXT; no task
,08-30 16:54:25.916  1733  4305 I SystemUpdateService: showing system update notification
,08-30 16:54:25.919  4137  4309 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 16:54:25.958  1733  1733 D SystemUpdateService: onDestroy
,08-30 16:54:25.960   875  2001 I ActivityManager: Killing 2244:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 16:54:26.167   875  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 16:54:26.278  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:26.325  1518  4012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 16:54:26.325  1518  4012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 16:54:26.326  1518  4012 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 16:54:26.326  1518  4012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:54:26.366  3678  3678 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 16:54:26.367  3678  3678 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 16:54:26.368  3678  3678 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 16:54:28.703   875   892 I ActivityManager: Start proc 4314:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 16:54:28.831  4314  4314 D AdapterServiceConfig: Adding HeadsetService
,08-30 16:54:28.832  4314  4314 D AdapterServiceConfig: Adding A2dpService
,08-30 16:54:28.833  4314  4314 D AdapterServiceConfig: Adding HidService
,08-30 16:54:28.835  4314  4314 D AdapterServiceConfig: Adding HealthService
,08-30 16:54:28.837  4314  4314 D AdapterServiceConfig: Adding PanService
,08-30 16:54:28.839  4314  4314 D AdapterServiceConfig: Adding GattService
,08-30 16:54:28.840  4314  4314 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 16:54:28.861   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4554f28:true
,08-30 16:54:28.861  4314  4314 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 16:54:28.867  4314  4314 I bt_bluedroid: init
,08-30 16:54:28.868  4314  4326 I BluetoothAdapterState: Entering OffState
,08-30 16:54:28.875  4314  4327 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 16:54:28.875  4314  4327 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 16:54:28.875  4314  4327 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:54:28.876  4314  4327 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 16:54:28.879  4314  4314 I bt_bluedroid: get_profile_interface socket
,08-30 16:54:28.881  4314  4314 I bt_bluedroid: get_profile_interface sdp
,08-30 16:54:28.887  4314  4325 I bt_bluedroid: config_hci_snoop_log
,08-30 16:54:28.887  4314  4330 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 16:54:28.889   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 16:54:28.890  4314  4330 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:54:28.900  4314  4326 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 16:54:28.901  4314  4326 D BluetoothAdapterProperties: Setting state to 14
08-30 16:54:28.901  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-30 16:54:28.904  4314  4326 D BluetoothBondStateMachine: make
,08-30 16:54:28.908  4314  4331 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 16:54:28.912  4314  4326 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:54:28.914  4314  4314 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 16:54:28.918  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:28.919  4314  4314 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:54:28.920  4314  4314 D BtGatt.GattService: Received start request. Starting profile...
08-30 16:54:28.920  4314  4314 D BtGatt.GattService: start()
08-30 16:54:28.920  4314  4314 I bt_bluedroid: get_profile_interface gatt
,08-30 16:54:28.921  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:28.921  4314  4314 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:54:28.932  4314  4314 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:28.933  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:28.933  4314  4314 V BluetoothAdapterState: isBleTurningOn()=true
08-30 16:54:28.933  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:28.934  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 16:54:28.934  4314  4326 I bt_bluedroid: enable
08-30 16:54:28.936  4314  4327 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 16:54:28.937  4314  4327 I bt_hci  : start_up
,08-30 16:54:28.958  4314  4327 I bt_vendor: alloc value 0xb3a24189
08-30 16:54:28.958  4314  4327 I bt_vendor: init
08-30 16:54:28.958  4314  4327 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 16:54:28.959  4314  4327 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 16:54:29.066  4314  4327 D bt_hci  : start_up starting async portion
,08-30 16:54:29.067  4314  4334 I bt_hci  : event_finish_startup
08-30 16:54:29.068  4314  4334 I bt_hci_h4: hal_open
08-30 16:54:29.068  4314  4334 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 16:54:29.081  4314  4334 I bt_userial_vendor: device fd = 51 open
,08-30 16:54:29.107  4314  4334 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:54:29.139  4314  4334 D bt_hwcfg: Chipset BCM4354A2,
08-30 16:54:29.139  4314  4334 D bt_hwcfg: Target name = [BCM4354A2]
08-30 16:54:29.140  4314  4334 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 16:54:29.803  4314  4334 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,08-30 16:54:29.805  4314  4334 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 16:54:29.805  4314  4334 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 16:54:29.922  4314  4334 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:54:29.923  4314  4334 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 16:54:29.953  4314  4334 I bt_hwcfg: vendor lib fwcfg completed
,08-30 16:54:29.953  4314  4334 I bt_vendor: firmware callback
08-30 16:54:29.953  4314  4334 I bt_hci  : firmware_config_callback
,08-30 16:54:29.965  4314  4336 I bt_btu  : btu_task pending for preload complete event
,08-30 16:54:29.965  4314  4336 I bt_btu_task: Bluetooth chip preload is complete
,08-30 16:54:29.965  4314  4336 I bt_btu  : btu_task received preload complete event
,08-30 16:54:29.978  4314  4336 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 16:54:29.978  4314  4336 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:54:29.979  4314  4336 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:54:29.979  4314  4336 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 16:54:29.979  4314  4336 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:54:29.980  4314  4336 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 16:54:29.980  4314  4336 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:54:29.980  4314  4336 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 16:54:29.980  4314  4336 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:54:29.981  4314  4336 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 16:54:29.981  4314  4336 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 16:54:29.981  4314  4336 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:54:29.981  4314  4336 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:54:29.982  4314  4336 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:54:29.982  4314  4336 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:54:30.105  4314  4336 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a1d9d
08-30 16:54:30.105  4314  4336 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a1d9d 
,08-30 16:54:30.112  4314  4330 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 16:54:30.115  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 16:54:30.115  4314  4330 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:54:30.118  4314  4330 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:54:30.122  4314  4330 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:54:30.122  4314  4330 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:54:30.122  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:30.122  4314  4330 D bt_hci  : do_postload posting postload work item
08-30 16:54:30.123  4314  4334 I bt_hci  : event_postload
08-30 16:54:30.123  4314  4334 I bt_vendor: sco_config_cb
08-30 16:54:30.123  4314  4334 I bt_hci  : sco_config_callback postload finished.
08-30 16:54:30.126  4314  4330 D bt_bte_conf: Device ID record 1 : primary
,08-30 16:54:30.126  4314  4330 D bt_bte_conf:   vendorId            = 000f
08-30 16:54:30.127  4314  4330 D bt_bte_conf:   vendorIdSource      = 0001
08-30 16:54:30.127  4314  4330 D bt_bte_conf:   product             = 1200
08-30 16:54:30.127  4314  4330 D bt_bte_conf:   version             = 1436
08-30 16:54:30.127  4314  4330 D bt_bte_conf:   clientExecutableURL = 
08-30 16:54:30.127  4314  4330 D bt_bte_conf:   serviceDescription  = 
08-30 16:54:30.127  4314  4330 D bt_bte_conf:   documentationURL    = 
08-30 16:54:30.128  4314  4330 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 16:54:30.128  4314  4327 D bt_stack_manager: event_start_up_stack finished
08-30 16:54:30.130  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 16:54:30.131  4314  4326 D BluetoothAdapterProperties: Setting state to 15
,08-30 16:54:30.131  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 16:54:30.133  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:30.134  4314  4326 I BluetoothAdapterState: Entering BleOnState
08-30 16:54:30.135  4314  4326 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 16:54:30.136  4314  4326 D BluetoothAdapterProperties: Setting state to 11
08-30 16:54:30.136  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 16:54:30.136  4314  4334 I bt_vendor: low_power_mode_cb
,08-30 16:54:30.154  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:30.156  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:30.157  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:30.158  4314  4314 D HeadsetService: Received start request. Starting profile...
,08-30 16:54:30.160  4314  4314 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 16:54:30.161  4314  4314 D HeadsetStateMachine: make
,08-30 16:54:30.168  4314  4314 D HeadsetStateMachine: max_hf_connections = 1
,08-30 16:54:30.168  4314  4314 I bt_bluedroid: get_profile_interface handsfree
08-30 16:54:30.169  4314  4326 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:54:30.169  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 16:54:30.170  4314  4330 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-30 16:54:30.174  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:30.175  4314  4314 D A2dpService: Received start request. Starting profile...
,08-30 16:54:30.176  4314  4314 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:54:30.176  4314  4314 I bt_bluedroid: get_profile_interface avrcp
,08-30 16:54:30.181  4314  4314 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 16:54:30.181  4314  4314 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:54:30.182  4314  4314 D A2dpStateMachine: make
,08-30 16:54:30.182  4314  4314 I bt_bluedroid: get_profile_interface a2dp
,08-30 16:54:30.183  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 16:54:30.187  4314  4345 D A2dpStateMachine: Enter Disconnected: -2
,08-30 16:54:30.188  4314  4314 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 16:54:30.189  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:30.191  4086  4086 D BluetoothInputDevice: Proxy object connected
,08-30 16:54:30.191  4314  4314 D HidService: Received start request. Starting profile...
08-30 16:54:30.191  4314  4314 I bt_bluedroid: get_profile_interface hidhost
,08-30 16:54:30.191  4314  4330 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39833e5
,08-30 16:54:30.191  4086  4086 D HidProfile: Bluetooth service connected
08-30 16:54:30.191  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 16:54:30.191  4314  4314 D HidService: setHidService(): set to: null,
,08-30 16:54:30.195  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:54:30.195  4314  4314 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:54:30.196  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:30.196  4314  4314 D HealthService: Received start request. Starting profile...
,08-30 16:54:30.198  4314  4314 I bt_bluedroid: get_profile_interface health
,08-30 16:54:30.198  4314  4314 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 16:54:30.199  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:30.200  4314  4314 D PanService: Received start request. Starting profile...
,08-30 16:54:30.201  4314  4314 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:54:30.201  4314  4314 I bt_bluedroid: get_profile_interface pan
,08-30 16:54:30.201  4086  4086 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:54:30.201  4314  4330 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:54:30.201  4086  4086 D PanProfile: Bluetooth service connected
,08-30 16:54:30.204  4314  4314 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:30.205  4314  4314 D BluetoothMapService: Received start request. Starting profile...
08-30 16:54:30.205  4314  4314 D BluetoothMapService: start()
,08-30 16:54:30.205  4086  4086 D BluetoothMap: Proxy object connected
08-30 16:54:30.206  4086  4086 D MapProfile: Bluetooth service connected
08-30 16:54:30.206  4086  4086 D BluetoothMap: getConnectedDevices()
08-30 16:54:30.206  4086  4086 D BluetoothMap: Bluetooth is Not enabled
08-30 16:54:30.207  4314  4314 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 16:54:30.208  4314  4314 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 16:54:30.208  4314  4314 D BluetoothMapAppObserver: createReceiver()
,08-30 16:54:30.209  4314  4314 D BluetoothMapAppObserver: initObservers()
,08-30 16:54:30.209  4314  4314 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 16:54:30.217  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:30.217  4314  4314 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:30.217  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:30.217  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:30.219  4314  4343 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:30.219  4314  4314 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isTurningOn()=true
,08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 16:54:30.220  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:30.220  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 16:54:30.220  4314  4326 D BluetoothAdapterProperties: ScanMode =  20
,08-30 16:54:30.220  4314  4326 D BluetoothAdapterProperties: State =  11
08-30 16:54:30.221  4314  4326 D BluetoothAdapterProperties: Setting state to 12,
08-30 16:54:30.221  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 16:54:30.221  1370  1383 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:54:30.222  4314  4326 I BluetoothAdapterState: Entering OnState
,08-30 16:54:30.224  4314  4330 D BluetoothAdapterProperties: Scan Mode:21
,08-30 16:54:30.224  4314  4330 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:54:30.225  4086  4096 D BluetoothInputDevice: onBluetoothStateChange: up=true,
,08-30 16:54:30.225  1370  4289 D BluetoothPan: onBluetoothStateChange on: true
,08-30 16:54:30.227  4030  4030 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:30.227  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:30.229  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 16:54:30.229  4086  4098 D BluetoothPan: onBluetoothStateChange on: true
,08-30 16:54:30.229  1370  1370 D PanProfile: Bluetooth service connected
08-30 16:54:30.229  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:30.229  1964  1982 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:30.230  1370  1383 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:30.232  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:30.233  1370  1370 D BluetoothMap: Proxy object connected
,08-30 16:54:30.233  4086  4096 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:54:30.233  1370  1370 D MapProfile: Bluetooth service connected
08-30 16:54:30.233  1370  1370 D BluetoothMap: getConnectedDevices()
08-30 16:54:30.233  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:30.235   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:30.235   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:54:30.235   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:54:30.236  4086  4098 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:54:30.236   875   875 D BluetoothA2dp: Proxy object connected
08-30 16:54:30.236   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:30.236  1370  4289 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:54:30.237  4314  4314 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 16:54:30.237  1370  1388 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:54:30.238  4314  4314 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 16:54:30.239  1370  1370 D BluetoothInputDevice: Proxy object connected
08-30 16:54:30.239  1370  1370 D HidProfile: Bluetooth service connected
,08-30 16:54:30.240  1370  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:54:30.240  4314  4314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:54:30.241  1370  1370 D BluetoothA2dp: Proxy object connected
08-30 16:54:30.242  4314  4314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:54:30.243   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 16:54:30.246  4314  4314 D ObexServerSockets: Succeed to create listening sockets 
08-30 16:54:30.246  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:30.246  4314  4314 D ObexServerSockets0: startAccept()
,08-30 16:54:30.246  4314  4314 D ObexServerSockets0: prepareForNewConnect()
08-30 16:54:30.246  4086  4086 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 16:54:30.247  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:30.249  4314  4314 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-30 16:54:30.249  4314  4314 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 16:54:30.249  4314  4314 D BluetoothMapService: onReceive
08-30 16:54:30.249  4314  4314 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:54:30.249  4314  4314 D BluetoothMapService: STATE_ON
08-30 16:54:30.250  4314  4353 D ObexServerSockets0: Accepting socket connection...
08-30 16:54:30.250  4314  4352 D ObexServerSockets0: Accepting socket connection...
,08-30 16:54:30.252  4086  4086 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 16:54:30.258  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:54:30.260  4086  4086 D BluetoothA2dp: Proxy object connected
,08-30 16:54:30.263  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:54:30.270  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:54:30.272  1370  1370 D BluetoothPbap: Proxy object connected
,08-30 16:54:30.272  1370  1370 D PbapServerProfile: Bluetooth service connected
08-30 16:54:30.272  4086  4086 D BluetoothPbap: Proxy object connected
08-30 16:54:30.273  4086  4086 D PbapServerProfile: Bluetooth service connected
,08-30 16:54:30.278  4314  4314 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:54:30.278  4314  4314 D ObexServerSockets0: prepareForNewConnect()
,08-30 16:54:30.280  4314  4357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:54:30.291  4314  4361 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:54:30.292  4314  4361 I BtOppRfcommListener: Accept thread started.
,08-30 16:54:30.332  1964  2126 D BluetoothHeadset: Proxy object connected
,08-30 16:54:30.332   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:54:30.332  1370  1383 D BluetoothHeadset: Proxy object connected
08-30 16:54:30.332   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:54:30.333   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:54:30.332  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-30 16:54:30.334   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:54:30.336   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:54:30.337   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:54:30.337  1370  1387 D BluetoothHeadset: Proxy object connected
08-30 16:54:30.337  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-30 16:54:30.355  4086  4096 D BluetoothHeadset: Proxy object connected
,08-30 16:54:30.356  4086  4086 D HeadsetProfile: Bluetooth service connected
,08-30 16:54:31.665  4314  4326 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 16:54:31.665  4314  4326 D BluetoothAdapterProperties: Setting state to 13
,08-30 16:54:31.665  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 16:54:31.667  4314  4326 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 16:54:31.672  4314  4326 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:54:31.682  4314  4314 D BluetoothMapService: onReceive
,08-30 16:54:31.682  4314  4314 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:54:31.682  4314  4314 D BluetoothMapService: STATE_TURNING_OFF
08-30 16:54:31.682  4314  4314 D BluetoothMapService: MAP Service closeService in
08-30 16:54:31.682  4314  4314 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 16:54:31.683  4314  4314 D ObexServerSockets0: shutdown(block = true)
08-30 16:54:31.684  4314  4314 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 16:54:31.684  4314  4314 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 16:54:31.684  4314  4353 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 16:54:31.685  4314  4339 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 16:54:31.686  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:31.686  4314  4352 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:31.686  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:31.687  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:31.687  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:31.687  4314  4314 I BtOppRfcommListener: stopping Accept Thread
,08-30 16:54:31.688  4314  4361 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 16:54:31.691  4314  4361 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 16:54:31.693  4314  4330 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:54:31.694  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 16:54:31.698  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:31.698  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:31.699  4030  4030 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 16:54:31.699  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:31.700  4314  4314 D HeadsetService: Received stop request...Stopping profile...
08-30 16:54:31.700  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:54:31.701  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:31.702  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:31.704  1964  1982 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:31.704   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:31.705  1370  1388 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:31.705   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:31.705   875   875 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:31.706  4314  4314 D A2dpService: Received stop request...Stopping profile...
08-30 16:54:31.706  4086  4098 D BluetoothHeadset: Proxy object disconnected
08-30 16:54:31.706  4314  4345 D A2dpStateMachine: Exit Disconnected: -1
,08-30 16:54:31.710   875   875 D BluetoothA2dp: Proxy object disconnected
,08-30 16:54:31.711  4314  4314 D HidService: Received stop request...Stopping profile...
,08-30 16:54:31.711  4314  4314 D HidService: Stopping Bluetooth HidService
08-30 16:54:31.712  4086  4086 D DockEventReceiver: finishStartingService: stopping service
08-30 16:54:31.713  4086  4086 D HeadsetProfile: Bluetooth service disconnected
08-30 16:54:31.713  4086  4086 D BluetoothA2dp: Proxy object disconnected
08-30 16:54:31.713  4314  4314 D HealthService: Received stop request...Stopping profile...
08-30 16:54:31.714  1370  1370 D HeadsetProfile: Bluetooth service disconnected
,08-30 16:54:31.714  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-30 16:54:31.715  4086  4086 D BluetoothInputDevice: Proxy object disconnected
08-30 16:54:31.715  4086  4086 D HidProfile: Bluetooth service disconnected
08-30 16:54:31.715  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-30 16:54:31.715  1370  1370 D HidProfile: Bluetooth service disconnected,
08-30 16:54:31.716  4314  4314 D PanService: Received stop request...Stopping profile...
08-30 16:54:31.717  4086  4086 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:54:31.717  4086  4086 D PanProfile: Bluetooth service disconnected
08-30 16:54:31.717  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 16:54:31.717  1370  1370 D PanProfile: Bluetooth service disconnected
,08-30 16:54:31.717  4314  4314 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 16:54:31.717  4314  4314 D BluetoothMapService: stop()
08-30 16:54:31.718  4314  4314 D BluetoothMapAppObserver: deinitObservers()
,08-30 16:54:31.718  4314  4314 D BluetoothMapAppObserver: removeReceiver()
08-30 16:54:31.720  4314  4314 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:54:31.720  1370  1370 D BluetoothMap: Proxy object disconnected
,08-30 16:54:31.720  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:31.720  1370  1370 D MapProfile: Bluetooth service disconnected
,08-30 16:54:31.719  4086  4086 D BluetoothMap: Proxy object disconnected
08-30 16:54:31.720  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:31.720  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 16:54:31.720  4086  4086 D MapProfile: Bluetooth service disconnected
08-30 16:54:31.721  4314  4314 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 16:54:31.721  4314  4314 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 16:54:31.721  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 16:54:31.722  4314  4336 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:31.722  4314  4336 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:31.722  4314  4336 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:31.722  4314  4330 E bt_btif : btif_hf_upstreams_evt: Invalid index 17,
,08-30 16:54:31.723  4314  4314 V BluetoothAdapterState: isTurningOff()=true
,08-30 16:54:31.723  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:31.723  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:31.725  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:31.726  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 16:54:31.726  4314  4336 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:31.726  4314  4336 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 16:54:31.726  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:54:31.726  4314  4336 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:54:31.726  4314  4336 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 16:54:31.726  4314  4336 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 16:54:31.726  4314  4336 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 16:54:31.727  4314  4314 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:31.727  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:31.727  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:31.727  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:31.727  4314  4314 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 16:54:31.728  4314  4330 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 16:54:31.727  4314  4314 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 16:54:31.728  4314  4314 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:31.728  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:31.728  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:31.728  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:31.728  4314  4314 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 16:54:31.728  4314  4330 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 16:54:31.729  4314  4314 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 16:54:31.729  4314  4314 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:31.729  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:31.729  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:31.729  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:31.730  4314  4314 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 16:54:31.730  4314  4314 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 16:54:31.731  4314  4314 D BluetoothMapService: MAP Service closeService in
08-30 16:54:31.731  4314  4314 V BluetoothAdapterState: isTurningOff()=true
08-30 16:54:31.731  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:31.731  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:31.731  4314  4314 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:31.732  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 16:54:31.732  4314  4326 D BluetoothAdapterProperties: Setting state to 15
08-30 16:54:31.732  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-30 16:54:31.733  4314  4326 I BluetoothAdapterState: Entering BleOnState
08-30 16:54:31.733  1370  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:54:31.734  4086  4096 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:54:31.735  1370  1387 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:54:31.734  4314  4314 D BluetoothMapService: cleanup()
08-30 16:54:31.735  4314  4314 D BluetoothMapService: MAP Service closeService in
08-30 16:54:31.735  4086  4098 D BluetoothPan: onBluetoothStateChange on: false
08-30 16:54:31.736  4086  4096 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:31.737  1964  2126 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:54:31.737  1370  4289 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:54:31.738  4086  4098 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 16:54:31.738   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:31.738   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:54:31.737  4086  4086 D BluetoothPbap: Proxy object disconnected
,08-30 16:54:31.738  4086  4086 D PbapServerProfile: Bluetooth service disconnected
,08-30 16:54:31.741   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:31.741  4086  4096 D BluetoothMap: onBluetoothStateChange: up=false
08-30 16:54:31.742   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 16:54:31.742  4086  4098 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 16:54:31.743  1370  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 16:54:31.743  1370  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 16:54:31.746  1370  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 16:54:31.747  4314  4326 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 16:54:31.747  4314  4326 D BluetoothAdapterProperties: Setting state to 16
,08-30 16:54:31.747  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 16:54:31.748  4314  4326 D BluetoothAdapterProperties: onBleDisable
08-30 16:54:31.748  4314  4326 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:54:31.748  4314  4327 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 16:54:31.749  4314  4336 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 16:54:31.749  4314  4336 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 16:54:31.751  4314  4330 D BluetoothAdapterProperties: Scan Mode:20
08-30 16:54:31.753  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:31.754  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:31.754  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 16:54:31.756  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:31.759  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:31.761  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:54:31.761  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:54:31.950  4314  4330 I bt_hci  : shut_down
,08-30 16:54:31.951  4314  4334 D bt_hwcfg: hw_epilog_process
08-30 16:54:31.953  4314  4334 I bt_vendor: low_power_mode_cb
,08-30 16:54:31.971  4314  4334 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 16:54:31.972  4314  4334 I bt_vendor: epilog_cb
,08-30 16:54:31.972  4314  4334 I bt_hci  : epilog_finished_callback
,08-30 16:54:31.983  4314  4330 I bt_hci_h4: hal_close
,08-30 16:54:31.984  4314  4330 I bt_userial_vendor: device fd = 51 close
,08-30 16:54:32.111  4314  4327 D bt_stack_manager: event_shut_down_stack finished.
,08-30 16:54:32.112  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 16:54:32.117  4314  4326 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-30 16:54:32.118  4314  4314 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 16:54:32.119  4314  4314 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 16:54:32.119  4314  4314 D BtGatt.GattService: stop()
08-30 16:54:32.120  4314  4314 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 16:54:32.124  4314  4314 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:32.125  4314  4314 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:32.125  4314  4314 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:32.125  4314  4314 V BluetoothAdapterState: isBleTurningOff()=true
,08-30 16:54:32.126  4314  4326 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 16:54:32.128  4314  4326 D BluetoothAdapterProperties: Setting state to 10
,08-30 16:54:32.128  4314  4326 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 16:54:32.130  4314  4326 I BluetoothAdapterState: Entering OffState
,08-30 16:54:32.132   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 16:54:32.149  4314  4314 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 16:54:32.150  4314  4314 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-30 16:54:32.150  4314  4327 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-30 16:54:32.153  4314  4327 D bt_stack_manager: event_clean_up_stack finished.
,08-30 16:54:32.153  4314  4314 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 16:54:32.156  4314  4314 I art     : System.exit called, status: 0
08-30 16:54:32.156  4314  4314 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 16:54:32.224   875  2021 I ActivityManager: Process com.android.bluetooth (pid 4314) has died
,08-30 16:54:33.067   875  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-30 16:54:34.661  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:34.661  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:37.669  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:54:37.670  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a934dae added. We now have 6 listener(s)
08-30 16:54:37.670  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:37.674  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:37.674  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f7474f added. We now have 7 listener(s)
,08-30 16:54:37.674  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:37.676  4030  4076 I System.out: IsBluetoothEnabled
,08-30 16:54:37.688  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:37.739   875   892 I ActivityManager: Start proc 4371:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 16:54:37.865  4371  4371 D AdapterServiceConfig: Adding HeadsetService
,08-30 16:54:37.865  4371  4371 D AdapterServiceConfig: Adding A2dpService
08-30 16:54:37.865  4371  4371 D AdapterServiceConfig: Adding HidService
08-30 16:54:37.866  4371  4371 D AdapterServiceConfig: Adding HealthService
08-30 16:54:37.866  4371  4371 D AdapterServiceConfig: Adding PanService
,08-30 16:54:37.866  4371  4371 D AdapterServiceConfig: Adding GattService
08-30 16:54:37.866  4371  4371 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 16:54:37.876   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0263e8:true
,08-30 16:54:37.876  4371  4371 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 16:54:37.880  4371  4371 I bt_bluedroid: init
,08-30 16:54:37.880  4371  4385 I BluetoothAdapterState: Entering OffState
,08-30 16:54:37.882  4371  4386 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 16:54:37.882  4371  4386 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 16:54:37.882  4371  4386 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 16:54:37.882  4371  4386 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 16:54:37.882  4371  4371 I bt_bluedroid: get_profile_interface socket
,08-30 16:54:37.884  4371  4371 I bt_bluedroid: get_profile_interface sdp
,08-30 16:54:37.886  4371  4382 I bt_bluedroid: config_hci_snoop_log
,08-30 16:54:37.887   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-30 16:54:37.887  4371  4389 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:54:37.890  4371  4389 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:54:37.892  4371  4385 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 16:54:37.892  4371  4385 D BluetoothAdapterProperties: Setting state to 14
08-30 16:54:37.892  4371  4385 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 16:54:37.893  4371  4385 D BluetoothBondStateMachine: make,
,08-30 16:54:37.895  4371  4390 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 16:54:37.898  4371  4385 I BluetoothAdapterState: Entering PendingCommandState
,08-30 16:54:37.899  4371  4371 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 16:54:37.900  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
,08-30 16:54:37.901  4371  4371 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 16:54:37.901  4371  4371 D BtGatt.GattService: Received start request. Starting profile...
08-30 16:54:37.902  4371  4371 D BtGatt.GattService: start()
,08-30 16:54:37.902  4371  4371 I bt_bluedroid: get_profile_interface gatt
08-30 16:54:37.902  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:37.902  4371  4371 D BtGatt.AdvertiseManager: advertise manager created
,08-30 16:54:37.906  4371  4371 V BluetoothAdapterState: isTurningOff()=false
,08-30 16:54:37.906  4371  4371 V BluetoothAdapterState: isTurningOn()=false
08-30 16:54:37.906  4371  4371 V BluetoothAdapterState: isBleTurningOn()=true
08-30 16:54:37.906  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:37.907  4371  4385 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 16:54:37.907  4371  4385 I bt_bluedroid: enable
,08-30 16:54:37.907  4371  4386 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 16:54:37.907  4371  4386 I bt_hci  : start_up
,08-30 16:54:37.911  4371  4386 I bt_vendor: alloc value 0xb3a24189
,08-30 16:54:37.911  4371  4386 I bt_vendor: init
08-30 16:54:37.911  4371  4386 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 16:54:37.911  4371  4386 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 16:54:38.020  4371  4386 D bt_hci  : start_up starting async portion
,08-30 16:54:38.020  4371  4393 I bt_hci  : event_finish_startup
08-30 16:54:38.021  4371  4393 I bt_hci_h4: hal_open
08-30 16:54:38.021  4371  4393 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 16:54:38.031  4371  4393 I bt_userial_vendor: device fd = 51 open
,08-30 16:54:38.060  4371  4393 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:54:38.092  4371  4393 D bt_hwcfg: Chipset BCM4354A2
,08-30 16:54:38.093  4371  4393 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 16:54:38.093  4371  4393 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 16:54:38.749  4371  4393 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 16:54:38.751  4371  4393 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 16:54:38.751  4371  4393 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 16:54:38.868  4371  4393 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 16:54:38.869  4371  4393 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 16:54:38.899  4371  4393 I bt_hwcfg: vendor lib fwcfg completed
,08-30 16:54:38.899  4371  4393 I bt_vendor: firmware callback
08-30 16:54:38.900  4371  4393 I bt_hci  : firmware_config_callback
,08-30 16:54:38.911  4371  4395 I bt_btu  : btu_task pending for preload complete event
,08-30 16:54:38.911  4371  4395 I bt_btu_task: Bluetooth chip preload is complete
08-30 16:54:38.911  4371  4395 I bt_btu  : btu_task received preload complete event
,08-30 16:54:38.923  4371  4395 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 16:54:38.924  4371  4395 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 16:54:38.924  4371  4395 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 16:54:38.924  4371  4395 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 16:54:38.925  4371  4395 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 16:54:38.925  4371  4395 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 16:54:38.925  4371  4395 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 16:54:38.925  4371  4395 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 16:54:38.926  4371  4395 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 16:54:38.926  4371  4395 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 16:54:38.926  4371  4395 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 16:54:38.926  4371  4395 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 16:54:38.927  4371  4395 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 16:54:38.927  4371  4395 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 16:54:38.927  4371  4395 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 16:54:39.061  4371  4395 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a1d9d
,08-30 16:54:39.061  4371  4395 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a1d9d 
,08-30 16:54:39.074  4371  4389 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-30 16:54:39.076  4371  4389 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 16:54:39.077  4371  4389 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 16:54:39.080  4371  4389 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 16:54:39.083  4371  4389 D BluetoothAdapterProperties: Scan Mode:20
,08-30 16:54:39.083  4371  4389 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:54:39.084  4371  4389 D bt_hci  : do_postload posting postload work item
,08-30 16:54:39.085  4371  4393 I bt_hci  : event_postload
08-30 16:54:39.085  4371  4393 I bt_vendor: sco_config_cb
,08-30 16:54:39.086  4371  4393 I bt_hci  : sco_config_callback postload finished.
,08-30 16:54:39.089  4371  4389 D bt_bte_conf: Device ID record 1 : primary
08-30 16:54:39.089  4371  4389 D bt_bte_conf:   vendorId            = 000f
,08-30 16:54:39.090  4371  4389 D bt_bte_conf:   vendorIdSource      = 0001
08-30 16:54:39.090  4371  4389 D bt_bte_conf:   product             = 1200
,08-30 16:54:39.090  4371  4389 D bt_bte_conf:   version             = 1436
08-30 16:54:39.090  4371  4389 D bt_bte_conf:   clientExecutableURL = 
08-30 16:54:39.091  4371  4389 D bt_bte_conf:   serviceDescription  = 
08-30 16:54:39.091  4371  4389 D bt_bte_conf:   documentationURL    = 
08-30 16:54:39.091  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:39.091  4371  4389 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 16:54:39.092  4371  4386 D bt_stack_manager: event_start_up_stack finished
08-30 16:54:39.093  4371  4385 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 16:54:39.095  4371  4385 D BluetoothAdapterProperties: Setting state to 15
08-30 16:54:39.095  4371  4385 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 16:54:39.097  4371  4385 I BluetoothAdapterState: Entering BleOnState
08-30 16:54:39.101  4371  4393 I bt_vendor: low_power_mode_cb
,08-30 16:54:39.104  4371  4385 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-30 16:54:39.106  4371  4385 D BluetoothAdapterProperties: Setting state to 11
08-30 16:54:39.106  4371  4385 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 16:54:39.112  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:39.117  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:39.118  4371  4371 D HeadsetService: Received start request. Starting profile...
08-30 16:54:39.121  4371  4371 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 16:54:39.122  4371  4371 D HeadsetStateMachine: make
08-30 16:54:39.129  4371  4385 I BluetoothAdapterState: Entering PendingCommandState
08-30 16:54:39.133  4371  4371 D HeadsetStateMachine: max_hf_connections = 1
08-30 16:54:39.133  4371  4371 I bt_bluedroid: get_profile_interface handsfree
08-30 16:54:39.133  4371  4389 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 16:54:39.133  4371  4389 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-30 16:54:39.137  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:39.138  4371  4371 D A2dpService: Received start request. Starting profile...
08-30 16:54:39.138  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 16:54:39.139  4371  4371 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 16:54:39.139  4371  4371 I bt_bluedroid: get_profile_interface avrcp
08-30 16:54:39.146  4371  4371 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 16:54:39.146  4371  4371 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 16:54:39.146  4371  4371 D A2dpStateMachine: make
08-30 16:54:39.148  4371  4371 I bt_bluedroid: get_profile_interface a2dp
08-30 16:54:39.149  4371  4389 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-30 16:54:39.150  4371  4404 D A2dpStateMachine: Enter Disconnected: -2
08-30 16:54:39.151  4371  4371 I BluetoothHidServiceJni: classInitNative: succeeds
08-30 16:54:39.152  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:39.153  4371  4371 D HidService: Received start request. Starting profile...
08-30 16:54:39.153  4371  4371 I bt_bluedroid: get_profile_interface hidhost
08-30 16:54:39.153  4371  4371 D HidService: setHidService(): set to: null
08-30 16:54:39.153  4371  4389 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39833e5
08-30 16:54:39.153  4371  4389 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 16:54:39.154  4371  4371 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 16:54:39.154  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:39.155  4371  4371 D HealthService: Received start request. Starting profile...
08-30 16:54:39.158  4371  4371 I bt_bluedroid: get_profile_interface health
08-30 16:54:39.158  4371  4371 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 16:54:39.159  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:39.160  4371  4371 D PanService: Received start request. Starting profile...
08-30 16:54:39.160  4371  4371 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 16:54:39.160  4371  4371 I bt_bluedroid: get_profile_interface pan
08-30 16:54:39.160  4371  4389 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-30 16:54:39.163  4371  4371 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:39.164  4371  4371 D BluetoothMapService: Received start request. Starting profile...
08-30 16:54:39.164  4371  4371 D BluetoothMapService: start()
08-30 16:54:39.166  4371  4371 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-30 16:54:39.167  4371  4371 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 16:54:39.167  4371  4371 D BluetoothMapAppObserver: createReceiver()
08-30 16:54:39.168  4371  4371 D BluetoothMapAppObserver: initObservers()
08-30 16:54:39.168  4371  4371 D BluetoothMapAppObserver: getEnabledAccountItems()
08-30 16:54:39.177  4371  4371 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:39.177  4371  4371 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:39.177  4371  4371 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:39.177  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:39.180  4371  4402 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:39.180  4371  4371 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isTurningOff()=false
08-30 16:54:39.181  4371  4371 V BluetoothAdapterState: isTurningOn()=true
08-30 16:54:39.182  4371  4371 V BluetoothAdapterState: isBleTurningOn()=false
08-30 16:54:39.182  4371  4371 V BluetoothAdapterState: isBleTurningOff()=false
08-30 16:54:39.182  4371  4385 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 16:54:39.182  4371  4385 D BluetoothAdapterProperties: ScanMode =  20
08-30 16:54:39.182  4371  4385 D BluetoothAdapterProperties: State =  11
08-30 16:54:39.183  4371  4385 D BluetoothAdapterProperties: Setting state to 12
08-30 16:54:39.183  4371  4385 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 16:54:39.184  1370  1383 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 16:54:39.184  4371  4385 I BluetoothAdapterState: Entering OnState
08-30 16:54:39.185  4371  4389 D BluetoothAdapterProperties: Scan Mode:21
08-30 16:54:39.185  4371  4389 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:39.189  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:39.191  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:39.193  4086  4098 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 16:54:39.195  4371  4371 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 16:54:39.196  4371  4371 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 16:54:39.198  4371  4371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:54:39.200  4371  4371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 16:54:39.202  1370  1388 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:54:39.203  4371  4371 D ObexServerSockets: Succeed to create listening sockets 
08-30 16:54:39.204  4371  4371 D ObexServerSockets0: startAccept()
08-30 16:54:39.204  4371  4371 D ObexServerSockets0: prepareForNewConnect()
08-30 16:54:39.206  4371  4371 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 16:54:39.206  4371  4371 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 16:54:39.208  4086  4096 D BluetoothPan: onBluetoothStateChange on: true
08-30 16:54:39.209  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:54:39.209  1370  1370 D PanProfile: Bluetooth service connected
08-30 16:54:39.210  4371  4409 D ObexServerSockets0: Accepting socket connection...
08-30 16:54:39.210  4371  4410 D ObexServerSockets0: Accepting socket connection...
08-30 16:54:39.210  4086  4098 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:54:39.211  1964  1978 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 16:54:39.211  4086  4086 D BluetoothInputDevice: Proxy object connected
08-30 16:54:39.211  4086  4086 D HidProfile: Bluetooth service connected
08-30 16:54:39.212  1370  1387 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 16:54:39.215  4086  4096 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 16:54:39.215  4086  4086 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 16:54:39.215  4086  4086 D PanProfile: Bluetooth service connected
08-30 16:54:39.215  1370  1370 D BluetoothMap: Proxy object connected
08-30 16:54:39.216  1370  1370 D MapProfile: Bluetooth service connected
08-30 16:54:39.216  1370  1370 D BluetoothMap: getConnectedDevices()
08-30 16:54:39.217   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:39.217   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 16:54:39.218   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:39.219  4086  4098 D BluetoothMap: onBluetoothStateChange: up=true
08-30 16:54:39.219   875   875 D BluetoothA2dp: Proxy object connected
,08-30 16:54:39.221   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:39.221  4086  4096 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:54:39.222  4086  4086 D BluetoothMap: Proxy object connected
08-30 16:54:39.222  4086  4086 D MapProfile: Bluetooth service connected
08-30 16:54:39.222  4086  4086 D BluetoothMap: getConnectedDevices()
,08-30 16:54:39.223  1370  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 16:54:39.223  1370  4289 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 16:54:39.225  1370  1370 D BluetoothInputDevice: Proxy object connected
08-30 16:54:39.225  1370  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 16:54:39.225  1370  1370 D HidProfile: Bluetooth service connected
08-30 16:54:39.226  4086  4086 D BluetoothA2dp: Proxy object connected
,08-30 16:54:39.227  1370  1370 D BluetoothA2dp: Proxy object connected
,08-30 16:54:39.230   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 16:54:39.231  4371  4371 D BluetoothMapService: onReceive
,08-30 16:54:39.231  4371  4371 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 16:54:39.231  4371  4371 D BluetoothMapService: STATE_ON
,08-30 16:54:39.232  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:39.236  4086  4086 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 16:54:39.242  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 16:54:39.246  4086  4086 D DockEventReceiver: finishStartingService: stopping service
,08-30 16:54:39.252  4086  4086 D BluetoothPbap: Proxy object connected
,08-30 16:54:39.252  4086  4086 D PbapServerProfile: Bluetooth service connected
,08-30 16:54:39.255  1370  1370 D BluetoothPbap: Proxy object connected
,08-30 16:54:39.255  1370  1370 D PbapServerProfile: Bluetooth service connected
,08-30 16:54:39.263  4371  4371 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 16:54:39.263  4371  4371 D ObexServerSockets0: prepareForNewConnect()
08-30 16:54:39.263  4371  4416 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:54:39.300  4371  4420 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 16:54:39.305  4371  4420 I BtOppRfcommListener: Accept thread started.
,08-30 16:54:39.312  1964  2158 D BluetoothHeadset: Proxy object connected
08-30 16:54:39.312   875   875 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.312  1964  1982 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.312  1370  1383 D BluetoothHeadset: Proxy object connected
08-30 16:54:39.313  1370  1370 D HeadsetProfile: Bluetooth service connected
08-30 16:54:39.313   875   875 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.313   875   875 D BluetoothHeadset: Proxy object connected
08-30 16:54:39.313  4086  4411 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.316  4086  4086 D HeadsetProfile: Bluetooth service connected
,08-30 16:54:39.318   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.319   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.321   875   892 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.324  1370  4289 D BluetoothHeadset: Proxy object connected
,08-30 16:54:39.324  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:39.711  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:39.717  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:39.721  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 16:54:39.722  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1d9edc added. We now have 8 listener(s)
08-30 16:54:39.722  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:39.727   875  1992 D WifiService: setWifiEnabled: false pid=4030, uid=10000
,08-30 16:54:39.728   875  1992 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:54:39.740  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:39.742   875   885 D WifiService: setWifiEnabled: true pid=4030, uid=10000
,08-30 16:54:39.742   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 16:54:39.756   875  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:39.773  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:39.780  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:39.788   875  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-30 16:54:39.789   875  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-30 16:54:39.790   875  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 16:54:39.791   875  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 16:54:39.791   875  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 16:54:39.791   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 16:54:39.791   875  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 16:54:39.806   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 16:54:39.806   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:54:39.808   373   873 D CommandListener: Setting iface cfg
,08-30 16:54:39.857   875  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,08-30 16:54:39.858   875  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 16:54:39.863   875  1316 E native  : do suspend true
,08-30 16:54:39.879   875  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 16:54:39.880   875  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 16:54:39.897   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:40.766  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:40.774  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:40.786  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 16:54:40.788  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 16:54:40.794  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a7a2e6d Bundle[{}]
,08-30 16:54:40.795  4030  4076 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 16:54:40.795  4030  4076 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 16:54:40.796  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 16:54:40.796  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 16:54:40.797  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 16:54:40.798  4030  4076 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 16:54:40.802  4030  4076 I System.out: Running OutgoingSocketThread
,08-30 16:54:40.804  4030  4427 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 463)
08-30 16:54:40.807  4030  4427 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47839
08-30 16:54:40.807  4030  4427 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 16:54:41.320   875  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 16:54:41.459   875  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=11.88 delta 1000 -> 994
,08-30 16:54:41.462   875  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 16:54:41.462   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 16:54:41.481   875  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 16:54:41.527   875  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 16:54:41.528  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 16:54:41.805  4030  4076 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 464)
08-30 16:54:41.805  4030  4076 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 464)
,08-30 16:54:41.815  4030  4076 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 469)
,08-30 16:54:41.817  4030  4076 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 16:54:41.818  4030  4076 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 470)
,08-30 16:54:41.822  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:41.822  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2bdbe5 added. We now have 2 listener(s)
,08-30 16:54:41.824  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:54:41.824  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:41.824  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:41.824  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:41.825  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ca96ba added. We now have 9 listener(s)
08-30 16:54:41.825  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:41.825  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:54:41.829  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:41.833  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:41.835  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:41.835  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:41.835  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:41.835  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@653ccc8 added. We now have 3 listener(s)
,08-30 16:54:41.837  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:54:41.837  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:41.837  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:41.837  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:41.837  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c35161 added. We now have 10 listener(s)
,08-30 16:54:41.838  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:41.838  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:41.838  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:41.838  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 16:54:41.838  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:41.838  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:41.838  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:41.838  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:54:41.838  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2bdbe5 removed from the list
08-30 16:54:41.838  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:41.838  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ca96ba removed from the list
08-30 16:54:41.838  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:41.839  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:41.839  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:41.839  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.839  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:41.844  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:41.844  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:41.844  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:41.844  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ca96ba not in the list
08-30 16:54:41.844  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:41.844  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:41.845  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:41.846  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:41.846  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:41.846  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:41.846  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c35161 removed from the list
08-30 16:54:41.846  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:41.846  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:41.846  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:41.846  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:41.847  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@653ccc8 removed from the list
08-30 16:54:41.847  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:41.847  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb6486 added. We now have 2 listener(s)
08-30 16:54:41.849  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:54:41.849  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:41.849  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:41.850  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:41.850  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ed147 added. We now have 9 listener(s)
,08-30 16:54:41.850  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:41.850  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:54:41.854  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:41.860  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:41.863  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 16:54:41.863  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:41.863  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 16:54:41.863  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302a29d added. We now have 3 listener(s)
,08-30 16:54:41.865  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:54:41.865  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 16:54:41.865  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:41.865  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:41.866  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8194312 added. We now have 10 listener(s)
,08-30 16:54:41.866  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:41.866  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:54:41.866  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 16:54:41.866  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-30 16:54:41.866  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:41.866  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:54:41.866  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:41.870  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:41.871  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:54:41.871  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:54:41.875  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 16:54:41.876  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:54:41.876  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:54:41.880  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 16:54:41.881  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:54:41.881  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:54:41.881  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:41.886  4371  4381 D BtGatt.GattService: registerClient() - UUID=5a60b463-afb4-45b6-91ad-4bd912648560
,08-30 16:54:41.888  4371  4389 D BtGatt.GattService: onClientRegistered() - UUID=5a60b463-afb4-45b6-91ad-4bd912648560, clientIf=5
,08-30 16:54:41.889  4030  4040 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 16:54:41.890  4371  4412 D BtGatt.GattService: start scan with filters
,08-30 16:54:41.895  4371  4392 D BtGatt.ScanManager: handling starting scan
,08-30 16:54:41.896  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:54:41.896  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 16:54:41.896  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 16:54:41.896  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:54:41.897  4371  4392 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@eac031
08-30 16:54:41.899  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:54:41.899  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:54:41.900  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:54:41.901  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 16:54:41.904  4371  4389 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:54:41.904  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:41.904  4371  4392 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:54:41.910  4030  4076 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 16:54:41.911  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:41.911  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 16:54:41.911  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.911  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:54:41.912  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 16:54:41.912  4371  4389 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:54:41.912  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:41.912  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 16:54:41.912  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:54:41.913  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:54:41.913  4371  4392 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:54:41.913  4371  4392 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:54:41.913  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:54:41.913  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:54:41.915  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:41.916  4371  4382 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:54:41.918  4371  4401 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 16:54:41.919  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 16:54:41.920  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:54:41.920  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:54:41.920  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 16:54:41.920  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:54:41.921  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:41.922  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:54:41.922  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:54:41.922  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:54:41.922  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 16:54:41.923  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:41.924  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:41.924  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:54:41.926  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 16:54:41.926  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:41.926  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:41.927  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:41.927  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:41.927  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:41.927  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:41.927  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb6486 removed from the list
08-30 16:54:41.927  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:41.927  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ed147 removed from the list
08-30 16:54:41.927  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:41.927  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:41.928  4371  4389 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:54:41.928  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:41.928  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:41.928  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:41.930  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:41.930  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:41.930  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:41.930  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84ed147 not in the list
08-30 16:54:41.930  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.930  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:41.931  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:41.931  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:41.931  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:41.931  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8194312 removed from the list
08-30 16:54:41.931  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:41.931  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.931  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:41.932  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:41.932  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@302a29d removed from the list
08-30 16:54:41.932  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:41.933  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c47e5e added. We now have 2 listener(s)
,08-30 16:54:41.934  4371  4389 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:54:41.934  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:41.935  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:54:41.935  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:41.935  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:41.936  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:41.936  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adea23f added. We now have 9 listener(s)
,08-30 16:54:41.936  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:41.936  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 16:54:41.939  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:41.942  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 16:54:41.943  4371  4389 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:54:41.943  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:41.944  4371  4392 D BtGatt.ScanManager: stopping BLe Batch
,08-30 16:54:41.945  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:41.945  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:41.945  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:41.945  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a48855 added. We now have 3 listener(s)
,08-30 16:54:41.947  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 16:54:41.948  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:41.948  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:41.948  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:41.948  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e56226a added. We now have 10 listener(s)
08-30 16:54:41.948  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:41.948  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:54:41.949  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 16:54:41.949  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:54:41.949  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 16:54:41.949  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 16:54:41.949  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 16:54:41.950  4371  4389 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:54:41.950  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:41.951  4371  4392 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:54:41.951  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:41.952  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 16:54:41.954  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-30 16:54:41.955  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:54:41.956  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:54:41.960  4371  4389 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:54:41.960  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:41.965  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:54:41.965  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:54:41.965  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 16:54:41.969  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 16:54:41.969  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:54:41.969  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:54:41.970  4030  4076 D BluetoothAdapter: STATE_ON
,08-30 16:54:41.972  4371  4382 D BtGatt.GattService: registerClient() - UUID=9db34e33-2f73-4c7c-a796-c57e11177ffe
,08-30 16:54:41.972  4371  4389 D BtGatt.GattService: onClientRegistered() - UUID=9db34e33-2f73-4c7c-a796-c57e11177ffe, clientIf=5
08-30 16:54:41.972  4030  4041 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:54:41.972  4371  4412 D BtGatt.GattService: start scan with filters
,08-30 16:54:41.975  4371  4392 D BtGatt.ScanManager: handling starting scan
,08-30 16:54:41.975  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 16:54:41.976  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:54:41.976  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:54:41.976  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-30 16:54:41.979  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:54:41.979  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 16:54:41.980  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 16:54:41.981  4371  4389 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 16:54:41.981  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:41.982  4371  4392 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 16:54:41.982  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 16:54:41.985  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:54:41.986  4030  4076 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 16:54:41.986  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:41.986  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 16:54:41.986  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:41.986  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 16:54:41.987  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.987  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:54:41.987  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 16:54:41.987  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6c47e5e removed from the list
08-30 16:54:41.987  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:41.987  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adea23f removed from the list
08-30 16:54:41.987  4371  4389 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:54:41.987  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:41.987  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:41.987  4371  4392 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:54:41.987  4371  4392 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 16:54:41.987  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:41.988  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.988  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 16:54:41.988  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 16:54:41.988  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:41.990  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:41.993  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 16:54:41.993  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:41.993  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adea23f not in the list,
,08-30 16:54:41.993  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 16:54:41.993  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:54:41.993  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:54:41.993  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 16:54:41.993  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:54:41.993  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 16:54:41.993  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-30 16:54:41.994  4030  4076 D BluetoothAdapter: STATE_ON
08-30 16:54:41.995  4371  4381 D BtGatt.GattService: stopScan() - queue size =1
,08-30 16:54:41.995  4371  4401 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:54:41.996  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:54:41.996  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 16:54:41.996  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:54:41.996  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 16:54:41.996   875  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 16:54:41.996  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 16:54:41.997  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 16:54:41.997  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:54:41.997  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 16:54:41.997  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:54:41.998  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 16:54:41.999  4371  4389 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 16:54:41.999  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 16:54:42.000  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:42.000  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 16:54:42.000  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 16:54:42.001  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:42.001  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e56226a removed from the list
08-30 16:54:42.001  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:42.001  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:42.001  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.001  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:42.001  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.001  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:42.001  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a48855 removed from the list
08-30 16:54:42.002  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:42.003  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabfb36 added. We now have 2 listener(s)
08-30 16:54:42.004  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:54:42.005   875  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 16:54:42.005   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-30 16:54:42.005   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:54:42.006  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:42.006  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:42.006  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:42.006  4371  4389 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:54:42.006  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.006  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4889a37 added. We now have 9 listener(s)
08-30 16:54:42.007  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:42.008  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:54:42.011  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:42.012  4371  4389 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:54:42.012  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.012  4371  4392 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:42.019  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:42.020  4371  4389 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:54:42.020  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.020  4371  4392 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:54:42.021   875  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 16:54:42.022  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:42.022  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:42.022  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:42.022  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1766d0d added. We now have 3 listener(s)
08-30 16:54:42.023  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:54:42.023  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:42.023  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:42.023  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:42.023  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:42.023  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b494c2 added. We now have 10 listener(s)
08-30 16:54:42.023  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:42.024  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:54:42.024  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 16:54:42.024  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 16:54:42.024  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:42.024  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 16:54:42.024  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:42.025  4371  4389 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:54:42.025  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.027  4030  4076 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 16:54:42.027  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 16:54:42.031   373   873 D CommandListener: Setting iface cfg
08-30 16:54:42.032   875  1316 D WifiStateMachine: Start Dhcp Watchdog 3
08-30 16:54:42.034  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 16:54:42.035  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 16:54:42.035  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 16:54:42.037  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 16:54:42.037  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 16:54:42.038  4030  4076 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 16:54:42.038  4030  4076 D BluetoothAdapter: STATE_ON
08-30 16:54:42.040  4371  4381 D BtGatt.GattService: registerClient() - UUID=59574b4c-246f-4ec4-b99a-cc2d4ae560eb
08-30 16:54:42.040  4371  4389 D BtGatt.GattService: onClientRegistered() - UUID=59574b4c-246f-4ec4-b99a-cc2d4ae560eb, clientIf=5
08-30 16:54:42.040  4030  4041 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 16:54:42.041   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-30 16:54:42.041  4371  4412 D BtGatt.GattService: start scan with filters
08-30 16:54:42.042  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 16:54:42.042  4371  4392 D BtGatt.ScanManager: handling starting scan
08-30 16:54:42.042  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 16:54:42.042  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 16:54:42.042  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 16:54:42.044  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:54:42.045  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 16:54:42.045  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 16:54:42.046  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-30 16:54:42.046  4371  4389 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 16:54:42.046  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.046  4371  4392 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-30 16:54:42.049  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:42.049  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:42.049  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:42.049  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:42.049  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.049  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 16:54:42.049  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:42.049  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabfb36 removed from the list
08-30 16:54:42.049  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:42.049  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4889a37 removed from the list
08-30 16:54:42.049  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:42.050  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:42.050  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.050  4371  4389 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 16:54:42.050  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 16:54:42.050  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.050  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.050  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:42.050  4371  4392 D BtGatt.ScanManager: Starting BLE batch scan
08-30 16:54:42.050  4371  4392 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 16:54:42.051  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:42.051  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:42.051  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:42.051  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4889a37 not in the list
08-30 16:54:42.051  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 16:54:42.051  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 16:54:42.051  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 16:54:42.051  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 16:54:42.051  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 16:54:42.051  4030  4076 D BluetoothAdapter: STATE_ON
08-30 16:54:42.052  4371  4412 D BtGatt.GattService: stopScan() - queue size =1
08-30 16:54:42.052  4371  4401 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 16:54:42.052  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 16:54:42.052  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 16:54:42.052  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 16:54:42.052  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 16:54:42.052  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 16:54:42.053  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:42.053  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 16:54:42.053  4030  4076 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 16:54:42.053  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 16:54:42.054  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.054  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:42.054  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:42.054  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:42.054  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:42.054  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b494c2 removed from the list
08-30 16:54:42.054  4030  4030 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 16:54:42.054  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:42.055  4030  4030 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 16:54:42.055  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.055  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.055  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:42.055  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1766d0d removed from the list
08-30 16:54:42.056  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:42.056  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bb3b0e added. We now have 2 listener(s)
08-30 16:54:42.057  4371  4389 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-30 16:54:42.057  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.057  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:54:42.057  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:42.057  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:42.058  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:42.058  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a992f added. We now have 9 listener(s)
08-30 16:54:42.058  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 16:54:42.058  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 16:54:42.059  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 16:54:42.060  4371  4389 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 16:54:42.060  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.061   875  4431 D DhcpClient: Receive thread started
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 16:54:42.062  4030  4076 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 16:54:42.063  4030  4076 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 16:54:42.064  4030  4076 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 16:54:42.064  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 16:54:42.064  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9930c5 added. We now have 3 listener(s)
08-30 16:54:42.064  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:42.064  4371  4389 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 16:54:42.064  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.064  4371  4392 D BtGatt.ScanManager: stopping BLe Batch
08-30 16:54:42.065  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 16:54:42.065  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 16:54:42.065  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 16:54:42.066  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 16:54:42.066  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 16:54:42.066  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@473fa1a added. We now have 10 listener(s)
08-30 16:54:42.066  4030  4076 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 16:54:42.066  4030  4076 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 16:54:42.066  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:42.066  4030  4076 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 16:54:42.066  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:42.067  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.067  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 16:54:42.067  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:42.067  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bb3b0e removed from the list
08-30 16:54:42.067  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:42.067  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a992f removed from the list
08-30 16:54:42.067  4030  4076 D io.jxcore.node.ConnectivityMonitor: stop
08-30 16:54:42.067  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.068  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.068  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.068  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:42.068  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:42.068  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:42.068  4371  4389 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 16:54:42.068  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.068  4030  4076 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8a992f not in the list
08-30 16:54:42.068  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.068  4371  4392 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 16:54:42.068  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.069  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 16:54:42.069  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 16:54:42.069  4030  4076 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 16:54:42.069  4030  4076 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@473fa1a removed from the list
08-30 16:54:42.069  4030  4076 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 16:54:42.069  4030  4076 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 16:54:42.069  4030  4076 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 16:54:42.069  4030  4076 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 16:54:42.069  4030  4076 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9930c5 removed from the list
08-30 16:54:42.070  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 16:54:42.070  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 16:54:42.070  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 16:54:42.070  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 16:54:42.070  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 16:54:42.070  4030  4076 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 16:54:42.072  4371  4389 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 16:54:42.072  4371  4389 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 16:54:42.074  4030  4432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 478, name: My test thread name)
08-30 16:54:42.074  4030  4432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 478, thread name: My test thread name)
08-30 16:54:42.074  4030  4432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 478, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 16:54:42.075  4030  4433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 480, name: My test thread name)
08-30 16:54:42.075  4030  4433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 480, thread name: My test thread name)
08-30 16:54:42.075  4030  4433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 480, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 16:54:42.076  4030  4076 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 16:54:42.076  4030  4076 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 16:54:42.076  4030  4076 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 16:54:42.076  4030  4076 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 16:54:42.076  4030  4076 D com.test.thalitest.ThaliTestRunner: Total duration: 22882 ms
08-30 16:54:42.077  4030  4076 I jxcore-log: *Native tests were executed*
08-30 16:54:42.077  4030  4076 I jxcore-log: 
08-30 16:54:42.078  4030  4076 I jxcore-log: Total number of executed tests:  80
08-30 16:54:42.078  4030  4076 I jxcore-log: 
08-30 16:54:42.078  4030  4076 I jxcore-log: Number of passed tests:  80
08-30 16:54:42.078  4030  4076 I jxcore-log: 
08-30 16:54:42.078  4030  4076 I jxcore-log: Number of failed tests:  0
08-30 16:54:42.078  4030  4076 I jxcore-log: 
08-30 16:54:42.078  4030  4076 I jxcore-log: Number of ignored tests:  0
08-30 16:54:42.078  4030  4076 I jxcore-log: 
08-30 16:54:42.078  4030  4076 I jxcore-log: Total duration:  22882
08-30 16:54:42.078  4030  4076 I jxcore-log: 
08-30 16:54:42.078  4030  4076 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 16:54:42.078  4030  4076 I jxcore-log: 
08-30 16:54:42.081  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.081  4030  4076 I jxcore-log: 
08-30 16:54:42.082  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.082  4030  4076 I jxcore-log: 
08-30 16:54:42.083  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.083  4030  4076 I jxcore-log: 
08-30 16:54:42.084  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.084  4030  4076 I jxcore-log: 
08-30 16:54:42.084  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.084  4030  4076 I jxcore-log: 
08-30 16:54:42.086  4030  4030 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 16:54:42.086  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.086  4030  4076 I jxcore-log: 
08-30 16:54:42.087  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.087  4030  4076 I jxcore-log: 
08-30 16:54:42.088  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.088  4030  4076 I jxcore-log: 
08-30 16:54:42.089  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.089  4030  4076 I jxcore-log: 
08-30 16:54:42.089  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.089  4030  4076 I jxcore-log: 
08-30 16:54:42.090  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.090  4030  4076 I jxcore-log: 
08-30 16:54:42.090  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.090  4030  4076 I jxcore-log: 
08-30 16:54:42.091  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:54:42.091  4030  4076 I jxcore-log: 
08-30 16:54:42.092  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.092  4030  4076 I jxcore-log: 
08-30 16:54:42.092  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.092  4030  4076 I jxcore-log: 
08-30 16:54:42.092  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.092  4030  4076 I jxcore-log: 
08-30 16:54:42.093  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.093  4030  4076 I jxcore-log: 
08-30 16:54:42.093  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.093  4030  4076 I jxcore-log: 
08-30 16:54:42.094  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.094  4030  4076 I jxcore-log: 
08-30 16:54:42.094  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.094  4030  4076 I jxcore-log: 
08-30 16:54:42.095  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.095  4030  4076 I jxcore-log: 
08-30 16:54:42.095  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.095  4030  4076 I jxcore-log: 
08-30 16:54:42.096  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.096  4030  4076 I jxcore-log: 
08-30 16:54:42.096  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.096  4030  4076 I jxcore-log: 
08-30 16:54:42.097  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.097  4030  4076 I jxcore-log: 
08-30 16:54:42.097  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.097  4030  4076 I jxcore-log: 
08-30 16:54:42.097  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 16:54:42.097  4030  4076 I jxcore-log: 
08-30 16:54:42.098  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.098  4030  4076 I jxcore-log: 
08-30 16:54:42.098  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.098  4030  4076 I jxcore-log: 
08-30 16:54:42.099  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.099  4030  4076 I jxcore-log: 
08-30 16:54:42.099  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.099  4030  4076 I jxcore-log: 
08-30 16:54:42.100  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.100  4030  4076 I jxcore-log: 
08-30 16:54:42.100  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.100  4030  4076 I jxcore-log: 
08-30 16:54:42.100  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 16:54:42.100  4030  4076 I jxcore-log: 
,08-30 16:54:42.142   875  1316 E native  : do suspend false
,08-30 16:54:42.152   875  1857 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 16:54:42.164   875  4431 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-30 16:54:42.165   875  1857 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-30 16:54:42.168   875  1857 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 16:54:42.223   875  4431 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 16:54:42.223   875  1857 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 16:54:42.225   373   873 D CommandListener: Setting iface cfg
,08-30 16:54:42.231   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 16:54:42.232   875  1857 D DhcpClient: Scheduling renewal in 86399s
,08-30 16:54:42.233   875  1316 E native  : do suspend true
,08-30 16:54:42.249   875  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 16:54:42.251   875  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 16:54:42.252   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,08-30 16:54:42.255   875  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 16:54:42.260   875  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 16:54:42.338   875  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 16:54:42.339   875  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 16:54:42.342   875  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 16:54:42.344   875  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-30 16:54:42.345   875  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 16:54:42.355   875  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 16:54:42.360   875  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-30 16:54:42.361   875  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-30 16:54:42.361   875  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-30 16:54:42.361   875  1318 D ConnectivityService:    accepting network in place of null
08-30 16:54:42.361   875  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 16:54:42.362   875  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 16:54:42.363   875  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 16:54:42.411   875  4429 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218127, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 16:54:42.416   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:54:42.424  4030  4030 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:54:42.427  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:54:42.427  4030  4076 I jxcore-log: 
,08-30 16:54:42.448   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 16:54:42.453   875  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 16:54:42.453   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:54:42.457   875  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-30 16:54:42.457   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 16:54:42.471  4030  4030 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 16:54:42.473  4030  4030 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 16:54:42.474  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 16:54:42.474  4030  4076 I jxcore-log: 
,08-30 16:54:42.481  1733  1733 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 16:54:42.487  1733  1733 D SystemUpdateService: onCreate
,08-30 16:54:42.494  1733  1733 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-30 16:54:42.501  4030  4030 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 16:54:42.504  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:54:42.504  4030  4076 I jxcore-log: 
08-30 16:54:42.517  1733  4445 I SystemUpdateService: active receiver: enabled
,08-30 16:54:42.535  1733  4445 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 16:54:42.538  1733  4445 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 16:54:42.538  1733  4445 I SystemUpdateService: now status is 0 (complete)
,08-30 16:54:42.538  1733  4445 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 16:54:42.538  1733  4445 I SystemUpdateService: file has been verified
08-30 16:54:42.540  1733  4445 I SystemUpdateService: OTA package size = 12249756
,08-30 16:54:42.553  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:42.555  4030  4030 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 16:54:42.556  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 16:54:42.558  4030  4076 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 16:54:42.558  4030  4076 I jxcore-log: 
,08-30 16:54:42.576  3949  4446 V GoogleAuthProtoRequest: [356] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:54:42.578  1733  4445 I SystemUpdateService: showing system update notification
,08-30 16:54:42.607  1733  1733 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 16:54:42.619  1733  4448 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 16:54:42.619  1733  4448 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 16:54:42.621  1733  4448 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 16:54:42.622  1733  1733 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 16:54:42.623  1733  1733 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 16:54:42.625  4166  4166 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 16:54:42.630  4166  4166 D SprintDMHelper: simOperator: 
,08-30 16:54:42.630  4166  4166 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 16:54:42.651   875  4428 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-30 16:54:42.657  1733  2314 I iu.UploadsManager: num queued entries: 0
,08-30 16:54:42.671  1733  2314 I iu.UploadsManager: num updated entries: 0
,08-30 16:54:42.671  1733  2314 I iu.SyncManager: NEXT; no task
,08-30 16:54:42.701  1518  2340 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-30 16:54:42.701  1518  2340 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-30 16:54:42.702  1518  2340 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:54:42.702  1518  2340 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:54:42.737  1733  1733 D SystemUpdateService: onDestroy
,08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: [356] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: [356] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-30 16:54:42.748  3949  4446 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-30 16:54:42.760   875  4428 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 14:54:42 GMT], X-Android-Received-Millis=[1472568882759], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472568882712]}
,08-30 16:54:42.762   875  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 16:54:42.762   875  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 16:54:42.762   875  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 16:54:42.764   875  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 16:54:42.768  1518  2137 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 16:54:42.768  1518  2137 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 16:54:42.768  1518  2137 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 16:54:42.768  1518  2137 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 16:54:42.799  1733  4448 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-30 16:54:42.825  4434  4434 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 16:54:42.829  4434  4434 D AndroidRuntime: CheckJNI is OFF
,08-30 16:54:42.868  4434  4434 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 16:54:42.915  4434  4434 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 16:54:42.938  4434  4434 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 16:54:42.953   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 16:54:42.954   875   888 I ActivityManager: Killing 4030:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 16:54:43.040   875  1382 I WindowState: WIN DEATH: Window{8392e2a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 16:54:43.037   875  1317 D WifiService: Client connection lost with reason: 4
08-30 16:54:43.036   875  2018 D GraphicsStats: Buffer count: 2
,08-30 16:54:43.099   875   898 W PackageSettings: Skipping PackageSetting{d5c251a com.example.hello/10273} due to missing metadata
,08-30 16:54:43.131   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 16:54:43.132   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 16:54:43.133   875   898 I art     : Starting a blocking GC Explicit
,08-30 16:54:43.135   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-30 16:54:43.135   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 16:54:43.135   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.135   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.135   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:54:43.135   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-30 16:54:43.138   875   888 I ActivityManager:   Force finishing activity ActivityRecord{dc49117 u0 com.test.thalitest/.MainActivity t2}
,08-30 16:54:43.150   875  1984 W ActivityManager: Spurious death for ProcessRecord{fcbde05 0:com.test.thalitest/u0a0}, curProc for 4030: null
,08-30 16:54:43.180  4137  4451 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 16:54:43.182   875   898 I art     : Explicit concurrent mark sweep GC freed 34067(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 795us total 48.501ms
,08-30 16:54:43.233   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 16:54:43.235  4434  4434 I art     : System.exit called, status: 0
08-30 16:54:43.235  4434  4434 I AndroidRuntime: VM exiting with result code 0.
,08-30 16:54:43.239   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 16:54:43.253   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 16:54:43.258  4371  4371 D BluetoothMapAppObserver: onReceive
,08-30 16:54:43.258  4371  4371 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-30 16:54:43.261  2091  2296 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 16:54:43.262   875  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 16:54:43.259  3806  3806 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 16:54:43.264  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 16:54:43.288  1881  4467 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 16:54:43.294  1881  4467 I Decoder : createOrResetDecoder
,08-30 16:54:43.302  1964  1964 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 16:54:43.312   875  1984 I ActivityManager: Start proc 4470:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 16:54:43.331  1518  1518 I ConfigService: onCreate
,08-30 16:54:43.341   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 16:54:43.343  4470  4470 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 16:54:43.363  1981  2086 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 16:54:43.364   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-30 16:54:43.369   875  2028 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4030 uid 10000
,08-30 16:54:43.366   875   887 E PackageManager: Failed to write settings, restoring backup
08-30 16:54:43.366   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 16:54:43.366   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 16:54:43.366   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 16:54:43.366   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 16:54:43.366   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 16:54:43.366   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.366   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.366   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:54:43.370  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-30 16:54:43.374   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-30 16:54:43.374   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 16:54:43.374   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:43.374   875   888 E DropBoxManagerService: 	... 13 more
,08-30 16:54:43.378   875  1382 I ActivityManager: Start proc 4483:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 16:54:43.379  1981  2086 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 16:54:43.379  1981  2086 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1981
08-30 16:54:43.379  1981  2086 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.379  1981  2086 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:54:43.381   875   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 16:54:43.381   875  4489 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:54:43.381   875  4489 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:43.381   875  4489 E DropBoxManagerService: 	... 5 more
08-30 16:54:43.384  1981  2086 I Process : Sending signal. PID: 1981 SIG: 9
,08-30 16:54:43.394  1881  4467 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 16:54:43.430  4470  4470 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 16:54:43.453   875  2021 I WindowState: WIN DEATH: Window{c82d95 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-30 16:54:43.453   875  2018 D GraphicsStats: Buffer count: 1
,08-30 16:54:43.457   875   886 I ActivityManager: Start proc 4501:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 16:54:43.478   875  1924 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1981) has died
,08-30 16:54:43.479   875  1924 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 16:54:43.479  1881  4467 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 16:54:43.480   875  1924 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 16:54:43.481  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 16:54:43.481  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 16:54:43.482  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 16:54:43.482  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 16:54:43.487  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-30 16:54:43.487  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 16:54:43.487  1881  4467 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 16:54:43.488  1881  4467 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 16:54:43.488  1881  4467 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 16:54:43.488  1881  4467 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 16:54:43.488  1881  4467 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-30 16:54:43.488  1881  4467 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 16:54:43.491  4470  4513 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 16:54:43.494  4470  4497 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.494  4470  4497 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:54:43.496   875  1992 I ActivityManager: Start proc 4514:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 16:54:43.515  4501  4501 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 16:54:43.538  4514  4514 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:43.538  4514  4514 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 16:54:43.538  4514  4514 D AndroidRuntime: Shutting down VM
,08-30 16:54:43.542  4514  4514 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:54:43.542  4514  4514 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4514
08-30 16:54:43.542  4514  4514 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:54:43.542  4514  4514 E AndroidRuntime: 	... 10 more
,08-30 16:54:43.544   875   885 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 16:54:43.545  4514  4514 I Process : Sending signal. PID: 4514 SIG: 9
08-30 16:54:43.545   875  4529 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:54:43.545   875  4529 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:43.545   875  4529 E DropBoxManagerService: 	... 5 more
,08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.569  4470  4497 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:54:43.570   875  1984 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4514) has died,
,08-30 16:54:43.571   875  1984 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 16:54:43.576  1733  4530 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 16:54:43.580  1518  1518 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-30 16:54:43.580  1733  4530 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-30 16:54:43.585   875   888 I ActivityManager: Start proc 4532:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:54:43.584  1518  1518 D AndroidRuntime: Shutting down VM
,08-30 16:54:43.593   875  1989 I ActivityManager: Killing 3863:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 16:54:43.596  1518  1518 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:54:43.596  1518  1518 E AndroidRuntime: Process: com.google.process.gapps, PID: 1518
08-30 16:54:43.596  1518  1518 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 16:54:43.596  1518  1518 E AndroidRuntime: 	... 8 more
,08-30 16:54:43.634  4470  4497 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 16:54:43.638  4470  4513 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.638  4470  4513 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:54:43.639  4470  4513 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 16:54:43.639  4470  4513 E AndroidRuntime: Process: android.process.acore, PID: 4470
08-30 16:54:43.639  4470  4513 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694),
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.639  4470  4513 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 16:54:43.639  4470  4497 I Process : Sending signal. PID: 4470 SIG: 9
,08-30 16:54:43.654  1733  4530 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 16:54:43.659  1733  4530 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 16:54:43.661   875  4544 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:54:43.661   875  4544 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:43.661   875  4544 E DropBoxManagerService: 	... 5 more
,08-30 16:54:43.675   875  4545 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:54:43.675   875  4545 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:43.675   875  4545 E DropBoxManagerService: 	... 5 more
,08-30 16:54:43.678   875  2022 I ActivityManager: Process android.process.acore (pid 4470) has died
08-30 16:54:43.678   875  2022 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-30 16:54:43.680  1518  1518 I Process : Sending signal. PID: 1518 SIG: 9
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:43.690  4532  4532 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:54:43.690  4532  4532 D AndroidRuntime: Shutting down VM
08-30 16:54:43.698  4532  4532 E AndroidRuntime: FATAL EXCEPTION: main
08-30 16:54:43.698  4532  4532 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4532
08-30 16:54:43.698  4532  4532 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 16:54:43.698  4532  4532 E AndroidRuntime: 	... 10 more
08-30 16:54:43.700   875  2021 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:54:43.701  4532  4532 I Process : Sending signal. PID: 4532 SIG: 9
08-30 16:54:43.701   875  4546 E DropBoxManagerService: Can't write: system_app_crash
08-30 16:54:43.701   875  4546 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 16:54:43.701   875  4546 E DropBoxManagerService: 	... 5 more
,08-30 16:54:43.713  1733  4530 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-30 16:54:43.713  1733  4530 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-30 16:54:43.724   875  2022 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4532) has died
08-30 16:54:43.725   875  2022 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-30 16:54:43.739   875   888 I ActivityManager: Start proc 4547:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 16:54:43.740   875  1317 D WifiService: Client connection lost with reason: 4

```
