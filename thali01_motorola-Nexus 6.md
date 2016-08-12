#### Test 797510159e44f0b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 21:57:18.168   872  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 21:57:18.837  3941  3941 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 21:57:18.843  3941  3941 D AndroidRuntime: CheckJNI is OFF
08-12 21:57:18.885  3941  3941 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 21:57:18.935  3941  3941 I Radio-JNI: register_android_hardware_Radio DONE
08-12 21:57:18.957  3941  3941 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 21:57:18.963   872  1396 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 21:57:19.031  2032  2376 W SearchService: Abort, client detached.
08-12 21:57:19.035  2032  2321 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d325698
08-12 21:57:19.035  2032  2331 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 21:57:19.035  2032  2032 I HotwordDetector: Closing mic
08-12 21:57:19.036  3941  3941 D AndroidRuntime: Shutting down VM
08-12 21:57:19.070   872  1881 I ActivityManager: Start proc 3951:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 21:57:19.099   375  2333 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 21:57:19.100   375  2333 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 21:57:19.108   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 21:57:19.109  2032  2330 I MicroRecognitionRnrImpl: Detection finished
08-12 21:57:19.109  2032  2325 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 21:57:19.147  3951  3951 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 21:57:19.168  3951  3951 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 21:57:19.176  3951  3951 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4906-4909)
08-12 21:57:19.176  3951  3951 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 21:57:19.189  3951  3951 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a19364e}
08-12 21:57:19.189  3951  3951 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 21:57:19.190  3951  3951 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 21:57:19.197  3951  3951 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 21:57:19.199  3951  3951 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 21:57:19.210  3951  3951 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 21:57:19.221  3951  3951 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 21:57:19.221  3951  3951 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 21:57:19.221  3951  3951 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 21:57:19.221  3951  3951 I Adreno  : Build Date                       : 10/20/15
08-12 21:57:19.221  3951  3951 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 21:57:19.221  3951  3951 I Adreno  : Local Branch                     : M14
08-12 21:57:19.221  3951  3951 I Adreno  : Remote Branch                    : 
08-12 21:57:19.221  3951  3951 I Adreno  : Remote Branch                    : 
08-12 21:57:19.221  3951  3951 I Adreno  : Reconstruct Branch               : 
,08-12 21:57:19.267   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63802a4:true
,08-12 21:57:19.297  3951  3951 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 21:57:19.308  3951  3951 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 21:57:19.344  3951  3990 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 21:57:19.351  3951  3977 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 21:57:19.379  3951  3990 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 21:57:19.393  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-12 21:57:19.439   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +385ms
,08-12 21:57:19.473  3951  3951 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3951
,08-12 21:57:19.578  3951  3951 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 21:57:19.805  3951  3993 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1683551952
,08-12 21:57:19.810  3951  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 21:57:19.810  3951  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 21:57:19.810  3951  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 21:57:19.810  3951  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 21:57:19.810  3951  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 21:57:19.810  3951  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d61d17d added. We now have 1 listener(s)
,08-12 21:57:19.814  3951  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 21:57:19.814  3951  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 21:57:19.815  3951  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 21:57:19.815  3951  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 21:57:19.819  3951  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbf0879 added. We now have 1 listener(s)
08-12 21:57:19.820  3951  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 21:57:19.822   872  1311 D WifiService: New client listening to asynchronous messages
,08-12 21:57:19.825  3951  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 21:57:19.825  3951  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 21:57:19.827  3951  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-12 21:57:19.827  3951  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 21:57:19.827  3951  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 21:57:19.831  3951  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 21:57:19.832  3951  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 21:57:19.842  3951  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 21:57:19.844  3951  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 21:57:19.844  3951  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 21:57:19.844  3951  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 21:57:19.846  3951  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 21:57:19.846  3951  3993 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 21:57:19.848  3951  3951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 21:57:19.865   872  1902 I ActivityManager: Killing 2242:com.google.android.talk/u0a61 (adj 15): empty #17
,08-12 21:57:19.923   872  1902 I ActivityManager: Killing 3117:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-12 21:57:19.982  3951  3951 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 21:57:20.903  3951  4002 W jxcore-log: Initializing JXcore engine
,08-12 21:57:20.904  3951  4002 W jxcore-log: JXcore engine is ready
,08-12 21:57:20.938  4002  4002 W Thread-345: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8953 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 21:57:20.938  4002  4002 W Thread-345: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10649]" dev="sockfs" ino=10649 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 21:57:20.938  4002  4002 W Thread-345: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 21:57:20.938  4002  4002 W Thread-345: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27021]" dev="sockfs" ino=27021 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 21:57:20.954  3951  4002 W jxcore-log: Starting JXcore engine
,08-12 21:57:21.042  3951  4002 W jxcore-log: Platform android
08-12 21:57:21.042  3951  4002 W jxcore-log: 
,08-12 21:57:21.042  3951  4002 W jxcore-log: Process ARCH arm
08-12 21:57:21.042  3951  4002 W jxcore-log: 
,08-12 21:57:21.274  3951  4002 I jxcore-log: JXcore Cordova bridge is ready!
08-12 21:57:21.274  3951  4002 I jxcore-log: 
,08-12 21:57:21.274  3951  4002 W jxcore-log: JXcore engine is started
,08-12 21:57:21.285  3951  3993 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 21:57:21.289  3951  3951 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 21:57:23.129  3286  4004 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 21:57:23.156  3286  4005 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 21:57:23.178  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:23.181  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:23.222  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 21:57:23.222  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 21:57:23.223  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:23.223  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:23.266  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:23.271  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:23.320  1501  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 21:57:23.320  1501  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 21:57:23.320  1501  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 21:57:23.321  1501  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:23.379  3286  4005 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 21:57:23.379  3286  4004 E BooksSync: Soft error
08-12 21:57:23.379  3286  4004 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 21:57:23.379  3286  4004 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 21:57:23.379  3286  4004 E BooksSync: Sync error
08-12 21:57:23.379  3286  4004 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 21:57:23.379  3286  4004 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 21:57:23.380  3286  4004 I BooksSync: Finished books sync
,08-12 21:57:23.390   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128823, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 21:57:24.283  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:24.293  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:24.296  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:24.328  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 21:57:24.328  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 21:57:24.328  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:24.328  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:24.358  3668  3668 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 21:57:24.359  3668  3668 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 21:57:24.359  3668  3668 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 21:57:24.930   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 21:57:29.250  3763  4015 V GoogleAuthProtoRequest: [310] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 21:57:29.344  1501  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 21:57:29.345  1501  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 21:57:29.345  1501  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:29.345  1501  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: [310] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: [310] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 21:57:29.366  3763  4015 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 21:57:29.393  1501  4017 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 21:57:29.395  1501  4017 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 21:57:29.412  1501  4017 W Uploader:  no longer exists, so no auth token.
,08-12 21:57:30.447  1501  4017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 21:57:30.447  1501  4017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 21:57:30.448  1501  4017 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:30.448  1501  4017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:30.464  1501  4017 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 21:57:30.464  1501  4017 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 21:57:30.464  1501  4017 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 21:57:30.719  1501  4017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 21:57:30.719  1501  4017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 21:57:30.719  1501  4017 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:30.720  1501  4017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:30.741  1501  4017 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 21:57:30.741  1501  4017 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 21:57:30.741  1501  4017 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 21:57:31.155  1501  4017 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 21:57:31.155  1501  4017 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 21:57:31.156  1501  4017 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:31.156  1501  4017 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:31.199  1501  4017 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 21:57:31.199  1501  4017 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 21:57:31.199  1501  4017 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 21:57:37.509  3951  4002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 21:57:37.509  3951  4002 I jxcore-log: 
,08-12 21:57:37.512  3951  4002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 21:57:37.512  3951  4002 I jxcore-log: 
,08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 21:57:37.523  3951  4002 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 21:57:37.527  3951  4002 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 21:57:37.529  3951  4002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 21:57:37.529  3951  4002 I jxcore-log: 
,08-12 21:57:37.530  3951  4002 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 21:57:37.530  3951  4002 I jxcore-log: 
,08-12 21:57:37.868  3951  4002 I jxcore-log: Unit Test app is loaded
08-12 21:57:37.868  3951  4002 I jxcore-log: 
,08-12 21:57:37.875  3951  4002 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 21:57:37.875  3951  4002 I jxcore-log: 
,08-12 21:57:37.878  3951  4002 I jxcore-log: My device name is: motorola-Nexus 6
08-12 21:57:37.878  3951  4002 I jxcore-log: 
,08-12 21:57:37.880  3951  4002 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 21:57:37.880  3951  4002 I jxcore-log: 
,08-12 21:57:37.894  3951  3951 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 21:57:40.173  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 21:57:40.173  3951  4002 I jxcore-log: 
,08-12 21:57:40.778  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 21:57:40.778  3951  4002 I jxcore-log: 
,08-12 21:57:40.802  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 21:57:40.802  3951  4002 I jxcore-log: 
,08-12 21:57:42.128  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 21:57:42.128  3951  4002 I jxcore-log: 
,08-12 21:57:42.352  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 21:57:42.352  3951  4002 I jxcore-log: 
,08-12 21:57:42.358  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 21:57:42.358  3951  4002 I jxcore-log: 
,08-12 21:57:42.364  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 21:57:42.364  3951  4002 I jxcore-log: 
,08-12 21:57:42.380  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 21:57:42.380  3951  4002 I jxcore-log: 
,08-12 21:57:42.385  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 21:57:42.385  3951  4002 I jxcore-log: 
,08-12 21:57:43.046  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 21:57:43.046  3951  4002 I jxcore-log: 
,08-12 21:57:43.059  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 21:57:43.059  3951  4002 I jxcore-log: 
,08-12 21:57:43.068  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 21:57:43.068  3951  4002 I jxcore-log: 
,08-12 21:57:43.076  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 21:57:43.076  3951  4002 I jxcore-log: 
,08-12 21:57:43.124  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 21:57:43.124  3951  4002 I jxcore-log: 
,08-12 21:57:43.180  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 21:57:43.180  3951  4002 I jxcore-log: 
,08-12 21:57:43.187  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 21:57:43.187  3951  4002 I jxcore-log: 
,08-12 21:57:43.350  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 21:57:43.350  3951  4002 I jxcore-log: 
,08-12 21:57:43.377  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 21:57:43.377  3951  4002 I jxcore-log: 
,08-12 21:57:43.383  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 21:57:43.383  3951  4002 I jxcore-log: 
,08-12 21:57:43.389  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 21:57:43.389  3951  4002 I jxcore-log: 
,08-12 21:57:43.407  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 21:57:43.407  3951  4002 I jxcore-log: 
,08-12 21:57:43.491  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 21:57:43.491  3951  4002 I jxcore-log: 
,08-12 21:57:43.503  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 21:57:43.503  3951  4002 I jxcore-log: 
,08-12 21:57:43.531  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 21:57:43.531  3951  4002 I jxcore-log: 
,08-12 21:57:43.544  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 21:57:43.544  3951  4002 I jxcore-log: 
,08-12 21:57:43.563  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 21:57:43.563  3951  4002 I jxcore-log: 
,08-12 21:57:43.599  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 21:57:43.599  3951  4002 I jxcore-log: 
,08-12 21:57:43.605  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 21:57:43.605  3951  4002 I jxcore-log: 
,08-12 21:57:43.806  3951  4002 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 21:57:43.806  3951  4002 I jxcore-log: 
,08-12 21:57:43.818  3951  4002 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 21:57:43.819  3951  4002 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 21:57:43.819  3951  4002 I jxcore-log: 
,08-12 21:57:44.647  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:44.658  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:44.661  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:44.696  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 21:57:44.696  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 21:57:44.696  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:44.696  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:44.736  3668  3668 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 21:57:44.738  3668  3668 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 21:57:44.739  3668  3668 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 21:57:47.497   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 21:57:47.506  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-12 21:57:47.526   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 21:57:47.526   872   892 I Adreno  : Build Date                       : 10/20/15
08-12 21:57:47.526   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 21:57:47.526   872   892 I Adreno  : Local Branch                     : M14
08-12 21:57:47.526   872   892 I Adreno  : Remote Branch                    : 
08-12 21:57:47.526   872   892 I Adreno  : Remote Branch                    : 
08-12 21:57:47.526   872   892 I Adreno  : Reconstruct Branch               : 
,08-12 21:57:47.587   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (328 us)
,08-12 21:57:48.184  3951  3951 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 21:57:48.184  3951  3951 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 21:57:48.230   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 21:57:48.235  3951  3951 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@cd12b14 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3e5e793, 16908290=android.view.AbsSavedState$1@3e5e793}, android:focusedViewId=100}]}]
,08-12 21:57:48.235  3951  3951 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-12 21:57:48.237  3951  3951 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 21:57:48.237  3951  3951 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 21:57:48.248   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 21:57:48.252   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-12 21:57:48.252   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-12 21:57:48.252   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 21:57:48.490   281   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 21:57:48.493   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 21:57:48.499   872  1336 D SurfaceControl: Excessive delay in setPowerMode(): 247ms
,08-12 21:57:48.503   872   892 I DreamManagerService: Entering dreamland.
,08-12 21:57:48.504   872   892 I PowerManagerService: Dozing...
08-12 21:57:48.505   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 21:57:48.550   375  1319 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 21:57:48.550   375  1319 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 21:57:48.561   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 21:57:48.567  1930  4031 D NfcService: Discovery configuration equal, not updating.
,08-12 21:57:48.574   872  1309 E native  : do suspend false
,08-12 21:57:48.592   872  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 21:57:48.605   872  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 21:57:48.608   872  1309 E native  : do suspend true
,08-12 21:57:48.693   375  1318 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-12 21:57:48.693   375  1318 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 21:57:49.065   872  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 21:57:53.626  3732  4038 V KeepSync: Connecting to GoogleApiClient
,08-12 21:57:53.628   872  1983 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 21:57:53.637  1882  2721 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 21:57:53.706  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:53.708  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:57:53.745  1501  3790 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-12 21:57:53.745  1501  3790 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-12 21:57:53.745  1501  3790 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:53.745  1501  3790 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:53.754  1501  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 21:57:53.754  1501  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 21:57:53.754  1501  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:53.754  1501  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:53.772  1709  4040 V BaseAuthAsyncOperation: access token request failed
,08-12 21:57:53.773  3732  4038 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 21:57:53.806  3136  4039 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 21:57:53.806  3136  4039 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jdm.a(PG:82)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jcs.o(PG:406)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jcn.a(PG:1379)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jcs.i(PG:143)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at blb.a(PG:3937)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at czp.a(PG:18188)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at czp.a(PG:9081)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at czq.run(PG:1686)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 21:57:53.806  3136  4039 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jdj.a(PG:4091)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jdj.a(PG:1125)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jdm.a(PG:77)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	... 12 more
08-12 21:57:53.806  3136  4039 E HttpOperation: Caused by: faj: BadAuthentication
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at fal.a(PG:38)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	at jdj.a(PG:4089)
08-12 21:57:53.806  3136  4039 E HttpOperation: 	... 14 more
,08-12 21:57:53.913  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 21:57:53.913  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 21:57:53.913  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:53.913  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:53.915  1501  2021 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-12 21:57:53.915  1501  2021 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 21:57:53.916  1501  2021 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:57:53.916  1501  2021 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:57:53.940  3136  4039 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 21:57:53.940  3136  4039 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jdm.a(PG:82)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jcs.o(PG:406)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jcn.a(PG:1379)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jcs.i(PG:143)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at hec.a(PG:42)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at hee.a(PG:102)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at czr.a(PG:65)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at kka.a(PG:108)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at czp.a(PG:19176)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at czp.a(PG:9081)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at czq.run(PG:1686)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 21:57:53.940  3136  4039 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jdj.a(PG:4091)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jdj.a(PG:1125)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jdm.a(PG:77)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	... 15 more
08-12 21:57:53.940  3136  4039 E HttpOperation: Caused by: faj: BadAuthentication
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at fal.a(PG:38)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	at jdj.a(PG:4089)
08-12 21:57:53.940  3136  4039 E HttpOperation: 	... 17 more
08-12 21:57:53.940  3136  4039 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 21:57:53.940  3136  4039 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at hec.a(PG:42)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at hee.a(PG:102)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at czr.a(PG:65)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at kka.a(PG:108)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	... 15 more
08-12 21:57:53.940  3136  4039 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at fal.a(PG:38)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 21:57:53.940  3136  4039 E ExperimentLoader: 	... 17 more
,08-12 21:57:53.961  3732  4038 E KeepSync: IOException
08-12 21:57:53.961  3732  4038 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 21:57:53.961  3732  4038 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 21:57:53.961  3732  4038 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 21:57:53.961  3732  4038 E KeepSync: 	... 10 more
,08-12 21:57:53.962  3732  4038 W KeepSync: Sync result 2
,08-12 21:57:53.972   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 132862, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 21:57:54.070   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131998, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 21:57:57.491   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=163224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 21:57:58.181   872  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 21:58:07.078   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=172810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 21:58:47.552  1868  1911 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-12 21:58:47.552  1868  1911 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 21:58:47.603  1501  1501 I ConfigService: onCreate
,08-12 21:58:52.674  1501  1501 I ConfigService: onDestroy
,08-12 21:58:53.624   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 21:59:02.718   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=228451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 21:59:23.991  3286  4047 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 21:59:24.019  3286  4048 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 21:59:24.037  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:59:24.039  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:59:24.070  1501  2021 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 21:59:24.070  1501  2021 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 21:59:24.070  1501  2021 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:59:24.071  1501  2021 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:59:24.102  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:59:24.104  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:59:24.131  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 21:59:24.132  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 21:59:24.132  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:59:24.132  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:59:24.149  3286  4048 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 21:59:24.150  3286  4047 E BooksSync: Soft error
08-12 21:59:24.150  3286  4047 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 21:59:24.150  3286  4047 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 21:59:24.150  3286  4047 E BooksSync: Sync error
08-12 21:59:24.150  3286  4047 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 21:59:24.150  3286  4047 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 21:59:24.150  3286  4047 I BooksSync: Finished books sync
,08-12 21:59:24.160   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 249655, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 21:59:28.931   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=254664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 21:59:38.078   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=263810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 21:59:59.475  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:59:59.476  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 21:59:59.484  3763  4051 V GoogleAuthProtoRequest: [311] a.<init>: mAccountName set to: thalitester@gmail.com
,08-12 21:59:59.501  1501  2021 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-12 21:59:59.501  1501  2021 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-12 21:59:59.501  1501  2021 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 21:59:59.501  1501  2021 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 21:59:59.512  3763  4051 W ExperimentUpdateService: [311] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: [311] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-12 21:59:59.513  3763  4051 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-12 22:00:01.514  1501  3790 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 22:00:01.514  1501  3790 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 22:00:01.514  1501  3790 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:00:01.514  1501  3790 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:00:01.537  3136  4057 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 22:00:01.537  3136  4057 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jdm.a(PG:82)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jcs.o(PG:406)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jcn.a(PG:1379)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jcs.i(PG:143)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at blb.a(PG:3937)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at czp.a(PG:18188)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at czp.a(PG:9081)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at czq.run(PG:1686)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:00:01.537  3136  4057 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jdj.a(PG:4091)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jdj.a(PG:1125)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jdm.a(PG:77)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	... 12 more
08-12 22:00:01.537  3136  4057 E HttpOperation: Caused by: faj: BadAuthentication
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at fal.a(PG:38)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	at jdj.a(PG:4089)
08-12 22:00:01.537  3136  4057 E HttpOperation: 	... 14 more
,08-12 22:00:01.632  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 22:00:01.632  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 22:00:01.632  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:00:01.633  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:00:01.662  3136  4057 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 22:00:01.662  3136  4057 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jdm.a(PG:82)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jcs.o(PG:406)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jcn.a(PG:1379)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jcs.i(PG:143)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at hec.a(PG:42)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at hee.a(PG:102)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at czr.a(PG:65)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at kka.a(PG:108)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at czp.a(PG:19176)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at czp.a(PG:9081)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at czq.run(PG:1686)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:00:01.662  3136  4057 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jdj.a(PG:4091)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jdj.a(PG:1125)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jdm.a(PG:77)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	... 15 more
08-12 22:00:01.662  3136  4057 E HttpOperation: Caused by: faj: BadAuthentication
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at fal.a(PG:38)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	at jdj.a(PG:4089)
08-12 22:00:01.662  3136  4057 E HttpOperation: 	... 17 more
,08-12 22:00:01.662  3136  4057 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 22:00:01.662  3136  4057 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at hec.a(PG:42)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at hee.a(PG:102)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at czr.a(PG:65)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at kka.a(PG:108)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	... 15 more
08-12 22:00:01.662  3136  4057 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at fal.a(PG:38)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 22:00:01.662  3136  4057 E ExperimentLoader: 	... 17 more
,08-12 22:00:01.794   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 287059, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:00:01.857  3732  4059 V KeepSync: Connecting to GoogleApiClient
,08-12 22:00:01.859   872  1881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 22:00:01.945  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-12 22:00:01.945  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 22:00:01.945  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:00:01.945  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:00:01.964  1709  4060 V BaseAuthAsyncOperation: access token request failed
,08-12 22:00:01.965  3732  4059 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 22:00:02.022  1501  2026 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 22:00:02.022  1501  2026 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 22:00:02.022  1501  2026 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 22:00:02.022  1501  2026 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:00:02.045  3732  4059 E KeepSync: IOException
08-12 22:00:02.045  3732  4059 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 22:00:02.045  3732  4059 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 22:00:02.045  3732  4059 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 22:00:02.045  3732  4059 E KeepSync: 	... 10 more
,08-12 22:00:02.045  3732  4059 W KeepSync: Sync result 2
,08-12 22:00:02.052   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 287421, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 22:00:04.344   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=290077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 22:00:13.464   872  2107 D NetlinkSocketObserver: NeighborEvent{elapsedMs=299197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 22:00:58.986  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:00:58.996  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:00:59.002  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 22:00:59.067  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 22:00:59.068  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 22:00:59.068  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 22:00:59.068  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 22:00:59.097  1501  1514 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 22:00:59.097  1501  1514 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 22:00:59.097  1501  1514 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 22:00:59.097  1501  1514 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 22:00:59.097  1501  1514 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 22:00:59.097  1501  1514 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 22:00:59.097  1501  1514 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 22:00:59.108  3668  3699 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 22:00:59.108  3668  3699 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 22:00:59.108  3668  3699 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 22:00:59.108  3668  3699 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 22:00:59.108  3668  3699 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 22:00:59.108  3668  3699 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 22:00:59.108  3668  3699 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 22:01:03.986  3951  4002 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 22:01:03.986  3951  4002 I jxcore-log: 
,08-12 22:01:04.594  4076  4076 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 22:01:04.599  4076  4076 D AndroidRuntime: CheckJNI is OFF
,08-12 22:01:04.642  4076  4076 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 22:01:04.689  4076  4076 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 22:01:04.712  4076  4076 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 22:01:04.721   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 22:01:04.722   872   885 I ActivityManager: Killing 3951:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 22:01:04.829   872   895 W PackageSettings: Skipping PackageSetting{cc56b15 com.example.hello/10273} due to missing metadata
,08-12 22:01:04.865   872  1997 D GraphicsStats: Buffer count: 2
,08-12 22:01:04.865   872  1983 I WindowState: WIN DEATH: Window{8f35cd4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 22:01:04.866   872  1311 D WifiService: Client connection lost with reason: 4
,08-12 22:01:04.871   872   895 I art     : Starting a blocking GC Explicit
,08-12 22:01:04.920   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-12 22:01:04.920   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 22:01:04.920   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-12 22:01:04.920   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 22:01:04.920   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:04.920   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:04.920   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:01:04.920   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 22:01:04.921   872   885 I ActivityManager:   Force finishing activity ActivityRecord{a9b96e5 u0 com.test.thalitest/.MainActivity t2}
,08-12 22:01:04.929   872  1997 W ActivityManager: Spurious death for ProcessRecord{6d0d1b1 0:com.test.thalitest/u0a0}, curProc for 3951: null
,08-12 22:01:04.946   872   895 I art     : Explicit concurrent mark sweep GC freed 17649(1214KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.129ms total 73.117ms
,08-12 22:01:04.987   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 22:01:04.990  4076  4076 I art     : System.exit called, status: 0
08-12 22:01:04.990  4076  4076 I AndroidRuntime: VM exiting with result code 0.
,08-12 22:01:04.994   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 22:01:05.013   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 22:01:05.018  2833  2833 D BluetoothMapAppObserver: onReceive
08-12 22:01:05.018  2833  2833 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 22:01:05.025   872  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 22:01:05.026  1882  2275 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 22:01:05.026  1868  1868 I Keyboard.Facilitator: resetDictionaries() : en_US
08-12 22:01:05.029  3822  3822 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 22:01:05.059  1868  4087 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 22:01:05.064  1868  4087 I Decoder : createOrResetDecoder
,08-12 22:01:05.072  3179  4090 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 22:01:05.081  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 22:01:05.088  1501  1501 I ConfigService: onCreate
,08-12 22:01:05.124   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 22:01:05.149  1868  4087 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 22:01:05.157  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-12 22:01:05.159  1501  1501 D AndroidRuntime: Shutting down VM
,08-12 22:01:05.160   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-12 22:01:05.160   872   884 E PackageManager: Failed to write settings, restoring backup
08-12 22:01:05.160   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 22:01:05.160   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 22:01:05.160   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 22:01:05.160   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 22:01:05.160   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 22:01:05.160   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.160   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:05.160   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 22:01:05.160  1958  2065 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-12 22:01:05.162   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-12 22:01:05.162   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 22:01:05.162   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:01:05.162   872   885 E DropBoxManagerService: 	... 13 more
--------- beginning of crash
08-12 22:01:05.163  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
08-12 22:01:05.163  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
08-12 22:01:05.163  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 22:01:05.163  1501  15,01 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 22:01:05.163  1501  1501 E AndroidRuntime: 	... 8 more
08-12 22:01:05.176   872  1970 I ActivityManager: Start proc 4095:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-12 22:01:05.176  1958  2065 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 22:01:05.176  1958  2065 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1958
08-12 22:01:05.176  1958  2065 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:05.176  1958  2065 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:01:05.181   872  1385 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 22:01:05.183   872  4106 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:01:05.183   872  4106 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:01:05.183   872  4106 E DropBoxManagerService: 	... 5 more
08-12 22:01:05.184   872  4105 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:01:05.184   872  4105 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:01:05.184   872  4105 E DropBoxManagerService: 	... 5 more
08-12 22:01:05.192  1958  2065 I Process : Sending signal. PID: 1958 SIG: 9
08-12 22:01:05.194  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
,08-12 22:01:05.218  1868  4087 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-12 22:01:05.220  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-12 22:01:05.220  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-12 22:01:05.222  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-12 22:01:05.222  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 22:01:05.222  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-12 22:01:05.223  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-12 22:01:05.223  1868  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 22:01:05.223  1868  4087 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 22:01:05.223  1868  4087 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 22:01:05.224  1868  4087 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 22:01:05.224  1868  4087 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 22:01:05.224  1868  4087 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-12 22:01:05.249   872  1311 D WifiService: Client connection lost with reason: 4
,08-12 22:01:05.253   872  1992 I ActivityManager: Process com.google.process.gapps (pid 1501) has died
,08-12 22:01:05.254   872  1992 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 1000ms
,08-12 22:01:05.254   872  1992 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-12 22:01:05.254   872  1992 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-12 22:01:05.254   872  1992 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,08-12 22:01:05.270   872  1396 I ActivityManager: Start proc 4111:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
,08-12 22:01:05.272  1709  1709 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-12 22:01:05.284   872  1902 D GraphicsStats: Buffer count: 1
,08-12 22:01:05.287   872  1982 I WindowState: WIN DEATH: Window{f76951f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-12 22:01:05.307   872  1902 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1958) has died
,08-12 22:01:05.308   872  1902 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40947ms
,08-12 22:01:05.333  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-12 22:01:05.333  1709  1709 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 22:01:05.340  1709  1709 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-12 22:01:05.341  1709  1709 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 22:01:05.351  1709  4126 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 22:01:05.367   872  1992 I ActivityManager: Start proc 4129:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-12 22:01:05.368  1709  4126 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 22:01:05.368  1709  4126 E AndroidRuntime: Process: com.google.android.gms, PID: 1709
08-12 22:01:05.368  1709  4126 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 22:01:05.368  1709  4126 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-12 22:01:05.370  2032  4125 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 22:01:05.393  1709  4126 I Process : Sending signal. PID: 1709 SIG: 9
,08-12 22:01:05.393   872  4141 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:01:05.393   872  4141 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:01:05.393   872  4141 E DropBoxManagerService: 	... 5 more
,08-12 22:01:05.407  4111  4111 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-12 22:01:05.415  2032  4125 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 22:01:05.427  2032  4125 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-12 22:01:05.427  2032  4125 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 22:01:05.427  2032  4125 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2032
08-12 22:01:05.427  2032  4125 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:05.427  2032  4125 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 22:01:05.429   872  1997 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 22:01:05.429   872  1997 I ActivityManager: Killing 2032:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
,08-12 22:01:05.430   872  4142 E DropBoxManagerService: Can't write: system_app_crash
08-12 22:01:05.430   872  4142 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 22:01:05.430   872  4142 E DropBoxManagerService: 	... 5 more
,08-12 22:01:05.446  4111  4111 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 22:01:05.460  4111  4111 I MultiDex: install
08-12 22:01:05.460  4111  4111 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 22:01:05.490  4129  4129 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 22:01:05.490  4129  4129 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 22:01:05.490  4129  4129 D AndroidRuntime: Shutting down VM
,08-12 22:01:05.510   872  2013 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@ed5928d)
,08-12 22:01:05.517   872  1312 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 22:01:05.517   872  1312 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 22:01:05.525  4095  4095 E GmsClient: service descriptor mismatch: com.google.android.gms.feedback.internal.IFeedbackService vs. 
08-12 22:01:05.526  4095  4127 W GmsClient: service died
08-12 22:01:05.529  4095  4095 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
08-12 22:01:05.531   872  1311 D WifiService: Client connection lost with reason: 4
,08-12 22:01:05.536   872  1997 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-12 22:01:05.540   279   279 E lowmemorykiller: Error opening /proc/1709/oom_score_adj; errno=2
,08-12 22:01:05.548   872  1881 I ActivityManager: Process com.google.android.gms (pid 1709) has died
08-12 22:01:05.548   872  1881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-12 22:01:05.548   872  1881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-12 22:01:05.548   872  1881 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 11000ms

```
