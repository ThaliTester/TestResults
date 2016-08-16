#### Test 807613747a577d4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 12:10:37.515   875  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 12:10:38.233  3843  3843 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 12:10:38.238  3843  3843 D AndroidRuntime: CheckJNI is OFF
08-16 12:10:38.281  3843  3843 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 12:10:38.330  3843  3843 I Radio-JNI: register_android_hardware_Radio DONE
08-16 12:10:38.352  3843  3843 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 12:10:38.356   875  1915 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 12:10:38.384  2060  2075 W SearchService: Abort, client detached.
08-16 12:10:38.389  3843  3843 D AndroidRuntime: Shutting down VM
08-16 12:10:38.402  2060  2060 I HotwordDetector: Closing mic
08-16 12:10:38.404  2060  2334 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@823c518
08-16 12:10:38.404  2060  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 12:10:38.420   875  2017 I ActivityManager: Start proc 3852:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 12:10:38.455   375  2346 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 12:10:38.457   375  2346 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 12:10:38.460   375  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 12:10:38.463  2060  2342 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 12:10:38.465  2060  2343 I MicroRecognitionRnrImpl: Detection finished
08-16 12:10:38.495  3852  3852 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 12:10:38.516  3852  3852 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 12:10:38.522  3852  3852 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4724-4726)
08-16 12:10:38.522  3852  3852 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:10:38.536  3852  3852 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a318ce}
08-16 12:10:38.536  3852  3852 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:10:38.537  3852  3852 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:10:38.545  3852  3852 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 12:10:38.546  3852  3852 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 12:10:38.561  3852  3852 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 12:10:38.572  3852  3852 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 12:10:38.572  3852  3852 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 12:10:38.572  3852  3852 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 12:10:38.572  3852  3852 I Adreno  : Build Date                       : 10/20/15
08-16 12:10:38.572  3852  3852 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 12:10:38.572  3852  3852 I Adreno  : Local Branch                     : M14
08-16 12:10:38.572  3852  3852 I Adreno  : Remote Branch                    : 
08-16 12:10:38.572  3852  3852 I Adreno  : Remote Branch                    : 
08-16 12:10:38.572  3852  3852 I Adreno  : Reconstruct Branch               : 
,08-16 12:10:38.626   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b39497a:true
,08-16 12:10:38.663  3852  3852 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 12:10:38.675  3852  3852 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 12:10:38.754  3852  3891 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 12:10:38.770  3852  3877 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 12:10:38.800  3852  3891 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 12:10:38.889  1890  1890 I Keyboard.Facilitator: onFinishInput()
,08-16 12:10:38.890   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +495ms
,08-16 12:10:38.944  3852  3852 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3852
,08-16 12:10:39.147  3852  3852 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 12:10:39.225   875  2012 I ActivityManager: Killing 3039:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 12:10:39.273   875  2012 I ActivityManager: Killing 3253:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 12:10:39.366  3852  3893 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684408016
,08-16 12:10:39.373  3852  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 12:10:39.373  3852  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 12:10:39.373  3852  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 12:10:39.373  3852  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 12:10:39.373  3852  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 12:10:39.373  3852  3893 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a352f2 added. We now have 1 listener(s)
,08-16 12:10:39.385  3852  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 12:10:39.386  3852  3893 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:10:39.387  3852  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:10:39.387  3852  3893 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 12:10:39.392  3852  3893 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9184f9 added. We now have 1 listener(s)
08-16 12:10:39.392  3852  3893 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:10:39.397   875  1319 D WifiService: New client listening to asynchronous messages
,08-16 12:10:39.398  3852  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:10:39.398  3852  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 12:10:39.398  3852  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 12:10:39.398  3852  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 12:10:39.398  3852  3893 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2,
,08-16 12:10:39.403  3852  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:10:39.403  3852  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 12:10:39.417  3852  3893 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:10:39.418  3852  3893 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:10:39.418  3852  3893 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
08-16 12:10:39.418  3852  3893 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:10:39.419  3852  3893 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 12:10:39.421  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:10:39.424  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:10:39.466  3852  3852 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 12:10:40.582  3852  3901 W jxcore-log: Initializing JXcore engine
,08-16 12:10:40.582  3852  3901 W jxcore-log: JXcore engine is ready
,08-16 12:10:40.621  3901  3901 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 12:10:40.621  3901  3901 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12686]" dev="sockfs" ino=12686 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 12:10:40.621  3901  3901 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 12:10:40.621  3901  3901 W Thread-337: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25294]" dev="sockfs" ino=25294 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 12:10:40.636  3852  3901 W jxcore-log: Starting JXcore engine
,08-16 12:10:40.721  3852  3901 W jxcore-log: Platform android
08-16 12:10:40.721  3852  3901 W jxcore-log: 
,08-16 12:10:40.721  3852  3901 W jxcore-log: Process ARCH arm
08-16 12:10:40.721  3852  3901 W jxcore-log: 
,08-16 12:10:40.937  3852  3901 I jxcore-log: JXcore Cordova bridge is ready!
08-16 12:10:40.937  3852  3901 I jxcore-log: 
,08-16 12:10:40.937  3852  3901 W jxcore-log: JXcore engine is started
,08-16 12:10:40.949  3852  3893 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 12:10:40.955  3852  3852 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 12:10:41.206   875  2082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 12:10:43.002  3239  3903 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 12:10:43.021  3239  3904 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 12:10:43.033  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.036  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.068  1487  1931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 12:10:43.068  1487  1931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:10:43.068  1487  1931 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:10:43.069  1487  1931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:43.119  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.121  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.163  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 12:10:43.163  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:10:43.164  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:10:43.164  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:43.187  3239  3904 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 12:10:43.188  3239  3903 E BooksSync: Soft error
08-16 12:10:43.188  3239  3903 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:10:43.188  3239  3903 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 12:10:43.189  3239  3903 E BooksSync: Sync error
08-16 12:10:43.189  3239  3903 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:10:43.189  3239  3903 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 12:10:43.189  3239  3903 I BooksSync: Finished books sync
,08-16 12:10:43.192   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129166, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 12:10:43.547  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.550  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.561  3665  3910 V GoogleAuthProtoRequest: [303] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 12:10:43.582  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 12:10:43.582  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 12:10:43.582  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:10:43.582  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: [303] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: [303] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 12:10:43.597  3665  3910 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 12:10:43.697  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:10:43.740  1487  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 12:10:43.741  1487  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 12:10:43.741  1487  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:10:43.741  1487  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:43.755  3591  3591 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 12:10:43.755  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 12:10:43.755  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 12:10:43.785  1487  3912 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 12:10:43.787  1487  3912 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 12:10:44.107  1487  3912 W Uploader:  no longer exists, so no auth token.
,08-16 12:10:44.798  1487  3912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 12:10:44.798  1487  3912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 12:10:44.798  1487  3912 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:10:44.799  1487  3912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:44.818  1487  3912 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 12:10:44.818  1487  3912 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 12:10:44.818  1487  3912 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 12:10:45.094  1487  3912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 12:10:45.095  1487  3912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 12:10:45.096  1487  3912 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:10:45.099  1487  3912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:45.135  1487  3912 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 12:10:45.135  1487  3912 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 12:10:45.135  1487  3912 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 12:10:45.599  1487  3912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 12:10:45.600  1487  3912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 12:10:45.600  1487  3912 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:10:45.600  1487  3912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:10:45.638  1487  3912 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 12:10:45.638  1487  3912 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 12:10:45.638  1487  3912 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 12:10:48.833   875  2082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=135037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 12:10:57.026  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 12:10:57.026  3852  3901 I jxcore-log: 
,08-16 12:10:57.028  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 12:10:57.028  3852  3901 I jxcore-log: 
,08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:10:57.039  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:10:57.048  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:10:57.054  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 12:10:57.054  3852  3901 I jxcore-log: 
,08-16 12:10:57.065  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 12:10:57.065  3852  3901 I jxcore-log: 
,08-16 12:10:57.454  3852  3901 I jxcore-log: Running unit tests
08-16 12:10:57.454  3852  3901 I jxcore-log: 
,08-16 12:10:57.455  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:10:57.455  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5037c added. We now have 2 listener(s)
08-16 12:10:57.456  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:10:57.456  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:10:57.456  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:10:57.456  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:10:57.456  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@faa7405 added. We now have 2 listener(s)
08-16 12:10:57.456  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:10:57.457  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:10:57.460  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:10:57.472  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:10:57.476  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:10:57.476  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:10:57.477  3852  3901 D ExecuteNativeTests: Running unit tests
,08-16 12:10:57.480  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:10:57.489  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:02.578  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:11:02.578  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b added. We now have 3 listener(s)
,08-16 12:11:02.585  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:11:02.586  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:11:02.586  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:11:02.587  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:11:02.587  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 added. We now have 3 listener(s)
,08-16 12:11:02.588  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:11:02.589  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:11:02.600  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:02.617  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:11:02.627  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:02.627  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:11:02.636  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:02.639  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 12:11:02.640  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:11:02.641  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:11:02.641  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:11:02.649  3852  3901 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 12:11:02.649  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:02.650  3852  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 12:11:02.650  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:11:02.650  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:11:02.651  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:11:02.651  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:11:02.653  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:02.654  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:02.655  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:02.658  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:02.660  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.660  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:11:02.660  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:11:02.661  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b removed from the list
08-16 12:11:02.661  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:02.661  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 removed from the list
08-16 12:11:02.661  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:02.661  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.662  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.662  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.663  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:02.663  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:02.664  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:02.664  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:02.666  3852  3901 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 12:11:02.667  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:02.667  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:02.667  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:02.667  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:02.667  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.667  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.667  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:02.667  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:02.668  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:02.668  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:02.668  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.668  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.668  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.668  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.669  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:02.669  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:02.670  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:02.670  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:02.676  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:11:02.677  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:11:02.678  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-16 12:11:02.679  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:11:02.679  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:02.679  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:02.679  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:11:02.679  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:02.680  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.680  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.680  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:02.680  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:02.680  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:02.680  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:02.680  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.680  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.680  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:02.680  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:02.682  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:02.682  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:02.682  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:02.682  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:02.683  3852  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:11:02.685  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:02.690  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:11:02.693  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:02.693  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:11:02.693  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:11:02.693  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:11:02.693  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:11:02.694  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:11:02.694  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:11:02.697  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:02.699  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:02.701  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 12:11:02.701  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:11:02.709  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:11:02.711  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 12:11:02.712  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:11:02.715  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage,
,08-16 12:11:02.717  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 12:11:02.717  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 12:11:02.717  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 12:11:02.718  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 12:11:02.720  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:11:02.726  2638  2791 D BtGatt.GattService: registerClient() - UUID=ef328ab1-b9b1-4c8e-b6ff-600f3698d70f
,08-16 12:11:02.728  2638  2660 D BtGatt.GattService: onClientRegistered() - UUID=ef328ab1-b9b1-4c8e-b6ff-600f3698d70f, clientIf=5
08-16 12:11:02.729  3852  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:11:02.732  2638  2649 D BtGatt.GattService: start scan with filters
,08-16 12:11:02.736  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:11:02.737  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:11:02.737  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:11:02.737  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 12:11:02.738  2638  2667 D BtGatt.ScanManager: handling starting scan
,08-16 12:11:02.739  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:11:02.740  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:11:02.741  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:11:02.741  2638  2667 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
08-16 12:11:02.742  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:11:02.745  3852  3901 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 12:11:02.750  2638  2660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 12:11:02.751  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:02.752  2638  2667 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 12:11:02.764  2638  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 12:11:02.765  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:02.768  2638  2667 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:11:02.768  2638  2667 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 12:11:02.796  2638  2660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:11:02.796  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:02.815  2638  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 12:11:02.815  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:03.242  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-16 12:11:03.243  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 12:11:03.243  3852  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:11:04.121   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 12:11:04.132  1890  1890 I Keyboard.Facilitator: onFinishInput()
,08-16 12:11:04.143   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 12:11:04.143   875   895 I Adreno  : Build Date                       : 10/20/15
08-16 12:11:04.143   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 12:11:04.143   875   895 I Adreno  : Local Branch                     : M14
08-16 12:11:04.143   875   895 I Adreno  : Remote Branch                    : 
08-16 12:11:04.143   875   895 I Adreno  : Remote Branch                    : 
08-16 12:11:04.143   875   895 I Adreno  : Reconstruct Branch               : 
,08-16 12:11:04.196   280  1309 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (316 us)
,08-16 12:11:04.314  2638  2638 D BtGatt.ScanManager: awakened up at time 150518
,08-16 12:11:04.316  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:04.349  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 12:11:04.349  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:04.349  2638  2660 D BtGatt.GattService: current time is 150554370996
08-16 12:11:04.350  2638  2660 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -87, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -91, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-16 12:11:04.351  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 12:11:04.351  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 12:11:04.351  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 12:11:04.352  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 12:11:04.352  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-16 12:11:04.352  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-16 12:11:04.822  3852  3852 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 12:11:04.822  3852  3852 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 12:11:04.863   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 12:11:04.870  3852  3852 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bc66194 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3d3312d, 16908290=android.view.AbsSavedState$1@3d3312d}, android:focusedViewId=100}]}]
08-16 12:11:04.870  3852  3852 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 12:11:04.870  3852  3852 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 12:11:04.870  3852  3852 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-16 12:11:04.873   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 12:11:04.877   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 12:11:04.877   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-16 12:11:04.877   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 12:11:05.115   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 12:11:05.119   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-16 12:11:05.121   875  1344 D SurfaceControl: Excessive delay in setPowerMode(): 244ms
08-16 12:11:05.124   875   895 I DreamManagerService: Entering dreamland.
08-16 12:11:05.126   875   895 I PowerManagerService: Dozing...
,08-16 12:11:05.127   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 12:11:05.188   375  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-16 12:11:05.188   375  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 12:11:05.194  2638  2638 D BtGatt.ScanManager: awakened up at time 151398
,08-16 12:11:05.195  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:05.201   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:11:05.217   875  1317 E native  : do suspend false
,08-16 12:11:05.219  1966  3931 D NfcService: Discovery configuration equal, not updating.
,08-16 12:11:05.231  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-16 12:11:05.232  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:05.232  2638  2660 D BtGatt.GattService: current time is 151436560823
,08-16 12:11:05.232  2638  2660 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -94, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -91, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -80, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -96, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 12:11:05.232  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 12:11:05.232  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 12:11:05.233  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 12:11:05.233  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-16 12:11:05.233  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 12:11:05.237   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 12:11:05.250   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:11:05.254   875  1317 E native  : do suspend true
,08-16 12:11:05.311   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 12:11:05.312   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 12:11:05.708   875  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 12:11:06.738  2638  2638 D BtGatt.ScanManager: awakened up at time 152942
,08-16 12:11:06.742  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:06.772  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-16 12:11:06.773  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:06.773  2638  2660 D BtGatt.GattService: current time is 152977850179
,08-16 12:11:06.774  2638  2660 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -92, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 12:11:06.775  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 12:11:06.776  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 12:11:06.777  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 12:11:07.755  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:07.756  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:07.756  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 12:11:07.756  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:07.757  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 12:11:07.757  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:11:07.757  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:11:07.757  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:11:07.758  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 12:11:07.760  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 12:11:07.761  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 12:11:07.763  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:11:07.765  2638  2649 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:11:07.769  2638  2650 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:11:07.770  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:11:07.771  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:11:07.771  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 12:11:07.771  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 12:11:07.772  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 12:11:07.777  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:11:07.778  2638  2638 D BtGatt.ScanManager: awakened up at time 153982
,08-16 12:11:07.779  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 12:11:07.780  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 12:11:07.780  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:11:07.783  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:11:07.789  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:11:07.789  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:07.789  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:07.789  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:11:07.790  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:11:07.790  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:07.790  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:07.790  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:11:07.790  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:07.790  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:07.790  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:07.791  2638  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:11:07.791  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:07.792  2638  2667 D BtGatt.ScanManager: stopping BLe Batch
,08-16 12:11:07.800  2638  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:11:07.800  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:07.801  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:07.807  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 12:11:07.807  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:08.291  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:11:09.038  1487  2237 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 12:11:09.387  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:09.397  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:09.399  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:09.436  1487  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 12:11:09.437  1487  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 12:11:09.437  1487  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:11:09.437  1487  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:09.464  3591  3591 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 12:11:09.464  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 12:11:09.464  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 12:11:11.871  1845  2692 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 12:11:12.792  3852  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 12:11:12.798  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:12.813  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:11:12.820  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:12.821  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:11:12.821  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 12:11:12.822  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:11:12.822  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 12:11:12.822  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:11:12.823  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:11:12.828  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:12.836  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 12:11:12.836  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:11:12.837  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:12.850  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:11:12.852  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 12:11:12.852  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:11:12.863  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 12:11:12.864  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
,08-16 12:11:12.864  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 12:11:12.866  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:11:12.874  2638  2649 D BtGatt.GattService: registerClient() - UUID=d3d0dcc6-8c48-4b2d-82a0-86a03836346a
,08-16 12:11:12.876  2638  2660 D BtGatt.GattService: onClientRegistered() - UUID=d3d0dcc6-8c48-4b2d-82a0-86a03836346a, clientIf=5
08-16 12:11:12.877  3852  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:11:12.879  2638  2650 D BtGatt.GattService: start scan with filters
,08-16 12:11:12.889  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:11:12.889  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-16 12:11:12.889  2638  2667 D BtGatt.ScanManager: handling starting scan
08-16 12:11:12.890  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:11:12.890  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 12:11:12.906  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:11:12.907  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:11:12.908  2638  2660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 12:11:12.908  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:12.909  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:11:12.910  2638  2667 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 12:11:12.917  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:11:12.924  2638  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 12:11:12.924  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:12.924  2638  2667 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 12:11:12.925  2638  2667 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 12:11:12.930  3852  3901 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 12:11:12.936  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:12.937  3852  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 12:11:12.937  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:12.938  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 12:11:12.938  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:12.938  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 12:11:12.938  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 12:11:12.938  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:11:12.939  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:11:12.939  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:11:12.940  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:11:12.940  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 12:11:12.943  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:11:12.945  2638  2649 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:11:12.952  2638  2649 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:11:12.953  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:11:12.953  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 12:11:12.953  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:11:12.954  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:11:12.954  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:11:12.954  2638  2660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:11:12.954  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:12.958  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:11:12.959  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:11:12.959  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 12:11:12.959  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:11:12.959  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:11:12.962  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:11:12.962  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:12.962  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:12.962  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:11:12.962  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:11:12.962  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:11:12.962  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:12.962  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:12.962  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:12.962  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:12.962  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:12.963  2638  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 12:11:12.963  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:12.963  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:12.963  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:12.964  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:12.964  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:12.964  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:12.964  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:12.965  3852  3901 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:11:12.967  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:12.972  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:11:12.973  2638  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:11:12.973  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:12.973  2638  2667 D BtGatt.ScanManager: stopping BLe Batch
08-16 12:11:12.974  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:12.975  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:11:12.975  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:11:12.976  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:11:12.976  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:11:12.976  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:11:12.976  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:11:12.978  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:12.980  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:11:12.980  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:11:12.981  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:12.981  2638  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:11:12.981  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:12.981  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 12:11:12.984  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:11:12.985  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:11:12.985  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 12:11:12.989  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 12:11:12.989  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 12:11:12.989  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 12:11:12.990  3852  3901 D BluetoothAdapter: STATE_ON
08-16 12:11:12.992  2638  2649 D BtGatt.GattService: registerClient() - UUID=06fcdc98-557b-45b6-ac5b-31033e09fb88
,08-16 12:11:12.992  2638  2660 D BtGatt.GattService: onClientRegistered() - UUID=06fcdc98-557b-45b6-ac5b-31033e09fb88, clientIf=5
08-16 12:11:12.993  3852  3864 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 12:11:12.993  2638  2650 D BtGatt.GattService: start scan with filters
08-16 12:11:12.995  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-16 12:11:12.995  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:12.995  2638  2660 D BtGatt.GattService: current time is 159200268107
08-16 12:11:12.996  2638  2660 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 12:11:12.996  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 12:11:12.996  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:11:12.996  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 12:11:12.996  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:11:12.996  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 12:11:12.997  2638  2667 D BtGatt.ScanManager: handling starting scan
08-16 12:11:12.999  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:11:12.999  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:11:12.999  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 12:11:13.001  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 12:11:13.004  3852  3901 I io.jxcore.node.ConnectionHelper: start: OK
08-16 12:11:13.004  2638  2660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 12:11:13.004  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:13.004  2638  2667 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 12:11:13.011  2638  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 12:11:13.011  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:13.011  2638  2667 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:11:13.011  2638  2667 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 12:11:13.022  2638  2660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:11:13.023  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:13.028  2638  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 12:11:13.029  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:13.422  3116  3936 V KeepSync: Connecting to GoogleApiClient
08-16 12:11:13.423   875   886 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 12:11:13.499  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 12:11:13.499  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:11:13.499  3852  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:11:13.532  2638  2638 D BtGatt.ScanManager: awakened up at time 159736
,08-16 12:11:13.534  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:13.556  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-16 12:11:13.557  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:13.557  2638  2660 D BtGatt.GattService: current time is 159761534517
,08-16 12:11:13.557  2638  2660 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 12:11:13.557  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 12:11:13.558  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 12:11:13.558  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 12:11:13.560  1487  1931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 12:11:13.560  1487  1931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 12:11:13.561  1487  1931 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:11:13.561  1487  1931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:13.577  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 12:11:13.578  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 12:11:13.578  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:11:13.579  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 12:11:13.581  1691  3939 V BaseAuthAsyncOperation: access token request failed
08-16 12:11:13.583  3116  3936 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 12:11:13.610  3060  3938 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 12:11:13.610  3060  3938 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jdm.a(PG:82)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jcs.o(PG:406)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jcn.a(PG:1379)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jcs.i(PG:143)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at blb.a(PG:3937)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at czp.a(PG:18188)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at czp.a(PG:9081)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at czq.run(PG:1686)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:11:13.610  3060  3938 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jdj.a(PG:4091)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jdj.a(PG:1125)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jdm.a(PG:77)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	... 12 more
08-16 12:11:13.610  3060  3938 E HttpOperation: Caused by: faj: BadAuthentication
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at fal.a(PG:38)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	at jdj.a(PG:4089)
08-16 12:11:13.610  3060  3938 E HttpOperation: 	... 14 more
,08-16 12:11:13.676  1487  1931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 12:11:13.676  1487  1931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 12:11:13.676  1487  1931 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:11:13.676  1487  1931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:13.681  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 12:11:13.681  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 12:11:13.681  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:11:13.681  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:13.691  3060  3938 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 12:11:13.691  3060  3938 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jdm.a(PG:82)
08-16 12:11:13.691  3060  3938 E HttpOperation: ,	at jcs.o(PG:406)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jcn.a(PG:1379)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jcs.i(PG:143)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at hec.a(PG:42)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at hee.a(PG:102)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at czr.a(PG:65)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at kka.a(PG:108)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at czp.a(PG:19176)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at czp.a(PG:9081)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at czq.run(PG:1686)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:11:13.691  3060  3938 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jdj.a(PG:4091)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jdj.a(PG:1125)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jdm.a(PG:77)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	... 15 more
08-16 12:11:13.691  3060  3938 E HttpOperation: Caused by: faj: BadAuthentication
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at fal.a(PG:38)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	at jdj.a(PG:4089)
08-16 12:11:13.691  3060  3938 E HttpOperation: 	... 17 more
,08-16 12:11:13.692  3060  3938 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 12:11:13.692  3060  3938 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at hec.a(PG:42)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at hee.a(PG:102)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at czr.a(PG:65)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at kka.a(PG:108)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	... 15 more
08-16 12:11:13.692  3060  3938 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at fal.a(PG:38)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 12:11:13.692  3060  3938 E ExperimentLoader: 	... 17 more
,08-16 12:11:13.699  3116  3936 E KeepSync: IOException
08-16 12:11:13.699  3116  3936 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 12:11:13.699  3116  3936 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 12:11:13.699  3116  3936 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140),
08-16 12:11:13.699  3116  3936 E KeepSync: 	... 10 more
08-16 12:11:13.701  3116  3936 W KeepSync: Sync result 2
,08-16 12:11:13.708   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130187, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 12:11:13.783   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 132394, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 12:11:14.061  2638  2638 D BtGatt.ScanManager: awakened up at time 160265
08-16 12:11:14.063  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:14.104  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-16 12:11:14.104  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:14.105  2638  2660 D BtGatt.GattService: current time is 160309688062
,08-16 12:11:14.106  2638  2660 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -89, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 12:11:14.107  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 12:11:14.108  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 12:11:15.607  2638  2638 D BtGatt.ScanManager: awakened up at time 161812
,08-16 12:11:15.611  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:15.655  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-16 12:11:15.655  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:15.656  2638  2660 D BtGatt.GattService: current time is 161860482956
,08-16 12:11:15.657  2638  2660 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -95, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -94, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -90, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-16 12:11:15.657  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 12:11:15.658  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 12:11:15.659  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 12:11:15.660  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 12:11:15.660  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 12:11:15.661  2638  2660 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-16 12:11:17.159  2638  2638 D BtGatt.ScanManager: awakened up at time 163363
,08-16 12:11:17.161  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:17.179  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 12:11:17.179  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:17.531   875  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 12:11:18.004  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:18.005  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:18.005  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:11:18.006  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:18.006  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 12:11:18.006  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:11:18.007  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:11:18.007  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 12:11:18.008  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:11:18.009  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:11:18.009  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 12:11:18.011  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:11:18.013  2638  2649 D BtGatt.GattService: stopScan() - queue size =1
08-16 12:11:18.016  2638  2650 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 12:11:18.017  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:11:18.017  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 12:11:18.018  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 12:11:18.018  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 12:11:18.018  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:11:18.022  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:11:18.022  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:11:18.023  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 12:11:18.023  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:11:18.024  2638  2638 D BtGatt.ScanManager: awakened up at time 164229
,08-16 12:11:18.024  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:11:18.030  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:11:18.030  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:11:18.030  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:11:18.033  2638  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 12:11:18.033  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:18.033  2638  2667 D BtGatt.ScanManager: stopping BLe Batch
,08-16 12:11:18.046  2638  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 12:11:18.046  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:11:18.047  2638  2667 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:11:18.059  2638  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 12:11:18.059  2638  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:11:18.531  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:11:18.531  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:18.532  3852  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:11:23.031  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:23.032  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:23.032  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:11:23.034  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.034  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.034  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:11:23.035  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.035  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.036  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:23.036  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.036  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.038  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.038  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.042  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:23.042  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:23.042  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.043  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:23.045  3852  3901 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 12:11:23.047  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:23.048  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:23.048  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:23.048  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.049  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.049  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.049  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.050  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.050  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.050  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.050  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.050  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.051  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.051  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.053  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:23.053  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:23.053  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.053  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:23.054  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:11:23.054  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:23.055  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:23.055  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:23.055  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:23.055  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.055  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.055  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.055  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:23.056  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.056  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 12:11:23.056  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.056  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.056  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.056  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.058  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:23.058  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:23.058  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.058  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:23.059  3852  3901 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 12:11:23.059  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:23.059  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:23.059  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:11:23.059  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.060  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 12:11:23.060  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.060  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.060  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:23.060  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.060  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:23.060  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.060  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.060  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.060  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.062  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:23.062  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:23.062  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:23.062  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.063  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 12:11:23.063  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:23.063  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:23.063  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:23.064  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.064  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.064  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.064  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:23.064  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.064  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.064  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.064  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.064  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.064  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.064  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.066  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:23.067  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:23.067  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.067  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.067  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:11:23.068  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:11:23.068  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:11:23.068  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:11:23.068  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:11:23.068  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 12:11:23.068  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 12:11:23.068  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:11:23.068  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:11:23.069  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:23.069  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:23.069  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:23.069  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.069  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.069  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.069  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.069  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.070  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:23.070  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.070  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.070  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.070  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.070  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.072  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:23.072  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:23.072  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:23.073  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.074  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:11:23.075  3852  3901 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 12:11:23.075  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 12:11:23.082  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:11:23.082  3852  3901 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 12:11:23.082  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 12:11:23.082  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 12:11:23.083  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-16 12:11:23.083  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-16 12:11:23.083  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-16 12:11:23.083  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 12:11:23.083  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 12:11:23.083  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 12:11:23.084  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:11:23.084  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:11:23.084  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-16 12:11:23.084  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 12:11:23.084  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:11:23.084  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:11:23.085  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
08-16 12:11:23.086  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 12:11:23.086  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
08-16 12:11:23.086  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:11:23.086  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-16 12:11:23.087  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:11:23.087  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:11:23.087  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-16 12:11:23.087  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:11:23.087  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 12:11:23.088  3852  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:11:23.088  3852  3901 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 12:11:23.088  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 12:11:23.088  3852  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:11:23.089  3852  3901 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 12:11:23.089  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 12:11:23.089  3852  3901 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:11:23.089  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 12:11:23.094  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 12:11:23.095  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-16 12:11:23.095  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 12:11:23.096  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-16 12:11:23.096  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 12:11:23.096  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-16 12:11:23.096  3852  3901 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:11:23.097  3852  3901 E io.jxcore.node.ConnectionHelper: connect: Callback is null,
08-16 12:11:23.097  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:23.097  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:23.098  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 12:11:23.098  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:23.098  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.098  3852  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-16 12:11:23.098  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.099  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 12:11:23.100  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.100  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:23.100  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.100  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.101  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.101  3852  3942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-16 12:11:23.101  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 12:11:23.101  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.101  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.103  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:23.104  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:23.104  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.104  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list,
08-16 12:11:23.106  3852  3901 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 12:11:23.106  3852  3941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:11:23.107  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:23.108  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:23.108  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:11:23.108  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.109  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.109  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.109  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.109  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.110  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:23.110  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.110  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.110  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.110  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.111  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 12:11:23.116  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:23.116  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:23.116  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.116  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.117  3852  3901 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 12:11:23.117  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:23.117  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:23.117  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:11:23.118  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.118  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.118  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.118  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:23.118  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.118  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.118  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:23.118  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.118  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.118  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.118  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:23.119  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:23.119  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:23.119  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.119  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.120  3852  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-16 12:11:23.120  3852  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 12:11:23.120  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:11:23.120  3852  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 12:11:23.120  3852  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-16 12:11:23.120  3852  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 12:11:23.120  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:11:23.120  3852  3901 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 12:11:23.121  3852  3901 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:11:23.121  3852  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 12:11:23.121  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:11:23.121  3852  3901 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 12:11:23.121  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:23.121  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:23.121  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:23.121  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.121  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.121  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.121  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:23.122  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.122  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.122  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.122  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.122  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.122  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.122  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.123  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:23.123  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:23.123  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.123  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.123  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:23.123  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:23.123  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:23.124  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:23.124  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:23.124  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:23.124  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:23.124  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:23.124  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.125  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:28.125  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:28.126  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:28.126  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.126  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.127  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:28.127  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:28.127  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:28.128  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 12:11:28.130  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:28.130  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.130  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.131  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:28.131  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:28.131  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:28.132  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:28.132  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.132  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.132  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.133  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.137  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:28.137  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:28.137  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 12:11:28.138  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:28.144  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 12:11:28.144  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:11:28.145  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 12:11:28.146  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
08-16 12:11:28.146  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING,
08-16 12:11:28.147  3852  3852 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 12:11:28.147  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 12:11:28.147  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-16 12:11:28.147  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:28.147  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 12:11:28.148  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 12:11:28.148  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
08-16 12:11:28.148  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.148  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 12:11:28.148  3852  3852 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 12:11:28.148  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:28.148  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:28.148  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:11:28.149  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:11:28.149  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:11:28.149  3852  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 12:11:28.149  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.149  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.149  3852  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 12:11:28.151  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:11:28.152  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:11:28.152  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:11:28.152  3852  3852 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 12:11:28.152  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:11:28.152  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:28.152  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:28.152  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:28.153  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:28.153  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:11:28.153  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.153  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.153  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:28.153  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:28.153  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:28.153  38,52  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:28.154  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.154  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.154  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.154  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.156  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:11:28.156  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:11:28.156  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:28.156  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:28.159  3852  3901 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 12:11:28.160  3852  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:11:28.160  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 12:11:28.161  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 12:11:28.161  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:11:28.162  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:28.162  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:28.162  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:28.163  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:28.164  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.164  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.164  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:28.164  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:28.166  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:28.166  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:28.167  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.168  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.169  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.169  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.171  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:28.171  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:28.171  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:28.171  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list,
,08-16 12:11:28.186  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:11:28.186  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:11:28.187  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 12:11:28.187  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:28.187  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.187  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.188  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
,08-16 12:11:28.188  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:28.188  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:28.188  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:28.189  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.189  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.189  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.189  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.192  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:28.192  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:28.192  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:28.193  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:28.196  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:11:28.196  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:11:28.197  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:11:28.197  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:11:28.197  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.197  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.198  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c18507b not in the list
08-16 12:11:28.198  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:28.198  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
08-16 12:11:28.198  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:28.198  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:28.199  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:28.200  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:28.200  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:11:28.203  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:11:28.203  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:11:28.203  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:28.203  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@901ee98 not in the list
,08-16 12:11:28.236  2638  2776 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-16 12:11:28.237  2638  2788 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 12:11:28.238  3852  3941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
,08-16 12:11:28.653  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:11:30.060   875  2082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 12:11:33.208  3852  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 12:11:33.208  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:11:33.209  3852  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 12:11:33.209  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 12:11:33.210  3852  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 12:11:33.210  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 12:11:33.220  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 12:11:33.220  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 12:11:33.223  3852  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 12:11:33.224  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:11:33.224  3852  3901 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 12:11:33.224  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:11:33.224  3852  3901 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 12:11:33.224  3852  3901 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 12:11:33.225  3852  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 12:11:33.225  3852  3901 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 12:11:33.225  3852  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 12:11:33.225  3852  3901 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 12:11:33.225  3852  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 12:11:33.226  3852  3901 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 12:11:33.227  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:11:33.227  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cda4e6b added. We now have 3 listener(s)
08-16 12:11:33.227  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:11:33.230  3852  3901 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 12:11:33.231   875  3221 D WifiService: setWifiEnabled: true pid=3852, uid=10000
,08-16 12:11:33.231   875  3221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:11:35.826  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:35.839  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:35.841  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:35.908  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 12:11:35.909  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 12:11:35.909  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:11:35.910  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:35.976  3591  3591 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 12:11:35.977  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 12:11:35.981  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 12:11:38.240  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:11:38.241  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9a2dc8 added. We now have 4 listener(s)
08-16 12:11:38.241  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:11:38.262  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:38.263  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9a2dc8 removed from the list
08-16 12:11:38.263  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:38.264  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:38.264  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:38.266  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:11:38.267  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2489e61 added. We now have 4 listener(s)
,08-16 12:11:38.267  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:11:38.271  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:38.272  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2489e61 removed from the list
,08-16 12:11:38.272  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:38.272  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:38.273  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 12:11:38.275  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:11:38.276  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9332d86 added. We now have 4 listener(s)
08-16 12:11:38.276  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:11:38.283   875  2012 D WifiService: setWifiEnabled: false pid=3852, uid=10000
08-16 12:11:38.283   875  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:11:38.296  2638  2656 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 12:11:38.296  2638  2656 D BluetoothAdapterProperties: Setting state to 13
08-16 12:11:38.297  2638  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 12:11:38.297  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:11:38.299  2638  2656 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 12:11:38.301  2638  2656 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:11:38.307  2638  2660 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:11:38.307  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:38.308  2638  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:38.308  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:11:38.311  2638  2638 D BluetoothMapService: onReceive
08-16 12:11:38.311  2638  2638 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:11:38.312  2638  2638 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:11:38.312  2638  2638 D BluetoothMapService: MAP Service closeService in
08-16 12:11:38.313  2638  2638 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 12:11:38.313  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:38.313  2638  2638 D ObexServerSockets0: shutdown(block = true)
08-16 12:11:38.313  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:38.314  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:11:38.318  2638  2802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 12:11:38.320  2638  2638 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 12:11:38.320  2638  2788 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 12:11:38.320  2638  2803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 12:11:38.320  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:38.321  2638  2638 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 12:11:38.321  2638  2638 I BtOppRfcommListener: stopping Accept Thread
,08-16 12:11:38.321  2638  3482 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 12:11:38.321  2638  3482 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 12:11:38.323  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:38.327  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:38.327  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:11:38.328  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:38.328  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:38.331  1424  1424 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 12:11:38.332   875   888 I ActivityManager: Start proc 3947:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 12:11:38.332  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
,08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:38.333  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:11:38.334  2638  2638 D HeadsetService: Received stop request...Stopping profile...
,08-16 12:11:38.334   875  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 12:11:38.334   875  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 12:11:38.334   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
08-16 12:11:38.334   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:11:38.335   875   875 D BluetoothHeadset: Proxy object disconnected
,08-16 12:11:38.335   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:38.336  1983  2065 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:38.337  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.337  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:38.338   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:38.338  1362  1374 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:38.340  2638  2638 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:38.340  2638  2638 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:38.340  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:38.340  2638  2638 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:38.342  2638  2638 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 12:11:38.343  2638  2638 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:11:38.343  2638  2660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 12:11:38.343  2638  2776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:38.343  2638  2776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 12:11:38.343  2638  2776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:38.343  2638  2660 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 12:11:38.344  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.345  2638  2638 D A2dpService: Received stop request...Stopping profile...
08-16 12:11:38.346  2638  2797 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:11:38.348   875   875 D BluetoothA2dp: Proxy object disconnected
08-16 12:11:38.348  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-16 12:11:38.348  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-16 12:11:38.349  2638  2638 D HidService: Received stop request...Stopping profile...
08-16 12:11:38.349  2638  2638 D HidService: Stopping Bluetooth HidService
08-16 12:11:38.350  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-16 12:11:38.350  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.350  1362  1362 D HidProfile: Bluetooth service disconnected
08-16 12:11:38.351  2638  2638 D HealthService: Received stop request...Stopping profile...
08-16 12:11:38.352   875  1317 E native  : do suspend true
08-16 12:11:38.352  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.354  2638  2638 D PanService: Received stop request...Stopping profile...
08-16 12:11:38.355  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 12:11:38.355  1362  1362 D PanProfile: Bluetooth service disconnected
08-16 12:11:38.355  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.356  2638  2638 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:11:38.356  2638  2638 D BluetoothMapService: stop()
08-16 12:11:38.357  2638  2638 D BluetoothMapAppObserver: deinitObservers()
08-16 12:11:38.357  2638  2638 D BluetoothMapAppObserver: removeReceiver()
08-16 12:11:38.359  1362  1362 D BluetoothMap: Proxy object disconnected
08-16 12:11:38.359  2638  2638 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:38.359  1362  1362 D MapProfile: Bluetooth service disconnected
08-16 12:11:38.359  2638  2638 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:38.359  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:38.359  2638  2638 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:38.360  2638  2776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:38.360  2638  2776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:38.361  2638  2776 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:11:38.361  2638  2776 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:11:38.361  2638  2776 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:11:38.361  2638  2776 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:11:38.361  2638  2660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 12:11:38.362  2638  2638 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:38.364  2638  2638 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:38.364  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:38.364  2638  2638 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:38.364   371   873 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:11:38.365   875  2083 D DhcpClient: Clearing IP address
08-16 12:11:38.365  2638  2638 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 12:11:38.367  2638  2638 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:11:38.367  2638  2638 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:38.367  2638  2638 V BluetoothAdapterState,: isTurningOn()=false
08-16 12:11:38.367  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:38.367  2638  2638 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:38.368  2638  2638 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 12:11:38.368  2638  2638 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:11:38.368  2638  2638 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:38.368  2638  2638 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:38.368   371   873 D CommandListener: Setting iface cfg
08-16 12:11:38.368  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:38.368  2638  2638 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:38.368  2638  2638 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:11:38.369  2638  2638 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 12:11:38.372  2638  2660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 12:11:38.372  2638  2660 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 12:11:38.373   875  2087 D DhcpClient: Receive thread stopped
08-16 12:11:38.375  1487  2543 V NativeCrypto: Read error: ssl=0x9b385200: I/O error during system call, Connection timed out
,08-16 12:11:38.378   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 12:11:38.378  2638  2638 D BluetoothMapService: MAP Service closeService in
,08-16 12:11:38.378   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 12:11:38.378  2638  2638 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:11:38.378  2638  2638 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:11:38.378  1487  2543 V NativeCrypto: SSL shutdown failed: ssl=0x9b385200: I/O error during system call, Broken pipe
,08-16 12:11:38.378  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:38.378  2638  2638 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:38.378  2638  2638 D BluetoothMapService: cleanup()
,08-16 12:11:38.378  2638  2638 D BluetoothMapService: MAP Service closeService in
,08-16 12:11:38.379  2638  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 12:11:38.379  2638  2656 D BluetoothAdapterProperties: Setting state to 15
,08-16 12:11:38.379  2638  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 12:11:38.379  1362  1380 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:11:38.380  2638  2656 I BluetoothAdapterState: Entering BleOnState
08-16 12:11:38.381   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:11:38.381   394   394 E Parcel  : Reading a NULL string not supported here.
08-16 12:11:38.381   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:38.381   875  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 12:11:38.381  1362  2084 D BluetoothPan: onBluetoothStateChange on: false
,08-16 12:11:38.382   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:11:38.382   875  1317 E native  : do suspend true
,08-16 12:11:38.382  1362  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 12:11:38.385  1362  2084 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:11:38.385   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:11:38.385   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 12:11:38.386  1983  2065 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:38.386  1362  2081 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:11:38.386   875  1321 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 12:11:38.387  1362  2084 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 12:11:38.389  2638  2656 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 12:11:38.389  2638  2656 D BluetoothAdapterProperties: Setting state to 16
08-16 12:11:38.389  2638  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 12:11:38.389  2638  2656 D BluetoothAdapterProperties: onBleDisable
08-16 12:11:38.389  2638  2656 I BluetoothAdapterState: Entering PendingCommandState
08-16 12:11:38.390  2638  2657 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 12:11:38.391  2638  2776 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 12:11:38.391  2638  2776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:38.391  2638  2660 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:11:38.392  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:38.392  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:38.393  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:38.393  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:38.394  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:38.394  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:38.395  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.395  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:38.396  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:38.396  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:38.397  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.397  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:38.398  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.400  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.401  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.419   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 12:11:38.436   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 12:11:38.436   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:11:38.437   875  1321 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 12:11:38.437   875  1321 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 12:11:38.439   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 12:11:38.442   875   892 D Tethering: MasterInitialState.processMessage what=3
08-16 12:11:38.445  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.446  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.447  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:38.453  3485  3485 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7a352f2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 12:11:38.461   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:11:38.464  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:38.464  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:38.464  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.464  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:38.466  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:38.466  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:38.466  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.466  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:38.466   875  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 12:11:38.467  1845  2270 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:11:38.468  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:38.468  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:38.468  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:38.468  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:38.470  3947  3947 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 12:11:38.479  3947  3947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:11:38.483   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc9e44b:true
,08-16 12:11:38.484  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:11:38.497   875  1383 I ActivityManager: Start proc 3969:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 12:11:38.501   371   873 E Netd    : netlink response contains error (No such file or directory)
,08-16 12:11:38.501   875  1321 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 12:11:38.508  3947  3947 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 12:11:38.510  3947  3947 D BluetoothMap: Create BluetoothMap proxy object
,08-16 12:11:38.515  3947  3947 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 12:11:38.520  3947  3947 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:11:38.523   875   885 I ActivityManager: Killing 2225:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 12:11:38.584  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 12:11:38.601  2638  2660 I bt_hci  : shut_down
,08-16 12:11:38.613  2638  2668 D bt_hwcfg: hw_epilog_process
,08-16 12:11:38.614  2638  2668 I bt_vendor: low_power_mode_cb
,08-16 12:11:38.639  2638  2668 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 12:11:38.640  2638  2668 I bt_vendor: epilog_cb
08-16 12:11:38.640  2638  2668 I bt_hci  : epilog_finished_callback
,08-16 12:11:38.646  2638  2660 I bt_hci_h4: hal_close
,08-16 12:11:38.647  2638  2660 I bt_userial_vendor: device fd = 51 close
,08-16 12:11:38.720  3969  3969 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.720  3969  3969 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.720  3969  3969 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.720  3969  3969 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.720  3969  3969 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.720  3969  3969 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.720  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.721  3969  3969 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.721  3969  3969 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:11:38.721  3969  3969 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:11:38.750   875   886 I ActivityManager: Start proc 3998:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 12:11:38.751   875   886 I ActivityManager: Killing 3485:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 12:11:38.839  2638  2657 D bt_stack_manager: event_shut_down_stack finished.
,08-16 12:11:38.840  2638  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 12:11:38.842  2638  2656 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 12:11:38.842  2638  2638 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:11:38.843  2638  2638 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 12:11:38.843  2638  2638 D BtGatt.GattService: stop()
,08-16 12:11:38.843  3998  3998 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
08-16 12:11:38.843  2638  2638 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 12:11:38.845  2638  2638 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:38.845  2638  2638 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:38.845  2638  2638 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:38.845  2638  2638 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 12:11:38.845  2638  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 12:11:38.845  2638  2656 D BluetoothAdapterProperties: Setting state to 10
08-16 12:11:38.845  2638  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 12:11:38.846  2638  2656 I BluetoothAdapterState: Entering OffState
,08-16 12:11:38.847   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 12:11:38.854  2638  2638 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 12:11:38.854  2638  2638 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 12:11:38.854  2638  2638 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 12:11:38.855  2638  2657 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 12:11:38.857  2638  2657 D bt_stack_manager: event_clean_up_stack finished.
,08-16 12:11:38.873  2638  2638 I art     : System.exit called, status: 0
08-16 12:11:38.873  2638  2638 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 12:11:38.925   875  1383 I ActivityManager: Process com.android.bluetooth (pid 2638) has died
,08-16 12:11:39.124  3998  4018 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 12:11:39.124  3998  4018 I Babel_SMS: MmsConfig.loadMmsSettings
08-16 12:11:39.125  3998  4018 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 12:11:39.125  3998  4018 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 12:11:39.169  3998  4018 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 12:11:39.170  3998  4018 I Babel_SMS: MmsConfig.loadFromResources
,08-16 12:11:39.175  3998  4018 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 12:11:39.175  3998  4018 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 12:11:39.199  3998  3998 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:11:39.203  3998  3998 I Babel_Crash: startup - clean
,08-16 12:11:39.230  3998  3998 I Babel_telephony: TeleModule.launchCompleted
,08-16 12:11:39.248   875  2012 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 12:11:39.260  3998  3998 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 12:11:39.266  3998  3998 W Babel   : BAM#gBA: invalid account id: -1
,08-16 12:11:39.267  3998  3998 W Babel   : BAM#gBA: invalid account id: -1
,08-16 12:11:39.267  3998  3998 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 12:11:39.289  3998  4024 I Babel   : deleted: false for 0
,08-16 12:11:39.299   875  1423 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 12:11:39.313  3947  3947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:11:39.332   875   885 I ActivityManager: Start proc 4027:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 12:11:39.334  3947  3947 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:11:39.372  3998  3998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:11:39.398  3969  3987 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding HeadsetService
,08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding A2dpService
,08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding HidService
,08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding HealthService
08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding PanService
,08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding GattService
08-16 12:11:39.438  4027  4027 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 12:11:39.442  3998  3998 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 12:11:39.454  3998  3998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:11:39.456  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:11:39.478  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:11:39.479  3998  3998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:11:39.484  1691  1691 D SystemUpdateService: onCreate
,08-16 12:11:39.487  3998  3998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:11:39.500  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:11:39.509  1691  4040 I SystemUpdateService: active receiver: enabled
,08-16 12:11:39.508  3998  3998 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:11:39.542  1691  4040 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:11:39.558   875  1917 I ActivityManager: Killing 3549:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 12:11:39.559  1691  4040 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 12:11:39.560  1691  4040 I SystemUpdateService: now status is 0 (complete)
,08-16 12:11:39.560  1691  4040 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 12:11:39.560  1691  4040 I SystemUpdateService: file has been verified
08-16 12:11:39.561  1691  4040 I SystemUpdateService: OTA package size = 12249756
,08-16 12:11:39.566  1691  4040 I SystemUpdateService: showing system update notification
,08-16 12:11:39.610  3998  3998 I vclib   : onServiceConnected
08-16 12:11:39.610  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 12:11:39.618  1691  2521 I iu.UploadsManager: num queued entries: 0
,08-16 12:11:39.619  1691  2521 I iu.UploadsManager: num updated entries: 0
,08-16 12:11:39.619  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:11:39.622  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:11:39.626  1691  2521 I iu.SyncManager: NEXT; no task
,08-16 12:11:39.636   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a000ff:true
,08-16 12:11:39.641   875  1980 I ActivityManager: Start proc 4042:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 12:11:39.643  1691  1691 D SystemUpdateService: onDestroy
,08-16 12:11:39.675  4042  4042 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 12:11:39.678  4042  4042 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:11:39.683  4042  4042 D SprintDMHelper: simOperator: 
08-16 12:11:39.683  4042  4042 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:11:39.705   875  1423 I ActivityManager: Start proc 4054:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 12:11:39.706   875  1423 I ActivityManager: Killing 3101:android.process.acore/u0a5 (adj 15): empty #17
,08-16 12:11:39.843   875  1383 I ActivityManager: Start proc 4069:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 12:11:39.847  3998  4068 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 12:11:39.851   875  3221 I ActivityManager: Killing 3737:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 12:11:39.914  4069  4069 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 12:11:39.969  4069  4069 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 12:11:39.969  4069  4069 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 12:11:39.969  4069  4069 I GAv4    :   adb logcat -s GAv4
,08-16 12:11:39.983  4069  4069 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 12:11:39.990  4069  4069 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 12:11:40.016  4069  4086 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 12:11:40.126  4069  4069 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 12:11:40.164  4069  4069 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 12:11:40.171  4069  4069 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6373-6376)
,08-16 12:11:40.172  4069  4069 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 12:11:40.184  4069  4069 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9525ca2}
,08-16 12:11:40.184  4069  4069 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 12:11:40.184  4069  4069 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 12:11:40.193  4069  4069 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 12:11:40.194  4069  4069 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 12:11:40.212  4069  4069 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 12:11:40.224  4069  4069 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 12:11:40.224  4069  4069 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 12:11:40.224  4069  4069 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 12:11:40.224  4069  4069 I Adreno  : Build Date                       : 10/20/15
08-16 12:11:40.224  4069  4069 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 12:11:40.224  4069  4069 I Adreno  : Local Branch                     : M14
08-16 12:11:40.224  4069  4069 I Adreno  : Remote Branch                    : 
08-16 12:11:40.224  4069  4069 I Adreno  : Remote Branch                    : 
08-16 12:11:40.224  4069  4069 I Adreno  : Reconstruct Branch               : 
,08-16 12:11:40.289  4069  4069 I NSApplication: Starting up...
,08-16 12:11:40.302  4069  4115 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 12:11:40.335   875  2012 I ActivityManager: Start proc 4120:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-16 12:11:40.336   875  2012 I ActivityManager: Killing 3750:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 12:11:40.430  4120  4120 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 12:11:40.615   875  2012 I ActivityManager: Killing 3510:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 12:11:43.316   875  2016 D WifiService: setWifiEnabled: true pid=3852, uid=10000
,08-16 12:11:43.316   875  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:11:43.329   875  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-16 12:11:43.338  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:43.338  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:43.339  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:43.339  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:43.341  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:43.342  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:43.342  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:43.342  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:43.344  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:43.345  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:43.345  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:43.345  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:43.354   875  1317 D WifiConfigStore: loaded 0 passpoint configs
08-16 12:11:43.355   875  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 12:11:43.356   875  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 12:11:43.358   875  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 12:11:43.358   875  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 12:11:43.359   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 12:11:43.359   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 12:11:43.380   371   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 12:11:43.381   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 12:11:43.382   371   873 D CommandListener: Setting iface cfg
,08-16 12:11:43.390   875  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 12:11:43.390   875  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 12:11:43.391   875  1317 E native  : do suspend true
,08-16 12:11:43.398   875  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 12:11:43.398   875  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 12:11:43.404   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:11:44.327   875  1990 I ActivityManager: Killing 3703:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-16 12:11:44.758   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 12:11:44.793   875  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.44 rxSuccessRate=7.69 delta 1000 -> 994
,08-16 12:11:44.795   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 12:11:44.795   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:11:44.811   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 12:11:44.872   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 12:11:44.873  1424  1424 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 12:11:45.290  1424  1424 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 12:11:45.329  1424  1424 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 12:11:45.330  1424  1424 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 12:11:45.340   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:11:45.358   875  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:11:45.358   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:11:45.359   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 12:11:45.389   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:11:45.409   371   873 D CommandListener: Setting iface cfg
,08-16 12:11:45.409   875  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 12:11:45.418   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 12:11:45.449   875  4146 D DhcpClient: Receive thread started
,08-16 12:11:45.532   875  1317 E native  : do suspend false
,08-16 12:11:45.542   875  2083 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 12:11:45.554   875  4146 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172632, domain null
,08-16 12:11:45.555   875  2083 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172632 seconds
,08-16 12:11:45.558   875  2083 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 12:11:45.570   875  4146 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 12:11:45.571   875  2083 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 12:11:45.575   371   873 D CommandListener: Setting iface cfg
,08-16 12:11:45.585   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 12:11:45.585   875  2083 D DhcpClient: Scheduling renewal in 86399s
,08-16 12:11:45.588   875  1317 E native  : do suspend true
,08-16 12:11:45.607   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 12:11:45.609   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 12:11:45.610   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 12:11:45.611   875  1321 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 12:11:45.618   875  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 12:11:45.681   875  1321 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 12:11:45.682   875  1321 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 12:11:45.683   875  1321 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 12:11:45.686   875  1321 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 12:11:45.688   875  1321 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 12:11:45.701   875  1321 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 12:11:45.708   875  1321 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-16 12:11:45.709   875  1321 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 12:11:45.709   875  1321 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 12:11:45.709   875  1321 D ConnectivityService:    accepting network in place of null
,08-16 12:11:45.709   875  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 12:11:45.710   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:11:45.710   875  1321 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:11:45.714   875  4145 D NetlinkSocketObserver: NeighborEvent{elapsedMs=191918, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 12:11:45.763   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:11:45.780   875  4144 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:815::200e
,08-16 12:11:45.823   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:11:45.829   875  1321 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 12:11:45.829   875  1321 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:11:45.833   875  1321 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 12:11:45.836   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:11:45.843  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:45.844  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:11:45.844  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:45.844  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:45.847   875  4144 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:11:45 GMT], X-Android-Received-Millis=[1471342305847], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471342305822]}
08-16 12:11:45.848  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:45.848  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:11:45.848  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:45.849  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:45.853  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:11:45.853  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:11:45.853  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:45.854   875  1321 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 12:11:45.854  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:11:45.854   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 12:11:45.854   875  1321 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 12:11:45.855   875  1321 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 12:11:45.868  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:11:45.875  1691  1691 D SystemUpdateService: onCreate
,08-16 12:11:45.880  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:11:45.893  1691  4157 I SystemUpdateService: active receiver: enabled
,08-16 12:11:45.903  1691  4157 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:11:45.908  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 12:11:45.911  1691  2521 I iu.UploadsManager: num queued entries: 0
,08-16 12:11:45.912  1691  2521 I iu.UploadsManager: num updated entries: 0
,08-16 12:11:45.912  1691  4157 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 12:11:45.913  1691  4157 I SystemUpdateService: now status is 0 (complete)
08-16 12:11:45.913  1691  4157 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 12:11:45.913  1691  4157 I SystemUpdateService: file has been verified
08-16 12:11:45.914  1691  4157 I SystemUpdateService: OTA package size = 12249756
,08-16 12:11:45.924  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:11:45.925  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:11:45.927  1691  2521 I iu.SyncManager: NEXT; no task
,08-16 12:11:45.928  1691  4157 I SystemUpdateService: showing system update notification
,08-16 12:11:45.938  4042  4042 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:11:45.943  1691  4162 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 12:11:45.944  1691  4162 W BaseAppContext: Using Auth Proxy for data requests.
08-16 12:11:45.946  1691  4162 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
08-16 12:11:45.946  4042  4042 D SprintDMHelper: simOperator: 
08-16 12:11:45.946  4042  4042 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:11:45.963  1691  1691 D SystemUpdateService: onDestroy
08-16 12:11:45.964  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:45.969  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:46.031  1487  2292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 12:11:46.032  1487  2292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 12:11:46.032  1487  2292 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:11:46.032  1487  2292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:46.049  1691  4162 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-16 12:11:46.104  3998  4164 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 12:11:46.830   875  1321 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 12:11:48.323   875  3221 D WifiService: setWifiEnabled: false pid=3852, uid=10000
,08-16 12:11:48.323   875  3221 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:11:48.354  1424  1424 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 12:11:48.361   875  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 12:11:48.361   875  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 12:11:48.361   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:11:48.362   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:11:48.382   875  1317 E native  : do suspend true
,08-16 12:11:48.393   875  2083 D DhcpClient: Clearing IP address
08-16 12:11:48.393   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:11:48.396   371   873 D CommandListener: Setting iface cfg
,08-16 12:11:48.401  1487  4168 V NativeCrypto: Read error: ssl=0x9b385200: I/O error during system call, Connection timed out
,08-16 12:11:48.406  1487  4168 V NativeCrypto: SSL shutdown failed: ssl=0x9b385200: I/O error during system call, Broken pipe
,08-16 12:11:48.407   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 12:11:48.407   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-16 12:11:48.410   875  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 12:11:48.412   394   394 E Parcel  : Reading a NULL string not supported here.
,08-16 12:11:48.418   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:11:48.418   875  1317 E native  : do suspend true
,08-16 12:11:48.426   875  4146 D DhcpClient: Receive thread stopped
,08-16 12:11:48.428   875  1321 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 12:11:48.431   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:11:48.435   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 12:11:48.453   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:11:48.455  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:48.455  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:48.455  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:48.455  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:48.456  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:48.456  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:48.456  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:48.457  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:48.457  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:48.458  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:48.458  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:48.458  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:48.459  1845  2270 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:11:48.464   875  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 12:11:48.475   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:11:48.504   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:11:48.506   875  1321 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 12:11:48.506   875  1321 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:11:48.516   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:11:48.520  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:48.522  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:48.524  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:48.538  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:11:48.543  1691  1691 D SystemUpdateService: onCreate
,08-16 12:11:48.555  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:11:48.567  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 12:11:48.575  1691  4180 I SystemUpdateService: active receiver: enabled
,08-16 12:11:48.577  1691  2521 I iu.UploadsManager: num queued entries: 0
,08-16 12:11:48.580  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:11:48.581  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:11:48.583  4042  4042 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:11:48.587  4042  4042 D SprintDMHelper: simOperator: 
,08-16 12:11:48.587  4042  4042 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:11:48.613   371   873 E Netd    : netlink response contains error (No such file or directory)
,08-16 12:11:48.614   875  1321 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent,
08-16 12:11:48.615  3998  4184 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 12:11:48.619  1691  4180 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:11:48.621  1691  2521 I iu.UploadsManager: num updated entries: 0
,08-16 12:11:48.624  1691  2521 I iu.SyncManager: NEXT; no task
,08-16 12:11:48.624  1691  4180 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 12:11:48.625  1691  4180 I SystemUpdateService: now status is 0 (complete)
,08-16 12:11:48.625  1691  4180 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 12:11:48.625  1691  4180 I SystemUpdateService: file has been verified
08-16 12:11:48.625  1691  4180 I SystemUpdateService: OTA package size = 12249756
,08-16 12:11:48.629  1691  4180 I SystemUpdateService: showing system update notification
,08-16 12:11:48.639  1691  1691 D SystemUpdateService: onDestroy
,08-16 12:11:53.360   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@96843c0:true
,08-16 12:11:53.360  4027  4027 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 12:11:53.365  4027  4027 I bt_bluedroid: init
,08-16 12:11:53.366  4027  4186 I BluetoothAdapterState: Entering OffState
,08-16 12:11:53.371  4027  4187 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 12:11:53.371  4027  4187 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 12:11:53.372  4027  4187 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:11:53.372  4027  4187 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 12:11:53.374  4027  4027 I bt_bluedroid: get_profile_interface socket
,08-16 12:11:53.377  4027  4190 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:11:53.379  4027  4027 I bt_bluedroid: get_profile_interface sdp
,08-16 12:11:53.379  4027  4190 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:11:53.385  4027  4037 I bt_bluedroid: config_hci_snoop_log
,08-16 12:11:53.390   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 12:11:53.399  4027  4186 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 12:11:53.399  4027  4186 D BluetoothAdapterProperties: Setting state to 14
08-16 12:11:53.400  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 12:11:53.404  4027  4186 D BluetoothBondStateMachine: make
,08-16 12:11:53.409  4027  4191 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 12:11:53.415  4027  4186 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:11:53.417  4027  4027 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 12:11:53.423  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:11:53.424  4027  4027 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:11:53.425  4027  4027 D BtGatt.GattService: Received start request. Starting profile...
,08-16 12:11:53.425  4027  4027 D BtGatt.GattService: start()
,08-16 12:11:53.426  4027  4027 I bt_bluedroid: get_profile_interface gatt
,08-16 12:11:53.427  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:11:53.428  4027  4027 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:11:53.437  4027  4027 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:53.437  4027  4027 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:53.437  4027  4027 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 12:11:53.437  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:53.438  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 12:11:53.438  4027  4186 I bt_bluedroid: enable
08-16 12:11:53.439  4027  4187 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 12:11:53.439  4027  4187 I bt_hci  : start_up
,08-16 12:11:53.448  4027  4187 I bt_vendor: alloc value 0xb3979189
,08-16 12:11:53.448  4027  4187 I bt_vendor: init
,08-16 12:11:53.448  4027  4187 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 12:11:53.448  4027  4187 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 12:11:53.561  4027  4187 D bt_hci  : start_up starting async portion
,08-16 12:11:53.561  4027  4194 I bt_hci  : event_finish_startup
,08-16 12:11:53.562  4027  4194 I bt_hci_h4: hal_open
08-16 12:11:53.562  4027  4194 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 12:11:53.574  4027  4194 I bt_userial_vendor: device fd = 51 open
,08-16 12:11:53.599  4027  4194 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:11:53.631  4027  4194 D bt_hwcfg: Chipset BCM4354A2
,08-16 12:11:53.632  4027  4194 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 12:11:53.632  4027  4194 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 12:11:53.714   875  1321 D ConnectivityService: handlePromptUnvalidated 101
,08-16 12:11:54.293  4027  4194 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 12:11:54.294  4027  4194 D bt_hwcfg: Settlement delay -- 100 ms
08-16 12:11:54.294  4027  4194 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 12:11:54.411  4027  4194 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:11:54.412  4027  4194 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 12:11:54.442  4027  4194 I bt_hwcfg: vendor lib fwcfg completed
,08-16 12:11:54.442  4027  4194 I bt_vendor: firmware callback
08-16 12:11:54.442  4027  4194 I bt_hci  : firmware_config_callback
,08-16 12:11:54.454  4027  4196 I bt_btu  : btu_task pending for preload complete event
,08-16 12:11:54.454  4027  4196 I bt_btu_task: Bluetooth chip preload is complete
08-16 12:11:54.454  4027  4196 I bt_btu  : btu_task received preload complete event
,08-16 12:11:54.468  4027  4196 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 12:11:54.469  4027  4196 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 12:11:54.469  4027  4196 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 12:11:54.469  4027  4196 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 12:11:54.469  4027  4196 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 12:11:54.470  4027  4196 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 12:11:54.470  4027  4196 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 12:11:54.470  4027  4196 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 12:11:54.471  4027  4196 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 12:11:54.471  4027  4196 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 12:11:54.471  4027  4196 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 12:11:54.471  4027  4196 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 12:11:54.472  4027  4196 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 12:11:54.472  4027  4196 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 12:11:54.472  4027  4196 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:11:54.601  4027  4196 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
08-16 12:11:54.602  4027  4196 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-16 12:11:54.608  4027  4190 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 12:11:54.610  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 12:11:54.610  4027  4190 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:11:54.612  4027  4190 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:11:54.614  4027  4190 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:11:54.614  4027  4190 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 12:11:54.614  4027  4190 D bt_hci  : do_postload posting postload work item
08-16 12:11:54.615  4027  4194 I bt_hci  : event_postload
08-16 12:11:54.615  4027  4194 I bt_vendor: sco_config_cb
08-16 12:11:54.615  4027  4194 I bt_hci  : sco_config_callback postload finished.
,08-16 12:11:54.621  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:54.622  4027  4194 I bt_vendor: low_power_mode_cb
,08-16 12:11:54.622  4027  4190 D bt_bte_conf: Device ID record 1 : primary
08-16 12:11:54.622  4027  4190 D bt_bte_conf:   vendorId            = 000f
08-16 12:11:54.623  4027  4190 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 12:11:54.623  4027  4190 D bt_bte_conf:   product             = 1200
08-16 12:11:54.623  4027  4190 D bt_bte_conf:   version             = 1436
08-16 12:11:54.623  4027  4190 D bt_bte_conf:   clientExecutableURL = 
,08-16 12:11:54.623  4027  4190 D bt_bte_conf:   serviceDescription  = 
08-16 12:11:54.623  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:54.624  4027  4190 D bt_bte_conf:   documentationURL    = 
08-16 12:11:54.624  4027  4190 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 12:11:54.624  4027  4187 D bt_stack_manager: event_start_up_stack finished
,08-16 12:11:54.625  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 12:11:54.626  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:54.626  4027  4186 D BluetoothAdapterProperties: Setting state to 15
,08-16 12:11:54.626  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 12:11:54.627  4027  4186 I BluetoothAdapterState: Entering BleOnState
,08-16 12:11:54.630  4027  4186 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 12:11:54.632  4027  4186 D BluetoothAdapterProperties: Setting state to 11
,08-16 12:11:54.632  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 12:11:54.640  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:11:54.641  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:54.641  4027  4027 D HeadsetService: Received start request. Starting profile...
,08-16 12:11:54.642  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:54.643  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:54.649  4027  4027 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 12:11:54.649  4027  4027 D HeadsetStateMachine: make
,08-16 12:11:54.659  4027  4027 D HeadsetStateMachine: max_hf_connections = 1
,08-16 12:11:54.659  4027  4027 I bt_bluedroid: get_profile_interface handsfree
08-16 12:11:54.660  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 12:11:54.660  4027  4190 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 12:11:54.662  4027  4186 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:11:54.663  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:11:54.664  4027  4027 D A2dpService: Received start request. Starting profile...
,08-16 12:11:54.664  4027  4027 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 12:11:54.665  4027  4027 I bt_bluedroid: get_profile_interface avrcp
,08-16 12:11:54.670  4027  4027 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 12:11:54.670  4027  4027 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:11:54.670  4027  4027 D A2dpStateMachine: make
,08-16 12:11:54.672  4027  4027 I bt_bluedroid: get_profile_interface a2dp
,08-16 12:11:54.674  4027  4205 D A2dpStateMachine: Enter Disconnected: -2
,08-16 12:11:54.674  4027  4027 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 12:11:54.675  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
08-16 12:11:54.673  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 12:11:54.676  4027  4027 D HidService: Received start request. Starting profile...
08-16 12:11:54.676  3947  3947 D BluetoothInputDevice: Proxy object connected
08-16 12:11:54.676  4027  4027 I bt_bluedroid: get_profile_interface hidhost
08-16 12:11:54.676  4027  4190 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-16 12:11:54.676  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 12:11:54.677  4027  4027 D HidService: setHidService(): set to: null
08-16 12:11:54.677  3947  3947 D HidProfile: Bluetooth service connected
08-16 12:11:54.677  4027  4027 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 12:11:54.678  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
08-16 12:11:54.678  4027  4027 D HealthService: Received start request. Starting profile...
,08-16 12:11:54.680  4027  4027 I bt_bluedroid: get_profile_interface health
,08-16 12:11:54.683  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:11:54.684  4027  4027 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 12:11:54.685  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:11:54.686  3947  3947 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:11:54.686  4027  4027 D PanService: Received start request. Starting profile...
08-16 12:11:54.686  4027  4027 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 12:11:54.686  4027  4027 I bt_bluedroid: get_profile_interface pan
08-16 12:11:54.687  3947  3947 D PanProfile: Bluetooth service connected
08-16 12:11:54.687  4027  4190 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 12:11:54.692  4027  4027 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:11:54.692  4027  4027 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:54.692  4027  4027 V BluetoothAdapterState: isTurningOn()=true
,08-16 12:11:54.692  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:54.692  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:54.696  3947  3947 D BluetoothMap: Proxy object connected
08-16 12:11:54.696  3947  3947 D MapProfile: Bluetooth service connected
08-16 12:11:54.697  3947  3947 D BluetoothMap: getConnectedDevices()
,08-16 12:11:54.698  4027  4027 D BluetoothMapService: Received start request. Starting profile...
,08-16 12:11:54.698  3947  3947 D BluetoothMap: Bluetooth is Not enabled
08-16 12:11:54.698  4027  4027 D BluetoothMapService: start()
,08-16 12:11:54.703  4027  4027 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 12:11:54.704  4027  4027 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 12:11:54.704  4027  4027 D BluetoothMapAppObserver: createReceiver()
,08-16 12:11:54.706  4027  4027 D BluetoothMapAppObserver: initObservers()
,08-16 12:11:54.706  4027  4027 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 12:11:54.722  4027  4203 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isTurningOn()=true
08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isTurningOn()=true
08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isTurningOff()=false
08-16 12:11:54.722  4027  4027 V BluetoothAdapterState: isTurningOn()=true
08-16 12:11:54.723  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false,
08-16 12:11:54.723  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:54.725  4027  4027 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:54.725  4027  4027 V BluetoothAdapterState: isTurningOn()=true
08-16 12:11:54.725  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:54.725  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:54.726  4027  4027 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:11:54.726  4027  4027 V BluetoothAdapterState: isTurningOn()=true
08-16 12:11:54.726  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:54.726  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:54.726  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 12:11:54.726  4027  4186 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:11:54.727  4027  4186 D BluetoothAdapterProperties: State =  11
08-16 12:11:54.728  4027  4190 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:11:54.728  4027  4190 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:11:54.728  4027  4186 D BluetoothAdapterProperties: Setting state to 12
,08-16 12:11:54.728  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:11:54.729  1362  2081 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:11:54.730  4027  4186 I BluetoothAdapterState: Entering OnState
,08-16 12:11:54.730  3947  3958 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:11:54.732   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:11:54.732   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:11:54.732  3947  3957 D BluetoothMap: onBluetoothStateChange: up=true
08-16 12:11:54.733  1362  2084 D BluetoothPan: onBluetoothStateChange on: true
,08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:54.733  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:54.735  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:54.735  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:11:54.736  1362  1362 D PanProfile: Bluetooth service connected
08-16 12:11:54.736  1362  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 12:11:54.737  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-16 12:11:54.737  1362  1362 D HidProfile: Bluetooth service connected
08-16 12:11:54.738  1362  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:11:54.738   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:11:54.738   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:54.740  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:11:54.741  4027  4027 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 12:11:54.742  4027  4027 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 12:11:54.742  1983  2007 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:11:54.742  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:54.743  1362  2084 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:11:54.748  1362  1362 D BluetoothMap: Proxy object connected
,08-16 12:11:54.749  3947  3958 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:54.750  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:54.743  4027  4027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:11:54.753  1362  1362 D MapProfile: Bluetooth service connected
,08-16 12:11:54.753  1362  1362 D BluetoothMap: getConnectedDevices()
08-16 12:11:54.753  1362  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:11:54.756  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:11:54.757  3947  3957 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:11:54.757  4027  4027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:11:54.759   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 12:11:54.760  4027  4027 D ObexServerSockets: Succeed to create listening sockets 
08-16 12:11:54.760  4027  4027 D ObexServerSockets0: startAccept()
08-16 12:11:54.760  4027  4027 D ObexServerSockets0: prepareForNewConnect()
08-16 12:11:54.762  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:54.763  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:54.765  3947  3947 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 12:11:54.766  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:54.766  4027  4027 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 12:11:54.766  4027  4027 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 12:11:54.768   875   875 D BluetoothA2dp: Proxy object connected
08-16 12:11:54.768  1362  1362 D BluetoothA2dp: Proxy object connected
08-16 12:11:54.768  4027  4027 D BluetoothMapService: onReceive
08-16 12:11:54.768  4027  4027 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:11:54.768  4027  4027 D BluetoothMapService: STATE_ON
08-16 12:11:54.769  4027  4212 D ObexServerSockets0: Accepting socket connection...
08-16 12:11:54.770  4027  4213 D ObexServerSockets0: Accepting socket connection...
,08-16 12:11:54.771  3947  3947 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 12:11:54.777  3947  3947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:11:54.779  3947  3947 D BluetoothA2dp: Proxy object connected
,08-16 12:11:54.783  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:11:54.788  3947  3947 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:11:54.789  3947  3947 D BluetoothPbap: Proxy object connected
,08-16 12:11:54.790  3947  3947 D PbapServerProfile: Bluetooth service connected
,08-16 12:11:54.791  1362  1362 D BluetoothPbap: Proxy object connected
,08-16 12:11:54.791  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-16 12:11:54.798  4027  4027 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 12:11:54.798  4027  4027 D ObexServerSockets0: prepareForNewConnect()
08-16 12:11:54.799  4027  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:11:54.825  4027  4221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:11:54.827  4027  4221 I BtOppRfcommListener: Accept thread started.
,08-16 12:11:54.833   875   875 D BluetoothHeadset: Proxy object connected
08-16 12:11:54.833   875   875 D BluetoothHeadset: Proxy object connected
,08-16 12:11:54.834  1983  2065 D BluetoothHeadset: Proxy object connected
08-16 12:11:54.834   875   875 D BluetoothHeadset: Proxy object connected
,08-16 12:11:54.834  1362  1374 D BluetoothHeadset: Proxy object connected
,08-16 12:11:54.835  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-16 12:11:54.838  1362  2081 D BluetoothHeadset: Proxy object connected
,08-16 12:11:54.838  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-16 12:11:54.839   875   892 D BluetoothHeadset: Proxy object connected
,08-16 12:11:54.843  1983  2131 D BluetoothHeadset: Proxy object connected
,08-16 12:11:54.875  3947  3957 D BluetoothHeadset: Proxy object connected
08-16 12:11:54.876  3947  3947 D HeadsetProfile: Bluetooth service connected
,08-16 12:11:58.156  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:58.168  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:58.173  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:11:58.237  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 12:11:58.238  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 12:11:58.239  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:11:58.239  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:11:58.299  3591  3591 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 12:11:58.300  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 12:11:58.305  3591  3591 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 12:11:58.338  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:58.338  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:58.340  4027  4186 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 12:11:58.340  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:11:58.340  4027  4186 D BluetoothAdapterProperties: Setting state to 13
,08-16 12:11:58.340  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9332d86 removed from the list
,08-16 12:11:58.341  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:11:58.341  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 12:11:58.341  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:11:58.341  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:58.342  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:11:58.342  4027  4186 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 12:11:58.342  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e085e74 added. We now have 4 listener(s)
08-16 12:11:58.342  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:11:58.346  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:11:58.346  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e085e74 removed from the list
08-16 12:11:58.346  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:11:58.346  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:11:58.346  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:11:58.347  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:11:58.347  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80fbf9d added. We now have 4 listener(s)
08-16 12:11:58.347  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:11:58.349  4027  4186 I BluetoothAdapterState: Entering PendingCommandState
08-16 12:11:58.351  4027  4027 D BluetoothMapService: onReceive
08-16 12:11:58.351  4027  4027 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:11:58.351  4027  4027 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:11:58.351  4027  4027 D BluetoothMapService: MAP Service closeService in
,08-16 12:11:58.352  4027  4027 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 12:11:58.352  4027  4027 D ObexServerSockets0: shutdown(block = true)
08-16 12:11:58.353  4027  4027 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 12:11:58.353  4027  4027 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 12:11:58.353  4027  4212 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 12:11:58.356  4027  4198 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 12:11:58.353  4027  4213 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 12:11:58.360  4027  4027 I BtOppRfcommListener: stopping Accept Thread
08-16 12:11:58.361  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:58.361  4027  4221 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:58.361  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:58.361  4027  4221 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:11:58.362  4027  4190 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:11:58.362  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 12:11:58.363  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:58.363  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:58.368  4027  4027 D HeadsetService: Received stop request...Stopping profile...
08-16 12:11:58.370  3947  3947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 12:11:58.370  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:11:58.370  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:11:58.371  3852  3852 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:11:58.371  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:11:58.373  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:58.373   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:58.374  3947  3957 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:58.374   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:58.374  1983  1999 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:58.375   875   875 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:58.375  1362  2081 D BluetoothHeadset: Proxy object disconnected
08-16 12:11:58.376  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:58.376  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 23
08-16 12:11:58.377  4027  4027 D A2dpService: Received stop request...Stopping profile...
08-16 12:11:58.377  4027  4205 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:11:58.379   875   875 D BluetoothA2dp: Proxy object disconnected
08-16 12:11:58.379  4027  4027 D HidService: Received stop request...Stopping profile...
08-16 12:11:58.380  4027  4027 D HidService: Stopping Bluetooth HidService
08-16 12:11:58.381  4027  4027 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:11:58.381  4027  4027 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:58.381  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:58.381  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:58.381  4027  4027 D HealthService: Received stop request...Stopping profile...
,08-16 12:11:58.384  4027  4027 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:11:58.384  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008,
,08-16 12:11:58.385  4027  4027 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 12:11:58.385  4027  4196 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 12:11:58.385  4027  4196 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:58.385  4027  4196 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,08-16 12:11:58.385  4027  4190 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 12:11:58.385  4027  4027 D PanService: Received stop request...Stopping profile...
,08-16 12:11:58.388  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-16 12:11:58.389  4027  4027 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:11:58.389  4027  4027 D BluetoothMapService: stop()
,08-16 12:11:58.390  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-16 12:11:58.390  1362  1362 D BluetoothInputDevice: Proxy object disconnected,
08-16 12:11:58.390  1362  1362 D HidProfile: Bluetooth service disconnected
,08-16 12:11:58.390  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 12:11:58.390  1362  1362 D PanProfile: Bluetooth service disconnected
,08-16 12:11:58.390  4027  4027 D BluetoothMapAppObserver: deinitObservers()
08-16 12:11:58.390  4027  4027 D BluetoothMapAppObserver: removeReceiver()
,08-16 12:11:58.391  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:11:58.392  4027  4027 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:58.392  4027  4027 V BluetoothAdapterState: isTurningOn()=false,
08-16 12:11:58.392  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:58.392  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:11:58.393  1362  1362 D BluetoothMap: Proxy object disconnected
,08-16 12:11:58.393  1362  1362 D MapProfile: Bluetooth service disconnected
,08-16 12:11:58.395  3947  3947 D DockEventReceiver: finishStartingService: stopping service
08-16 12:11:58.395  3947  3947 D HeadsetProfile: Bluetooth service disconnected
,08-16 12:11:58.396  3947  3947 D BluetoothA2dp: Proxy object disconnected
08-16 12:11:58.396  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 12:11:58.396  4027  4196 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 12:11:58.396  4027  4196 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:58.396  4027  4196 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 12:11:58.396  4027  4027 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:11:58.396  4027  4196 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:11:58.396  4027  4027 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:11:58.396  4027  4196 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:11:58.396  4027  4196 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:11:58.396  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false,
08-16 12:11:58.396  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:58.396  3947  3947 D BluetoothInputDevice: Proxy object disconnected,
08-16 12:11:58.396  3947  3947 D HidProfile: Bluetooth service disconnected
08-16 12:11:58.396  3947  3947 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 12:11:58.397  3947  3947 D PanProfile: Bluetooth service disconnected
08-16 12:11:58.397  4027  4027 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 12:11:58.397  4027  4190 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 12:11:58.397  4027  4027 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:11:58.397  3947  3947 D BluetoothMap: Proxy object disconnected
,08-16 12:11:58.397  3947  3947 D MapProfile: Bluetooth service disconnected
08-16 12:11:58.398  4027  4027 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:11:58.398  4027  4027 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:11:58.398  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:11:58.398  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:58.398  4027  4027 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 12:11:58.399  4027  4190 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 12:11:58.399  4027  4027 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 12:11:58.399  4027  4027 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:58.399  4027  4027 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:58.399  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:58.399  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:58.400  4027  4027 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 12:11:58.400  4027  4027 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 12:11:58.402  3947  3947 D BluetoothPbap: Proxy object disconnected
08-16 12:11:58.402  3947  3947 D PbapServerProfile: Bluetooth service disconnected
,08-16 12:11:58.402  1362  1362 D BluetoothPbap: Proxy object disconnected
08-16 12:11:58.402  1362  1362 D PbapServerProfile: Bluetooth service disconnected
08-16 12:11:58.403  4027  4027 D BluetoothMapService: MAP Service closeService in
,08-16 12:11:58.403  4027  4027 V BluetoothAdapterState: isTurningOff()=true
08-16 12:11:58.403  4027  4027 V BluetoothAdapterState: isTurningOn()=false
08-16 12:11:58.403  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:58.403  4027  4027 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:11:58.404  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 12:11:58.404  4027  4186 D BluetoothAdapterProperties: Setting state to 15
08-16 12:11:58.404  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 12:11:58.404  4027  4186 I BluetoothAdapterState: Entering BleOnState
,08-16 12:11:58.404  4027  4027 D BluetoothMapService: cleanup()
08-16 12:11:58.404  4027  4027 D BluetoothMapService: MAP Service closeService in
,08-16 12:11:58.404  1362  1374 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 12:11:58.405  3947  3958 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:58.406  3947  3957 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 12:11:58.407   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:11:58.407   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:58.407  3947  3958 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:11:58.408  1362  2081 D BluetoothPan: onBluetoothStateChange on: false
,08-16 12:11:58.409  1362  2084 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 12:11:58.410  1362  1380 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:58.410   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:58.410  3947  3957 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:11:58.413   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:11:58.414  1983  2007 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:11:58.414  1362  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:11:58.414  3947  3958 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:11:58.415  1362  2081 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:11:58.416  3947  3957 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:11:58.416  4027  4186 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 12:11:58.416  4027  4186 D BluetoothAdapterProperties: Setting state to 16
08-16 12:11:58.416  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 12:11:58.417  4027  4186 D BluetoothAdapterProperties: onBleDisable
08-16 12:11:58.417  4027  4186 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:11:58.417  4027  4187 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 12:11:58.419  4027  4196 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 12:11:58.419  4027  4196 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:11:58.420  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:58.420  4027  4190 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:11:58.421  3947  3947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 12:11:58.424  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:58.426  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:11:58.426  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:11:58.427  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:11:58.433  3947  3947 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:11:58.624  4027  4190 I bt_hci  : shut_down
,08-16 12:11:58.633  4027  4194 I bt_vendor: low_power_mode_cb
,08-16 12:11:58.633  4027  4194 D bt_hwcfg: hw_epilog_process
,08-16 12:11:58.660  4027  4194 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 12:11:58.660  4027  4194 I bt_vendor: epilog_cb
08-16 12:11:58.660  4027  4194 I bt_hci  : epilog_finished_callback
,08-16 12:11:58.666  4027  4190 I bt_hci_h4: hal_close
,08-16 12:11:58.667  4027  4190 I bt_userial_vendor: device fd = 51 close
,08-16 12:11:58.793  4027  4187 D bt_stack_manager: event_shut_down_stack finished.
,08-16 12:11:58.796  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 12:11:58.802  4027  4027 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 12:11:58.802  4027  4186 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 12:11:58.803  4027  4027 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 12:11:58.804  4027  4027 D BtGatt.GattService: stop()
08-16 12:11:58.804  4027  4027 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 12:11:58.809  4027  4027 V BluetoothAdapterState: isTurningOff()=false
08-16 12:11:58.809  4027  4027 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:11:58.809  4027  4027 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:11:58.810  4027  4027 V BluetoothAdapterState: isBleTurningOff()=true
08-16 12:11:58.811  4027  4186 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 12:11:58.811  4027  4186 D BluetoothAdapterProperties: Setting state to 10
,08-16 12:11:58.811  4027  4186 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 12:11:58.813  4027  4186 I BluetoothAdapterState: Entering OffState
08-16 12:11:58.815   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 12:11:58.841  4027  4027 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 12:11:58.841  4027  4027 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 12:11:58.842  4027  4187 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 12:11:58.854  4027  4187 D bt_stack_manager: event_clean_up_stack finished.
,08-16 12:11:58.854  4027  4027 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 12:11:58.859  4027  4027 I art     : System.exit called, status: 0
,08-16 12:11:58.859  4027  4027 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 12:11:58.920   875  1383 I ActivityManager: Process com.android.bluetooth (pid 4027) has died
,08-16 12:12:03.368  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:03.407   875   892 I ActivityManager: Start proc 4232:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 12:12:03.520  4232  4232 D AdapterServiceConfig: Adding HeadsetService
,08-16 12:12:03.521  4232  4232 D AdapterServiceConfig: Adding A2dpService
,08-16 12:12:03.522  4232  4232 D AdapterServiceConfig: Adding HidService
,08-16 12:12:03.523  4232  4232 D AdapterServiceConfig: Adding HealthService
,08-16 12:12:03.524  4232  4232 D AdapterServiceConfig: Adding PanService
,08-16 12:12:03.524  4232  4232 D AdapterServiceConfig: Adding GattService
,08-16 12:12:03.526  4232  4232 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 12:12:03.554  4232  4232 D BluetoothAdapterState: make() - Creating AdapterState
08-16 12:12:03.554   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cf1ce57:true
,08-16 12:12:03.559  4232  4232 I bt_bluedroid: init
,08-16 12:12:03.559  4232  4244 I BluetoothAdapterState: Entering OffState
,08-16 12:12:03.565  4232  4245 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 12:12:03.566  4232  4245 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 12:12:03.566  4232  4245 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:12:03.566  4232  4245 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 12:12:03.568  4232  4232 I bt_bluedroid: get_profile_interface socket
,08-16 12:12:03.570  4232  4232 I bt_bluedroid: get_profile_interface sdp
,08-16 12:12:03.576  4232  4248 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:12:03.576  4232  4243 I bt_bluedroid: config_hci_snoop_log
,08-16 12:12:03.579  4232  4248 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:12:03.579   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.,
,08-16 12:12:03.588  4232  4244 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 12:12:03.589  4232  4244 D BluetoothAdapterProperties: Setting state to 14
,08-16 12:12:03.589  4232  4244 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 12:12:03.594  4232  4244 D BluetoothBondStateMachine: make
,08-16 12:12:03.599  4232  4249 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 12:12:03.605  4232  4244 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:12:03.608  4232  4232 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 12:12:03.615  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:03.617  4232  4232 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:12:03.619  4232  4232 D BtGatt.GattService: Received start request. Starting profile...
,08-16 12:12:03.619  4232  4232 D BtGatt.GattService: start()
08-16 12:12:03.619  4232  4232 I bt_bluedroid: get_profile_interface gatt
,08-16 12:12:03.621  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:03.622  4232  4232 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:12:03.636  4232  4232 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:12:03.637  4232  4232 V BluetoothAdapterState: isTurningOn()=false
08-16 12:12:03.637  4232  4232 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 12:12:03.637  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:12:03.639  4232  4244 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 12:12:03.639  4232  4244 I bt_bluedroid: enable
,08-16 12:12:03.640  4232  4245 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 12:12:03.641  4232  4245 I bt_hci  : start_up
,08-16 12:12:03.651  4232  4245 I bt_vendor: alloc value 0xb39e6189
,08-16 12:12:03.651  4232  4245 I bt_vendor: init
08-16 12:12:03.651  4232  4245 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 12:12:03.652  4232  4245 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 12:12:03.761  4232  4245 D bt_hci  : start_up starting async portion
,08-16 12:12:03.762  4232  4252 I bt_hci  : event_finish_startup
,08-16 12:12:03.762  4232  4252 I bt_hci_h4: hal_open
08-16 12:12:03.762  4232  4252 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 12:12:03.773  4232  4252 I bt_userial_vendor: device fd = 51 open
,08-16 12:12:03.803  4232  4252 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:12:03.835  4232  4252 D bt_hwcfg: Chipset BCM4354A2
,08-16 12:12:03.835  4232  4252 D bt_hwcfg: Target name = [BCM4354A2]
08-16 12:12:03.836  4232  4252 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 12:12:04.173  1890  2023 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 12:12:04.174  1890  2023 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 12:12:04.226  1487  1487 I ConfigService: onCreate
,08-16 12:12:04.496  4232  4252 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 12:12:04.497  4232  4252 D bt_hwcfg: Settlement delay -- 100 ms
08-16 12:12:04.498  4232  4252 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 12:12:04.614  4232  4252 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:12:04.616  4232  4252 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 12:12:04.645  4232  4252 I bt_hwcfg: vendor lib fwcfg completed
,08-16 12:12:04.646  4232  4252 I bt_vendor: firmware callback
08-16 12:12:04.646  4232  4252 I bt_hci  : firmware_config_callback
,08-16 12:12:04.661  4232  4255 I bt_btu  : btu_task pending for preload complete event
08-16 12:12:04.661  4232  4255 I bt_btu_task: Bluetooth chip preload is complete
,08-16 12:12:04.662  4232  4255 I bt_btu  : btu_task received preload complete event
,08-16 12:12:04.672  4232  4255 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 12:12:04.673  4232  4255 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 12:12:04.673  4232  4255 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 12:12:04.673  4232  4255 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 12:12:04.674  4232  4255 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 12:12:04.674  4232  4255 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 12:12:04.674  4232  4255 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 12:12:04.674  4232  4255 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 12:12:04.675  4232  4255 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 12:12:04.675  4232  4255 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 12:12:04.675  4232  4255 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 12:12:04.675  4232  4255 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 12:12:04.676  4232  4255 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 12:12:04.676  4232  4255 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 12:12:04.676  4232  4255 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:12:04.807  4232  4255 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3963d9d
,08-16 12:12:04.807  4232  4255 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3963d9d 
,08-16 12:12:04.819  4232  4248 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 12:12:04.821  4232  4248 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 12:12:04.822  4232  4248 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:12:04.825  4232  4248 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:12:04.828  4232  4248 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:12:04.829  4232  4248 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 12:12:04.829  4232  4248 D bt_hci  : do_postload posting postload work item
,08-16 12:12:04.830  4232  4252 I bt_hci  : event_postload
,08-16 12:12:04.830  4232  4252 I bt_vendor: sco_config_cb
,08-16 12:12:04.830  4232  4252 I bt_hci  : sco_config_callback postload finished.
,08-16 12:12:04.833  4232  4248 D bt_bte_conf: Device ID record 1 : primary
,08-16 12:12:04.833  4232  4248 D bt_bte_conf:   vendorId            = 000f,
,08-16 12:12:04.834  4232  4248 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 12:12:04.834  4232  4248 D bt_bte_conf:   product             = 1200
,08-16 12:12:04.834  4232  4248 D bt_bte_conf:   version             = 1436
,08-16 12:12:04.835  4232  4248 D bt_bte_conf:   clientExecutableURL = 
08-16 12:12:04.835  4232  4248 D bt_bte_conf:   serviceDescription  = 
,08-16 12:12:04.835  4232  4248 D bt_bte_conf:   documentationURL    = 
08-16 12:12:04.836  4232  4248 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 12:12:04.836  4232  4245 D bt_stack_manager: event_start_up_stack finished
,08-16 12:12:04.838  4232  4244 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 12:12:04.839  4232  4244 D BluetoothAdapterProperties: Setting state to 15
,08-16 12:12:04.839  4232  4244 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 12:12:04.839  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:04.841  4232  4244 I BluetoothAdapterState: Entering BleOnState
08-16 12:12:04.843  4232  4252 I bt_vendor: low_power_mode_cb
,08-16 12:12:04.844  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:04.847  4232  4244 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 12:12:04.847  4232  4244 D BluetoothAdapterProperties: Setting state to 11,
08-16 12:12:04.847  4232  4244 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11,
08-16 12:12:04.854  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:04.855  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:04.862  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:04.863  4232  4232 D HeadsetService: Received start request. Starting profile...,
08-16 12:12:04.867  4232  4232 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-16 12:12:04.868  4232  4232 D HeadsetStateMachine: make,
,08-16 12:12:04.872  4232  4244 I BluetoothAdapterState: Entering PendingCommandState
08-16 12:12:04.875  4232  4232 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:12:04.876  4232  4232 I bt_bluedroid: get_profile_interface handsfree
08-16 12:12:04.876  4232  4248 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 12:12:04.876  4232  4248 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-16 12:12:04.881  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
08-16 12:12:04.881  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:12:04.881  4232  4232 D A2dpService: Received start request. Starting profile...
08-16 12:12:04.882  4232  4232 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 12:12:04.883  4232  4232 I bt_bluedroid: get_profile_interface avrcp
,08-16 12:12:04.888  4232  4232 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 12:12:04.889  4232  4232 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:12:04.889  4232  4232 D A2dpStateMachine: make
,08-16 12:12:04.890  4232  4232 I bt_bluedroid: get_profile_interface a2dp
,08-16 12:12:04.890  4232  4248 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 12:12:04.892  4232  4264 D A2dpStateMachine: Enter Disconnected: -2
,08-16 12:12:04.892  4232  4232 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 12:12:04.893  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:04.894  4232  4232 D HidService: Received start request. Starting profile...
,08-16 12:12:04.894  4232  4232 I bt_bluedroid: get_profile_interface hidhost
,08-16 12:12:04.894  4232  4232 D HidService: setHidService(): set to: null
,08-16 12:12:04.894  4232  4248 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39453e5
,08-16 12:12:04.894  4232  4248 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 12:12:04.894  4232  4232 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 12:12:04.895  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:04.896  4232  4232 D HealthService: Received start request. Starting profile...
,08-16 12:12:04.897  4232  4232 I bt_bluedroid: get_profile_interface health
,08-16 12:12:04.898  4232  4232 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 12:12:04.899  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:04.899  4232  4232 D PanService: Received start request. Starting profile...
,08-16 12:12:04.899  4232  4232 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 12:12:04.900  4232  4232 I bt_bluedroid: get_profile_interface pan
,08-16 12:12:04.900  4232  4248 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 12:12:04.904  4232  4232 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:12:04.905  4232  4232 D BluetoothMapService: Received start request. Starting profile...
,08-16 12:12:04.905  4232  4232 D BluetoothMapService: start()
,08-16 12:12:04.907  4232  4232 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 12:12:04.908  4232  4232 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 12:12:04.908  4232  4232 D BluetoothMapAppObserver: createReceiver()
,08-16 12:12:04.909  4232  4232 D BluetoothMapAppObserver: initObservers()
,08-16 12:12:04.909  4232  4232 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 12:12:04.917  4232  4232 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:12:04.917  4232  4232 V BluetoothAdapterState: isTurningOn()=true
08-16 12:12:04.917  4232  4232 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:12:04.917  4232  4262 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:12:04.917  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:12:04.919  4232  4232 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:12:04.919  4232  4232 V BluetoothAdapterState: isTurningOn()=true
08-16 12:12:04.919  4232  4232 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isTurningOff()=false
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isTurningOn()=true
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isTurningOn()=true
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:12:04.920  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isTurningOff()=false
08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isTurningOn()=true
08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isTurningOff()=false
08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isTurningOn()=true
,08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:12:04.921  4232  4232 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:12:04.922  4232  4244 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-16 12:12:04.922  4232  4244 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:12:04.922  4232  4244 D BluetoothAdapterProperties: State =  11
08-16 12:12:04.922  4232  4244 D BluetoothAdapterProperties: Setting state to 12
08-16 12:12:04.922  4232  4244 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:12:04.923  1362  2084 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 12:12:04.923  4232  4244 I BluetoothAdapterState: Entering OnState
08-16 12:12:04.927  4232  4248 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:12:04.927  3947  3957 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:12:04.927  4232  4248 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:12:04.928  3947  3958 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:12:04.931  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:12:04.933   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:12:04.933   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:12:04.933  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:12:04.933  3947  3957 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:12:04.936  1362  2081 D BluetoothPan: onBluetoothStateChange on: true
,08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:12:04.936  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:12:04.937  4232  4232 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 12:12:04.938  4232  4232 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 12:12:04.939  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:12:04.940  1362  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 12:12:04.942  4232  4232 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:12:04.943  1362  1380 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:12:04.943   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:12:04.944  3947  3958 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:12:04.945  4232  4232 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:12:04.947  4232  4232 D ObexServerSockets: Succeed to create listening sockets 
,08-16 12:12:04.947  4232  4232 D ObexServerSockets0: startAccept()
,08-16 12:12:04.947  4232  4232 D ObexServerSockets0: prepareForNewConnect()
08-16 12:12:04.949   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:12:04.950  1983  2007 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:12:04.950  1362  2084 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:12:04.951  4232  4232 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 12:12:04.951  4232  4232 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 12:12:04.952  3947  3957 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:12:04.954  4232  4269 D ObexServerSockets0: Accepting socket connection...
08-16 12:12:04.954  1362  1362 D BluetoothMap: Proxy object connected
,08-16 12:12:04.954  1362  1362 D MapProfile: Bluetooth service connected
,08-16 12:12:04.954  1362  1362 D BluetoothMap: getConnectedDevices()
08-16 12:12:04.956   875   875 D BluetoothA2dp: Proxy object connected
08-16 12:12:04.956  1362  2081 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:12:04.957  4232  4270 D ObexServerSockets0: Accepting socket connection...
,08-16 12:12:04.957  3947  3947 D BluetoothMap: Proxy object connected
08-16 12:12:04.957  3947  3947 D MapProfile: Bluetooth service connected
08-16 12:12:04.957  3947  3947 D BluetoothMap: getConnectedDevices()
08-16 12:12:04.957  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 12:12:04.957  1362  1362 D PanProfile: Bluetooth service connected
08-16 12:12:04.957  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-16 12:12:04.957  1362  1362 D HidProfile: Bluetooth service connected
08-16 12:12:04.958  3947  3957 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:12:04.960  1362  1362 D BluetoothA2dp: Proxy object connected
,08-16 12:12:04.964  3947  3947 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 12:12:04.964  3947  3947 D PanProfile: Bluetooth service connected
,08-16 12:12:04.964  3947  3947 D BluetoothA2dp: Proxy object connected
08-16 12:12:04.965   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 12:12:04.966  4232  4232 D BluetoothMapService: onReceive
08-16 12:12:04.966  4232  4232 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:12:04.966  4232  4232 D BluetoothMapService: STATE_ON
,08-16 12:12:04.969  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:04.970  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:12:04.970  3947  3947 D BluetoothInputDevice: Proxy object connected
08-16 12:12:04.970  3947  3947 D HidProfile: Bluetooth service connected
,08-16 12:12:04.976  3947  3947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:12:04.983  3947  3947 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:12:04.985  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:12:04.996  1362  1362 D BluetoothPbap: Proxy object connected
,08-16 12:12:04.996  3947  3947 D BluetoothPbap: Proxy object connected
08-16 12:12:04.996  3947  3947 D PbapServerProfile: Bluetooth service connected
08-16 12:12:04.996  1362  1362 D PbapServerProfile: Bluetooth service connected
08-16 12:12:04.997  4232  4232 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 12:12:04.997  4232  4232 D ObexServerSockets0: prepareForNewConnect()
,08-16 12:12:05.006  4232  4277 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:12:05.023  4232  4281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:12:05.025  4232  4281 I BtOppRfcommListener: Accept thread started.
,08-16 12:12:05.030   875   875 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.030  3947  4271 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.030   875   875 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.030  3947  3947 D HeadsetProfile: Bluetooth service connected
,08-16 12:12:05.031  1983  2065 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.031   875   875 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.032  1362  2081 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.032  1362  1362 D HeadsetProfile: Bluetooth service connected
08-16 12:12:05.033   875   892 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.033   875   892 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.044  1362  2084 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.044  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-16 12:12:05.044   875   892 D BluetoothHeadset: Proxy object connected
,08-16 12:12:05.051  1983  2131 D BluetoothHeadset: Proxy object connected
,08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:12:08.385  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:12:08.392  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:12:08.393  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:12:08.393  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80fbf9d removed from the list
08-16 12:12:08.394  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:12:08.394  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:12:08.394  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:12:08.397  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:12:08.397  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b849c12 added. We now have 4 listener(s)
08-16 12:12:08.397  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:12:08.401   875  1917 D WifiService: setWifiEnabled: false pid=3852, uid=10000
08-16 12:12:08.402   875  1917 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:12:09.317  1487  1487 I ConfigService: onDestroy
,08-16 12:12:13.413  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:12:13.414   875  2015 D WifiService: setWifiEnabled: true pid=3852, uid=10000
08-16 12:12:13.415   875  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:12:13.427   875  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:12:13.446  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:12:13.456  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:12:13.459   875  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-16 12:12:13.460   875  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 12:12:13.461   875  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 12:12:13.462   875  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 12:12:13.462   875  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 12:12:13.462   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 12:12:13.463   875  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:12:13.463  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:12:13.465  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:12:13.478   371   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 12:12:13.479   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 12:12:13.479   371   873 D CommandListener: Setting iface cfg
08-16 12:12:13.480   875  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 12:12:13.480   875  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 12:12:13.533   875  1317 E native  : do suspend true
,08-16 12:12:13.546   875  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 12:12:13.547   875  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 12:12:13.559   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:12:14.962   875  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 12:12:15.107   875  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.25 rxSuccessRate=9.19 delta 1000 -> 994
,08-16 12:12:15.109   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 12:12:15.109   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:12:15.132   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 12:12:15.196   875  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 12:12:15.202  1424  1424 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 12:12:15.667  1424  1424 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 12:12:15.718  1424  1424 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 12:12:15.719  1424  1424 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 12:12:15.723   875  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:12:15.738   875  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:12:15.739   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:12:15.739   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 12:12:15.760   875  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:12:15.774   371   873 D CommandListener: Setting iface cfg
,08-16 12:12:15.776   875  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 12:12:15.785   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 12:12:15.803   875  4290 D DhcpClient: Receive thread started
,08-16 12:12:15.898   875  1317 E native  : do suspend false
,08-16 12:12:15.923   875  2083 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 12:12:15.936   875  4290 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172770, domain null
,08-16 12:12:15.937   875  2083 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172770 seconds
,08-16 12:12:15.943   875  2083 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 12:12:15.956   875  4290 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 12:12:15.957   875  2083 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 12:12:15.964   371   873 D CommandListener: Setting iface cfg
,08-16 12:12:15.975   875  2083 D DhcpClient: Scheduling renewal in 86399s
,08-16 12:12:15.980   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 12:12:15.981   875  1317 E native  : do suspend true
,08-16 12:12:15.995   875  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 12:12:15.996   875  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 12:12:15.997   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 12:12:16.000   875  1321 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 12:12:16.006   875  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 12:12:16.046   875  1321 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 12:12:16.046   875  1321 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 12:12:16.050   875  1321 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 12:12:16.054   875  1321 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 12:12:16.058   875  1321 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 12:12:16.095   875  1321 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 12:12:16.103   875  1321 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 12:12:16.103   875  1321 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 12:12:16.103   875  1321 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-16 12:12:16.103   875  1321 D ConnectivityService:    accepting network in place of null
08-16 12:12:16.104   875  1321 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:12:16.104   875  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 12:12:16.106   875  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:12:16.117   875  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222321, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 12:12:16.149   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:12:16.189   875  4288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:817::200e
,08-16 12:12:16.213   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:12:16.219   875  1321 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 12:12:16.219   875  1321 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:12:16.221   875  1321 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 12:12:16.223   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:12:16.243  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:12:16.247  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:12:16.253  3852  3852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:12:16.256  3852  3852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:12:16.256   875  4288 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:12:16 GMT], X-Android-Received-Millis=[1471342336256], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471342336231]}
,08-16 12:12:16.257   875  1321 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 12:12:16.258   875  1321 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 12:12:16.258   875  1321 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 12:12:16.259   875  1321 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 12:12:16.264  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:12:16.270  1691  1691 D SystemUpdateService: onCreate
,08-16 12:12:16.275  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:12:16.294  1691  4300 I SystemUpdateService: active receiver: enabled
,08-16 12:12:16.304  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 12:12:16.309  1691  2521 I iu.UploadsManager: num queued entries: 0
,08-16 12:12:16.309  1691  2521 I iu.UploadsManager: num updated entries: 0
,08-16 12:12:16.310  1691  2521 I iu.SyncManager: NEXT; no task
,08-16 12:12:16.311  1691  4300 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:12:16.314  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:12:16.315  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:12:16.323  1691  4300 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 12:12:16.323  1691  4300 I SystemUpdateService: now status is 0 (complete)
08-16 12:12:16.323  1691  4300 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 12:12:16.323  1691  4300 I SystemUpdateService: file has been verified
,08-16 12:12:16.323  1691  4300 I SystemUpdateService: OTA package size = 12249756
,08-16 12:12:16.326  4042  4042 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:12:16.333  1691  4303 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 12:12:16.333  1691  4303 W BaseAppContext: Using Auth Proxy for data requests.
08-16 12:12:16.336  1691  4303 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 12:12:16.341  4042  4042 D SprintDMHelper: simOperator: 
08-16 12:12:16.341  4042  4042 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:12:16.347  1691  4300 I SystemUpdateService: showing system update notification
,08-16 12:12:16.393  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:12:16.395  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:12:16.453  1691  1691 D SystemUpdateService: onDestroy
,08-16 12:12:16.463  3998  4305 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 12:12:16.488  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 12:12:16.488  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 12:12:16.488  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:12:16.489  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:12:16.511  1691  4303 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-16 12:12:17.220   875  1321 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:12:18.439  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:12:18.446  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:12:18.447  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:12:18.447  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b849c12 removed from the list
08-16 12:12:18.448  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:12:18.448  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:12:18.448  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:12:23.461  3852  4311 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 12:12:23.461  3852  4311 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 12:12:24.111   875  1321 D ConnectivityService: handlePromptUnvalidated 102
,08-16 12:12:26.472  3852  4312 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-16 12:12:26.473  3852  4312 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:12:26.473  3852  4311 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 12:12:26.474  3852  4311 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:12:26.474  3852  4312 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:26.474  3852  4311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:26.476  3852  4312 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:26.476  3852  4311 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
,08-16 12:12:26.481  3852  4311 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 12:12:26.481  3852  4314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: IncomingSocketThread/Sender)
08-16 12:12:26.481  3852  4312 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 12:12:26.486  3852  4315 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: OutgoingSocketThread/Sender)
,08-16 12:12:26.490  3852  4316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: OutgoingSocketThread/Receiver)
08-16 12:12:26.491  3852  4316 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: OutgoingSocketThread/Receiver)
,08-16 12:12:26.491  3852  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: IncomingSocketThread/Receiver)
08-16 12:12:26.491  3852  4316 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 12:12:26.492  3852  4316 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 12:12:26.493  3852  4317 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: IncomingSocketThread/Receiver)
08-16 12:12:26.493  3852  4317 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 12:12:26.493  3852  4317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 12:12:34.471  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 12:12:34.473  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 12:12:34.482  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bc66194 Bundle[{}]
,08-16 12:12:34.485  3852  3901 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 12:12:34.487  3852  3901 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 12:12:34.488  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 12:12:34.489  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 12:12:34.490  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 12:12:34.491  3852  3901 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 12:12:43.777  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:12:43.781  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:12:43.796  3665  4320 V GoogleAuthProtoRequest: [305] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 12:12:43.830  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 12:12:43.830  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 12:12:43.831  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:12:43.831  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: [305] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: [305] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 12:12:43.854  3665  4320 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 12:12:44.510  3852  3901 I System.out: Running OutgoingSocketThread
,08-16 12:12:44.515  3852  4321 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 12:12:44.515  3852  4321 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 12:12:46.280  3239  4322 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 12:12:46.303  3239  4323 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 12:12:46.369  1487  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 12:12:46.369  1487  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:12:46.369  1487  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:12:46.370  1487  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:12:46.436  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 12:12:46.436  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:12:46.436  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:12:46.437  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:12:46.460  3239  4323 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:12:46.461  3239  4322 E BooksSync: Soft error
08-16 12:12:46.461  3239  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:12:46.461  3239  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 12:12:46.461  3239  4322 E BooksSync: Sync error
08-16 12:12:46.461  3239  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:12:46.461  3239  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 12:12:46.461  3239  4322 I BooksSync: Finished books sync
,08-16 12:12:46.471   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 252248, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 12:12:47.524  3852  4324 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 12:12:47.524  3852  4324 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:12:47.525  3852  4324 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:47.525  3852  4321 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 12:12:47.526  3852  4321 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 12:12:47.526  3852  4321 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:47.526  3852  4324 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:47.528  3852  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: IncomingSocketThread/Sender)
,08-16 12:12:47.529  3852  4321 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 12:12:47.531  3852  4321 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 12:12:47.532  3852  4324 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 12:12:47.538  3852  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: OutgoingSocketThread/Sender)
,08-16 12:12:47.541  3852  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: IncomingSocketThread/Receiver)
,08-16 12:12:47.543  3852  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: OutgoingSocketThread/Receiver)
,08-16 12:12:47.543  3852  4329 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: IncomingSocketThread/Receiver)
,08-16 12:12:47.544  3852  4329 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-16 12:12:47.544  3852  4329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-16 12:12:47.544  3852  4328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: OutgoingSocketThread/Receiver)
08-16 12:12:47.545  3852  4328 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-16 12:12:47.545  3852  4328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 12:12:55.527  3852  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 457)
,08-16 12:12:55.530  3852  3901 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 12:12:55.531  3852  3901 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 458)
,08-16 12:13:00.544  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:13:00.544  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f01fe3 added. We now have 3 listener(s)
,08-16 12:13:00.555  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:13:00.555  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:13:00.556  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:13:00.557  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:13:00.558  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86ede0 added. We now have 4 listener(s)
08-16 12:13:00.559  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:13:00.561  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:13:00.568  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:13:00.583  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:13:00.590  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:13:00.590  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:13:00.591  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:13:00.592  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:13:00.592  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:13:00.592  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:00.593  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:00.593  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-16 12:13:00.593  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:13:00.593  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f01fe3 removed from the list
08-16 12:13:00.594  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:00.594  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86ede0 removed from the list
,08-16 12:13:00.597  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:13:00.603  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:13:00.604  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:13:00.604  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:00.605  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:00.605  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:00.608  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:13:00.608  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:13:00.608  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:00.609  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86ede0 not in the list,
08-16 12:13:00.609  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:00.609  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:00.612  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:13:00.612  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:13:00.612  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:00.613  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a86ede0 not in the list
,08-16 12:13:00.613  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:00.613  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:00.614  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:00.614  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f01fe3 not in the list,
08-16 12:13:00.616  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-16 12:13:00.616  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80c675e added. We now have 3 listener(s)
,08-16 12:13:00.622  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-16 12:13:00.623  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:13:00.623  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:13:00.623  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:13:00.624  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57ad73f added. We now have 4 listener(s)
08-16 12:13:00.624  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:13:00.625  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:13:00.632  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:13:00.639  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:13:00.642  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:13:00.642  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:13:00.643  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 12:13:00.643  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:13:00.643  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 12:13:00.643  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:13:00.643  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:13:00.647  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:13:00.650  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 12:13:00.651  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:13:00.660  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:13:00.660  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:13:00.662  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:13:00.662  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:13:00.669  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 12:13:00.670  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 12:13:00.670  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 12:13:00.671  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:13:00.675  4232  4260 D BtGatt.GattService: registerClient() - UUID=1b29983f-9926-4a6a-b616-fd51cf15380c
,08-16 12:13:00.677  4232  4248 D BtGatt.GattService: onClientRegistered() - UUID=1b29983f-9926-4a6a-b616-fd51cf15380c, clientIf=5
,08-16 12:13:00.679  3852  3966 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:13:00.681  4232  4272 D BtGatt.GattService: start scan with filters
,08-16 12:13:00.687  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:13:00.687  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:13:00.687  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:13:00.687  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 12:13:00.688  4232  4251 D BtGatt.ScanManager: handling starting scan
,08-16 12:13:00.691  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:13:00.691  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 12:13:00.691  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:13:00.692  4232  4251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1383ee8
,08-16 12:13:00.693  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:13:00.696  3852  3901 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 12:13:00.696  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 12:13:00.696  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:13:00.696  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:00.696  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 12:13:00.696  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:13:00.696  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:13:00.696  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:13:00.696  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:13:00.697  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:13:00.697  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 12:13:00.698  3852  3901 D BluetoothAdapter: STATE_ON
08-16 12:13:00.699  4232  4260 D BtGatt.GattService: stopScan() - queue size =1
08-16 12:13:00.700  4232  4272 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:13:00.700  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:13:00.700  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:13:00.701  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 12:13:00.701  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:13:00.701  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:13:00.702  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-16 12:13:00.703  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:13:00.703  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:13:00.703  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:13:00.703  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:13:00.705  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:13:00.706  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:13:00.706  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:13:00.707  4232  4248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 12:13:00.707  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:00.709  4232  4251 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 12:13:00.722  4232  4248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 12:13:00.723  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:00.724  4232  4251 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:13:00.724  4232  4251 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 12:13:00.747  4232  4248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 12:13:00.747  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:00.764  4232  4248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 12:13:00.764  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:00.787  4232  4248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 12:13:00.787  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:00.788  4232  4251 D BtGatt.ScanManager: stopping BLe Batch
,08-16 12:13:00.805  4232  4248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:13:00.806  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:00.806  4232  4251 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:13:00.825  4232  4248 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 12:13:00.826  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:01.013   875  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267217, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 12:13:01.207  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:13:01.208  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:13:01.208  3852  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:13:03.706  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:13:03.706  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:13:03.706  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:13:03.707  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:03.707  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:13:03.707  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:13:03.708  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:13:03.708  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80c675e removed from the list
08-16 12:13:03.709  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:13:03.709  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57ad73f removed from the list
,08-16 12:13:03.709  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:13:03.710  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:03.711  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:13:03.712  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:03.715  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:13:03.715  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:03.715  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:03.716  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57ad73f not in the list
,08-16 12:13:03.716  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:03.716  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:03.720  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:03.720  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:13:03.720  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:13:03.721  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57ad73f not in the list
08-16 12:13:03.721  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:03.721  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:03.722  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:03.723  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80c675e not in the list
08-16 12:13:03.724  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:13:03.725  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1898f8 added. We now have 3 listener(s)
,08-16 12:13:03.730  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:13:03.730  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:13:03.730  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:13:03.730  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:13:03.731  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce4e1d1 added. We now have 4 listener(s)
08-16 12:13:03.731  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:13:03.732  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:13:03.737  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:13:03.746  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:13:03.750  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:13:03.750  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:13:03.751  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 12:13:03.752  3852  3901 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 12:13:03.753  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-16 12:13:03.753  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 12:13:03.753  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-16 12:13:03.754  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 12:13:03.754  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:13:03.754  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:13:03.755  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 12:13:03.756  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 12:13:03.757  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-16 12:13:03.758  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 12:13:03.758  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 12:13:03.758  3852  4330 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:13:03.758  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:13:03.758  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:13:03.759  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:13:03.759  3852  3852 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 12:13:03.761  3852  4330 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-16 12:13:03.766  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:13:03.766  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:13:03.772  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:13:03.773  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:13:03.773  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:13:03.776  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 12:13:03.776  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:13:03.777  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-16 12:13:03.778  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 12:13:03.778  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 12:13:03.778  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-16 12:13:03.780  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:13:03.784  4232  4242 D BtGatt.GattService: registerClient() - UUID=11fda9d1-9abf-4516-86c2-3fd01e323b71
,08-16 12:13:03.785  4232  4248 D BtGatt.GattService: onClientRegistered() - UUID=11fda9d1-9abf-4516-86c2-3fd01e323b71, clientIf=5
08-16 12:13:03.785  3852  3863 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 12:13:03.789  4232  4250 D BtGatt.AdvertiseManager: message : 0
,08-16 12:13:03.793  4232  4250 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 12:13:03.806  4232  4248 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 12:13:03.816  4232  4248 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 12:13:03.817  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 12:13:03.818  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:13:03.824  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:13:03.826  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 12:13:03.827  3852  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 12:13:03.827  3852  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-16 12:13:03.827  3852  3852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 12:13:03.827  3852  3852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-16 12:13:03.828  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 12:13:03.830  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 12:13:03.833  3852  3852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-16 12:13:03.833  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 12:13:04.334  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-16 12:13:04.334  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 12:13:04.335  3852  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:13:06.486   875  4289 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 12:13:06.831  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:13:06.832  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-16 12:13:06.832  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 12:13:06.833  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 12:13:06.833  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 12:13:06.834  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 12:13:06.835  3852  4330 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 12:13:06.836  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 12:13:06.836  3852  3901 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 12:13:06.835  3852  4330 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-16 12:13:06.836  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:13:06.837  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:13:06.836  3852  3852 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-16 12:13:06.837  3852  4330 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 12:13:06.837  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:13:06.838  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:13:06.838  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 12:13:06.841  3852  3901 D BluetoothAdapter: STATE_ON
08-16 12:13:06.841  3852  3901 D BluetoothLeScanner: could not find callback wrapper
08-16 12:13:06.841  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:13:06.842  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-16 12:13:06.845  4232  4250 D BtGatt.AdvertiseManager: message : 1
08-16 12:13:06.847  4232  4250 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 12:13:06.855  4232  4248 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-16 12:13:06.856  4232  4248 D BtGatt.GattService: Client app is not null!
08-16 12:13:06.857  4232  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:13:06.858  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:13:06.858  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-16 12:13:06.858  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 12:13:06.858  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-16 12:13:06.858  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-16 12:13:06.860  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:13:06.860  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:13:06.861  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 12:13:06.861  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:13:06.864  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:06.864  3852  3852 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 12:13:06.864  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:13:06.864  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:13:06.864  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:13:06.864  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:13:06.864  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1898f8 removed from the list
,08-16 12:13:06.864  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:06.864  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce4e1d1 removed from the list
08-16 12:13:06.864  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:13:06.864  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:13:06.864  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:13:06.864  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:06.865  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:06.865  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:06.866  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:13:06.866  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:06.866  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:06.866  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce4e1d1 not in the list
08-16 12:13:06.866  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:06.866  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:06.867  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:06.867  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:13:06.867  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:13:06.867  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce4e1d1 not in the list
08-16 12:13:06.867  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:06.868  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:06.868  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:06.868  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1898f8 not in the list
08-16 12:13:06.869  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:13:06.869  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f282dc2 added. We now have 3 listener(s)
,08-16 12:13:06.870  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:13:06.871  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:13:06.871  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:13:06.871  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:13:06.871  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818c7d3 added. We now have 4 listener(s)
08-16 12:13:06.871  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:13:06.871  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:13:06.879  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:13:06.883  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:13:06.886  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:13:06.886  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:13:06.886  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:13:06.886  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:13:06.887  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:13:06.887  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:13:06.887  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:13:06.890  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:13:06.891  3852  3901 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:13:06.891  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:13:06.892  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:13:06.901  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:13:06.901  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:13:06.902  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:13:06.905  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 12:13:06.905  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 12:13:06.905  3852  3901 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 12:13:06.906  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:13:06.910  4232  4273 D BtGatt.GattService: registerClient() - UUID=b805d7cf-9b4e-43c6-991d-3307849e51a5
,08-16 12:13:06.910  4232  4248 D BtGatt.GattService: onClientRegistered() - UUID=b805d7cf-9b4e-43c6-991d-3307849e51a5, clientIf=5
08-16 12:13:06.911  3852  3863 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:13:06.912  4232  4243 D BtGatt.GattService: start scan with filters
,08-16 12:13:06.916  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:13:06.916  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 12:13:06.917  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:13:06.917  4232  4251 D BtGatt.ScanManager: handling starting scan
,08-16 12:13:06.917  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 12:13:06.927  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:13:06.928  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:13:06.928  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:13:06.929  4232  4248 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 12:13:06.929  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:06.929  4232  4251 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 12:13:06.935  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:13:06.941  4232  4248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 12:13:06.941  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:06.941  4232  4251 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:13:06.942  4232  4251 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 12:13:06.967  4232  4248 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 12:13:06.967  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:06.984  4232  4248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 12:13:06.984  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:13:07.366  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:13:07.428  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 12:13:07.429  3852  3852 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:13:07.429  3852  3852 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:13:08.490  4232  4232 D BtGatt.ScanManager: awakened up at time 274694
,08-16 12:13:08.492  4232  4251 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:13:08.553  4232  4248 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 12:13:08.553  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:08.554  4232  4248 D BtGatt.GattService: current time is 274758837045
,08-16 12:13:08.556  4232  4248 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -89, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -87, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 12:13:08.560  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-16 12:13:08.561  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 12:13:08.562  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 12:13:08.562  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 12:13:08.562  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 12:13:08.563  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 12:13:09.952  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:13:09.953  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:13:09.953  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 12:13:09.953  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:09.954  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 12:13:09.955  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:13:09.955  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:13:09.956  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 12:13:09.956  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 12:13:09.961  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:13:09.962  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 12:13:09.964  3852  3901 D BluetoothAdapter: STATE_ON
,08-16 12:13:09.966  4232  4260 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:13:09.969  4232  4273 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:13:09.973  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:13:09.973  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:13:09.973  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:13:09.974  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:13:09.975  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 12:13:09.979  4232  4232 D BtGatt.ScanManager: awakened up at time 276183
08-16 12:13:09.979  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:13:09.980  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:13:09.981  3852  3901 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:13:09.981  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 12:13:09.984  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:13:09.987  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:13:09.987  3852  3852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:13:09.988  3852  3852 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:13:09.988  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:09.988  4232  4248 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:13:09.988  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:09.988  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:13:09.988  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:09.988  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:13:09.988  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f282dc2 removed from the list
08-16 12:13:09.988  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:09.988  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818c7d3 removed from the list
08-16 12:13:09.989  4232  4251 D BtGatt.ScanManager: stopping BLe Batch
,08-16 12:13:09.989  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:13:09.989  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:09.989  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:09.989  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:09.990  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:13:09.990  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:09.991  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:13:09.991  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818c7d3 not in the list
,08-16 12:13:09.991  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:09.991  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:09.992  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:09.992  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:13:09.993  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:09.993  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@818c7d3 not in the list
08-16 12:13:09.993  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:13:09.993  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:09.993  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:09.993  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f282dc2 not in the list
08-16 12:13:09.994  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:13:09.995  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788c3c added. We now have 3 listener(s)
08-16 12:13:09.996  4232  4248 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:13:09.996  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:09.997  4232  4251 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 12:13:09.997  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:13:09.997  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:13:09.997  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:13:09.997  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:13:09.998  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@762dc5 added. We now have 4 listener(s)
08-16 12:13:09.998  3852  3901 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:13:09.998  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:13:10.001  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:13:10.012  4232  4248 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-16 12:13:10.013  4232  4248 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:13:10.013  4232  4248 D BtGatt.GattService: current time is 276217955146
,08-16 12:13:10.014  4232  4248 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -90, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -95, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-16 12:13:10.014  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:13:10.015  3852  3901 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:13:10.015  4232  4248 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-16 12:13:10.018  3852  3901 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:13:10.018  3852  3901 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:13:10.018  3852  3901 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:13:10.018  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:13:10.018  3852  3901 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:13:10.018  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:13:10.019  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:10.019  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:13:10.019  3852  3901 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:13:10.019  3852  3901 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788c3c removed from the list
08-16 12:13:10.019  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:10.019  3852  3901 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@762dc5 removed from the list
,08-16 12:13:10.021  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:13:10.022  3852  3901 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:13:10.022  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:10.023  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:10.023  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:13:10.025  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:13:10.025  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:13:10.025  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:13:10.025  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@762dc5 not in the list
08-16 12:13:10.025  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:10.026  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:10.026  3852  3852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:13:10.027  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:13:10.027  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:13:10.027  3852  3901 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:13:10.027  3852  3901 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@762dc5 not in the list
08-16 12:13:10.027  3852  3901 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:13:10.027  3852  3901 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:13:10.027  3852  3901 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:13:10.027  3852  3901 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788c3c not in the list
,08-16 12:13:10.489  3852  3852 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:13:15.030  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 12:13:15.031  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 12:13:15.031  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 12:13:15.032  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:13:15.032  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-16 12:13:15.033  3852  3901 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:13:18.479  3239  4332 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 12:13:18.532  3239  4333 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 12:13:18.554  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:13:18.560  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:13:18.607  1487  1498 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 12:13:18.607  1487  1498 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:13:18.607  1487  1498 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:13:18.607  1487  1498 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:13:18.657  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:13:18.662  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:13:18.703  1487  1931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 12:13:18.703  1487  1931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:13:18.703  1487  1931 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:13:18.703  1487  1931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:13:18.726  3239  4333 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:13:18.727  3239  4332 E BooksSync: Soft error
08-16 12:13:18.727  3239  4332 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:13:18.727  3239  4332 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 12:13:18.727  3239  4332 E BooksSync: Sync error
08-16 12:13:18.727  3239  4332 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:13:18.727  3239  4332 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 12:13:18.727  3239  4332 I BooksSync: Finished books sync
,08-16 12:13:18.737   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284640, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,08-16 12:13:22.059  3852  4338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: My test thread name)
,08-16 12:13:24.057  3852  3901 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 467
08-16 12:13:24.058  3852  3901 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 467, name: My test thread name)
,08-16 12:13:24.063  3852  4338 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-16 12:13:24.067  3852  4339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: My test thread name)
,08-16 12:13:24.068  3852  4339 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 468, thread name: My test thread name)
08-16 12:13:24.068  3852  4339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 12:13:24.074  3852  3901 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 12:13:24.084  3852  4340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: My test thread name)
08-16 12:13:24.085  3852  4340 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 472, thread name: My test thread name): Test exception.
,08-16 12:13:24.085  3852  4340 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 472, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 12:13:24.095  3852  3901 I jxcore-log: Total number of executed tests:  82
08-16 12:13:24.095  3852  3901 I jxcore-log: 
08-16 12:13:24.096  3852  3901 I jxcore-log: Number of passed tests:  82
08-16 12:13:24.096  3852  3901 I jxcore-log: 
,08-16 12:13:24.096  3852  3901 I jxcore-log: Number of failed tests:  0
08-16 12:13:24.096  3852  3901 I jxcore-log: 
08-16 12:13:24.097  3852  3901 I jxcore-log: Number of ignored tests:  0
08-16 12:13:24.097  3852  3901 I jxcore-log: 
08-16 12:13:24.099  3852  3901 I jxcore-log: Total duration:  146512
08-16 12:13:24.099  3852  3901 I jxcore-log: 
,08-16 12:13:24.100  3852  3901 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 12:13:24.100  3852  3901 I jxcore-log: 
,08-16 12:13:24.112  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.112  3852  3901 I jxcore-log: 
,08-16 12:13:24.122  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.122  3852  3901 I jxcore-log: 
,08-16 12:13:24.124  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.124  3852  3901 I jxcore-log: 
,08-16 12:13:24.125  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.125  3852  3901 I jxcore-log: 
,08-16 12:13:24.127  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 12:13:24.127  3852  3901 I jxcore-log: 
,08-16 12:13:24.129  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:13:24.129  3852  3901 I jxcore-log: 
,08-16 12:13:24.132  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.132  3852  3901 I jxcore-log: 
08-16 12:13:24.132  3852  3852 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 12:13:24.134  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.134  3852  3901 I jxcore-log: 
,08-16 12:13:24.135  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 12:13:24.135  3852  3901 I jxcore-log: 
,08-16 12:13:24.135  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:13:24.135  3852  3901 I jxcore-log: 
08-16 12:13:24.136  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:13:24.136  3852  3901 I jxcore-log: 
08-16 12:13:24.137  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.137  3852  3901 I jxcore-log: 
08-16 12:13:24.138  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.138  3852  3901 I jxcore-log: 
08-16 12:13:24.139  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.139  3852  3901 I jxcore-log: 
08-16 12:13:24.139  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.139  3852  3901 I jxcore-log: 
,08-16 12:13:24.140  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.140  3852  3901 I jxcore-log: 
08-16 12:13:24.142  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.142  3852  3901 I jxcore-log: 
,08-16 12:13:24.142  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.142  3852  3901 I jxcore-log: 
,08-16 12:13:24.143  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.143  3852  3901 I jxcore-log: 
08-16 12:13:24.144  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.144  3852  3901 I jxcore-log: 
08-16 12:13:24.145  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.145  3852  3901 I jxcore-log: 
,08-16 12:13:24.146  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.146  3852  3901 I jxcore-log: 
08-16 12:13:24.147  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.147  3852  3901 I jxcore-log: 
08-16 12:13:24.147  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.147  3852  3901 I jxcore-log: 
,08-16 12:13:24.148  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.148  3852  3901 I jxcore-log: 
08-16 12:13:24.149  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.149  3852  3901 I jxcore-log: 
,08-16 12:13:24.150  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.150  3852  3901 I jxcore-log: 
08-16 12:13:24.151  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.151  3852  3901 I jxcore-log: 
,08-16 12:13:24.151  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.151  3852  3901 I jxcore-log: 
08-16 12:13:24.152  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.152  3852  3901 I jxcore-log: 
,08-16 12:13:24.153  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.153  3852  3901 I jxcore-log: 
08-16 12:13:24.154  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.154  3852  3901 I jxcore-log: 
,08-16 12:13:24.155  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.155  3852  3901 I jxcore-log: 
08-16 12:13:24.155  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.155  3852  3901 I jxcore-log: 
,08-16 12:13:24.156  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.156  3852  3901 I jxcore-log: 
08-16 12:13:24.157  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.157  3852  3901 I jxcore-log: 
,08-16 12:13:24.158  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:13:24.158  3852  3901 I jxcore-log: 
08-16 12:13:24.158  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.158  3852  3901 I jxcore-log: 
,08-16 12:13:24.160  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:13:24.160  3852  3901 I jxcore-log: 
,08-16 12:13:24.161  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.161  3852  3901 I jxcore-log: 
08-16 12:13:24.161  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.161  3852  3901 I jxcore-log: 
08-16 12:13:24.162  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.162  3852  3901 I jxcore-log: 
,08-16 12:13:24.162  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.162  3852  3901 I jxcore-log: 
08-16 12:13:24.163  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.163  3852  3901 I jxcore-log: 
08-16 12:13:24.163  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:13:24.163  3852  3901 I jxcore-log: 
,08-16 12:13:24.164  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.164  3852  3901 I jxcore-log: 
08-16 12:13:24.164  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 12:13:24.164  3852  3901 I jxcore-log: 
08-16 12:13:24.165  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.165  3852  3901 I jxcore-log: 
,08-16 12:13:24.165  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:13:24.165  3852  3901 I jxcore-log: 
08-16 12:13:24.166  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 12:13:24.166  3852  3901 I jxcore-log: 
08-16 12:13:24.166  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:13:24.166  3852  3901 I jxcore-log: 
08-16 12:13:24.167  3852  3901 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:13:24.167  3852  3901 I jxcore-log: 
,08-16 12:13:24.746  4341  4341 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 12:13:24.750  4341  4341 D AndroidRuntime: CheckJNI is OFF
,08-16 12:13:24.786  4341  4341 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 12:13:24.828  4341  4341 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 12:13:24.848  4341  4341 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 12:13:24.860   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 12:13:24.860   875   888 I ActivityManager: Killing 3852:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 12:13:25.004   875   898 W PackageSettings: Skipping PackageSetting{7b96f95 com.example.hello/10273} due to missing metadata
,08-16 12:13:25.008   875  1980 D GraphicsStats: Buffer count: 2
,08-16 12:13:25.009   875  2017 I WindowState: WIN DEATH: Window{737052a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 12:13:25.009   875  1319 D WifiService: Client connection lost with reason: 4
,08-16 12:13:25.048   875   898 I art     : Starting a blocking GC Explicit
,08-16 12:13:25.058   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 12:13:25.060   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 12:13:25.064   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-16 12:13:25.064   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 12:13:25.064   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.064   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.064   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 12:13:25.064   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 12:13:25.067   875   888 I ActivityManager:   Force finishing activity ActivityRecord{2cf72c3 u0 com.test.thalitest/.MainActivity t2}
,08-16 12:13:25.075   875  3221 W ActivityManager: Spurious death for ProcessRecord{d62c2cb 0:com.test.thalitest/u0a0}, curProc for 3852: null
,08-16 12:13:25.101   875   898 I art     : Explicit concurrent mark sweep GC freed 64636(3MB) AllocSpace objects, 10(216KB) LOS objects, 33% free, 29MB/43MB, paused 739us total 51.199ms
,08-16 12:13:25.131   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 12:13:25.137  4341  4341 I art     : System.exit called, status: 0
08-16 12:13:25.137  4341  4341 I AndroidRuntime: VM exiting with result code 0.
,08-16 12:13:25.190   875   898 I ActivityManager: Start proc 4352:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-16 12:13:25.190   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 12:13:25.229   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 12:13:25.232  4232  4232 D BluetoothMapAppObserver: onReceive
08-16 12:13:25.232  4232  4232 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 12:13:25.235  1845  2241 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 12:13:25.242   875  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:13:25.244  3723  3723 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 12:13:25.249  1890  1890 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 12:13:25.254  1890  4365 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 12:13:25.270  1890  4365 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-16 12:13:25.270  1890  4365 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-16 12:13:25.270  1890  4365 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-16 12:13:25.271  1890  4365 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-16 12:13:25.271  1890  4365 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-16 12:13:25.271  1890  4365 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-16 12:13:25.281   875  1315 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-16 12:13:25.285  1983  1983 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-16 12:13:25.292  1890  4365 I Decoder : createOrResetDecoder
,08-16 12:13:25.293   875  1915 I ActivityManager: Start proc 4368:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 12:13:25.318  1487  1487 I ConfigService: onCreate
,08-16 12:13:25.329  4368  4368 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-16 12:13:25.330   875  1990 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3852 uid 10000
,08-16 12:13:25.331  1890  1890 I Keyboard.Facilitator: onFinishInput()
,08-16 12:13:25.336  1487  4380 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 12:13:25.336  1487  4380 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 12:13:25.336  1487  4380 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-16 12:13:25.340  1487  4380 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-16 12:13:25.342   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 12:13:25.366  1996  2085 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 12:13:25.367   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 12:13:25.368   875   887 E PackageManager: Failed to write settings, restoring backup
08-16 12:13:25.368   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 12:13:25.368   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 12:13:25.368   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 12:13:25.368   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 12:13:25.368   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 12:13:25.368   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.368   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.368   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:13:25.371   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-16 12:13:25.371   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 12:13:25.371   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:13:25.371   875   888 E DropBoxManagerService: 	... 13 more
,08-16 12:13:25.381   875  2016 I ActivityManager: Start proc 4381:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 12:13:25.382  1996  2085 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 12:13:25.382  1996  2085 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1996
08-16 12:13:25.382  1996  2085 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.382  1996  2085 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:13:25.384   875  1917 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 12:13:25.385   875  4387 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:13:25.385   875  4387 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:13:25.385   875  4387 E DropBoxManagerService: 	... 5 more
08-16 12:13:25.388  1996  2085 I Process : Sending signal. PID: 1996 SIG: 9
08-16 12:13:25.395  1890  4365 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 12:13:25.434  1890  4365 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 12:13:25.437  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 12:13:25.437  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 12:13:25.439  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 12:13:25.439  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 12:13:25.439  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 12:13:25.439  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 12:13:25.440  1890  4365 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 12:13:25.440  1890  4365 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-16 12:13:25.440  1890  4365 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 12:13:25.440  1890  4365 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 12:13:25.440  1890  4365 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 12:13:25.440  1890  4365 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 12:13:25.472  4368  4368 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 12:13:25.485   278   278 E lowmemorykiller: Error writing /proc/1996/oom_score_adj; errno=22
,08-16 12:13:25.490   875  1990 D GraphicsStats: Buffer count: 1
,08-16 12:13:25.490   875  1980 I WindowState: WIN DEATH: Window{3d829f2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 12:13:25.508  4368  4396 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.508  4368  4396 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:13:25.510  4368  4400 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.511  4368  4396 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:13:25.529   875   885 I ActivityManager: Start proc 4402:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 12:13:25.530   278   278 E lowmemorykiller: Error opening /proc/1996/oom_score_adj; errno=2
,08-16 12:13:25.533   875  1990 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1996) has died
08-16 12:13:25.534   875  1990 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-16 12:13:25.535   875  1990 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 12:13:25.551   875   888 I ActivityManager: Start proc 4415:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 12:13:25.573  1691  4412 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 12:13:25.575  1691  4412 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 12:13:25.578  4402  4402 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 12:13:25.597  1487  1487 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 12:13:25.599  1487  1487 D AndroidRuntime: Shutting down VM
08-16 12:13:25.600  1487  1487 E AndroidRuntime: FATAL EXCEPTION: main
08-16 12:13:25.600  1487  1487 E AndroidRuntime: Process: com.google.process.gapps, PID: 1487
08-16 12:13:25.600  1487  1487 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 12:13:25.600  1487  1487 E AndroidRuntime: 	... 8 more
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLit,eConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:13:25.603  4415  4415 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:13:25.604   875  4429 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(B,lockGuardOs.java:186)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:13:25.604   875  4429 E DropBoxManagerService: 	... 5 more
08-16 12:13:25.604  1487  1487 I Process : Sending signal. PID: 1487 SIG: 9
08-16 12:13:25.604  4415  4415 D AndroidRuntime: Shutting down VM
08-16 12:13:25.615  4415  4415 E AndroidRuntime: FATAL EXCEPTION: main
08-16 12:13:25.615  4415  4415 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4415
08-16 12:13:25.615  4415  4415 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 12:13:25.615  4415  4415 E AndroidRuntime: 	... 10 more
08-16 12:13:25.619   875  1915 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 12:13:25.620   875  4431 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:13:25.620   875  4431 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:13:25.620   875  4431 E DropBoxManagerService: 	... 5 more
08-16 12:13:25.621  4415  4415 I Process : Sending signal. PID: 4415 SIG: 9
08-16 12:13:25.627  1691  4412 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 12:13:25.627  1691  4412 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-16 12:13:25.641   875  2017 I ActivityManager: Killing 3776:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 12:13:25.650  4368  4396 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-16 12:13:25.657   875  1319 D WifiService: Client connection lost with reason: 4
08-16 12:13:25.662   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
