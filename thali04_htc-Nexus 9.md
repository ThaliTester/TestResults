#### Test 75789268d2ecd3a_thali04_htc-Nexus 9 Logs


```
--------- beginning of system
07-08 14:02:36.011   590   630 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-08 14:02:36.015   590   630 I PowerManagerService: Sleeping (uid 1000)...
--------- beginning of main
07-08 14:02:36.043   992   992 I Keyboard.Facilitator: onFinishInput()
07-08 14:02:36.065  1097  1110 W SearchService: Abort, client detached.
07-08 14:02:36.094  1097  1097 I HotwordDetector: Closing mic
07-08 14:02:36.095  1097  1307 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ec2a9e6
07-08 14:02:36.124   222   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-08 14:02:36.127  1097  1315 I MicroRecognitionRnrImpl: Detection finished
07-08 14:02:36.127  1097  1309 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-08 14:02:36.141   590  1308 I ActivityManager: Killing 1583:com.google.android.talk/u0a56 (adj 15): empty #17
07-08 14:02:36.165   170  1292 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (111 us)
07-08 14:02:36.172   590  1308 I ActivityManager: Killing 2384:com.google.android.apps.photos/u0a66 (adj 15): empty #18
07-08 14:02:36.765   590   630 V KeyguardServiceDelegate: onScreenTurnedOff()
07-08 14:02:36.779   590   630 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-08 14:02:36.782   590   628 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-08 14:02:36.782   170   170 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x556abc1430
07-08 14:02:36.782   170   170 D hwcomposer: hwc_blank: display 0: blank
07-08 14:02:36.783   170   170 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
07-08 14:02:37.099   590   681 D SurfaceControl: Excessive delay in setPowerMode(): 317ms
07-08 14:02:37.149   590   662 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:02:37.174   590   662 E native  : do suspend false
07-08 14:02:37.192   590   662 D WifiConfigStore: No blacklist allowed without epno enabled
07-08 14:02:37.207   590   662 D WifiConfigStore: Retrieve network priorities after PNO.
07-08 14:02:37.210   590   662 E native  : do suspend true
,07-08 14:02:37.659   590   662 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
07-08 14:02:38.003  2757  2757 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:02:38.010  2757  2757 D AndroidRuntime: CheckJNI is OFF
07-08 14:02:38.077  2757  2757 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:02:38.148  2757  2757 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:02:38.201  2757  2757 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-08 14:02:38.214   590  1959 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-08 14:02:38.255   590  1959 I ActivityManager: Start proc 2766:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-08 14:02:38.262  2757  2757 D AndroidRuntime: Shutting down VM
07-08 14:02:38.406  2766  2766 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-08 14:02:38.554  2766  2766 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-08 14:02:38.588  2766  2766 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 6132-6152)
,07-08 14:02:38.589  2766  2766 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:02:38.655  2766  2766 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7cb144f}
,07-08 14:02:38.656  2766  2766 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:02:38.658  2766  2766 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-08 14:02:38.671  2766  2766 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-08 14:02:38.675  2766  2766 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-08 14:02:38.739  2766  2766 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-08 14:02:38.761  2766  2766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:02:38.762  2766  2766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:02:38.827   590   623 W ActivityManager: Activity pause timeout for ActivityRecord{45a782d u0 com.test.thalitest/.MainActivity t62}
,07-08 14:02:39.127   590   627 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f6c0c8:true
,07-08 14:02:39.227  2766  2766 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-08 14:02:39.241  1010  1540 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-08 14:02:39.255  2766  2766 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,07-08 14:02:39.338  2766  2804 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-08 14:02:39.354  2766  2791 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-08 14:02:39.405  2766  2804 I OpenGLRenderer: Initialized EGL, version 1.4
,07-08 14:02:39.573   590   628 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s247ms (total +1s336ms)
,07-08 14:02:39.578   992   992 I Keyboard.Facilitator: onFinishInput()
,07-08 14:02:39.663  2766  2766 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2766
,07-08 14:02:39.846  2766  2766 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-08 14:02:40.087  2766  2806 D jxcore_app_log: JniHelper::setJavaVM(0xaaf287b8), pthread_self() = -558323408
,07-08 14:02:40.094  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-08 14:02:40.094  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-08 14:02:40.094  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-08 14:02:40.094  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-08 14:02:40.094  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-08 14:02:40.095  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28362d2 added. We now have 1 listener(s)
,07-08 14:02:40.100  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
,07-08 14:02:40.104  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-08 14:02:40.105  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-08 14:02:40.106  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-08 14:02:40.111  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b053e59 added. We now have 1 listener(s)
07-08 14:02:40.112  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:02:40.116   590   663 D WifiService: New client listening to asynchronous messages
,07-08 14:02:40.119  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-08 14:02:40.120  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-08 14:02:40.121  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-08 14:02:40.121  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-08 14:02:40.121  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-08 14:02:40.127  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:02:40.128  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:40.136  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:02:40.136  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-08 14:02:40.136  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:02:40.139  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:40.142  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:40.143  2766  2806 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:02:40.188  2766  2766 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-08 14:02:41.026  2766  2813 W jxcore-log: Initializing JXcore engine
,07-08 14:02:41.026  2766  2813 W jxcore-log: JXcore engine is ready
,07-08 14:02:41.143  2813  2813 W Thread-58: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=7484 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-08 14:02:41.143  2813  2813 W Thread-58: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11308]" dev="sockfs" ino=11308 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-08 14:02:41.143  2813  2813 W Thread-58: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-08 14:02:41.143  2813  2813 W Thread-58: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20681]" dev="sockfs" ino=20681 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-08 14:02:41.169  2766  2813 W jxcore-log: Starting JXcore engine
,07-08 14:02:41.182   590  2227 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158746, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:02:41.439  2766  2813 W jxcore-log: Platform android
07-08 14:02:41.439  2766  2813 W jxcore-log: 
,07-08 14:02:41.439  2766  2813 W jxcore-log: Process ARCH arm
07-08 14:02:41.439  2766  2813 W jxcore-log: 
,07-08 14:02:41.740  2766  2813 I jxcore-log: JXcore Cordova bridge is ready!
07-08 14:02:41.740  2766  2813 I jxcore-log: 
,07-08 14:02:41.740  2766  2813 W jxcore-log: JXcore engine is started
,07-08 14:02:41.747  2766  2806 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-08 14:02:41.750  2766  2766 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-08 14:02:45.023   590   662 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 12 -> obsolete
,07-08 14:02:46.316  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:02:46.326  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:02:46.330  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:02:46.358  1078  1090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-08 14:02:46.358  1078  1090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-08 14:02:46.358  1078  1090 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:02:46.358  1078  1090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:02:46.416  2465  2465 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-08 14:02:46.417  2465  2465 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-08 14:02:46.417  2465  2465 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-08 14:02:50.256  2716  2822 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:02:50.280  2716  2823 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:02:50.317  1078  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:02:50.317  1078  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:02:50.318  1078  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:02:50.318  1078  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:02:50.372  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:02:50.372  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:02:50.372  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:02:50.372  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:02:50.392  2716  2823 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:02:50.394  2716  2822 E BooksSync: Soft error
07-08 14:02:50.394  2716  2822 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:02:50.394  2716  2822 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:02:50.394  2716  2822 E BooksSync: Sync error
07-08 14:02:50.394  2716  2822 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:02:50.394  2716  2822 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:02:50.394  2716  2822 I BooksSync: Finished books sync
,07-08 14:02:50.407   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 167748, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:02:53.453  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-08 14:02:53.453  2766  2813 I jxcore-log: 
,07-08 14:02:53.457  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-08 14:02:53.457  2766  2813 I jxcore-log: 
,07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:53.464  2766  2813 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:53.466  2766  2813 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:02:53.469  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-08 14:02:53.469  2766  2813 I jxcore-log: 
,07-08 14:02:53.472  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-08 14:02:53.472  2766  2813 I jxcore-log: 
,07-08 14:02:53.849  2766  2813 I jxcore-log: Unit Test app is loaded
07-08 14:02:53.849  2766  2813 I jxcore-log: 
,07-08 14:02:53.863  2766  2766 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-08 14:02:53.864  2766  2806 D JX-Cordova: Running tests
,07-08 14:02:53.871  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:02:53.871  2766  2813 I jxcore-log: 
,07-08 14:02:53.878  2766  2813 I jxcore-log: My device name is: htc-Nexus 9
07-08 14:02:53.878  2766  2813 I jxcore-log: 
,07-08 14:02:54.062  2766  2806 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-08 14:02:54.062  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:02:54.062  2766  2806 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-08 14:02:54.062  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-08 14:02:54.062  2766  2806 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-08 14:02:54.063  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-08 14:02:54.064  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-08 14:02:54.064  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-08 14:02:54.065  2766  2806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-08 14:02:54.065  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-08 14:02:54.065  2766  2806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-08 14:02:54.065  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-08 14:02:54.065  2766  2806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-08 14:02:54.065  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-08 14:02:54.066  2766  2806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-08 14:02:54.066  2766  2806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-08 14:02:54.067  2766  2806 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,07-08 14:02:54.067  2766  2806 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-08 14:02:54.067  2766  2806 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-08 14:02:54.067  2766  2806 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-08 14:02:54.068  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:54.068  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d131af added. We now have 2 listener(s)
07-08 14:02:54.068  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:54.072  2766  2806 D BluetoothAdapter: enable(): BT is already enabled..!
,07-08 14:02:54.076   590   745 D WifiService: setWifiEnabled: true pid=2766, uid=10000
07-08 14:02:54.076   590   745 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:02:54.078  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:54.078  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98fa9bc added. We now have 3 listener(s)
,07-08 14:02:54.078  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:54.085  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:02:54.085  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4abd45 added. We now have 4 listener(s)
07-08 14:02:54.085  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:54.088  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:02:54.088  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdbcc9a added. We now have 5 listener(s)
07-08 14:02:54.088  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:02:54.091   590  1984 D WifiService: setWifiEnabled: false pid=2766, uid=10000
,07-08 14:02:54.091   590  1984 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:02:54.107   590   662 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-08 14:02:54.107   590   662 D IpReachabilityMonitor: clear: iface{wlan0/6}, v{4}, ntable=[]
,07-08 14:02:54.108   590   662 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:02:54.108   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:02:54.111  1620  1666 D BluetoothAdapterState: Current state: ON, message: 23
,07-08 14:02:54.112  1620  1666 D BluetoothAdapterProperties: Setting state to 13
,07-08 14:02:54.113  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:02:54.112  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-08 14:02:54.124  1620  1620 I BtOppRfcommListener: stopping Accept Thread
,07-08 14:02:54.125  1620  2193 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:54.125  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:54.126  1620  2193 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-08 14:02:54.128   590   662 E native  : do suspend true
07-08 14:02:54.130  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:54.131  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:02:54.133  1620  1666 D BluetoothAdapterProperties: onBluetoothDisable()
,07-08 14:02:54.136  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:54.138  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:54.140   590  2228 D DhcpClient: Clearing IP address
,07-08 14:02:54.141   218   621 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:02:54.143  1620  1666 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:02:54.158   590   623 I ActivityManager: Start proc 2826:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-08 14:02:54.159  1620  1670 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:54.160  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:02:54.165  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:02:54.167  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-08 14:02:54.170  1620  1620 D HeadsetService: Received stop request...Stopping profile...
,07-08 14:02:54.173  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:54.183   590   590 D BluetoothHeadset: Proxy object disconnected
,07-08 14:02:54.184   738   753 D BluetoothHeadset: Proxy object disconnected
,07-08 14:02:54.182   218   621 D CommandListener: Setting iface cfg
,07-08 14:02:54.185  1620  1620 D A2dpService: Received stop request...Stopping profile...
,07-08 14:02:54.186  1620  1815 D A2dpStateMachine: Exit Disconnected: -1
,07-08 14:02:54.199   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-08 14:02:54.200   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,07-08 14:02:54.209   590  2229 D DhcpClient: Receive thread stopped
,07-08 14:02:54.223   590   662 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-08 14:02:54.228  1620  1620 D HidService: Received stop request...Stopping profile...
,07-08 14:02:54.228  1620  1620 D HidService: Stopping Bluetooth HidService
,07-08 14:02:54.233   590   664 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-08 14:02:54.238  1078  2273 V NativeCrypto: Read error: ssl=0x55a23f3390: I/O error during system call, Connection timed out
,07-08 14:02:54.243  1620  1620 D HealthService: Received stop request...Stopping profile...
07-08 14:02:54.248  1620  1620 D PanService: Received stop request...Stopping profile...
07-08 14:02:54.253  1620  1620 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:54.253  1620  1620 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:54.254  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:02:54.254  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:54.256   590   662 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:02:54.256   590   662 E native  : do suspend true
,07-08 14:02:54.273  1620  1620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:02:54.273  1620  1670 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
,07-08 14:02:54.273  1620  1620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-08 14:02:54.277  1620  1620 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:54.277  1620  1620 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:54.277  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:54.277  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:54.286  1620  1775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:54.290  1620  1775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:02:54.291  1620  1670 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-08 14:02:54.292  1620  1620 V BluetoothAdapterState: isTurningOff()=true
07-08 14:02:54.292  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:54.293  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:02:54.293  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:54.293  1620  1620 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-08 14:02:54.293  1620  1620 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,07-08 14:02:54.293  1620  1620 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:54.294  1620  1620 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:54.294  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:02:54.294  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:02:54.294  1620  1620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:02:54.294  1620  1670 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
,07-08 14:02:54.294  1620  1775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-08 14:02:54.295  1620  1775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-08 14:02:54.296  1620  1775 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-08 14:02:54.296  1620  1775 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-08 14:02:54.296  1620  1775 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-08 14:02:54.296  1620  1775 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-08 14:02:54.294  1620  1670 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
,07-08 14:02:54.297  1620  1620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-08 14:02:54.298  1620  1620 V BluetoothAdapterState: isTurningOff()=true
,07-08 14:02:54.298  1620  1620 V BluetoothAdapterState: isTurningOn()=false
07-08 14:02:54.298  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:02:54.298  1620  1620 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:02:54.298  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:02:54.298  1620  1666 D BluetoothAdapterProperties: Setting state to 15
07-08 14:02:54.298  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-08 14:02:54.299   590   627 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-08 14:02:54.299   590   627 D BluetoothHeadset: Proxy object disconnected
,07-08 14:02:54.300  1620  1666 I BluetoothAdapterState: Entering BleOnState
,07-08 14:02:54.301   738  2836 D BluetoothPan: onBluetoothStateChange on: false
,07-08 14:02:54.301   590   627 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-08 14:02:54.302   738  2836 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:02:54.303   738  2836 E BluetoothMap: 
07-08 14:02:54.303   738  2836 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@c91bd7d
07-08 14:02:54.303   738  2836 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-08 14:02:54.303   738  2836 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-08 14:02:54.303   738  2836 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-08 14:02:54.303   738  2836 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-08 14:02:54.303   738  2836 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-08 14:02:54.303   738  2836 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:02:54.303   738  2836 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:02:54.304   738  2836 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:54.304   738  2836 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:02:54.306  1620  1670 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-08 14:02:54.310  1078  2273 V NativeCrypto: SSL shutdown failed: ssl=0x55a23f3390: I/O error during system call, Broken pipe
,07-08 14:02:54.311  1620  1620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-08 14:02:54.311  1620  1620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-08 14:02:54.312   738  2836 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-08 14:02:54.322   590   627 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-08 14:02:54.323   590   627 D BluetoothHeadset: Proxy object disconnected
,07-08 14:02:54.323   590   627 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:02:54.323  1036  1139 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:02:54.324  1036  1139 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:54.325  1620  1666 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-08 14:02:54.326  1620  1666 D BluetoothAdapterProperties: Setting state to 16
07-08 14:02:54.326  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-08 14:02:54.331  1620  1666 D BluetoothAdapterProperties: onBleDisable
07-08 14:02:54.334  1620  1667 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:02:54.348  1620  1775 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-08 14:02:54.348  1620  1775 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-08 14:02:54.356  1620  1670 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:54.359  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:54.360  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:54.362  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:54.363  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:54.364  1620  1666 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:02:54.473   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:02:54.534   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-08 14:02:54.535   590   664 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-08 14:02:54.536   590   664 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-08 14:02:54.538   218   621 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:54.545  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:54.548  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:54.558  1620  1775 W bt_btif : ag scb idx 1 not allocated
07-08 14:02:54.558  1620  1775 E bt_btif : BTA AG is already disabled, ignoring ...
07-08 14:02:54.559  1620  1670 I bt_hci  : shut_down
,07-08 14:02:54.570  1620  1675 D bt_hwcfg: hw_epilog_process
07-08 14:02:54.570  1620  1675 I bt_vendor: low_power_mode_cb
07-08 14:02:54.593  1620  1675 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-08 14:02:54.594  1620  1675 I bt_vendor: epilog_cb
07-08 14:02:54.594  1620  1675 I bt_hci  : epilog_finished_callback
07-08 14:02:54.596  1620  1670 I bt_hci_h4: hal_close
07-08 14:02:54.597  1620  1670 I bt_userial_vendor: device fd = 49 close
,07-08 14:02:54.703   218   621 E Netd    : netlink response contains error (No such file or directory)
07-08 14:02:54.706   590   662 D DhcpClient: doQuit
07-08 14:02:54.707   590   662 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:02:54.707   590  2228 D DhcpClient: onQuitting
,07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:54.715  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:54.717  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:02:54.719  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:02:54.720  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:02:54.722  1075  1075 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,07-08 14:02:54.730  1036  1137 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:54.730   590   590 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:54.731   590   590 D BluetoothHeadset: Proxy object disconnected
07-08 14:02:54.732   738   738 D HeadsetProfile: Bluetooth service disconnected
07-08 14:02:54.732   590   590 D RttService: SCAN_AVAILABLE : 1
,07-08 14:02:54.732   590   677 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-08 14:02:54.734   590   627 D Tethering: MasterInitialState.processMessage what=3
07-08 14:02:54.740  1075  1075 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
07-08 14:02:54.747  1075  1075 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-08 14:02:54.780  1075  1075 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-08 14:02:54.792  1075  1075 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-08 14:02:54.834  2826  2826 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
07-08 14:02:54.836   590   600 W art     : Suspending all threads took: 8.298ms
07-08 14:02:54.856  1097  1097 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-08 14:02:54.878   590   600 I art     : Background partial concurrent mark sweep GC freed 49685(3MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 17MB/26MB, paused 11.757ms total 561.576ms
07-08 14:02:54.901   590   662 D wifi    : In wifi stop Hal
07-08 14:02:54.901   590   662 D wifi    : halHandle = 0x55a23f0240, mVM = 0x55a2049c30, mCls = 0x100ad2
07-08 14:02:54.902   590  1071 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-08 14:02:54.902   590  1071 D WifiHAL : Got a signal to exit!!!
07-08 14:02:54.903   590  1071 I WifiHAL : Exit wifi_event_loop
,07-08 14:02:54.905   590   662 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 9
07-08 14:02:54.905  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:54.905   590   662 E WifiHAL : Event processing terminated
07-08 14:02:54.905   590   662 D wifi    : In wifi cleaned up handler
07-08 14:02:54.905   590   662 I WifiHAL : Internal cleanup completed
07-08 14:02:54.907  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:54.973  2826  2826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:54.983  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:55.002   590   611 I ActivityManager: Start proc 2851:com.google.android.apps.maps/u0a60 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-08 14:02:55.009  1620  1667 D bt_stack_manager: event_shut_down_stack finished.
,07-08 14:02:55.009  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
07-08 14:02:55.012  1620  1666 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-08 14:02:55.012  1620  1620 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:02:55.013  1620  1620 D BtGatt.GattService: Received stop request...Stopping profile...
,07-08 14:02:55.013  1620  1620 D BtGatt.GattService: stop()
,07-08 14:02:55.013  1620  1620 D BtGatt.AdvertiseManager: advertise clients cleared
,07-08 14:02:55.014  1620  1620 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:02:55.014  1620  1620 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:02:55.014  1620  1620 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:02:55.015  1620  1620 V BluetoothAdapterState: isBleTurningOff()=true
,07-08 14:02:55.015  1620  1666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-08 14:02:55.015  1620  1666 D BluetoothAdapterProperties: Setting state to 10
,07-08 14:02:55.015  1620  1666 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-08 14:02:55.016  1620  1666 I BluetoothAdapterState: Entering OffState
,07-08 14:02:55.017   590   627 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,07-08 14:02:55.026   590  1071 D wifi    : set interface wlan0 flags (DOWN)
,07-08 14:02:55.027   590   662 D WifiNative-HAL: HAL event thread stopped successfully
,07-08 14:02:55.071  1620  1620 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-08 14:02:55.072  1620  1620 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,07-08 14:02:55.090  1620  1667 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-08 14:02:55.092  1620  1620 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-08 14:02:55.094  1620  1667 D bt_stack_manager: event_clean_up_stack finished.
,07-08 14:02:55.107   590   627 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c28c6a3:true
,07-08 14:02:55.110  1620  1620 I art     : System.exit called, status: 0
,07-08 14:02:55.110  1620  1620 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:02:55.169  1010  1269 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:02:55.170  2826  2826 D LocalBluetoothProfileManager: Adding local MAP profile
,07-08 14:02:55.177  2826  2826 D BluetoothMap: Create BluetoothMap proxy object
,07-08 14:02:55.179   590  1984 I ActivityManager: Process com.android.bluetooth (pid 1620) has died
,07-08 14:02:55.183  2826  2826 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-08 14:02:55.188  2851  2851 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,07-08 14:02:55.192  2826  2826 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-08 14:02:55.218  2826  2826 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:55.233   590  1308 I ActivityManager: Killing 2487:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,07-08 14:02:55.457  2851  2851 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.457  2851  2851 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.457  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.458  2851  2851 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.458  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.459  2851  2851 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.e.b(PG:170)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.459  2851  2851 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.k.d(PG:583)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.e.b(PG:170)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.459  2851  2851 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.459  2851  2851 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.File.exists(File.java:361)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.459  2851  2851 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-08 14:02:55.459  2851  2851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-08 14:02:55.467  2826  2826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:02:55.492   590   958 I ActivityManager: Start proc 2879:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,07-08 14:02:55.519  2826  2826 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:02:55.543   590   610 I ActivityManager: Killing 2514:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-08 14:02:55.696  2879  2879 D AdapterServiceConfig: Adding HeadsetService
,07-08 14:02:55.696  2879  2879 D AdapterServiceConfig: Adding A2dpService
07-08 14:02:55.696  2879  2879 D AdapterServiceConfig: Adding HidService
,07-08 14:02:55.697  2879  2879 D AdapterServiceConfig: Adding HealthService
07-08 14:02:55.697  2879  2879 D AdapterServiceConfig: Adding PanService
07-08 14:02:55.697  2879  2879 D AdapterServiceConfig: Adding GattService
07-08 14:02:55.700   590  1959 I ActivityManager: Killing 1635:com.android.providers.calendar/u0a2 (adj 15): empty #17
,07-08 14:02:55.729  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:02:55.753  1171  1171 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-08 14:02:55.763  1171  2248 I iu.UploadsManager: num queued entries: 0
,07-08 14:02:55.764  1171  2248 I iu.UploadsManager: num updated entries: 0
07-08 14:02:55.765  1171  2248 I iu.SyncManager: NEXT; no task
,07-08 14:02:55.770  1171  1171 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:02:55.773  1171  1171 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-08 14:02:55.786   590   958 I ActivityManager: Start proc 2893:com.android.chrome/u0a34 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-08 14:02:55.997   590   611 I ActivityManager: Start proc 2907:com.google.android.talk/u0a56 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,07-08 14:02:55.999   590   611 I ActivityManager: Killing 2565:com.android.defcontainer/u0a4 (adj 15): empty #17
,07-08 14:02:56.102  2907  2907 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-08 14:02:56.613  2851  2870 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-08 14:02:56.680  2907  2926 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-08 14:02:56.680  2907  2926 I Babel_SMS: MmsConfig.loadMmsSettings
,07-08 14:02:56.695  2907  2926 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=, mUaProfUrl=
,07-08 14:02:56.695  2907  2926 I Babel_SMS: MmsConfig.loadFromDatabase
,07-08 14:02:56.738  2851  2860 W art     : Suspending all threads took: 92.986ms
,07-08 14:02:56.760  2907  2926 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-08 14:02:56.760  2907  2926 I Babel_SMS: MmsConfig.loadFromResources
,07-08 14:02:56.771  2907  2926 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-08 14:02:56.772  2907  2926 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=Hangouts/4.1.102314611, mUaProfUrl=https://ssl.gstatic.com/android/hangouts/hangouts_mms_ua_profile.xml
,07-08 14:02:56.831  2907  2907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:02:56.842  2907  2907 I Babel_Crash: startup - clean
,07-08 14:02:56.956   590   958 I ActivityManager: Start proc 2929:com.google.android.apps.magazines/u0a62 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-08 14:02:57.067   590   627 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f08b18:true
,07-08 14:02:57.143  2929  2929 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm64
,07-08 14:02:57.213  2907  2907 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-08 14:02:57.267  2907  2907 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-08 14:02:57.299  2907  2907 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8,
,07-08 14:02:57.312  2907  2907 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-08 14:02:57.319  2907  2907 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-08 14:02:57.328  2907  2907 W VideoCapabilities: Unrecognized level 0 for video/x-vnd.on2.vp8
,07-08 14:02:57.346  2907  2907 I vclib   : onServiceConnected
,07-08 14:02:57.351  2907  2943 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-08 14:02:57.408  2929  2929 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-08 14:02:57.408  2929  2929 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:02:57.408  2929  2929 I GAv4    :   adb logcat -s GAv4
,07-08 14:02:57.430  2929  2929 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:57.441  2929  2929 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:57.478  2929  2947 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:02:57.796  2929  2929 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-08 14:02:57.899  2929  2929 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm64
,07-08 14:02:57.912  2929  2929 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5472-5476)
,07-08 14:02:57.916  2929  2929 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:02:57.940  2929  2929 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e7d9ef}
,07-08 14:02:57.944  2929  2929 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-08 14:02:57.944  2929  2929 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-08 14:02:57.955  2929  2929 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-08 14:02:57.969  2929  2929 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-08 14:02:58.062  2929  2929 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-08 14:02:58.073  2929  2929 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:02:58.073  2929  2929 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-08 14:02:58.288  2929  2929 I NSApplication: Starting up...
,07-08 14:02:58.311  2929  2976 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-08 14:02:58.319   590   745 I ActivityManager: Start proc 2981:com.google.android.apps.photos/u0a66 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-08 14:02:58.322   590   745 I ActivityManager: Killing 2446:android.process.acore/u0a3 (adj 15): empty #17
,07-08 14:02:58.441  2981  2981 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-08 14:02:58.698   590  1959 I ActivityManager: Killing 2617:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,07-08 14:02:59.140   590  1043 D WifiService: setWifiEnabled: true pid=2766, uid=10000
,07-08 14:02:59.140   590  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-08 14:02:59.144   218   621 D SoftapController: Softap fwReload - Ok
07-08 14:02:59.146   218   621 D CommandListener: Setting iface cfg
07-08 14:02:59.146   218   621 D CommandListener: Trying to bring down wlan0
07-08 14:02:59.147   218   621 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:02:59.150   590   662 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:02:59.744  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-08 14:02:59.744  2766  2813 I jxcore-log: 
,07-08 14:02:59.818   590   662 D wifi    : set interface wlan0 flags (UP)
,07-08 14:02:59.819   590   662 I WifiHAL : Initializing wifi
07-08 14:02:59.820   590   662 I WifiHAL : Creating socket
07-08 14:02:59.823   590   662 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-08 14:02:59.823   590   662 D wifi    : Did set static halHandle = 0x55a254eb00
07-08 14:02:59.823   590   662 D wifi    : halHandle = 0x55a254eb00, mVM = 0x55a2049c30, mCls = 0x20191e
07-08 14:02:59.824   590   662 D wifi    : array field set
07-08 14:02:59.824   590   662 I WifiNative-HAL: interface[0] = wlan0
07-08 14:02:59.833  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:02:59.833   590   662 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-08 14:02:59.834   590   662 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-08 14:02:59.835  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:02:59.839   590  2999 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=367795694336
07-08 14:02:59.840   590  2999 D wifi    : waitForHalEvents called, vm = 0x55a2049c30, obj = 0x20191e, env = 0x55a284e210
,07-08 14:02:59.936  3000  3000 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-08 14:03:00.044  3000  3000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:03:00.086  3000  3000 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-08 14:03:00.087  3000  3000 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-08 14:03:00.267  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-08 14:03:00.267  2766  2813 I jxcore-log: 
,07-08 14:03:00.293  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-08 14:03:00.293  2766  2813 I jxcore-log: 
,07-08 14:03:00.299  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-08 14:03:00.299  2766  2813 I jxcore-log: 
,07-08 14:03:00.317  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-08 14:03:00.317  2766  2813 I jxcore-log: 
,07-08 14:03:00.322  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-08 14:03:00.322  2766  2813 I jxcore-log: 
,07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:00.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:00.845  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:00.845  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:00.846  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:00.848   590   662 D WifiConfigStore: Loading config and enabling all networks 
,07-08 14:03:00.864   590   662 D WifiConfigStore: loaded 0 passpoint configs,
,07-08 14:03:00.867   590   662 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-08 14:03:00.868   590   662 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-08 14:03:00.869   590   662 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-08 14:03:00.871   590   662 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-08 14:03:00.871   590   662 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-08 14:03:00.871   590   662 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-08 14:03:00.880   590   662 D WifiNative-HAL: Setting external_sim to 1
,07-08 14:03:00.880   590   662 D wifi    : setting dfs flag to true, 0x55a284e1d0
,07-08 14:03:00.881   590   662 D WifiStateMachine: Setting OUI to DA-A1-19
,07-08 14:03:00.881   590   662 D wifi    : setting scan oui 0x55a284e1d0
,07-08 14:03:00.881   590   662 D WifiHAL : Sending mac address OUI
,07-08 14:03:00.883  2907  2907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:03:00.903   590   662 E native  : do suspend true
,07-08 14:03:00.909   590   662 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-08 14:03:00.909   590   662 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:03:00.910   218   621 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-08 14:03:00.911   590   590 D RttService: SCAN_AVAILABLE : 3
,07-08 14:03:00.911   590   677 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-08 14:03:00.912   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:00.913   590   661 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '60 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 60 Failed to set address (No such device)'
,07-08 14:03:00.913   590   661 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-08 14:03:00.928   590   661 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:03:00.929   590   661 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-08 14:03:00.965   590   625 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178529 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,07-08 14:03:01.616   590  1308 I ActivityManager: Killing 2631:com.android.musicfx/u0a14 (adj 15): empty #17
,07-08 14:03:02.538  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-08 14:03:02.538  2766  2813 I jxcore-log: 
,07-08 14:03:02.553  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-08 14:03:02.553  2766  2813 I jxcore-log: 
,07-08 14:03:02.563  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-08 14:03:02.563  2766  2813 I jxcore-log: 
,07-08 14:03:02.733  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-08 14:03:02.733  2766  2813 I jxcore-log: 
,07-08 14:03:02.816  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-08 14:03:02.816  2766  2813 I jxcore-log: 
,07-08 14:03:02.878  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-08 14:03:02.878  2766  2813 I jxcore-log: 
,07-08 14:03:02.886  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-08 14:03:02.886  2766  2813 I jxcore-log: 
,07-08 14:03:03.088  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-08 14:03:03.088  2766  2813 I jxcore-log: 
,07-08 14:03:03.111  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-08 14:03:03.111  2766  2813 I jxcore-log: 
,07-08 14:03:03.117  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-08 14:03:03.117  2766  2813 I jxcore-log: 
,07-08 14:03:03.125  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-08 14:03:03.125  2766  2813 I jxcore-log: 
,07-08 14:03:03.142  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-08 14:03:03.142  2766  2813 I jxcore-log: 
,07-08 14:03:03.164  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-08 14:03:03.164  2766  2813 I jxcore-log: 
,07-08 14:03:03.250  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-08 14:03:03.250  2766  2813 I jxcore-log: 
,07-08 14:03:03.257  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-08 14:03:03.257  2766  2813 I jxcore-log: 
,07-08 14:03:03.283  2766  2813 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-08 14:03:03.283  2766  2813 I jxcore-log: 
,07-08 14:03:03.294  2766  2813 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-08 14:03:03.297  2766  2813 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-08 14:03:03.297  2766  2813 I jxcore-log: 
,07-08 14:03:03.352  3000  3000 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-08 14:03:03.378   590   662 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-08 14:03:03.385  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:03:03.385  2766  2813 I jxcore-log: 
,07-08 14:03:03.385   590   662 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,07-08 14:03:03.385   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:03:03.386  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:03:03.386  2766  2813 I jxcore-log: 
07-08 14:03:03.387  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:03:03.387  2766  2813 I jxcore-log: 
07-08 14:03:03.388  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:03:03.388  2766  2813 I jxcore-log: 
,07-08 14:03:03.392  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:03.392  2766  2813 I jxcore-log: 
,07-08 14:03:03.396  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:03.396  2766  2813 I jxcore-log: 
,07-08 14:03:03.398  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:03:03.398  2766  2813 I jxcore-log: 
,07-08 14:03:03.399  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-08 14:03:03.399  2766  2813 I jxcore-log: 
,07-08 14:03:03.401   590   662 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-08 14:03:03.450   590   662 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-08 14:03:03.771  3000  3000 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:03:03.820  3000  3000 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-08 14:03:03.822  3000  3000 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-08 14:03:03.825   590   662 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:03:03.848   590   662 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:03:03.848   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:03:03.849   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:03:03.869   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:03:03.886   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:03.897   590   662 D WifiStateMachine: Start Dhcp Watchdog 2
,07-08 14:03:03.908   590   662 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-08 14:03:03.922   590  3008 D DhcpClient: Receive thread started
,07-08 14:03:04.011   590   662 E native  : do suspend false
,07-08 14:03:04.029   590  3007 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:03:04.043   590  3008 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172661, domain null
,07-08 14:03:04.043   590  3007 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172661 seconds
,07-08 14:03:04.048   590  3007 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-08 14:03:04.062   590  3008 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-08 14:03:04.062   590  3007 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-08 14:03:04.067   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:04.073   590   662 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
,07-08 14:03:04.081   590  3007 D DhcpClient: Scheduling renewal in 86399s
,07-08 14:03:04.085   590   662 E native  : do suspend true
,07-08 14:03:04.103   590   662 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-08 14:03:04.106   590   662 D WifiConfigStore: No blacklist allowed without epno enabled
07-08 14:03:04.107   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-08 14:03:04.111   590   664 D ConnectivityService: Adding iface wlan0 to network 101
,07-08 14:03:04.114   590   662 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-08 14:03:04.145   590   611 D WifiService: setWifiEnabled: false pid=2766, uid=10000
,07-08 14:03:04.145   590   611 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:03:04.181   590   664 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-08 14:03:04.182   590   664 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
07-08 14:03:04.184   590   664 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-08 14:03:04.188   590   664 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-08 14:03:04.191   590   664 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-08 14:03:04.195   590   662 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-08 14:03:04.201   590   662 D IpReachabilityMonitor: clear: iface{wlan0/6}, v{4}, ntable=[]
,07-08 14:03:04.201   590   662 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:03:04.201   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:03:04.211   590   662 E native  : do suspend true
,07-08 14:03:04.213   590   664 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-08 14:03:04.221   590   664 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-08 14:03:04.221   590   664 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-08 14:03:04.221   590   664 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
07-08 14:03:04.221   590   664 D ConnectivityService:    accepting network in place of null
07-08 14:03:04.224   590   664 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-08 14:03:04.229   590  3007 D DhcpClient: Clearing IP address
,07-08 14:03:04.276   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:03:04.304   590  3005 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.110,2a00:1450:4001:817::200e
,07-08 14:03:04.327   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:03:04.327   218   621 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:03:04.336   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:04.341   590  3005 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,07-08 14:03:04.344   590   664 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-08 14:03:04.344   590   664 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:03:04.353   590   627 D Tethering: MasterInitialState.processMessage what=3
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:03:04.358  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:03:04.363  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-08 14:03:04.377   590   662 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:03:04.378   590   664 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
07-08 14:03:04.383   590   590 D RttService: SCAN_AVAILABLE : 1
07-08 14:03:04.383   590   677 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-08 14:03:04.384   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
07-08 14:03:04.384   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-08 14:03:04.384   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-08 14:03:04.386   590   662 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-08 14:03:04.388   590   662 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-08 14:03:04.389   590   662 E native  : do suspend true
07-08 14:03:04.391   590   664 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-08 14:03:04.416   590  3008 D DhcpClient: Receive thread stopped
07-08 14:03:04.460  1171  1171 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:03:04.471  1171  1171 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-08 14:03:04.485   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:03:04.521  1171  3018 I MDM     : [199] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
,07-08 14:03:04.521  1171  3018 W BaseAppContext: Using Auth Proxy for data requests.
07-08 14:03:04.523  1171  3018 V GoogleAuthProtoRequest: [199] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:03:04.539   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:03:04.540   218   621 D CommandListener: Clearing all IP addresses on wlan0
07-08 14:03:04.540   590   664 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-08 14:03:04.540   590   664 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:04.545  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:04.546   590   627 D Tethering: MasterInitialState.processMessage what=3
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:04.548  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:04.593  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:03:04.596  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:03:04.600  1171  1171 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:03:04.601  1171  1171 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-08 14:03:04.657  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-08 14:03:04.657  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,07-08 14:03:04.657  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:03:04.658  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:03:04.669   218   621 E Netd    : netlink response contains error (No such file or directory)
07-08 14:03:04.671   590   664 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-08 14:03:04.673   590   662 D DhcpClient: doQuit
07-08 14:03:04.673   590   662 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:03:04.673   590  3007 D DhcpClient: onQuitting
07-08 14:03:04.674  3000  3000 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:04.677  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:04.677  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:04.680  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:04.680  2766  2813 I jxcore-log: 
,07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:04.680  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:04.681  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:04.683  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:04.683  2766  2813 I jxcore-log: 
,07-08 14:03:04.698  3000  3000 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,07-08 14:03:04.708  3000  3000 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-08 14:03:04.727  1171  3018 E MDM     : [199] SitrepService.a: Error sending sitrep.
,07-08 14:03:04.736  3000  3000 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-08 14:03:04.752  3000  3000 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-08 14:03:04.856   590   662 D wifi    : In wifi stop Hal
,07-08 14:03:04.857   590   662 D wifi    : halHandle = 0x55a254eb00, mVM = 0x55a2049c30, mCls = 0x20191e
,07-08 14:03:04.859   590  2999 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-08 14:03:04.859   590  2999 D WifiHAL : Got a signal to exit!!!
,07-08 14:03:04.859   590  2999 I WifiHAL : Exit wifi_event_loop
07-08 14:03:04.862  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:04.863  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:04.864   590   662 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 9
07-08 14:03:04.864   590   662 E WifiHAL : Event processing terminated
07-08 14:03:04.864   590   662 D wifi    : In wifi cleaned up handler
07-08 14:03:04.865   590   662 I WifiHAL : Internal cleanup completed
07-08 14:03:04.867  2907  2907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:03:04.880  1010  1269 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:03:04.983   590  2999 D wifi    : set interface wlan0 flags (DOWN)
,07-08 14:03:04.983   590   662 D WifiNative-HAL: HAL event thread stopped successfully
,07-08 14:03:05.344   590   664 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-08 14:03:07.375  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:03:07.401  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-08 14:03:07.401  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-08 14:03:07.402  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:03:07.402  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:03:07.426  2465  2465 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-08 14:03:07.427  2465  2465 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-08 14:03:07.427  2465  2465 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-08 14:03:09.182   590   627 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e1bf675:true
,07-08 14:03:09.183  2879  2879 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:03:09.188  2879  2879 I bt_bluedroid: init
,07-08 14:03:09.189  2879  3035 I BluetoothAdapterState: Entering OffState
,07-08 14:03:09.191  2879  3036 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-08 14:03:09.192  2879  3036 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:03:09.192  2879  3036 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-08 14:03:09.192  2879  3036 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-08 14:03:09.194  2879  2879 I bt_bluedroid: get_profile_interface socket
,07-08 14:03:09.197  2879  2879 I bt_bluedroid: get_profile_interface sdp
,07-08 14:03:09.199  2879  3039 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-08 14:03:09.200  2879  2890 I bt_bluedroid: config_hci_snoop_log
07-08 14:03:09.200  2879  3039 D BluetoothAdapterProperties: Name is: Nexus 9
,07-08 14:03:09.202   590   627 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-08 14:03:09.207  2879  3035 D BluetoothAdapterState: Current state: OFF, message: 0
,07-08 14:03:09.207  2879  3035 D BluetoothAdapterProperties: Setting state to 14
07-08 14:03:09.207  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-08 14:03:09.208  2879  3035 D BluetoothBondStateMachine: make
07-08 14:03:09.211  2879  3040 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-08 14:03:09.214  2879  3035 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:09.215  2879  2879 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-08 14:03:09.218  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:09.219  2879  2879 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:03:09.220  2879  2879 D BtGatt.GattService: Received start request. Starting profile...
07-08 14:03:09.220  2879  2879 D BtGatt.GattService: start()
07-08 14:03:09.221  2879  2879 I bt_bluedroid: get_profile_interface gatt
,07-08 14:03:09.221  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:09.222  2879  2879 D BtGatt.AdvertiseManager: advertise manager created
,07-08 14:03:09.230  2879  2879 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:09.230  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:09.230  2879  2879 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:03:09.230  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:09.230  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:03:09.231  2879  3035 I bt_bluedroid: enable
07-08 14:03:09.231  2879  3036 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:03:09.231  2879  3036 I bt_hci  : start_up
,07-08 14:03:09.241  2879  3036 I bt_vendor: alloc value 0xf3cfc889
,07-08 14:03:09.242  2879  3036 I bt_vendor: init
07-08 14:03:09.242  2879  3036 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-08 14:03:09.444  2879  3036 D bt_hci  : start_up starting async portion
,07-08 14:03:09.444  2879  3043 I bt_hci  : event_finish_startup
,07-08 14:03:09.444  2879  3043 I bt_hci_h4: hal_open
07-08 14:03:09.444  2879  3043 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
07-08 14:03:09.445  2879  3043 I bt_userial_vendor: device fd = 49 open
,07-08 14:03:09.456  2879  3043 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-08 14:03:09.492  2879  3043 D bt_hwcfg: Chipset BCM4350C0
,07-08 14:03:09.492  2879  3043 D bt_hwcfg: Target name = [BCM4350C0]
07-08 14:03:09.492  2879  3043 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-08 14:03:10.125  2879  3043 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:03:10.126  2879  3043 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:03:10.126  2879  3043 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:03:10.234  2879  3043 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-08 14:03:10.234  2879  3043 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-08 14:03:10.270  2879  3043 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:03:10.270  2879  3043 I bt_vendor: firmware callback
07-08 14:03:10.271  2879  3043 I bt_hci  : firmware_config_callback
,07-08 14:03:10.278  2879  3045 I bt_btu  : btu_task pending for preload complete event
,07-08 14:03:10.279  2879  3045 I bt_btu_task: Bluetooth chip preload is complete
07-08 14:03:10.279  2879  3045 I bt_btu  : btu_task received preload complete event
,07-08 14:03:10.288  2879  3045 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:03:10.288  2879  3045 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-08 14:03:10.288  2879  3045 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-08 14:03:10.288  2879  3045 I         : BTE_InitTraceLevels -- TRC_AVDT
07-08 14:03:10.289  2879  3045 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:03:10.289  2879  3045 I         : BTE_InitTraceLevels -- TRC_A2D
07-08 14:03:10.289  2879  3045 I         : BTE_InitTraceLevels -- TRC_BNEP
07-08 14:03:10.289  2879  3045 I         : BTE_InitTraceLevels -- TRC_BTM
07-08 14:03:10.289  2879  3045 I         : BTE_InitTraceLevels -- TRC_GAP
07-08 14:03:10.289  2879  3045 I         : BTE_InitTraceLevels -- TRC_PAN
,07-08 14:03:10.290  2879  3045 I         : BTE_InitTraceLevels -- TRC_SDP
,07-08 14:03:10.290  2879  3045 I         : BTE_InitTraceLevels -- TRC_GATT
07-08 14:03:10.290  2879  3045 I         : BTE_InitTraceLevels -- TRC_SMP
07-08 14:03:10.290  2879  3045 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-08 14:03:10.290  2879  3045 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:03:10.515  2879  3045 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c7aa31
,07-08 14:03:10.515  2879  3045 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c7aa31 
,07-08 14:03:10.524  2879  3039 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
,07-08 14:03:10.527  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:03:10.527  2879  3039 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-08 14:03:10.532  2879  3039 D BluetoothAdapterProperties: Name is: Nexus 9
,07-08 14:03:10.537  2879  3039 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:10.537  2879  3039 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:03:10.538  2879  3039 D bt_hci  : do_postload posting postload work item
07-08 14:03:10.538  2879  3043 I bt_hci  : event_postload
07-08 14:03:10.538  2879  3043 I bt_vendor: sco_config_cb
07-08 14:03:10.538  2879  3043 I bt_hci  : sco_config_callback postload finished.
07-08 14:03:10.543  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:10.546  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:10.548  2879  3043 I bt_vendor: low_power_mode_cb
,07-08 14:03:10.549  2879  3039 D bt_bte_conf: Device ID record 1 : primary
07-08 14:03:10.549  2879  3039 D bt_bte_conf:   vendorId            = 000f
07-08 14:03:10.549  2879  3039 D bt_bte_conf:   vendorIdSource      = 0001
07-08 14:03:10.549  2879  3039 D bt_bte_conf:   product             = 1200
07-08 14:03:10.549  2879  3039 D bt_bte_conf:   version             = 1436
07-08 14:03:10.549  2879  3039 D bt_bte_conf:   clientExecutableURL = 
07-08 14:03:10.549  2879  3039 D bt_bte_conf:   serviceDescription  = 
,07-08 14:03:10.550  2879  3039 D bt_bte_conf:   documentationURL    = 
07-08 14:03:10.550  2879  3039 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-08 14:03:10.551  2879  3036 D bt_stack_manager: event_start_up_stack finished
07-08 14:03:10.551  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-08 14:03:10.551  2879  3035 D BluetoothAdapterProperties: Setting state to 15
07-08 14:03:10.551  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-08 14:03:10.555  2879  3035 I BluetoothAdapterState: Entering BleOnState
07-08 14:03:10.556  2879  3035 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:03:10.556  2879  3035 D BluetoothAdapterProperties: Setting state to 11
07-08 14:03:10.556  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-08 14:03:10.560  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:10.571  2879  2879 D HeadsetService: Received start request. Starting profile...
,07-08 14:03:10.579  2879  3035 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:03:10.583  2879  2879 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-08 14:03:10.583  2879  2879 D HeadsetStateMachine: make
,07-08 14:03:10.597  2879  2879 D HeadsetStateMachine: max_hf_connections = 1
,07-08 14:03:10.598  2879  2879 I bt_bluedroid: get_profile_interface handsfree
07-08 14:03:10.598  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-08 14:03:10.598  2879  3039 E bt_btif : btif_hf_upstreams_evt: Invalid index 15647
,07-08 14:03:10.604  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:10.604  2879  2879 D A2dpService: Received start request. Starting profile...
,07-08 14:03:10.605  2879  2879 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-08 14:03:10.605  2879  2879 I bt_bluedroid: get_profile_interface avrcp
,07-08 14:03:10.627  2879  2879 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-08 14:03:10.627  2879  2879 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-08 14:03:10.627  2879  2879 D A2dpStateMachine: make
,07-08 14:03:10.630  2879  2879 I bt_bluedroid: get_profile_interface a2dp
,07-08 14:03:10.635  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-08 14:03:10.637  2879  2879 I BluetoothHidServiceJni: classInitNative: succeeds
,07-08 14:03:10.638  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:10.640  2879  3053 D A2dpStateMachine: Enter Disconnected: -2
,07-08 14:03:10.641  2879  2879 D HidService: Received start request. Starting profile...
07-08 14:03:10.641  2879  2879 I bt_bluedroid: get_profile_interface hidhost
07-08 14:03:10.641  2879  3039 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c5c099
07-08 14:03:10.642  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-08 14:03:10.642  2879  2879 D HidService: setHidService(): set to: null
,07-08 14:03:10.643  2879  2879 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-08 14:03:10.644  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:10.645  2879  2879 D HealthService: Received start request. Starting profile...
07-08 14:03:10.645  2826  2826 D BluetoothInputDevice: Proxy object connected
07-08 14:03:10.646  2826  2826 D HidProfile: Bluetooth service connected
,07-08 14:03:10.649  2879  2879 I bt_bluedroid: get_profile_interface health
,07-08 14:03:10.650  2879  2879 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-08 14:03:10.651  2879  2879 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:10.653  2879  2879 D PanService: Received start request. Starting profile...
07-08 14:03:10.653  2879  2879 D BluetoothPanServiceJni: initializeNative(L110): pan
07-08 14:03:10.653  2879  2879 I bt_bluedroid: get_profile_interface pan
,07-08 14:03:10.653  2826  2826 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:03:10.654  2879  3039 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-08 14:03:10.654  2826  2826 D PanProfile: Bluetooth service connected
,07-08 14:03:10.662  2879  2879 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:10.662  2879  2879 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:10.662  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:10.662  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:10.665  2879  3051 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-08 14:03:10.665  2879  2879 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:10.665  2879  2879 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:10.666  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:10.667  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:10.667  2879  2879 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:10.667  2879  2879 V BluetoothAdapterState: isTurningOn()=true
07-08 14:03:10.667  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:10.668  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:10.668  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-08 14:03:10.668  2879  3035 D BluetoothAdapterProperties: ScanMode =  20
07-08 14:03:10.668  2879  3035 D BluetoothAdapterProperties: State =  11
,07-08 14:03:10.669  2879  3035 D BluetoothAdapterProperties: Setting state to 12
,07-08 14:03:10.669  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-08 14:03:10.670  2826  2839 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:03:10.673   590   627 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:10.674   738   754 D BluetoothPan: onBluetoothStateChange on: true
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:10.676  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:10.677  2879  3039 D BluetoothAdapterProperties: Scan Mode:21
,07-08 14:03:10.677  2879  3039 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:03:10.678  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:10.679  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:10.679  2766  2813 I jxcore-log: 
,07-08 14:03:10.683   738   738 D BluetoothPan: BluetoothPAN Proxy object connected
,07-08 14:03:10.683   738   738 D PanProfile: Bluetooth service connected
,07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:10.683  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:10.685  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:10.686  2879  3035 I BluetoothAdapterState: Entering OnState
07-08 14:03:10.687  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:10.687  2766  2813 I jxcore-log: 
,07-08 14:03:10.687   590   627 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:10.687   738  2841 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:03:10.687  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-08 14:03:10.688   738  2841 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-08 14:03:10.688   738  2840 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:03:10.690   738   738 D BluetoothInputDevice: Proxy object connected
07-08 14:03:10.690   738   738 D HidProfile: Bluetooth service connected
07-08 14:03:10.692   738  1115 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:10.692   738  2836 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:03:10.694   738   753 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:03:10.698   738   738 D BluetoothA2dp: Proxy object connected
07-08 14:03:10.700   590   627 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:10.700  2826  2837 D BluetoothPan: onBluetoothStateChange on: true
,07-08 14:03:10.700   590   627 D BluetoothA2dp: onBluetoothStateChange: up=true
07-08 14:03:10.701   590   590 D BluetoothA2dp: Proxy object connected
07-08 14:03:10.703  2826  2839 D BluetoothPbap: onBluetoothStateChange: up=true
,07-08 14:03:10.706  1036  1056 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:10.709  2826  2837 D BluetoothMap: onBluetoothStateChange: up=true
07-08 14:03:10.709  2826  2837 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-08 14:03:10.711   590   590 I Telecom : BluetoothPhoneService: queryPhoneState
07-08 14:03:10.747   590   600 I art     : Background partial concurrent mark sweep GC freed 52010(3MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 17MB/26MB, paused 2.098ms total 152.331ms
,07-08 14:03:10.750  2826  2826 D LocalBluetoothProfileManager: Adding local A2DP profile
07-08 14:03:10.754  2826  2826 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-08 14:03:10.763  2826  2826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:03:10.766  2826  2826 D BluetoothA2dp: Proxy object connected
,07-08 14:03:10.772  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:10.788   738   738 D BluetoothPbap: Proxy object connected
,07-08 14:03:10.789   738   738 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:10.793   590   590 D BluetoothHeadset: Proxy object connected
,07-08 14:03:10.793   738  1115 D BluetoothHeadset: Proxy object connected
07-08 14:03:10.794   738  2836 D BluetoothHeadset: Proxy object connected
07-08 14:03:10.794   590   590 D BluetoothHeadset: Proxy object connected
07-08 14:03:10.794   738   738 D HeadsetProfile: Bluetooth service connected
07-08 14:03:10.797   738   738 D HeadsetProfile: Bluetooth service connected
07-08 14:03:10.800   590   627 D BluetoothHeadset: Proxy object connected
07-08 14:03:10.806  2826  2826 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:10.808  2826  2826 D BluetoothPbap: Proxy object connected
07-08 14:03:10.808  1036  1059 D BluetoothHeadset: Proxy object connected
,07-08 14:03:10.810  2826  2826 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:10.824  2879  3063 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:10.849  2879  3067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:10.851  2879  3067 I BtOppRfcommListener: Accept thread started.
,07-08 14:03:10.859  2826  2837 D BluetoothHeadset: Proxy object connected
,07-08 14:03:10.860  2826  2826 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:12.222   590   664 D ConnectivityService: handlePromptUnvalidated 101
,07-08 14:03:14.158  2879  3035 D BluetoothAdapterState: Current state: ON, message: 23
,07-08 14:03:14.158  2879  3035 D BluetoothAdapterProperties: Setting state to 13
,07-08 14:03:14.158  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-08 14:03:14.159  2879  3035 D BluetoothAdapterProperties: onBluetoothDisable()
,07-08 14:03:14.162  2879  3035 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:14.171  2879  2879 I BtOppRfcommListener: stopping Accept Thread
07-08 14:03:14.175  2879  3067 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-08 14:03:14.175  2879  3067 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.195  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:14.196  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:14.199  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:14.199  2766  2813 I jxcore-log: 
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:14.201  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:14.202  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:14.181  2879  3039 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:14.204  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-08 14:03:14.204  2766  2813 I jxcore-log: 
07-08 14:03:14.205  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-08 14:03:14.208  2879  2879 D HeadsetService: Received stop request...Stopping profile...
,07-08 14:03:14.212   590   590 D BluetoothHeadset: Proxy object disconnected
,07-08 14:03:14.212   738  2840 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:14.212   738   738 D HeadsetProfile: Bluetooth service disconnected
,07-08 14:03:14.214  1036  1139 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:14.214   590   590 D BluetoothHeadset: Proxy object disconnected
,07-08 14:03:14.215   590   590 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:14.215  2826  2839 D BluetoothHeadset: Proxy object disconnected
07-08 14:03:14.215  2879  2879 D A2dpService: Received stop request...Stopping profile...
07-08 14:03:14.216  2879  3053 D A2dpStateMachine: Exit Disconnected: -1
07-08 14:03:14.217   590   590 D BluetoothA2dp: Proxy object disconnected
,07-08 14:03:14.218   738   738 D BluetoothA2dp: Proxy object disconnected
07-08 14:03:14.219  2879  2879 D HidService: Received stop request...Stopping profile...
,07-08 14:03:14.219  2879  2879 D HidService: Stopping Bluetooth HidService
07-08 14:03:14.220   738   738 D BluetoothInputDevice: Proxy object disconnected
07-08 14:03:14.220   738   738 D HidProfile: Bluetooth service disconnected
07-08 14:03:14.222  2879  2879 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:14.222  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:14.223  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:14.223  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:14.224  2879  2879 D HealthService: Received stop request...Stopping profile...
07-08 14:03:14.227  2879  2879 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-08 14:03:14.228  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
,07-08 14:03:14.228  2879  3045 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:14.228  2879  3045 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:14.231  2879  3039 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-08 14:03:14.233  2879  2879 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-08 14:03:14.236  2879  2879 D PanService: Received stop request...Stopping profile...
,07-08 14:03:14.239   738   738 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-08 14:03:14.240   738   738 D PanProfile: Bluetooth service disconnected
07-08 14:03:14.240  2879  2879 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:14.240  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:14.240  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:14.241  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:14.242  2879  2879 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:14.242  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:14.242  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:14.242  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:14.243  2879  3045 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:14.243  2879  3045 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-08 14:03:14.243  2879  3045 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:03:14.243  2879  3045 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:03:14.243  2879  3045 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-08 14:03:14.244  2879  3045 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-08 14:03:14.244  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100020
07-08 14:03:14.244  2879  2879 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-08 14:03:14.244  2879  3039 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-08 14:03:14.244  2879  2879 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-08 14:03:14.245  2879  2879 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:14.245  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:14.245  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:14.245  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:14.245  2879  2879 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-08 14:03:14.246  2879  3039 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-08 14:03:14.246  2879  2879 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-08 14:03:14.247  2879  2879 V BluetoothAdapterState: isTurningOff()=true
07-08 14:03:14.247  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:14.247  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:14.247  2879  2879 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:14.248  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-08 14:03:14.248  2879  3035 D BluetoothAdapterProperties: Setting state to 15
,07-08 14:03:14.248  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-08 14:03:14.249  2826  2839 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:03:14.250   590   627 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:14.252   738  2840 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:03:14.252  2879  3035 I BluetoothAdapterState: Entering BleOnState
07-08 14:03:14.253   590   627 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:14.254   738  2836 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:03:14.255   738  2836 E BluetoothMap: 
07-08 14:03:14.255   738  2836 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@c91bd7d
07-08 14:03:14.255   738  2836 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-08 14:03:14.255   738  2836 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-08 14:03:14.255   738  2836 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-08 14:03:14.255   738  2836 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-08 14:03:14.255   738  2836 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-08 14:03:14.255   738  2836 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:03:14.255   738  1115 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-08 14:03:14.256   738   754 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:14.256   738   753 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:03:14.258  2826  2826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:03:14.260   738  1114 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:03:14.260  2879  2879 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-08 14:03:14.262  2879  2879 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-08 14:03:14.264   590   627 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-08 14:03:14.264  2826  2839 D BluetoothPan: onBluetoothStateChange on: false
07-08 14:03:14.266  2826  2837 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:14.266   590   627 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:03:14.266  2826  2839 D BluetoothPbap: onBluetoothStateChange: up=false
07-08 14:03:14.268  1036  1137 D BluetoothHeadset: onBluetoothStateChange: up=false
07-08 14:03:14.268  2826  2837 D BluetoothMap: onBluetoothStateChange: up=false
07-08 14:03:14.269  2826  2837 E BluetoothMap: 
07-08 14:03:14.269  2826  2837 E BluetoothMap: java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@f1777e3
07-08 14:03:14.269  2826  2837 E BluetoothMap: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1044)
07-08 14:03:14.269  2826  2837 E BluetoothMap: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1337)
07-08 14:03:14.269  2826  2837 E BluetoothMap: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:616)
07-08 14:03:14.269  2826  2837 E BluetoothMap: 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:64)
07-08 14:03:14.269  2826  2837 E BluetoothMap: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
07-08 14:03:14.269  2826  2837 E BluetoothMap: 	at android.os.Binder.execTransact(Binder.java:453)
07-08 14:03:14.270  2826  2839 D BluetoothA2dp: onBluetoothStateChange: up=false
07-08 14:03:14.274  2826  2826 D HeadsetProfile: Bluetooth service disconnected
07-08 14:03:14.281  2879  3035 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-08 14:03:14.281  2879  3035 D BluetoothAdapterProperties: Setting state to 16
,07-08 14:03:14.281  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-08 14:03:14.282  2879  3035 D BluetoothAdapterProperties: onBleDisable
07-08 14:03:14.282  2879  3035 I BluetoothAdapterState: Entering PendingCommandState
07-08 14:03:14.283  2879  3036 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-08 14:03:14.286  2879  3045 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-08 14:03:14.286  2879  3045 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-08 14:03:14.291  2826  2826 D DockEventReceiver: finishStartingService: stopping service
07-08 14:03:14.295  2879  3039 D BluetoothAdapterProperties: Scan Mode:20
07-08 14:03:14.301  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.303  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:14.312  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-08 14:03:14.320  2826  2826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-08 14:03:14.328  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:14.339  2826  2826 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:14.491  2879  3045 W bt_btif : ag scb idx 1 not allocated
,07-08 14:03:14.491  2879  3045 E bt_btif : BTA AG is already disabled, ignoring ...
,07-08 14:03:14.492  2879  3039 I bt_hci  : shut_down
,07-08 14:03:14.514  2879  3043 I bt_vendor: low_power_mode_cb
,07-08 14:03:14.516  2879  3043 D bt_hwcfg: hw_epilog_process
,07-08 14:03:14.522  2879  3043 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-08 14:03:14.522  2879  3043 I bt_vendor: epilog_cb
07-08 14:03:14.522  2879  3043 I bt_hci  : epilog_finished_callback
,07-08 14:03:14.525  2879  3039 I bt_hci_h4: hal_close
,07-08 14:03:14.526  2879  3039 I bt_userial_vendor: device fd = 49 close
,07-08 14:03:14.730  2879  3036 D bt_stack_manager: event_shut_down_stack finished.
,07-08 14:03:14.730  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-08 14:03:14.732  2879  3035 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-08 14:03:14.732  2879  2879 D BtGatt.DebugUtils: handleDebugAction() action=null
07-08 14:03:14.733  2879  2879 D BtGatt.GattService: Received stop request...Stopping profile...
07-08 14:03:14.733  2879  2879 D BtGatt.GattService: stop()
,07-08 14:03:14.733  2879  2879 D BtGatt.AdvertiseManager: advertise clients cleared
07-08 14:03:14.735  2879  2879 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:14.735  2879  2879 V BluetoothAdapterState: isTurningOn()=false
07-08 14:03:14.735  2879  2879 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:14.735  2879  2879 V BluetoothAdapterState: isBleTurningOff()=true
07-08 14:03:14.735  2879  3035 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-08 14:03:14.736  2879  3035 D BluetoothAdapterProperties: Setting state to 10
07-08 14:03:14.736  2879  3035 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-08 14:03:14.736  2879  3035 I BluetoothAdapterState: Entering OffState
07-08 14:03:14.737   590   627 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-08 14:03:14.744  2879  2879 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-08 14:03:14.744  2879  2879 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-08 14:03:14.744  2879  3036 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-08 14:03:14.745  2879  2879 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-08 14:03:14.748  2879  3036 D bt_stack_manager: event_clean_up_stack finished.
07-08 14:03:14.751  2879  2879 I art     : System.exit called, status: 0
07-08 14:03:14.751  2879  2879 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-08 14:03:14.782   590  1984 I ActivityManager: Process com.android.bluetooth (pid 2879) has died
,07-08 14:03:19.157  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:19.158  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:19.174  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:19.175  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ba5a8 added. We now have 6 listener(s)
07-08 14:03:19.175  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:19.177  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:19.178  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fdee8c1 added. We now have 7 listener(s)
,07-08 14:03:19.178  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:19.179  2766  2806 I System.out: IsBluetoothEnabled
,07-08 14:03:19.189  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:19.234   590   627 I ActivityManager: Start proc 3075:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-08 14:03:19.336  3075  3075 D AdapterServiceConfig: Adding HeadsetService
07-08 14:03:19.337  3075  3075 D AdapterServiceConfig: Adding A2dpService
,07-08 14:03:19.337  3075  3075 D AdapterServiceConfig: Adding HidService
07-08 14:03:19.337  3075  3075 D AdapterServiceConfig: Adding HealthService
07-08 14:03:19.337  3075  3075 D AdapterServiceConfig: Adding PanService
07-08 14:03:19.337  3075  3075 D AdapterServiceConfig: Adding GattService
,07-08 14:03:19.355   590   627 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e971628:true
,07-08 14:03:19.356  3075  3075 D BluetoothAdapterState: make() - Creating AdapterState
,07-08 14:03:19.361  3075  3087 I BluetoothAdapterState: Entering OffState
,07-08 14:03:19.361  3075  3075 I bt_bluedroid: init
,07-08 14:03:19.365  3075  3088 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-08 14:03:19.365  3075  3088 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-08 14:03:19.365  3075  3088 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-08 14:03:19.365  3075  3088 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-08 14:03:19.367  3075  3075 I bt_bluedroid: get_profile_interface socket
,07-08 14:03:19.370  3075  3075 I bt_bluedroid: get_profile_interface sdp
,07-08 14:03:19.371  3075  3091 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
07-08 14:03:19.374  3075  3091 D BluetoothAdapterProperties: Name is: Nexus 9
07-08 14:03:19.374  3075  3086 I bt_bluedroid: config_hci_snoop_log
,07-08 14:03:19.376   590   627 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-08 14:03:19.380  3075  3087 D BluetoothAdapterState: Current state: OFF, message: 0
07-08 14:03:19.381  3075  3087 D BluetoothAdapterProperties: Setting state to 14
07-08 14:03:19.381  3075  3087 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-08 14:03:19.382  3075  3087 D BluetoothBondStateMachine: make
,07-08 14:03:19.386  3075  3092 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-08 14:03:19.388  3075  3087 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:03:19.389  3075  3075 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-08 14:03:19.392  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:19.393  3075  3075 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-08 14:03:19.393  3075  3075 D BtGatt.GattService: Received start request. Starting profile...
,07-08 14:03:19.393  3075  3075 D BtGatt.GattService: start()
07-08 14:03:19.394  3075  3075 I bt_bluedroid: get_profile_interface gatt
,07-08 14:03:19.394  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:19.395  3075  3075 D BtGatt.AdvertiseManager: advertise manager created
,07-08 14:03:19.403  3075  3075 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:19.403  3075  3075 V BluetoothAdapterState: isTurningOn()=false
,07-08 14:03:19.403  3075  3075 V BluetoothAdapterState: isBleTurningOn()=true
07-08 14:03:19.403  3075  3075 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:19.403  3075  3087 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-08 14:03:19.403  3075  3087 I bt_bluedroid: enable
,07-08 14:03:19.404  3075  3088 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-08 14:03:19.404  3075  3088 I bt_hci  : start_up
,07-08 14:03:19.414  3075  3088 I bt_vendor: alloc value 0xf3d08889
07-08 14:03:19.415  3075  3088 I bt_vendor: init
07-08 14:03:19.415  3075  3088 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-08 14:03:19.616  3075  3088 D bt_hci  : start_up starting async portion
,07-08 14:03:19.617  3075  3095 I bt_hci  : event_finish_startup
,07-08 14:03:19.617  3075  3095 I bt_hci_h4: hal_open
07-08 14:03:19.617  3075  3095 I bt_userial_vendor: userial vendor open: opening /dev/ttyTHS2
,07-08 14:03:19.618  3075  3095 I bt_userial_vendor: device fd = 49 open
,07-08 14:03:19.629  3075  3095 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-08 14:03:19.665  3075  3095 D bt_hwcfg: Chipset BCM4350C0
,07-08 14:03:19.665  3075  3095 D bt_hwcfg: Target name = [BCM4350C0]
07-08 14:03:19.666  3075  3095 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4350c0.hcd
,07-08 14:03:20.252  3075  3095 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-08 14:03:20.253  3075  3095 D bt_hwcfg: Settlement delay -- 100 ms
07-08 14:03:20.253  3075  3095 I bt_hwcfg: Setting fw settlement delay to 100 
,07-08 14:03:20.361  3075  3095 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-08 14:03:20.361  3075  3095 I bt_hwcfg: Setting local bd addr to B4:CE:F6:34:3D:CC
,07-08 14:03:20.398  3075  3095 I bt_hwcfg: vendor lib fwcfg completed
,07-08 14:03:20.398  3075  3095 I bt_vendor: firmware callback
07-08 14:03:20.398  3075  3095 I bt_hci  : firmware_config_callback
,07-08 14:03:20.408  3075  3097 I bt_btu  : btu_task pending for preload complete event
,07-08 14:03:20.408  3075  3097 I bt_btu_task: Bluetooth chip preload is complete
,07-08 14:03:20.409  3075  3097 I bt_btu  : btu_task received preload complete event
,07-08 14:03:20.420  3075  3097 I         : BTE_InitTraceLevels -- TRC_HCI
,07-08 14:03:20.420  3075  3097 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-08 14:03:20.420  3075  3097 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-08 14:03:20.421  3075  3097 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-08 14:03:20.421  3075  3097 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-08 14:03:20.421  3075  3097 I         : BTE_InitTraceLevels -- TRC_A2D
07-08 14:03:20.421  3075  3097 I         : BTE_InitTraceLevels -- TRC_BNEP
07-08 14:03:20.421  3075  3097 I         : BTE_InitTraceLevels -- TRC_BTM
07-08 14:03:20.421  3075  3097 I         : BTE_InitTraceLevels -- TRC_GAP
07-08 14:03:20.422  3075  3097 I         : BTE_InitTraceLevels -- TRC_PAN
07-08 14:03:20.422  3075  3097 I         : BTE_InitTraceLevels -- TRC_SDP
,07-08 14:03:20.422  3075  3097 I         : BTE_InitTraceLevels -- TRC_GATT
07-08 14:03:20.422  3075  3097 I         : BTE_InitTraceLevels -- TRC_SMP
07-08 14:03:20.422  3075  3097 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-08 14:03:20.422  3075  3097 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-08 14:03:20.647  3075  3097 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c86a31
,07-08 14:03:20.647  3075  3097 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c86a31 
,07-08 14:03:20.674  3075  3091 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 55 mTotNumOfTrackableAdv = 0 mIsExtendedScanSupported = false mIsDebugLogSupported = false
,07-08 14:03:20.678  3075  3091 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-08 14:03:20.679  3075  3091 D BluetoothAdapterProperties: Address is:B4:CE:F6:34:3D:CC
,07-08 14:03:20.682  3075  3091 D BluetoothAdapterProperties: Name is: Nexus 9
07-08 14:03:20.688  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:20.690  3075  3091 D BluetoothAdapterProperties: Scan Mode:20
,07-08 14:03:20.691  3075  3091 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:03:20.691  3075  3091 D bt_hci  : do_postload posting postload work item
,07-08 14:03:20.691  3075  3095 I bt_hci  : event_postload
07-08 14:03:20.691  3075  3095 I bt_vendor: sco_config_cb
,07-08 14:03:20.691  3075  3095 I bt_hci  : sco_config_callback postload finished.
,07-08 14:03:20.694  3075  3091 D bt_bte_conf: Device ID record 1 : primary
,07-08 14:03:20.695  3075  3091 D bt_bte_conf:   vendorId            = 000f
,07-08 14:03:20.695  3075  3091 D bt_bte_conf:   vendorIdSource      = 0001
,07-08 14:03:20.695  3075  3091 D bt_bte_conf:   product             = 1200
07-08 14:03:20.699  3075  3095 I bt_vendor: low_power_mode_cb
,07-08 14:03:20.708  3075  3091 D bt_bte_conf:   version             = 1436
,07-08 14:03:20.708  3075  3091 D bt_bte_conf:   clientExecutableURL = 
,07-08 14:03:20.708  3075  3091 D bt_bte_conf:   serviceDescription  = 
07-08 14:03:20.708  3075  3091 D bt_bte_conf:   documentationURL    = 
07-08 14:03:20.708  3075  3091 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-08 14:03:20.709  3075  3088 D bt_stack_manager: event_start_up_stack finished
,07-08 14:03:20.709  3075  3087 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-08 14:03:20.710  3075  3087 D BluetoothAdapterProperties: Setting state to 15
07-08 14:03:20.710  3075  3087 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,07-08 14:03:20.714  3075  3087 I BluetoothAdapterState: Entering BleOnState
07-08 14:03:20.716  3075  3087 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-08 14:03:20.716  3075  3087 D BluetoothAdapterProperties: Setting state to 11
,07-08 14:03:20.716  3075  3087 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-08 14:03:20.721  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:20.727  3075  3075 D HeadsetService: Received start request. Starting profile...
,07-08 14:03:20.730  3075  3075 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-08 14:03:20.731  3075  3075 D HeadsetStateMachine: make
07-08 14:03:20.744  3075  3087 I BluetoothAdapterState: Entering PendingCommandState
,07-08 14:03:20.750  3075  3075 D HeadsetStateMachine: max_hf_connections = 1
07-08 14:03:20.750  3075  3075 I bt_bluedroid: get_profile_interface handsfree
,07-08 14:03:20.751  3075  3091 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000020
07-08 14:03:20.752  3075  3091 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
07-08 14:03:20.760  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:20.761  3075  3075 D A2dpService: Received start request. Starting profile...
,07-08 14:03:20.762  3075  3075 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-08 14:03:20.762  3075  3075 I bt_bluedroid: get_profile_interface avrcp
,07-08 14:03:20.775  3075  3075 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-08 14:03:20.776  3075  3075 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-08 14:03:20.776  3075  3075 D A2dpStateMachine: make
,07-08 14:03:20.779  3075  3075 I bt_bluedroid: get_profile_interface a2dp
,07-08 14:03:20.780  3075  3091 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000028
,07-08 14:03:20.786  3075  3105 D A2dpStateMachine: Enter Disconnected: -2
,07-08 14:03:20.787  3075  3075 I BluetoothHidServiceJni: classInitNative: succeeds
,07-08 14:03:20.789  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
07-08 14:03:20.790  3075  3075 D HidService: Received start request. Starting profile...
07-08 14:03:20.790  3075  3075 I bt_bluedroid: get_profile_interface hidhost
07-08 14:03:20.790  3075  3075 D HidService: setHidService(): set to: null
07-08 14:03:20.791  3075  3091 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c68099
,07-08 14:03:20.791  3075  3091 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100028
07-08 14:03:20.792  3075  3075 I BluetoothHealthServiceJni: classInitNative: succeeds
07-08 14:03:20.793  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:20.795  3075  3075 D HealthService: Received start request. Starting profile...
,07-08 14:03:20.799  3075  3075 I bt_bluedroid: get_profile_interface health
,07-08 14:03:20.800  3075  3075 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-08 14:03:20.802  3075  3075 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:20.803  3075  3075 D PanService: Received start request. Starting profile...
,07-08 14:03:20.804  3075  3075 D BluetoothPanServiceJni: initializeNative(L110): pan
,07-08 14:03:20.805  3075  3075 I bt_bluedroid: get_profile_interface pan
,07-08 14:03:20.805  3075  3091 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-08 14:03:20.814  3075  3075 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:20.814  3075  3075 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:20.814  3075  3075 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:20.815  3075  3075 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:20.818  3075  3103 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
07-08 14:03:20.824  3075  3075 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:20.824  3075  3075 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:20.824  3075  3075 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:20.824  3075  3075 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:20.825  3075  3075 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:20.825  3075  3075 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:20.825  3075  3075 V BluetoothAdapterState: isBleTurningOn()=false
,07-08 14:03:20.825  3075  3075 V BluetoothAdapterState: isBleTurningOff()=false
07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isTurningOff()=false
07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isTurningOff()=false
,07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isTurningOn()=true
,07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isBleTurningOn()=false
07-08 14:03:20.826  3075  3075 V BluetoothAdapterState: isBleTurningOff()=false
,07-08 14:03:20.827  3075  3087 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-08 14:03:20.827  3075  3087 D BluetoothAdapterProperties: ScanMode =  20
,07-08 14:03:20.828  3075  3087 D BluetoothAdapterProperties: State =  11
,07-08 14:03:20.828  3075  3087 D BluetoothAdapterProperties: Setting state to 12
07-08 14:03:20.828  3075  3087 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-08 14:03:20.831  2826  2839 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-08 14:03:20.837  3075  3091 D BluetoothAdapterProperties: Scan Mode:21
07-08 14:03:20.838  3075  3091 D BluetoothAdapterProperties: Discoverable Timeout:120
07-08 14:03:20.843  2826  2826 D BluetoothInputDevice: Proxy object connected
07-08 14:03:20.844  2826  2826 D HidProfile: Bluetooth service connected
,07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:20.844  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:20.845  3075  3087 I BluetoothAdapterState: Entering OnState
,07-08 14:03:20.846   590   627 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:20.846   738  1115 D BluetoothPan: onBluetoothStateChange on: true
,07-08 14:03:20.848  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:20.850  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:20.850  2766  2813 I jxcore-log: 
07-08 14:03:20.852   590   627 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:20.853   738   754 D BluetoothMap: onBluetoothStateChange: up=true
,07-08 14:03:20.853   738   738 D BluetoothPan: BluetoothPAN Proxy object connected
,07-08 14:03:20.853   738   738 D PanProfile: Bluetooth service connected
07-08 14:03:20.854   738   754 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,07-08 14:03:20.854   738  2841 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-08 14:03:20.853  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:20.858   738   738 D BluetoothInputDevice: Proxy object connected
,07-08 14:03:20.858   738   738 D HidProfile: Bluetooth service connected
,07-08 14:03:20.863   738  2840 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:20.863   738  1115 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:03:20.868   738   753 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-08 14:03:20.874   590   627 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:20.874  2826  2837 D BluetoothPan: onBluetoothStateChange on: true
,07-08 14:03:20.875   738   738 D BluetoothA2dp: Proxy object connected
07-08 14:03:20.880  2826  2839 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-08 14:03:20.880   590   627 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-08 14:03:20.881   590   590 D BluetoothA2dp: Proxy object connected
,07-08 14:03:20.881  2826  3111 D BluetoothPbap: onBluetoothStateChange: up=true
07-08 14:03:20.884  1036  1056 D BluetoothHeadset: onBluetoothStateChange: up=true
07-08 14:03:20.888  2826  2837 D BluetoothMap: onBluetoothStateChange: up=true
,07-08 14:03:20.888  2826  2837 E BluetoothMap: Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
07-08 14:03:20.889  2826  2839 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-08 14:03:20.892  2826  2826 D BluetoothPan: BluetoothPAN Proxy object connected
07-08 14:03:20.892  2826  2826 D PanProfile: Bluetooth service connected
07-08 14:03:20.893   590   590 I Telecom : BluetoothPhoneService: queryPhoneState
,07-08 14:03:20.894  2826  2826 D BluetoothA2dp: Proxy object connected
07-08 14:03:20.903  2826  2826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-08 14:03:20.912  1078  1078 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-08 14:03:20.921  2826  2826 D DockEventReceiver: finishStartingService: stopping service
,07-08 14:03:20.927   738   738 D BluetoothPbap: Proxy object connected
,07-08 14:03:20.927  2826  2826 D BluetoothPbap: Proxy object connected
,07-08 14:03:20.927   738   738 D PbapServerProfile: Bluetooth service connected
07-08 14:03:20.927  2826  2826 D PbapServerProfile: Bluetooth service connected
,07-08 14:03:20.955  3075  3116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:20.961   590   590 D BluetoothHeadset: Proxy object connected
07-08 14:03:20.963   738  2841 D BluetoothHeadset: Proxy object connected
07-08 14:03:20.963   738  2840 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.963   738   738 D HeadsetProfile: Bluetooth service connected
07-08 14:03:20.963  1036  1059 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.963   590   590 D BluetoothHeadset: Proxy object connected
07-08 14:03:20.964   590   590 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.964  2826  3111 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.966   738   738 D HeadsetProfile: Bluetooth service connected
07-08 14:03:20.968  2826  2826 D HeadsetProfile: Bluetooth service connected
07-08 14:03:20.975   590   627 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.981  2826  2839 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.982  2826  2826 D HeadsetProfile: Bluetooth service connected
,07-08 14:03:20.988  1036  1139 D BluetoothHeadset: Proxy object connected
,07-08 14:03:20.990  3075  3120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-08 14:03:20.992  3075  3120 I BtOppRfcommListener: Accept thread started.
,07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:21.206  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:21.211  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:21.213  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:21.213  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31a1866 added. We now have 8 listener(s)
07-08 14:03:21.213  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:21.214  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-08 14:03:21.214  2766  2813 I jxcore-log: 
,07-08 14:03:21.217   590   958 D WifiService: setWifiEnabled: false pid=2766, uid=10000
,07-08 14:03:21.217   590   958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:03:21.224  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:21.225   590   745 D WifiService: setWifiEnabled: true pid=2766, uid=10000
,07-08 14:03:21.225   590   745 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-08 14:03:21.231   218   621 D SoftapController: Softap fwReload - Ok
,07-08 14:03:21.234   218   621 D CommandListener: Setting iface cfg
07-08 14:03:21.234   218   621 D CommandListener: Trying to bring down wlan0
07-08 14:03:21.236   218   621 D CommandListener: Clearing all IP addresses on wlan0
,07-08 14:03:21.240   590   662 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-08 14:03:21.915   590   662 D wifi    : set interface wlan0 flags (UP)
,07-08 14:03:21.915   590   662 I WifiHAL : Initializing wifi
07-08 14:03:21.915   590   662 I WifiHAL : Creating socket
,07-08 14:03:21.920   590   662 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-08 14:03:21.920   590   662 D wifi    : Did set static halHandle = 0x55a26e5d50
,07-08 14:03:21.920   590   662 D wifi    : halHandle = 0x55a26e5d50, mVM = 0x55a2049c30, mCls = 0x201206
07-08 14:03:21.921   590   662 D wifi    : array field set
07-08 14:03:21.921   590   662 I WifiNative-HAL: interface[0] = wlan0
07-08 14:03:21.933   590   662 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-08 14:03:21.938  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:21.940   590  3124 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=367797362000
07-08 14:03:21.941   590  3124 D wifi    : waitForHalEvents called, vm = 0x55a2049c30, obj = 0x201206, env = 0x55a237a150
,07-08 14:03:22.025  3125  3125 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-08 14:03:22.087  3125  3125 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:03:22.141  3125  3125 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-08 14:03:22.141  3125  3125 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:22.187  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:22.190  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:22.194  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:22.194  2766  2813 I jxcore-log: 
,07-08 14:03:22.196   590   662 D WifiConfigStore: Loading config and enabling all networks 
,07-08 14:03:22.219   590   662 D WifiConfigStore: loaded 0 passpoint configs
,07-08 14:03:22.220   590   662 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-08 14:03:22.221   590   662 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-08 14:03:22.223   590   662 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-08 14:03:22.223   590   662 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-08 14:03:22.223   590   662 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-08 14:03:22.223   590   662 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-08 14:03:22.230  2907  2907 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-08 14:03:22.230   590   662 D WifiNative-HAL: Setting external_sim to 1
07-08 14:03:22.230   590   662 D wifi    : setting dfs flag to true, 0x55a24b1a60
,07-08 14:03:22.231   590   662 D WifiStateMachine: Setting OUI to DA-A1-19
,07-08 14:03:22.231   590   662 D wifi    : setting scan oui 0x55a24b1a60
,07-08 14:03:22.231   590   662 D WifiHAL : Sending mac address OUI
,07-08 14:03:22.254   590   662 E native  : do suspend true
,07-08 14:03:22.262   218   621 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
07-08 14:03:22.262   590   590 D RttService: SCAN_AVAILABLE : 3
,07-08 14:03:22.263   590   677 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-08 14:03:22.264   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:22.265   590   661 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '91 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 91 Failed to set address (No such device)'
,07-08 14:03:22.265   590   662 D wifi    : android_net_wifi_setLinkLayerStats: 1
,07-08 14:03:22.266   590   661 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-08 14:03:22.266   590   662 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-08 14:03:22.289   590   661 D WifiNative-HAL: p2pGetDeviceAddress
,07-08 14:03:22.290   590   661 D WifiNative-HAL: p2pGetDeviceAddress returning 52:2e:5c:e5:0c:a7
,07-08 14:03:22.297   590   625 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=199861 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.245  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:23.250  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.253  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.253  2766  2813 I jxcore-log: 
07-08 14:03:23.255  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-08 14:03:23.256  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-08 14:03:23.265  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7a1579d Bundle[{}]
,07-08 14:03:23.266  2766  2806 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-08 14:03:23.267  2766  2806 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-08 14:03:23.268  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-08 14:03:23.269  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-08 14:03:23.270  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-08 14:03:23.271  2766  2806 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-08 14:03:23.279  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-08 14:03:23.280  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-08 14:03:23.280  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-08 14:03:23.280  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-08 14:03:23.280  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-08 14:03:23.280  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:03:23.286  2766  2806 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 85)
,07-08 14:03:23.286  2766  2806 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 85)
,07-08 14:03:23.286  2766  2806 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 85)
07-08 14:03:23.286  2766  2806 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 85)
,07-08 14:03:23.289  2766  2806 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 91)
,07-08 14:03:23.289  2766  2806 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 91)
,07-08 14:03:23.289  2766  2806 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 91)
,07-08 14:03:23.294  2766  2806 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 92)
,07-08 14:03:23.295  2766  2806 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 94)
07-08 14:03:23.296  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.296  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6fa7a7 added. We now have 2 listener(s)
,07-08 14:03:23.298  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.299  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.299  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:03:23.299  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.299  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c97454 added. We now have 9 listener(s)
07-08 14:03:23.299  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:23.301  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-08 14:03:23.304  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.308  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:23.309  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.309  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-08 14:03:23.310  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.310  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f54f2 added. We now have 3 listener(s)
,07-08 14:03:23.311  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.312  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.314  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.314  2766  2813 I jxcore-log: 
,07-08 14:03:23.314  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-08 14:03:23.315  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.315  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.315  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:23.316  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be51743 added. We now have 10 listener(s)
,07-08 14:03:23.316  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.318  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.318  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.318  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:23.318  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.318  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.319  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.319  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.319  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6fa7a7 removed from the list
07-08 14:03:23.319  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.319  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c97454 removed from the list
07-08 14:03:23.319  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.319  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-08 14:03:23.321  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.321  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:23.321  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.321  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c97454 not in the list
07-08 14:03:23.321  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.321  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:23.321  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.321  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be51743 removed from the list
07-08 14:03:23.321  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.321  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.321  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:23.321  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.322  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f54f2 removed from the list
07-08 14:03:23.323  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:03:23.323  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7381c0 added. We now have 2 listener(s)
07-08 14:03:23.325  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.325  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:03:23.325  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.325  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:23.326  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336eef9 added. We now have 9 listener(s)
07-08 14:03:23.326  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:23.328  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-08 14:03:23.331  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.334  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:23.336  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.337  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:23.337  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.337  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb7e49f added. We now have 3 listener(s)
07-08 14:03:23.338  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.338  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.339  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.339  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.339  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef9ec added. We now have 10 listener(s)
07-08 14:03:23.339  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-08 14:03:23.339  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.339  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:23.339  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.339  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:23.340  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.342  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:23.346  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.346  2766  2813 I jxcore-log: 
,07-08 14:03:23.351  2766  2806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:03:23.351  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:03:23.363  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:03:23.366  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-08 14:03:23.367  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:03:23.367  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:03:23.367  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:03:23.368  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-08 14:03:23.369  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:23.379  3075  3110 D BtGatt.GattService: registerClient() - UUID=41b14925-225b-4225-afe0-370ad5ed9444
,07-08 14:03:23.380  3075  3091 D BtGatt.GattService: onClientRegistered() - UUID=41b14925-225b-4225-afe0-370ad5ed9444, clientIf=5
,07-08 14:03:23.381  2766  2776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-08 14:03:23.382  3075  3086 D BtGatt.GattService: start scan with filters
,07-08 14:03:23.388  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-08 14:03:23.389  3075  3094 D BtGatt.ScanManager: handling starting scan
07-08 14:03:23.389  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:03:23.389  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:03:23.389  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:03:23.389  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:03:23.390  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:03:23.390  3075  3094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b70b661
,07-08 14:03:23.390  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-08 14:03:23.393  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.393  2766  2813 I jxcore-log: 
,07-08 14:03:23.395  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-08 14:03:23.395  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:03:23.395  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:03:23.396  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.396  2766  2813 I jxcore-log: 
,07-08 14:03:23.397  3075  3091 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-08 14:03:23.398  2766  2806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-08 14:03:23.398  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.398  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.399  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.399  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.399  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
07-08 14:03:23.399  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:03:23.399  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-08 14:03:23.399  3075  3094 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-08 14:03:23.400  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:03:23.400  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-08 14:03:23.401  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.401  3075  3085 D BtGatt.GattService: stopScan() - queue size =1
,07-08 14:03:23.402  3075  3110 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:03:23.402  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:23.402  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:03:23.402  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:03:23.402  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:03:23.402  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:03:23.403  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.403  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:23.403  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:03:23.403  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:23.404  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.405  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:23.405  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:23.406  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.406  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:23.411  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-08 14:03:23.411  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.411  3075  3094 D BtGatt.ScanManager: Starting BLE batch scan
07-08 14:03:23.411  3075  3094 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-08 14:03:23.415  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.415  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.415  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:23.415  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.415  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.415  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.416  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.416  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7381c0 removed from the list
07-08 14:03:23.416  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.416  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336eef9 removed from the list
07-08 14:03:23.416  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.416  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.417  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.417  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:03:23.417  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.417  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.417  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.417  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@336eef9 not in the list
07-08 14:03:23.420  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.420  2766  2766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:03:23.424  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:23.426  2766  2766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:23.426  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:03:23.426  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:23.431  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.432  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.432  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:23.432  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:23.433  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:23.435  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.435  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:23.435  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:23.435  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:23.435  3075  3091 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:03:23.435  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.435  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.435  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eef9ec removed from the list
07-08 14:03:23.435  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.436  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.436  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:23.436  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.436  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb7e49f removed from the list
07-08 14:03:23.436  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.436  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3bc897 added. We now have 2 listener(s)
07-08 14:03:23.438  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.438  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.438  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.438  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.438  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5c9a84 added. We now have 9 listener(s)
07-08 14:03:23.438  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.440  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.440  2766  2813 I jxcore-log: 
07-08 14:03:23.441  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.441  2766  2813 I jxcore-log: 
07-08 14:03:23.443  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:03:23.446  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:03:23.446  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.448  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.452  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:23.461  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-08 14:03:23.462  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:03:23.462  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.462  3075  3094 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:03:23.469  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:23.471  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.473  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.474  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-08 14:03:23.474  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.474  3075  3094 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:03:23.476  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.476  2766  2813 I jxcore-log: 
07-08 14:03:23.476  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.476  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@552dea2 added. We now have 3 listener(s)
07-08 14:03:23.479  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.479  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.479  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.479  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.480  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76a5733 added. We now have 10 listener(s)
07-08 14:03:23.480  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.480  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.480  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.481  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:23.481  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.481  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:23.486  3075  3091 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:03:23.486  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.488  2766  2806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.488  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:03:23.494  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:23.496  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:23.496  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:03:23.496  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:03:23.496  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:03:23.496  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-08 14:03:23.497  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:23.500  3075  3085 D BtGatt.GattService: registerClient() - UUID=ddcf05b2-be36-4920-be4a-2dfdb28d77d3
07-08 14:03:23.501  3075  3091 D BtGatt.GattService: onClientRegistered() - UUID=ddcf05b2-be36-4920-be4a-2dfdb28d77d3, clientIf=5
07-08 14:03:23.501  2766  2776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:03:23.501  3075  3110 D BtGatt.GattService: start scan with filters
07-08 14:03:23.505  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-08 14:03:23.505  3075  3094 D BtGatt.ScanManager: handling starting scan
07-08 14:03:23.505  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:03:23.505  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:03:23.505  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:03:23.505  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:03:23.505  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-08 14:03:23.505  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:03:23.507  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.507  2766  2813 I jxcore-log: 
07-08 14:03:23.507  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:03:23.507  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:03:23.507  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:03:23.508  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.508  2766  2813 I jxcore-log: 
07-08 14:03:23.511  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.511  2766  2806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-08 14:03:23.512  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.513  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.513  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:23.513  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.513  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.513  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.513  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.513  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3bc897 removed from the list
07-08 14:03:23.513  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.513  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5c9a84 removed from the list
07-08 14:03:23.513  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.514  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.514  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.514  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:03:23.514  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.514  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.514  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.514  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5c9a84 not in the list
07-08 14:03:23.515  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:03:23.515  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:03:23.515  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:03:23.515  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:03:23.515  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:03:23.516  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.517  3075  3091 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-08 14:03:23.517  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.517  3075  3094 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:03:23.518  3075  3112 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:03:23.519  3075  3085 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:03:23.519  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:23.519  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:03:23.520  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:03:23.520  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:03:23.520  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:03:23.520  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.520  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:23.520  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:03:23.521  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-08 14:03:23.522  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-08 14:03:23.523  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:23.523  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:23.523  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.523  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:23.529  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-08 14:03:23.529  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.529  3075  3094 D BtGatt.ScanManager: Starting BLE batch scan
,07-08 14:03:23.529  3075  3094 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-08 14:03:23.529  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:03:23.529  2766  2766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:03:23.536  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-08 14:03:23.536  2766  2766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-08 14:03:23.537  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-08 14:03:23.537  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:03:23.543  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.543  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,07-08 14:03:23.543  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:03:23.544  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:23.544  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:23.544  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:23.544  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:03:23.544  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.544  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76a5733 removed from the list
,07-08 14:03:23.544  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.544  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.544  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-08 14:03:23.544  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.544  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@552dea2 removed from the list
07-08 14:03:23.545  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:03:23.545  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c959ffa added. We now have 2 listener(s)
,07-08 14:03:23.547  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-08 14:03:23.547  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.547  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.547  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.547  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cf79ab added. We now have 9 listener(s)
07-08 14:03:23.547  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.549  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.549  2766  2813 I jxcore-log: 
07-08 14:03:23.550  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.550  2766  2813 I jxcore-log: 
07-08 14:03:23.553  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:03:23.556  3075  3091 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:03:23.556  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.556  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.560  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:23.562  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.562  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:23.565  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.566  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.567  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:03:23.567  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.567  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.567  2766  2813 I jxcore-log: 
07-08 14:03:23.568  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.568  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5bdba1 added. We now have 3 listener(s)
07-08 14:03:23.570  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.570  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.570  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.570  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.570  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28dc1c6 added. We now have 10 listener(s)
07-08 14:03:23.570  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.570  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.570  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:23.571  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.571  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:23.574  2766  2806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.575  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:03:23.581  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:03:23.581  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.581  3075  3094 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:03:23.581  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:23.583  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:23.583  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:03:23.583  2766  28,06 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:03:23.583  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-08 14:03:23.583  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-08 14:03:23.584  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.587  3075  3085 D BtGatt.GattService: registerClient() - UUID=fa13fd16-7203-4d12-b9e9-17d2f5b6130b
07-08 14:03:23.588  3075  3091 D BtGatt.GattService: onClientRegistered() - UUID=fa13fd16-7203-4d12-b9e9-17d2f5b6130b, clientIf=5
07-08 14:03:23.588  2766  2777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:03:23.589  3075  3112 D BtGatt.GattService: start scan with filters
07-08 14:03:23.592  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-08 14:03:23.592  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:03:23.592  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-08 14:03:23.592  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.592  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:03:23.592  3075  3094 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:03:23.592  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-08 14:03:23.593  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:03:23.593  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
,07-08 14:03:23.594  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.594  2766  2813 I jxcore-log: 
,07-08 14:03:23.593  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-08 14:03:23.597  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-08 14:03:23.597  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-08 14:03:23.597  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-08 14:03:23.599  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.599  2766  2813 I jxcore-log: 
07-08 14:03:23.601  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:23.602  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:03:23.602  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:23.602  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.602  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.602  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-08 14:03:23.602  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:03:23.602  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c959ffa removed from the list
,07-08 14:03:23.602  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.602  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cf79ab removed from the list
,07-08 14:03:23.603  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:23.603  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.603  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.603  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:03:23.604  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.604  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.604  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.604  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cf79ab not in the list
,07-08 14:03:23.604  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-08 14:03:23.604  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-08 14:03:23.604  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-08 14:03:23.604  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-08 14:03:23.605  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-08 14:03:23.605  3075  3091 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:03:23.605  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.606  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:23.607  3075  3094 D BtGatt.ScanManager: handling starting scan
07-08 14:03:23.607  3075  3110 D BtGatt.GattService: stopScan() - queue size =0
07-08 14:03:23.608  3075  3086 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-08 14:03:23.608  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:03:23.608  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:03:23.608  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-08 14:03:23.609  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-08 14:03:23.609  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:03:23.610  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:23.610  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.610  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-08 14:03:23.614  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.614  2766  2766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:03:23.620  3075  3091 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:03:23.620  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.620  3075  3094 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:03:23.620  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:23.621  2766  2766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:23.621  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-08 14:03:23.621  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-08 14:03:23.624  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:03:23.624  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.625  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:03:23.625  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.625  2766  2806 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:03:23.626  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:23.626  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:03:23.626  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.626  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28dc1c6 removed from the list
,07-08 14:03:23.626  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.626  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.626  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.626  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:03:23.626  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5bdba1 removed from the list
07-08 14:03:23.629  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.629  2766  2813 I jxcore-log: 
07-08 14:03:23.630  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.630  2766  2813 I jxcore-log: 
,07-08 14:03:23.631  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.631  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7777323 added. We now have 2 listener(s)
07-08 14:03:23.631  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-08 14:03:23.632  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.632  3075  3094 D BtGatt.ScanManager: Starting BLE batch scan
,07-08 14:03:23.632  3075  3094 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-08 14:03:23.633  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-08 14:03:23.634  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-08 14:03:23.634  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-08 14:03:23.634  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-08 14:03:23.634  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@302e020 added. We now have 9 listener(s)
07-08 14:03:23.634  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.637  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:03:23.642  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.646  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:23.648  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.648  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:23.649  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.651  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:23.652  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.652  2766  2813 I jxcore-log: 
07-08 14:03:23.652  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-08 14:03:23.653  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1d439e added. We now have 3 listener(s)
,07-08 14:03:23.654  3075  3091 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-08 14:03:23.654  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.656  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.656  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:03:23.656  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.656  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.656  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4441e7f added. We now have 10 listener(s)
,07-08 14:03:23.656  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.657  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.657  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:03:23.657  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:23.657  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.659  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.659  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-08 14:03:23.659  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.659  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7777323 removed from the list
07-08 14:03:23.659  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.659  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@302e020 removed from the list
07-08 14:03:23.659  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:23.659  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.660  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.661  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.661  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.661  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.661  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.661  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@302e020 not in the list
07-08 14:03:23.661  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.661  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.662  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.662  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.662  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.663  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4441e7f removed from the list
,07-08 14:03:23.663  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.663  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.663  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.663  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-08 14:03:23.663  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1d439e removed from the list
07-08 14:03:23.663  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-08 14:03:23.664  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c added. We now have 2 listener(s)
07-08 14:03:23.672  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-08 14:03:23.672  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.672  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
07-08 14:03:23.672  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-08 14:03:23.672  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-08 14:03:23.672  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-08 14:03:23.672  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 added. We now have 9 listener(s)
,07-08 14:03:23.673  2766  2806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-08 14:03:23.676  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-08 14:03:23.687  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-08 14:03:23.687  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:03:23.687  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.688  3075  3094 D BtGatt.ScanManager: stopping BLe Batch
,07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.690  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-08 14:03:23.693  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.693  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:23.694  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-08 14:03:23.694  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-08 14:03:23.694  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-08 14:03:23.694  2766  2806 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-08 14:03:23.700  2766  2806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,07-08 14:03:23.700  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-08 14:03:23.700  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:03:23.700  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:03:23.701  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.701  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:03:23.701  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:23.701  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.701  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.702  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-08 14:03:23.702  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,07-08 14:03:23.702  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-08 14:03:23.702  2766  2806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c removed from the list
,07-08 14:03:23.702  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.702  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 removed from the list
07-08 14:03:23.702  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-08 14:03:23.702  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.702  3075  3094 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:03:23.705  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.706  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.706  2766  2813 I jxcore-log: 
,07-08 14:03:23.708  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.708  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.709  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.709  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.709  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.709  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.709  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.709  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:23.710  2766  2806 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-08 14:03:23.711  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:23.711  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.711  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:23.711  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.711  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.711  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.711  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:23.712  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.712  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:23.712  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.712  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.712  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.712  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.712  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.712  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.712  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.712  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.712  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:23.715  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-08 14:03:23.715  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,07-08 14:03:23.716  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-08 14:03:23.717  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-08 14:03:23.718  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-08 14:03:23.718  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-08 14:03:23.718  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.718  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:23.719  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.719  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.719  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.719  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
,07-08 14:03:23.719  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.719  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:23.719  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.719  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.719  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.719  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.719  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.720  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.720  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.720  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:23.720  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:23.721  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:23.721  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.721  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:23.722  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:23.722  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.722  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.722  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:23.722  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.722  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:23.722  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:23.722  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.722  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:23.722  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.722  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.722  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:23.723  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:23.723  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.723  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:23.724  2766  2806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-08 14:03:23.727  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.728  3075  3091 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:03:23.728  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-08 14:03:23.731  2766  2806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-08 14:03:23.734  2766  2806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-08 14:03:23.734  2766  2806 D io.jxcore.node.ConnectivityMonitor: start: OK
07-08 14:03:23.735  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.737  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-08 14:03:23.738  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-08 14:03:23.738  2766  2813 I jxcore-log: 
,07-08 14:03:23.735  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.738  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-08 14:03:23.739  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.739  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-08 14:03:23.741  2766  2806 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:03:23.741  2766  2806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-08 14:03:23.745  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:23.746  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:23.746  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-08 14:03:23.746  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-08 14:03:23.746  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-08 14:03:23.746  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-08 14:03:23.747  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.749  3075  3085 D BtGatt.GattService: registerClient() - UUID=a158a07e-d606-483b-8a9d-d0bb687997ec
07-08 14:03:23.750  3075  3091 D BtGatt.GattService: onClientRegistered() - UUID=a158a07e-d606-483b-8a9d-d0bb687997ec, clientIf=5
,07-08 14:03:23.750  2766  2777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-08 14:03:23.751  3075  3112 D BtGatt.GattService: start scan with filters
07-08 14:03:23.753  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-08 14:03:23.753  3075  3094 D BtGatt.ScanManager: handling starting scan
07-08 14:03:23.753  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-08 14:03:23.753  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-08 14:03:23.753  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-08 14:03:23.754  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:03:23.754  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: false
07-08 14:03:23.754  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-08 14:03:23.758  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:03:23.759  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-08 14:03:23.759  2766  2766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-08 14:03:23.759  2766  2766 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-08 14:03:23.759  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-08 14:03:23.759  2766  2806 I io.jxcore.node.ConnectionHelper: start: OK
07-08 14:03:23.761  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.761  2766  2813 I jxcore-log: 
07-08 14:03:23.762  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-08 14:03:23.762  2766  2813 I jxcore-log: 
07-08 14:03:23.765  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:23.766  3075  3091 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-08 14:03:23.766  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.767  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.767  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:23.767  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 5 listener(s) left
07-08 14:03:23.767  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-08 14:03:23.767  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:03:23.767  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:03:23.767  3075  3094 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-08 14:03:23.767  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:03:23.767  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-08 14:03:23.768  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:23.768  3075  3086 D BtGatt.GattService: stopScan() - queue size =1
07-08 14:03:23.771  3075  3110 D BtGatt.GattService: unregisterClient() - clientIf=5
07-08 14:03:23.771  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:23.771  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-08 14:03:23.771  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-08 14:03:23.771  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-08 14:03:23.773  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-08 14:03:23.773  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.773  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:23.773  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:03:23.773  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:23.773  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:03:23.773  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-08 14:03:23.774  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:23.774  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:23.774  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:23.778  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-08 14:03:23.778  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:23.778  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:23.778  2766  2766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:03:23.778  3075  3094 D BtGatt.ScanManager: Starting BLE batch scan
07-08 14:03:23.779  3075  3094 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-08 14:03:23.782  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:23.783  2766  2766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:23.783  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:03:23.783  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:23.788  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:03:23.788  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
07-08 14:03:23.788  2766  2766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:23.788  2766  2766 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-08 14:03:23.788  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:23.790  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.790  2766  2813 I jxcore-log: 
,07-08 14:03:23.791  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:23.791  2766  2813 I jxcore-log: 
07-08 14:03:23.791  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:23.995  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:23.995  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:03:23.995  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:23.995  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:23.996  2766  2806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:03:23.996  2766  2806 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,07-08 14:03:23.996  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-08 14:03:24.001  3075  3091 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-08 14:03:24.001  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:24.005  2766  2806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:03:24.005  2766  2806 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-08 14:03:24.005  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,07-08 14:03:24.005  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-08 14:03:24.005  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-08 14:03:24.005  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,07-08 14:03:24.005  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,07-08 14:03:24.006  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-08 14:03:24.007  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-08 14:03:24.040  3075  3091 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-08 14:03:24.041  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-08 14:03:24.041  3075  3094 D BtGatt.ScanManager: stopping BLe Batch
07-08 14:03:24.050   590   600 I art     : Background partial concurrent mark sweep GC freed 21347(1212KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 17MB/26MB, paused 9.173ms total 372.786ms
07-08 14:03:24.051  3075  3091 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-08 14:03:24.051  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:24.051  3075  3094 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-08 14:03:24.025  2766  2806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-08 14:03:24.055  2766  2806 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-08 14:03:24.061  3075  3091 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-08 14:03:24.061  3075  3091 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-08 14:03:24.063  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:24.064  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.064  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.064  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:24.065  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.065  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.065  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.065  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.065  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.065  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:24.065  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.065  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.065  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.065  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:03:24.065  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.065  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.065  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:03:24.066  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:24.066  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.066  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.066  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.066  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:24.068  2766  2806 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-08 14:03:24.068  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.068  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.068  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:24.069  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.069  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.069  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.069  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.069  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.069  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.069  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:24.069  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.069  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.070  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.070  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.070  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.070  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.070  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.071  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.071  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.071  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.071  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.071  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.071  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.072  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.072  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:24.072  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.072  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.072  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.072  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.073  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.073  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.073  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.073  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.073  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.073  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.073  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.073  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.073  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.073  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.074  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.074  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.074  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.074  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.074  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.074  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.075  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.075  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:24.075  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.075  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.075  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.075  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.075  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.075  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.076  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.076  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.076  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.076  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.076  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.076  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.076  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.076  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.077  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:24.077  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.077  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.077  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.077  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.077  2766  2806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-08 14:03:24.078  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:24.078  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.078  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.078  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.078  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.078  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.078  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.078  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.078  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.078  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:24.078  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.078  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.079  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.079  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
,07-08 14:03:24.079  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.079  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.079  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.079  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-08 14:03:24.079  2766  2813 I jxcore-log: 
,07-08 14:03:24.080  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.080  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.080  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.080  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.080  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:24.080  2766  2806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-08 14:03:24.080  2766  2806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-08 14:03:24.081  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-08 14:03:24.082  2766  2806 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,07-08 14:03:24.082  2766  2806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-08 14:03:24.082  2766  2806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-08 14:03:24.082  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:03:24.082  2766  2806 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-08 14:03:24.082  2766  2806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-08 14:03:24.082  2766  2806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-08 14:03:24.082  2766  2806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-08 14:03:24.082  2766  2806 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-08 14:03:24.083  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:24.083  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.083  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.083  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-08 14:03:24.083  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.083  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.083  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.083  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.083  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:24.083  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.083  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.083  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.083  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.083  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.084  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.084  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.084  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.084  2766  2806 D BluetoothAdapter: STATE_ON
,07-08 14:03:24.084  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.084  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.085  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.085  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:24.086  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.086  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.086  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.086  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.086  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.086  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.086  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.086  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.086  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.086  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.086  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.087  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.087  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.087  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.087  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.087  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.087  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.087  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.087  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.087  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.087  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.087  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.087  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.087  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.088  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.088  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.088  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.088  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.088  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.088  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.088  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.088  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.089  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.089  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.089  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:03:24.089  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.089  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.090  2766  2806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-08 14:03:24.090  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:24.091  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-08 14:03:24.093  2766  2806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-08 14:03:24.093  2766  2806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-08 14:03:24.093  2766  2766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-08 14:03:24.093  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-08 14:03:24.094  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.094  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-08 14:03:24.094  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-08 14:03:24.094  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-08 14:03:24.094  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: No Bluetooth server socket to close
,07-08 14:03:24.094  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.094  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.094  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.094  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-08 14:03:24.094  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-08 14:03:24.094  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-08 14:03:24.094  2766  2806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-08 14:03:24.095  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.095  2766  2806 D BluetoothLeScanner: could not find callback wrapper
,07-08 14:03:24.095  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.095  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.095  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-08 14:03:24.096  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.096  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.096  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.096  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.096  2766  2806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:24.096  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:24.096  2766  3130 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-08 14:03:24.096  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-08 14:03:24.096  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-08 14:03:24.096  2766  3130 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-08 14:03:24.098  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-08 14:03:24.099  2766  2766 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-08 14:03:24.102  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-08 14:03:24.102  2766  2766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-08 14:03:24.102  2766  2766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-08 14:03:24.102  2766  2766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-08 14:03:24.104  2766  2766 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-08 14:03:24.105  2766  2766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-08 14:03:24.105  2766  2766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-08 14:03:24.105  2766  2766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-08 14:03:24.105  2766  2766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-08 14:03:24.105  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.105  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.105  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.105  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.106  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.106  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.106  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:03:24.106  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.106  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.107  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.107  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.107  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.107  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
07-08 14:03:24.107  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.107  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.107  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:03:24.107  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-08 14:03:24.107  2766  2813 I jxcore-log: 
07-08 14:03:24.108  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.108  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.108  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.108  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.108  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.109  2766  2806 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,07-08 14:03:24.109  2766  2806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-08 14:03:24.109  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-08 14:03:24.113  2766  2806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-08 14:03:24.113  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.113  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:03:24.113  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.113  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.114  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.114  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.114  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
,07-08 14:03:24.114  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.114  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.114  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.114  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.114  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.115  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.115  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.115  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.115  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.115  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.116  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.116  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.116  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-08 14:03:24.116  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.116  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.121  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.121  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.121  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-08 14:03:24.121  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.121  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.121  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.121  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.121  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.121  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.121  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.121  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.122  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.122  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.122  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.122  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.122  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.122  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-08 14:03:24.122  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.123  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.123  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.123  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.123  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.123  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.123  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.123  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.123  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.124  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.124  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.124  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.124  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.124  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.124  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.124  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.124  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.124  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.124  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.124  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.124  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.124  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.125  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.125  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.125  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.125  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.125  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:24.126  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.126  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.127  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.127  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.127  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.127  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.127  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.127  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.127  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.127  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
,07-08 14:03:24.127  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.127  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.127  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.127  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.127  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.128  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-08 14:03:24.128  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.129  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.129  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.129  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.129  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.129  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.130  2766  2806 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 00:11:22:33:44:55]
,07-08 14:03:24.130  2766  2806 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID 00:11:22:33:44:55
07-08 14:03:24.131  2766  2766 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 00:11:22:33:44:55], Bluetooth address: 00:11:22:33:44:55, device name: , device address: 
07-08 14:03:24.133  2766  2806 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 00:11:22:33:44:55], added - the peer count is 1
07-08 14:03:24.133  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-08 14:03:24.133  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.133  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.134  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.134  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.134  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.134  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.134  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.135  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.135  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.135  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.135  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.135  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.135  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.134  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
07-08 14:03:24.134  2766  2813 I jxcore-log: 
07-08 14:03:24.135  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.135  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.136  2766  2806 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,07-08 14:03:24.136  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.136  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.136  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.137  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.137  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.137  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.137  2766  2806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-08 14:03:24.137  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-08 14:03:24.137  2766  2806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-08 14:03:24.137  2766  2806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-08 14:03:24.137  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.137  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.137  2766  2806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@785de4c not in the list
07-08 14:03:24.137  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-08 14:03:24.139  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
07-08 14:03:24.139  2766  2806 D io.jxcore.node.ConnectivityMonitor: stop
07-08 14:03:24.139  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.139  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.139  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-08 14:03:24.139  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 2 listener(s) left
07-08 14:03:24.139  2766  2806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-08 14:03:24.139  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-08 14:03:24.139  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-08 14:03:24.140  2766  2806 D BluetoothAdapter: STATE_ON
07-08 14:03:24.140  2766  2806 D BluetoothLeScanner: could not find callback wrapper
07-08 14:03:24.140  2766  2806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-08 14:03:24.140  2766  2806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-08 14:03:24.140  2766  2806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@882fe95 not in the list
,07-08 14:03:24.141  2766  2806 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 87
07-08 14:03:24.141  2766  2806 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 87
07-08 14:03:24.141  2766  2806 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-08 14:03:24.141  2766  2806 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-08 14:03:24.141  2766  2806 E com.test.thalitest.ThaliTestRunner: Total duration: 30086 ms
07-08 14:03:24.141  2766  2806 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 30277ms. Plugin should use CordovaInterface.getThreadPool().
,07-08 14:03:24.711  3125  3125 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-08 14:03:24.725   590   662 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-08 14:03:24.731   590   662 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,07-08 14:03:24.731   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:03:24.739   590   662 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-08 14:03:24.771   590   662 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-08 14:03:25.128  3125  3125 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-08 14:03:25.147  3125  3125 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-08 14:03:25.147  3125  3125 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-08 14:03:25.151   590   662 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:03:25.158   590   662 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:03:25.158   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-08 14:03:25.158   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-08 14:03:25.169   590   662 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-08 14:03:25.179   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:25.186   590   662 D WifiStateMachine: Start Dhcp Watchdog 3
,07-08 14:03:25.192   590   662 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{1}, ntable=[]
,07-08 14:03:25.210   590  3134 D DhcpClient: Receive thread started
,07-08 14:03:25.290   590   662 E native  : do suspend false
,07-08 14:03:25.302   590  3133 D DhcpClient: Broadcasting DHCPDISCOVER
,07-08 14:03:25.309   590  3134 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 OFFER, ip /192.168.1.110, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172779, domain null
07-08 14:03:25.310   590  3133 D DhcpClient: Got pending lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172779 seconds
,07-08 14:03:25.311   590  3133 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.110 serverid=192.168.1.1
,07-08 14:03:25.318   590  3134 D DhcpClient: Received packet: 50:2e:5c:e5:0c:a7 ACK: your new IP /192.168.1.110, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-08 14:03:25.319   590  3133 D DhcpClient: Confirmed lease: IP address 192.168.1.110/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-08 14:03:25.320   218   621 D CommandListener: Setting iface cfg
,07-08 14:03:25.325   590   662 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{2}, ntable=[]
,07-08 14:03:25.326   590  3133 D DhcpClient: Scheduling renewal in 86399s
,07-08 14:03:25.327   590   662 E native  : do suspend true
,07-08 14:03:25.341   590   662 D IpReachabilityMonitor: watch: iface{wlan0/6}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-08 14:03:25.342   590   662 D WifiConfigStore: No blacklist allowed without epno enabled
,07-08 14:03:25.342   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-08 14:03:25.344   590   662 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-08 14:03:25.349   590   664 D ConnectivityService: Adding iface wlan0 to network 102
,07-08 14:03:25.398   590   664 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-08 14:03:25.398   590   664 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-08 14:03:25.400   590   664 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-08 14:03:25.401   590   664 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-08 14:03:25.402   590   664 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-08 14:03:25.413   590   664 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:03:25.418   590   664 D ConnectivityService: scheduleUnvalidatedPrompt 102
07-08 14:03:25.419   590   664 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
07-08 14:03:25.419   590   664 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-08 14:03:25.419   590   662 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-08 14:03:25.419   590   664 D ConnectivityService:    accepting network in place of null
07-08 14:03:25.420   590   662 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-08 14:03:25.421   590   664 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::522e:5cff:fee5:ca7/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-08 14:03:25.435   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202999, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:03:25.462   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:03:25.504   218   621 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-08 14:03:25.510   590   664 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
07-08 14:03:25.510   590   664 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-08 14:03:25.512   590   664 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-08 14:03:25.515   590   627 D Tethering: MasterInitialState.processMessage what=3
07-08 14:03:25.519   590  3131 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:807::200e
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-08 14:03:25.527  2766  2766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-08 14:03:25.529  2766  2766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-08 14:03:25.531  2766  2813 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-08 14:03:25.531  2766  2813 I jxcore-log: 
07-08 14:03:25.535  1097  1097 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-08 14:03:25.591  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:03:25.594  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:03:25.608   590  3131 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jul 2016 12:03:25 GMT], X-Android-Received-Millis=[1467979405607], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1467979405559]}
,07-08 14:03:25.608  2579  3144 V GoogleAuthProtoRequest: [249] a.<init>: mAccountName set to: thalitester@gmail.com
07-08 14:03:25.608   590   664 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-08 14:03:25.608   590   664 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,07-08 14:03:25.609   590   664 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:03:25.610   590   664 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-08 14:03:25.622  1171  1171 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-08 14:03:25.628  1171  2248 I iu.UploadsManager: num queued entries: 0
,07-08 14:03:25.631  1171  2248 I iu.UploadsManager: num updated entries: 0
,07-08 14:03:25.637  1171  1171 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-08 14:03:25.640  1171  1171 I Kids    : [GCoreUtils] Current gmscore version, 8186446 is smaller than the required version 8400000
,07-08 14:03:25.657  1171  3147 I MDM     : [202] SitrepService.onHandleIntent: sending sitrep: [0, 2, [Dm42Sezn61r6yJxW_kdgWJ-UM6U], null]
,07-08 14:03:25.657  1171  3147 W BaseAppContext: Using Auth Proxy for data requests.
,07-08 14:03:25.664  1171  3147 V GoogleAuthProtoRequest: [202] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:03:25.669  1171  2248 I iu.SyncManager: NEXT; no task
,07-08 14:03:25.708  1078  1090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-08 14:03:25.709  1078  1090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-08 14:03:25.710  1078  1090 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:03:25.710  1078  1090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:03:25.731  1078  1091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager,
07-08 14:03:25.731  1078  1091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-08 14:03:25.732  1078  1091 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:03:25.732  1078  1091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:03:25.755  2579  3144 W ExperimentUpdateService: [249] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: [249] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:03:25.756  2579  3144 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:03:25.763  1171  3147 E MDM     : [202] SitrepService.a: Error sending sitrep.
,07-08 14:03:25.794  2907  3150 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-08 14:03:26.414  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-08 14:03:26.414  2766  2806 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,07-08 14:03:26.599  2766  2806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-08 14:03:26.599  2766  2806 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,07-08 14:03:33.420   590   664 D ConnectivityService: handlePromptUnvalidated 102
,07-08 14:03:39.579   992  1093 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-08 14:03:39.579   992  1093 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-08 14:03:39.607  1078  1078 I ConfigService: onCreate
,07-08 14:03:44.641  1078  1078 I ConfigService: onDestroy
,07-08 14:03:53.497   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=231060, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:04:13.294  3075  3103 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-08 14:04:19.513  2036  3158 V KeepSync: Connecting to GoogleApiClient
,07-08 14:04:19.513   590  1959 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-08 14:04:19.556  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:04:19.558  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:04:19.579  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:04:19.579  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:04:19.579  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:04:19.580  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:04:19.594  1171  3159 V BaseAuthAsyncOperation: access token request failed
,07-08 14:04:19.595  2036  3158 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:04:19.699  1078  1356 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-08 14:04:19.700  1078  1356 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:04:19.700  1078  1356 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:04:19.700  1078  1356 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:04:19.716  2036  3158 E KeepSync: IOException
07-08 14:04:19.716  2036  3158 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:04:19.716  2036  3158 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:04:19.716  2036  3158 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:04:19.716  2036  3158 E KeepSync: 	... 10 more
07-08 14:04:19.716  2036  3158 W KeepSync: Sync result 2
,07-08 14:04:19.722   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 256720, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:04:40.805   590  1308 I ActivityManager: Start proc 3160:com.google.android.youtube/u0a81 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-08 14:04:40.886  3160  3160 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,07-08 14:04:41.191  3160  3172 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,07-08 14:04:41.322  3160  3172 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-08 14:04:41.394  3160  3172 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-08 14:04:41.530  3160  3160 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-08 14:04:41.709  3187  3187 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads887810829.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads887810829.dex
,07-08 14:04:41.802  3160  3160 W InstanceID/Rpc: Found 10007
,07-08 14:04:41.954  3187  3187 I dex2oat : dex2oat took 245.841ms (threads: 2) arena alloc=242KB java alloc=37KB native alloc=757KB free=66KB
,07-08 14:04:46.983   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284547, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:04:51.362  2036  3244 V KeepSync: Connecting to GoogleApiClient
,07-08 14:04:51.363   590   611 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-08 14:04:51.412  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:04:51.415  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:04:51.441  1078  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:04:51.441  1078  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:04:51.442  1078  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:04:51.442  1078  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:04:51.458  1171  3246 V BaseAuthAsyncOperation: access token request failed
,07-08 14:04:51.460  2036  3244 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:04:51.509  1078  1305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:04:51.509  1078  1305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:04:51.509  1078  1305 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:04:51.509  1078  1305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:04:51.524  2036  3244 E KeepSync: IOException
07-08 14:04:51.524  2036  3244 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:04:51.524  2036  3244 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:04:51.524  2036  3244 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:04:51.524  2036  3244 E KeepSync: 	... 10 more
,07-08 14:04:51.524  2036  3244 W KeepSync: Sync result 2
,07-08 14:04:51.531   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 288807, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:05:21.655  2716  3248 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:05:21.683  2716  3249 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:05:21.697  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:21.699  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:21.723  1078  1091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:05:21.723  1078  1091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:05:21.723  1078  1091 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:21.723  1078  1091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:21.758  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:21.759  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:21.783  1078  1305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:05:21.783  1078  1305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:05:21.783  1078  1305 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:05:21.783  1078  1305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:21.797  2716  3249 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:05:21.798  2716  3248 E BooksSync: Soft error
07-08 14:05:21.798  2716  3248 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:05:21.798  2716  3248 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:05:21.798  2716  3248 E BooksSync: Sync error
07-08 14:05:21.798  2716  3248 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:05:21.798  2716  3248 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:05:21.798  2716  3248 I BooksSync: Finished books sync
,07-08 14:05:21.803   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 294571, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:05:25.842  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:25.848  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:25.876  2579  3250 V GoogleAuthProtoRequest: [250] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:05:25.914  1078  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-08 14:05:25.914  1078  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:05:25.914  1078  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:25.914  1078  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:25.934  2579  3250 W ExperimentUpdateService: [250] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: [250] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:05:25.936  2579  3250 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:05:33.157   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330720, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:05:39.598   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=337161, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:05:48.153  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:48.171  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:48.175  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:48.204  1078  1305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-08 14:05:48.204  1078  1305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-08 14:05:48.205  1078  1305 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:48.205  1078  1305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:48.226  1078  1305 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-08 14:05:48.226  1078  1305 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-08 14:05:48.226  1078  1305 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-08 14:05:48.226  1078  1305 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-08 14:05:48.226  1078  1305 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-08 14:05:48.226  1078  1305 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-08 14:05:48.226  1078  1305 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:05:48.231  2465  2506 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-08 14:05:48.231  2465  2506 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-08 14:05:48.231  2465  2506 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-08 14:05:48.231  2465  2506 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-08 14:05:48.231  2465  2506 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-08 14:05:48.231  2465  2506 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-08 14:05:48.231  2465  2506 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-08 14:05:54.024  2716  3254 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:05:54.060  2716  3255 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:05:54.077  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:54.080  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:54.114  1078  1091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:05:54.114  1078  1091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:05:54.114  1078  1091 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:54.114  1078  1091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:54.146  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:54.149  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:05:54.178  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:05:54.178  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:05:54.178  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:05:54.179  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:05:54.201  2716  3255 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:05:54.203  2716  3254 E BooksSync: Soft error
07-08 14:05:54.203  2716  3254 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:05:54.203  2716  3254 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:05:54.203  2716  3254 E BooksSync: Sync error
07-08 14:05:54.203  2716  3254 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:05:54.203  2716  3254 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:05:54.203  2716  3254 I BooksSync: Finished books sync
,07-08 14:05:54.208   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 351551, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:06:16.091   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=373654, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:06:24.454  2036  3256 V KeepSync: Connecting to GoogleApiClient
,07-08 14:06:24.456   590   611 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-08 14:06:24.541  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:06:24.546  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:06:24.569  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:06:24.569  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:06:24.569  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:06:24.569  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:06:24.584  1171  3257 V BaseAuthAsyncOperation: access token request failed
,07-08 14:06:24.585  2036  3256 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:06:24.635  1078  1091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:06:24.635  1078  1091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:06:24.635  1078  1091 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:06:24.636  1078  1091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:06:24.652  2036  3256 E KeepSync: IOException
07-08 14:06:24.652  2036  3256 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:06:24.652  2036  3256 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:06:24.652  2036  3256 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:06:24.652  2036  3256 E KeepSync: 	... 10 more
07-08 14:06:24.652  2036  3256 W KeepSync: Sync result 2
,07-08 14:06:24.657   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 352136, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:06:58.679  2716  3258 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:06:58.730  2716  3259 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:06:58.754  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:06:58.759  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:06:58.809  1078  1356 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:06:58.809  1078  1356 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:06:58.810  1078  1356 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:06:58.810  1078  1356 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:06:58.864  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:06:58.868  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:06:58.915  1078  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-08 14:06:58.916  1078  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:06:58.916  1078  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:06:58.916  1078  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-08 14:06:58.951  2716  3259 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:06:58.953  2716  3258 E BooksSync: Soft error
07-08 14:06:58.953  2716  3258 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:06:58.953  2716  3258 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:06:58.954  2716  3258 E BooksSync: Sync error
07-08 14:06:58.954  2716  3258 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:06:58.954  2716  3258 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:06:58.954  2716  3258 I BooksSync: Finished books sync
,07-08 14:06:58.970   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 416140, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:07:13.359  1171  1171 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-08 14:07:13.365  1171  3260 I ConfigFetchService: running network task: configservice_periodic
,07-08 14:07:13.368  1171  3260 E WakeLock: callingPackage is not supposed to be empty for wakelock Config Service fetch!
07-08 14:07:13.368  1171  3260 E WakeLock: java.lang.IllegalArgumentException
07-08 14:07:13.368  1171  3260 E WakeLock: 	at com.google.android.gms.stats.d.<init>(SourceFile:135)
07-08 14:07:13.368  1171  3260 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:341)
07-08 14:07:13.368  1171  3260 E WakeLock: 	at com.google.android.gms.config.ConfigFetchService.a(SourceFile:159)
07-08 14:07:13.368  1171  3260 E WakeLock: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-08 14:07:13.370  1171  3260 I ConfigFetchService: launchTask
07-08 14:07:13.370  1078  1078 I ConfigService: onCreate
,07-08 14:07:13.384  1171  1171 I ConfigFetchService: service connected
,07-08 14:07:13.388  1171  1171 D ConfigFetchService: ConfigApi connection successful.
,07-08 14:07:23.420  1171  3261 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UAWOwfWdNuaR3KMWb2QFvrEhM6Kd21GUBxFaA1z370TSwYS1px7nan3hk5wFJhKFuNb_RGUS8KFNg9lUHX8WdSoALiR52FT4Lgbrbw3LddVacvb8fQQ6pO6UniGqBXYbKeX8_7Bh4XIE23wy_HALzqB4fO1ajVSTc8grseE7MwSt_Gt2Ji8m44y5HC-iPqquGkBg3QsJMvC4YQqY_KWJvmK7dSzvY5RU2rTr1Gbu8wP6y8Oyc
,07-08 14:07:23.470  1171  3261 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-08 14:07:23.851  1171  3261 I ConfigFetchTask: updating config table for com.google.android.gms
,07-08 14:07:23.899  1171  1171 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,07-08 14:07:23.905  1171  1171 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-08 14:07:23.905  1171  1171 I ConfigFetchService: GmsCore config value changed; rescheduling
,07-08 14:07:23.910  1171  1171 I ConfigFetchService: fetch service done; releasing wakelock
,07-08 14:07:23.927  1171  3265 I ConfigFetchService: self-hosted config:fetch_interval = 43200
,07-08 14:07:23.952  1171  3265 I ConfigFetchService: stopping self
,07-08 14:07:24.044  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:07:24.056  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:07:24.058  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:07:24.090  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,07-08 14:07:24.091  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
07-08 14:07:24.091  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:07:24.091  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:07:24.109  1171  3266 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
,07-08 14:07:24.211   590   600 I art     : Background partial concurrent mark sweep GC freed 31057(2029KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 17MB/26MB, paused 2.132ms total 103.312ms
,07-08 14:07:28.504   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=446067, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:07:28.964  1078  1078 I ConfigService: onDestroy
,07-08 14:07:51.717   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=469281, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:08:30.625   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=508188, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:08:30.829  2036  3269 V KeepSync: Connecting to GoogleApiClient
07-08 14:08:30.830   590  1984 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-08 14:08:30.884  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:30.887  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:08:30.912  1078  1355 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:08:30.912  1078  1355 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:08:30.912  1078  1355 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:08:30.912  1078  1355 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:08:30.930  1171  3270 V BaseAuthAsyncOperation: access token request failed
,07-08 14:08:30.932  2036  3269 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:08:30.988  1078  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-08 14:08:30.988  1078  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:08:30.989  1078  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:08:30.989  1078  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:08:31.004  2036  3269 E KeepSync: IOException
07-08 14:08:31.004  2036  3269 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:08:31.004  2036  3269 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:08:31.004  2036  3269 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:08:31.004  2036  3269 E KeepSync: 	... 10 more
,07-08 14:08:31.004  2036  3269 W KeepSync: Sync result 2
,07-08 14:08:31.010   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 508303, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:08:58.170   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=535734, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:09:07.924  2716  3271 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:09:07.942  2716  3273 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:09:07.950  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:07.952  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:07.973  1078  1090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:09:07.974  1078  1090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:09:07.974  1078  1090 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:07.974  1078  1090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:07.997  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:07.999  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:08.018  1078  1356 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:09:08.018  1078  1356 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:09:08.018  1078  1356 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:09:08.018  1078  1356 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:08.032  2716  3273 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:09:08.033  2716  3271 E BooksSync: Soft error
07-08 14:09:08.033  2716  3271 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:09:08.033  2716  3271 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:09:08.034  2716  3271 E BooksSync: Sync error
07-08 14:09:08.034  2716  3271 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:09:08.034  2716  3271 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:09:08.034  2716  3271 I BooksSync: Finished books sync
,07-08 14:09:08.038   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 545270, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:09:10.676   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=548240, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:09:26.003  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:26.008  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:09:26.028  2579  3274 V GoogleAuthProtoRequest: [251] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:09:26.083  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-08 14:09:26.084  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:09:26.084  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:09:26.084  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:09:26.097  2579  3274 W ExperimentUpdateService: [251] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: [251] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:09:26.098  2579  3274 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:09:38.277   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=575840, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:09:47.050   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=584614, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:10:09.851   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=607414, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:10:53.558   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=651121, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:11:21.104   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=678667, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:11:28.918   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=686481, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:11:56.518   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=714081, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:12:28.865   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=746428, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:12:43.254  2036  3283 V KeepSync: Connecting to GoogleApiClient
,07-08 14:12:43.255   590  1984 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-08 14:12:43.344  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:43.348  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:43.393  1078  1356 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:12:43.393  1078  1356 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:12:43.394  1078  1356 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:12:43.394  1078  1356 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:12:43.431  1171  3284 V BaseAuthAsyncOperation: access token request failed
,07-08 14:12:43.434  2036  3283 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:12:43.545  1078  1355 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:12:43.546  1078  1355 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-08 14:12:43.546  1078  1355 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:12:43.550  1078  1355 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:12:43.582  2036  3283 E KeepSync: IOException
07-08 14:12:43.582  2036  3283 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:12:43.582  2036  3283 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:12:43.582  2036  3283 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:12:43.582  2036  3283 E KeepSync: 	... 10 more
07-08 14:12:43.582  2036  3283 W KeepSync: Sync result 2
,07-08 14:12:43.587   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 760734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:12:56.464   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=774027, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:12:59.859  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-08 14:12:59.861  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:12:59.870  2579  3285 V GoogleAuthProtoRequest: [252] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:12:59.890  1078  1355 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-08 14:12:59.890  1078  1355 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:12:59.890  1078  1355 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:12:59.890  1078  1355 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: [252] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: [252] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:12:59.906  2579  3285 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:13:25.704  2716  3287 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:13:25.758  2716  3288 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:13:25.778  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:25.782  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:25.829  1078  1356 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:13:25.830  1078  1356 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:13:25.830  1078  1356 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:13:25.830  1078  1356 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:13:25.881  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:25.886  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:25.928  1078  1090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-08 14:13:25.928  1078  1090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:13:25.928  1078  1090 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:13:25.929  1078  1090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-08 14:13:25.944  2716  3288 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:13:25.949  2716  3287 E BooksSync: Soft error
07-08 14:13:25.949  2716  3287 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:13:25.949  2716  3287 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:13:25.949  2716  3287 E BooksSync: Sync error
07-08 14:13:25.949  2716  3287 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:13:25.949  2716  3287 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:13:25.949  2716  3287 I BooksSync: Finished books sync
,07-08 14:13:25.957   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 803075, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:13:30.045  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:30.047  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:13:30.057  2579  3290 V GoogleAuthProtoRequest: [253] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:13:30.079  1078  1355 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-08 14:13:30.080  1078  1355 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:13:30.080  1078  1355 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:13:30.081  1078  1355 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:13:30.094  2579  3290 W ExperimentUpdateService: [253] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: [253] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:13:30.095  2579  3290 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:14:30.248  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-08 14:14:30.250  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:14:30.262  2579  3291 V GoogleAuthProtoRequest: [254] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:14:30.283  1078  1305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-08 14:14:30.284  1078  1305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:14:30.284  1078  1305 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:14:30.284  1078  1305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:14:30.298  2579  3291 W ExperimentUpdateService: [254] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: [254] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:14:30.299  2579  3291 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:15:30.085   590   623 I ActivityManager: Start proc 3292:com.google.android.deskclock/u0a38 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,07-08 14:15:30.199  3292  3292 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,07-08 14:15:30.233  3292  3292 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-08 14:15:30.233  3292  3292 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-08 14:15:30.233  3292  3292 I GAv4    :   adb logcat -s GAv4
,07-08 14:15:30.248  3292  3292 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:15:30.254  3292  3292 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:15:30.269  3292  3309 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-08 14:15:30.324   590  1959 I ActivityManager: Killing 1248:com.google.android.gms.wearable/u0a7 (adj 15): empty #17
,07-08 14:16:30.403  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:16:30.405  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:16:30.420  2579  3310 V GoogleAuthProtoRequest: [255] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:16:30.442  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-08 14:16:30.442  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:16:30.443  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:16:30.443  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:16:30.460  2579  3310 W ExperimentUpdateService: [255] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: [255] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:16:30.461  2579  3310 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:17:26.186  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:17:26.188  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:17:26.198  2579  3311 V GoogleAuthProtoRequest: [256] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:17:26.226  1078  1509 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-08 14:17:26.226  1078  1509 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-08 14:17:26.227  1078  1509 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:17:26.227  1078  1509 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:17:26.242  2579  3311 W ExperimentUpdateService: [256] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: [256] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:17:26.243  2579  3311 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:18:20.719  3075  3090 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-08 14:19:35.224   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172787, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-08 14:19:47.184   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1184747, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-08 14:20:23.351   590   622 I UsageStatsService: User[0] Flushing usage stats to disk
,07-08 14:20:30.584  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:20:30.586  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:20:30.597  2579  3315 V GoogleAuthProtoRequest: [257] a.<init>: mAccountName set to: thalitester@gmail.com
,07-08 14:20:30.619  1078  1356 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-08 14:20:30.619  1078  1356 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-08 14:20:30.619  1078  1356 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:20:30.619  1078  1356 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: [257] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: [257] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-08 14:20:30.633  2579  3315 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-08 14:21:08.052  2036  3316 V KeepSync: Connecting to GoogleApiClient
,07-08 14:21:08.053   590   610 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-08 14:21:08.087  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:21:08.089  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:21:08.110  1078  1147 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-08 14:21:08.110  1078  1147 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-08 14:21:08.110  1078  1147 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:21:08.110  1078  1147 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:21:08.125  1171  3317 V BaseAuthAsyncOperation: access token request failed
,07-08 14:21:08.127  2036  3316 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-08 14:21:08.175  1078  1091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-08 14:21:08.176  1078  1091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-08 14:21:08.176  1078  1091 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:21:08.176  1078  1091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:21:08.198  2036  3316 E KeepSync: IOException
07-08 14:21:08.198  2036  3316 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-08 14:21:08.198  2036  3316 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-08 14:21:08.198  2036  3316 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-08 14:21:08.198  2036  3316 E KeepSync: 	... 10 more
,07-08 14:21:08.198  2036  3316 W KeepSync: Sync result 2
,07-08 14:21:08.208   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1265471, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:22:01.052  2716  3318 I BooksSync: Starting books sync for 61035162, extras: ade
,07-08 14:22:01.070  2716  3319 I BooksConfig: GmsCore Version = 8.1.86 (2287566-446)
,07-08 14:22:01.081  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:22:01.086  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:22:01.112  1078  1091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-08 14:22:01.112  1078  1091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:22:01.112  1078  1091 I GLSUser : [GLSUser] Extracting token using key: Auth
07-08 14:22:01.112  1078  1091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:22:01.137  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:22:01.139  1078  1078 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-08 14:22:01.158  1078  1090 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-08 14:22:01.159  1078  1090 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-08 14:22:01.159  1078  1090 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-08 14:22:01.159  1078  1090 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-08 14:22:01.173  2716  3319 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-08 14:22:01.174  2716  3318 E BooksSync: Soft error
07-08 14:22:01.174  2716  3318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:22:01.174  2716  3318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-08 14:22:01.174  2716  3318 E BooksSync: Sync error
07-08 14:22:01.174  2716  3318 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-08 14:22:01.174  2716  3318 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-08 14:22:01.174  2716  3318 I BooksSync: Finished books sync
,07-08 14:22:01.181   590   622 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1318466, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-08 14:25:14.937   590   654 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-08 14:25:14.940   590   590 V KeyguardServiceDelegate: onStartedWakingUp()
,07-08 14:25:14.941   590   630 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-08 14:25:14.954  2766  2766 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-08 14:25:14.956  2766  2766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-08 14:25:14.953   590   630 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@8ba5a8)
07-08 14:25:14.965  2766  2766 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-08 14:25:14.965  2766  2766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-08 14:25:14.973   590  1043 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-08 14:25:14.979   170   170 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x556abc1430
07-08 14:25:14.979   170   170 D hwcomposer: hwc_blank: display 0: unblank
,07-08 14:25:14.979   170   170 D hwcomposer: hwc_blank_display: display 0: [1 -> 0]
07-08 14:25:14.979   170   170 D hwcomposer: Display 0 layer clip is 1536 x 2048
07-08 14:25:14.979   170   170 D hwcomposer: Display 0 device clip is 1536 x 2048
07-08 14:25:14.981   590   628 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-08 14:25:14.990   590   590 I CwMcuSensor: CwMcuSensor::batch: set IIO buffer length = 4096, success
,07-08 14:25:15.004  1010  1010 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,07-08 14:25:15.011   590   662 D WifiConfigStore: Retrieve network priorities after PNO.
,07-08 14:25:15.014   590   664 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-08 14:25:15.033   590  1984 I ActivityManager: Start proc 3322:com.google.android.apps.fitness/u0a45 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-08 14:25:15.035   590   662 E native  : do suspend false
07-08 14:25:15.043   590   662 D WifiConfigStore: No blacklist allowed without epno enabled
,07-08 14:25:15.116   590   624 I CwMcuSensor: CwMcuSensor::flush: fd = 195, sensors_id = 0, path = /sys/class/htc_sensorhub/sensor_hub/flush, err = 0
,07-08 14:25:15.116   590   630 I DisplayPowerController: Unblocked screen on after 175 ms
07-08 14:25:15.117   590   630 V KeyguardServiceDelegate: onScreenTurnedOn()
,07-08 14:25:15.145  3322  3322 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm64
,07-08 14:25:15.250   590   958 I ActivityManager: Killing 2658:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,07-08 14:25:15.261   590   681 D SurfaceControl: Excessive delay in setPowerMode(): 285ms
,07-08 14:25:18.054   590   664 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,07-08 14:25:20.023   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1517587, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-08 14:25:31.503   590  3132 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1529067, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),07-08 14:26:09.006  3356  3356 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-08 14:26:09.011  3356  3356 D AndroidRuntime: CheckJNI is OFF
07-08 14:26:09.044  3356  3356 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-08 14:26:09.076  3356  3356 I Radio-JNI: register_android_hardware_Radio DONE
07-08 14:26:09.098  3356  3356 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-08 14:26:09.106   590   623 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-08 14:26:09.107   590   623 I ActivityManager: Killing 2766:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-08 14:26:09.142   590   590 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 112)
07-08 14:26:09.144   590   611 I WindowState: WIN DEATH: Window{83febf8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-08 14:26:09.144   590  1959 D GraphicsStats: Buffer count: 2
07-08 14:26:09.144   590   663 D WifiService: Client connection lost with reason: 4
07-08 14:26:09.168   590   633 W PackageSettings: Skipping PackageSetting{c2fe997 com.example.hello/10095} due to missing metadata
07-08 14:26:09.192   590   633 I art     : Starting a blocking GC Explicit
07-08 14:26:09.206   590   623 W ActivityManager: Force removing ActivityRecord{45a782d u0 com.test.thalitest/.MainActivity t62}: app died, no saved state
07-08 14:26:09.214   590   958 W ActivityManager: Spurious death for ProcessRecord{e7381c0 0:com.test.thalitest/u0a0}, curProc for 2766: null
07-08 14:26:09.275   590   958 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 2766 uid 10000
07-08 14:26:09.275   590   633 I art     : Explicit concurrent mark sweep GC freed 29823(1714KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 907us total 80.229ms
07-08 14:26:09.297   590   633 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-08 14:26:09.315   992   992 I Keyboard.Facilitator: onFinishInput()
07-08 14:26:09.360  1097  1097 W LocationOracleImpl: Best location was null
07-08 14:26:09.370  3356  3356 I art     : System.exit called, status: 0
07-08 14:26:09.370  3356  3356 I AndroidRuntime: VM exiting with result code 0.
07-08 14:26:09.383  1097  3371 I MicroRecognitionRnrImpl: Starting detection.
07-08 14:26:09.388  1097  3372 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@d20ddd3
07-08 14:26:09.391   222   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-08 14:26:09.392   590   633 I ActivityManager: Start proc 3375:com.android.defcontainer/u0a4 for service com.android.defcontainer/.DefaultContainerService
07-08 14:26:09.393   222  3374 I AudioFlinger: AudioFlinger's thread 0xab82e420 ready to run
07-08 14:26:09.394  1097  3372 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@d20ddd3
07-08 14:26:09.398   590   633 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-08 14:26:09.441  1036  1036 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-08 14:26:09.450   590   654 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-08 14:26:09.457  1010  1245 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-08 14:26:09.474   590  1308 I ActivityManager: Start proc 3392:android.process.acore/u0a3 for broadcast com.android.providers.contacts/.PackageIntentReceiver
07-08 14:26:09.513   992   992 I Keyboard.Facilitator: resetDictionaries() : en_US
07-08 14:26:09.552  1010  1177 W GCoreFlp: No location to return for getLastLocation()
07-08 14:26:09.559   590   590 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-08 14:26:09.559   992  3403 I Keyboard.Facilitator.DecoderInitializer: run()
07-08 14:26:09.563   590   660 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
07-08 14:26:09.577   992  3403 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
07-08 14:26:09.577  1010  1177 W GCoreFlp: No location to return for getLastLocation()
07-08 14:26:09.579  1097  1097 I HotwordWorkerImpl: onReady
07-08 14:26:09.577   992  3403 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
07-08 14:26:09.582   992  3403 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-08 14:26:09.582   992  3403 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-08 14:26:09.583   992  3403 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-08 14:26:09.583   992  3403 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-08 14:26:09.610  1044  1111 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-08 14:26:09.617  1010  1177 W GCoreFlp: No location to return for getLastLocation()

```
