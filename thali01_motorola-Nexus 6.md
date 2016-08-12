#### Test 797510151684451_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 18:36:09.568  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:09.588  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 18:36:09.594  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 18:36:09.669  1495  2231 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 18:36:09.669  1495  2231 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 18:36:09.669  1495  2231 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:09.670  1495  2231 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 18:36:09.715  3545  3545 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 18:36:09.715  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 18:36:09.716  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-12 18:36:10.225  3901  3901 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 18:36:10.229  3901  3901 D AndroidRuntime: CheckJNI is OFF
08-12 18:36:10.267  3901  3901 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 18:36:10.311  3901  3901 I Radio-JNI: register_android_hardware_Radio DONE
08-12 18:36:10.333  3901  3901 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 18:36:10.340   876  1987 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 18:36:10.418  3901  3901 D AndroidRuntime: Shutting down VM
08-12 18:36:10.419  2015  3805 W SearchService: Abort, client detached.
08-12 18:36:10.428  2015  2355 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9d1cbf0
08-12 18:36:10.428  2015  2367 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 18:36:10.429  2015  2015 I HotwordDetector: Closing mic
08-12 18:36:10.449   876  1975 I ActivityManager: Start proc 3911:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 18:36:10.475   378  2369 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 18:36:10.478   378  2369 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 18:36:10.483   378  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 18:36:10.486  2015  2362 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 18:36:10.486  2015  2364 I MicroRecognitionRnrImpl: Detection finished
08-12 18:36:10.531  3911  3911 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 18:36:10.561  3911  3911 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 18:36:10.572  3911  3911 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2127-2132)
08-12 18:36:10.572  3911  3911 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:36:10.585  3911  3911 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fe81254}
08-12 18:36:10.585  3911  3911 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:36:10.586  3911  3911 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 18:36:10.593  3911  3911 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 18:36:10.595  3911  3911 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-12 18:36:10.638  3911  3911 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 18:36:10.652  3911  3911 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:36:10.652  3911  3911 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:36:10.652  3911  3911 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 18:36:10.652  3911  3911 I Adreno  : Build Date                       : 10/20/15
08-12 18:36:10.652  3911  3911 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 18:36:10.652  3911  3911 I Adreno  : Local Branch                     : M14
08-12 18:36:10.652  3911  3911 I Adreno  : Remote Branch                    : 
08-12 18:36:10.652  3911  3911 I Adreno  : Remote Branch                    : 
08-12 18:36:10.652  3911  3911 I Adreno  : Reconstruct Branch               : 
08-12 18:36:10.755   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c286bb:true
08-12 18:36:10.803  3911  3911 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 18:36:10.819  3911  3911 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-12 18:36:10.869  3911  3949 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 18:36:10.876  3911  3936 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 18:36:10.914  3911  3949 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:36:10.980   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +547ms
08-12 18:36:10.990  1879  1879 I Keyboard.Facilitator: onFinishInput()
08-12 18:36:11.075  3911  3911 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3911
08-12 18:36:11.196  3911  3911 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-12 18:36:11.264   876  1391 I ActivityManager: Killing 3404:com.google.android.music:main/u0a66 (adj 15): empty #17
08-12 18:36:11.303   876  1391 I ActivityManager: Killing 2989:com.google.android.calendar/u0a37 (adj 15): empty #18
08-12 18:36:11.466  3911  3952 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1719928528
08-12 18:36:11.476  3911  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:36:11.476  3911  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:36:11.476  3911  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:36:11.476  3911  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:36:11.476  3911  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 18:36:11.476  3911  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f484b98 added. We now have 1 listener(s)
08-12 18:36:11.481  3911  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-12 18:36:11.483  3911  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 18:36:11.484  3911  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 18:36:11.484  3911  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 18:36:11.489  3911  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5dd3a57 added. We now have 1 listener(s)
08-12 18:36:11.490  3911  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 18:36:11.492   876  1309 D WifiService: New client listening to asynchronous messages
08-12 18:36:11.494  3911  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 18:36:11.494  3911  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 18:36:11.494  3911  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:36:11.494  3911  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:36:11.494  3911  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 18:36:11.497  3911  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 18:36:11.497  3911  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-12 18:36:11.504  3911  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:36:11.505  3911  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:36:11.505  3911  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:36:11.505  3911  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 18:36:11.506  3911  3952 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 18:36:11.509  3911  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:36:11.513  3911  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:36:11.542  3911  3911 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-12 18:36:11.957   876  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 18:36:12.735  3911  3960 W jxcore-log: Initializing JXcore engine
,08-12 18:36:12.735  3911  3960 W jxcore-log: JXcore engine is ready
,08-12 18:36:12.776  3960  3960 W Thread-338: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 18:36:12.776  3960  3960 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11853]" dev="sockfs" ino=11853 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 18:36:12.776  3960  3960 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 18:36:12.776  3960  3960 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25476]" dev="sockfs" ino=25476 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 18:36:12.789  3911  3960 W jxcore-log: Starting JXcore engine
,08-12 18:36:12.862  3911  3960 W jxcore-log: Platform android
08-12 18:36:12.862  3911  3960 W jxcore-log: 
,08-12 18:36:12.862  3911  3960 W jxcore-log: Process ARCH arm
08-12 18:36:12.862  3911  3960 W jxcore-log: 
,08-12 18:36:13.074  3911  3960 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:36:13.074  3911  3960 I jxcore-log: 
,08-12 18:36:13.074  3911  3960 W jxcore-log: JXcore engine is started
,08-12 18:36:13.086  3911  3952 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 18:36:13.092  3911  3911 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 18:36:15.150  3630  3963 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 18:36:15.172  3630  3964 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 18:36:15.183  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:15.185  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:15.219  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 18:36:15.219  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 18:36:15.220  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:15.220  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:15.262  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:15.266  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:15.303  1495  2005 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 18:36:15.303  1495  2005 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 18:36:15.303  1495  2005 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:36:15.303  1495  2005 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:15.325  3630  3964 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 18:36:15.326  3630  3963 E BooksSync: Soft error
08-12 18:36:15.326  3630  3963 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 18:36:15.326  3630  3963 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 18:36:15.327  3630  3963 E BooksSync: Sync error
08-12 18:36:15.327  3630  3963 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 18:36:15.327  3630  3963 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 18:36:15.327  3630  3963 I BooksSync: Finished books sync
,08-12 18:36:15.338   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 126661, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:36:15.558  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:15.560  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:15.591  1495  2231 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
,08-12 18:36:15.591  1495  2231 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
,08-12 18:36:15.591  1495  2231 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:36:15.591  1495  2231 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:15.612  2015  2208 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:36:15.612  2015  2208 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
,08-12 18:36:15.614  2015  2176 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-12 18:36:15.648  2015  2176 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-12 18:36:15.656  2015  2176 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7213-7216)
,08-12 18:36:15.656  2015  2176 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 18:36:20.850   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 18:36:29.070  3911  3960 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:36:29.070  3911  3960 I jxcore-log: 
,08-12 18:36:29.073  3911  3960 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:36:29.073  3911  3960 I jxcore-log: 
,08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:36:29.082  3911  3960 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 18:36:29.086  3911  3960 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 18:36:29.088  3911  3960 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:36:29.088  3911  3960 I jxcore-log: 
,08-12 18:36:29.090  3911  3960 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:36:29.090  3911  3960 I jxcore-log: 
,08-12 18:36:29.437  3911  3960 I jxcore-log: Unit Test app is loaded
08-12 18:36:29.437  3911  3960 I jxcore-log: 
,08-12 18:36:29.444  3911  3960 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:36:29.444  3911  3960 I jxcore-log: 
,08-12 18:36:29.448  3911  3960 I jxcore-log: My device name is: motorola-Nexus 6
08-12 18:36:29.448  3911  3960 I jxcore-log: 
,08-12 18:36:29.450  3911  3960 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 18:36:29.450  3911  3960 I jxcore-log: 
,08-12 18:36:29.462  3911  3911 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 18:36:31.733  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 18:36:31.733  3911  3960 I jxcore-log: 
,08-12 18:36:32.353  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 18:36:32.353  3911  3960 I jxcore-log: 
,08-12 18:36:32.380  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 18:36:32.380  3911  3960 I jxcore-log: 
,08-12 18:36:32.509  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 18:36:32.511  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:32.521  3445  3990 V GoogleAuthProtoRequest: [280] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 18:36:32.554  1495  2005 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 18:36:32.555  1495  2005 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 18:36:32.555  1495  2005 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:32.555  1495  2005 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: [280] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: [280] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 18:36:32.573  3445  3990 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 18:36:32.645  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:32.668  1495  2231 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 18:36:32.668  1495  2231 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 18:36:32.668  1495  2231 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:32.668  1495  2231 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:32.681  3545  3545 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 18:36:32.681  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 18:36:32.681  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-12 18:36:32.710  1495  3991 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 18:36:32.712  1495  3991 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 18:36:32.737  1495  3991 W Uploader:  no longer exists, so no auth token.
,08-12 18:36:33.844  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 18:36:33.844  3911  3960 I jxcore-log: 
,08-12 18:36:34.045  1495  3991 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-12 18:36:34.045  1495  3991 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 18:36:34.045  1495  3991 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:34.045  1495  3991 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:34.073  1495  3991 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 18:36:34.073  1495  3991 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 18:36:34.073  1495  3991 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 18:36:34.091  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 18:36:34.091  3911  3960 I jxcore-log: 
,08-12 18:36:34.097  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 18:36:34.097  3911  3960 I jxcore-log: 
,08-12 18:36:34.104  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 18:36:34.104  3911  3960 I jxcore-log: 
,08-12 18:36:34.123  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 18:36:34.123  3911  3960 I jxcore-log: 
,08-12 18:36:34.127  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 18:36:34.127  3911  3960 I jxcore-log: 
,08-12 18:36:34.388  1495  3991 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 18:36:34.388  1495  3991 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 18:36:34.388  1495  3991 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:34.388  1495  3991 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:34.418  1495  3991 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 18:36:34.418  1495  3991 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 18:36:34.418  1495  3991 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 18:36:34.824  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 18:36:34.824  3911  3960 I jxcore-log: 
,08-12 18:36:34.836  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 18:36:34.836  3911  3960 I jxcore-log: 
,08-12 18:36:34.846  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 18:36:34.846  3911  3960 I jxcore-log: 
,08-12 18:36:34.853  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 18:36:34.853  3911  3960 I jxcore-log: 
,08-12 18:36:34.900  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 18:36:34.900  3911  3960 I jxcore-log: 
,08-12 18:36:34.959  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 18:36:34.959  3911  3960 I jxcore-log: 
,08-12 18:36:34.968  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 18:36:34.968  3911  3960 I jxcore-log: 
,08-12 18:36:35.018  1495  3991 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 18:36:35.018  1495  3991 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 18:36:35.018  1495  3991 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:36:35.020  1495  3991 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:35.061  1495  3991 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 18:36:35.061  1495  3991 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 18:36:35.061  1495  3991 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 18:36:35.146  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 18:36:35.146  3911  3960 I jxcore-log: 
,08-12 18:36:35.175  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 18:36:35.175  3911  3960 I jxcore-log: 
,08-12 18:36:35.182  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 18:36:35.182  3911  3960 I jxcore-log: 
,08-12 18:36:35.189  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 18:36:35.189  3911  3960 I jxcore-log: 
,08-12 18:36:35.212  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 18:36:35.212  3911  3960 I jxcore-log: 
,08-12 18:36:35.298  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 18:36:35.298  3911  3960 I jxcore-log: 
,08-12 18:36:35.310  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 18:36:35.310  3911  3960 I jxcore-log: 
,08-12 18:36:35.337  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 18:36:35.337  3911  3960 I jxcore-log: 
,08-12 18:36:35.350  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 18:36:35.350  3911  3960 I jxcore-log: 
,08-12 18:36:35.369  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 18:36:35.369  3911  3960 I jxcore-log: 
,08-12 18:36:35.408  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 18:36:35.408  3911  3960 I jxcore-log: 
,08-12 18:36:35.415  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 18:36:35.415  3911  3960 I jxcore-log: 
,08-12 18:36:35.623  3911  3960 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 18:36:35.623  3911  3960 I jxcore-log: 
,08-12 18:36:35.636  3911  3960 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 18:36:35.637  3911  3960 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 18:36:35.637  3911  3960 I jxcore-log: 
,08-12 18:36:38.630   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 18:36:38.642  1879  1879 I Keyboard.Facilitator: onFinishInput()
,08-12 18:36:38.658   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 18:36:38.658   876   896 I Adreno  : Build Date                       : 10/20/15
08-12 18:36:38.658   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 18:36:38.658   876   896 I Adreno  : Local Branch                     : M14
08-12 18:36:38.658   876   896 I Adreno  : Remote Branch                    : 
08-12 18:36:38.658   876   896 I Adreno  : Remote Branch                    : 
08-12 18:36:38.658   876   896 I Adreno  : Reconstruct Branch               : 
,08-12 18:36:38.690   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (189 us)
,08-12 18:36:39.368  3911  3911 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 18:36:39.368  3911  3911 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 18:36:39.419  3911  3911 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7f71e4a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@17ff141, 16908290=android.view.AbsSavedState$1@17ff141}, android:focusedViewId=100}]}]
,08-12 18:36:39.419  3911  3911 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-12 18:36:39.419  3911  3911 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 18:36:39.419  3911  3911 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 18:36:39.420   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 18:36:39.436   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 18:36:39.441   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 18:36:39.443   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-12 18:36:39.443   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-12 18:36:39.671   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 18:36:39.673   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 18:36:39.678   876  1332 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
,08-12 18:36:39.683   876   896 I DreamManagerService: Entering dreamland.
,08-12 18:36:39.684   876   896 I PowerManagerService: Dozing...
,08-12 18:36:39.685   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 18:36:39.757   378  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 18:36:39.757   378  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 18:36:39.770   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 18:36:39.787  1929  4007 D NfcService: Discovery configuration equal, not updating.
,08-12 18:36:39.787   876  1308 E native  : do suspend false
,08-12 18:36:39.811   876  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 18:36:39.829   876  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 18:36:39.835   876  1308 E native  : do suspend true
,08-12 18:36:39.887   378  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-12 18:36:39.888   378  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 18:36:40.277   876  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 18:36:44.294  1868  2645 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 18:36:45.555  3045  4013 V KeepSync: Connecting to GoogleApiClient
,08-12 18:36:45.555   876  1424 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 18:36:45.612  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:45.615  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:45.654  1495  2983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-12 18:36:45.654  1495  2983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 18:36:45.654  1495  2983 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:45.654  1495  2983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:45.683  1688  4016 V BaseAuthAsyncOperation: access token request failed
,08-12 18:36:45.687  3045  4013 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 18:36:45.743  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 18:36:45.743  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 18:36:45.744  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:36:45.744  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:45.773  1495  2231 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-12 18:36:45.774  1495  2231 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 18:36:45.774  1495  2231 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:36:45.776  1495  2231 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:45.781  3588  4015 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 18:36:45.781  3588  4015 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jdm.a(PG:82)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jcs.o(PG:406)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jcn.a(PG:1379)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jcs.i(PG:143)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at blb.a(PG:3937)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at czp.a(PG:18188)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at czp.a(PG:9081)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at czq.run(PG:1686)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:36:45.781  3588  4015 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jdj.a(PG:4091)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jdj.a(PG:1125)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jdm.a(PG:77)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	... 12 more
08-12 18:36:45.781  3588  4015 E HttpOperation: Caused by: faj: BadAuthentication
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at fal.a(PG:38)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	at jdj.a(PG:4089)
08-12 18:36:45.781  3588  4015 E HttpOperation: 	... 14 more
,08-12 18:36:45.825  3045  4013 E KeepSync: IOException
08-12 18:36:45.825  3045  4013 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 18:36:45.825  3045  4013 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 18:36:45.825  3045  4013 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 18:36:45.825  3045  4013 E KeepSync: 	... 10 more
,08-12 18:36:45.825  3045  4013 W KeepSync: Sync result 2
,08-12 18:36:45.837   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127014, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:36:45.843  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 18:36:45.843  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 18:36:45.844  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:36:45.844  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:45.864  3588  4015 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 18:36:45.864  3588  4015 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jdm.a(PG:82)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jcs.o(PG:406)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jcn.a(PG:1379)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jcs.i(PG:143)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at hec.a(PG:42)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at hee.a(PG:102)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at czr.a(PG:65)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at kka.a(PG:108)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at czp.a(PG:19176)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at czp.a(PG:9081)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at czq.run(PG:1686)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588),
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:36:45.864  3588  4015 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jdj.a(PG:4091)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jdj.a(PG:1125)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jdm.a(PG:77)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	... 15 more
08-12 18:36:45.864  3588  4015 E HttpOperation: Caused by: faj: BadAuthentication
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at fal.a(PG:38)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	at jdj.a(PG:4089)
08-12 18:36:45.864  3588  4015 E HttpOperation: 	... 17 more
,08-12 18:36:45.865  3588  4015 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 18:36:45.865  3588  4015 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at hec.a(PG:42)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at hee.a(PG:102)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at czr.a(PG:65)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at kka.a(PG:108)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	... 15 more
08-12 18:36:45.865  3588  4015 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at fal.a(PG:38)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 18:36:45.865  3588  4015 E ExperimentLoader: 	... 17 more
,08-12 18:36:46.067   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127952, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:36:51.973   876  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 18:36:53.107  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:53.128  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:53.135  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:36:53.227  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 18:36:53.227  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 18:36:53.228  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:36:53.228  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:36:53.300  3545  3545 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 18:36:53.303  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 18:36:53.307  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 18:37:04.384   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 18:37:13.635  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:37:13.654  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:37:13.661  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:37:13.765  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 18:37:13.765  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 18:37:13.766  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:37:13.767  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:37:13.824  3545  3545 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 18:37:13.825  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 18:37:13.829  3545  3545 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 18:37:13.931   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=185491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 18:37:38.643  1879  1919 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-12 18:37:38.643  1879  1919 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 18:37:38.692  1495  1495 I ConfigService: onCreate
,08-12 18:37:43.210   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=214770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 18:37:43.729  1495  1495 I ConfigService: onDestroy
,08-12 18:37:49.905   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 18:38:09.748  1495  2061 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 18:38:17.514  3630  4022 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 18:38:17.547  3630  4023 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 18:38:17.561  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:17.565  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:17.592  1495  2231 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 18:38:17.592  1495  2231 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 18:38:17.592  1495  2231 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:38:17.592  1495  2231 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:38:17.623  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:17.625  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:17.656  1495  2983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 18:38:17.656  1495  2983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 18:38:17.656  1495  2983 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:38:17.656  1495  2983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:38:17.687  3630  4023 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 18:38:17.688  3630  4022 E BooksSync: Soft error
08-12 18:38:17.688  3630  4022 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 18:38:17.688  3630  4022 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 18:38:17.689  3630  4022 E BooksSync: Sync error
08-12 18:38:17.689  3630  4022 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 18:38:17.689  3630  4022 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 18:38:17.689  3630  4022 I BooksSync: Finished books sync
,08-12 18:38:17.703   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 248970, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:38:19.157   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=250717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 18:38:25.944   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 18:38:32.695  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:32.697  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:32.709  3445  4024 V GoogleAuthProtoRequest: [281] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 18:38:32.736  1495  2231 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 18:38:32.736  1495  2231 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 18:38:32.736  1495  2231 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:38:32.736  1495  2231 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: [281] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: [281] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 18:38:32.757  3445  4024 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 18:38:50.042  3045  4026 V KeepSync: Connecting to GoogleApiClient
08-12 18:38:50.042   876  1680 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 18:38:50.092  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:50.094  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:38:50.137  1495  2005 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 18:38:50.137  1495  2005 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 18:38:50.138  1495  2005 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 18:38:50.138  1495  2005 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:38:50.162  1688  4027 V BaseAuthAsyncOperation: access token request failed
,08-12 18:38:50.163  3045  4026 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 18:38:50.240  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 18:38:50.240  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 18:38:50.240  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:38:50.240  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:38:50.251  3045  4026 E KeepSync: IOException
08-12 18:38:50.251  3045  4026 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 18:38:50.251  3045  4026 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 18:38:50.251  3045  4026 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 18:38:50.251  3045  4026 E KeepSync: 	... 10 more
,08-12 18:38:50.251  3045  4026 W KeepSync: Sync result 2
,08-12 18:38:50.256   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 281461, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:38:55.210   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=286770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 18:39:01.331   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=292890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 18:39:20.474  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:39:20.475  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:39:20.503  1495  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 18:39:20.504  1495  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 18:39:20.504  1495  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:39:20.504  1495  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:39:20.517  3588  4035 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 18:39:20.517  3588  4035 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jdm.a(PG:82)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jcs.o(PG:406)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jcn.a(PG:1379)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jcs.i(PG:143)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at blb.a(PG:3937)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at czp.a(PG:18188)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at czp.a(PG:9081)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at czq.run(PG:1686)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:39:20.517  3588  4035 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jdj.a(PG:4091)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jdj.a(PG:1125)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jdm.a(PG:77)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	... 12 more
08-12 18:39:20.517  3588  4035 E HttpOperation: Caused by: faj: BadAuthentication
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at fal.a(PG:38)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	at jdj.a(PG:4089)
08-12 18:39:20.517  3588  4035 E HttpOperation: 	... 14 more
,08-12 18:39:20.609  1495  2983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 18:39:20.609  1495  2983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 18:39:20.609  1495  2983 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:39:20.609  1495  2983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:39:20.629  3588  4035 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 18:39:20.629  3588  4035 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jdm.a(PG:82)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jcs.o(PG:406)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jcn.a(PG:1379)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jcs.i(PG:143)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at hec.a(PG:42)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at hee.a(PG:102)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at czr.a(PG:65)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at kka.a(PG:108)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at czp.a(PG:19176)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at czp.a(PG:9081)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at czq.run(PG:1686)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:39:20.629  3588  4035 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jdj.a(PG:4091)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jdj.a(PG:1125)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jdm.a(PG:77)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	... 15 more
08-12 18:39:20.629  3588  4035 E HttpOperation: Caused by: faj: BadAuthentication
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at fal.a(PG:38)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	at jdj.a(PG:4089)
08-12 18:39:20.629  3588  4035 E HttpOperation: 	... 17 more
,08-12 18:39:20.629  3588  4035 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 18:39:20.629  3588  4035 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at hec.a(PG:42)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at hee.a(PG:102)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at czr.a(PG:65)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: ,	at kka.a(PG:108)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	... 15 more
08-12 18:39:20.629  3588  4035 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at fal.a(PG:38)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 18:39:20.629  3588  4035 E ExperimentLoader: 	... 17 more
,08-12 18:39:20.726   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 283771, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 18:39:30.624   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=322184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 18:39:37.091   876  2124 D NetlinkSocketObserver: NeighborEvent{elapsedMs=328650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 18:39:50.388  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:39:50.399  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:39:50.402  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 18:39:50.446  1495  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 18:39:50.446  1495  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 18:39:50.447  1495  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 18:39:50.447  1495  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 18:39:50.479  1495  1508 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 18:39:50.479  1495  1508 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 18:39:50.479  1495  1508 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 18:39:50.479  1495  1508 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 18:39:50.479  1495  1508 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 18:39:50.479  1495  1508 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 18:39:50.479  1495  1508 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 18:39:50.484  3545  3579 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 18:39:50.484  3545  3579 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 18:39:50.484  3545  3579 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 18:39:50.484  3545  3579 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 18:39:50.484  3545  3579 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 18:39:50.484  3545  3579 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 18:39:50.484  3545  3579 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 18:40:01.811  3911  3960 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 18:40:01.811  3911  3960 I jxcore-log: 
,08-12 18:40:02.417  4049  4049 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 18:40:02.422  4049  4049 D AndroidRuntime: CheckJNI is OFF
,08-12 18:40:02.457  4049  4049 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 18:40:02.498  4049  4049 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 18:40:02.518  4049  4049 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:40:02.528   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 18:40:02.529   876   889 I ActivityManager: Killing 3911:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 18:40:02.639   876   899 W PackageSettings: Skipping PackageSetting{e4febd3 com.example.hello/10273} due to missing metadata
,08-12 18:40:02.651   876  1424 D GraphicsStats: Buffer count: 2
08-12 18:40:02.651   876  1424 I WindowState: WIN DEATH: Window{9e94ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:40:02.652   876  1309 D WifiService: Client connection lost with reason: 4
,08-12 18:40:02.691   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 18:40:02.691   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 18:40:02.692   876   889 E ActivityManager: Failure starting process com.test.thalitest
08-12 18:40:02.692   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 18:40:02.692   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:02.692   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:02.692   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:02.692   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 18:40:02.693   876   889 I ActivityManager:   Force finishing activity ActivityRecord{eb1f390 u0 com.test.thalitest/.MainActivity t2}
,08-12 18:40:02.694   876   899 I art     : Starting a blocking GC Explicit
08-12 18:40:02.705   876  2077 W ActivityManager: Spurious death for ProcessRecord{9a05f98 0:com.test.thalitest/u0a0}, curProc for 3911: null
,08-12 18:40:02.735   876   899 I art     : Explicit concurrent mark sweep GC freed 24257(1675KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 728us total 40.722ms
,08-12 18:40:02.758   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 18:40:02.762  4049  4049 I art     : System.exit called, status: 0
,08-12 18:40:02.762  4049  4049 I AndroidRuntime: VM exiting with result code 0.
,08-12 18:40:02.767   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 18:40:02.786   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 18:40:02.791  2703  2703 D BluetoothMapAppObserver: onReceive
,08-12 18:40:02.792  2703  2703 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-12 18:40:02.792   876  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 18:40:02.794  1868  2260 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 18:40:02.798  1879  1879 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 18:40:02.803  3695  3695 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 18:40:02.817  1879  4060 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 18:40:02.819  1879  4060 I Decoder : createOrResetDecoder
,08-12 18:40:02.835  1947  1947 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 18:40:02.853  1708  4064 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 18:40:02.864  1495  1495 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-12 18:40:02.864  1495  1495 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-12 18:40:02.876   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 18:40:02.889  1495  1495 I ConfigService: onCreate
,08-12 18:40:02.898  1708  1729 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj68FC4D90C) - 
,08-12 18:40:02.898  1688  4067 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 18:40:02.898  1688  4067 D AccountUtils: Clearing selected account for com.test.thalitest
,08-12 18:40:02.902  1495  4068 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-12 18:40:02.906  1962  2052 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-12 18:40:02.906   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-12 18:40:02.907  1708  4064 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-12 18:40:02.907  1708  4064 I Process : Sending signal. PID: 1708 SIG: 9
,08-12 18:40:02.908   876   888 E PackageManager: Failed to write settings, restoring backup
08-12 18:40:02.908   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 18:40:02.908   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 18:40:02.908   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 18:40:02.908   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 18:40:02.908   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 18:40:02.908   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:02.908   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:02.908   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:40:02.915   876   889 E DropBoxManagerService: Can't write: system_server_wtf
08-12 18:40:02.915   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 18:40:02.915   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:40:02.915   876   889 E DropBoxManagerService: 	... 13 more
,08-12 18:40:02.919   876  1680 I ActivityManager: Start proc 4071:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-12 18:40:02.919  1962  2052 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 18:40:02.919  1962  2052 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1962
08-12 18:40:02.919  1962  2052 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:02.919  1962  2052 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:40:02.924   876   887 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 18:40:02.925   876  4079 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:40:02.925   876  4079 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:40:02.925   876  4079 E DropBoxManagerService: 	... 5 more
,08-12 18:40:02.928  1962  2052 I Process : Sending signal. PID: 1962 SIG: 9
,08-12 18:40:02.932  1879  4060 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 18:40:02.936  1688  4067 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-12 18:40:02.949  1688  4067 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:02.949  1688  4067 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:02.958  1688  4067 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:40:02.959  1688  4067 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-12 18:40:02.992   278   278 E lowmemorykiller: Error writing /proc/1708/oom_score_adj; errno=22
,08-12 18:40:03.000  1688  1688 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 18:40:03.000  1688  1688 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 18:40:03.002   278   278 E lowmemorykiller: Error writing /proc/1708/oom_score_adj; errno=22
,08-12 18:40:03.011  1688  1688 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 18:40:03.011  1688  1688 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 18:40:03.016   278   278 E lowmemorykiller: Error writing /proc/1708/oom_score_adj; errno=22
,08-12 18:40:03.018  1879  4060 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 18:40:03.023  1688  4086 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 18:40:03.024  1688  4086 E DriveAsyncService: disk I/O error (code 3850)
,08-12 18:40:03.024  1688  4086 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:40:03.024  1688  4086 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:40:03.025  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-12 18:40:03.025  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 18:40:03.030  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-12 18:40:03.030  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-12 18:40:03.040   278   278 E lowmemorykiller: Error writing /proc/1962/oom_score_adj; errno=22
,08-12 18:40:03.040   876  1424 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
,08-12 18:40:03.041   876  1424 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-12 18:40:03.041   876  1424 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	,at android.os.BinderProxy.transactNative(Native Method)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-12 18:40:03.041   876  1424 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 18:40:03.044  1688  4094 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 18:40:03.046  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-12 18:40:03.046  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-12 18:40:03.049  1688  4087 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:03.049  1688  4087 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:03.049  1688  4087 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:03.051  1879  4060 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 18:40:03.051  1879  4060 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 18:40:03.052  1879  4060 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 18:40:03.052  1879  4060 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 18:40:03.052  1879  4060 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 18:40:03.059  1879  4060 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-12 18:40:03.065  1688  4087 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-12 18:40:03.066  1688  4087 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-12 18:40:03.066  1688  4087 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-12 18:40:03.068   876  2076 D GraphicsStats: Buffer count: 1
08-12 18:40:03.068   876  1975 I WindowState: WIN DEATH: Window{b45ea6b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-12 18:40:03.072  1688  4087 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-12 18:40:03.073   876  1424 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-12 18:40:03.083  1688  4094 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 18:40:03.083  1688  4094 E AndroidRuntime: Process: com.google.android.gms, PID: 1688
08-12 18:40:03.083  1688  4094 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 18:40:03.083  1688  4094 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-12 18:40:03.086  1688  4087 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-12 18:40:03.086   876  1424 I ActivityManager: Start proc 4096:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-12 18:40:03.089   278   278 E lowmemorykiller: Error writing /proc/1708/oom_score_adj; errno=22
08-12 18:40:03.090   876  2076 W ActivityManager: Spurious death for ProcessRecord{d69af7c 4096:com.google.android.googlequicksearchbox/u0a28}, curProc for 1962: null
08-12 18:40:03.093  2015  4092 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 18:40:03.094   876  4104 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:40:03.094   876  4104 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:40:03.094   876  4104 E DropBoxManagerService: 	... 5 more
08-12 18:40:03.115   278   278 E lowmemorykiller: Error writing /proc/1708/oom_score_adj; errno=22
08-12 18:40:03.119   278   278 E lowmemorykiller: Error writing /proc/1708/oom_score_adj; errno=22
08-12 18:40:03.119  1688  4094 I Process : Sending signal. PID: 1688 SIG: 9
,08-12 18:40:03.131  2015  4092 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 18:40:03.140   876  2076 I ActivityManager: Delaying start of: ServiceRecord{d54e491 u0 com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService}
08-12 18:40:03.148  2015  4092 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-12 18:40:03.148  2015  4092 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 18:40:03.148  2015  4092 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2015
08-12 18:40:03.148  2015  4092 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:03.148  2015  4092 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:03.150   876  1975 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 18:40:03.150   876  1975 I ActivityManager: Killing 2015:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-12 18:40:03.153   876  4110 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:40:03.153   876  4110 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:40:03.153   876  4110 E DropBoxManagerService: 	... 5 more
,08-12 18:40:03.190  4096  4096 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 18:40:03.190  4096  4096 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 18:40:03.190  4096  4096 D AndroidRuntime: Shutting down VM
,08-12 18:40:03.203   876  1992 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3efaff6)
,08-12 18:40:03.204   876  1310 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
08-12 18:40:03.207   876  1310 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 18:40:03.223   876  1309 D WifiService: Client connection lost with reason: 4
,08-12 18:40:03.226   278   278 E lowmemorykiller: Error opening /proc/1688/oom_score_adj; errno=2
08-12 18:40:03.229   876  1975 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-12 18:40:03.233   876  1391 I ActivityManager: Process com.google.android.gms (pid 1688) has died
,08-12 18:40:03.234   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
08-12 18:40:03.234   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
08-12 18:40:03.234   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,08-12 18:40:03.234   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 10999ms
08-12 18:40:03.235   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
08-12 18:40:03.235   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
08-12 18:40:03.235   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 20999ms
,08-12 18:40:03.235   876  1391 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20999ms
,08-12 18:40:03.237   876  1961 W ActivityManager: Spurious death for ProcessRecord{25756b8 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 2015: null
,08-12 18:40:03.239   876   894 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
,08-12 18:40:03.240   876   894 W DisplayManagerService: Failed to notify process 1708 that displays changed, assuming it died.
08-12 18:40:03.240   876   894 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 18:40:03.240   876   894 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 18:40:03.258   876  1424 I ActivityManager: Start proc 4114:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-12 18:40:03.260  4096  4096 E AndroidRuntime: FATAL EXCEPTION: main
08-12 18:40:03.260  4096  4096 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4096
08-12 18:40:03.260  4096  4096 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 18:40:03.260  4096  4096 E AndroidRuntime: 	... 10 more
08-12 18:40:03.262   876  1680 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 18:40:03.264  4096  4096 I Process : Sending signal. PID: 4096 SIG: 9
08-12 18:40:03.265   876  4120 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:40:03.265   876  4120 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 18:40:03.265   876  4120 E DropBoxManagerService: 	... 5 more
08-12 18:40:03.275   876  2076 I ActivityManager: Start proc 4126:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-12 18:40:03.282   876  2077 I ActivityManager: Process android.process.acore (pid 1708) has died
,08-12 18:40:03.282   876  2077 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 10952ms
,08-12 18:40:03.290   876  1987 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4096) has died
,08-12 18:40:03.291   876  1987 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
