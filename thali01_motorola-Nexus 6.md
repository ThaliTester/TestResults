#### Test 82642184a744340_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-25 03:21:02.375  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 03:21:02.395  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 03:21:02.401  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 03:21:02.488  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 03:21:02.489  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:21:02.490  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:02.490  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 03:21:02.534  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 03:21:02.535  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 03:21:02.535  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-25 03:21:03.041  3797  3797 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 03:21:03.046  3797  3797 D AndroidRuntime: CheckJNI is OFF
08-25 03:21:03.103  3797  3797 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 03:21:03.158  3797  3797 I Radio-JNI: register_android_hardware_Radio DONE
08-25 03:21:03.186  3797  3797 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 03:21:03.192   873  1386 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 03:21:03.247  1978  2391 W SearchService: Abort, client detached.
08-25 03:21:03.251  3797  3797 D AndroidRuntime: Shutting down VM
08-25 03:21:03.258  1978  1978 I HotwordDetector: Closing mic
08-25 03:21:03.259  1978  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@cc3aacc
08-25 03:21:03.259  1978  2349 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 03:21:03.274   873  1697 I ActivityManager: Start proc 3806:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 03:21:03.320   376  2351 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 03:21:03.321   376  2351 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 03:21:03.325   376  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 03:21:03.329  1978  2348 I MicroRecognitionRnrImpl: Detection finished
08-25 03:21:03.330  1978  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 03:21:03.354  3806  3806 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 03:21:03.373  3806  3806 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 03:21:03.386  3806  3806 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 268-277)
08-25 03:21:03.386  3806  3806 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:21:03.402  3806  3806 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ecdf30f}
08-25 03:21:03.402  3806  3806 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:21:03.403  3806  3806 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 03:21:03.412  3806  3806 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 03:21:03.413  3806  3806 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 03:21:03.427  3806  3806 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-25 03:21:03.436  3806  3806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 03:21:03.436  3806  3806 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 03:21:03.436  3806  3806 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 03:21:03.436  3806  3806 I Adreno  : Build Date                       : 10/20/15
08-25 03:21:03.436  3806  3806 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 03:21:03.436  3806  3806 I Adreno  : Local Branch                     : M14
08-25 03:21:03.436  3806  3806 I Adreno  : Remote Branch                    : 
08-25 03:21:03.436  3806  3806 I Adreno  : Remote Branch                    : 
08-25 03:21:03.436  3806  3806 I Adreno  : Reconstruct Branch               : 
,08-25 03:21:03.499   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77e200c:true
,08-25 03:21:03.542  3806  3806 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 03:21:03.555  3806  3806 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 03:21:03.649  3806  3844 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 03:21:03.675  3806  3831 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 03:21:03.746  3806  3844 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 03:21:03.829   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +578ms
,08-25 03:21:03.843  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-25 03:21:03.886  3806  3806 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3806
,08-25 03:21:04.041  3806  3806 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 03:21:04.094   873  1386 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 03:21:04.136   873  1386 I ActivityManager: Killing 3214:com.google.android.gm/u0a78 (adj 15): empty #18
,08-25 03:21:04.235  3806  3848 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1684272848
,08-25 03:21:04.248  3806  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 03:21:04.248  3806  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 03:21:04.248  3806  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 03:21:04.248  3806  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 03:21:04.248  3806  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 03:21:04.249  3806  3848 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9059892 added. We now have 1 listener(s)
,08-25 03:21:04.253  3806  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 03:21:04.255  3806  3848 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:21:04.256  3806  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:21:04.256  3806  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 03:21:04.260  3806  3848 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34e3f19 added. We now have 1 listener(s)
08-25 03:21:04.260  3806  3848 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:21:04.272   873  1312 D WifiService: New client listening to asynchronous messages
,08-25 03:21:04.273  3806  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:21:04.273  3806  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 03:21:04.273  3806  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 03:21:04.273  3806  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-25 03:21:04.273  3806  3848 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 03:21:04.277  3806  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:21:04.277  3806  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 03:21:04.285  3806  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:04.286  3806  3848 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:21:04.287  3806  3848 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-25 03:21:04.287  3806  3848 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:21:04.287  3806  3848 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 03:21:04.289  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:04.291  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:04.316  3806  3806 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 03:21:05.041  3806  3856 W jxcore-log: Initializing JXcore engine
,08-25 03:21:05.041  3806  3856 W jxcore-log: JXcore engine is ready
,08-25 03:21:05.090  3856  3856 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 03:21:05.093  3856  3856 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12170]" dev="sockfs" ino=12170 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-25 03:21:05.093  3856  3856 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-25 03:21:05.093  3856  3856 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26968]" dev="sockfs" ino=26968 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 03:21:05.108  3806  3856 W jxcore-log: Starting JXcore engine
,08-25 03:21:05.187  3806  3856 W jxcore-log: Platform android
08-25 03:21:05.187  3806  3856 W jxcore-log: 
,08-25 03:21:05.187  3806  3856 W jxcore-log: Process ARCH arm
08-25 03:21:05.187  3806  3856 W jxcore-log: 
,08-25 03:21:05.327   873  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 03:21:05.418  3806  3856 I jxcore-log: JXcore Cordova bridge is ready!
08-25 03:21:05.418  3806  3856 I jxcore-log: 
,08-25 03:21:05.421  3806  3856 W jxcore-log: JXcore engine is started
,08-25 03:21:05.432  3806  3848 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 03:21:05.437  3806  3806 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 03:21:11.107  3614  3863 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:21:11.141  3614  3864 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:21:11.152  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:11.158  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:11.204  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:21:11.204  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:21:11.205  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:21:11.205  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:11.275  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:11.281  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:11.342  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:21:11.342  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:21:11.342  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:11.342  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:11.379  3614  3864 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-25 03:21:11.381  3614  3863 E BooksSync: Soft error
08-25 03:21:11.381  3614  3863 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:21:11.381  3614  3863 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 03:21:11.382  3614  3863 E BooksSync: Sync error
08-25 03:21:11.382  3614  3863 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:21:11.382  3614  3863 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 03:21:11.384  3614  3863 I BooksSync: Finished books sync
,08-25 03:21:11.389   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127877, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:21:12.813   873  1877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:21:19.742  3806  3856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 03:21:19.742  3806  3856 I jxcore-log: 
,08-25 03:21:19.745  3806  3856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 03:21:19.745  3806  3856 I jxcore-log: 
,08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:19.753  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:19.757  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:19.760  3806  3856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 03:21:19.760  3806  3856 I jxcore-log: 
,08-25 03:21:19.762  3806  3856 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 03:21:19.762  3806  3856 I jxcore-log: 
,08-25 03:21:20.117  3806  3856 I jxcore-log: Running unit tests
08-25 03:21:20.117  3806  3856 I jxcore-log: 
08-25 03:21:20.118  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:21:20.118  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dbfb00 added. We now have 2 listener(s)
,08-25 03:21:20.119  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:21:20.119  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:21:20.119  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:21:20.120  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:21:20.120  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e240f39 added. We now have 2 listener(s)
08-25 03:21:20.120  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:21:20.120  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:21:20.122  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:20.142  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:20.146  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:20.146  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:21:20.147  3806  3856 D ExecuteNativeTests: Running unit tests,
,08-25 03:21:20.162  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:20.164  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:20.242  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 03:21:20.243  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf added. We now have 3 listener(s)
08-25 03:21:20.244  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:21:20.244  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 03:21:20.244  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:21:20.244  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:21:20.244  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c added. We now have 3 listener(s)
08-25 03:21:20.244  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:21:20.246  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:21:20.253  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:20.265  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:20.270  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:20.270  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:21:20.272  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 03:21:20.273  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 03:21:20.273  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 03:21:20.273  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 03:21:20.273  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:20.274  3806  3856 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 03:21:20.274  3806  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-25 03:21:20.274  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 03:21:20.274  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 03:21:20.274  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 03:21:20.274  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 03:21:20.275  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:20.276  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:20.276  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:20.276  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:20.276  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:20.276  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:21:20.276  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 03:21:20.276  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf removed from the list
08-25 03:21:20.276  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:20.277  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c removed from the list
08-25 03:21:20.280  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:20.280  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:20.280  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.281  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:20.281  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.281  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:20.282  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:20.282  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:20.282  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:20.284  3806  3856 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 03:21:20.284  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:20.284  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:20.284  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:20.285  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:20.285  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:20.285  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.285  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:20.285  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:20.285  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:20.285  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:20.285  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:20.285  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.285  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:20.285  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.287  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:20.288  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:20.288  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:20.288  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-25 03:21:20.294  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 03:21:20.295  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 03:21:20.296  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 03:21:20.297  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 03:21:20.297  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 03:21:20.297  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-25 03:21:20.297  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 03:21:20.297  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 03:21:20.297  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:20.297  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:20.297  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:20.298  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:20.298  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:20.298  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:20.298  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:20.298  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:20.298  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:20.298  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:20.298  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:20.298  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.298  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:20.299  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:20.300  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:20.300  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:20.300  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:20.300  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:20.301  3806  3856 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 03:21:20.304  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:20.313  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:20.315  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:20.315  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:21:20.315  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:21:20.315  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:21:20.315  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:21:20.315  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:21:20.315  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:21:20.318  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:20.319  3806  3856 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:21:20.319  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:21:20.320  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:20.324  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:21:20.326  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:21:20.326  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:21:20.330  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 03:21:20.333  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 03:21:20.333  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:21:20.334  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:21:20.334  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:21:20.335  3806  3856 D BluetoothAdapter: STATE_ON
,08-25 03:21:20.341  2683  3436 D BtGatt.GattService: registerClient() - UUID=75263fb7-a9f3-44b3-aaf6-e91933a5ce09
,08-25 03:21:20.341  2683  2704 D BtGatt.GattService: onClientRegistered() - UUID=75263fb7-a9f3-44b3-aaf6-e91933a5ce09, clientIf=5
,08-25 03:21:20.342  3806  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 03:21:20.344  2683  2696 D BtGatt.GattService: start scan with filters
,08-25 03:21:20.347  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 03:21:20.347  2683  2709 D BtGatt.ScanManager: handling starting scan
08-25 03:21:20.348  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 03:21:20.348  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 03:21:20.348  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 03:21:20.349  2683  2709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:21:20.353  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:21:20.354  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:21:20.354  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:21:20.357  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:21:20.358  2683  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 03:21:20.358  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:20.359  2683  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 03:21:20.363  3806  3856 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 03:21:20.368  2683  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 03:21:20.368  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:20.369  2683  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:21:20.369  2683  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 03:21:20.382  2683  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 03:21:20.382  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:20.393  2683  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 03:21:20.393  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:20.856  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-25 03:21:20.857  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 03:21:20.857  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:21:21.900  2683  2683 D BtGatt.ScanManager: awakened up at time 138791
08-25 03:21:21.902  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:21.943  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-25 03:21:21.943  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:21.943  2683  2704 D BtGatt.GattService: current time is 138834899307
,08-25 03:21:21.944  2683  2704 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -90, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -90, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -90, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:21:21.947  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-25 03:21:21.948  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-25 03:21:21.949  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-25 03:21:21.949  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-25 03:21:21.950  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-25 03:21:21.950  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:21:23.449  2683  2683 D BtGatt.ScanManager: awakened up at time 140340
,08-25 03:21:23.451  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:23.515  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-25 03:21:23.515  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:23.516  2683  2704 D BtGatt.GattService: current time is 140407163369
08-25 03:21:23.516  2683  2704 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -94, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,08-25 03:21:23.517  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-25 03:21:23.518  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-25 03:21:23.785  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:23.802  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:23.806  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:23.877  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 03:21:23.878  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:21:23.878  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:21:23.878  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:23.930  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 03:21:23.931  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 03:21:23.933  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-25 03:21:25.020  2683  2683 D BtGatt.ScanManager: awakened up at time 141911
,08-25 03:21:25.022  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:25.065  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-25 03:21:25.065  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:25.066  2683  2704 D BtGatt.GattService: current time is 141957167579
,08-25 03:21:25.067  2683  2704 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -97, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-25 03:21:25.068  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-25 03:21:25.068  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:21:25.069  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-25 03:21:25.070  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 03:21:25.071  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-25 03:21:25.372  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:25.373  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:21:25.373  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:21:25.374  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:25.374  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-25 03:21:25.374  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 03:21:25.375  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:21:25.376  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:21:25.376  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 03:21:25.380  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:21:25.381  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 03:21:25.384  3806  3856 D BluetoothAdapter: STATE_ON
,08-25 03:21:25.387  2683  3436 D BtGatt.GattService: stopScan() - queue size =1
,08-25 03:21:25.390  2683  2877 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:21:25.391  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 03:21:25.392  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 03:21:25.393  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 03:21:25.393  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 03:21:25.393  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 03:21:25.398  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:21:25.400  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:21:25.400  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:21:25.401  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:21:25.403  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:21:25.406  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:21:25.406  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:25.407  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:25.407  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:21:25.407  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:21:25.407  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:21:25.407  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:25.408  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:25.408  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:25.409  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:21:25.410  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:25.413  2683  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 03:21:25.413  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:25.414  2683  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:21:25.429  2683  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 03:21:25.429  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:25.429  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:25.440  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 03:21:25.441  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:25.909  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:21:30.413  3806  3856 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 03:21:30.420  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:30.435  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:30.442  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:30.443  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:21:30.444  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:21:30.444  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 03:21:30.444  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:21:30.445  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:21:30.445  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:21:30.453  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:30.460  3806  3856 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 03:21:30.460  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:21:30.461  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:30.475  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:21:30.477  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:21:30.478  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:21:30.489  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:21:30.490  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:21:30.490  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:21:30.492  3806  3856 D BluetoothAdapter: STATE_ON
,08-25 03:21:30.500  2683  3436 D BtGatt.GattService: registerClient() - UUID=0d9c3eac-7fac-44be-a442-57fa2998105e
,08-25 03:21:30.502  2683  2704 D BtGatt.GattService: onClientRegistered() - UUID=0d9c3eac-7fac-44be-a442-57fa2998105e, clientIf=5
,08-25 03:21:30.503  3806  3818 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 03:21:30.504  2683  2694 D BtGatt.GattService: start scan with filters
,08-25 03:21:30.513  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 03:21:30.514  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 03:21:30.514  2683  2709 D BtGatt.ScanManager: handling starting scan
,08-25 03:21:30.514  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:21:30.514  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:21:30.530  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:21:30.531  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:21:30.531  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:21:30.533  2683  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 03:21:30.533  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.533  2683  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 03:21:30.539  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:21:30.541  2683  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 03:21:30.541  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.541  2683  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:21:30.542  2683  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 03:21:30.546  3806  3856 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 03:21:30.551  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:30.551  3806  3856 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 03:21:30.551  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:30.551  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:21:30.551  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:30.551  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-25 03:21:30.552  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 03:21:30.552  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 03:21:30.552  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:21:30.552  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 03:21:30.552  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:21:30.552  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 03:21:30.553  3806  3856 D BluetoothAdapter: STATE_ON
08-25 03:21:30.553  2683  2694 D BtGatt.GattService: stopScan() - queue size =1
08-25 03:21:30.554  2683  2877 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:21:30.555  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:21:30.555  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 03:21:30.555  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 03:21:30.555  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 03:21:30.555  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 03:21:30.556  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:21:30.557  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:21:30.557  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 03:21:30.557  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:21:30.558  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:21:30.559  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:21:30.559  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:21:30.559  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:21:30.559  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:30.559  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:30.559  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:21:30.560  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:30.560  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:30.560  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:30.560  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:30.560  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:30.560  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:30.560  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:30.561  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:30.561  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:30.562  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:30.562  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:30.563  3806  3856 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 03:21:30.565  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:21:30.566  2683  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 03:21:30.566  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:30.573  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:30.576  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:30.576  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:21:30.576  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:21:30.576  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:21:30.576  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:21:30.576  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:21:30.576  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:21:30.580  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:30.580  2683  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 03:21:30.580  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.581  3806  3856 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:21:30.581  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:21:30.583  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:30.585  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:21:30.586  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:21:30.586  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:21:30.590  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:21:30.590  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:21:30.590  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:21:30.591  2683  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 03:21:30.591  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.591  2683  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:21:30.592  3806  3856 D BluetoothAdapter: STATE_ON
,08-25 03:21:30.595  2683  2696 D BtGatt.GattService: registerClient() - UUID=0f8602e2-7a91-4a1b-8e18-4b73770a20f6
,08-25 03:21:30.595  2683  2704 D BtGatt.GattService: onClientRegistered() - UUID=0f8602e2-7a91-4a1b-8e18-4b73770a20f6, clientIf=5
08-25 03:21:30.596  3806  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 03:21:30.597  2683  2694 D BtGatt.GattService: start scan with filters
,08-25 03:21:30.600  2683  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 03:21:30.600  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:30.600  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:30.602  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 03:21:30.602  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 03:21:30.602  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:21:30.602  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:21:30.606  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:21:30.606  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 03:21:30.606  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 03:21:30.606  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.606  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:21:30.608  2683  2709 D BtGatt.ScanManager: handling starting scan
08-25 03:21:30.608  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:21:30.611  3806  3856 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 03:21:30.614  2683  2704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 03:21:30.615  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.615  2683  2709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 03:21:30.621  2683  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 03:21:30.621  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:30.621  2683  2709 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:21:30.622  2683  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 03:21:30.633  2683  2704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 03:21:30.633  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:30.640  2683  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 03:21:30.640  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:31.107  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-25 03:21:31.108  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:21:31.108  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:21:32.147  2683  2683 D BtGatt.ScanManager: awakened up at time 149038
08-25 03:21:32.149  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:32.181  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-25 03:21:32.182  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:32.182   873  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-25 03:21:32.182  2683  2704 D BtGatt.GattService: current time is 149073543396
08-25 03:21:32.187  2683  2704 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-25 03:21:32.188  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-25 03:21:32.189  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-25 03:21:32.190  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-25 03:21:32.191  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-25 03:21:33.369   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 03:21:33.383  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-25 03:21:33.393   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 03:21:33.393   873   893 I Adreno  : Build Date                       : 10/20/15
08-25 03:21:33.393   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 03:21:33.393   873   893 I Adreno  : Local Branch                     : M14
08-25 03:21:33.393   873   893 I Adreno  : Remote Branch                    : 
08-25 03:21:33.393   873   893 I Adreno  : Remote Branch                    : 
08-25 03:21:33.393   873   893 I Adreno  : Reconstruct Branch               : 
,08-25 03:21:33.433   281   358 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (198 us)
,08-25 03:21:33.685  2683  2683 D BtGatt.ScanManager: awakened up at time 150576
,08-25 03:21:33.689  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:33.714  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-25 03:21:33.714  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:33.714  2683  2704 D BtGatt.GattService: current time is 150605680167
08-25 03:21:33.714  2683  2704 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-25 03:21:33.715  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 03:21:33.715  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-25 03:21:33.715  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:21:34.022  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 03:21:34.023  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 03:21:34.058   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 03:21:34.062  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2f50c5d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4c59e19, 16908290=android.view.AbsSavedState$1@4c59e19}, android:focusedViewId=100}]}]
,08-25 03:21:34.063   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 03:21:34.062  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 03:21:34.065  3806  3806 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 03:21:34.067   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-25 03:21:34.067   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-25 03:21:34.067   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-25 03:21:34.067  3806  3806 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 03:21:34.300   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 03:21:34.304   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 03:21:34.306   873  1336 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-25 03:21:34.313   873   893 I DreamManagerService: Entering dreamland.
,08-25 03:21:34.314   873   893 I PowerManagerService: Dozing...
08-25 03:21:34.315   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 03:21:34.369   376  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 03:21:34.370   376  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 03:21:34.372  2683  2683 D BtGatt.ScanManager: awakened up at time 151263
,08-25 03:21:34.373  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:34.384   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:21:34.396  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-25 03:21:34.396  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:21:34.396  2683  2704 D BtGatt.GattService: current time is 151287423724
,08-25 03:21:34.396  2683  2704 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-25 03:21:34.396  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-25 03:21:34.398   873  1311 E native  : do suspend false
,08-25 03:21:34.400  1917  3875 D NfcService: Discovery configuration equal, not updating.
,08-25 03:21:34.419   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 03:21:34.431   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:21:34.436   873  1311 E native  : do suspend true
,08-25 03:21:34.506   376  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 03:21:34.506   376  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 03:21:34.889   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-25 03:21:35.611  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:35.612  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:35.612  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 03:21:35.613  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:35.613  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-25 03:21:35.613  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 03:21:35.614  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:21:35.614  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 03:21:35.614  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:21:35.615  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:21:35.615  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 03:21:35.618  3806  3856 D BluetoothAdapter: STATE_ON
,08-25 03:21:35.620  2683  2696 D BtGatt.GattService: stopScan() - queue size =1
,08-25 03:21:35.623  2683  2694 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:21:35.624  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:21:35.624  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 03:21:35.624  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 03:21:35.625  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 03:21:35.625  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 03:21:35.628  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:21:35.629  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:21:35.630  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:21:35.630  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:21:35.632  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:21:35.634  2683  2683 D BtGatt.ScanManager: awakened up at time 152525
,08-25 03:21:35.635  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:21:35.635  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:21:35.635  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:21:35.637  2683  2704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 03:21:35.637  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:35.638  2683  2709 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:21:35.645  2683  2704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 03:21:35.645  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:35.645  2683  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:21:35.668  2683  2704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-25 03:21:35.669  2683  2704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:21:35.669  2683  2704 D BtGatt.GattService: current time is 152560747175
,08-25 03:21:35.670  2683  2704 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -89, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:21:35.673  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-25 03:21:35.673  2683  2704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:21:36.137  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:21:36.137  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:36.137  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:21:37.826   873  1877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:21:39.558  2114  2639 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 03:21:40.636  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:40.636  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.637  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.637  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:21:40.638  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.638  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:21:40.638  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:40.639  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.639  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:40.639  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.640  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.641  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:40.642  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.645  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.646  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:21:40.646  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.646  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.648  3806  3856 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-25 03:21:40.650  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:40.651  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.651  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.652  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:21:40.653  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.653  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.653  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:40.653  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.654  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:40.654  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.654  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.654  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.654  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.654  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.655  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:21:40.655  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.655  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.656  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:40.657  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 03:21:40.657  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:40.657  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:21:40.657  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.657  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.657  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:40.657  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.657  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:40.657  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.657  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:40.658  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.658  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:40.658  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.658  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.658  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.659  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.659  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:21:40.659  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.659  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.660  3806  3856 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-25 03:21:40.660  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:40.660  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:21:40.660  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.661  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:21:40.661  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.661  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.661  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:40.661  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.661  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.661  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:21:40.661  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.661  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.661  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:40.661  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.664  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.665  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.665  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.665  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.665  3806  3856 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 03:21:40.666  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:40.666  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.666  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.666  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.666  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.666  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.666  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:40.666  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.666  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.666  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.666  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.666  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.667  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.667  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.668  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.668  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:21:40.668  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.668  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.669  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 03:21:40.669  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:21:40.669  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:21:40.670  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 03:21:40.670  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 03:21:40.670  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:21:40.670  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:21:40.670  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 03:21:40.670  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:21:40.670  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:40.670  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.670  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.670  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.671  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:40.671  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.671  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:40.671  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.671  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.671  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.671  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.671  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.671  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:40.671  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.673  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.674  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.674  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.674  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.676  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:21:40.676  3806  3856 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-25 03:21:40.676  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 03:21:40.681  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-25 03:21:40.681  3806  3856 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 03:21:40.681  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 03:21:40.681  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 03:21:40.681  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 03:21:40.682  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-25 03:21:40.683  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 03:21:40.684  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 03:21:40.684  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 03:21:40.684  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 03:21:40.684  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 03:21:40.684  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 03:21:40.684  3806  3856 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-25 03:21:40.685  3806  3856 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 03:21:40.685  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:21:40.685  3806  3856 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:21:40.685  3806  3856 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 03:21:40.685  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:21:40.685  3806  3856 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:21:40.685  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-25 03:21:40.689  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-25 03:21:40.690  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 03:21:40.690  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 03:21:40.691  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-25 03:21:40.691  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-25 03:21:40.691  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 03:21:40.691  3806  3856 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:21:40.692  3806  3856 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-25 03:21:40.692  3806  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-25 03:21:40.693  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:40.693  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.693  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:21:40.693  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.693  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.693  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.694  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 03:21:40.694  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:40.695  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:40.695  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.695  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.695  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.695  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.695  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.695  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.695  3806  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
,08-25 03:21:40.697  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.697  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.697  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.697  3806  3880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:21:40.697  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.698  3806  3856 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 03:21:40.699  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:40.699  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.699  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.699  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.699  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.699  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.699  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:40.699  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:40.700  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.700  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:21:40.700  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.700  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.700  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.700  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.701  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.701  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.701  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:40.701  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.703  3806  3856 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 03:21:40.703  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:40.703  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:40.703  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.704  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:21:40.704  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.704  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.704  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:40.704  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.704  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.704  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.704  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.704  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:40.704  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.704  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.705  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.706  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.706  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.707  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.707  3806  3856 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-25 03:21:40.707  3806  3856 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 03:21:40.707  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:21:40.708  3806  3856 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 03:21:40.708  3806  3856 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 03:21:40.708  3806  3856 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 03:21:40.708  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 03:21:40.708  3806  3856 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 03:21:40.708  3806  3856 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 03:21:40.708  3806  3856 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 03:21:40.708  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 03:21:40.708  3806  3856 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 03:21:40.708  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:40.708  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:21:40.709  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:40.709  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.709  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.709  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.709  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:40.709  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.709  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.709  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:21:40.709  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.709  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.709  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.710  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.710  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:40.710  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:40.711  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:40.711  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:40.711  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:40.711  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.711  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:40.711  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:40.711  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:40.712  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:40.712  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:40.712  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:40.712  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:41.710  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:41.715  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:41.776  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:21:41.776  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:21:41.776  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:41.777  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:41.827  3555  3883 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:21:41.827  3555  3883 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:21:41.827  3555  3883 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	... 12 more
08-25 03:21:41.827  3555  3883 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at fal.a(PG:38)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:21:41.827  3555  3883 E HttpOperation: 	... 14 more
,08-25 03:21:41.905  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-25 03:21:41.905  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 03:21:41.905  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:41.905  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:41.950  3555  3883 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 03:21:41.950  3555  3883 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at hec.a(PG:42)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at hee.a(PG:102)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at czr.a(PG:65)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at kka.a(PG:108)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:21:41.950  3555  3883 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	... 15 more
08-25 03:21:41.950  3555  3883 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at fal.a(PG:38)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:21:41.950  3555  3883 E HttpOperation: 	... 17 more
,08-25 03:21:41.955  3555  3883 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:21:41.955  3555  3883 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at hee.a(PG:102)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	... 15 more
08-25 03:21:41.955  3555  3883 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:21:41.955  3555  3883 E ExperimentLoader: 	... 17 more
,08-25 03:21:42.070   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 129341, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:21:44.106  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:44.277  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:44.283  1522  3886 I VacuumService: Vacuum at: now=1472088104283 tag=VacuumService
,08-25 03:21:44.341  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 03:21:44.342  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 03:21:44.342  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:44.342  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:44.356  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 03:21:44.357  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 03:21:44.357  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-25 03:21:44.395  1522  3887 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-25 03:21:44.397  1522  3887 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 03:21:44.422  1522  3887 W Uploader:  no longer exists, so no auth token.
,08-25 03:21:45.341   873  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-25 03:21:45.713  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:45.713  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.713  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:45.714  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:45.714  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.714  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:45.715  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:45.715  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:45.716  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:21:45.717  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:45.717  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.717  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:45.718  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:45.718  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.718  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:45.718  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:45.719  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:45.719  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.719  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.720  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:45.724  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:21:45.725  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:45.725  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:45.726  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.730  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 03:21:45.731  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:21:45.734  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-25 03:21:45.736  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 03:21:45.737  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-25 03:21:45.738  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 03:21:45.739  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-25 03:21:45.739  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:21:45.740  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:21:45.740  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 03:21:45.741  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 03:21:45.741  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 03:21:45.741  3806  3894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:21:45.741  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:45.742  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 03:21:45.743  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-25 03:21:45.743  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:45.743  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:45.744  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:21:45.744  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:21:45.744  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:21:45.746  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.746  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.747  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:21:45.748  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:21:45.748  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:21:45.748  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:21:45.748  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:45.748  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:45.748  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:45.748  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:45.749  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:45.749  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.749  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.749  3806  3894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 03:21:45.749  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:45.749  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:45.749  3806  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 03:21:45.749  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.749  3806  3894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 03:21:45.749  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:45.749  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.749  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.750  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.750  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:45.750  3806  3806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 03:21:45.752  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:45.752  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:21:45.752  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.752  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.754  3806  3856 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 03:21:45.754  3806  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 03:21:45.754  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 03:21:45.755  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:21:45.755  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:21:45.755  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:45.755  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:21:45.755  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:45.755  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:45.755  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.755  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.756  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
,08-25 03:21:45.756  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.756  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.756  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:45.756  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.756  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.756  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.756  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.758  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:45.758  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:21:45.758  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.758  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
,08-25 03:21:45.764  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:21:45.764  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:21:45.764  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:45.765  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:45.765  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.765  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.765  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:45.765  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:45.765  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.765  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:45.765  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.766  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.766  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.766  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:45.767  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:45.767  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:21:45.767  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.767  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.769  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:21:45.769  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:21:45.769  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:21:45.769  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:21:45.769  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.770  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.770  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d4fdcf not in the list
08-25 03:21:45.770  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.770  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.770  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:45.770  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:21:45.770  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:45.770  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:45.770  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:45.772  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:21:45.772  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:21:45.772  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:21:45.772  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1f535c not in the list
08-25 03:21:45.774  3806  3856 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 03:21:45.774  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:21:45.774  3806  3856 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 03:21:45.774  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:21:45.774  3806  3856 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 03:21:45.774  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 03:21:45.778  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 03:21:45.778  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 03:21:45.779  3806  3856 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-25 03:21:45.779  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 03:21:45.779  3806  3856 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 03:21:45.780  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 03:21:45.780  3806  3856 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 03:21:45.780  3806  3856 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-25 03:21:45.780  3806  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 03:21:45.780  3806  3856 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 03:21:45.781  3806  3856 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 03:21:45.781  3806  3856 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 03:21:45.781  3806  3856 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 03:21:45.781  3806  3856 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 03:21:45.782  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:21:45.783  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d6f8bf added. We now have 3 listener(s)
08-25 03:21:45.783  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:21:45.785  3806  3856 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 03:21:45.785   873  2090 D WifiService: setWifiEnabled: true pid=3806, uid=10000
,08-25 03:21:45.786   873  2090 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:21:45.828  2683  2839 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-25 03:21:45.829  3806  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-25 03:21:45.830  2683  2872 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-25 03:21:46.249  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:21:46.820  1522  3887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-25 03:21:46.820  1522  3887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-25 03:21:46.820  1522  3887 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:21:46.820  1522  3887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:46.851  1522  3887 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:21:46.851  1522  3887 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 03:21:46.851  1522  3887 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 03:21:47.136  1522  3887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-25 03:21:47.136  1522  3887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-25 03:21:47.136  1522  3887 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:47.137  1522  3887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:47.161  1522  3887 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:21:47.161  1522  3887 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 03:21:47.161  1522  3887 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 03:21:47.630  1522  3887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-25 03:21:47.630  1522  3887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-25 03:21:47.630  1522  3887 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:47.631  1522  3887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:47.650  1522  3887 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:21:47.650  1522  3887 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 03:21:47.650  1522  3887 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 03:21:49.453   873  1877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 03:21:50.247  1522  2211 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 03:21:50.796  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:21:50.797  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90c4b8c added. We now have 4 listener(s)
08-25 03:21:50.797  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:21:50.814  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:50.815  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90c4b8c removed from the list
08-25 03:21:50.815  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:21:50.816  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:50.816  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:21:50.820  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:21:50.821  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38902d5 added. We now have 4 listener(s)
08-25 03:21:50.821  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:21:50.826  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:21:50.827  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38902d5 removed from the list
08-25 03:21:50.827  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:21:50.827  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:21:50.827  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:21:50.830  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:21:50.830  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f14aea added. We now have 4 listener(s)
08-25 03:21:50.830  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:21:50.836   873  1942 D WifiService: setWifiEnabled: false pid=3806, uid=10000
,08-25 03:21:50.836   873  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:21:50.845  2683  2700 D BluetoothAdapterState: Current state: ON, message: 23
08-25 03:21:50.845  2683  2700 D BluetoothAdapterProperties: Setting state to 13
,08-25 03:21:50.845  2683  2700 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 03:21:50.846  2683  2700 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 03:21:50.846  2683  2700 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:21:50.847  2683  2704 D BluetoothAdapterProperties: Scan Mode:20
,08-25 03:21:50.848  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:21:50.848  2683  2700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 03:21:50.855  2683  2683 D BluetoothMapService: onReceive
08-25 03:21:50.855  2683  2683 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:21:50.855  2683  2683 D BluetoothMapService: STATE_TURNING_OFF
08-25 03:21:50.855  2683  2683 D BluetoothMapService: MAP Service closeService in
08-25 03:21:50.855  2683  2683 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 03:21:50.855  2683  2683 D ObexServerSockets0: shutdown(block = true)
08-25 03:21:50.856  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 03:21:50.856  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 03:21:50.857  2683  2884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 03:21:50.857  2683  2872 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 03:21:50.857  2683  2885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-25 03:21:50.861  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:50.861  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:21:50.862  2683  2683 I BtOppRfcommListener: stopping Accept Thread
08-25 03:21:50.863  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.863  2683  3445 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:21:50.863  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:50.864  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:21:50.865  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 03:21:50.868  2683  3445 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 03:21:50.869   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 03:21:50.869   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-25 03:21:50.869   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 03:21:50.869   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:21:50.872  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:50.876  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:50.880  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:50.880  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:21:50.881  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.881  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:50.883   873  1311 E native  : do suspend true
08-25 03:21:50.884  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:50.884  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:21:50.885   873   886 I ActivityManager: Start proc 3904:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-25 03:21:50.885  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.885  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:50.888  2683  2683 D HeadsetService: Received stop request...Stopping profile...
08-25 03:21:50.891  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:50.895  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:50.895  1931  2108 D BluetoothHeadset: Proxy object disconnected
08-25 03:21:50.897  1355  2012 D BluetoothHeadset: Proxy object disconnected
08-25 03:21:50.897   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 03:21:50.897   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 03:21:50.897   873   873 D BluetoothHeadset: Proxy object disconnected
,08-25 03:21:50.897  2683  2683 D A2dpService: Received stop request...Stopping profile...
08-25 03:21:50.898  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:50.898  2683  2879 D A2dpStateMachine: Exit Disconnected: -1
08-25 03:21:50.898  1355  1355 D HeadsetProfile: Bluetooth service disconnected
08-25 03:21:50.899   873   873 D BluetoothA2dp: Proxy object disconnected
08-25 03:21:50.899  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 03:21:50.899  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 03:21:50.899  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-25 03:21:50.899  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:21:50.899  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:21:50.900  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:50.900   873  1879 D DhcpClient: Clearing IP address
08-25 03:21:50.901  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 03:21:50.901   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:21:50.901  2683  2839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:21:50.901  2683  2839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:21:50.901  2683  2839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:21:50.901  2683  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 03:21:50.902  2683  2704 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 03:21:50.902  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:21:50.903  2683  2683 D HidService: Received stop request...Stopping profile...
,08-25 03:21:50.903  2683  2683 D HidService: Stopping Bluetooth HidService
08-25 03:21:50.903  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-25 03:21:50.903  1355  1355 D HidProfile: Bluetooth service disconnected
08-25 03:21:50.904  2683  2683 D HealthService: Received stop request...Stopping profile...
08-25 03:21:50.904   372   871 D CommandListener: Setting iface cfg
08-25 03:21:50.906  2683  2683 D PanService: Received stop request...Stopping profile...
08-25 03:21:50.907   873  1880 D DhcpClient: Receive thread stopped
08-25 03:21:50.907  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 03:21:50.907  1355  1355 D PanProfile: Bluetooth service disconnected
08-25 03:21:50.908  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 03:21:50.908  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 03:21:50.908  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:21:50.908  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:21:50.909  2683  2683 D BluetoothMapService: Received stop request...Stopping profile...
08-25 03:21:50.909  2683  2683 D BluetoothMapService: stop()
08-25 03:21:50.910   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 03:21:50.911   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 03:21:50.912   873  1311 E native  : do suspend true
08-25 03:21:50.912   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 03:21:50.912   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 03:21:50.915  2683  2683 D BluetoothMapAppObserver: deinitObservers()
,08-25 03:21:50.915  2683  2683 D BluetoothMapAppObserver: removeReceiver()
08-25 03:21:50.915   873  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 03:21:50.916   395   395 E Parcel  : Reading a NULL string not supported here.
08-25 03:21:50.920  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 03:21:50.920  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 03:21:50.920  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:21:50.920  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:21:50.920  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 03:21:50.920  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-25 03:21:50.921  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 03:21:50.921  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 03:21:50.921  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:21:50.921  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:21:50.921  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 03:21:50.921  2683  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 03:21:50.921  2683  2704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 03:21:50.921  2683  2839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:21:50.921  1355  1355 D BluetoothMap: Proxy object disconnected
08-25 03:21:50.922  1355  1355 D MapProfile: Bluetooth service disconnected
08-25 03:21:50.922  2683  2839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 03:21:50.922  2683  2839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:21:50.922  2683  2839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:21:50.922  2683  2839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:21:50.922  2683  2839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:21:50.922  2683  2704 E bt_btif : L2CAP - PSM: 0x0017 not found f: Unknown service being enabled
08-25 03:21:50.923  1522  2109 V NativeCrypto: Read error: ssl=0xaa2a6c00: I/O error during system call, Connection timed out
08-25 03:21:50.923  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:21:50.923  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 03:21:50.923  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 03:21:50.923  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:21:50.923  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:21:50.923  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 03:21:50.923  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 03:21:50.925  2683  2683 D BluetoothMapService: MAP Service closeService in
08-25 03:21:50.925  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 03:21:50.925  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 03:21:50.925  1522  2109 V NativeCrypto: SSL shutdown failed: ssl=0xaa2a6c00: I/O error during system call, Broken pipe
08-25 03:21:50.925  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:21:50.925  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:21:50.926  2683  2700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 03:21:50.926  2683  2700 D BluetoothAdapterProperties: Setting state to 15
08-25 03:21:50.926  2683  2700 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 03:21:50.926  2683  2683 D BluetoothMapService: cleanup()
08-25 03:21:50.926  2683  2683 D BluetoothMapService: MAP Service closeService in
08-25 03:21:50.926  1931  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:21:50.927  2683  2700 I BluetoothAdapterState: Entering BleOnState
08-25 03:21:50.927  1355  2266 D BluetoothPan: onBluetoothStateChange on: false
08-25 03:21:50.928  1355  1367 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 03:21:50.929  1355  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:21:50.929   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:21:50.929   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 03:21:50.929   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:21:50.929  1355  2012 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 03:21:50.933  1355  2266 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:21:50.934  1355  1367 D BluetoothMap: onBluetoothStateChange: up=false
08-25 03:21:50.934   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:21:50.934  2683  2700 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 03:21:50.934  2683  2700 D BluetoothAdapterProperties: Setting state to 16
08-25 03:21:50.934  2683  2700 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 03:21:50.935  2683  2700 D BluetoothAdapterProperties: onBleDisable
,08-25 03:21:50.935  2683  2700 I BluetoothAdapterState: Entering PendingCommandState
08-25 03:21:50.935  2683  2701 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 03:21:50.936  2683  2704 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:21:50.937  2683  2839 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 03:21:50.937  2683  2839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:21:50.938  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:50.938  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:50.939  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.939  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:50.940  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:50.940  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:50.941  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.941  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:21:50.946  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:50.946  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:50.947  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:50.947  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:21:50.948  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:50.952  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:50.953  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:50.955  3904  3904 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-25 03:21:50.964   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 03:21:50.975  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 03:21:50.979   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f4adc6:true
08-25 03:21:50.980  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:21:50.994   873  2966 I ActivityManager: Start proc 3920:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 03:21:50.999   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 03:21:51.000   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 03:21:51.001   873  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 03:21:51.001   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:21:51.002   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-25 03:21:51.005   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 03:21:51.007  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:51.008  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:21:51.010  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:21:51.015  3391  3391 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ecaa263 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-25 03:21:51.018   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 03:21:51.021  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:51.021  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:51.021   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 03:21:51.022  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:51.022  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:51.024  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:51.024  2114  2329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:51.024  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:51.024  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:51.025  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:51.026  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:51.026  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:51.027  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:51.027  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:51.037  3904  3904 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 03:21:51.039  3904  3904 D BluetoothMap: Create BluetoothMap proxy object
,08-25 03:21:51.046  3920  3920 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 03:21:51.048  3904  3904 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 03:21:51.061  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:21:51.069   873  2965 I ActivityManager: Killing 3047:com.google.android.talk/u0a61 (adj 15): empty #17
,08-25 03:21:51.082   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-25 03:21:51.140  2683  2704 I bt_hci  : shut_down
,08-25 03:21:51.141  2683  2711 D bt_hwcfg: hw_epilog_process
,08-25 03:21:51.153  2683  2711 I bt_vendor: low_power_mode_cb
,08-25 03:21:51.183  2683  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 03:21:51.183  2683  2711 I bt_vendor: epilog_cb
08-25 03:21:51.183  2683  2711 I bt_hci  : epilog_finished_callback
,08-25 03:21:51.190  2683  2704 I bt_hci_h4: hal_close
,08-25 03:21:51.190  2683  2704 I bt_userial_vendor: device fd = 51 close
,08-25 03:21:51.216  3920  3920 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 03:21:51.216  3920  3920 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
,08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 03:21:51.216  3920  3920 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.216  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 03:21:51.217  3920  3920 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 03:21:51.217  3920  3920 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:21:51.217  3920  3920 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:21:51.217  3920  3920 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:21:51.217  3920  3920 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:21:51.217  3920  3920 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:21:51.222  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 03:21:51.232  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:21:51.277   873  2966 I ActivityManager: Start proc 3955:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-25 03:21:51.279  3904  3904 D DockEventReceiver: finishStartingService: stopping service
08-25 03:21:51.280   873  2965 I ActivityManager: Killing 3391:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 03:21:51.357  2683  2701 D bt_stack_manager: event_shut_down_stack finished.
08-25 03:21:51.357  2683  2700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 03:21:51.358  2683  2700 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 03:21:51.358  2683  2683 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 03:21:51.359  2683  2683 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 03:21:51.359  2683  2683 D BtGatt.GattService: stop()
08-25 03:21:51.359  2683  2683 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 03:21:51.363  2683  2683 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:21:51.363  2683  2683 V BluetoothAdapterState: isTurningOn()=false
,08-25 03:21:51.363  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:21:51.363  2683  2683 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 03:21:51.364  2683  2700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 03:21:51.364  2683  2700 D BluetoothAdapterProperties: Setting state to 10
,08-25 03:21:51.364  2683  2700 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 03:21:51.365  2683  2700 I BluetoothAdapterState: Entering OffState
,08-25 03:21:51.366   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 03:21:51.376  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 03:21:51.376  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 03:21:51.376  2683  2683 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 03:21:51.377  2683  2701 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 03:21:51.380  2683  2701 D bt_stack_manager: event_clean_up_stack finished.
,08-25 03:21:51.386  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-25 03:21:51.389  2683  2683 I art     : System.exit called, status: 0
,08-25 03:21:51.389  2683  2683 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 03:21:51.449   873  1942 I ActivityManager: Process com.android.bluetooth (pid 2683) has died
,08-25 03:21:51.563  3955  3974 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 03:21:51.563  3955  3974 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 03:21:51.568  3955  3974 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 03:21:51.568  3955  3974 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 03:21:51.661  3955  3974 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 03:21:51.661  3955  3974 I Babel_SMS: MmsConfig.loadFromResources
08-25 03:21:51.662  3955  3974 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-25 03:21:51.663  3955  3974 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 03:21:51.759  3955  3955 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 03:21:51.762  3955  3955 I Babel_Crash: startup - clean
,08-25 03:21:51.804  3955  3955 I Babel_telephony: TeleModule.launchCompleted
,08-25 03:21:51.816   873  1942 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 03:21:51.839  3955  3955 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-25 03:21:51.853  3955  3955 W Babel   : BAM#gBA: invalid account id: -1
,08-25 03:21:51.853  3955  3955 W Babel   : BAM#gBA: invalid account id: -1
,08-25 03:21:51.853  3955  3955 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-25 03:21:51.859   873  1698 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 03:21:51.861  3955  3981 I Babel   : deleted: false for 0
,08-25 03:21:51.879  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:21:51.892  1742  1742 D SystemUpdateService: onCreate
,08-25 03:21:51.904  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:21:51.917  1742  3983 I SystemUpdateService: active receiver: enabled
,08-25 03:21:51.922  1742  3983 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:21:51.924  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 03:21:51.926  1742  3983 I SystemUpdateService: network: null; metered: false; mobile allowed: false
08-25 03:21:51.928  1742  2416 I iu.UploadsManager: num queued entries: 0
,08-25 03:21:51.928  1742  2416 I iu.UploadsManager: num updated entries: 0
,08-25 03:21:51.931  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:21:51.931  1742  3983 I SystemUpdateService: now status is 0 (complete)
08-25 03:21:51.932  1742  2416 I iu.SyncManager: NEXT; no task
,08-25 03:21:51.932  1742  3983 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 03:21:51.933  1742  3983 I SystemUpdateService: file has been verified
,08-25 03:21:51.933  1742  3983 I SystemUpdateService: OTA package size = 12249756
,08-25 03:21:51.937  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 03:21:51.937  1742  3983 I SystemUpdateService: showing system update notification
,08-25 03:21:51.963  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:21:51.974   873  1915 I ActivityManager: Start proc 3985:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 03:21:51.975  1742  1742 D SystemUpdateService: onDestroy
,08-25 03:21:52.004  3985  3985 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 03:21:52.008  3985  3985 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:21:52.043  3985  3985 D SprintDMHelper: simOperator: 
,08-25 03:21:52.043  3985  3985 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:21:52.046  3955  3955 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 03:21:52.053  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:21:52.061   873  1947 I ActivityManager: Start proc 3997:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 03:21:52.068  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:21:52.072  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:21:52.074  3920  3942 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 03:21:52.078  3955  3955 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:21:52.081   873   883 I ActivityManager: Killing 3584:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-25 03:21:52.142  3955  3955 I vclib   : onServiceConnected
,08-25 03:21:52.170   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e091998:true
,08-25 03:21:52.252   873  1942 I ActivityManager: Start proc 4012:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 03:21:52.254  3955  4011 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 03:21:52.257   873  2965 I ActivityManager: Killing 3462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 03:21:52.336  4012  4012 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 03:21:52.398  4012  4012 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 03:21:52.398  4012  4012 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 03:21:52.398  4012  4012 I GAv4    :   adb logcat -s GAv4
,08-25 03:21:52.413  4012  4012 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 03:21:52.422  4012  4012 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 03:21:52.450  4012  4030 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 03:21:52.569  4012  4012 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 03:21:52.608  4012  4012 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 03:21:52.622  4012  4012 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9505-9512)
,08-25 03:21:52.622  4012  4012 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 03:21:52.635  4012  4012 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ed8ea53}
,08-25 03:21:52.636  4012  4012 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 03:21:52.636  4012  4012 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 03:21:52.646  4012  4012 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 03:21:52.648  4012  4012 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 03:21:52.665  4012  4012 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 03:21:52.680  4012  4012 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 03:21:52.680  4012  4012 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 03:21:52.680  4012  4012 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 03:21:52.680  4012  4012 I Adreno  : Build Date                       : 10/20/15
08-25 03:21:52.680  4012  4012 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 03:21:52.680  4012  4012 I Adreno  : Local Branch                     : M14
08-25 03:21:52.680  4012  4012 I Adreno  : Remote Branch                    : 
08-25 03:21:52.680  4012  4012 I Adreno  : Remote Branch                    : 
08-25 03:21:52.680  4012  4012 I Adreno  : Reconstruct Branch               : 
,08-25 03:21:52.741  4012  4012 I NSApplication: Starting up...
,08-25 03:21:52.751  4012  4058 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 03:21:52.788   873  1915 I ActivityManager: Start proc 4063:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 03:21:52.789   873  1915 I ActivityManager: Killing 3500:android.process.acore/u0a5 (adj 15): empty #17
,08-25 03:21:52.875  4063  4063 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 03:21:53.082   873  1915 I ActivityManager: Killing 3689:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 03:21:53.162   873  1386 I ActivityManager: Start proc 4077:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 03:21:53.220  4077  4077 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 03:21:53.264  4077  4077 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides,
,08-25 03:21:53.281   873  1947 I ActivityManager: Killing 3705:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 03:21:55.867   873  1698 D WifiService: setWifiEnabled: true pid=3806, uid=10000
08-25 03:21:55.868   873  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:21:55.880   873  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-25 03:21:55.890  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:55.890  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:21:55.890  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:55.891  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:55.896  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:55.897  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:21:55.897  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:55.897  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:55.901  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:21:55.901  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:21:55.902  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:55.902  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:21:55.925   873  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-25 03:21:55.927   873  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 03:21:55.928   873  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 03:21:55.929   873  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 03:21:55.929   873  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 03:21:55.930   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 03:21:55.930   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 03:21:55.955   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 03:21:55.956   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:21:55.957   372   871 D CommandListener: Setting iface cfg
,08-25 03:21:55.963   873  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
08-25 03:21:55.963   873  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 03:21:55.964   873  1311 E native  : do suspend true
,08-25 03:21:55.977   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:21:55.985   873  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 03:21:55.992   873  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 03:21:56.886   873  2965 I ActivityManager: Killing 2230:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 03:21:57.243   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:21:57.306   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=9.06 delta 1000 -> 994
08-25 03:21:57.308   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 03:21:57.308   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:21:57.320   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 03:21:57.369   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 03:21:57.371  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 03:21:57.425  4012  4012 I art     : Waiting for a blocking GC DisableMovingGc
,08-25 03:21:57.427  4012  4012 I art     : Starting a blocking GC DisableMovingGc
,08-25 03:21:57.793  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 03:21:57.836  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 03:21:57.836  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 03:21:57.845   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:21:57.864   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 03:21:57.864   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:21:57.864   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 03:21:57.878   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:21:57.887   372   871 D CommandListener: Setting iface cfg
,08-25 03:21:57.887   873  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 03:21:57.895   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 03:21:57.938   873  4114 D DhcpClient: Receive thread started
,08-25 03:21:58.021   873  1311 E native  : do suspend false
,08-25 03:21:58.041   873  1879 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 03:21:58.054   873  4114 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172647, domain null
,08-25 03:21:58.055   873  1879 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172647 seconds
,08-25 03:21:58.058   873  1879 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 03:21:58.073   873  4114 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 03:21:58.074   873  1879 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 03:21:58.079   372   871 D CommandListener: Setting iface cfg
,08-25 03:21:58.091   873  1879 D DhcpClient: Scheduling renewal in 86399s
,08-25 03:21:58.094   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 03:21:58.095   873  1311 E native  : do suspend true
,08-25 03:21:58.111   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 03:21:58.112   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 03:21:58.113   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 03:21:58.114   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 03:21:58.118   873  1313 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 03:21:58.172   873  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 03:21:58.172   873  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 03:21:58.174   873  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-25 03:21:58.175   873  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 03:21:58.177   873  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 03:21:58.192   873  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 03:21:58.202   873  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 03:21:58.202   873  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-25 03:21:58.203   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 03:21:58.203   873  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-25 03:21:58.203   873  1313 D ConnectivityService:    accepting network in place of null
08-25 03:21:58.203   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 03:21:58.205   873  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:21:58.215   873  4113 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175106, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 03:21:58.263   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:21:58.301   873  4110 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.87,2a00:1450:400d:803::200e
,08-25 03:21:58.309   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:21:58.314   873  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 03:21:58.314   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:21:58.321   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 03:21:58.325   873  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 03:21:58.327  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:58.328  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:21:58.328  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:58.328  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:58.334  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:58.335  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:21:58.335  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:58.336  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:58.340  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:21:58.340  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:21:58.341  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for mu,ltiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:21:58.341  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:21:58.343   873  4110 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:21:58 GMT], X-Android-Received-Millis=[1472088118341], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472088118332]}
,08-25 03:21:58.347   873  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 03:21:58.347   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 03:21:58.348   873  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 03:21:58.349   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 03:21:58.356  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:21:58.364  1742  1742 D SystemUpdateService: onCreate
,08-25 03:21:58.369  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:21:58.390  1742  4126 I SystemUpdateService: active receiver: enabled
,08-25 03:21:58.397  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 03:21:58.400  1742  2416 I iu.UploadsManager: num queued entries: 0
,08-25 03:21:58.401  1742  2416 I iu.UploadsManager: num updated entries: 0
,08-25 03:21:58.411  1742  4126 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:21:58.414  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:21:58.416  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 03:21:58.417  1742  4126 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
08-25 03:21:58.418  1742  4126 I SystemUpdateService: now status is 0 (complete)
08-25 03:21:58.418  1742  4126 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:21:58.418  1742  4126 I SystemUpdateService: file has been verified
,08-25 03:21:58.418  1742  4126 I SystemUpdateService: OTA package size = 12249756
08-25 03:21:58.419  3985  3985 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:21:58.422  1742  2416 I iu.SyncManager: NEXT; no task
,08-25 03:21:58.427  1742  4130 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 03:21:58.427  1742  4130 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 03:21:58.427  3985  3985 D SprintDMHelper: simOperator: 
08-25 03:21:58.428  3985  3985 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:21:58.433  1742  4130 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 03:21:58.444  1742  4126 I SystemUpdateService: showing system update notification
08-25 03:21:58.447  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:58.450  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:21:58.532  3955  4133 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 03:21:58.539  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 03:21:58.541  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 03:21:58.545  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:21:58.545  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:58.552  1742  1742 D SystemUpdateService: onDestroy
,08-25 03:21:58.569  1742  4130 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-25 03:21:58.578  3028  4125 V KeepSync: Connecting to GoogleApiClient
,08-25 03:21:58.578   873  1947 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 03:21:58.631  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 03:21:58.631  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 03:21:58.631  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:21:58.631  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:58.647  1742  4141 V BaseAuthAsyncOperation: access token request failed
,08-25 03:21:58.648  3028  4125 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 03:21:58.725  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 03:21:58.725  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-25 03:21:58.725  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:21:58.725  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:21:58.742  3028  4125 E KeepSync: IOException
08-25 03:21:58.742  3028  4125 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 03:21:58.742  3028  4125 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:21:58.742  3028  4125 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 03:21:58.742  3028  4125 E KeepSync: 	... 10 more
,08-25 03:21:58.742  3028  4125 W KeepSync: Sync result 2
,08-25 03:21:58.749   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 161820, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:21:59.315   873  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 03:22:00.874   873  1386 D WifiService: setWifiEnabled: false pid=3806, uid=10000
08-25 03:22:00.874   873  1386 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:22:00.905  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 03:22:00.908   873  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 03:22:00.908   873  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 03:22:00.908   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 03:22:00.909   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:22:00.922   873  1311 E native  : do suspend true
,08-25 03:22:00.935   873  1879 D DhcpClient: Clearing IP address
,08-25 03:22:00.937   372   871 D CommandListener: Setting iface cfg
,08-25 03:22:00.940   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 03:22:00.943   873  4114 D DhcpClient: Receive thread stopped
,08-25 03:22:00.952  1522  4140 V NativeCrypto: Read error: ssl=0x9a87fa00: I/O error during system call, Connection timed out
,08-25 03:22:00.954  1522  4140 V NativeCrypto: SSL shutdown failed: ssl=0x9a87fa00: I/O error during system call, Broken pipe
,08-25 03:22:00.958   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 03:22:00.958   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-25 03:22:00.964   395   395 E Parcel  : Reading a NULL string not supported here.
,08-25 03:22:00.971   873  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-25 03:22:00.973   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 03:22:00.973   873  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-25 03:22:00.973   873  1311 E native  : do suspend true
,08-25 03:22:01.004   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:22:01.034   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:22:01.035   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 03:22:01.036   873  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 03:22:01.037   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:22:01.042   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 03:22:01.051  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:01.051  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:01.051  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:22:01.052  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:01.053   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:22:01.056  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:01.056  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:01.057  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.057  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:01.059  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:01.060  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:01.060  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.060  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:01.073  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:22:01.074   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 03:22:01.076  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:01.076  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:01.077  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.077  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:01.078   873  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 03:22:01.079  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:01.079  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:01.079  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.080  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:01.081  1742  1742 D SystemUpdateService: onCreate
08-25 03:22:01.081  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:01.082  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:01.082  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:01.082  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:01.084  2114  2329 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 03:22:01.089  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:22:01.099  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 03:22:01.102  1742  2416 I iu.UploadsManager: num queued entries: 0
,08-25 03:22:01.106  1742  4150 I SystemUpdateService: active receiver: enabled
,08-25 03:22:01.109  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 03:22:01.110  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 03:22:01.112  3985  3985 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:22:01.116  3985  3985 D SprintDMHelper: simOperator: 
,08-25 03:22:01.116  3985  3985 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:22:01.153   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-25 03:22:01.154   873  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-25 03:22:01.157  3955  4153 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 03:22:01.164  1742  2416 I iu.UploadsManager: num updated entries: 0
,08-25 03:22:01.170  1742  2416 I iu.SyncManager: NEXT; no task
,08-25 03:22:01.172  1742  4150 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:22:01.173  1742  4150 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 03:22:01.173  1742  4150 I SystemUpdateService: now status is 0 (complete)
,08-25 03:22:01.173  1742  4150 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:22:01.173  1742  4150 I SystemUpdateService: file has been verified
08-25 03:22:01.174  1742  4150 I SystemUpdateService: OTA package size = 12249756
,08-25 03:22:01.177  1742  4150 I SystemUpdateService: showing system update notification
,08-25 03:22:01.191  1742  1742 D SystemUpdateService: onDestroy
,08-25 03:22:05.934   873   890 I ActivityManager: Start proc 4159:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 03:22:06.060  4159  4159 D AdapterServiceConfig: Adding HeadsetService
,08-25 03:22:06.060  4159  4159 D AdapterServiceConfig: Adding A2dpService
,08-25 03:22:06.060  4159  4159 D AdapterServiceConfig: Adding HidService
,08-25 03:22:06.061  4159  4159 D AdapterServiceConfig: Adding HealthService
,08-25 03:22:06.061  4159  4159 D AdapterServiceConfig: Adding PanService
,08-25 03:22:06.061  4159  4159 D AdapterServiceConfig: Adding GattService
,08-25 03:22:06.061  4159  4159 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 03:22:06.075   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bb0a83:true
08-25 03:22:06.076  4159  4159 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 03:22:06.082  4159  4159 I bt_bluedroid: init
,08-25 03:22:06.084  4159  4171 I BluetoothAdapterState: Entering OffState
,08-25 03:22:06.088  4159  4172 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 03:22:06.089  4159  4172 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 03:22:06.089  4159  4172 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 03:22:06.090  4159  4172 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 03:22:06.091  4159  4159 I bt_bluedroid: get_profile_interface socket
,08-25 03:22:06.093  4159  4159 I bt_bluedroid: get_profile_interface sdp
08-25 03:22:06.097  4159  4175 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 03:22:06.106  4159  4170 I bt_bluedroid: config_hci_snoop_log
,08-25 03:22:06.107  4159  4175 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:22:06.110   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 03:22:06.118  4159  4171 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 03:22:06.118  4159  4171 D BluetoothAdapterProperties: Setting state to 14
,08-25 03:22:06.119  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 03:22:06.121  4159  4171 D BluetoothBondStateMachine: make
,08-25 03:22:06.125  4159  4176 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 03:22:06.129  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:22:06.131  4159  4159 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 03:22:06.136  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:06.138  4159  4159 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 03:22:06.139  4159  4159 D BtGatt.GattService: Received start request. Starting profile...
,08-25 03:22:06.139  4159  4159 D BtGatt.GattService: start()
,08-25 03:22:06.139  4159  4159 I bt_bluedroid: get_profile_interface gatt
,08-25 03:22:06.140  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:06.140  4159  4159 D BtGatt.AdvertiseManager: advertise manager created
,08-25 03:22:06.150  4159  4159 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:22:06.150  4159  4159 V BluetoothAdapterState: isTurningOn()=false
,08-25 03:22:06.150  4159  4159 V BluetoothAdapterState: isBleTurningOn()=true
08-25 03:22:06.151  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:06.151  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 03:22:06.152  4159  4171 I bt_bluedroid: enable
,08-25 03:22:06.152  4159  4172 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 03:22:06.152  4159  4172 I bt_hci  : start_up
,08-25 03:22:06.164  4159  4172 I bt_vendor: alloc value 0xb3a79189
,08-25 03:22:06.164  4159  4172 I bt_vendor: init
08-25 03:22:06.164  4159  4172 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 03:22:06.164  4159  4172 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 03:22:06.207   873  1313 D ConnectivityService: handlePromptUnvalidated 101
,08-25 03:22:06.273  4159  4172 D bt_hci  : start_up starting async portion
,08-25 03:22:06.274  4159  4179 I bt_hci  : event_finish_startup
08-25 03:22:06.274  4159  4179 I bt_hci_h4: hal_open
,08-25 03:22:06.274  4159  4179 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 03:22:06.281  4159  4179 I bt_userial_vendor: device fd = 51 open
,08-25 03:22:06.316  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:22:06.348  4159  4179 D bt_hwcfg: Chipset BCM4354A2
,08-25 03:22:06.348  4159  4179 D bt_hwcfg: Target name = [BCM4354A2]
08-25 03:22:06.350  4159  4179 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 03:22:07.017  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 03:22:07.019  4159  4179 D bt_hwcfg: Settlement delay -- 100 ms
08-25 03:22:07.019  4159  4179 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 03:22:07.136  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:22:07.137  4159  4179 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 03:22:07.167  4159  4179 I bt_hwcfg: vendor lib fwcfg completed
,08-25 03:22:07.167  4159  4179 I bt_vendor: firmware callback
08-25 03:22:07.167  4159  4179 I bt_hci  : firmware_config_callback
,08-25 03:22:07.197  4159  4181 I bt_btu  : btu_task pending for preload complete event
,08-25 03:22:07.198  4159  4181 I bt_btu_task: Bluetooth chip preload is complete
08-25 03:22:07.198  4159  4181 I bt_btu  : btu_task received preload complete event
,08-25 03:22:07.219  4159  4181 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 03:22:07.219  4159  4181 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 03:22:07.219  4159  4181 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 03:22:07.220  4159  4181 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 03:22:07.220  4159  4181 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 03:22:07.220  4159  4181 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 03:22:07.220  4159  4181 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 03:22:07.221  4159  4181 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 03:22:07.221  4159  4181 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 03:22:07.221  4159  4181 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 03:22:07.221  4159  4181 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 03:22:07.222  4159  4181 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 03:22:07.222  4159  4181 I         : BTE_InitTraceLevels -- TRC_SMP
,08-25 03:22:07.222  4159  4181 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 03:22:07.222  4159  4181 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 03:22:07.349  4159  4181 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d
,08-25 03:22:07.349  4159  4181 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,08-25 03:22:07.363  4159  4175 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 03:22:07.364  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 03:22:07.365  4159  4175 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 03:22:07.367  4159  4175 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:22:07.370  4159  4175 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:22:07.371  4159  4175 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 03:22:07.371  4159  4175 D bt_hci  : do_postload posting postload work item,
08-25 03:22:07.372  4159  4179 I bt_hci  : event_postload
,08-25 03:22:07.372  4159  4179 I bt_vendor: sco_config_cb
08-25 03:22:07.373  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:07.373  4159  4179 I bt_hci  : sco_config_callback postload finished.
08-25 03:22:07.374  4159  4175 D bt_bte_conf: Device ID record 1 : primary
08-25 03:22:07.375  4159  4175 D bt_bte_conf:   vendorId            = 000f
08-25 03:22:07.375  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:07.375  4159  4175 D bt_bte_conf:   vendorIdSource      = 0001
08-25 03:22:07.375  4159  4175 D bt_bte_conf:   product             = 1200
,08-25 03:22:07.375  4159  4175 D bt_bte_conf:   version             = 1436
,08-25 03:22:07.376  4159  4175 D bt_bte_conf:   clientExecutableURL = 
,08-25 03:22:07.376  4159  4175 D bt_bte_conf:   serviceDescription  = 
,08-25 03:22:07.376  4159  4175 D bt_bte_conf:   documentationURL    = 
08-25 03:22:07.376  4159  4175 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 03:22:07.377  4159  4172 D bt_stack_manager: event_start_up_stack finished,
08-25 03:22:07.377  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:07.378  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-25 03:22:07.378  4159  4171 D BluetoothAdapterProperties: Setting state to 15
08-25 03:22:07.379  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 03:22:07.379  4159  4179 I bt_vendor: low_power_mode_cb
08-25 03:22:07.380  4159  4171 I BluetoothAdapterState: Entering BleOnState
,08-25 03:22:07.384  4159  4171 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 03:22:07.384  4159  4171 D BluetoothAdapterProperties: Setting state to 11
08-25 03:22:07.385  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-25 03:22:07.392  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:07.393  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
08-25 03:22:07.393  4159  4159 D HeadsetService: Received start request. Starting profile...
08-25 03:22:07.394  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:07.395  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:07.396  4159  4159 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:22:07.397  4159  4159 D HeadsetStateMachine: make
,08-25 03:22:07.410  4159  4159 D HeadsetStateMachine: max_hf_connections = 1
,08-25 03:22:07.410  4159  4159 I bt_bluedroid: get_profile_interface handsfree
08-25 03:22:07.411  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040,
08-25 03:22:07.411  4159  4175 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-25 03:22:07.414  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:22:07.415  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
08-25 03:22:07.416  4159  4159 D A2dpService: Received start request. Starting profile...
08-25 03:22:07.417  4159  4159 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 03:22:07.417  4159  4159 I bt_bluedroid: get_profile_interface avrcp
,08-25 03:22:07.422  4159  4159 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 03:22:07.422  4159  4159 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 03:22:07.422  4159  4159 D A2dpStateMachine: make
,08-25 03:22:07.423  4159  4159 I bt_bluedroid: get_profile_interface a2dp
,08-25 03:22:07.424  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 03:22:07.428  4159  4190 D A2dpStateMachine: Enter Disconnected: -2
08-25 03:22:07.428  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:22:07.429  4159  4159 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 03:22:07.430  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:07.431  3904  3904 D BluetoothInputDevice: Proxy object connected
,08-25 03:22:07.432  4159  4159 D HidService: Received start request. Starting profile...
08-25 03:22:07.432  4159  4159 I bt_bluedroid: get_profile_interface hidhost
08-25 03:22:07.432  4159  4175 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
08-25 03:22:07.432  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 03:22:07.432  3904  3904 D HidProfile: Bluetooth service connected
08-25 03:22:07.432  4159  4159 D HidService: setHidService(): set to: null
,08-25 03:22:07.433  4159  4159 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:22:07.434  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:07.434  4159  4159 D HealthService: Received start request. Starting profile...
,08-25 03:22:07.435  4159  4159 I bt_bluedroid: get_profile_interface health
,08-25 03:22:07.436  4159  4159 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 03:22:07.437  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:07.438  4159  4159 D PanService: Received start request. Starting profile...
,08-25 03:22:07.438  4159  4159 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 03:22:07.438  4159  4159 I bt_bluedroid: get_profile_interface pan
,08-25 03:22:07.438  3904  3904 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 03:22:07.438  4159  4175 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 03:22:07.440  3904  3904 D PanProfile: Bluetooth service connected
08-25 03:22:07.441  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:07.442  4159  4159 D BluetoothMapService: Received start request. Starting profile...
08-25 03:22:07.442  3904  3904 D BluetoothMap: Proxy object connected
,08-25 03:22:07.442  4159  4159 D BluetoothMapService: start()
08-25 03:22:07.442  3904  3904 D MapProfile: Bluetooth service connected
,08-25 03:22:07.442  3904  3904 D BluetoothMap: getConnectedDevices()
08-25 03:22:07.443  3904  3904 D BluetoothMap: Bluetooth is Not enabled
08-25 03:22:07.444  4159  4159 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 03:22:07.444  4159  4159 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 03:22:07.445  4159  4159 D BluetoothMapAppObserver: createReceiver()
08-25 03:22:07.445  4159  4159 D BluetoothMapAppObserver: initObservers()
08-25 03:22:07.446  4159  4159 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 03:22:07.451  4159  4159 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:22:07.451  4159  4159 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:07.451  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:07.451  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:07.453  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:07.453  4159  4159 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:07.453  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:22:07.453  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:07.453  4159  4188 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:07.454  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:07.455  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:07.456  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 03:22:07.456  4159  4171 D BluetoothAdapterProperties: ScanMode =  20
,08-25 03:22:07.456  4159  4171 D BluetoothAdapterProperties: State =  11
08-25 03:22:07.459  4159  4175 D BluetoothAdapterProperties: Scan Mode:21
08-25 03:22:07.459  4159  4171 D BluetoothAdapterProperties: Setting state to 12
08-25 03:22:07.459  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 03:22:07.459  4159  4175 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:22:07.459  4159  4171 I BluetoothAdapterState: Entering OnState
,08-25 03:22:07.460  1931  2214 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:07.460  1355  1367 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:07.462  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:07.463  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:22:07.463  1355  1355 D PanProfile: Bluetooth service connected
08-25 03:22:07.463  3904  3914 D BluetoothPan: onBluetoothStateChange on: true
,08-25 03:22:07.463  3904  3916 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 03:22:07.464  1355  2012 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 03:22:07.464  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:07.465  1355  1355 D BluetoothInputDevice: Proxy object connected
08-25 03:22:07.465  1355  1355 D HidProfile: Bluetooth service connected
,08-25 03:22:07.465  1355  1367 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:22:07.466   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:22:07.466   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:22:07.466  3904  3914 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:22:07.466   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:07.466  1355  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:22:07.467   873   873 D BluetoothA2dp: Proxy object connected
,08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:07.467  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:07.468  1355  2266 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:22:07.469  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:07.470  1355  1355 D BluetoothA2dp: Proxy object connected
,08-25 03:22:07.471  1355  1367 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 03:22:07.472  4159  4159 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 03:22:07.472  1355  1355 D BluetoothMap: Proxy object connected
08-25 03:22:07.472  1355  1355 D MapProfile: Bluetooth service connected
,08-25 03:22:07.472   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:07.472  1355  1355 D BluetoothMap: getConnectedDevices()
08-25 03:22:07.473  3904  3916 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:22:07.473  4159  4159 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:07.473  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:07.475  4159  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:22:07.475  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:07.476   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 03:22:07.477  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:07.478  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:07.480  4159  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:07.480  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:07.481  3904  3904 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-25 03:22:07.481  4159  4159 D ObexServerSockets: Succeed to create listening sockets 
08-25 03:22:07.481  4159  4159 D ObexServerSockets0: startAccept()
08-25 03:22:07.481  4159  4159 D ObexServerSockets0: prepareForNewConnect()
08-25 03:22:07.483  3904  3904 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 03:22:07.484  4159  4159 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 03:22:07.484  4159  4159 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-25 03:22:07.484  4159  4159 D BluetoothMapService: onReceive
08-25 03:22:07.484  4159  4159 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:22:07.484  4159  4159 D BluetoothMapService: STATE_ON
08-25 03:22:07.485  4159  4197 D ObexServerSockets0: Accepting socket connection...
08-25 03:22:07.485  4159  4196 D ObexServerSockets0: Accepting socket connection...
,08-25 03:22:07.493  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:22:07.496  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 03:22:07.499  3904  3904 D BluetoothA2dp: Proxy object connected
,08-25 03:22:07.499  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:22:07.501  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:22:07.505  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:22:07.505  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:22:07.516  1355  1355 D BluetoothPbap: Proxy object connected
08-25 03:22:07.516  1355  1355 D PbapServerProfile: Bluetooth service connected
08-25 03:22:07.516  3904  3904 D BluetoothPbap: Proxy object connected
08-25 03:22:07.516  3904  3904 D PbapServerProfile: Bluetooth service connected
08-25 03:22:07.516  4159  4159 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 03:22:07.516  4159  4159 D ObexServerSockets0: prepareForNewConnect()
,08-25 03:22:07.525  4159  4201 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:07.528  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 03:22:07.528  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:22:07.529  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:22:07.529  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:22:07.538  4159  4205 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:07.540  4159  4205 I BtOppRfcommListener: Accept thread started.
,08-25 03:22:07.549  3518  3518 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 03:22:07.549  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 03:22:07.550  3518  3518 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-25 03:22:07.562  1931  1945 D BluetoothHeadset: Proxy object connected
,08-25 03:22:07.563  1355  1367 D BluetoothHeadset: Proxy object connected
08-25 03:22:07.563  1355  1355 D HeadsetProfile: Bluetooth service connected
08-25 03:22:07.563   873   873 D BluetoothHeadset: Proxy object connected
08-25 03:22:07.563   873   873 D BluetoothHeadset: Proxy object connected
08-25 03:22:07.563   873   873 D BluetoothHeadset: Proxy object connected
,08-25 03:22:07.566  1355  2266 D BluetoothHeadset: Proxy object connected
,08-25 03:22:07.566  1355  1355 D HeadsetProfile: Bluetooth service connected
08-25 03:22:07.566   873   890 D BluetoothHeadset: Proxy object connected
08-25 03:22:07.566   873   890 D BluetoothHeadset: Proxy object connected
,08-25 03:22:07.573   873   890 D BluetoothHeadset: Proxy object connected
,08-25 03:22:07.586  3904  3914 D BluetoothHeadset: Proxy object connected
,08-25 03:22:07.587  3904  3904 D HeadsetProfile: Bluetooth service connected
,08-25 03:22:10.891  4159  4171 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 03:22:10.891  4159  4171 D BluetoothAdapterProperties: Setting state to 13
,08-25 03:22:10.892  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 03:22:10.894  4159  4171 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 03:22:10.897  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:22:10.900  4159  4175 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:22:10.901  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 03:22:10.908  4159  4159 D BluetoothMapService: onReceive
08-25 03:22:10.908  4159  4159 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:22:10.908  4159  4159 D BluetoothMapService: STATE_TURNING_OFF
,08-25 03:22:10.909  4159  4159 D BluetoothMapService: MAP Service closeService in
08-25 03:22:10.909  4159  4159 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 03:22:10.910  4159  4159 D ObexServerSockets0: shutdown(block = true)
08-25 03:22:10.913  4159  4196 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 03:22:10.915  4159  4159 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 03:22:10.916  4159  4159 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 03:22:10.917  4159  4183 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 03:22:10.917  4159  4197 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-25 03:22:10.918  4159  4159 I BtOppRfcommListener: stopping Accept Thread
,08-25 03:22:10.919  4159  4205 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:22:10.919  4159  4205 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 03:22:10.924  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 03:22:10.924  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:10.924  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:10.928  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:10.928  4159  4159 D HeadsetService: Received stop request...Stopping profile...
08-25 03:22:10.928  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:10.930  3904  3914 D BluetoothHeadset: Proxy object disconnected
,08-25 03:22:10.930  4159  4159 D A2dpService: Received stop request...Stopping profile...
,08-25 03:22:10.930  1931  2214 D BluetoothHeadset: Proxy object disconnected
,08-25 03:22:10.930  4159  4190 D A2dpStateMachine: Exit Disconnected: -1
,08-25 03:22:10.931  1355  1367 D BluetoothHeadset: Proxy object disconnected
08-25 03:22:10.932   873   873 D BluetoothHeadset: Proxy object disconnected
,08-25 03:22:10.932   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 03:22:10.932   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 03:22:10.932   873   873 D BluetoothA2dp: Proxy object disconnected
08-25 03:22:10.932  4159  4159 D HidService: Received stop request...Stopping profile...
,08-25 03:22:10.932  4159  4159 D HidService: Stopping Bluetooth HidService
08-25 03:22:10.933  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:10.933  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:10.934  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:10.934  4159  4159 D HealthService: Received stop request...Stopping profile...
,08-25 03:22:10.934  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:10.937  4159  4159 D PanService: Received stop request...Stopping profile...
08-25 03:22:10.938  4159  4159 D BluetoothMapService: Received stop request...Stopping profile...
08-25 03:22:10.938  4159  4159 D BluetoothMapService: stop()
08-25 03:22:10.939  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:10.939  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:22:10.939  4159  4159 D BluetoothMapAppObserver: deinitObservers()
,08-25 03:22:10.939  4159  4159 D BluetoothMapAppObserver: removeReceiver()
08-25 03:22:10.940  3806  3806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:22:10.940  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:10.941  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:10.942  3904  3904 D DockEventReceiver: finishStartingService: stopping service
08-25 03:22:10.942  4159  4159 V BluetoothAdapterState: isTurningOff()=true
,08-25 03:22:10.942  4159  4159 V BluetoothAdapterState: isTurningOn()=false
08-25 03:22:10.942  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:10.942  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:10.943  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:10.944  4159  4159 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 03:22:10.945  4159  4181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:22:10.945  4159  4181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:22:10.945  3904  3904 D HeadsetProfile: Bluetooth service disconnected
08-25 03:22:10.945  4159  4181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:22:10.945  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-25 03:22:10.945  4159  4175 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 03:22:10.946  3904  3904 D BluetoothA2dp: Proxy object disconnected
08-25 03:22:10.946  3904  3904 D BluetoothInputDevice: Proxy object disconnected
08-25 03:22:10.946  3904  3904 D HidProfile: Bluetooth service disconnected
08-25 03:22:10.947  1355  1355 D HeadsetProfile: Bluetooth service disconnected
,08-25 03:22:10.947  1355  1355 D BluetoothA2dp: Proxy object disconnected
08-25 03:22:10.947  3904  3904 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 03:22:10.947  1355  1355 D BluetoothInputDevice: Proxy object disconnected
08-25 03:22:10.948  1355  1355 D HidProfile: Bluetooth service disconnected
08-25 03:22:10.948  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:10.945  4159  4159 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 03:22:10.949  1355  1355 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 03:22:10.949  1355  1355 D PanProfile: Bluetooth service disconnected
08-25 03:22:10.949  4159  4159 V BluetoothAdapterState: isTurningOff()=true
08-25 03:22:10.949  4159  4159 V BluetoothAdapterState: isTurningOn()=false
,08-25 03:22:10.949  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:10.949  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:10.950  1355  1355 D BluetoothMap: Proxy object disconnected
08-25 03:22:10.950  1355  1355 D MapProfile: Bluetooth service disconnected
,08-25 03:22:10.947  3904  3904 D PanProfile: Bluetooth service disconnected
08-25 03:22:10.951  3904  3904 D BluetoothMap: Proxy object disconnected
,08-25 03:22:10.953  4159  4181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 03:22:10.953  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:22:10.953  4159  4181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:22:10.954  4159  4181 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:22:10.954  4159  4181 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:22:10.954  4159  4181 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 03:22:10.954  4159  4181 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:22:10.954  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 03:22:10.954  4159  4159 V BluetoothAdapterState: isTurningOff()=true
08-25 03:22:10.954  4159  4159 V BluetoothAdapterState: isTurningOn()=false
,08-25 03:22:10.954  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:10.954  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:10.955  4159  4159 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 03:22:10.955  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 03:22:10.955  4159  4159 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 03:22:10.955  4159  4159 V BluetoothAdapterState: isTurningOff()=true
08-25 03:22:10.955  4159  4159 V BluetoothAdapterState: isTurningOn()=false
08-25 03:22:10.955  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:10.956  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:10.956  4159  4159 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 03:22:10.956  4159  4175 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 03:22:10.956  4159  4159 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:22:10.956  4159  4159 V BluetoothAdapterState: isTurningOff()=true
08-25 03:22:10.957  4159  4159 V BluetoothAdapterState: isTurningOn()=false
08-25 03:22:10.957  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:10.957  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:10.957  4159  4159 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 03:22:10.957  4159  4159 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 03:22:10.958  3904  3904 D MapProfile: Bluetooth service disconnected
,08-25 03:22:10.958  4159  4159 D BluetoothMapService: MAP Service closeService in
08-25 03:22:10.958  4159  4159 V BluetoothAdapterState: isTurningOff()=true
08-25 03:22:10.958  4159  4159 V BluetoothAdapterState: isTurningOn()=false
,08-25 03:22:10.958  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:22:10.959  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:10.959  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 03:22:10.959  4159  4171 D BluetoothAdapterProperties: Setting state to 15
,08-25 03:22:10.959  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 03:22:10.960  4159  4171 I BluetoothAdapterState: Entering BleOnState
08-25 03:22:10.960  4159  4159 D BluetoothMapService: cleanup()
08-25 03:22:10.960  4159  4159 D BluetoothMapService: MAP Service closeService in
,08-25 03:22:10.962  1355  1355 D BluetoothPbap: Proxy object disconnected
08-25 03:22:10.963  1355  1355 D PbapServerProfile: Bluetooth service disconnected
08-25 03:22:10.963  1931  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:22:10.963  1355  1376 D BluetoothPan: onBluetoothStateChange on: false
,08-25 03:22:10.966  3904  3916 D BluetoothPan: onBluetoothStateChange on: false
,08-25 03:22:10.966  3904  3914 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 03:22:10.967  1355  1367 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 03:22:10.967  1355  2266 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:22:10.967   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:22:10.968  3904  3916 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:22:10.968   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:22:10.968  3904  3914 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 03:22:10.969   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:22:10.969  1355  2012 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 03:22:10.969  1355  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 03:22:10.970  1355  1367 D BluetoothMap: onBluetoothStateChange: up=false
08-25 03:22:10.970   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:22:10.977  3904  3916 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 03:22:10.978  3904  3914 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:22:10.978  4159  4171 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 03:22:10.978  4159  4171 D BluetoothAdapterProperties: Setting state to 16
08-25 03:22:10.978  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 03:22:10.979  4159  4171 D BluetoothAdapterProperties: onBleDisable
,08-25 03:22:10.979  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
08-25 03:22:10.980  4159  4172 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 03:22:10.981  4159  4181 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 03:22:10.981  4159  4181 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:22:10.981  4159  4175 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:22:10.973  3904  3904 D BluetoothPbap: Proxy object disconnected
08-25 03:22:10.984  3904  3904 D PbapServerProfile: Bluetooth service disconnected
,08-25 03:22:10.985  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 03:22:10.986  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:10.987  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:10.989  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:10.990  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:10.991  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:10.991  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:22:10.993  3904  3904 D DockEventReceiver: finishStartingService: stopping service
08-25 03:22:10.993  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:11.183  4159  4175 I bt_hci  : shut_down
,08-25 03:22:11.183  4159  4179 D bt_hwcfg: hw_epilog_process
,08-25 03:22:11.187  4159  4179 I bt_vendor: low_power_mode_cb
,08-25 03:22:11.210  4159  4179 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 03:22:11.211  4159  4179 I bt_vendor: epilog_cb
08-25 03:22:11.211  4159  4179 I bt_hci  : epilog_finished_callback
,08-25 03:22:11.220  4159  4175 I bt_hci_h4: hal_close
,08-25 03:22:11.222  4159  4175 I bt_userial_vendor: device fd = 51 close
,08-25 03:22:11.340  4159  4172 D bt_stack_manager: event_shut_down_stack finished.
,08-25 03:22:11.340  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 03:22:11.346  4159  4171 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 03:22:11.346  4159  4159 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 03:22:11.348  4159  4159 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 03:22:11.348  4159  4159 D BtGatt.GattService: stop()
,08-25 03:22:11.348  4159  4159 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 03:22:11.353  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:11.353  4159  4159 V BluetoothAdapterState: isTurningOn()=false
08-25 03:22:11.353  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:22:11.354  4159  4159 V BluetoothAdapterState: isBleTurningOff()=true
08-25 03:22:11.354  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 03:22:11.355  4159  4171 D BluetoothAdapterProperties: Setting state to 10
,08-25 03:22:11.355  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 03:22:11.358  4159  4171 I BluetoothAdapterState: Entering OffState
08-25 03:22:11.359   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 03:22:11.375  4159  4159 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 03:22:11.375  4159  4159 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 03:22:11.375  4159  4159 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 03:22:11.378  4159  4172 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 03:22:11.381  4159  4172 D bt_stack_manager: event_clean_up_stack finished.
,08-25 03:22:11.382  4159  4159 I art     : System.exit called, status: 0
,08-25 03:22:11.382  4159  4159 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 03:22:11.433   873  1697 I ActivityManager: Process com.android.bluetooth (pid 4159) has died
,08-25 03:22:15.888  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:22:15.889  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:15.894  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:22:15.895  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f14aea removed from the list
08-25 03:22:15.895  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:22:15.895  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:15.896  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:15.901  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:22:15.902  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f89478 added. We now have 4 listener(s)
08-25 03:22:15.902  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:22:15.907  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:22:15.907  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f89478 removed from the list
08-25 03:22:15.907  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:22:15.907  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:15.907  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:15.908  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:22:15.908  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e3f751 added. We now have 4 listener(s)
08-25 03:22:15.908  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:22:20.919  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:20.972   873   890 I ActivityManager: Start proc 4219:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 03:22:21.109  4219  4219 D AdapterServiceConfig: Adding HeadsetService
,08-25 03:22:21.109  4219  4219 D AdapterServiceConfig: Adding A2dpService
08-25 03:22:21.109  4219  4219 D AdapterServiceConfig: Adding HidService
08-25 03:22:21.110  4219  4219 D AdapterServiceConfig: Adding HealthService
08-25 03:22:21.110  4219  4219 D AdapterServiceConfig: Adding PanService
08-25 03:22:21.110  4219  4219 D AdapterServiceConfig: Adding GattService
08-25 03:22:21.110  4219  4219 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 03:22:21.124   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8ee9e16:true
,08-25 03:22:21.125  4219  4219 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 03:22:21.129  4219  4219 I bt_bluedroid: init
,08-25 03:22:21.129  4219  4231 I BluetoothAdapterState: Entering OffState
,08-25 03:22:21.136  4219  4232 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 03:22:21.137  4219  4232 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 03:22:21.137  4219  4232 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 03:22:21.138  4219  4232 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 03:22:21.139  4219  4219 I bt_bluedroid: get_profile_interface socket
,08-25 03:22:21.141  4219  4219 I bt_bluedroid: get_profile_interface sdp
08-25 03:22:21.146  4219  4230 I bt_bluedroid: config_hci_snoop_log
,08-25 03:22:21.146  4219  4235 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 03:22:21.150  4219  4235 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:22:21.150   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 03:22:21.161  4219  4231 D BluetoothAdapterState: Current state: OFF, message: 0
08-25 03:22:21.161  4219  4231 D BluetoothAdapterProperties: Setting state to 14
08-25 03:22:21.162  4219  4231 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 03:22:21.164  4219  4231 D BluetoothBondStateMachine: make
,08-25 03:22:21.168  4219  4236 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 03:22:21.171  4219  4231 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:22:21.173  4219  4219 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 03:22:21.176  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:21.177  4219  4219 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 03:22:21.177  4219  4219 D BtGatt.GattService: Received start request. Starting profile...
08-25 03:22:21.177  4219  4219 D BtGatt.GattService: start()
,08-25 03:22:21.177  4219  4219 I bt_bluedroid: get_profile_interface gatt
,08-25 03:22:21.178  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:21.178  4219  4219 D BtGatt.AdvertiseManager: advertise manager created
,08-25 03:22:21.187  4219  4219 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:22:21.187  4219  4219 V BluetoothAdapterState: isTurningOn()=false
08-25 03:22:21.187  4219  4219 V BluetoothAdapterState: isBleTurningOn()=true
,08-25 03:22:21.187  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:21.188  4219  4231 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 03:22:21.188  4219  4231 I bt_bluedroid: enable
,08-25 03:22:21.189  4219  4232 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 03:22:21.189  4219  4232 I bt_hci  : start_up
,08-25 03:22:21.196  4219  4232 I bt_vendor: alloc value 0xb3a79189
,08-25 03:22:21.196  4219  4232 I bt_vendor: init
08-25 03:22:21.196  4219  4232 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-25 03:22:21.196  4219  4232 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 03:22:21.304  4219  4232 D bt_hci  : start_up starting async portion
,08-25 03:22:21.305  4219  4239 I bt_hci  : event_finish_startup
08-25 03:22:21.306  4219  4239 I bt_hci_h4: hal_open
08-25 03:22:21.306  4219  4239 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 03:22:21.320  4219  4239 I bt_userial_vendor: device fd = 51 open
,08-25 03:22:21.348  4219  4239 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:22:21.379  4219  4239 D bt_hwcfg: Chipset BCM4354A2
,08-25 03:22:21.379  4219  4239 D bt_hwcfg: Target name = [BCM4354A2]
08-25 03:22:21.380  4219  4239 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 03:22:22.259  4219  4239 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 03:22:22.261  4219  4239 D bt_hwcfg: Settlement delay -- 100 ms
08-25 03:22:22.261  4219  4239 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 03:22:22.379  4219  4239 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:22:22.381  4219  4239 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61,
,08-25 03:22:22.409  4219  4239 I bt_hwcfg: vendor lib fwcfg completed
08-25 03:22:22.410  4219  4239 I bt_vendor: firmware callback
08-25 03:22:22.410  4219  4239 I bt_hci  : firmware_config_callback
,08-25 03:22:22.422  4219  4241 I bt_btu  : btu_task pending for preload complete event
08-25 03:22:22.423  4219  4241 I bt_btu_task: Bluetooth chip preload is complete
08-25 03:22:22.423  4219  4241 I bt_btu  : btu_task received preload complete event
,08-25 03:22:22.433  4219  4241 I         : BTE_InitTraceLevels -- TRC_HCI,
,08-25 03:22:22.434  4219  4241 I         : BTE_InitTraceLevels -- TRC_L2CAP,
,08-25 03:22:22.434  4219  4241 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 03:22:22.434  4219  4241 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 03:22:22.435  4219  4241 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 03:22:22.435  4219  4241 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 03:22:22.435  4219  4241 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 03:22:22.435  4219  4241 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 03:22:22.436  4219  4241 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 03:22:22.436  4219  4241 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 03:22:22.436  4219  4241 I         : BTE_InitTraceLevels -- TRC_SDP
,08-25 03:22:22.436  4219  4241 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 03:22:22.437  4219  4241 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 03:22:22.437  4219  4241 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 03:22:22.437  4219  4241 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 03:22:22.587  4219  4241 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39f6d9d,
08-25 03:22:22.587  4219  4241 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39f6d9d 
,08-25 03:22:22.600  4219  4235 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-25 03:22:22.602  4219  4235 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 03:22:22.603  4219  4235 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 03:22:22.609  4219  4235 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:22:22.614  4219  4235 D BluetoothAdapterProperties: Scan Mode:20
,08-25 03:22:22.614  4219  4235 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 03:22:22.615  4219  4235 D bt_hci  : do_postload posting postload work item
,08-25 03:22:22.617  4219  4239 I bt_hci  : event_postload
08-25 03:22:22.617  4219  4239 I bt_vendor: sco_config_cb
08-25 03:22:22.618  4219  4239 I bt_hci  : sco_config_callback postload finished.
,08-25 03:22:22.620  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:22.622  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:22.622  4219  4235 D bt_bte_conf: Device ID record 1 : primary
,08-25 03:22:22.622  4219  4235 D bt_bte_conf:   vendorId            = 000f
,08-25 03:22:22.622  4219  4235 D bt_bte_conf:   vendorIdSource      = 0001,
08-25 03:22:22.622  4219  4235 D bt_bte_conf:   product             = 1200
,08-25 03:22:22.622  4219  4235 D bt_bte_conf:   version             = 1436
08-25 03:22:22.622  4219  4235 D bt_bte_conf:   clientExecutableURL = 
,08-25 03:22:22.623  4219  4235 D bt_bte_conf:   serviceDescription  = 
08-25 03:22:22.623  4219  4235 D bt_bte_conf:   documentationURL    = 
,08-25 03:22:22.623  4219  4235 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 03:22:22.623  4219  4232 D bt_stack_manager: event_start_up_stack finished
08-25 03:22:22.623  4219  4231 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
08-25 03:22:22.623  4219  4231 D BluetoothAdapterProperties: Setting state to 15
,08-25 03:22:22.623  4219  4231 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 03:22:22.627  4219  4231 I BluetoothAdapterState: Entering BleOnState
,08-25 03:22:22.628  4219  4231 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-25 03:22:22.628  4219  4231 D BluetoothAdapterProperties: Setting state to 11
08-25 03:22:22.628  4219  4231 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-25 03:22:22.630  4219  4239 I bt_vendor: low_power_mode_cb
,08-25 03:22:22.643  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:22.644  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:22.648  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:22.648  4219  4219 D HeadsetService: Received start request. Starting profile...
08-25 03:22:22.651  4219  4219 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:22:22.651  4219  4219 D HeadsetStateMachine: make
,08-25 03:22:22.661  4219  4231 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:22:22.662  4219  4219 D HeadsetStateMachine: max_hf_connections = 1,
,08-25 03:22:22.662  4219  4219 I bt_bluedroid: get_profile_interface handsfree
08-25 03:22:22.662  4219  4235 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 03:22:22.662  4219  4235 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 03:22:22.668  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
08-25 03:22:22.668  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:22:22.668  4219  4219 D A2dpService: Received start request. Starting profile...
08-25 03:22:22.669  4219  4219 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 03:22:22.669  4219  4219 I bt_bluedroid: get_profile_interface avrcp
,08-25 03:22:22.675  4219  4219 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 03:22:22.675  4219  4219 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 03:22:22.675  4219  4219 D A2dpStateMachine: make
08-25 03:22:22.676  4219  4219 I bt_bluedroid: get_profile_interface a2dp
,08-25 03:22:22.677  4219  4235 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-25 03:22:22.678  4219  4250 D A2dpStateMachine: Enter Disconnected: -2
08-25 03:22:22.678  4219  4219 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 03:22:22.679  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:22.680  4219  4219 D HidService: Received start request. Starting profile...
,08-25 03:22:22.680  4219  4219 I bt_bluedroid: get_profile_interface hidhost
08-25 03:22:22.680  4219  4235 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d83e5
,08-25 03:22:22.680  4219  4235 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 03:22:22.680  4219  4219 D HidService: setHidService(): set to: null
,08-25 03:22:22.681  4219  4219 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:22:22.681  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
08-25 03:22:22.682  4219  4219 D HealthService: Received start request. Starting profile...
,08-25 03:22:22.683  4219  4219 I bt_bluedroid: get_profile_interface health
08-25 03:22:22.684  4219  4219 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 03:22:22.685  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:22.685  4219  4219 D PanService: Received start request. Starting profile...
08-25 03:22:22.686  4219  4219 D BluetoothPanServiceJni: initializeNative(L110): pan,
08-25 03:22:22.686  4219  4219 I bt_bluedroid: get_profile_interface pan
08-25 03:22:22.686  4219  4235 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 03:22:22.690  4219  4219 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
,08-25 03:22:22.690  4219  4219 D BluetoothMapService: Received start request. Starting profile...
08-25 03:22:22.690  4219  4219 D BluetoothMapService: start(),
,08-25 03:22:22.692  4219  4219 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 03:22:22.693  4219  4219 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 03:22:22.693  4219  4219 D BluetoothMapAppObserver: createReceiver()
,08-25 03:22:22.694  4219  4219 D BluetoothMapAppObserver: initObservers()
08-25 03:22:22.694  4219  4219 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 03:22:22.699  4219  4219 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:22:22.699  4219  4219 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:22.700  4219  4219 V BluetoothAdapterState: isBleTurningOn()=false,
08-25 03:22:22.700  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:22.701  4219  4248 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
,08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isTurningOn()=true
,08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:22.704  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isTurningOff()=false
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isTurningOn()=true
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:22:22.705  4219  4219 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:22:22.706  4219  4231 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 03:22:22.706  4219  4231 D BluetoothAdapterProperties: ScanMode =  20
,08-25 03:22:22.706  4219  4231 D BluetoothAdapterProperties: State =  11
08-25 03:22:22.706  4219  4231 D BluetoothAdapterProperties: Setting state to 12
08-25 03:22:22.706  4219  4231 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 03:22:22.707  1931  1943 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:22.707  4219  4235 D BluetoothAdapterProperties: Scan Mode:21
08-25 03:22:22.707  4219  4235 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 03:22:22.708  1355  2012 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:22:22.708  4219  4231 I BluetoothAdapterState: Entering OnState
08-25 03:22:22.710  3904  3914 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:22:22.710  1355  1355 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:22:22.710  1355  1355 D PanProfile: Bluetooth service connected
,08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:22.711  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:22.713  3904  3916 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 03:22:22.713  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:22.716  1355  1367 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:22.716  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:22.718  1355  1355 D BluetoothInputDevice: Proxy object connected
,08-25 03:22:22.718  1355  1355 D HidProfile: Bluetooth service connected
08-25 03:22:22.718  1355  2012 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:22.718  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:22:22.719   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:22.719  3904  3916 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 03:22:22.721  4219  4219 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 03:22:22.721   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 03:22:22.721  4219  4219 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 03:22:22.722  3904  3914 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:22:22.723  4219  4219 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:22.723   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:22:22.724  1355  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:22:22.725  1355  2266 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:22:22.725  4219  4219 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:22:22.727  1355  1367 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:22:22.727  4219  4219 D ObexServerSockets: Succeed to create listening sockets 
08-25 03:22:22.727  4219  4219 D ObexServerSockets0: startAccept()
08-25 03:22:22.727  4219  4219 D ObexServerSockets0: prepareForNewConnect()
08-25 03:22:22.715  3904  3904 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:22:22.728  3904  3904 D PanProfile: Bluetooth service connected
08-25 03:22:22.728  3904  3904 D BluetoothInputDevice: Proxy object connected
08-25 03:22:22.728  3904  3904 D HidProfile: Bluetooth service connected
,08-25 03:22:22.728   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:22:22.729  3904  3916 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:22:22.729  4219  4219 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 03:22:22.729  4219  4219 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 03:22:22.729  4219  4256 D ObexServerSockets0: Accepting socket connection...
08-25 03:22:22.730  4219  4257 D ObexServerSockets0: Accepting socket connection...
,08-25 03:22:22.730  1355  1355 D BluetoothA2dp: Proxy object connected
,08-25 03:22:22.730   873   873 D BluetoothA2dp: Proxy object connected
08-25 03:22:22.731  3904  4255 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:22:22.732  1355  1355 D BluetoothMap: Proxy object connected
08-25 03:22:22.732  1355  1355 D MapProfile: Bluetooth service connected
08-25 03:22:22.732  1355  1355 D BluetoothMap: getConnectedDevices()
08-25 03:22:22.733  4219  4219 D BluetoothMapService: onReceive
08-25 03:22:22.733  4219  4219 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:22:22.734  4219  4219 D BluetoothMapService: STATE_ON
08-25 03:22:22.734  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:22.735   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 03:22:22.735  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:22.736  3904  3904 D BluetoothA2dp: Proxy object connected
08-25 03:22:22.737  3904  3904 D BluetoothMap: Proxy object connected
08-25 03:22:22.737  3904  3904 D MapProfile: Bluetooth service connected
08-25 03:22:22.737  3904  3904 D BluetoothMap: getConnectedDevices()
,08-25 03:22:22.743  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 03:22:22.748  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:22:22.753  3904  3904 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:22:22.756  3904  3904 D BluetoothPbap: Proxy object connected
,08-25 03:22:22.756  3904  3904 D PbapServerProfile: Bluetooth service connected
,08-25 03:22:22.759  1355  1355 D BluetoothPbap: Proxy object connected
,08-25 03:22:22.759  1355  1355 D PbapServerProfile: Bluetooth service connected
08-25 03:22:22.761  4219  4219 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 03:22:22.761  4219  4219 D ObexServerSockets0: prepareForNewConnect()
,08-25 03:22:22.766  4219  4262 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:22.788  4219  4266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:22.790  4219  4266 I BtOppRfcommListener: Accept thread started.
,08-25 03:22:22.812  3904  3916 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.813  3904  3904 D HeadsetProfile: Bluetooth service connected
,08-25 03:22:22.813  1931  2214 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.813  1355  1367 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.814  1355  1355 D HeadsetProfile: Bluetooth service connected
08-25 03:22:22.814   873   873 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.814   873   873 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.814   873   873 D BluetoothHeadset: Proxy object connected
,08-25 03:22:22.819  1355  2266 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.819   873   890 D BluetoothHeadset: Proxy object connected
08-25 03:22:22.819  1355  1355 D HeadsetProfile: Bluetooth service connected
,08-25 03:22:22.824   873   890 D BluetoothHeadset: Proxy object connected
,08-25 03:22:22.829   873   890 D BluetoothHeadset: Proxy object connected
,08-25 03:22:22.832  3904  4255 D BluetoothHeadset: Proxy object connected
,08-25 03:22:22.832  3904  3904 D HeadsetProfile: Bluetooth service connected
,08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:25.939  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:25.946  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:25.947  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:22:25.948  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e3f751 removed from the list
,08-25 03:22:25.948  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:22:25.948  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:25.948  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:25.952  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:22:25.953  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d112bb6 added. We now have 4 listener(s)
,08-25 03:22:25.953  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:22:25.957   873   884 D WifiService: setWifiEnabled: false pid=3806, uid=10000
08-25 03:22:25.958   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:22:30.973  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:30.974   873  1386 D WifiService: setWifiEnabled: true pid=3806, uid=10000
,08-25 03:22:30.974   873  1386 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:22:30.986   873  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:31.004  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:31.010  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:22:31.017  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:22:31.021  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:22:31.029   873  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-25 03:22:31.030   873  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-25 03:22:31.031   873  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 03:22:31.032   873  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 03:22:31.032   873  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 03:22:31.032   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 03:22:31.032   873  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 03:22:31.047   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-25 03:22:31.047   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 03:22:31.056   372   871 D CommandListener: Setting iface cfg
,08-25 03:22:31.105   873  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 03:22:31.105   873  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 03:22:31.113   873  1311 E native  : do suspend true
,08-25 03:22:31.115   873  1310 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 03:22:31.129   873  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 03:22:31.172   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:22:32.450   873  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:22:32.596   873  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=10.56 delta 1000 -> 994
,08-25 03:22:32.597   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 03:22:32.597   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:22:32.613   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 03:22:32.686   873  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 03:22:32.688  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 03:22:33.111  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 03:22:33.154  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 03:22:33.156  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 03:22:33.162   873  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:22:33.171   873  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:22:33.171   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:22:33.171   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 03:22:33.197   873  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:22:33.213   372   871 D CommandListener: Setting iface cfg
,08-25 03:22:33.217   873  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 03:22:33.231   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 03:22:33.251   873  4276 D DhcpClient: Receive thread started
,08-25 03:22:33.349   873  1311 E native  : do suspend false
,08-25 03:22:33.373   873  1879 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 03:22:33.393   873  4276 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-25 03:22:33.394   873  1879 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-25 03:22:33.398   873  1879 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 03:22:33.413   873  4276 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 03:22:33.414   873  1879 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 03:22:33.419   372   871 D CommandListener: Setting iface cfg
,08-25 03:22:33.422  1863  1892 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-25 03:22:33.431   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-25 03:22:33.432   873  1879 D DhcpClient: Scheduling renewal in 86399s
,08-25 03:22:33.434   873  1311 E native  : do suspend true
,08-25 03:22:33.436  1863  1892 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-25 03:22:33.461   873  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 03:22:33.463   873  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 03:22:33.465   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 03:22:33.467   873  1313 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 03:22:33.475  1522  1522 I ConfigService: onCreate
,08-25 03:22:33.478   873  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 03:22:33.522   873  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 03:22:33.522   873  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 03:22:33.524   873  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 03:22:33.525   873  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 03:22:33.526   873  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 03:22:33.533   873  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 03:22:33.537   873  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 03:22:33.537   873  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-25 03:22:33.537   873  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 03:22:33.538   873  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 03:22:33.538   873  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 03:22:33.538   873  1313 D ConnectivityService:    accepting network in place of null
08-25 03:22:33.539   873  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:22:33.550   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=210441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 03:22:33.581   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:22:33.605   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:22:33.614   873  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-25 03:22:33.614   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:22:33.621   873  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 03:22:33.632   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 03:22:33.636   873  4274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.88,2a00:1450:400d:802::200e
,08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:22:33.650  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:22:33.654  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:22:33.661   873  4274 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:22:33 GMT], X-Android-Received-Millis=[1472088153659], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472088153655]}
,08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:22:33.661  3806  3806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:22:33.662   873  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 03:22:33.662   873  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-25 03:22:33.663   873  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 03:22:33.663  3806  3806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-25 03:22:33.664   873  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 03:22:33.668  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:22:33.672  1742  1742 D SystemUpdateService: onCreate
,08-25 03:22:33.675  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:22:33.699  1742  4288 I SystemUpdateService: active receiver: enabled
,08-25 03:22:33.700  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 03:22:33.701  1742  2416 I iu.UploadsManager: num queued entries: 0
,08-25 03:22:33.709  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:22:33.711  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000,
,08-25 03:22:33.712  3985  3985 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:22:33.717  1742  4290 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 03:22:33.717  1742  4290 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 03:22:33.718  3985  3985 D SprintDMHelper: simOperator: 
,08-25 03:22:33.718  3985  3985 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:22:33.727  1742  4290 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 03:22:33.740  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:22:33.741  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:22:33.755  1742  4288 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:22:33.755  1742  2416 I iu.UploadsManager: num updated entries: 0
08-25 03:22:33.756  1742  2416 I iu.SyncManager: NEXT; no task
,08-25 03:22:33.778  1742  4288 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 03:22:33.779  1742  4288 I SystemUpdateService: now status is 0 (complete)
08-25 03:22:33.780  1742  4288 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:22:33.780  1742  4288 I SystemUpdateService: file has been verified
,08-25 03:22:33.780  1742  4288 I SystemUpdateService: OTA package size = 12249756
,08-25 03:22:33.796  1742  4288 I SystemUpdateService: showing system update notification
,08-25 03:22:33.800  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 03:22:33.800  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 03:22:33.800  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:22:33.800  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:22:33.843  3955  4293 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 03:22:33.856  1742  4290 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-25 03:22:33.860  1742  1742 D SystemUpdateService: onDestroy
,08-25 03:22:33.875  3028  4287 V KeepSync: Connecting to GoogleApiClient
,08-25 03:22:33.875   873  1942 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 03:22:33.928  1522  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 03:22:33.928  1522  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-25 03:22:33.928  1522  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:22:33.928  1522  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:22:33.944  1742  4299 V BaseAuthAsyncOperation: access token request failed
,08-25 03:22:33.945  3028  4287 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 03:22:34.014  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 03:22:34.014  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 03:22:34.014  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:22:34.014  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:22:34.034  3028  4287 E KeepSync: IOException
08-25 03:22:34.034  3028  4287 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 03:22:34.034  3028  4287 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:22:34.034  3028  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 03:22:34.034  3028  4287 E KeepSync: 	... 10 more
08-25 03:22:34.034  3028  4287 W KeepSync: Sync result 2
,08-25 03:22:34.046   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 206972, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:22:34.613   873  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:22:36.000  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:22:36.007  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:22:36.008  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:36.008  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d112bb6 removed from the list
,08-25 03:22:36.008  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:22:36.009  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:36.009  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:36.026  3806  4300 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-25 03:22:36.026  3806  4300 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 03:22:38.558  1522  1522 I ConfigService: onDestroy
,08-25 03:22:39.030  3806  4300 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-25 03:22:39.030  3806  4300 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-25 03:22:39.031  3806  4300 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:22:39.031  3806  4300 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:39.031  3806  4300 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-25 03:22:39.032  3806  4302 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-25 03:22:39.032  3806  4302 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:22:39.033  3806  4305 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Receiver)
,08-25 03:22:39.033  3806  4302 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:39.033  3806  4305 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: OutgoingSocketThread/Receiver)
08-25 03:22:39.033  3806  4305 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-25 03:22:39.034  3806  4305 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-25 03:22:39.034  3806  4302 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:39.035  3806  4306 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Sender)
08-25 03:22:39.036  3806  4302 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-25 03:22:39.036  3806  4304 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: OutgoingSocketThread/Sender)
08-25 03:22:39.037  3806  4307 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Receiver)
08-25 03:22:39.037  3806  4307 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: IncomingSocketThread/Receiver)
08-25 03:22:39.037  3806  4307 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-25 03:22:39.037  3806  4307 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-25 03:22:41.545   873  1313 D ConnectivityService: handlePromptUnvalidated 102
,08-25 03:22:42.032  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 03:22:42.035  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 03:22:42.042  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2f50c5d Bundle[{}]
,08-25 03:22:42.042  3806  3856 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 03:22:42.043  3806  3856 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 03:22:42.043  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 03:22:42.044  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 03:22:42.044  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 03:22:42.045  3806  3856 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 03:22:42.049  3806  3856 I System.out: Running OutgoingSocketThread
08-25 03:22:42.053  3806  4308 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-25 03:22:42.053  3806  4308 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 03:22:45.062  3806  4309 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-25 03:22:45.062  3806  4309 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:22:45.063  3806  4309 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:45.063  3806  4308 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-25 03:22:45.063  3806  4308 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:22:45.064  3806  4309 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:45.064  3806  4308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:45.068  3806  4308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:22:45.069  3806  4309 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-25 03:22:45.071  3806  4312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Sender)
,08-25 03:22:45.072  3806  4308 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-25 03:22:45.075  3806  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
,08-25 03:22:45.077  3806  4313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
,08-25 03:22:45.080  3806  4313 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
,08-25 03:22:45.081  3806  4313 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-25 03:22:45.082  3806  4313 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-25 03:22:45.083  3806  4314 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
,08-25 03:22:45.085  3806  4314 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
,08-25 03:22:45.086  3806  4314 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-25 03:22:45.087  3806  4314 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-25 03:22:48.065  3806  3856 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-25 03:22:48.067  3806  3856 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 03:22:48.068  3806  3856 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,08-25 03:22:48.075  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 03:22:48.075  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6540b7 added. We now have 3 listener(s)
,08-25 03:22:48.077  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:22:48.077  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:22:48.077  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 03:22:48.078  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:22:48.078  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e8024 added. We now have 4 listener(s)
,08-25 03:22:48.078  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:22:48.078  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:22:48.083  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:22:48.092  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:22:48.095  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:48.095  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:22:48.096  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:22:48.096  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:22:48.096  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:22:48.096  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:22:48.096  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:48.096  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:22:48.096  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:22:48.097  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6540b7 removed from the list
,08-25 03:22:48.097  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:48.097  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e8024 removed from the list
08-25 03:22:48.101  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:48.105  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:48.106  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:22:48.106  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:48.107  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:48.107  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:48.109  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:22:48.110  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:22:48.110  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:22:48.110  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e8024 not in the list
08-25 03:22:48.110  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:48.111  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:48.113  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:22:48.113  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:22:48.113  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:48.114  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@95e8024 not in the list
08-25 03:22:48.114  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:22:48.114  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:48.114  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:48.115  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6540b7 not in the list
,08-25 03:22:48.117  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:22:48.117  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37c4d42 added. We now have 3 listener(s)
,08-25 03:22:48.123  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:22:48.123  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 03:22:48.124  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:22:48.124  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:22:48.125  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e833153 added. We now have 4 listener(s)
08-25 03:22:48.125  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:22:48.126  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:22:48.134  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:22:48.145  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:22:48.152  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:22:48.152  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:22:48.153  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 03:22:48.153  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:22:48.153  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:22:48.153  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:22:48.154  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:22:48.159  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:48.162  3806  3856 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:22:48.163  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 03:22:48.167  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:48.175  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:22:48.177  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 03:22:48.177  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:22:48.182  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 03:22:48.182  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:22:48.182  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:22:48.183  3806  3856 D BluetoothAdapter: STATE_ON
,08-25 03:22:48.187  4219  4247 D BtGatt.GattService: registerClient() - UUID=144522bb-5594-477d-935c-b4ae50cca72b
,08-25 03:22:48.189  4219  4235 D BtGatt.GattService: onClientRegistered() - UUID=144522bb-5594-477d-935c-b4ae50cca72b, clientIf=5
08-25 03:22:48.189  3806  3817 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 03:22:48.190  4219  4229 D BtGatt.GattService: start scan with filters
,08-25 03:22:48.197  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 03:22:48.197  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 03:22:48.197  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 03:22:48.197  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:22:48.197  4219  4238 D BtGatt.ScanManager: handling starting scan
08-25 03:22:48.200  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 03:22:48.201  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:22:48.201  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 03:22:48.201  4219  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ee9f21
08-25 03:22:48.202  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:22:48.210  3806  3856 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 03:22:48.210  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:22:48.210  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:22:48.210  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:48.211  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-25 03:22:48.211  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:22:48.211  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 03:22:48.211  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:22:48.212  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:22:48.212  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:22:48.213  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 03:22:48.213  4219  4235 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 03:22:48.214  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:22:48.214  3806  3856 D BluetoothAdapter: STATE_ON
08-25 03:22:48.215  4219  4229 D BtGatt.GattService: stopScan() - queue size =1
08-25 03:22:48.215  4219  4238 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 03:22:48.218  4219  4258 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 03:22:48.219  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:22:48.219  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 03:22:48.219  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 03:22:48.220  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 03:22:48.220  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 03:22:48.222  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:22:48.222  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:22:48.223  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:22:48.223  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 03:22:48.223  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:22:48.224  4219  4235 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 03:22:48.224  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:22:48.225  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:22:48.225  4219  4238 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:22:48.225  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:22:48.225  4219  4238 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 03:22:48.226  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:22:48.243  4219  4235 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 03:22:48.244  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:22:48.253  4219  4235 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 03:22:48.253  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:22:48.268  4219  4235 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 03:22:48.268  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:22:48.269  4219  4238 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:22:48.286  4219  4235 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 03:22:48.286  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:22:48.287  4219  4238 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:22:48.328  4219  4235 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-25 03:22:48.328  4219  4235 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:22:48.329  4219  4235 D BtGatt.GattService: current time is 225220634371
08-25 03:22:48.330  4219  4235 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-25 03:22:48.335  4219  4235 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-25 03:22:48.727  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:22:48.728  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:22:48.728  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:22:51.225  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:22:51.226  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:22:51.226  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:22:51.227  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:22:51.227  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:51.227  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:22:51.227  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:22:51.228  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37c4d42 removed from the list
,08-25 03:22:51.228  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:51.228  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e833153 removed from the list
08-25 03:22:51.229  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:22:51.229  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:51.231  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:51.231  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:51.234  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:22:51.235  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:22:51.235  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:51.236  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e833153 not in the list
08-25 03:22:51.236  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:51.237  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:51.240  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:22:51.240  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:22:51.240  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:51.241  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e833153 not in the list
,08-25 03:22:51.241  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:22:51.241  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:51.242  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:51.242  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37c4d42 not in the list
08-25 03:22:51.244  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:22:51.245  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@effafbc added. We now have 3 listener(s)
,08-25 03:22:51.251  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:22:51.251  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:22:51.251  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 03:22:51.252  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:22:51.252  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14b45 added. We now have 4 listener(s)
,08-25 03:22:51.252  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:22:51.254  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:22:51.260  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:22:51.271  3806  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:22:51.276  3806  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:22:51.277  3806  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:22:51.278  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-25 03:22:51.279  3806  3856 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-25 03:22:51.280  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-25 03:22:51.280  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-25 03:22:51.281  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-25 03:22:51.281  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 03:22:51.281  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:22:51.282  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:22:51.284  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 03:22:51.285  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 03:22:51.286  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-25 03:22:51.286  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 03:22:51.286  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-25 03:22:51.286  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:22:51.287  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:22:51.291  3806  3806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:22:51.291  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-25 03:22:51.293  3806  4316 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:22:51.298  3806  4316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-25 03:22:51.299  3806  3856 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:22:51.299  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 03:22:51.309  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:22:51.309  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 03:22:51.310  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:22:51.313  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-25 03:22:51.314  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:22:51.314  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-25 03:22:51.315  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-25 03:22:51.316  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-25 03:22:51.316  3806  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-25 03:22:51.317  3806  3856 D BluetoothAdapter: STATE_ON,
,08-25 03:22:51.321  4219  4230 D BtGatt.GattService: registerClient() - UUID=a19a48d1-4a84-440d-955f-4f7a44b239d7
,08-25 03:22:51.322  4219  4235 D BtGatt.GattService: onClientRegistered() - UUID=a19a48d1-4a84-440d-955f-4f7a44b239d7, clientIf=5
08-25 03:22:51.322  3806  3817 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-25 03:22:51.324  4219  4237 D BtGatt.AdvertiseManager: message : 0
,08-25 03:22:51.328  4219  4237 D BtGatt.AdvertiseManager: starting multi advertising
,08-25 03:22:51.341  4219  4235 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-25 03:22:51.354  4219  4235 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-25 03:22:51.356  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-25 03:22:51.357  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 03:22:51.360  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:22:51.363  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-25 03:22:51.363  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-25 03:22:51.364  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-25 03:22:51.364  3806  3806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-25 03:22:51.364  3806  3806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-25 03:22:51.364  3806  3806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-25 03:22:51.371  3806  3806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-25 03:22:51.371  3806  3806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-25 03:22:51.372  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 03:22:51.372  3806  3856 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:22:51.872  3806  3806 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-25 03:22:54.374  3806  3856 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:22:54.375  3806  3856 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-25 03:22:54.375  3806  3856 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:22:54.376  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-25 03:22:54.376  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 03:22:54.376  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 03:22:54.378  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-25 03:22:54.378  3806  4316 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 03:22:54.379  3806  3856 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 03:22:54.379  3806  4316 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 03:22:54.379  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:22:54.379  3806  3806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 03:22:54.380  3806  4316 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 03:22:54.380  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:22:54.380  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:22:54.380  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:22:54.381  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:22:54.383  3806  3856 D BluetoothAdapter: STATE_ON
08-25 03:22:54.383  3806  3856 D BluetoothLeScanner: could not find callback wrapper
08-25 03:22:54.383  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:22:54.384  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-25 03:22:54.386  4219  4237 D BtGatt.AdvertiseManager: message : 1
08-25 03:22:54.387  4219  4237 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-25 03:22:54.397  4219  4235 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-25 03:22:54.397  4219  4235 D BtGatt.GattService: Client app is not null!
,08-25 03:22:54.400  4219  4247 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:22:54.401  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:22:54.402  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-25 03:22:54.402  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-25 03:22:54.402  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-25 03:22:54.403  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-25 03:22:54.405  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:22:54.406  3806  3856 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:22:54.406  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 03:22:54.407  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:22:54.410  3806  3806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:22:54.410  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:22:54.410  3806  3806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 03:22:54.410  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:54.410  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:22:54.410  3806  3806 D AndroidRuntime: Shutting down VM
08-25 03:22:54.410  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:22:54.411  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@effafbc removed from the list
08-25 03:22:54.411  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
--------- beginning of crash
08-25 03:22:54.411  3806  3806 E AndroidRuntime: FATAL EXCEPTION: main
08-25 03:22:54.411  3806  3806 E AndroidRuntime: Process: com.test.thalitest, PID: 3806
08-25 03:22:54.411  3806  3806 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:22:54.411  3806  3806 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 03:22:54.411  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14b45 removed from the list
08-25 03:22:54.411  3806  3856 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:22:54.412  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:54.413  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:22:54.413  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:54.415   873  2082 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-25 03:22:54.416  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:22:54.417  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:22:54.417  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:54.417  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14b45 not in the list
08-25 03:22:54.417  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:54.418  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:22:54.423   873  2082 I ActivityManager: Killing 3737:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 03:22:54.428  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:22:54.428  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:22:54.428  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:22:54.429  3806  3856 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d14b45 not in the list
08-25 03:22:54.429  3806  3856 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:22:54.429  3806  3856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:22:54.429  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:22:54.430  3806  3856 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@effafbc not in the list
08-25 03:22:54.431  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:22:54.431  3806  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@719ee66 added. We now have 3 listener(s)
,08-25 03:22:54.440  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:22:54.441  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:22:54.441  3806  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:22:54.441  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:22:54.441  3806  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@591c5a7 added. We now have 4 listener(s)
,08-25 03:22:54.441  3806  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:22:54.449  3806  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:22:54.507  3806  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:22:54.507   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{2fc2088 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{c38547a 3806 com.test.thalitest/10000/u0 remote:c66f8a5}: process crashing
,08-25 03:22:54.507   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{8737a21 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{c38547a 3806 com.test.thalitest/10000/u0 remote:c66f8a5}: process crashing
,08-25 03:22:54.512  3806  3806 I Process : Sending signal. PID: 3806 SIG: 9
,08-25 03:22:54.620   873  2966 D GraphicsStats: Buffer count: 2
,08-25 03:22:54.621   873  1698 I WindowState: WIN DEATH: Window{1cfa43c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 03:22:54.622   873  1312 D WifiService: Client connection lost with reason: 4,
,08-25 03:22:54.647   873  2090 I ActivityManager: Process com.test.thalitest (pid 3806) has died
,08-25 03:22:54.697   873  1947 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3806 uid 10000
,08-25 03:22:54.700  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-25 03:22:59.020   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235910, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:23:07.042  3028  4318 V KeepSync: Connecting to GoogleApiClient
,08-25 03:23:07.043   873  2082 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 03:23:07.095  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:23:07.099  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:23:07.156  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 03:23:07.157  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 03:23:07.157  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:23:07.157  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:23:07.199  1742  4319 V BaseAuthAsyncOperation: access token request failed
08-25 03:23:07.201  3028  4318 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 03:23:07.309  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-25 03:23:07.309  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-25 03:23:07.309  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:23:07.310  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:23:07.359  3028  4318 E KeepSync: IOException
08-25 03:23:07.359  3028  4318 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 03:23:07.359  3028  4318 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:23:07.359  3028  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 03:23:07.359  3028  4318 E KeepSync: 	... 10 more
08-25 03:23:07.360  3028  4318 W KeepSync: Sync result 2
,08-25 03:23:07.379   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 243716, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:23:37.732  3614  4321 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:23:37.770  3614  4322 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:23:37.786  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:23:37.790  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:23:37.836  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:23:37.836  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:23:37.836  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:23:37.837  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:23:37.902  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:23:37.906  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:23:37.939  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-25 03:23:37.939  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:23:37.939  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:23:37.940  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:23:37.956  3614  4322 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:23:37.957  3614  4321 E BooksSync: Soft error
08-25 03:23:37.957  3614  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:23:37.957  3614  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 03:23:37.957  3614  4321 E BooksSync: Sync error
08-25 03:23:37.957  3614  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:23:37.957  3614  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:23:37.957  3614  4321 I BooksSync: Finished books sync
,08-25 03:23:37.974   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 252008, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:23:38.988   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=275878, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:23:54.742  1863  1892 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-25 03:23:54.743  1863  1892 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-25 03:23:54.772  1522  1522 I ConfigService: onCreate
,08-25 03:23:59.843  1522  1522 I ConfigService: onDestroy
,08-25 03:24:03.960   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=300850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:24:08.291  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:08.295  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:08.342  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:24:08.342  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:24:08.342  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:24:08.343  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:08.373  3555  4331 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:24:08.373  3555  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:24:08.373  3555  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	... 12 more
08-25 03:24:08.373  3555  4331 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at fal.a(PG:38)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:24:08.373  3555  4331 E HttpOperation: 	... 14 more
,08-25 03:24:08.473  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:24:08.473  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:24:08.473  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:24:08.473  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:08.500  3555  4331 E HttpOperation: [getmobileexperiments] Unexpected exception
,08-25 03:24:08.500  3555  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at hec.a(PG:42)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at hee.a(PG:102)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at czr.a(PG:65)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at kka.a(PG:108)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at czq.run(PG:1686),
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:24:08.500  3555  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	... 15 more
08-25 03:24:08.500  3555  4331 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at fal.a(PG:38)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:24:08.500  3555  4331 E HttpOperation: 	... 17 more
08-25 03:24:08.500  3555  4331 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:24:08.500  3555  4331 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at hee.a(PG:102)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	... 15 more
08-25 03:24:08.500  3555  4331 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:24:08.500  3555  4331 E ExperimentLoader: 	... 17 more
,08-25 03:24:08.640   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 287217, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:24:27.600   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:24:38.747  3614  4335 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:24:38.799  3614  4337 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:24:38.811  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:38.815  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:38.875  3028  4336 V KeepSync: Connecting to GoogleApiClient
,08-25 03:24:38.877  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:24:38.877  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:24:38.877  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:24:38.877  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:38.877   873  1698 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 03:24:38.948  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:38.959  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:39.025  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:24:39.025  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:24:39.025  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-25 03:24:39.025  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:39.037  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 03:24:39.037  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 03:24:39.037  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:24:39.037  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:39.056  3614  4337 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-25 03:24:39.060  3614  4335 E BooksSync: Soft error
08-25 03:24:39.060  3614  4335 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:24:39.060  3614  4335 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 03:24:39.066  3614  4335 E BooksSync: Sync error
08-25 03:24:39.066  3614  4335 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:24:39.066  3614  4335 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:24:39.067  3614  4335 I BooksSync: Finished books sync
,08-25 03:24:39.069  1742  4338 V BaseAuthAsyncOperation: access token request failed
08-25 03:24:39.070  3028  4336 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 03:24:39.087   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305743, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:24:39.146  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 03:24:39.146  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 03:24:39.146  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:24:39.146  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:39.165  3028  4336 E KeepSync: IOException
08-25 03:24:39.165  3028  4336 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 03:24:39.165  3028  4336 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:24:39.165  3028  4336 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 03:24:39.165  3028  4336 E KeepSync: 	... 10 more
,08-25 03:24:39.165  3028  4336 W KeepSync: Sync result 2
,08-25 03:24:39.181   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 309829, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:24:45.111  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:45.121  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:45.126  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:24:45.171  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-25 03:24:45.172  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-25 03:24:45.172  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:24:45.172  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:24:45.210  1522  2318 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:24:45.210  1522  2318 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:24:45.210  1522  2318 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:24:45.210  1522  2318 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-25 03:24:45.210  1522  2318 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-25 03:24:45.210  1522  2318 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-25 03:24:45.210  1522  2318 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-25 03:24:45.225  3518  3547 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:24:45.225  3518  3547 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-25 03:24:45.225  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-25 03:24:45.225  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-25 03:24:45.225  3518  3547 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-25 03:24:45.225  3518  3547 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-25 03:24:45.225  3518  3547 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-25 03:25:09.515  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:25:09.516  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:25:09.543  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:25:09.543  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 03:25:09.543  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:25:09.543  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:25:09.565  3555  4345 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:25:09.565  3555  4345 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:25:09.565  3555  4345 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	... 12 more
08-25 03:25:09.565  3555  4345 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at fal.a(PG:38)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:25:09.565  3555  4345 E HttpOperation: 	... 14 more
,08-25 03:25:09.645  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:25:09.645  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 03:25:09.646  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:25:09.646  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:25:09.663  3555  4345 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 03:25:09.663  3555  4345 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at hec.a(PG:42)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at hee.a(PG:102)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at czr.a(PG:65)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at kka.a(PG:108)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:25:09.663  3555  4345 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	... 15 more
08-25 03:25:09.663  3555  4345 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at fal.a(PG:38)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:25:09.663  3555  4345 E HttpOperation: 	... 17 more
,08-25 03:25:09.663  3555  4345 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:25:09.663  3555  4345 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at hee.a(PG:102)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at czp.a(PG:19176),
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	... 15 more
08-25 03:25:09.663  3555  4345 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:25:09.663  3555  4345 E ExperimentLoader: 	... 17 more
,08-25 03:25:09.828   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 337363, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:25:10.521   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=367412, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:25:41.064  3614  4348 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:25:41.081  3614  4349 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:25:41.100  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:25:41.102  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:25:41.130  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:25:41.130  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:25:41.130  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:25:41.130  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:25:41.156  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:25:41.158  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:25:41.178  1522  3183 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:25:41.178  1522  3183 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:25:41.178  1522  3183 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:25:41.179  1522  3183 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:25:41.197  3614  4349 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-25 03:25:41.197  3614  4348 E BooksSync: Soft error
08-25 03:25:41.197  3614  4348 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:25:41.197  3614  4348 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 03:25:41.197  3614  4348 E BooksSync: Sync error
08-25 03:25:41.197  3614  4348 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:25:41.197  3614  4348 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:25:41.198  3614  4348 I BooksSync: Finished books sync
,08-25 03:25:41.209   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 397732, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:25:52.893   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:26:17.828   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=434719, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:26:41.543  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:26:41.548  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:26:41.593  1522  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:26:41.593  1522  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 03:26:41.593  1522  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:26:41.593  1522  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:26:41.633  3555  4357 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:26:41.633  3555  4357 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:26:41.633  3555  4357 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	... 12 more
,08-25 03:26:41.633  3555  4357 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at fal.a(PG:38)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:26:41.633  3555  4357 E HttpOperation: 	... 14 more
,08-25 03:26:41.699  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:26:41.699  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:26:41.699  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:26:41.699  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:26:41.711  3555  4357 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 03:26:41.711  3555  4357 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at hec.a(PG:42)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at hee.a(PG:102)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at czr.a(PG:65)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at kka.a(PG:108)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:26:41.711  3555  4357 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	... 15 more
08-25 03:26:41.711  3555  4357 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at fal.a(PG:38)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:26:41.711  3555  4357 E HttpOperation: 	... 17 more
,08-25 03:26:41.711  3555  4357 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:26:41.711  3555  4357 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at hee.a(PG:102)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	... 15 more
08-25 03:26:41.711  3555  4357 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:26:41.711  3555  4357 E ExperimentLoader: 	... 17 more
,08-25 03:26:41.807   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 430382, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:27:11.955  3028  4361 V KeepSync: Connecting to GoogleApiClient
08-25 03:27:11.956   873  2966 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 03:27:12.015  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:27:12.020  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:27:12.070  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 03:27:12.070  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 03:27:12.071  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:27:12.071  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:27:12.101  1742  4362 V BaseAuthAsyncOperation: access token request failed
,08-25 03:27:12.102  3028  4361 V KeepSync: GoogleApiClient failed to connect with error code: 4,
,08-25 03:27:12.176  1522  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 03:27:12.177  1522  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 03:27:12.177  1522  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:27:12.177  1522  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:27:12.207  3028  4361 E KeepSync: IOException
08-25 03:27:12.207  3028  4361 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 03:27:12.207  3028  4361 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:27:12.207  3028  4361 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 03:27:12.207  3028  4361 E KeepSync: 	... 10 more
,08-25 03:27:12.208  3028  4361 W KeepSync: Sync result 2
,08-25 03:27:12.221   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 467188, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:27:38.682   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=515572, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:27:44.801  3614  4364 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:27:44.835  3614  4365 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:27:44.849  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:27:44.853  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:27:44.892  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:27:44.892  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:27:44.892  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:27:44.892  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:27:44.938  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:27:44.943  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:27:44.984  1522  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-25 03:27:44.984  1522  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:27:44.984  1522  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:27:44.985  1522  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:27:45.011  3614  4365 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-25 03:27:45.012  3614  4364 E BooksSync: Soft error
08-25 03:27:45.012  3614  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:27:45.012  3614  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:27:45.013  3614  4364 E BooksSync: Sync error
08-25 03:27:45.013  3614  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:27:45.013  3614  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:27:45.013  3614  4364 I BooksSync: Finished books sync
,08-25 03:27:45.025   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 521609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:28:03.640   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=540530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:28:33.403   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=570293, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:28:49.408  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:28:49.412  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:28:49.468  1522  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-25 03:28:49.469  1522  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 03:28:49.469  1522  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:28:49.469  1522  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:28:49.493  3555  4370 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:28:49.493  3555  4370 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:28:49.493  3555  4370 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	... 12 more
08-25 03:28:49.493  3555  4370 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at fal.a(PG:38)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:28:49.493  3555  4370 E HttpOperation: 	... 14 more
,08-25 03:28:49.579  1522  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:28:49.579  1522  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:28:49.579  1522  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:28:49.579  1522  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:28:49.603  3555  4370 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 03:28:49.603  3555  4370 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at hec.a(PG:42)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at hee.a(PG:102)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at czr.a(PG:65)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at kka.a(PG:108)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:28:49.603  3555  4370 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	... 15 more
08-25 03:28:49.603  3555  4370 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at fal.a(PG:38)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:28:49.603  3555  4370 E HttpOperation: 	... 17 more
,08-25 03:28:49.603  3555  4370 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:28:49.603  3555  4370 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at hee.a(PG:102),
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	... 15 more
08-25 03:28:49.603  3555  4370 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:28:49.603  3555  4370 E ExperimentLoader: 	... 17 more
,08-25 03:28:49.740   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 586022, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:28:58.361   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=595252, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:29:50.602   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647492, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-25 03:30:15.588   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=672478, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:37:34.095  1742  4398 I EventLogService: Opted in for usage reporting
,08-25 03:37:34.096  1742  4398 I EventLogService: Aggregate from 1472086800684 (log), 1472086800684 (data)
,08-25 03:37:34.163  1742  4398 W EventLogAggregator: Unknown tag: snet_gcore
08-25 03:37:34.163  1742  4398 W EventLogAggregator: Unknown tag: snet_launch_service
,08-25 03:37:34.294  1742  4398 I ServiceDumpSys: dumping service [account]
,08-25 03:37:39.055   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1115946, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 03:37:46.866   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1123757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:39:21.516   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-25 03:44:34.251  4421  4421 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 03:44:34.255  4421  4421 D AndroidRuntime: CheckJNI is OFF
08-25 03:44:34.291  4421  4421 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 03:44:34.330  4421  4421 I Radio-JNI: register_android_hardware_Radio DONE
08-25 03:44:34.351  4421  4421 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-25 03:44:34.363   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-25 03:44:34.471   873   896 W PackageSettings: Skipping PackageSetting{e99424a com.example.hello/10273} due to missing metadata
08-25 03:44:34.504   873   896 I art     : Starting a blocking GC Explicit
08-25 03:44:34.554   873   896 I art     : Explicit concurrent mark sweep GC freed 47185(2MB) AllocSpace objects, 11(220KB) LOS objects, 33% free, 29MB/43MB, paused 652us total 49.239ms
08-25 03:44:34.585   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-25 03:44:34.587  4421  4421 I art     : System.exit called, status: 0
08-25 03:44:34.587  4421  4421 I AndroidRuntime: VM exiting with result code 0.
08-25 03:44:34.592   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-25 03:44:34.605  4219  4219 D BluetoothMapAppObserver: onReceive
08-25 03:44:34.605  4219  4219 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-25 03:44:34.606  2114  2283 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 03:44:34.607  3675  3675 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-25 03:44:34.616   873  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 03:44:34.623  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
08-25 03:44:34.661  1863  4436 I Keyboard.Facilitator.DecoderInitializer: run()
08-25 03:44:34.669  1931  1931 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-25 03:44:34.674   873  1947 I ActivityManager: Start proc 4438:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-25 03:44:34.686  1863  4436 I Decoder : createOrResetDecoder
08-25 03:44:34.695   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 03:44:34.716  1522  1522 I ConfigService: onCreate
08-25 03:44:34.721  4438  4438 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 03:44:34.725  1522  4450 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 03:44:34.725  1522  4450 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:44:34.727  1522  4450 W SQLiteOpenHelper: Opened config.db in read-only mode
08-25 03:44:34.739  1948  2019 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-25 03:44:34.739   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-25 03:44:34.740   873   885 E PackageManager: Failed to write settings, restoring backup
08-25 03:44:34.740   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 03:44:34.740   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 03:44:34.740   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 03:44:34.740   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 03:44:34.740   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 03:44:34.740   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:34.740   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:34.740   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:34.748  1863  4436 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-25 03:44:34.748   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-25 03:44:34.748   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 03:44:34.748   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:44:34.748   873   886 E DropBoxManagerService: 	... 13 more
08-25 03:44:34.753   873  2082 I ActivityManager: Start proc 4451:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-25 03:44:34.755  1948  2019 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 03:44:34.755  1948  2019 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1948
08-25 03:44:34.755  1948  2019 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:34.755  1948  2019 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:34.757   873  1698 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 03:44:34.758   873  4456 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:44:34.758   873  4456 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:44:34.758   873  4456 E DropBoxManagerService: 	... 5 more
08-25 03:44:34.765  1948  2019 I Process : Sending signal. PID: 1948 SIG: 9
08-25 03:44:34.880  1863  4436 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-25 03:44:34.882  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 03:44:34.882  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-25 03:44:34.884  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-25 03:44:34.884  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-25 03:44:34.896  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-25 03:44:34.896  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-25 03:44:34.896  1863  4436 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-25 03:44:34.896  1863  4436 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 03:44:34.897  1863  4436 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 03:44:34.897  1863  4436 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-25 03:44:34.897  1863  4436 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 03:44:34.897  1863  4436 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-25 03:44:34.914   873  2090 D GraphicsStats: Buffer count: 1
08-25 03:44:34.914   873  2082 I WindowState: WIN DEATH: Window{3ade501 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-25 03:44:34.945   873  2966 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1948) has died
08-25 03:44:34.945   873  2966 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-25 03:44:34.947   873  2966 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:34.953  4438  4469 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:34.954  4438  4469 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:34.963  4438  4438 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-25 03:44:34.972   873   886 I ActivityManager: Start proc 4472:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 03:44:34.985  4438  4478 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-25 03:44:34.990   873   883 I ActivityManager: Start proc 4481:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-25 03:44:35.001  1742  4471 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-25 03:44:35.003  1742  4471 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-25 03:44:35.020  4481  4481 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-25 03:44:35.040  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-25 03:44:35.042  1522  1522 D AndroidRuntime: Shutting down VM
08-25 03:44:35.043  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
08-25 03:44:35.043  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
08-25 03:44:35.043  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 03:44:35.043  1522  1522 E AndroidRuntime: 	... 8 more
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:44:35.044  4472  4472 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:44:35.044  4472  4472 D AndroidRuntime: Shutting down VM
08-25 03:44:35.049   873  4499 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:44:35.049   873  4499 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:44:35.049   873  4499 E DropBoxManagerService: 	... 5 more
08-25 03:44:35.050  1522  1522 I Process : Sending signal. PID: 1522 SIG: 9
08-25 03:44:35.053  4472  4472 E AndroidRuntime: FATAL EXCEPTION: main
08-25 03:44:35.053  4472  4472 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4472
08-25 03:44:35.053  4472  4472 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 03:44:35.053  4472  4472 E AndroidRuntime: 	... 10 more
08-25 03:44:35.054   873  1942 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 03:44:35.055  4472  4472 I Process : Sending signal. PID: 4472 SIG: 9
08-25 03:44:35.055   873  4501 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:44:35.055   873  4501 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:44:35.055   873  4501 E DropBoxManagerService: 	... 5 more
08-25 03:44:35.067  1742  4471 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-25 03:44:35.067  1742  4471 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-25 03:44:35.081  4438  4469 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:35.086  4438  4478 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 03:44:35.087  4438  4478 E AndroidRuntime: Process: android.process.acore, PID: 4438
08-25 03:44:35.087  4438  4478 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:44:35.087  4438  4478 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:44:35.088  4438  4469 I Process : Sending signal. PID: 4438 SIG: 9
08-25 03:44:35.090   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
